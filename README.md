RESULTADOS
==========

Autocorrelación de % de carga (calculada a nivel circuito)
----------------------------------------------------------

-   El input debería ser un dataframe con

    -   timestamp
    -   correlacion

<!-- -->

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Correlación votos en PASO y % de voto (por partido) `porcentaje_de_carga`
-------------------------------------------------------------------------

-   El input debería ser un dataframe con

    -   timestap
    -   partido\_politico
    -   correlacion

Comparación entre carga PASO simulada con mesas en ACTUAL
---------------------------------------------------------

-   El input debería ser un dataframe con

    -   timestamp
    -   partido\_politico
    -   sesgo

Gráfico: Evolución de votos (por partido)
-----------------------------------------

-   OPCION 1: El input puede ser un jpg
-   OPCION 2: El input debería ser un dataframe con
-   timestamp
-   partido\_politico
-   voto(suma)

![](README_files/figure-markdown_strict/pressure-1.png)

Gráfico: Porcentaje de carga por departamento (datos GIS)
---------------------------------------------------------

-   NO SE QUE HABRIA QUE PONER ACA

Analizar timestams ???
----------------------

Predicción FINAL
----------------

-   El input debería ser un dataframe con

    -   timestamp
    -   partido\_politico
    -   prediccion
