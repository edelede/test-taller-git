# Taller GIT
Comandos:

1.Inicializar un repositorio desde terminal
```bash
git init
```
2.Ver el estado de los archivos dentro del repositorio y la branch en la que estas
```bash
git status
```
3.Añadir archivos al stage para ser agregados al commit
- Para añadir un solo archivo a la vez
```bash
git add <ruta/archivo.ext>
```
- Para añadir todos los archivos disponibles
```bash
git add .
```

4.Una vez seleccionados todos los archivos que deseas commitear debes agregarlos al commit
```bash
git commit -m "mensaje utilizado para describir los cambios realizados"
```
Ejemplo de buenas practicas para commits : [Buenas prácticas para escribir commits en Git](https://midu.dev/buenas-practicas-escribir-commits-git/ "Buenas prácticas para escribir commits en Git")

5.Conectar el repositorio a plataforma de control de versiones
```bash
git remote add origin https://github.com/<usuario>/<repositorio.git>
git branch -M main
git push -u origin main
```
6.Inicializar nueva rama
```bash
git branch <nombre_rama>
```
7.Moverse entre distintas ramas
```bash
git switch <rama_a_moverse>
```
8.Merge entre ramas

*Para esto se considerara que nos encontramos en la rama main y que utilizaremos la rama prueba para el merge*

```bash
git merge prueba
```

## Vamos a jugar!
[Learn GIT Branching](https://learngitbranching.js.org/?locale=es_ES "Learn GIT Branching")
