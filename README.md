Este es un tutorial sobre como hacer un mapa del calor del Perú.

Primero comenzamos buscando el archivo de los límites departamentales del Perú en formato Shapefile (.shp), este archivo se puede encontrar y descargar en la Plataforma de información territorial de la Secretaría de Demarcación y Organización Territorial del Perú: https://geosdot.servicios.gob.pe/visor/

1) Iniciamos cargando las librerías que necesitaremos

```{r}
library(plotly)
library(sf)        # manejar shapefiles
library(ggplot2)   # graficar
library(dplyr)     # manipulación de datos
library(tidyverse)
```
Hay muchas formas de crear un mapa del calor
