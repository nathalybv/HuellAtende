## Reporte de visión

### Descripción general del software

El proyecto consiste en el desarrollo de un software para la gestión de Peticiones, Quejas, Reclamos y Sugerencias (PQRS), orientado a apoyar los procesos de atención del Movimiento Estudiantil de Perritos y Gaticos (MEPEGA) de la Universidad de Antioquia. El sistema busca facilitar el registro, almacenamiento, consulta y actualización de las solicitudes relacionadas con la atención de perros y gatos, permitiendo organizar la información de manera estructurada y eficiente.

El software contará con una interfaz de consola amigable que permitirá al administrador registrar nuevas PQRS, consultar su estado, actualizar la información correspondiente y generar estadísticas sobre los registros. Asimismo, cada solicitud tendrá un número de radicado único y consecutivo, junto con información del solicitante, el tipo de solicitud, la mascota relacionada, el campus y las fechas asociadas a su gestión.

La información será almacenada mediante archivos planos independientes para cada tipo de solicitud, facilitando su organización y consulta. Adicionalmente, el sistema permitirá generar comprobantes de radicación y realizar seguimiento a los tiempos de respuesta establecidos.

### Objetivo del software

Desarrollar un sistema de información que permita gestionar de manera organizada las PQRS relacionadas con la atención de perros y gatos en la Universidad de Antioquia, facilitando el registro, almacenamiento, consulta y seguimiento de las solicitudes, así como la generación de reportes y estadísticas que apoyen la gestión administrativa de MEPEGA.

### Beneficios del software

- **Organización de la información:** permite almacenar las PQRS de forma estructurada, clasificándolas según su tipo y facilitando su consulta.
- **Agilidad en la gestión:** facilita el registro y la actualización de las solicitudes, reduciendo la necesidad de realizar estos procesos manualmente.
- **Seguimiento de las solicitudes:** permite consultar el estado de cada PQRS y conocer sus fechas de radicación y de respuesta.
- **Control de los tiempos de respuesta:** facilita la identificación de las fechas máximas de respuesta y de las solicitudes próximas a vencer.
- **Generación de estadísticas:** permite obtener información relevante sobre los registros, sus tipos, estados y tiempos de respuesta.
- **Trazabilidad:** asigna un número de radicado único a cada solicitud, facilitando su identificación y seguimiento.
- **Apoyo a la toma de decisiones:** proporciona información organizada que puede contribuir a identificar necesidades y mejorar la gestión de las solicitudes recibidas.

En conjunto, el software busca optimizar la gestión de las PQRS de MEPEGA mediante una herramienta accesible, organizada y funcional, que contribuya al seguimiento de las solicitudes y al mejoramiento de los procesos de atención de perros y gatos en la Universidad de Antioquia.

## Especificación de requisitos del SoftWare

### Requisitos funcionales
Los requisitos funcionales definen las acciones específicas, comportamientos y operaciones que el software debe ejecutar para satisfacer las necesidades del usuario final:

* **RF01 - Registro de PQRS:** El sistema debe permitir al administrador registrar nuevas Peticiones, Quejas, Reclamos y Sugerencias, ingresando la información del solicitante, el tipo de solicitud, la mascota relacionada y el campus correspondiente.
* **RF02 - Asignación de radicado único:** El sistema debe generar y asignar de manera automática un número de radicado único y consecutivo a cada nueva solicitud ingresada.
* **RF03 - Consulta de solicitudes:** El sistema debe permitir consultar el estado, los detalles y el historial de cada PQRS mediante su número de radicado o filtros por tipo y campus.
* **RF04 - Actualización de información:** El sistema debe permitir al administrador modificar y actualizar el estado y los datos de gestión asociados a una solicitud existente.
* **RF05 - Generación de comprobantes:** El sistema debe permitir generar comprobantes de radicación para las solicitudes ingresadas.
* **RF06 - Control de tiempos de respuesta:** El sistema debe permitir realizar seguimiento a los tiempos establecidos, identificando las fechas máximas de respuesta y las solicitudes próximas a vencer.
* **RF07 - Generación de estadísticas y reportes:** El sistema debe permitir procesar los datos almacenados para generar estadísticas relevantes sobre los registros, sus tipos, estados y tiempos de respuesta.
* **RF08 - Almacenamiento en archivos planos:** El sistema debe almacenar la información de forma estructurada utilizando archivos planos independientes para cada tipo de solicitud.

---

### Requisitos no funcionales
Los requisitos no funcionales especifican criterios que pueden usarse para juzgar la operación del sistema, más allá de los comportamientos específicos, incluyendo aspectos como rendimiento, seguridad, usabilidad, fiabilidad y compatibilidad:

* **RNF01 - Usabilidad (Interfaz de consola):** El software debe contar con una interfaz de consola amigable, clara y de fácil navegación para que el administrador pueda realizar las operaciones de forma eficiente.
* **RNF02 - Confiabilidad y Persistencia:** La información almacenada en los archivos planos debe garantizar la integridad de los datos para evitar pérdidas de información de las PQRS registradas.
* **RNF03 - Rendimiento:** El sistema debe procesar las consultas, registros y la generación de reportes estadísticos de forma rápida y eficiente en un entorno de consola.
* **RNF04 - Compatibilidad:** El software debe ser compatible con entornos estándar de ejecución de código para facilitar su despliegue y uso administrativo.
* **RNF05 - Disponibilidad:** El sistema debe estar disponible para su uso local por parte del administrador del MEPEGA cada vez que se requiera gestionar una solicitud.
