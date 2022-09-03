# Seguridad informatica para todos
## KISS: Keep It Simple, Stupid!
Mi intencion es que abordemos los temas de la forma mas simple posible, porque el principal enemigo de la seguridad es la complejidad. La leccion 3 es un cuestionario originalmente de la CIA, pero te lo traigo en un formato mas digerible con la intencion que lo puedas implementar en tu entorno: tu empresa, tu familia, tu comunidad, tu club social, tu taller, etc...
Entonces para llegar a tener una comprension util en la seguridad informatica, es necesario tener los fundamentos bien definidos, porque algo que eh notado principalmente en el area informatica, es que existen muchos "falsos amigos" como consecuencia del marketing (y de la ingenieria social).
Porque los sistemas que nos rodean en la actualidad, se basaron en la ocultacion, argumentando que el usuario no tiene porque estar enterado del funcionamiento real de las cosas, suponiendo que las cosas funcionan bien, pero, nada es para siempre y la seguridad implica uno de los factores mas criticos para el desarrollo del ser humano, entonces tal vez deban replantear esos principios que insisten en ocultar y como prueba de eso, los modulos de seguridad mas criticos estan dentro del microchip que conocemos como CPU/Procesador, que probablemente tenga su propio sistema operativo dentro (minix).

## Autorizacion y Autenticacion
### Autenticacion
Es el proceso de demostrar la posesion de una identidad determinada presentando uno o varios atributos de dicha identidad (clave, huella dactilar, certificado electronico, etc.)

### Autorizacion
proceso por el cual una autoridad concede a un usuario permisos de acceso a cierto conjunto de recursos ya sean archivos, sistemas, etc.

### Lenguaje Binario
Es la forma mas simple de representar la informacion.

### como realizar tu primer hackeo etico! __ aqui y ahora __!
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
