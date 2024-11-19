# Análisis de Meteoritos

Este proyecto es un análisis de datos sobre meteoritos utilizando herramientas de R. El objetivo principal es explorar la distribución geográfica y las características de los meteoritos caídos en diferentes regiones del mundo, así como su relación con las clases de meteoritos presentes en cada zona.



## Descripción del Proyecto

Este análisis se centra en un conjunto de datos públicos de meteoritos, proporcionando una visión detallada de la distribución de estos fenómenos naturales en función de su ubicación geográfica y masa. El análisis incluye visualizaciones como mapas de calor de meteoritos por región, distribución de meteoritos por latitud, y análisis de clases de meteoritos más comunes en diferentes zonas del planeta.



## Funcionalidades

**Carga y Limpieza de Datos:** Se descargan y limpian los datos de meteoritos para su análisis.

**Visualizaciones Interactivas:** Se generan gráficos que muestran la distribución geográfica de meteoritos, incluyendo mapas de calor y densidad.

**Análisis Regional:** Se calcula la masa total y promedio de meteoritos por región y se analizan las clases de meteoritos más comunes.

**Tablas Resumen:** Se generan tablas mejoradas que muestran estadísticas de meteoritos agrupados por regiones geográficas y clases de meteoritos.


## Requisitos

Para ejecutar este análisis, asegúrate de tener instalados los siguientes paquetes de R:

`ggplot2`

`dplyr`

`readr`

`maps`

Si no tenes ninguno de estos paquetes instalados, el código incluye una función que los instala automáticamente si es necesario.


## Instalación y Ejecución

1. Instalar los paquetes necesarios:
   
   El archivo RMD incluye un bloque de código que instala automáticamente los paquetes necesarios. Solo es necesario ejecutarlo al principio del análisis.
   
2. Ejecutar el Análisis:

   Abre el archivo `.Rmd` en RStudio y ejecuta el análisis. Esto generará un informe en formato HTML, PDF o Word con los resultados y visualizaciones.

## Análisis y Visualizaciones

***Distribución Global de Meteoritos***
   
Se genera un mapa global que muestra la concentración de meteoritos en diferentes partes del mundo, utilizando líneas de contorno para representar la densidad de impactos. Además, se destacan las regiones con mayores concentraciones.



***Distribución por Latitud***

Se genera una visualización de la densidad de meteoritos por latitud, destacando las zonas donde hay más caídas de meteoritos.



***Análisis de Regiones***

El análisis de las regiones examina las áreas del planeta con mayor número de meteoritos, y se comparan las masas totales y promedio por región. Además, se visualiza la masa total de meteoritos por región.



***Análisis de Clases de Meteoritos***

Se analiza la distribución de las 10 clases más comunes de meteoritos en diferentes regiones geográficas, destacando las proporciones y tendencias de cada clase en función de la ubicación.

   
