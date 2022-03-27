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
2. Copia el archivo EJER.TXT en AGENDA
~~~
C:\Users\cosmetorandell\Desktop\D\apli\word\textos>copy ejer.txt c:\Users\cosmetorandell\Desktop\D\varios\agenda
~~~
3. Borra el archivo almacenado en la carpeta TEXTOS
~~~
C:\Users\cosmetorandell\Desktop\D\apli\word\textos>del ejer.txt
~~~
4. Añade el siguiente párrafo al archivo EJER.TXT
>“Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos”
~~~
C:\Users\cosmetorandell\Desktop\D\varios\agenda>notepad ejer.txt
~~~
5. Copia el archivo EJER.TXT en la carpeta BASIC
~~~
C:\Users\cosmetorandell\Desktop\D\varios\agenda>copy ejer.txt c:\Users\cosmetorandell\Desktop\D\prog\basic
~~~
6. Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT
~~~
C:\Users\cosmetorandell\Desktop\D\varios\agenda>ren ejer.txt fichero.txt
~~~
7. Mueve el archivo FICHERO.TXT a la carpeta BASIC
~~~
C:\Users\cosmetorandell\Desktop\D\varios\agenda>move fichero.txt c:\Users\cosmetorandell\Desktop\D\prog\basic
~~~
8. Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el nombre NUEVO.TXT dentro de la carpeta BASIC
~~~
C:\Users\cosmetorandell\Desktop\D\prog\basic>notepad ejer.txt
~~~
9. Copia el archivo NUEVO.TXT en la carpeta NOTAS
~~~
C:\Users\cosmetorandell\Desktop\D\prog\basic>copy nuevo.txt c:\Users\cosmetorandell\Desktop\D\apli\word\notas
~~~
10. ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?

3 archivos en la carpeta basic y 1 archivo en la carpeta notas
## Ejercicio 3
1. Borra la carpeta ACCESS y en su lugar crea una nueva carpeta llamada ASTRO 
~~~
C:\Users\cosmetorandell\Desktop\D\apli>rmdir /s c:\Users\cosmetorandell\Desktop\D\apli\access
C:\Users\cosmetorandell\Desktop\D\apli>md astro
~~~
2. Crea la siguiente estructura de subcarpetas dentro de la carpeta ASTRO:
![Estructura2](https://github.com/cosmetorandellborras/Ejercicio-2-MS-DOS/blob/main/e2.png)
~~~
C:\Users\cosmetorandell\Desktop\D\apli>cd astro
C:\Users\cosmetorandell\Desktop\D\apli\astro>md historia ciencia
C:\Users\cosmetorandell\Desktop\D\apli\astro>cd historia
C:\Users\cosmetorandell\Desktop\D\apli\astro\historia>md datos1 datos2
C:\Users\cosmetorandell\Desktop\D\apli\astro\historia>cd ..
C:\Users\cosmetorandell\Desktop\D\apli\astro>cd ciencia
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>md astro1 astro2
~~~
3. Sitúate en la carpeta CIENCIA y desde allí muestra el listado de archivos y subcarpetas de la carpeta HISTORIA
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>dir c:\Users\cosmetorandell\Desktop\D\apli\astro\historia
~~~
4. Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre TYCHO.TXT dentro de la carpeta DATOS1
>“La importancia de Tycho Brahe (1546-1601) es debida a sus trabajos observacionales, que registraron posiciones notables del Sol, la Luna y los planetas”
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos1>copy con tycho.txt
"La importancia de Tycho Brahe (1546-1601) es debida a sus trabajos observacionales, que registraron posiciones notables del Sol, la Luna y los planetas"^Z
        1 archivo(s) copiado(s).
~~~
5. Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y guárdalo con el nombre KEPLER.TXT dentro de la carpeta DATOS2
>“ La información acumulada facilitó a Johannes Kepler (1571-1630) el descubrimiento de las leyes que gobiernan el movimiento de los planetas”
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos2>copy con kepler.txt
" La información acumulada facilitó a Johannes Kepler (1571-1630) el descubrimiento de las leyes que gobiernan el movimiento de los planetas"^Z
        1 archivo(s) copiado(s).
~~~
6. Copia los archivos TYCHO.TXT y KEPLER.TXT en la carpeta CIENCIA
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>copy c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos1\tycho.txt c:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia
___
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>copy c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos2\kepler.txt c:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia
~~~
7. Cambia de lugar los archivos almacenados en DATOS1 y DATOS2 de forma que TYCHO.TXT quede guardado dentro DATOS2 y KEPLER.TXT en DATOS1
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>move c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos1\tycho.txt c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos2
___
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>move c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos2\kepler.txt c:\Users\cosmetorandell\Desktop\D\apli\astro\historia\datos1 
~~~
8. Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el texto) y guárdalo dentro de la carpeta HISTORIA con el nombre TOTAL.TXT
~~~
C:\Users\cosmetorandell\Desktop\D>copy .\apli\astro\historia\datos1\kepler.txt + .\apli\astro\historia\datos2\tycho.txt .\apli\astro\historia\total.txt
~~~
9. Abre el archivo KEPLER.TXT almacenado en la carpeta CIENCIA y añade el siguiente texto:
>“Kepler aplicó sus teorías a los satélites de Júpiter, descubiertos por Galileo a través de un pequeño telescopio, cuya introducción en la observación astronómica constituye uno de los hitos de la astronomía.”
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>notepad c:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia\kepler.txt
~~~
10. Cambia el nombre del archivo anterior por el de GALILEO.TXT
~~~
C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia>ren C:\Users\cosmetorandell\Desktop\D\apli\astro\ciencia\kepler.txt galileo.txt
~~~
## Ejercicio 4
1. Crea en la carpeta raíz de la unidad A: una carpeta denominada TECINFO
~~~
C:\Users\cosmetorandell\Desktop\A>md tecinfo
~~~
2. Crea dentro de TECINFO el siguiente archivo de texto y llámalo HARD.TXT
>“El HARDWARE está constituido por los elementos físicos del ordenador. Consta esencialmente de componentes electrónicos que proporcionan el soporte necesario para la interpretación y ejecución de las operaciones elementales que realiza el ordenador”
~~~
C:\Users\cosmetorandell\Desktop\A\tecinfo\>copy con hard.txt
"El HARDWARE está constituido por los elementos físicos del ordenador. Consta esencialmente de componentes electrónicos que proporcionan el soporte necesario para la interpretación y ejecución de las operaciones elementales que realiza el ordenador"^Z
        1 archivo(s) copiado(s).
