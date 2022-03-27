# Ejercicio-2-MS-DOS

## Objetivos
Los objetivos de esta práctica son realizar una serie de ejercicios básicos de comandos MS-DOS con el fin de afianzar el conocimiento de los comandos básicos
## Ejercicio 1
1. Crea la siguiente estructura de carpetas:
![Estructura carpetas](https://github.com/cosmetorandellborras/Ejercicio-2-MS-DOS/blob/main/Ex%201.png)
![Comandos](https://github.com/cosmetorandellborras/Ejercicio-2-MS-DOS/blob/main/Cap%201.png)

2.Sitúate en la carpeta TABLAS
~~~
c:\Users\cosmetorandell\Desktop\D> cd apli\excel\tablas
~~~
3. Vuelve a la carpeta raíz
~~~
c:\Users\cosmetorandell\Desktop\D\apli\excel\tablas> cd\
~~~
4. Muestra el contenido de la carpeta PROG
~~~
C:\Users\cosmetorandell\Desktop\D>dir prog
~~~
5. Borra la carpeta PASCAL
~~~
C:\Users\cosmetorandell\Desktop\D\prog>rmdir pascal
~~~
6. Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamado PRACT
~~~
c:\Users\cosmetorandell\Desktop\D\varios>md c:\Users\cosmetorandell\Desktop\D\apli\word\pract
~~~
7. Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL
~~~
C:\Users\cosmetorandell\Desktop\D\apli\word\pract>dir c:\Users\cosmetorandell\Desktop\D\apli\excel
~~~
8. Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz
~~~
C:\Users\cosmetorandell\Desktop\D\apli\excel\tablas>dir c:\
~~~
9. Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de VARIOS
~~~
C:\Users\cosmetorandell\Desktop\D\apli>md c:\Users\cosmetorandell\Desktop\D\varios\agenda
~~~
10. Borra la carpeta EXCEL
~~~
C:\Users\cosmetorandell\Desktop\D\apli>rmdir /s c:\Users\cosmetorandell\Desktop\D\apli\excel
~~~
11. Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO
~~~
C:\Users\cosmetorandell\Desktop\D>md nuevo
~~~
12. Desde PRACT muestra el contenido de WORD
~~~
C:\Users\cosmetorandell\Desktop\D\varios\pract>dir c:\Users\cosmetorandell\Desktop\D\apli\word
~~~
## Ejercicio 2
1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT, con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior):
>“La información dentro de los discos se almacena en forma de archivos. Un archivo o fichero es un conjunto de datos que MS-DOS almacena en un disco y cuyo control interno es realizado por el sistema operativo, aunque desde el punto de vista lógico el control es del usuario”
~~~
C:\Users\cosmetorandell\Desktop\D\apli\word\textos>copy con ejer.txt
"La información dentro de los discos se almacena en forma de archivos. Un archivo o fichero es un conjunto de datos que MS-DOS almacena en un disco y cuyo control interno es realizado por el sistema operativo, aunque desde el punto de
vista lógico el control es del usuario"
^Z
        1 archivo(s) copiado(s).

~~~
