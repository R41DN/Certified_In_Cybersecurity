**Dispositivos de red**

Concentrador - HUB: dispositivo **simple** que permite conectar múltiples dispositivos a una red, toma una señal de datos entrante y la retransmite a todos los dispositivos conectados a él, lo que puede causar congestión de la red y disminución del rendimiento.

**Conmutador - Switch**: dispositivo **avanzado** que conecta múltiples dispositivos en una red (mejora el rendimiento de la red), dirige el tráfico de la red sólo a los dispositivos conectados que necesitan esa información, en lugar de enviar la señal a todos los dispositivos conectados como hace un concentrador, reduciendo la congestión de la red y aumentando la velocidad de transferencia de datos.

**Enrutador - Router**: dispositivo que conecta **múltiples redes** y permite que los dispositivos en diferentes redes se comuniquen entre sí, utilizan tablas de rutas para determinar la mejor ruta para enviar los datos entre las redes conectadas.

**Firewall**: software que controla el tráfico de red en función de reglas de seguridad predefinidas.

**Servidor**: es un equipo que proporciona servicios o recursos a otros equipos o usuarios en una red (web, base de datos, correo, etc).

**Punto final**: cualquier dispositivo final en una red que tiene una dirección IP única y que se utiliza para conectarse a la red (movil, table, computadora, etc).

**IP (Protocolo de Internet)**: es una etiqueta numérica que se asigna a cada dispositivo en una red que utiliza el protocolo IP para la comunicación (dirección logica). 

- Ejemplo: 192.168.20.4

**MAC (Control de acceso al medio)**: es una dirección única asignada a la tarjeta de red de un dispositivo por el fabricante (dirección fisica). 

- Ejemplo: 00:1A:2B:3C:4D:5E
---
**MODELO OSI**

**Capa1 - Física**: transmite los bits a través de medios de comunicación como cables de red, fibra óptica o señales inalámbricas (Tipos de Ataque : SNIFFING).

**Capa2 - Enlace de Datos**: se encarga de la transferencia confiable de datos en una red (Tipos de Ataque : SPOOFING).

**Capa3 - Red**: se encarga del enrutamiento de los datos a través de una red (Protocolos: IP, ICMP, IPsec, OSPF, ARP ; Tipos de Ataque : MAN_IN_THE_MIDDLE).

**Capa4 - Transporte**: se encarga de garantizar la entrega de datos sin errores (Protocolos: TCP, UDP, TLS, SSL, SCTP ; Tipos de Ataque : DoS).

**Capa5 - Sesión**: establece, administra y finaliza las conexiones entre los host (Tipos de Ataque : HIJACKING).

**Capa6 - Presentación**: define el formato y sintaxis de los datos que se van a intercambiar (Tipos de Ataque : PHISHING).

**Capa7 - Aplicación**: permite a las aplicaciones acceder a los servicios de red (Protocolos: SMTP, TELNET, P2P, DNS ; Tipos de Ataque : EXPLOIT).

-----

**PUERTOS MÁS CONOCIDOS**

**20/21** ---> **FTP (File Transfer Protocol)**: Utilizado para la transferencia de archivos entre un cliente y un servidor FTP.
**22** ---> **SSH (Secure Shell)**: Utilizado para el acceso remoto seguro a sistemas y administración de servidores.
**23** ---> **Telnet**: Utilizado para la administración remota de sistemas.
**25** ---> **SMTP (Simple Mail Transfer Protocol)**: Utilizado para el envío de correo electrónico desde un cliente de correo a un servidor de correo.
**53** ---> **DNS (Domain Name System)**: Utilizado para la resolución de nombres de dominio en direcciones IP y viceversa.
**67/68** ---> **DHCP (Dynamic Host Configuration Protocol)**: Utilizado para asignar configuraciones de red automáticamente a dispositivos en una red.
**80** ---> **HTTP (Hypertext Transfer Protocol)**: Utilizado para la comunicación web sin cifrado.
**110** ---> **POP3 (Post Office Protocol version 3)**: Utilizado para la descarga de correo electrónico desde un servidor a un cliente de correo.
**119** ---> **NNTP (Network News Transfer Protocol)**: Utilizado para la transferencia de noticias y grupos de discusión.
**143** ---> **IMAP (Internet Message Access Protocol)**: Utilizado para la gestión y acceso remoto a correos electrónicos almacenados en un servidor.
**161/162** ---> **SNMP (Simple Network Management Protocol)**: Utilizado para la supervisión y administración de dispositivos en una red.
**443** ---> **HTTPS (Hypertext Transfer Protocol Secure)**: Utilizado para la comunicación web segura a través de SSL/TLS.
**465** ---> **SMTPS (Simple Mail Transfer Protocol Secure)**: Utilizado para el envío de correo electrónico seguro a través de SMTP mediante SSL/TLS.
**514** ---> **Syslog**: Utilizado para el envío y recepción de mensajes de registro en una red.
**1433** ---> **MS SQL Server**: Utilizado para la comunicación con Microsoft SQL Server, un sistema de gestión de bases de datos.
**3306** ---> **MySQL**: Utilizado para la comunicación con el servidor de bases de datos MySQL.
**3389** ---> **RDP (Remote Desktop Protocol)**: Utilizado para el acceso remoto a un sistema operativo Windows a través del Escritorio Remoto.

