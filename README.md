# Práctica 3 (Exploración y Visualización de datos)

## Definición de objetivos deseados


El objetivo que se pretende conseguir con esta práctica, es realizar un estudio de la cantidad de viviendas que Airbnb tiene en Madrid, pero lo que realmente se desea es saber el pporcentaje de viviendas utilizadas por Airbnb respecto al total de viviendas que hay Madrid. Pero el estudio esta centrado a nivel de barrios de Madrid, así se podrá saber que barrio tiene mas viviendas tanto a nivel absoluto y relativo al número de viviendas que existen en ese barrio.

## Selección de KPIs

Para poder crear los KPIs deseados, el primer paso que se ha dado era encontar las fuentes de datos para poder realizar los indicadores deseados. Para ello necesitabamos los datos del catastro por barrios en el que entre los datos relevantes que se necesitaban era saber cuantas viviendas de uso residencial tiene Madrid. [Datos catastrales de Madrid por barrios](fuentes/datos_catastrales.xls)

A parte para el mejor análisis de la información tambien se ha cargado un __fichero espacial__ de tipo (_.shp_), en el cual estan cargados todos los [barrios de Madrid](fuentes/shp_barrios/).

EL KPI a estudiar es el siguiente: 

![KPI](/imagenes/formula_kpi.jpg "KPI")

## Realización de la práctica

Para la realización d ela prática se han utilizado tres fuents de datos, la tabla airbnb que la tenemos en una instancia de MySql en **Google Cloud SQL**, otra fuente es un **fichero Excel** donde obtenemos los datos catastrales de los barrios de Madrid y la última fuente es un **fichero espacial** para poder pintar los barrios de Madrid.

A continuación se presenta las relaciones realizadas entre las diferentes fuentes:

![Fuentes](/imagenes/cloudSql.jpg "Fuentes")





