# tzvs

---

## Proyectos

1. -  [ ] TZVS.tech
1. -  [ ] MinInspect
2. -  [ ] LegalTemplates (CITGO)
3. -  [ ] Discovery (Watson)
4. -  [ ] Chatbot (Watson)

---

## TZVS.tech

Para el desarollo y uso de estos proyectos y herramientas es necesario como minimo un servidor en el cual vivan estas plataformas. Es tambien recomendable un domain (ej. https://TZVS.tech) para acceder a estas plataformas.

Varios de estos proyectos involucran portales web, bases de datos, motores de procesos, etc. Por ejemplo: MinInspect necesita un dashboard web, una base de datos, y un repositorio de reportes; LegalTemplates(CITGO) necesita de lo mismo; Watson Discovery necesita un portal web con acceso a los motores de IBM y un repositorio de documentos; Watson Chatbot necesita de un portal web con interface para conversaciones al igual que una base de datos para guardar conversaciones he informacion de usuarios.

Ya que esto es necesario, propongo ademas aprovecharlo como el punto de partida de una rama de tecnologia de la firma - con el proposito de crear 'apps' o servicios que facilitan los procesos de la firma o que permiten a la firma crear nuevos servicios, productos, atender mejor a los clientes y ser la primera firma con un solido apalancamiento de tecnologia.

Por el momento los apps que vivirian ahi serian MinInspect, LegalTemplates(CITGO), Watson Discovery y Chatbot. Pero esta infrastructura permite que en el futuro se puedan desarollar servicios, herramientas, y aplicaciones de una manera agil (ej. servicio de firmas electronicas) , y desarollar una nueva cara tecnologica de la firma.

 - [x] Existe un servidor
 - [x] Existe un domain al cual acceder al servidor (https://TZVS.tech)
 - [x] El servidor esta protejido por firewall, comunicacion encriptada, y medidas standard de seguridad
 - [x] El servidor esta equipado con infrastructura para rapidamente levantar nuevos servicios


 - [x] En el servidor vive el prototipo de el dashboard MinInspect

---

## MinInspect

#### Producto
*Inspectorio para inspecciones mineras*

Un sistema compuesto de un servidor central de informacion, un dashboard para abogados, y un app para inspectores, que permite el procesamiento de reportes mineros hasta las acciones legales de una manera fluida, simple, y escalable.

1. Dashboard de analysis y manejo de reportes de mineria ilegal y su subsiguientes procesos legales.
2. Una aplicacion movil para uso de inspectores in situ que les permite crear reportes con data mas limpia y de manera mas simple.

#### Proposito
Asistir al equipo de mineria con el manejo de reportes y acciones legales. Crear de esta herramienta un producto para atraer a nuevos clientes y/o ofrecerla como servicio a compañias mineras, firmas legales, etc.

#### Funciones Preliminares

**Dashboard**\
*Usuario: Abogados*
1. - [x] Hay un dashboard al cual se accede via pagina web con credenciales
1. - [x] Hay un servidor central que sirve la informacion al dashboard y contiene la base de datos de reportes y motores de analysis
1. - [x] Abogados pueden subir los reportes PDF que existen hasta el momento
2. - [x] Abogados pueden visualizar el directorio de reportes
3. - [x] Abogados pueden manejar una Matriz creada a base de estos reportes (Añadir, Editar, Remover informacion, visualizarla como tabla excel)
4. - [x] Abogados pueden ver estadisticas acerca de estos reportes (numero de reportes activos, numero de reportes de actividad Regular, etc.)
5. - [x] Abogados pueden visualizar en un mapa interactivo (como Google Maps) las ubicaciones GPS de estos reportes
5. - [ ] Abogados pueden visualizar en un mapa interactivo el catastro minero
6. - [ ] Abogados pueden manejar los procesos y acciones legales necesarias a base de estos reportes
7. - [ ] La base de datos de reportes y la informacion extraida se puede poner bajo analysis (motores de inteligencia artificial, estadiistica)



**App**\
*Usuario: Inspectores*
1. - [ ] Inspector tiene un tablet customizado para correr unicamente esta applicacion
1. - [ ] Inspector puede usar la aplicacion para completar todo el proceso de inspeccion
1. - [ ] Inspector, al hacer las rondas, lleva el tablet y al detectar actividad inusual empieza el flujo de reporte
1. - [ ] Inspector toma fotos con la aplicacion, estas fotos son registradas con coordenadas GPS
1. - [ ] Luego, inspector llena un cuestionario diseñado para recoger la informacion necesario de manera simple y util. (cuestionario diseñado para servir al equipo de abogados)
1. - [ ] Al completar, la informacion es enviada a los servidores centrales de manera normalizada

#### Ejecucion

**Fase Diseño**
 - [x] Recoger informacion del equipo de abogados acerca de el proceso de inspeccion
 - [ ] Recoger informacion del equipo de abogados acerca de los procesos legales que nacen a partir de los reportes

**Fase Desarollo**
 - [x] Prototipo de dashboard
 - [ ] Prototipo de applicacion

**Fase "Feedback"**\
(feedback -> implementacion -> feedback)
 - [ ] "Feedback" Agil de abogados acerca de dashboard
 - [ ] "Feedback" Agil de abogados acerca de app
 - [ ] "Feedback" Agil de inspectores acerca de app

**Fase Pruebas**
 - [ ] Prubeas de cumplimiento de requerimientos funcionales
 - [ ] Pruebas en vivo del dashboard
 - [ ] Pruebas en vivo del inspector in situ

**Lanzamiento**
 - [ ] Lanzamiento de dashboard
 - [ ] Lanzamiento de app

**Mantenimieto y Evolucion**
 - Manteminiento de dashboard
 - Mantenimiento de app
 - Cyclos Agiles para mejora y evolucion del producto


#### Cronografia
Diciembre 2019
 - [ ] Entrega de Prototipo Dashboard
 - [ ] Inicio de fase "Feedback" de dashboard

Enero 2020
 - [ ] Entrega de prototipo de app
 - [ ] Inicio de fase feedback de app


 - [ ] Inicio de fase pruebas de dashboard

Febrero 2020
 - [ ] Inicio de fase pruebas de app

 - [ ] Entrega y Lanzamiento de Dashboard

Marzo 2020
 - [ ] Entrega y Lanzamiento de app

#### Recursos TZVS
 - Contacto y atencion de parte de un - o mas - miembros del equipo de mineria a traves de email, mensajes.
 - "Feedback" del equipo de mineria
 - Reuniones - (al menos una al mes) - con equipo de mineria
 - Utilizacion de GitHub para hacer manejo de versiones, rastreo y resolucion de problemas (opcional pero ***muy*** recomendado)


---

## LegalTemplates (CITGO)

#### Producto
*Clerky.com mejorado y para Ecuador*

Un sistema de manejo de procesos y templates legales a traves de una interface web que maneja el flujo y genera los templates necesarios.

#### Proposito

Enfocado en servir las necesidades de CITGO, pero con la larga vision de poder manejar los procesos "tipicos" legales (incorporacion de compania, etc.) de manera escalable. De tal manera que reduce el tiempo de los abogados y permite escalar el servicio a nuevos clientes sin tener que aumentar recursos legales.

#### Funciones Preliminares
#### Ejecucion
**Fase Diseño**
- [x] Reunion preliminar para entender las necesidades y la solucion
- [ ] Reunion con abogado junior para entrar en detalle en el paso a paso y ver ejemplos de documentos
- [ ] Definicion de los flujos requeridos para Version 1
- [ ] Inicio de creacion de templates legales
- [ ] Inicio de requerimientos funcionales

**Fase Desarollo**
- [ ] Finalizacion de requerimientos funcionales
- [ ] Prototipo de dashboard

**Fase "Feedback"**
- [ ] "Feeback" Agil de abogados acerca del dashboard, flujos, y procesos
- [ ] Finalizacion de templates legales para Version 1

**Fase Pruebas**

- [ ] Pruebas de cumplimiento de requerimientos funcionales
- [ ] Prubeas en vivo de dashboard

**Lanzamiento**

- [ ] Lanzamiento de dashboard Version 1

**Mantenimieto y Evolucion**

- Manteminiento de dashboard
- Creacion de nuevos flujos y nuevos templates

#### Cronografia

#### Recursos TZVS
 - reuniones para entender en detalle, con paso a paso y ejemplos de documentos, los flujos que se desean incorporar
 - ejemplos y soporte para generar los templates necesarios


---

## Discovery (Watson)
*Manejo de Conocimiento via Inteligencia Artificial*

#### Producto

Un portal web - estilo Google - donde viven todos los documentos y contratos de la firma y atraves de los cuales los abogados pueden hacer busquedas potenciadas por inteligencia artificial.

#### Proposito

Apalancar los servicios de Watson para aumentar eficiencia, conocimiento, y aprendizaje dentro de la firma, y mantener un conocimiento general que crezca con la firma en lugar de solo los abogados.

#### Funciones Preliminares
1. - [ ] Existe un portal web de busquda a traves del cual se pueden generar busquedas
2. - [ ] Las busquedas son potenciadas por el motor de Inteligencia Artificial de Watson para entregar resultados
3. - [ ] En el portal web se pueden ver y explorar en detalle los resultados
4. - [ ] Existe un mecanismo a traves del cual los documentos generados por la firma son guardados en el repositorio Watson.

#### Ejecucion

#### Cronografia
Diciembre 2019
 - [ ] Entrega de prototipo del portal web



#### Recursos TZVS
 - Coordinacion con Edgar para juntar el trabajo ya hecho con el trabajo restante

---


## Chatbot (Watson)
*Legal Chatbot*
#### Producto

Portal web (o futuro app movil) a traves del cual clientes pueden hacer preguntas legales respondidas por Inteligencia Artificial.

#### Proposito

Apalancar los servicios de Watson para poder servir a mas clientes sin aumentar recursos legales y atraer nuevos clientes con un sistema de respuestas y comunicacion novedoso y mas eficaz.

#### Funciones Preliminares

1. - [ ] Existe un portal web a traves del cual usuarios pueden iniciar un chat
1. - [ ] Las preguntas del chat son respondidas por el motor de Inteligencia Artificial de Watson y el banco de preguntas creado
1. - [ ] Las sesiones y preguntas de los usuarios son guardadas para que el usuario pueda volver a su conversacion
1. - [ ] Usando la conversacion - el sistema le notifica a los abogados que existe un pontencial nuevo cliente y cuales son sus inquietudes


#### Ejecucion
#### Cronografia
#### Recursos TZVS
 - creacion y manejo de banco de preguntas a traves del sistema Watson debe ser hecho por Edgar o los abogados
 - colaboracion con Edgar para juntar el trabajo ya hecho con lo que falta hacer

---
