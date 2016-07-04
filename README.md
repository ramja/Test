# Test
Este es una prueba de análisis de modelos a partir de un dataset


###Estructura del proyecto

* data
* images
* src

El contenido de este projecto se resume en los siguientes archivos:

src/análisis.Rmd    (R Markdown)
src/Boost.ipynb     (Jupyter Notebook)

Para ejecutar el segundo se puede ejecutar el siguiente comando desde la carpeta images:

docker build  -t miroculus_project --rm=true .

docker run -d --name miroculus -v [carpeta del proyecto]:/home/jovyan/work -p 8888:8888 miroculus_project

###Resultados
El archivo de resultados se encuentra en la carpeta data: "Miroculus.test.csv""
