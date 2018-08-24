# Acamica_Proyecto 1
Proyecto: Análisis mercado inmobiliario de la Ciudad de Buenos Aires
¡Bienvenidos al primer proyecto de la carrera de Data Science de Acamica!

En este proyecto vamos a trabajar con un dataset de propiedades en venta publicadas en el portal Properati. El objetivo es dar los primeros pasos en el proceso de exploración de datos usando las herramientas que trabajamos en las activades.

Vamos a enfocarnos en analizar algunos aspectos del mercado inmobiliario de la Ciudad de Buenos Aires pero para eso primero debemos limpiar un poco el dataset.

El dataset: propiedades en venta en Ciudad de Buenos Aires.
En este proyecto, trabajaremos con una muestra del conjunto de datos de propiedades en venta mencionado. En este dataset, cada fila es una propiedad en venta.

Los atributos
A continuación vamos a describir los atributos que consideramos en esta muestra:

id: id de la propiedad
created_on: fecha en la que la propiedad ingresó al sitio
operation: alquiler (rent) o venta (sell)
property_type: tipo de propiedad (casa, departamento, ph, etcétera)
place_with_parent_names: nombre del lugar donde se encuentra la propiedad según el publicador
lat-lon: coordenadas concatenadas
lat: latitud
lon: longitud
price: precio en la moneda especificada en currency
currency: divisa en la que está expresada la publicación
price_aprox_usd: precio aproximado en dólares estadounidenses
surface_total_in_m2: superficie total (en metros cuadrados)
surface_covered_in_m2: superficie cubierta (en metros cuadrados)
price_usd_per_m2: precio por metro cuadrado en dólares (precio dólares / superficie)
floor: número de piso (si corresponde)
rooms: cantidad de ambientes
expenses: expensas (si corresponde)
barrio: barrio según cartografía oficial
properati_url: url de la publicación en Properati
Importando las bibliotecas necesarias
Para poder trabajar en la limpieza de datos y la visualización de nuestro dataset vamos a utilizar las bibliotecas numpy, pandas, matplotlib.pylab y seaborn.
