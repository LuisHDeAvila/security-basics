# Cuando el alumno esta listo, aparece el maestro.
Me da gusto que hayas llegado hasta aqui.

### Repaso
Tal vez esto es la parte mas distintiva de la infosec, pues nunca falta el sujeto desesperado que anda buscando quien le pueda otorgar acceso al facebook de su novia.
El unico dia que podras conseguir que alguien te ayude con eso es el primero denero (p-r-i-m-e-r-o d-i-n-e-r-o).

---
### GIA: Gestion de Identidades y accesos.
Recientemente participe en un proyecto de web3, una DAP, y como siempre se me ocurrio mencionar que yo comenze como pentester.
Si me hubieran pagado si lo hubiera hecho, una auditoria "penetration testing" a Metamask, pero no me gusta explicar lo costoso que es solicitarme tal cosa, ya que es muy rentable el "bug bounty", cosa que pienso realizar por hobby una vez que tenga mi certificacion para realizar dichas auditorias sin tener problemas.
Como dije anteriormente, es mi hobby, entonces si realize algunos analisis por mi cuenta, mas que nada sobre una dificil cuestion "el mundo esta listo para ser libre?", y eso es una guerra santa, en la que no tengo interes de participar, ya no.
Esa pregunto surgio, de una de las respuestas mas frias que le eh dado a un usuario, "si pierdes el acceso, nadie podra ayudarte", en especifico: no existe la recuperacion de contrasena en un sistema de autenticacion en blockchain. Por lo que abordar este tipo de temas, es de mis prioridades al brindar una consultoria de seguridad informatica. cosa que es dificil, por tratarse de la misma identidad, en si.
A continuacion haremos un breve repaso de los modelos de control de accesos.

##### ACL
  **Lista de control de acceso.**
 El sistema consulta una lista para determinar si el usuario esta autorizado a acceder al recurso y de que manera.
  
##### RBAC
  **Control de acceso basado en roles.**
El sistema asigna uno o varios roles a un meta-usuario. Una vez asignado un rol, este es agregado a una lista de control.

##### ABAC
  **Control de acceso basado en atributos.**
Se asignan roles en base a reglas, de este modo el usuario solo podra acceder a los recursos correspondientes a su rol.

##### PBAC
  **Control de acceso basado en politicas.**
Combinacion de ABAC o RBAC con ACL. El sistema comprueba la politica de seguridad del recurso. un ejemplo de este modelo es SAML.
  
##### RADAC
  **Control de acceso adaptado al riesgo.**
El sistema calcula de manera heuristica y en base a factores externos a la identidad determina el nivel de riesgo del sistema, por lo tanto la autorizacion depende de factores como: la hora, la localizacion de la conexion, numero de intentos, cantidad de trafico, etc.

---
