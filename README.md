# Sistemas Informáticos - Práctica 2 MS-DOS - Xavier Borrás Mercant

## EJERCICIO 1
### 1. Crea la siguiente estructura de carpetas:

Creación de la carpeta base (D):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D"`

Creación de los tres primeros niveles de carpetas (APLI, PROG, VARIOS):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS"`

Creación de las tres carpetas hijas de APLI (WORD, ACCESS, EXCEL):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ACCESS"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL"`

Creación de las tres carpetas hijas de PROG (BASIC, PASCAL, FORTRAN):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\PASCAL"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\FORTRAN"`

Creación de las dos carpetas hijas de WORD (TEXTO, NOTAS):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\TEXTOS"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\NOTAS"`

Creación de las dos carpetas hijas de EXCEL (TABLAS, INFO):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL\TABLAS"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL\INFO"`


### 2. Sitúate en la carpeta TABLAS:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL\TABLAS"`


### 3. Vuelve a la carpeta raíz:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D"`


### 4. Muestra el contenido de la carpeta PROG:

`dir "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG"`


### 5. Borra la carpeta PASCAL:

`rd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\PASCAL"`


### 6. Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamada PRACT.
Nos situamos en la carpeta VARIOS:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS"`

Una vez desde la carpeta VARIOS ejecutamos el siguiente comando para crear una carpeta dentro de WORD llamada PRACT:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\PRACT"`


### 7. Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL
Nos situamos en la carpeta PRACT:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\PRACT"`

Mostramos el contenido de la carpeta EXCEL:

`dir "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL"`


### 8. Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz:
Nos situamos en la carpeta TABLAS:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\PRACT"`

Mostramos el contenido de la carpeta D (raíz):

`dir "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D"`


### 9. Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de VARIOS:
Nos situamos en la carpeta APLI:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI"`

Mostramos el contenido de la carpeta D (raíz):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D"`


### 10. Borra la carpeta EXCEL:

`rd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\EXCEL" /S`


### 11. Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO:
Nos situamos en la carpeta raíz (D):

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D"`

Creamos una nueva carpeta llamada NUEVO:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\NUEVO"`


### 12. Desde PRACT muestra el contenido de WORD:
`Nos situamos en la carpeta PRACT:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\PRACT"`

Mostramos el contenido de la carpeta D (raíz):

`dir "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD"`



## EJERCICIO 2
### 1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT, con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior):
Nos situamos en la carpeta TEXTO:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\TEXTOS"`

Una vez situados en la carpeta TEXTOS ejecutamos el siguiente comando para crear el archivo EJER.TXT en su interior:

`copy con EJER.TXT`

Después de ejecutar el comando deberemos escribir el contenido de este archivo de texto:

*"La información dentro de los discos se almacena en forma de archivos. Un archivo o fichero es un conjunto de datos que MS-DOS almacena en un disco y cuyo control interno es realizado por el sistema operativo, aunque desde el punto de vista lógico el control es del usuario"*


### 2. Copia el archivo EJER.TXT en AGENDA:
Nos situamos en TEXTOS:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\TEXTOS"`

Copiamos el archivo y lo pegamos en AGENDA con el siguiente comando:

`copy EJER.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA"`


### 3. Borra el archivo almacenado en la carpeta TEXTOS:
Nos situamos en TEXTOS:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\TEXTOS"`

Borramos el archivo EJER.TXT:

`del /s /q "EJER.txt"`


### 4. Añade el siguiente párrafo al archivo EJER.TXT:
Nos situamos en AGENDA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA"`

Editamos EJER.TXT con el comando:

`notepad ejer`

Y a continuación, dentro del bloc de notas, escribimos el texto que queramos añadir:

*“Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos”*


### 5. Copia el archivo EJER.TXT en la carpeta BASIC:
Nos situamos en AGENDA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA"`

Copiamos el archivo y lo pegamos en BASIC con el siguiente comando:

`copy EJER.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC"`

### 6. Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT
Nos situamos en AGENDA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA "`

Renombramos EJER.TXT a FICHERO.TXT:

`rename "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA\EJER.TXT" FICHERO.TXT`

### 7. Mueve el archivo FICHERO.TXT a la carpeta BASIC:
Nos situamos en AGENDA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA"`

