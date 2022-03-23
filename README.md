# Sistemas Informáticos - Práctica 2 MS-DOS
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
