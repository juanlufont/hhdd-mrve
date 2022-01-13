# Métodos Representación Visualización Espacial HHDD

## Trabajo de evaluación curso 2021-22

Mercancía: **ámbar**[^1][^2]
* Barnsteen (danés)
* Bernstein (neerlandés)

Periodo de tiempo: 1634-1857

## Contenido del repositorio

* `notebook.ipynb`: código para procesar datos en formato [Jupyter notebook](https://jupyter.org)
* `coordinates.json`: caché de coordenadas longitud-latitud para los puertos contemplados en el estudio
* `data/`: directorio con los archivos CSV originales con información sobre _cargoes_ y _assages_ relacionados con ámbar
* `amber.csv` archivo con los datos resultantes del procesado de los CSV de entrada
* `amber_port_destination.csv` archivo con el resumen de Kg de ámbar por puerto de destino
* `amber_port_origin.csv` archivo con el resumen de Kg de ámbar por puerto de llegada

## Dependencias software

El código contenido en `notebook.ipynb` require de un entorno Python (>= 3.6) con las siguientes librerías:

* `geopy`
* `notebook`
* `pandas`

## Referencias

[^1]: [Referencia de mercancías](http://www.soundtoll.nl/images/files/List%20of%20products.pdf) para Soundtoll Database
[^2]: [Unidad de medida](https://www.sizes.com/units/pund.htm)
