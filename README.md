# Scrape-hoteles.com
## Descripción
Este repositorio se ha creado para la asignatura Tipología y ciclo de vida de los datos, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. Este repositorio contiene principalmente un script en Python para hacer scrape de la página web www.hoteles.com. Este script ha sido utilizado para crear un dataset sobre habitaciones de hoteles en las 10 mejores ciudades del mundo.
## Miembros del equipo
Esta práctica ha sido realizada por Truman Tapia y Julio Zamora Guerrero.
## Ficheros
- **PRA1_ttapiam_jzamgu2.pdf**: pdf con las respuestas de la práctica.
- **src/hotelesComScraper.py**: script para hacer scrape a hoteles.com.
## Detalles del código
El script de este repositorio utiliza las siguientes bibliotecas:
BeautifulSoup, requests, pandas, y wolframclient.

El script se debe ejecutar de la siguiente manera para obtener el dataset generado:
```
python hotelesComScraper.py --startDate 01/12/2021 --endDate 01/03/2022
```

El script hace uso de tecnología Wolfram a través de su librería para Python wolframclient (https://reference.wolfram.com/language/WolframClientForPython/). Para usar esta librería se requiere tener instalado previamente un Kernel de Wolfram, el cual se puede encontrar en https://www.wolfram.com/engine/. Específicamente, en el código se hace uso de la función WebExecute de Wolfram para manejar programáticamente un navegador web Firefox, y así obtener el contenido dinámico de hoteles.com. En esta práctica se ha optado por el uso de Wolfram en lugar de librerías más convencionales como Selenium para manejar navegadores.
## Dataset
El dataset generado se encuentra en el siguiente link:
https://zenodo.org/record/5650235#.YYfxLLq21PY
## Video
https://drive.google.com/uc?id=1hQKR6reD3Hm6GcmXyCC2RPDRVeugtA-x&export=download
