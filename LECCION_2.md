# Leccion 2
## Sobre el lenguaje binario...
Cuando hablamos de lenguaje binario, no significa que hablemos de escribir ceros y unos (bits) en lugar de los caracteres de la lengua inglesa (ASCII), mas bien hablamos de la arquitectura con la que funcionan las computadoras contemporaneas, que de alguna forma fueron programadas, es decir, no cayeron del cielo (verdad?).
La base es el sistema binario ,que en contraste con el sistema decimal al que estamos acostumbrados a recurrir para realizar todo tipo de operaciones, siendo las mas basicas suma (adicion) y resta (sustraccion), y como dato de cultura general, usamos el sistema decimal porque tenemos 10 dedos y a nuestros antepasados les parecio mas facil trabajar en multiplos de 10, y no tampoco quiere decir que las computadoras tengan 2 dedos, pero el lenguaje binario tiene 2 simbolos para representar todo lo que vemos en nuestras pantallas digitales, al principio si se requeria la tediosa tarea de escribir esas largas cadenas de unos y ceros, pero luego a alguien se le ocurrio usar mnemotecnicos, para compactar esas cadenas de bits (instrucciones de maquina), en algo conocido como lenguaje ensamblador, luego se creo el lenguaje C, a partir de alli surgieron mas formas de representar las instrucciones, que hoy conocemos como lenguajes de programacion. Surgieron paradigmas de programacion, que son formas de resolver problemas, hasta el dia de hoy que podemos representar y digitalizar nuestra realidad mediante la abstraccion.

### en caso de que seas de los que aprenden haciendo, te dejare algo por aqui
Instrucciones: entra a [Online GDB](https://www.onlinegdb.com/) 
selecciona BASH como lenguaje. en la lista desplegable ubicada en la parte superior derecha de la interface.
Ahora introduce las siguientes lineas, y da click en [] RUN l> ]

```bash
cd .. ; cd .. ; 
ls -la; # permiso de lectura
cat /etc/passwd # usuarios autenticados del sistema
uname -a # Nombre del sistema que estas operando
whoami # tu nombre de usuario
bash -i # ahora entraste en una sesion interactiva de algo conocido como shell
help # te da una breve descripcion de los operadores disponibles en la shell
cd # volvimos a la carpeta Home de tu usuario
pwd # muestra la ruta absoluta desde la raiz
```
Mira 
Si quieres saber mas sobre que es una shell consulta el fichero llamado [LaLineadeComandos.txt](anexos/LaLineadeComandos.txt).
