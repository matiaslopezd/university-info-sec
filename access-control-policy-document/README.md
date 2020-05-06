# **POLÍTICA DE CONTROL DE ACCESO**

![Company Logo](https://raw.githubusercontent.com/vadymmarkov/Fakery/master/Images/logo.png)

# Índice

**[Declaración institucional](#_gjdgxs)**

**[Objetivo del documento](#_1fob9te)**

[Objetivo General](#_3znysh7)

[Objetivos específicos](#_2et92p0)

**[Alcance o ámbito de aplicación interno](#_2l3lo3buymo5)**

**[Roles y Responsabilidades](#_f2xt536dg8ay)**

**[Control Normativo](#_v3gnt63zpp2s)**

[Utilización de los servicios de red](#_4d34og8)

[Autentifación de usuarios para conexiones externas](#_2s8eyo1)

[Identificación de equipos en la red](#_17dp8vu)

[Protección de los puertos de configuración y diagnóstico remoto](#_3rdcrjn)

[Separación de redes](#_26in1rg)

[Control de conexión de las redes](#_lnxbz9)

[Administración del acceso de usuarios](#_35nkun2)

[Responsabilidades de los usuarios](#_1ksv4uv)

[Control de acceso de sistemas y aplicaciones](#_44sinio)

[Uso de utilidades del sistema](#_2jxsxqh)

[Computación móvil y trabajo remoto](#_z337ya)

[Procedimiento de inicio de sesión seguro](#_3j2qqm3)

**[Evaluación y seguimiento de la política](#_1y810tw)**

**[Difusión](#_4i7ojhp)**

**[Control de versiones](#_2xcytpi)**

**[Glosario y terminología](#_3whwml4)**

[Atribuciones](#atribuciones)

# Declaración Institucional

Fakery se compromete, de acuerdo con su misión y sus valores a mantener y mejorar la seguridad de la información y la continuidad de su actividad como mutua, dentro del marco legislativo vigente.

La Política de Seguridad de la Información de Fakery está orientada a garantizar la protección de todos los activos de información y la tecnología utilizada para su tratamiento, de las amenazas internas o externas, deliberadas o accidentales, con el fin de asegurar su integridad, disponibilidad y confidencialidad, favoreciendo el eficiente cumplimiento de los objetivos estratégicos de la entidad. Para apoyar la política, Fakery dispone de un Sistema de Gestión de Seguridad de la Información (SGSI) impulsado por la Dirección, que aporta un enfoque sistemático para la gestión de riesgos.

# Objetivo del documento

La política de seguridad de la información comprende un conjunto de directrices, normas y procedimientos documentados que regulan la forma en que se deben dirigir, proteger y distribuir los recursos informáticos de la empresa para llevar a cabo los objetivos de seguridad de la misma.
## Objetivo General
Fakery busca en este documento crear normativas para una gestión de la seguridad de la información mediante diferentes marcos normativos y conductuales ya sea de forma preventiva, ataques, desastres o emergencias.

## Objetivos Específicos

1. Proveer a los usuarios y equipos las directrices, normas y procedimientos que deben cumplir y utilizar para proteger los elementos de hardware y software de la plataforma tecnológica de servidores y comunicación de la empresa, así como la información que es procesada y almacenada en éstos.
2. Proteger los activos de información empresarial frente a amenazas, internas o externas, sean ellas deliberadas o accidentales, con el fin de asegurar el cumplimiento de la confidencialidad, integridad, disponibilidad, legalidad y confiabilidad de la información que estos recursos generan.
3. Mantener actualizadas las normativas y responsabilidades a efectos de asegurar su vigencia y nivel de eficacia.
4. Implementar acciones conducentes a optimizar y actualizar las tareas cotidianas, de normas y procedimientos que permitan transmitir adecuadamente el proceder en cada situación.

# Alcance o ámbito de aplicación interno

La presente política de seguridad se aplica a todas las empresas que componen el grupo de empresas Fakery y a sus sistemas y activos de información:

- A todos los departamentos, tanto a sus directivos como a empleados.
- A los contratistas, clientes o cualquier otra tercera parte que tenga acceso a la información o los sistemas de la organización.
- A bases de datos, ficheros electrónicos y en soporte papel, tratamientos, equipos, soportes, programas y sistemas.
- A la información generada, procesada y almacenada, independientemente de su soporte y formato, utilizada en tareas operativas o administrativas. 

# Roles y responsabilidades
Cumpliendo con los objetivos se definieron los siguientes roles y responsabilidades: 

- CTO: Responsable de aprobar la política de seguridad de la información y sus modificaciones en conjunto con el equipo SecOps.
- SecOps: El equipo se reunirá en forma mensual y/o en función de las contingencias que requieran, siendo indispensable que se registre las actividades y temáticas generandas durante las reuniones.

# Control Normativo
La información debe estar protegida contra accesos no autorizados. El responsable del servicio definirá las necesidades de acceso a la información a dos niveles, para el conjunto de áreas y las de cada usuario dentro del conjunto. Sólo se facilitará el acceso a la información necesaria para el trabajo a desarrollar.

# Reglas para el control de acceso
Para un correcto uso de los activos de Fakery por parte de su equipo o externos se definen las siguientes reglas para un control de acceso basado en los activos a utilizar.
### Acceso a redes y servicio de red
Para accesar a la red o servicios en esta, se deberá solicitar mediante el encargado de red asigando en caso de existir acceso local. En caso de requerir accesar de forma remota se realizará mediante VPN con credenciales entregadas por el mismo encargado.

### Control de acceso a la red
Para realizar conexiones a la red deberá contar con un usuario y contraseña en el caso de forma externa, en el caso local deberá utilizar solamente el equipo asignado o solicitado para tener acceso mediante su dirección MAC.

### Utilización de servicios de red
El acceso a la red será restringido por servicio como firewalls, analizadores de contenido (bloqueadores) u otros sistemas, software o hardware que provea la capacidad de mitigar, filtrar y asegurar que el tráfico no provenga o diriga con fines maliciosos o inseguros.

### Autentificación de usuarios para conexiones externas

En el caso de acceso externo el usuario deberá disponer de un usuario y contraseña para conectarse nuestra VPN. Queda estrictamente prohibido conectarse mediante VPN en redes públicas como cafés, centros comerciales, redes desconocidas en general.

### Identificación de equipos en la red
Para realizar incorporación de nuevos equipos a la red, estos deberán ser identificados mediante su dirección MAC.

### Protección de los puertos de configuración y diagnóstico remoto

 Queda estrictamente prohibido implementar soluciones de acceso remoto a equipos con Windows mediante la herramienta "Escritorio Remoto". Para implementaciones de soluciones de diagnóstico o acceso remoto se podrá utilizar solciones como VNC u otros.

### Separación de redes
En las redes de Fakery se segmentarán por equipos de trabajo. Es decir, cada equipo en la empresa tendrá un acceso a Internet segmentado de los demás evitando cruce de tráfico interno. Queda estrictamente prohibido acceso de equipos de trabajos ajenos a la red de los equipos de tecnología y seguridad.

### Administración de acceso a usuarios
La administración de acceso de usuarios se administrará mediante el método LDAP para cualquier plataforma interna de la empresa. La persona encargada deberá velar la seguridad de los accesos de alto nivel.

### Responsabilidad de los usuarios
Los usuarios indistintamente de los equipos de trabajo, deberán velar por sus credenciales de acceso. Queda estrictamente prohibido almacenar usuarios y contraseñas en otros métodos diferentes a los siguientes:

- LastPass Enterprise

### Control de acceso de sistemas y aplicaciones
Para accesar a las aplicaciones y sistemas de la empresa se utilizará el método LDAP, que permite centralizar bajo un mismo usuario y contraseña el acceso a diferentes servicios ya sea de red o software.

### Uso de utilitarios del sistema
La red de la empresa se utilizará solo con fines laborales en su gran medida, esto no restringe acceso a plataformas de redes sociales u otro tipo de plataformas cloud o web. Queda prohibido acceso a redes TOR o similares, a excepción del equipo de seguridad o en caso de existir una autorización por parte del CTO.

### Computación móvil y trabajo remoto
Para el trabajo remoto se utilizará conexiones a redes locales de la empresa en caso de ser necesario mediante una VPN.

### Procedimiento de inicio de sesión seguro
Referenciar a _Autentificación de usuarios para conexiones externas_

# Evaluación de seguimiento y de la política
El sistema de gestión de seguridad de la información (SGSI) dispone de un programa de auditoría interno para la revisión del cumplimiento de la política de seguridad. Fakery se somete sistemáticamente, cada un año a una auditoría mediante agentes externos para comprobar seguir estándares impuestos en este documento. 

# Difusión
La Política de Seguridad de la Información debe ser conocida por todos los empleados, así como aquellos que colaboren con Fakery. Debe comunicarse a toda la empresa y encontrarse disponible en los medios accesibles por todos los empleados.

Además se realizarán charlas mensuales y anuales con diferentes contextos basados en los diferentes equipos pertenecientes a la empresa, con el objetivo de retroalimentar una cultura sobre la seguridad de la información.

# Control de versiones

| Versión | Fecha de Aprobación |  Motivo del cambio   |     Autor     |
| :-----: | :-----------------: | :------------------: | :-----------: |
|   1.0   | 05 de Mayo del 2020 | Inicio del documento | @matiaslopezd |

# 10. GLOSARIO Y TERMINOLOGÍA

Para los propósitos de esta Política, se entenderá por:

**Acceso a la información:** El acceso a la información es el derecho de acceder a las informaciones contenidas en actos, resoluciones, actas, expedientes, contratos y acuerdos, así como a toda información elaborada con presupuesto público, cualquiera sea el formato o soporte en que se contenga, salvo las excepciones legales.

**Derechos de accesos:** Conjunto de permisos dados a un usuario, de acuerdo con sus funciones, para acceder a un determinado recurso.

**Restringir el acceso:** Delimitar el acceso de los funcionarios, servidores públicos a honorarios y terceras partes a determinados recursos.

**Sanción:** Puede ser definida como la consecuencia administrativa, civil o penal por el incumplimiento del deber que produce en relación con el obligado.

**Sistema informático:** Uno o más computadores, software asociado, periféricos, terminales, procesos físicos, medios de transferencia de información y otros, que forman un todo autónomo capaz de realizar procesamiento de información y/o transferencia de información.

**Usuario:** Persona que utiliza un sistema informático y/o recibe un servicio, tales como: correo electrónico o red de conectividad proporcionado o administrado por el Instituto Nacional de Estadísticas, ya sea que lo utilice en virtud de un empleo, de una función o de cualquier prestación de servicio, sin importar la naturaleza jurídica de ésta o del estatuto que lo rija.

**Documento electrónico:** Toda representación de un hecho, imagen o idea que sea creada, enviada, comunicada o recibida por medios electrónicos y almacenada de un modo idóneo para permitir su uso posterior.

**Documento público:** Aquellos documentos que no son ni reservados ni secretos y cuyo conocimiento no está circunscrito.

**Documento público reservado:** Es aquel documento cuyo conocimiento está circunscrito al ámbito de la respectiva unidad del órgano a que sean remitidos, en virtud de una ley o de una norma administrativa dictada en conformidad a ella, que les confiere tal carácter.

**Documento electrónico institucional:** Documento electrónico creado, enviado, comunicado o recibido, por los usuarios del Instituto Nacional de Estadísticas, en ejercicio de las funciones propias de la institución.

**Servicios de Red:** Son todos los servicios a los que un usuario puede acceder a través de la red. Típicamente se refieren a aplicaciones disponibles en sitios web internos (Intranet) o en la Internet, acceso a discos compartidos, servicios de impresión, etc.

**UID:** Identificador único numérico o alfanumérico asociado a un solo ente dentro de un sistema informático. Permite al sistema identificar en forma única dicho ente para interactuar con él en base a los permisos de uso, roles, funciones, restricciones, etc. que se definieron previamente para él.

**Utilitario:** Software del sistema diseñado para apoyar en el análisis, configuración, optimización, y mantenimiento de una o más tareas propias de la infraestructura de equipo computacional.

**Seguridad del documento electrónico.** La seguridad del documento electrónico se logra garantizando los siguientes atributos esenciales del documento: Integridad, disponibilidad y confidencialidad.

**Activos de información:** Son todos aquellos elementos relevantes en la producción, emisión, almacenamiento, comunicación, visualización y recuperación de información de valor para la Institución cualquiera sea el formato que la contenga y los equipos y sistemas que la soporten. Por ejemplo: dispositivos móviles, tarjetas de accesos, software, equipamiento computacional.

**Riesgo:** Es la contingencia de un daño a un activo de información. A su vez, contingencia significa que el daño puede materializarse en cualquier momento o no suceder nunca.

**Amenaza:** Causa potencial de un incidente no deseado por el cual puede resultar dañado un sistema u organización. A modo de ejemplo, terremotos, inundaciones, sabotajes, amenazas de bombas, negligencias humanas, cortes eléctricos, fallas en sala de servidores, entre otras.

**Gestión del riesgo:** Proceso definido para identificar, evaluar, manejar y controlar acontecimientos o situaciones potenciales, con el fin de proporcionar un aseguramiento razonable respecto al alcance de los objetivos de la organización. Es un proceso iterativo que debe contribuir a la mejora organizacional a través del perfeccionamiento de los procesos.

**Evaluación del riesgo:** Comparar los niveles de riesgo encontrados contra los criterios de riesgo preestablecidos (si es que han sido establecidos por la Dirección) considerando el balance entre los beneficios potenciales y resultados adversos. Ordenar y priorizar mediante un ranking los riesgos analizados.

**Seguridad de la Información:** Es el proceso encargado de asegurar que los recursos de un sistema de información sean utilizados de la manera que se decidió y que el acceso a la información allí contenida, así como su modificación, sólo sea posible a las personas que se encuentren acreditadas y dentro de los límites de su autorización, preservando la Integridad, Confidencialidad y Disponibilidad.

**Proceso:** Conjunto de actividades o eventos que se realizan o suceden (alternativa o simultáneamente) con un fin determinado.

**Incidente de Seguridad:** Se define incidente como cualquier evento o situación que comprometa de manera importante la disponibilidad, integridad y confidencialidad de la información, junto con la plataforma tecnológica, proceso y aplicativos que permitan acceder a ésta en forma oportuna. En general, es una violación de una política, estándar o procedimiento de seguridad, que no permite prestar un servicio computacional.

Como ejemplos de incidentes de seguridad podemos enumerar:

- Acceso no autorizado.

- Robo de contraseñas.

- Robo de información.

- Denegación de servicio.

- Robo y extravío de un medio de procesamiento de la información.

**Confidencialidad:** es asegurar que la información es accesible sólo para las personas autorizadas para ello.

**Integridad:** Es salvaguardar la exactitud y totalidad de la información en su procesamiento, transmisión y almacenamiento.

**Disponibilidad:** es asegurar que los usuarios autorizados tengan acceso a la información y los activos asociados cuando estos sean requeridos.

**Medios de procesamiento de información:** Los dispositivos internos y/o externos que tenga la capacidad de procesar información, almacenarla y que se encuentren disponibles para ser manipulados por el usuario.

Como ejemplos de medios de procesamiento de información, podemos enumerar:

Servidores de aplicaciones:de correo, de impresión, aplicaciones web.

- Servidores de Almacenamientos.

- Computadores personales.

- Discos duros externos

- Pendrives.

- Teléfonos móviles.

**Operaciones informáticas:** Son todas las actividades que estén relacionadas con un sistema informático y/o procesamiento de la información.

Como ejemplos de operaciones informáticas podemos enumerar:

- Configuración de servidores y estaciones de trabajo.

- Configuración de equipos de comunicación que conectan a los usuarios a la red.

- Creación y/o retiro de acceso a los medios de procesamiento de información.

- Mantención de base de datos de los sistemas.

- Respaldo de la información de servidores y estaciones de trabajo.

**Terceras partes:** Son todas las personas u organismo reconocidos como independiente de las partes implicadas en lo que se refiere a la materia en cuestión. Para este procedimiento, se entenderá como terceras partes a:

- Proveedores de servicios y de red.

- Proveedores de productos de software y servicios de información.

- Outsourcing de instalaciones y operaciones.

- Servicios de asesoría de seguridad.

- Auditores externos.

**Estación de Trabajo:** Es un computador que facilita a los usuarios el acceso a los servidores y servicios de la institución.

**Programa malicioso:** Es un tipo de software que tiene como objetivo infiltrarse o dañar una computadora sin el consentimiento de su propietario.

**APT:** Amenaza tecnológica persistente:

**Virus:** Se usa para designar un programa que, al ejecutarse, se propaga infectando otros softwares ejecutables dentro de los equipos computacionales.

**Malware:** El término malware es muy utilizado para referirse a una variedad de software hostil, intrusivo o molesto. El término malware incluye virus, gusanos, troyanos, la mayor parte de los rootkits, scareware, spyware, adware intrusivo, crimeware y otros softwares maliciosos e indeseables.

**SPAM:** Se llama spam al correo o mensaje basura, a los mensajes no solicitados, no deseados o de remitente no conocido.

# Atribuciones

> Se concede permiso para copiar, distribuir, y/o modificar este documento bajo los términos de la Licencia de Documentación Libre GNU, en su versión 1.3, o cualquiera de las versiones publicadas de manera posterior por la Free Software Foundation; sin Secciones invariantes (invariant sections), sin Textos de Portada (front-cover texts), y sin Textos de Contratapa (back-cover texts). Una copia de esta licencia se incluye en la sección &quot;Licencia de documentación libre GNU&quot;.

**Documento base creado por Sebastian Vargas**

