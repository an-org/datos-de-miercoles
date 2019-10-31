## Ayudantes para solicitudes de fusión en GitHub  

[_Helpers for GitHub pull requests (PR)_](https://usethis.r-lib.org/reference/pr_init.html)  

--

[Mauro Lepore](https://twitter.com/mauro_lepore)

--

### Repositorio: **<http://bit.ly/ayuda-pr>**



# [Licencia](https://github.com/an-org/datos-de-miercoles/blob/master/LICENCE)

> Copyright 2019  R4DS-en Español (cienciadedatos) Comunidad online 

> Se concede permiso ... a utilizar el Software sin restricción, ...sujeto a las siguientes condiciones:

> Este aviso se incluirán en todas las copias ...

> EL SOFTWARE SE PROPORCIONA "COMO ESTÁ", SIN GARANTÍA DE NINGÚN TIPO ...



## Contribuyendo a [Datos de miercoles](https://github.com/cienciadedatos/datos-de-miercoles/pull/58)

Inspirado en los datos de [Bicicletas de Buenos Aires (#58)](https://github.com/cienciadedatos/datos-de-miercoles/pull/58), contribuidos por [\@eliocamp](https://github.com/eliocamp), y administrados por [\@rivaquiroga](https://github.com/rivaquiroga).

--

<img src="https://i.imgur.com/74axHZu.png" align="center" width=760/>



## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Bifurca el repositorio fuente, y chequea una copia local, a mano

<img src="https://i.imgur.com/6BuhWV6.png" align="center" width=760/>

## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Bifurca el repositorio fuente, y chequea una copia local, a mano

<img src="https://i.imgur.com/YDkkx6q.png" align="center" width=760/>

## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Bifurca el repositorio fuente, y chequea una copia local, a mano

<img src="https://i.imgur.com/cgVQAyZ.png" align="center" width=760/>



## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Bifurca el repositorio fuente, y chequea una copia local, con usethis

```
library(usethis)
create_from_github(owner/repo)
```

## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Usa el paquete usethis

```
library(usethis)
```

Crea una rama para la PR

```
# Datos de bicicletas en Buenos Aires (cienciadedatos/datos-de-miercoles#55)
pr_init("55_bicicletas-en-ba")
```



## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Trabajando localmente, hace un commit que agrega datos y  archivos:

* `datos/2019/2019-08-28/README.md`
* `datos/2019/2019-08-28/bicicletas.csv`
* `datos/2019/2019-08-28/estaciones.csv`

## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Empuja la rama local a GitHub, y abre una pagina web para iniciar la PR

```
pr_push()
```



## [\@rivaquiroga](https://github.com/rivaquiroga) (administradora)

Usa el paquete usethis

```
library(usethis)
```

## [\@rivaquiroga](https://github.com/rivaquiroga) (administradora)

Descarga la PR localmente para revisarla

```
pr_fetch(58)
```

## [\@rivaquiroga](https://github.com/rivaquiroga) (administradora)

Edita la PR, hace un commit y lo empuja nuevamente a GitHub

```
pr_push() 
```

## [\@rivaquiroga](https://github.com/rivaquiroga) (administradora)

Funde la PR, y elimina la rama local

```
pr_finish() 
```

## [\@eliocamp](https://github.com/eliocamp) (contribuidor)

Usa el paquete usethis

```
library(usethis)
```

Elimina la rama de la PR

```
pr_finish() 
```



## [Casos mas complejos](https://usethis.r-lib.org/reference/pr_init.html)

Hay casos mas [casos mas complejos](https://usethis.r-lib.org/reference/pr_init.html), pero están fuera del alcance de esta demostración.


## Gracias

--

### <https://twitter.com/mauro_lepore>



# 

Fin



## Acerca de este repositorio

Este repositorio fue clonado de [Datos de miercoles](https://github.com/cienciadedatos/datos-de-miercoles) y simplificado para enfocarlo a datos específicos:

* El directorio `.git/` original fue reemplazado por uno nuevo.
* Los directorios `meta/` y `recursos/` fueron eliminados.
* Los subdirectorios de `datos/2019/` fueron eliminados, excepto
  `datos/2019/2019-08-28/`.
* El archivo `datos/2019/2019-08-28/bicicletas.csv` fue reducido a sus
  primeras 500 filas.




## TODO: 

* Add screenshots
* Record video and add link


