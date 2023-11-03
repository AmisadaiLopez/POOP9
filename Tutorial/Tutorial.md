---
marp: true 
author: Miriam Lopez
size: 4:3
theme: gaia 
---
# Tutorial
- **3 herramientas utilizadas en la práctica 9**
![width:500px](Captura20.png)

---
## Marp for VS Code
- *Instalar la extensión*
    - Abrir Visual Studio Code.
    - Ir a la pestaña de "Extensions" en la barra lateral izquierda.
    - Buscar "Marp" en la barra de búsqueda y seleccionar la extensión Marp for VS Code.
    - Hacer clic en "Install"  para instalar.
- *Crear un nuevo archivo Markdown*
    - Crear un nuevo archivo Markdown  (con extensión .md) en Visual Studio Code
---
#### Sintaxis de Marp
- Para las diapositivas: Utilizamos tres guiones - para separar diapositivas
- Para los títulos de diapositivas: Para agregar títulos a las diapositivas usamos un signo '#'
    - Depende el tamaño del título se usan varios signos '#'
---
- Para los diferentes tipos de letra se agregan de la siguiente manera 
![width:400px](Captura.png)
---
- Para agregar imagenes se guarda la imagen en la carpeta donde se esta elaborando la presentacion, y para agregarla utilizamos la forma '![width:800px](nombre de la imagen.png)'
- Para comentar se utiliza la siguiente forma '[comment]: <> (This is a comment, it will not be include)'
---
- Para agregar una tabla se escribe de la siguiente manera
![width:500px](Captura1.png)
---
#### Guardar las diapositivas elaboradas 
- Pulsamos en el ícono que apararece en la parte superior derecha 
![width:400px](Captura3.png)
- Después pulsamos en dónde dice exportar 
![width:400px](Captura4.png)
---
- Nos abrira el explorador de archivos en la carpeta donde estamos realizando las diapositivas
- Se puede descargar de diversas formas, en nuestro caso usamos PDF
![width:500px](Captura5.png)
---
## Markmap
- *Instalar la extensión*
    - Utilizamos la misma forma que al instalar Marp for VS Code
- *Crear un nuevo archivo Markmap*
    - Crear un nuevo archivo Markdown  (con extensión .md) en Visual Studio Code
---
#### Sintaxis de Markmap
- Se escribe un texto de la siguiente manera 
![width:500px](Captura6.png)
---
- Para visualizarlo en manera de mapa mental:
- Nos vamos a la parte superior derecha presionando el ícono que tiene forma de tridente
![width:500px](Captura7.png)
---
- Se vera de la siguiente forma
![width:500px](Captura8.png)
---
#### Descargar el mapa mental
- Para descargar el mapa, nos vamos a la parte inferior derecha, dónde dice 'Export'.
![width:500px](Captura9.png)
---
- Se abrira el explorador de archivos en la carpeta donde estamos realizando el proyecto. Se exportara en un archivo HTML.
![width:500px](Captura10.png)
- Podremos ver el archivo en nuestro navegador.
---
## PlantUML
- *Instalar la extensión*
    - Utilizamos la misma forma que al instalar Marp for VS Code
- *Crear un nuevo archivo PlantUML*
    - Crear un nuevo archivo Markdown  (con extensión .md) en Visual Studio Code
---
#### Sintaxis de PlantUML
- Agregamos al inicio el siguiente texto '@startuml scale 3'
- Para crear diagramas UML se utiliza la siguiente sintaxis: 
![width:500px](Captura11.png)
---
- Para imprimir se escribe lo siguiente: 
![width:500px](Captura12.png)
---
- Nosotros escribimos una clase abstracta y después ciertas clases, de la siguiente manera:
![width:500px](Captura13.png)
---
- Para imprimir esa sintaxis, la imprimimos de la siguiente manera: 
![width:500px](Captura14.png)
---
- Para poner que era una interfaz solo escribimos ': Interfaz' después del método, por ejemplo: 
![width:500px](Captura15.png)
- Al final de todo lo que escribimos agregamos '@enduml'
---
#### Visualizar el diagrama UML
- Nos dirigimos a la parte superior izquierda, en el apartado 'View'
![width:500px](Captura16.png)
---
- Nos saldra los siguiente y seleccionaremos 'Command Palette'
![width:500px](Captura17.png)
---
- Seleccionamos 'Preview current PlantUML code'
![width:500px](Captura18.png)
---
- El diagrama se visualizara de la siguiente manera
![width:500px](Captura19.png)
