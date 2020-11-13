# Tkinter label tool
Modificación de Bbox label tool for Python3.7

Codigo fuente original: https://github.com/BASFProject-2018spring/BBox-Label-Tool-large-img
_______________________________________________________________________________________________________________________________________
Archivos
1. main.py (para imagenes jpg)

2. class.txt (donde se define el nombre de las posibles etiquetas)

_______________________________________________________________________________________________________________________________________
Uso

1. Se recomienda dividir las imagenes en N carpetas para  que etiquetar todo un dataset de una sola vez.
- Ponga las imagenes en un folder llamado images, estas se guardan en un .txt **cada vez** como Images/001, Images/002, etc.

- En un folder 'Labels', creé folders vacios con el nombre de la clase a etiquetar Images (001,002,etc.). 

2. Para windows puede crear un 'main.exe' (posible crearlo con py2exe, bajo Linux o mac, use main.py)

3. Utilizando los botones de carga indique los folders de las imagenes y las etiquetas, y haga click en 'Load'.
Las imagenes se visualizaran en pantalla.

4. Seleccione la clase de a etiquetar, y haga click en 'confirm'. The default es la ultima ruta usada, sino existe estara
en blanco.

5. Para crear una nueva bounding box sobre la imagen, haga click izquierdo para seleccionar el primer vertice del rectangulo. 

dibuje el rectangulo con el mouse, y nuevamente haga click izquierdo para seleccionar el segundo vertice.

- Para cancelar el dibujo de la bounding box mientras se dibuja, presione la tecla 'Esc'.

- Para borrar un bounding box existente, seleccionelo de la listbox, y haga click en 'Delete'.

- Para borrar todas las bounding boxes existentes en la imagen, simplemente haga click en 'ClearAll'.


6. Luego de etiquetar todos los objetos en una imagen,haga click en 'Next' para avanzar con otra imagen. así mismo, click en 'Prev' lo lleva a la imagen anterior.
Es posibel navegar a una imagen especifica indicando su valor en le index y haciendo click en 'Go'.
- Las etiquetas de la imagen solo seran guardadas si se da clik en el boton 'Next'.  