-----

**Suplantación de identidad**: es una técnica utilizada por los atacantes para hacerse pasar por otra persona, entidad o sistema con el fin de obtener acceso no autorizado a información o recursos. Un ejemplo práctico sería un atacante que envía correos electrónicos falsificados haciéndose pasar por un banco legítimo, solicitando a los destinatarios que proporcionen su información personal y bancaria.

**DoS/DDoS (Denial of Service/Distributed Denial of Service)**: tiene como objetivo sobrecargar un sistema o red, impidiendo su funcionamiento normal y negando el acceso a los usuarios legítimos. Un ejemplo práctico sería un ataque DDoS en el que múltiples dispositivos se utilizan para inundar un servidor web con un gran número de solicitudes, provocando una congestión y dejando el servicio inaccesible para los usuarios legítimos.

**Virus**: es un programa malicioso que se inserta en otros archivos o programas y se propaga al ejecutarse. Puede dañar archivos, robar información o afectar el rendimiento de un sistema. Un ejemplo práctico sería un usuario que descarga e instala un archivo adjunto de correo electrónico que contiene un virus. Al ejecutar el archivo, el virus se activa y comienza a infectar otros archivos en el sistema.

**Gusano**: es un tipo de malware que se replica y se propaga automáticamente a través de redes y sistemas sin necesidad de intervención humana. A diferencia de un virus, un gusano puede propagarse sin necesidad de infectar archivos. Un ejemplo práctico sería un gusano que se propaga a través de una vulnerabilidad en un servidor de correo electrónico, enviando copias de sí mismo a los contactos de la libreta de direcciones del usuario infectado.

**Troyano**: es un tipo de malware que se presenta como un programa legítimo pero que oculta funcionalidades maliciosas. Puede permitir el acceso no autorizado al sistema, robar información o abrir una puerta trasera para futuros ataques. Un ejemplo práctico sería un usuario que descarga e instala una aplicación aparentemente inofensiva, pero que en realidad contiene un troyano que permite a un atacante tomar el control remoto del sistema.

**Amenaza Persistente Avanzada (APT)**: es un ataque prolongado y sofisticado en el que un adversario persiste en acceder de manera continua y no autorizada a un sistema o red durante un período prolongado. Los atacantes utilizan diversas técnicas, como el phishing, la explotación de vulnerabilidades y el uso de malware personalizado. Un ejemplo práctico sería un grupo de hackers respaldados por un estado que realiza un ataque prolongado y sigiloso contra una empresa para robar información confidencial.

**Amenaza Interna**: se refiere a los riesgos y ataques que provienen de dentro de una organización, ya sea de empleados, contratistas o personal autorizado. Puede incluir el acceso no autorizado a datos, robo de información o sabotaje. Un ejemplo práctico sería un empleado descontento que accede intencionalmente a los sistemas de la empresa y borra o modifica datos críticos.

**Malware**: es un término general que engloba a diversos tipos de software malicioso, como virus, gusanos, troyanos, ransomware, spyware, entre otros. Su objetivo principal es causar daño, robar información o comprometer la seguridad de un sistema. Un ejemplo práctico sería un usuario que descarga e instala un software de apariencia legítima, pero que en realidad contiene un malware que roba contraseñas y datos personales del usuario.

**Secuestro de datos**: también conocido como ransomware, es un tipo de ataque en el que un malware cifra los archivos de un sistema y exige un rescate para su liberación. Los atacantes solicitan un pago para proporcionar una clave de descifrado y restaurar el acceso a los datos. Un ejemplo práctico sería un usuario que abre un archivo adjunto de correo electrónico que contiene ransomware, y como resultado, todos sus archivos personales se cifran y se le exige un pago para recuperarlos.

-----

**SOLUCIONES DE SEGURIDAD**

**SIEM (Security Information and Event Management)** : recopila y analiza datos de seguridad de diferentes fuentes para identificar patrones y amenazas de seguridad.

**IDS (Intrusion Detection System)** : monitorea la red en busca de actividades maliciosas o sospechosas.Detecta casos como intentos de acceso no autorizado, escaneo de puertos, DoS, entre otros.

**IPS (Intrusion Prevention System)** : tiene la capacidad de bloquear y prevenir los ataques detectados.
Esto lo puede hacer generando alertas, modificando las reglas de seguridad de la red, incluso puede bloquear tráfico malicioso.

**EDR (Endpoint Detection and Response)** : monitorea y responde a actividades maliciosas en los endpoints (computadoras,dispositivos moviles).Puede detectar amenazas avanzadas y proporciona respuestas automatizadas para evitar daños mayores.

----

**PREVENCIÓN DE AMENAZAS**

- Mantener actualizados los sistemas y las aplicaciones
- Elimine o deshabilite los servicios y protocolos innecesarios
- Utilizar sistemas de detección y prevención de intrusos
- Utilice un software antimalware actualizado
- Utilice cortafuegos