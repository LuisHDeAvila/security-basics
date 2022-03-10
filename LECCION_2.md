# Autorizacion y Autenticacion

## Autenticacion
es el priceso de demostrar la posesion de una identidad determinada presentando uno o varios atributos de dicha identidad (clave, huella dactilar, certificado electronico, etc.)

## Autorizacion
proceso por el cual una autoridad concede a un usuario permisos de acceso a cierto conjunto de recursos ya sean archivos, sistemas, etc.

## explicacion para mortales
Estos dos terminos los entenderas del 1 al 7. 
y con el propietario, el grupo y otros.

### sabes como leer el lenguaje binario?
mira si leemos de derecha a izquierda, uno, pues es uno, si leemos uno uno es tres,  y si leemos uno uno uno es siete.
por lo tanto, respectivamente           1 r                           3 r   w                         7 r   w   x
y otra vez aparece                  1propietario                   3grupo                         7otros
y si leo los archivos de mi carpeta de Documentos con el comando ls -la
me diria.
```
.rw-r--r-- eleache eleache  64 KB Tue Mar  8 21:12:14 2022 - \.pdf
.rw-r--r-- eleache eleache   0 B  Thu Jan 27 05:58:44 2022 - anon.txt
```
podras notar unas letras y guiones al principio de la breve lista, digamos que significa que propietario puede leer(read) y escribir(write), grupo solo leer(read), y otros solo leer(read), ninguno tiene permiso de ejecucion (x).
Eso es el sistema de permisos del kernel linux, que hereda del lenguaje de programacion C, que tambien se lo heredo a sus semejantes Windows y MacOS.
Pero el sistema de autenticacion va mas alla en nuestra sociedad, pues en algunos paises ya se pide un chip para identificacion de la poblacion, o se le ponen numeros del en vez de nombres a los ninos por ser muy parecidos, tal es el caso de los paises asiaticos, de donde provienen los sistemas de huella digital (confirmo, ni ellos logran distinguirse ya que son muy parecidos, mas los "HAN", con todo respeto).

## como hacker tu primer hackeo aqui y ahora
entra a [Online GDB](https://www.onlinegdb.com/) 
selecciona BASH como lenguaje.
copia y pega esto
```
cd .. ; cd .. ; 
ls -la; # permiso de lectura
cat /etc/passwd # usuarios autenticados del sistema
uname -a # Nombre del sistema que estas operando
```
