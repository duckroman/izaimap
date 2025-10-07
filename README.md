# Visualizador de Casos COVID-19 en Zacatecas

Este proyecto presenta un mapa interactivo que visualiza los casos positivos de COVID-19 en los municipios del estado de Zacatecas, México.

## Descripción

El objetivo de este visualizador es ofrecer una representación geográfica clara de la distribución de casos de COVID-19 en la región. Utiliza datos geoespaciales para dibujar los límites municipales y superpone información estadística para mostrar el impacto de la pandemia en cada área.

## Cómo Utilizar

Para ver el mapa interactivo, sigue estos pasos:

1.  Clona o descarga este repositorio en tu máquina local.
2.  Navega a la carpeta `covid/`.
3.  Abre el archivo `mapaizai_covid.html` en cualquier navegador web moderno (como Chrome, Firefox o Safari).

No se requiere instalación de software adicional ni dependencias.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

-   `mapaizai_covid.html`: El archivo principal que contiene la estructura del mapa y la lógica de visualización.
-   `css/`: Contiene las hojas de estilo para dar formato y apariencia al mapa.
    -   `style.css`
    -   `style1.css`
-   `datasets/`: Almacena los conjuntos de datos utilizados.
    -   `positivos_covid_zac.xlsx`: Base de datos con el número de casos positivos por municipio.
-   `geo/`: Contiene los datos geoespaciales.
    -   `zacmun/municipalities.geojson`: Archivo GeoJSON con las coordenadas de los polígonos de los municipios de Zacatecas.
-   `img/icons/`: Contiene los íconos utilizados en el mapa para representar diferentes métricas (casos, recuperaciones, fallecimientos).
    -   `Coconut.png`
    -   `recu.png`
    -   `rip.png`

## Fuentes de Datos

-   **Datos de Casos Positivos:** Los datos sobre los casos de COVID-19 se obtuvieron de fuentes oficiales y se encuentran en el archivo `positivos_covid_zac.xlsx`.
-   **Datos Geoespaciales:** Los límites municipales se obtuvieron del archivo `municipalities.geojson`.
