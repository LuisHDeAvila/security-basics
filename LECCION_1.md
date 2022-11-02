# Antes de empezar...
Esta informacion es compartida con fines educativos, no me hago responsable por el malhuso que se pueda hacer de la misma.
este repositorio tiene la intencion de ser una guia conceptual.
--
## Definiciones que se usaran a lo largo de este mini-blog.
#### Que es seguridad informatica?
A lo largo de los años, hemos escuchado que los hackers son cada vez mas sofisticados y poseen mayor numero de herramientas para atacar los sistemas informaticos, y es cierto, pero tambien lo es el hecho de cada vez se tiene mas concientizacion en las empresas y por parte de los usuarios, lo que hace que exista cada vez mayor concentracion de contramedidas.
#### Que es cyber-seguridad?
hemos escuhado ininterrumpidamente en las noticias, en la prensa, en la television... el sufijo "cyber" acompañado de terminos como amenaza, delincuencia, seguridad, guerra. Si queremos saber la etimologia de este sufijo, tenemos que recurrir al griego que lo traduciria como "arte de gobernar una nave".
Simplemente, Cyberseguridad: "es el conjunto de metodos procedimientos y herramientas que nos permiten proporcionar seguridad a los sistemas, redes, dispositivos, software, servicios.Y por lo tanto es un requisito previo para que personas, empresas y administraciones puedan desarrollar su actividad en este entorno."

#### Que es un "Hacker"?
Segun la RAE, hacker es: "Persona con grandes habilidades en el manejo de computadoras que investiga un sistema informático para avisar de los fallos y desarrollar técnicas de mejora."
El "hacker" de hollywood la mayoria del tiempo corresponde a un cyber-terrorista, el "Hacker" del M.I.T. era el que solucionaba los errores de los primeros modems, dando un golpe sobre la carcasa del mismo, generando un sonido que se podria expresar como "hack! hack!" y asi podria realizar una larga lista de diferentes definiciones o enfoques derivados de la palabra con la que buscamos describir a una serie de sujetos que se describen a si mismos de la siguiente forma:
```
[…]

Este es nuestro mundo ahora…
El mundo del electrón y el conmutador, la belleza del baudio.
Hacemos uso de un servicio que ya existe sin pagar,
por que podría ser ridículamente barato,
como el polvo, si no estuviera en manos de glotones hambrientos de ganancias,
y ustedes nos llaman criminales.

Nosotros exploramos…
y ustedes nos llaman criminales.
Nosotros buscamos detrás del conocimiento…
y ustedes nos llaman criminales.
Nosotros existimos sin color, sin nacionalidad, sin prejuicios religiosos…
y ustedes nos llaman criminales.

Ustedes construyen bombas atómicas,
ustedes hacen la guerra,
asesinan, engañan y nos mienten
y tratan de hacernos creer que es por nuestro bien,
ahora nosotros somos los criminales.

Si, soy un criminal.
Mi crimen es la curiosidad.
Mi crimen es el juzgar a las personas por lo que dicen y piensan, no por como se ven.
Mi crimen es ser mucho más inteligente que ustedes, algo por lo cual jamás podrán perdonarme.

Soy un Hacker, y este es mi manifiesto.

Pueden detener a este individuo, pero no podrán detenernos a todos…
después de todo, todos somos iguales.

[…]
# from: [fwhibbit](https://fwhibbit.es/manifiesto-bienvenidos-a-fwhibbit): Follow the white rabbit...
```

#### Cualidades de la seguridad informatica
Ya que se hizo contraste entre los terminos cyber-seguridad y seguridad informatica, dentro de esta ultima hay una triada de cualidades que nos importan como responsables de la informacion.
- Confidencialidad (no es lo mismo que privacidad)
- Integridad
- Accesibilidad
Esta ultima es la mas importante, ya que sin tener acceso a la informacion, no podemos concebir la integridad, ni la confidencialidad, a la perdida de accesibilidad le llamamos denegacion de servicio (Denial Of Service) que comunmente se le hace referencia con las siglas DDOS (Distribuited Denial of Service), sin embargo no todas las D.O.S. provienen de un ataque distribuido, por ejemplo en los primeros ordenadores como Windows 95 existia una vulnerabilidad conocida como "Ping de la Muerte" (algunas instituciones siguen utilizando este sistema operativo en sus instalaciones, como hospitales).

#### Script-kiddie, Cracker y Phracker
Script-kiddie: se trata de usuarios con bajos o nulos conocimientos en programacion y desconoce el funcionamiento de las cosas que ejecuta scripts o programas para explotar vulnerabilidades conocidas (las vulnerabilidades pueden ser descubiertas o creadas por un atacante). La mayoria son aficionados motivados a llamar la atencion, y muchas de las veces sufren consecuencias por ejecutar programas desarrollados con malas intenciones que prometen hacer todo tan facil como presionar un boton (scam).

Cracker: Cyber-delincuente.

Phracker: Son antecesores de los hackers, comenzaron a explotar vulnerabilidades de sistemas de telecomunicaciones desde tiempos remotos. hoy en dia se considera altamente ilegal violar la seguridad de los sistemas de telecomunicaciones, por lo que no se encuentra mucho de este tema por la web, es mas comun en grupos de noticias o IRC (internet relay chat), sin embargo un tema facil de encontrar desde un motor de busqueda es: "Blue box".

#### La seguridad informatica es muy extensa...
Una forma de poder interpretar la inmensidad de temas y conocimiento que abarca la seguridad informatica, es tener en claro el modelo OSI. Al navegar por la web, podemos acceder al contenido con tanta facilidad gracias a que tenemos conexion de internet por medio de una red inhalambrica wifi (802.11), o por medio de un cable Ethernet[2], que solo estan compuestos por cobre, o fibra optica para conexiones de mayor velocidad [1]. Se nos asigna una direccion IP[3] principalmente por parte de un proveedor de internet o ISP. Y para mantener los flujos de bites que nos permiten ver videos, descargar musica, o revisar el correo electronico [7], establecemos una conexion TCP [4], desde nuestro ordenador [5], smartphone, televisor inteligente, incluso hoy en dia podemos hablar de refrigeradores que poseen conexion a internet, si te preguntas al igual que yo el motivo de esta caracteristica en aparatos que ni siquiera tienen un uso fundamental de conectividad, solamente debemos comprender que de manera informal, la capa 8 no-oficial del modelo OSI trata de todo lo que tiene que ver con el humano, y sus vulnerabilidades (que por supuesto existe el area de ingenieria social directamente dedicada a la explotacion de vulnerabilidades de las personas).
LAS 7 CAPAS DEL MODELO OSI y algunos de sus protocolos:
    7. APLICACION: Telnet, Ftp (file transfer protocol), SNMP, NNTP, SSH, POP3, DNS, NFS, HTTP
    6. PRESENTACION: ASN.1
    5. SESION: NetBIOS
    4. TRANSPORTE: TCP, UDP
    3. RED: ARP, IP(IPv4/IPv6), ICMP, X.25
    2. ENLACE DE DATOS: ETHERNET, GIGABIT, ATM, HDLC
    1. FISICA: MIME, IEEE, CGI
