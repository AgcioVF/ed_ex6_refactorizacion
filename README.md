# INICIO DEL EJERCICIO

## _Preparación inicial_
Creamos el repositorio en GitHub y los enlazamos al IDE, en mi caso IntelIJ.

Mediante el uso de los comandos:
***
* Inicializar git de forma local.
```
    git init
```
* Enlazar el projecto al repositorio.
```
    git remote add origin https://github.com/AgcioVF/ed_ex6_refactorizacion.git
```
* Para guardar y subir cambios respectivamente.
```
    git add .
    git commit -m "Primer commit"
```

Creamos el README.md para la documentación y lo subimos como parte del primer commit.
***

Preparamos la estructura del proyecto _(clase **NotaFinalCalculator** y **sonar-project.properties**)_ y la subimos con un segundo commit
***

## _Lanzamiento de sonar_scanner_

* Nos dirigimos a la ruta de nuestro proyecto.
```
    cd C:\rutaAbsoluta
```
* Aplicamos nuestro comando y lanzamos el análisis:
```
    for /r src %f in (*.java) do javac -d target\classes "%f"
    sonar-scanner
```
***
# REFACTORIZACION

Creamos una rama para desarrollar nuestra refactorización.
```
        git checkout -b refactorizacion_codigo
```

## BLOCKER

1. Eliminar una variable sin uso (label // linea 161)

## HIGH

