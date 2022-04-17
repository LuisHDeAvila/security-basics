# Autorizacion y Autenticacion

## Autenticacion
es el proceso de demostrar la posesion de una identidad determinada presentando uno o varios atributos de dicha identidad (clave, huella dactilar, certificado electronico, etc.)

## Autorizacion
proceso por el cual una autoridad concede a un usuario permisos de acceso a cierto conjunto de recursos ya sean archivos, sistemas, etc.

## explicacion para mortales
Estos dos terminos los entenderas del 1 al 7. 
y con el propietario, el grupo y otros.

### sabes como leer el lenguaje binario?
mira si leemos de derecha a izquierda, uno, pues es uno, si leemos uno uno es tres,  y si leemos uno uno uno es siete.
por lo tanto, respectivamente           1 r                           3  w  x                         7 r   w   x
y otra vez aparece                  1propietario                   3grupo                         7otros
y si leo los archivos de mi carpeta de Documentos con el comando ls -la
me diria.
```
.rw-r--r-- eleache eleache  64 KB Tue Mar  8 21:12:14 2022 - \.pdf
.rw-r--r-- eleache eleache   0 B  Thu Jan 27 05:58:44 2022 - anon.txt
```
y eso que significa? Creo que con la siguiente informacion podras deducir que significa.
```
.110100100  # representacion en binario
.[110][100][100] # binario separado en 3 grupos: propietario, grupo y otros
.[421][421][421] # representacion de las posiciones equivalentes en sistema decimal
.[7][7][7] = 111 111 111 = rwxrwxrwx = Maximo nivel de privilegios.

Permisos para Propietario del archivo, Grupo al que pertenece el propietario y Otros:
        1   ejecucion 
        2   escritura
        3   escritura y ejecucion
        4   lectura
        5   lectura y ejecucion
        6   lectura y escritura
        7   lectura, escritura y ejecucion
```
Eso es el sistema de permisos del kernel linux, que hereda del lenguaje de programacion C, que tambien se lo heredo a sus semejantes Windows y MacOS. Este es un tema avanzado en compiladores, pero mucha de la seguridad moderna se ve afectada por "herencia". y no es culpa de nadie, ni de Kurt Godel, que demostro que las matematicas eran inperfectas, y si, para corregir muchos de estos problemas, hay que crear unas nuevas matematicas, y si si estan trabajando en eso, y es la nueva tabla periodica que describen las 4 fuerzas fundamentales, pero estamos hablando de informatica, no de fisica cuantica...
Con eso cubrimos el aspecto de la Autorizacion, mientras tanto la autenticacion va mas alla en nuestra sociedad, pues en algunos paises se pide un chip para identificacion de la poblacion, o se le asigna un numero en lugar de nombres a los ninos por ser muy parecidos, tal es el caso de los paises asiaticos, de donde provienen los sistemas de huella digital (Confirmo un mito occidental, en occidente no logran distinguirse ya que son muy parecidos, mas los "HAN", con todo respeto). La web 3.0 traera libertad en cuanto a Identidad, pero no estoy seguro de que las personas esten listas para cuidar de si mismas, pues en estos modernos sistemas de criptografia y cadenas de bloques, todo sera resposabilidad del usuario, es decir si olvidas la contrasena, no habra un link que diga "recuperar"... 

## como realizar tu primer hackeo etico! __ aqui y ahora __!
entra a [Online GDB](https://www.onlinegdb.com/) 
selecciona BASH como lenguaje.
copia y pega esto
```
cd .. ; cd .. ; 
ls -la; # permiso de lectura
cat /etc/passwd # usuarios autenticados del sistema
uname -a # Nombre del sistema que estas operando
```
Este breve ejercicio equivale a lo que podrias llegar a ver en un servidor comun y corriente, ya que en su mayoria son Linux, o derivados del sistema operativo Unix. La mayoria de los servidores web son derivados de Unix, y esto no es casualidad, pues mucho del desarrollo de estos sistemas proviene de la colaboracion de millones de programadores, si quieres conocer la historia te invito a escuchar el siguiente podcast: 

[Command Line Heros, Spanish version.](https://www.redhat.com/es/command-line-heroes)

RedHat, te contare algo chistoso... hace unos meses cuando trabaje con un ex-gerente de microsoft como jefe, me propuse a que trabajaria en RedHat, cueste lo que cueste, lo chistoso es que RedHat no ofrece empleo, por su modelo opensource, y si, puedo brindar soporte en nombre de RedHat, de algun modo cumpli mi meta. 
