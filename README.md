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

`md "C:\Users\Usuario\Documents\DAM\SistemasInformaticos\MSDOS2\D\APLI\WORD\TEXTO"`

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
