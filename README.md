# Ayudantes para solicitudes de fusión en GitHub  
[_Helpers for GitHub pull requests (PR)_](https://usethis.r-lib.org/reference/pr_init.html)  

[\@mauro_lepore](https://twitter.com/mauro_lepore)

## Contribuyendo a [cienciadedatos/datos-de-miercoles](https://github.com/cienciadedatos/datos-de-miercoles/pull/58)

Inspirado en la contribución de [Bicicletas de Buenos Aires (#58)](https://github.com/cienciadedatos/datos-de-miercoles/pull/58) de [\@eliocamp](https://github.com/eliocamp), administrada por [\@rivaquiroga](https://github.com/rivaquiroga).

![](https://i.imgur.com/74axHZu.png)

Real > Demostración:

* [cienciadedatos/datos-de-miercoles](https://github.com/cienciadedatos/datos-de-miercoles) > [an-org/datos-de-miercoles](https://github.com/an-org/datos-de-miercoles)
* [\@eliocamp](https://github.com/eliocamp) (contribuidor) > \@maurolepore
* [\@rivaquiroga](https://github.com/rivaquiroga) (administradora) > \@maurolepore






TODO: 

* Add screenshots
* Record video and add link






### [\@eliocamp](https://github.com/eliocamp) (contribuidor)

* Usa el paquete usethis

```
library(usethis)
```

* Bifurca el repositorio fuente, y chequea una copia local

```
# Puede hacerse manualmente, o con:
create_from_github(owner/repo)
```

* Crea una rama para la PR. Usa el numero de issue (si existe) como prefijo

```
# Datos de bicicletas en Buenos Aires (cienciadedatos/datos-de-miercoles#55)
pr_init("55_bicicletas-en-ba")
```

* Trabajando localmente, hace un commit que agrega datos y  archivos:
    * `datos/2019/2019-08-28/README.md`
    * `datos/2019/2019-08-28/bicicletas.csv`
    * `datos/2019/2019-08-28/estaciones.csv`

* Empuja la rama local a GitHub, y abre una pagina web para iniciar la PR

```
pr_push()
```

### [\@rivaquiroga](https://github.com/rivaquiroga) (administradora)

* Usa el paquete usethis

```
library(usethis)
```

* Descarga la PR localmente para revisarla

```
pr_fetch(58)
```

* Edita la PR, hace un commit y lo empuja nuevamente a GitHub

```
pr_push() 
```

* Funde la PR, y elimina la rama local

```
pr_finish() 
```

### [\@eliocamp](https://github.com/eliocamp) (contribuidor)

* Usa el paquete usethis

```
library(usethis)
```

* Elimina la rama de la PR

```
pr_finish() 
```

Hay [casos mas complejos](https://usethis.r-lib.org/reference/pr_init.html), pero están fuera del alcance de esta demostración.



---

Este repositorio fue clonado de [Datos de miercoles](https://github.com/cienciadedatos/datos-de-miercoles) y simplificado para enfocarlo a datos específicos:

* El directorio `.git/` original fue reemplazado por uno nuevo.
* Los directorios `meta/` y `recursos/` fueron eliminados.
* Los subdirectorios de `datos/2019/` fueron eliminados, excepto
  `datos/2019/2019-08-28/`.
* El archivo `datos/2019/2019-08-28/bicicletas.csv` fue reducido a sus
  primeras 500 filas.