Movemos el archivo FICHERO.TXT a la carpeta BASIC:

`move FICHERO.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC"`

### 8. Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el nombre NUEVO.TXT dentro de la carpeta BASIC:
Nos situamos en BASIC:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC"`

Abrimos el archivo EJER.TXT con el siguiente comando, borramos la primera frase y guardamos el archivo modificado como NUEVO.TXT:

`notepad ejer`

### 9. Copia el archivo NUEVO.TXT en la carpeta NOTAS:
Nos situamos en BASIC:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC"`

Copiamos el archivo y lo pegamos en NOTAS con el siguiente comando:

`copy NUEVO.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\NOTAS"`

### 10. ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?
Vemos cuántos archivos hay en BASIC con el comando:

`dir /a:-d /s /b "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\PROG\BASIC" | find /c ":"`

*Aparecen 3 archivos*

Vemos cuántos archivos hay en NOTAS con el comando:

`dir /a:-d /s /b "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\NOTAS" | find /c ":"`

*Aparece 1 archivo*



## EJERCICIO 3
### 1. Borra la carpeta ACCESS y en su lugar crea una nueva carpeta llamada ASTRO:
Borramos la carpeta ACCESS:

`rd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ACCESS"`

Creamos la nueva carpeta llamada ASTRO:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO"`
### 2. Crea la siguiente estructura de subcarpetas dentro de la carpeta ASTRO:
Creación de Historia sus subcarpetas:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\DATOS1"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\DATOS2"`

Creación de Ciencia y sus subcarpetas:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA\ASTRO1"`

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA\ASTRO2"`

### 3. Sitúate en la carpeta CIENCIA y desde allí muestra el listado de archivos y subcarpetas de la carpeta HISTORIA
`Nos situamos en la carpeta CIENCIA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

Mostramos el contenido de la carpeta HISTORIA:

`dir "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA"`

### 4. Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre TYCHO.TXT dentro de la carpeta DATOS1
Nos situamos en la carpeta DATOS1:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS1"`

Una vez situados en la carpeta DATOS1 ejecutamos el siguiente comando para crear el archivo TYCHO.TXT en su interior:

`copy con TYCHO.TXT`

Después de ejecutar el comando deberemos escribir el contenido de este archivo de texto:

*“La importancia de Tycho Brahe (1546-1601) es debida a sus trabajos observacionales, que registraron posiciones notables del Sol, la Luna y los planetas”*


### 5. Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y guárdalo con el nombre KEPLER.TXT dentro de la carpeta DATOS2
Nos situamos en la carpeta DATOS2:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS2"`

Una vez situados en la carpeta DATOS2 ejecutamos el siguiente comando para crear el archivo KEPLER.TXT en su interior:

`copy con KEPLER.TXT`

Después de ejecutar el comando deberemos escribir el contenido de este archivo de texto:

*“La información acumulada facilitó a Johannes Kepler (1571-1630) el descubrimiento de las leyes que gobiernan el movimiento de los planetas”*

### 6. Copia los archivos TYCHO.TXT y KEPLER.TXT en la carpeta CIENCIA
Nos situamos en DATOS1:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS1"`

Copiamos el archivo y lo pegamos en CIENCIA con el siguiente comando:

`copy TYCHO.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

Nos situamos en DATOS2:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS2"`

Copiamos el archivo y lo pegamos en CIENCIA con el siguiente comando:

`copy KEPLER.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

### 7. Cambia de lugar los archivos almacenados en DATOS1 y DATOS2 de forma que TYCHO.TXT quede guardado dentro DATOS2 y KEPLER.TXT en DATOS1

Nos situamos en DATOS1:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS1"`

Movemos el archivo TYCHO.TXT a la carpeta DATOS2:

`move TYCHO.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS2"`

Nos situamos en DATOS2:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS2"`

Movemos el archivo KEPLER.TXT a la carpeta DATOS2:

`move KEPLER.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA\DATOS1"`

### 8. Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el texto) y guárdalo dentro de la carpeta HISTORIA con el nombre TOTAL.TXT

