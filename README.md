
## Ayuda para solicitudes de fusión en GitHub

[*Helpers for GitHub pull requests
(PR)*](https://usethis.r-lib.org/reference/pr_init.html)

–

[Mauro Lepore](https://twitter.com/mauro_lepore)

–

  - Todo disponible en <http://bit.ly/ayuda-pr>.
  - [Video de practica](https://youtu.be/O_9jdlgv2CM).
  - Presentacion en [.html](https://bookdown.org/maurolepore/ayuda-pr/)
    y
    [.pdf](https://github.com/an-org/datos-de-miercoles/blob/master/ayuda-pr.pdf).

# [Licencia](https://github.com/an-org/datos-de-miercoles/blob/master/LICENCE)

> Copyright 2019 R4DS-en Español (cienciadedatos) Comunidad online

> Se concede permiso … a utilizar el Software sin restricción, …sujeto a
> las siguientes condiciones:

> Este aviso se incluirán en todas las copias …

> EL SOFTWARE SE PROPORCIONA “COMO ESTÁ”, SIN GARANTÍA DE NINGÚN TIPO …

## Contribuyendo a [Datos de miercoles](https://github.com/cienciadedatos/datos-de-miercoles/pull/58)

Inspirado en los datos de [Bicicletas de Buenos Aires
(\#58)](https://github.com/cienciadedatos/datos-de-miercoles/pull/58),
contribuidos por [@eliocamp](https://github.com/eliocamp), y
administrados por [@rivaquiroga](https://github.com/rivaquiroga).

–

<img src="https://i.imgur.com/74axHZu.png" align="center" width=760/>

## Acerca de este repositorio

**<http://bit.ly/ayuda-pr>**

Este repositorio fue clonado de [Datos de
miercoles](https://github.com/cienciadedatos/datos-de-miercoles) y
simplificado para enfocarlo a datos específicos:

  - El directorio `.git/` original fue reemplazado por uno nuevo.
  - Los directorios `meta/` y `recursos/` fueron eliminados.
  - Los subdirectorios de `datos/2019/` fueron eliminados, excepto
    `datos/2019/2019-08-28/`.
  - El archivo `datos/2019/2019-08-28/bicicletas.csv` fue reducido a sus
    primeras 500 filas.

# Demostración

## Contribuidor

Bifurca el repositorio fuente, y chequea una copia local (a mano)

<img src="https://i.imgur.com/6BuhWV6.png" align="center" width=760/>

## Contribuidor

Bifurca el repositorio fuente, y chequea una copia local (a mano)

<img src="https://i.imgur.com/YDkkx6q.png" align="center" width=760/>

## Contribuidor

Bifurca el repositorio fuente, y chequea una copia local (a mano)

<img src="https://i.imgur.com/cgVQAyZ.png" align="center" width=760/>

## Contribuidor

Bifurca el repositorio fuente, y chequea una copia local (usethis)

    library(usethis)
    create_from_github(owner/repo)

## Contribuidor

Usando el paquete usethis, crea una rama para la PR

    library(usethis)
    
    # El numero de issue es opciopnal pero útil
    pr_init("<numero de issue>_bicicletas-en-ba")

–

<img src="https://i.imgur.com/8wjSn4d.png" align="center" width=760/>

## Contribuidor

Agrega y describe datos de bicicletas y estaciones

<img src="https://i.imgur.com/Kzcfgks.png" align="center" width=760/>

## Contribuidor

Empuja la PR a GitHub, y abre una pagina web para iniciar la PR

    pr_push()

<img src="https://i.imgur.com/cInDkah.png" align="center" width=760/>

–

<img src="https://i.imgur.com/7pdh9ri.png" align="center" width=760/>

## Administradora

Usando el paquete usethis, descarga la PR

    library(usethis)
    pr_fetch(<numero de pull request>)

<img src="https://i.imgur.com/uE7ZvHm.png" align="center" width=760/>

## Administradora

Edita la PR

<img src="https://i.imgur.com/UgIFeK2.png" align="center" width=760/>

## Administradora

Empuja la PR de regreso a GitHub

    pr_push() 

<img src="https://i.imgur.com/7ihDHpX.png" align="center" width=760/>

## Administradora

Funde la PR, y elimina la rama local

    pr_finish() 

<img src="https://i.imgur.com/tHCOaNz.png" align="center" width=760/>

## Contribuidor

Elimina la rama de la PR

    pr_finish() 

## [Casos mas complejos](https://usethis.r-lib.org/reference/pr_init.html)

Hay casos mas [casos mas
complejos](https://usethis.r-lib.org/reference/pr_init.html), pero están
fuera del alcance de esta demostración.

## Gracias

–

### <https://twitter.com/mauro_lepore>

# 

Fin
