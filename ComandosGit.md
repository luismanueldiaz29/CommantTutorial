# Comandos utiles de git

## Inicializar repositorio en git
```
git init
```
## Agregar archivos y prepararlo para su posterior captura
```
git add .
```
## Revierte los archivos agregados, revierte el git add .
```
git reset .
```
## Capturar la informacion, algo asi como una fotografia del proyecto
```
git commit
```
## Recuperar la información que se capturo en el ultimo commit del proyecto
```
5. git checkout -- .
```
## Ver el listado de los commit realizados
```
git log
```
## Corregir el mesaje del ultimo commit
```
git commit --amend
```
## Crear una nueva rama
```
git checkout -b rama-heroes
```
## Listado de las ramas que existen
```
git branch
```
## Pasar de una rama a otra, ejemplo pasar a la rama master:
```
git checkout master
```
## Borrar una rama, ejemplo eliminar la rama rama-heroes
```
git branch -d rama-heroes
```
## Realizar despliege a un repositorio externo
```
git push
```
## Comando simultanio: git add . && git commit
```
git commit -am
```