Nos situamos en la carpeta CIENCIA:
`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

Unimos los dos archivos en un mismo archivo llamado TOTAL.TXT
`copy *.txt TOTAL.TXT`

Movemos el archivo a HISTORIA:
`move TOTAL.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\HISTORIA"`

### 9. Abre el archivo KEPLER.TXT almacenado en la carpeta CIENCIA y añade el siguiente texto:

Nos situamos en la carpeta CIENCIA:
`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

Abrimos el archivo KEPLER.TXT:

`notepad kepler`

Añadimos el siguiente texto:
*“Kepler aplicó sus teorías a los satélites de Júpiter, descubiertos por Galileo a través de un pequeño telescopio, cuya introducción en la observación astronómica constituye uno de los hitos de la astronomía.”*

### 10. Cambia el nombre del archivo anterior por el de GALILEO.TXT

Nos situamos en la carpeta CIENCIA:
`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\ASTRO\CIENCIA"`

Renombramos el archivo de KEPLER.TXT a GALILEO.TXT:
`rename KEPLER.TXT GALILEO.TXT`

# EJERCICIO 4
### 1. Crea en la carpeta raíz de la unidad A: una carpeta denominada TECINFO

Creación de la carpeta base (A):

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A"`

Creamos la carpeta llamada TECINFO:

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO"`

### 2. Crea dentro de TECINFO el siguiente archivo de texto y llámalo HARD.TXT

Nos situamos en la carpeta TECINFO:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO"`

Una vez situados en la carpeta TECINFO ejecutamos el siguiente comando para crear el archivo HARD.TXT en su interior:

`copy con HARD.TXT`

Después de ejecutar el comando deberemos escribir el contenido de este archivo de texto:

*“El HARDWARE está constituido por los elementos físicos del ordenador. Consta esencialmente de componentes electrónicos que proporcionan el soporte necesario para la interpretación y ejecución de las operaciones elementales que realiza el ordenador”*

### 3. Crea dentro de TECINFO el siguiente archivo de texto y llámalo SOFT.TXT

Nos situamos en la carpeta TECINFO:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO"`

Una vez situados en la carpeta TECINFO ejecutamos el siguiente comando para crear el archivo SOFT.TXT en su interior:

`copy con SOFT.TXT`

Después de ejecutar el comando deberemos escribir el contenido de este archivo de texto:

*“El SOFTWARE es el conjunto de elementos lógicos necesarios para que el ordenador realice las funciones que se le encomiendan. Está formado por los programas, es decir, por un conjunto ordenado de instrucciones, comprensibles por la máquina, que permiten desarrollar tareas concretas”*

### 4. Mueve el contenido de TECINFO a la carpeta APLI del disquete A utilizado para realizar los ejercicios anteriores

Movemos HARD.TXT:

`move "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO\SOFT.txt" "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI"`

Movemos SOFT.TXT:

`move "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO\SOFT.txt" "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI"`

### 5. Crea un nuevo archivo formado por la unión de HARD.TXT y SOFT.TXT, sin volver a escribir el texto, y guárdalo en la carpeta AGENDA con el nombre ORDER.TXT
Nos situamos en la carpeta TECINFO:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO"`

Unimos los dos archivos en un mismo archivo llamado ORDER.TXT
`copy *.txt ORDER.TXT`

Movemos el archivo a AGENDA:
`move ORDER.TXT "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENDA"`
### 6. Elimina la carpeta TECINFO
`rd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\A\TECINFO /s"`

### 7. Copia a la vez los archivos HARD.TXT y SOFT.TXT en la carpeta VARIOS

Copiamos los archivos .txt del directorio APLI:

`copy "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\*.*" "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS"`

### 8. Cambia la extensión de los archivos contenidos en AGENDA por .TYP
Nos situamos en AGENDA:

`cd "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\VARIOS\AGENA"`

Renombramos todos los archivos .TXT a .TYP:

`ren *.txt *.typ`

### 9. Cambia la primera letra del nombre de todos los archivos del directorio APLI que empiecen por la letra C y tengan extensión DOC de forma que empiecen con la letra S

No hay ningun archivo .DOC ni que empiece por C en APLI.

### 10. Copia los archivos contenidos en la carpeta APLI que tengan extensión DOC en la carpeta AGENDA

No hay ningun archivo .DOC en APLI.
