FROM jupyter/all-spark-notebook
USER root
RUN apt-get update
RUN apt-get install -y libreadline-dev
RUN pip install --upgrade pip

ADD requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt


