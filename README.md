# pasos para compilar libro SDR
Este **README** trata de como compilar el Libro del curso srd para poder verlo en formato pdf 
## PASOS PREVIOS A LA COMPILACION  🚀 🚀 🚀
para comenzar debemos hacer un git clone del libro directamente del repositorio 
desde la cosola 
```
git clone git@github.com:microondas901/Edicion-1-.git
```
seguido de esto debemos  de  tener instalado otras 2 herramientas para poder compilar el libro 

las cuales son:

la primera es inkscape, en caso tal de no tener instalada  basta con solo ingresar el siguente comando en consola:

**para tener en cuenta:** los siguiente comandos son dependiendo de las distro linux que estes utilizando 
###  comando para linux mint  :
```
sudo apt-get install inksacape 
```
###  comando para ubuntu  :
```
sudo apt-get install inksacape 
```
la segunda es tex live en la version minima  para poder compilar de .tex a .pdf 

**los comandos son:**
###  comando para linux mint  :
```
sudo apt-get install texlive-latex-base 
```
###  comando para ubuntu  :
```
sudo apt-get install texlive-latex-base 
```

## COMPILACION  DEL LIBRO ⚙️⚙️⚙️
lo primero que tenemos que hacer para proceder con la compilaciones del libro en caso tal de que se enuentre el formato zip 
es proceder a descomprimir una ves que se descomprima arojara una carpeta la cua contiene todos los archivos nesesarios para la compilacion

:red_circle: nota: ***lo descrito anterior es para aquellos que descargran el libro directamente del repositorio si usted clono el repositorio omita este paso***

una ves aclarado esto ahora si procederemos a iniciar nuestra compilacion del libro 

ubicamos la carpeta que contine todo lo nesesario para la compilacion y damos sobre ella click derecho

y damos en la opcion abrir con la teminal 

cuando la terminal abra procederemos a escribir el siguiente comando:

```
make
```
que en este caso se veria asi:

```
Edicion-1--master$ make
```
damos enter y esperamos unos minutos mientras se compila nuestro libro 
