# Mirror de la Wiki del Proyecto CIAA

Este repositorio contiene una copia de la Wiki del Proyecto Computadora Industrial Abierta Argentina.

La versión web se puede acceder desde la URL: https://mefhigoseth.github.io/ciaa-wiki/

## Cómo se hizo este Mirror ?

Para realizar el mirror se utilizó el siguiente comando:

```
$ wget --mirror --convert-links --adjust-extension --page-requisites --no-parent  http://www.proyecto-ciaa.com.ar/devwiki/doku.php?id=start .
```