~~~
3. Crea dentro de TECINFO el siguiente archivo de texto y llámalo SOFT.TXT
>“El SOFTWARE es el conjunto de elementos lógicos necesarios para que el ordenador realice las funciones que se le encomiendan. Está formado por los programas, es decir, por un conjunto ordenado de instrucciones,
comprensibles por la máquina, que permiten desarrollar tareas concretas”
~~~
C:\Users\cosmetorandell\Desktop\A\tecinfo>copy con soft.txt
"El SOFTWARE es el conjunto de elementos lógicos necesarios para que el ordenador realice las funciones que se le encomiendan. Está formado por los programas, es decir, por un conjunto ordenado de instrucciones,
comprensibles por la máquina, que permiten desarrollar tareas concretas"
^Z
        1 archivo(s) copiado(s).
~~~
4. Mueve el contenido de TECINFO a la carpeta APLI del disquete A utilizado para realizar los ejercicios anteriores
~~~
C:\Users\cosmetorandell\Desktop\A\tecinfo>move C:\Users\cosmetorandell\Desktop\A\tecinfo       c:\Users\cosmetorandell\Desktop\D\apli
~~~
5. Crea un nuevo archivo formado por la unión de HARD.TXT y SOFT.TXT, sin volver a escribir el texto, y guárdalo en la carpeta AGENDA con el nombre ORDER.TXT
~~~
C:\Users\cosmetorandell\Desktop\D\apli>copy hard.txt+soft.txt ..\varios\agenda\order.txt
~~~
6. Elimina la carpeta TECINFO
~~~
C:\Users\cosmetorandell\Desktop\A>rd tecinfo
~~~
7. Copia a la vez los archivos HARD.TXT y SOFT.TXT en la carpeta VARIOS
~~~
C:\Users\cosmetorandell\Desktop\D\apli>copy *.txt ..\varios
~~~
8. Cambia la extensión de los archivos contenidos en AGENDA por .TYP
~~~
C:\Users\cosmetorandell\Desktop\D\varios\agenda>ren *.* *.typ
~~~
9. Cambia la primera letra del nombre de todos los archivos del directorio APLI que empiecen por la letra C y tengan extensión DOC de forma que empiecen con la letra S
~~~
C:\Users\cosmetorandell\Desktop\D\apli>ren c*.doc* s*.doc*
~~~
10. Copia los archivos contenidos en la carpeta APLI que tengan extensión DOC en la carpeta AGENDA
~~~
C:\Users\cosmetorandell\Desktop\D\apli>copy *.doc ..\varios\agenda
~~~

