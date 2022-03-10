# Introduccion al maravilloso mundo de las vulnerabilidades
## Lo que necesitas saber
Mira existen muchas explicaciones, comenzare por explicarte que hablar de codigo de programacion de computadoras, es como hablar de alicia en el pais de las maravillas. tu sabes, ese cuento donde siguio al conejo blanco a un mundo muy abstracto.
y esa es la palabra magica: ABSTRACCION. ejemplos de abstraccion: el amor, el tiempo y la muerte.

## De la abstraccion a la realidad
"bajarse del avion" es como mis amigos le dicen, y eso que algunos son cientificos biologos, es decir son chicos educados, y bien portados (naaaah). Hay uno en especial por el que me identifico como crybaby en algunos entornos. y es para representar que llevo a hellboy a donde quiera que lo vaya a necesitar, es decir Hellboy y Crybaby son canciones de lilpeeep que escogimos durante nuestro viaje a canada. dejando un sticker en el callejon de los grafitis de toronto. cerca de kensignton market, donde nos hospedamos durante 9 dias.
Hellboy, hace unos 4 anos le confese que me encontraba decepcionado de la gente, y de la realidad, que me parecia que muchas cosas no tenian sentido, y poder volver a confiar en un amigo como sucedio con el, servia como validacion de que este mundo y esta vida tenia sentido. 
```
vida+mundo=sentido; Verdadero
vida + mundo - sentido = 0; # el cero representa un punto de equilibrio, es decir [OK][TRUE] si fuera !0 seria un problema hasta para imaginarlo.

(vida+mundo)-sentido = True = 1  # Esto es realidad, que analizamos a partir de la anterior abstraccion. Verdad que se prefiere una abstraccion para comprender sus significado?
```
por lo tanto en el software encontraras algo llamado Paradigma orientado a objetos. de vez en cuando escucharas terminos como polimorfismo, o herencia.
y esque para comprender estas cualidades de los objetos hay que abstraer, ya luego lo podras traducir a codigo. pero preferiras su hablar de esto en su forma abstracta, Eso es algo que aprendi durante mi participacion en un proyecto programando con React, al intentar explicarle a mi jefe como iba a Prevenir el "HTML INYECTION y el XSS" en el input del buscador de la aplicacion.
Me respondio: "Oye, esque no puedes explicar la logica en lenguaje natural, si no sonarias como robot, suenas como robot". Me dio risa y se lo agradeci mucho, pues porfin volveria a poder platicar con seres humanos. y porfin aceptar que hay cosas que no se pueden explicar con lenguaje natural de una forma optima.

## Una vulnerabilidad comun
Es el la referencia insegura a objetos en el codigo HTML. 
Si estas en PC tecla el siguiente atajo: 
 ```
 Ctrl + U
 ```
Si estas en smartphone o algo similar, busca la aplicacion HTML VIEWER, e introduce el URL de cualquier sitio del que quieras ver su codigo HTML.
un ejemplo, es la foto de perfil de ins7agr4m, la cual se supone que no debes obtener ni permiso para guardar ni permiso para realizar zoom. Cosa que cambia cuando tienes el link de referencia directo al archivo de dicho recurso.
y este es un ejemplo de lo mas inocente, ya que seguramente la aplicacion es conciente de este hecho, y solo brinca una capa adicional por temas de usabilidad.

## Capas?
Como las munecas rusas, esas que vienen una dentro de la otra, o como shrek nos explico en su siniestra intervencion sobre las cebollas. Las capas por ejemplo en el modelo OSI brincan ABSTRACCION para comprender mejor algunas cosas complicadas. Por el momento no abordare el Modelo OSI y sus 8 capas, siendo 7 reales y la octava agregada por mi para hacer incapie en que el ser humano tambien representa un vector por el cual se ataca a las organizaciones. Ya sabes lo que dicen, No confies en nadie. (en seguridad informatica se conoce como politica ZeroTrust)
