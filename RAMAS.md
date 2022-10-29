# Comandos para ramas, uniones y conflictos
## *Crear una nueva rama*
```
git branch nombre-rama
```
## *Moverse a la nueva rama*
```
git checkout nombre-rama
```
## *Crear y moverse a una nueva rama*
```
git checkout -b nombre-rama
```
## *Eliminar una rama*
```
git branch -d nombre-rama
```
## *Si la rama nunca se unio a otra se puede forzar la eliminación con --force o -f*
```
git branch -d nombre-rama -f
```
---
## Tipos de uniones:
* *fast-forward: Se hacen cambios en rama secundaria pero no en rama principal*
* *unión automática: Se hacen cambios en ambas ramas pero en diferentes lineas, no hay conflictos. Se necesita de un commit para unir ambas ramas*
* *uniones con conflictos: se hacen cambios en ambas ramas en la misma linea del mismo archivo, hay conflictos que resolver manualmente*

## *Unir una rama a la rama principal desde la rama principal*
```
git merge nombre-rama
```
#### en caso de necesitar salir de la consola luego del commit que solicita el merge:
```
:wq!
```