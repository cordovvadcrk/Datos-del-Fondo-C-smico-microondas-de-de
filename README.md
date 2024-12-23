# Descripción
El presente codigo tiene como objetivo utilizar datos de la mision "WMAP" de la NASA para poder estudiar el CMB(fondo de radiación de microondas), para esto se utilizarán API´S de astrofisica junto la utilizacion de bases de datos NoSQL.

## Dependencias para su funcionamiento:

* Numpy
* Matpllotlib
* AstroPy
* Scipy
* Pymongo

## Como utilizar el código
Para poder utilizar el codigo antes que nada es necesario inicializar una instancia de mongodb en el sistema local (sea via mongoatlas o creando un servidor local), tras esto tener el archivo llamado "wmap_mollweide_band_imap_r9_9yr_K_v5.fits" descargado en el sistema, en caso de querer utilizar otro archivo de la misma base de datos simplemente reemplace el nombre del archivo antes mencionado por el que desea utilizar en la variable "fits_file" del codigo.

## Diagrama de flujo
