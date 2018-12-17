## Cómo funciona internet, los protocolos y los navegadores

Internet es, resumidamente, una red de ordenadores a nivel mundial que pueden intercambiar información entre ellos a través de un protocolo común (TCP/IP).

Hemos comprado un ordenador y queremos conectarnos a internet.

###**Pasos:**

1. Un ISP (proveedor de acceso a internet: Vodafone, Orange, Telefónica...) nos conecta a internet.
2. Para conectarnos a internet nos asigna un número único a nuestro ordenador (IP) para identificarlo dentro de la red. No hay otro ordenador dentro de la misma red que tenga la misma IP que el nuestro. Una IP luce tal que así: `150.214.90.20` y viene siendo como nuestro nombre, apellidos y dirección en internet.
3. Los datos que enviamos por la red, se codifican y se enviaban a través del `modem` aunque hoy en día utilizamos `routers`.

> ¡STOP! No se si te has fijado... pero... no hemos explicado la diferencia entre modem y router. Quizás es un buen momento para, como hemos visto en la lección 1, sacar nuestra curiosidad a pasear y buscarla por nosotros mismo ;)

4. Los routers codifican y decodifican esos datos que entran y salen de nuestro ordenador, une las redes y decide las rutas de tráfico y lo hace a través del protocolo TCP/IP.

###TCP/IP y sus capas con sus protocolos:
Como hemos dicho, los datos se envían a través del protocolo TCP/IP, pero, ¿qué es? puedes ver [este vídeo](https://www.youtube.com/watch?v=JQDCL17sARA) para saberlo!

En resumen: **La arquitectura de protocolos TCP/IP está basada** en un modelo conceptual de **cuatro capas** conocido como el modelo DARPA, nombre de la agencia gubernamental de EE.UU. que desarrolló inicialmente el protocolo TCP/IP.

Las cuatro capas del modelo DARPA son:

- Aplicación
- Transporte
- Internet
- Interfaz de red

Si os fijáis habla de la capa aplicación que es la que nos interesa.

La capa de aplicación proporciona a las aplicaciones la capacidad de acceder a los servicios de las demás capas y define los protocolos que utilizan las aplicaciones para intercambiar datos. Existen muchos protocolos de capa de aplicación y continuamente se están desarrollando nuevos.

Los más utilizados son:

- Hypertext Transfer Protocol (**HTTP**): se utiliza para transferir archivos que componen las páginas Web de la World Wide Web.
- File Transfer Protocol (**FTP**): se utiliza para la transferencia interactiva de archivos.
- Simple Mail Transfer Protocol (SMTP): se utiliza para la transferencia de mensajes de correo electrónico y archivos adjuntos.
- Telnet: es un protocolo de emulación de terminal, se utiliza para iniciar la sesión de forma remota en máquinas de la red.
-

Además, dentro de la arquitectura de protocolos TCP/IP, estos otros protocolos de capa de aplicación ayudan a facilitar el uso y la gestión de redes TCP/IP:

- Domain Name System (**DNS**): se utiliza para resolver un nombre de host a una dirección IP.
- Routing Information Protocol (RIP): es un protocolo de enrutamiento que los enrutadores utilizan para intercambiar información de enrutamiento en una red IP.
- Simple Network Management Protocol (SNMP): se utiliza entre una consola de gestión de red y dispositivos de red (routers, bridges, hubs inteligentes) para recoger e intercambiar información de gestión de la red.

> HTTP, HTTPS, FTP, DNS... mmmm... ¿Buen momento para poner tus dotes de búsqueda en práctica? ;)

### Los navegadores

Los navegadores son esos programas que usamos para navegar por internet pero... ¿Cómo funcionan?
Te dejo [aquí](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) una guía standard que explica todo lo que necesitas saber.

En resumen: el navegador actúa como un cliente que contacta con el servidor y pide información. Envía una petición a al servidor a través del protocolo HTTP y el servidor envía una respuesta con el HTML, CSS y el resto de archivos al navegador.

[Volver](../README.md)
