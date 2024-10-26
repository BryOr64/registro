# QA PROJECT URBAN ROUTES es

Este proyecto realiza una prueba al formulario creado para la inscripcion a una unidad educativa pidiendo los 
datos basicos para que se pueda inscribir un estudiante.

Tendremos que realizar una revision automatisada donde veremos testearemos todos los campos de el formulario 
en cuestion para ver si podemos detectar algun error al mometo de realizar la prueba automatizada.

podremos revisar y conocer mas del lenguaje de Python, tambien realizaremos varias pruebas para la ejecucion 
automatizada.

## Herramientas

las Herramientas que utilizaremos en este proyecto seran Python, selenium y pytest todo esto configurado en 
el ID de pycharm.

## Instalación de herramientas

Instrucciones detalladas para descargar el proyecto e instalar alguanos complementos que 
necesitaremos en el proyecto son:

```python
# El ID que se esta utilizando
    PYCHARM descargalo en https://www.jetbrains.com/pycharm/

# Clonar el repositorio
    git clone https://github.com/usuario/registro.git

# Entrar al directorio del proyecto
    cd ./registro

# Instalar selenium mediante la consola
    pip install selenium
    o
    pip3 install selenium

# Instalar Pytest mediante la consola
    pip install pytest
    o
    pip3 install pytest
```
# Estructura del Proyecto
 
 - **forumulario.html** - contine toda la programacion de lo que lleva el formulario.
 - **estilos.css** - Contiene todo lo que es los estilos colores de el formlario .
 - **test_formulario.py** - contiene todos los test que se realizaran.

# Ejecución del Proyecto
   1. Como primer paso tenemos que ver que este **ChromeDriver** instalado 
     y que esten condfigurado en tu PATH
   2. Ejecutar el archivo TestUrbanRoutes.py

# Conclusiones
este es un proyecto en el cual pudimos ver lo importante que es llenar los campos para 
el registro de un estudiante en el colegio ya que si nos equivocamos podemos probocar una contaminacion en
en los datos. las prubas salieron existos pero aun nos falta analizar con mas detalle las pruebas
