# GIT Básico

## Instalacióm

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

``` 
git config --global user.name "nombreusuario"
git config --global user.email "correousuario"
``` 

## Crear un repositorio git

``` 
git init
``` 

## Comprobar el estado e Git

Ver la situación en la que están los cambios desde el último comit

```

git status
```
## Añadir archivos al staging area

Añade tofos los cambios pendientes

```

git add -A
```
## Crear un comit

Para guardar un conjunto de cambios y crear un punto de control usamos los commit

```
git commit -m "mensaje del commit"