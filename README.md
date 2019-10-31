# Ayudantes para solicitudes de fusión en GitHub  
[_Helpers for GitHub pull requests (usethis)_](https://usethis.r-lib.org/reference/pr_init.html)  

[\@mauro_lepore](https://twitter.com/mauro_lepore)



## [Resumen](https://twitter.com/lorenzwalthert/status/1188932430171983873?s=20)

![](https://i.imgur.com/jTXUIpL.png)

## Ejemplo: Contribuyendo a [cienciadedatos/datos-de-miercoles](https://github.com/cienciadedatos/datos-de-miercoles/pull/58)

Simulo la contribucion (simplificada) de [Bicicletas de Buenos Aires (#58)](https://github.com/cienciadedatos/datos-de-miercoles/pull/58) de [\@eliocamp](https://github.com/eliocamp), administrada por [\@rivaquiroga](https://github.com/rivaquiroga).

![](https://i.imgur.com/74axHZu.png)



### Elio (contribuidor)

* Fork the source repository and check out a local copy, manually or with

```
create_from_github(owner/repo)
```

* Create a branch for your PR (never from `master`)

```
pr_init()
```

* Work locally, making changes to files and checking them into git

* When ready, push local branch to GitHub, and open a webpage to initiate the PR

```
pr_push()
```

### Riva (administradora)

* Download PR locally to experiment with it

```
pr_fetch(<pr_number>)
```

* Make changes and push them back to GitHub

```
pr_push() 
```

Merge the PR, and delete the local branch

```
pr_finish() 
```

### Elio (contribuidor)

The maintainer accepted the PR. Close and delete the PR branch.

```
pr_finish() 
```

More complex cases are outside the scope of this demo

---

Este repositorio fue clonado de [Datos de miercoles](https://github.com/cienciadedatos/datos-de-miercoles) y simplificado para enfocarlo a datos específicos:

* El directorio `.git/` original fue reemplazado por uno nuevo.
* Los directorios `meta/` y `recursos/` fueron eliminados.
* Los subdirectorios de `datos/2019/` fueron eliminados, excepto
  `datos/2019/2019-08-28/`.
* El archivo `datos/2019/2019-08-28/bicicletas.csv` fue reducido a sus
  primeras 500 filas.

