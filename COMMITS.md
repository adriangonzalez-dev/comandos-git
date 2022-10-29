# Comandos para staging y commits
## *Conocer estado de archivos*
```
git status
```
## *Conocer estado de archivos de forma abreviada*
```
git status --short
```

---
## *Darle seguimiento a los archivos*
#### Seguir un archivo (ejemplo)
```
git add index.html
```
#### Seguir todos los archivos
```
git add .
```

#### Seguir todos los directorios y archivos de una carpeta en particular
```
git add views/
```

#### Darle seguimiento a todos los archivos de una misma extension en la carpeta raiz
```
git add *.html
```

#### Darle seguimiento a todos los archivos de una misma extension en una carpeta particular
```
git add views/*.html
```
#### Dejar de darle seguimiento a un archivo
```
git reset index.html
```

---
## *Realizar un commit a los archivos que estan seguimiento*
```
git commit -m "nombre del commit"
```

---
## *Forma abreviada de añadir al stage y realizar commit*

```
git commit -am "nombre del commit"
```
---
## *Modificar nombre del ultimo commit realizado*
```
git commit --amend -m "nombre actualizado"
```
---
## *Agregar cambios al ultimo commit realizado*
```
git reset --soft HEAD^
```
#### HEAD apunta al ultimo commit
#### ^ apunta a un commit anterior al último
---
## *Mostrar los cambios en los archivos que no estan en el stage*

```
git diff
```

## *Mostrar los cambios en el stage*

```
git diff --staged
```

