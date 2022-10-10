### DESCRIPCION GENERAL DEL REQUERIMIENTO 

| PROYECTO                                                                     | Abogabot|
|---                                                                           |---|
| Nombre Requerimiento:                                                        | Creacion de sitio web. |
| Fecha Solicitud:                                                             | 01/10/2022 |
|  Responsable(s) Solicitante:                                                 | LaunchX |
|Dependencia(s) Solicitante:                                                   | Desarrollo de Software|
|Responsable Funcional designado <br />por el equipo de desarrollo de software:|Alejandro Reyes Cerecero |
___
### FASE DE FORMALIZACION
| Descripcion de la Solicitud  |
|---|
| Usuario Solicitante  |
| Crear una pagina web donde los clientes puedan hacer la creacion, modificacion y seguimiento de sus casos, haci como el pago correspondiente de los mismos. Los administradores del sitio deberan ser capaces de recibir el pago por parte de los clientes, actualizar los casos y recibir notificaciones.  |
|  Lider Funcional |
| Creacion de un sitio web en donde los clientes de la firma puedan ser capaces de llenar un formulario cuando estan interesados en realizar un movimiento legal, los usuarios deberan ser capaces de registrarse en el sitio web, tambein debera ser posible para los usuarios recibir notificaciones de cada actualizacion en cuanto a su caso y por ultimo el cliente debera ser capaz de realizar el pago desde la misma pagina web. El sitio web tambien debera de tener opcion para que los administradores reciban notificaciones cuando un caso nuevo a sido registrado, Los administradores tambien deberan poder recibir el pago por parte del cliente y poder actualizar cada caso.   |
___
### ANALISIS DE REQUISITOS Y REQUERIMIENTOS

| Modelamiento de Negocio  |
|---|
| ![Diagrama bmpn representando los requerimientos para el sitio web.](images/Abogabot.svg)  |

___
|   | Terminos de Referencia  |
|---|---|
|Alcance de la solucion | * Pagina Web <br/> * Creacion de usuarios <br/> * Los usuarios podran crear y observar el progreso de sus casos. <br/> * Creacion automatica del documento legal apartir del formulario creado por el usuario. <br/> * Pagos desde la Web. <br/>  * Correos de actualizacion y notificaciones al usuario. Y de nuevos casos a los administradores. <br/> * Sitio web responsibo para celular. <br/> FUERA DEL ALCANCE: <br/> * Pagos en efectivo. <br/>  * Capacitacion de los administradores. | 
|Requerimientos Funcionales y <br> criterios de aceptacion. |Requisito: Los tramites de los pagos ocurren sin fallos. <br/> Criterio de aceptacion: La transferencia monetaria ocurre sin problemas y fue aceptada al 100%. <br/> Requisito:El sitio web se debe adaptar a diferentes dispositivos. <br/> Criterio de aceptacion: El sitio web se adapta a la mayoria de displays. <br/> Requisito: El sitio web debe generar el documento legal automaticamente. <br/> Criterio de aceptacion: El documento debe ser generado en el 100% de los casos. <br/> Requisito: El usuario debe ser notiificado en cada avance de su caso. <br/> Criterio de aceptacion: El usuario es notificado en las actualizaciones mas importantes.|
|Requerimientos no Funcionales  | * El sitio web debe poder ser accesible el 99,9% de las veces en que un usuario intente accederlo. <br/> * El formulario, los datos personales de los usuario y contraseñas deberan ser encriptadas. <br/> * La aplicacion debera poder ser usada en los navegadores mas usados.  |
