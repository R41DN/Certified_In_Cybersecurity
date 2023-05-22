Un control de seguridad es un conjunto de medidas implementadas para proteger la triada CID contra amenazas, vulnerabilidades y riesgos de seguridad. 

El acceso se basa en 3 componentes:

**Sujeto**: es el usuario o la entidad que intenta acceder a un objeto.
- Es un usuario, un proceso, un procedimiento, un cliente (o un servidor), un programa, un dispositivo como un punto final, una estación de trabajo, un teléfono inteligente o un dispositivo de almacenamiento extraíble con firmware integrado.
- Está activo: Inicia una solicitud de acceso a recursos o servicios.
- Solicita un servicio de un objeto.
- Debe tener un nivel de autorización (permisos) que se relacione con su capacidad para acceder con éxito a servicios o recursos.

**Objeto**: es el recurso al que se está intentando acceder.

Un objeto:

- Es un edificio, una computadora, un archivo, una base de datos, una impresora o un escáner, un servidor, un recurso de comunicaciones, un bloque de memoria, un puerto de entrada/salida, una persona, una tarea de software, un hilo o un proceso.
- Es todo aquello que presta servicio a un usuario.
- Es pasivo
- Responde a una solicitud.

**Reglas**: son las políticas y permisos que rigen el acceso.

- Compare múltiples atributos para determinar el acceso apropiado.
- Permitir el acceso a un objeto.
- Defina cuánto acceso está permitido.
- Denegar el acceso a un objeto.
- Aplicar acceso basado en el tiempo.

Ejemplo:

**Sujeto** ---> Equipo de contabilidad 
**Objeto** ---> Base de datos financiera 
**Reglas** ---> El equipo de contabilidad tiene permisos de acceso de solo lectura a la base de datos financiera.

**Defensa en Profundidad**: es una estrategia que consiste en utilizar múltiples capas de protección (personas, tecnología y capacidades operativas) para asegurar los sistemas de información y minimizar el impacto de posibles ataques. 

**Principio de Mínimo Privilegio**: es un estándar que permite solo el acceso mínimo necesario para que los usuarios o programas cumplan su función. A los usuarios se les proporciona acceso solo a los sistemas y programas que necesitan para realizar su trabajo o tareas específicas.

**Cuentas Privilegiadas**: son aquellas que tienen acceso a recursos y datos confidenciales en una organización, por lo que su uso indebido o abuso puede ser un riesgo elevado para la seguridad informática.

- Administradores de sistemas, que tienen las responsabilidades principales de los sistemas operativos, la implementación de aplicaciones y la gestión del rendimiento.
- El personal de la mesa de ayuda o de soporte de TI, que a menudo necesita ver o manipular puntos finales, servidores y plataformas de aplicaciones mediante operaciones privilegiadas o restringidas. 
- Analistas de seguridad, que pueden requerir un acceso rápido a toda la infraestructura de TI, los sistemas, los puntos finales y el entorno de datos de la organización.

Para moderar este riesgo, se utilizan medidas típicas que incluyen:

- Registro más extenso y detallado: es importante registrar todas las acciones realizadas por las cuentas privilegiadas, tanto como elemento disuasorio como para auditar y revisar los registros en caso de detectar actividades maliciosas. 

  - Ejemplo: Registros detallados de las acciones realizadas por un administrador de sistemas en un servidor crítico de la organización.

- Control de acceso más estricto: los usuarios privilegiados deben pasar por una autenticación adicional o más rigurosa antes de acceder a los recursos y datos confidenciales. La identidad justo a tiempo también debe considerarse como una forma de restringir el uso de estos privilegios a tareas específicas y momentos específicos. 

  - Ejemplo: Un administrador de bases de datos que debe proporcionar credenciales adicionales y autenticarse mediante un token de seguridad antes de acceder a los datos confidenciales.
 
- Verificación de confianza más profunda: los titulares de cuentas privilegiadas deben estar sujetos a verificaciones de antecedentes más detalladas, acuerdos de confidencialidad más estrictos y políticas de uso aceptable, y estar dispuestos a someterse a una investigación financiera. 

  - Verificación de antecedentes detallados y evaluación de la confiabilidad de un administrador de seguridad antes de concederle acceso a los sistemas críticos.

La segregación de funciones es una práctica de seguridad informática que implica dividir las responsabilidades y funciones de una organización para evitar que una sola persona tenga acceso y control completo sobre un proceso o sistema. El objetivo es prevenir fraudes, errores, manipulaciones y malas prácticas.

Algunos ejemplos prácticos de segregación de funciones son los siguientes:

- En una empresa, el equipo de compras no debería tener la responsabilidad de aprobar los pagos. Debería haber un equipo de cuentas por pagar separado que revise las facturas y apruebe los pagos para garantizar que no haya fraude o malversación de fondos.
   
- En una empresa de desarrollo de software, el equipo de desarrollo no debería tener acceso a los servidores de producción. Debe haber un equipo de operaciones separado que administre y controle los servidores de producción para evitar cualquier manipulación no autorizada.
   
- En una organización gubernamental, el equipo de auditoría interna no debería tener la responsabilidad de realizar auditorías de las áreas en las que trabajan ellos mismos. Debe haber un equipo de auditoría externo que realice las auditorías para garantizar la objetividad y la imparcialidad.

---

**Controles de acceso físico**: son mecanismos físicos implementados para prevenir, monitorear o detectar el contacto directo con sistemas o áreas dentro de una instalación.

-   Cerraduras en puertas y ventanas
-   Cámaras de vigilancia
-   Control de acceso físico con tarjetas de identificación
-   Almacenamiento en armarios con llave o salas de seguridad con protección contra incendios

---

**Controles de acceso lógico**

**Controles de acceso discrecional** (DAC): es un modelo que permite a los propietarios de recursos (archivos, carpetas, etc.) decidir quién tiene acceso a ellos y cómo se puede acceder a ellos.

- Permisos en linux

**Controles de acceso obligatorio** (MAC): el administrador de seguridad son los que controlan el acceso a los recursos.

Cada recurso tiene una etiqueta de seguridad que indica el nivel de clasificación o sensibilidad del recurso. Los usuarios y procesos también tienen etiquetas de seguridad asignadas que indican su nivel de autorización.

- SELinux/AppArmor

**Controles de acceso basado en roles** (RBAC): los permisos de acceso a los recursos se otorgan en función del rol o posición del usuario dentro de la organización.

- En una empresa, los empleados del departamento de Recursos Humanos tienen acceso solo a los datos de recursos humanos, mientras que los empleados del departamento de Finanzas tienen acceso solo a los datos financieros.
- En un sistema de gestión de contenido, los autores de contenido tienen permisos de edición y publicación, mientras que los usuarios anónimos solo tienen permisos de lectura.

---
