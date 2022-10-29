# Manipular commits anteriores
## *Regresar a un punto anterior*

#### obtener el hash/id del commit
```
git log
```
#### con el hash, ejecutar:
```
git reset --mixed aaabbb
```
ó

```
git reset --hard aaabbb
```

#### --mixed mantiene los cambios, --hard los destruye
---

## *Recuperar un commit*
#### Buscar el hash del commit con:
```
git reflog
```
#### con el hash, ejecutar:
```
git reset --hard aaabbb
```
---
## *Mover archivos o renombrar sin perder historial*
```
git mv nombreviejo.ext nombrenuevo.ext
```
---
## *Eliminar un archivo*
```
git rm archivo.ext
```
---
## *Recuperar archivo eliminado en commit anterior (vuelve un commit atrás)*
```
git reset --hard
```