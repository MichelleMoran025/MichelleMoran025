# EVALUACIÓN PRÁCTICA

Se deberán entregar las resoluciones en un archivo Readme.md de un repositorio de github publico. Aquí un instructivo de como hacer uno. Se valorará muchísimo el nivel de presentación teniendo en cuenta en cuenta la redacción, faltas de ortografía, uso de tabulación, tamaños de fuentes y diversas herramientas que entrega el readme para hacer más fácil su comprensión. 


## EJERCICIO 1
Instalación del ambiente
El presente ejercicio busca realizar la instalación del ambiente para el desarrollo del trabajo práctico. A continuación se listará una serie de aplicaciones a instalar

1.	Instalar el IDE Visual Studio Code: Un IDE (Entorno de desarrollo integrado), es una aplicación que nos brinda facilidades al momento de generar código. Dentro de Pro Contacto utilizamos Visual Studio Code para los proyectos relacionados a aplicaciones web y móviles. El mismo permite trabajar con varios lenguajes tales como: HTML, CSS, C#, Javascript, APEX (NodeJS, Angular, IONIC, React, Typescript, etc).

2.	Instalar GIT y GIT Bash: Git es una aplicación utilizada para el control de versionado de código. En otras palabras, es una suerte de “disco” en donde se guardarán los distintos files que componen nuestra aplicación (ejemplo: index.html, estilos.css, etc). La gran ventaja de GIT es que al momento de subir una versión nueva de un archivo, genera un “backup” de la versión anterior para poder ser restaurado cuando se desee. Además, el código se encuentra en la “nube”, por lo que puede ser accedido y descargado desde cualquier lugar que tenga acceso a internet.


## Ejercicio 2 

Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son diagnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:

**1. ¿Qué es un servidor HTTP?**

> Es un software que por medio del protocolo HTTP se encarga de realizar peticiones de los clientes (conexión cliente/servidor). 

Estas peticiones pueden ser:

- Intercambio de datos

- Mostrar contenido de la Web

**2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

Se encargan de indicar que acciones se requieren hacer sobre el servidor. 

Los más conocidos son:

- GET: consulta

- POST: agrega un nuevo recurso

- PUT: modifica algún recurso existente

- PATCH: actualiza los elementos de algún recurso

- DELETE: elimina un recurso en especifíco

**3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 

•	Request (petición): es el requierimiento por parte de un cliente al servidor solicitando algún recurso, este se puede hacer por medio del método GET.

•	Response (respuesta): es el mensaje de respuesta del servidor al cliente dado un request con anterioridad.

•	Headers: son esquemas de key:value que contienen información sobre el HTTP request y el navegador. Aquí también se encuentran los datos de las cookies. La mayoría de los headers son opcionales.

4.	¿Qué es un queryString? (En el contexto de una url)

Es una cadena de consulta que hace referencia a la interacción en una Base de Datos.
	
5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

Es un código de respuesta que proporciona información de estado sobre la solicitud.

#(200): son los valores de respuesta que han sido satisfactorias.

#(300): son los valores de respuesta que han sido redireccionados.

#(400): son los valores de respuesta que ha sido incorrecta.

#(500): son los valores de respuesta de error por parte del servidor.

6. ¿Cómo se envía la data en un GET y cómo en un POST? 

• En un  GET la data se lleva acabo en por medio de una URL, dónde los datos son visibles por el usuario.

• En un  POST la data se lleva acabo por medio de un formulario, cabe mencionar que los datos no son visibles al usuario.

7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

• GET: consulta

8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

Estructuras de datos JSON:

Existen dos estructuras de datos en JSON:

• Una es una colección de datos nombres/valores (objeto) los cúales son: registro, estructura, diccionario, tabla hash, lista de claves o un arreglo asociativo  

• Una lista ordenada de valores los cúales son: arreglos, vectores, listas o sequencias.

9. Explicar brevemente el estándar SOAP

Es un protocolo escrito en XLM  que sirve para el intercambio de información entre aplicaciones está diseñado para la comunicación con el protocolo HTML.  

10. Explicar brevemente el estándar REST Full

Es un conjutno de restricciones y prinipios de la arquitectura REST. Usa caracteristicas y capacidades  existentes de la Web. Se apoya sobre un protocolo HTTP.

11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

• Los HTTP headers son la parte central de los HTTP requests y responses. Tansmiten información acerca del navegador del cliente, de la página solicitada, del servidor, étc.

• El key content-type en un header dice al cliente que tipo de contenido será retornado.


## EJERCICIO 3
Recomendamos previamente entender los conceptos de la sintaxis “json” antes de arrancar con los ejercicios.
Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:

1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
2.	Realizar un request POST a la URL anterior, y con body:
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
Tip: (Marcar la opción “raw” como body)
3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
¿Qué diferencias se observan entre las llamadas el punto 1 y 3?



## EJERCICIO 4
Solicitar usuario de Trailhead a ariel.tarsitano@procontacto.com.mx
Cambiar el idioma de Trailhead a inglés.
Realizar los siguientes módulos de Trailhead:

●	Fundamento de la plataforma Salesforce
●	Fundamentos de Apex y .NET
●	Modelado de datos
●	Fundamentos y base de datos de Apex
●	Desencadenadores de Apex
●	Apex Integration Services

Se recomienda usar el mismo Playground para todos los módulos solicitados. Excepto que se solicite crear uno nuevo en el enunciado del Módulo.
Para revisar la resolución de los módulos, compartir la URL del perfil público de Trailhead en una liga dentro del Readme.



## EJERCICIO 5
Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:

1.	Lead
2.	Account
3.	Contact
4.	Opportunity
5.	Product
6.	PriceBook
7.	Quote
8.	Asset
9.	Case
10.	Article

Los campos enumerarlos a través de una lista de texto en el Readme y las relaciones a través de un diagrama UML simple realizado con Drawio.
Ejemplo de diagrama
Drawio: https://app.diagrams.net/

Que una cuenta tiene muchos contactos se representa de la siguiente manera:

 

Completar el resto de las relaciones agregando el resto de los objetos enumerados.

Exportar el diagrama de Drawio, subirlo al repositorio y agregarlo dentro del readme con la etiqueta para linkear imágenes.

Se puede usar el schema builder de salesforce para entender las relaciones.

https://trailhead.salesforce.com/content/learn/modules/data_modeling/schema_builder

 



## EJERCICIO 6

Responder las siguientes preguntas brevemente sobre:

Soluciones de Salesforce

A. ¿Qué es Salesforce?

Salesforce es una plataforma de gestión de las relaciones con los clientes (CRM) basada en la nube que proporciona a todos los departamentos de su organización, incluidos los de marketing, ventas, servicio al cliente y comercio electrónico, una visión unificada de sus clientes en una plataforma integrada.

B. ¿Qué es Sales Cloud?

Sales Cloud es un software de ventas y CRM que reúne la mayor parte de las funcionalidades encontradas en las demás plataformas. La gran ventaja de elegirlo es que, con nuestro CRM de ventas, podrás aprovechar todos los recursos de automatización que necesitas en una única plataforma.

C. ¿Qué es Service Cloud?

Sales Cloud es un software de ventas y CRM que reúne la mayor parte de las funcionalidades encontradas en las demás plataformas. La gran ventaja de elegirlo es que, con nuestro CRM de ventas, podrás aprovechar todos los recursos de automatización que necesitas en una única plataforma.

D. ¿Qué es Health Cloud?

Health Cloud permite una conversación personalizada entre el paciente y las entidades sanitarias asociadas. No solo es beneficioso para los equipos de atención médica, sino que también beneficia a los pacientes al establecer comunicaciones digitales con su equipo de atención.

E. ¿Qué es Marketing Cloud?

Marketing Cloud es una plataforma de Salesforce que las pymes y grandes empresas pueden utilizar para invertir en estrategias de email marketing de nivel profesional. Las pequeñas empresas, por ejemplo, pueden conquistar nuevos clientes y asegurarse la lealtad de sus clientes actuales sin necesidad de aumentar el número de empleados para lograr esos resultados. Utiliza el software de marketing para planificar, personalizar y optimizar el recorrido de tus clientes, conociéndolos cada vez mejor, midiendo los resultados y sacándole el máximo provecho a tu presupuesto de marketing.

Funcionalidades de Salesforce

A. ¿Qué es un RecordType?

Los Record Types en Salesforce nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

Un Record Type se puede utilizar cuando un objeto en Salesforce es usado para multiples propósitos, y debe mostrar diferente información en su respectivo Page Layout.

Los Record Types pueden ser creados para todos los objetos en Salesforce. Sin embargo, en algunos objetos, primero debemos crear un Business Process y luego su respectivo Record type. Estos objetos son: Lead, Opportunity, Case y Solution.

B. ¿Qué es un ReportType?

Es un tipo de informe basado en las relaciones entre un objeto principal y sus objetos relacionados. Los informes muestran solo los registros que cumplen los criterios definidos en el tipo de informe. 

C. ¿Qué es un Page Layout?

Controlan el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos.

D. ¿Qué es un Compact Layout?

Muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

E. ¿Qué es un Perfil?

Es una forma de acceder a los usuarios, muestra detalles de cada usuario. 

F. ¿Qué es un Rol?

Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

G. ¿Qué es un Validation Rule?

Las reglas de validación en Salesforce verifican que los datos ingresados por un usuario cumplan con ciertos criterios antes de que el usuario pueda guardar el registro.

H. ¿Qué diferencia hay entre una relación Master Detail y Lookup?

La relación Master Detail se usa cuando queremos controlar la visualización de los registros de detalle en función del valor del registro maestro vs es un tipo de relación de Salesforce que conecta dos objetos sin afectar las propiedades de seguridad y eliminación. Es posible crear una relación intermedia entre objetos agregando relaciones de búsqueda a objetos estándar, personalizados y externos.

I. ¿Qué es un Sandbox?

Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.

J. ¿Qué es un ChangeSet?

Se usa para enviar personalizaciones de una organización de Salesforce a otra. Por ejemplo, puede crear y probar un nuevo objeto en una organización sandbox y luego enviarlo a su organización de producción mediante un conjunto de cambios. Los conjuntos de cambios solo pueden contener modificaciones que puede realizar a través del menú Configuración. Por ejemplo, no puede usar un conjunto de cambios para cargar una lista de registros de contactos. Los conjuntos de cambios contienen información sobre la organización. No contienen datos, como registros.


K. ¿Para qué sirve el import Wizard de Salesforce?

facilita la importación de datos para muchos objetos estándar de Salesforce, incluidas cuentas, contactos, clientes potenciales, soluciones, miembros de campaña y cuentas personales. También puede importar datos para objetos personalizados. Puede importar hasta 50.000 registros a la vez.

L. ¿Para qué sirve la funcionalidad Web to Lead?

El proceso de usar un formulario de sitio web para capturar información del visitante y almacenar esa información como un nuevo cliente potencial en Salesforce. Salesforce le permite crear fácilmente formularios web para clientes potenciales que capturan información sobre los visitantes de su sitio web.

M. ¿Para qué sirve la funcionalidad Web to Case?

son herramientas que capturan automáticamente prospectos o casos de un sitio web externo a Salesforce para crear un registro de prospecto o caso directamente en Salesforce. Estas herramientas se utilizan para generar un Webform en formato HTML con los campos de Salesforce que recuperan la información del registro.

N. ¿Para qué sirve la funcionalidad Omnichannel?

Omni-Channel es una herramienta que se encuentra dentro de la Consola de ventas o de servicio que, una vez habilitada y configurada, automáticamente envía trabajo a sus usuarios en tiempo real. Por ejemplo, se pueden configurar reglas de enrutamiento para asignar casos a agentes a través de Omni-Channel o configurar reglas de enrutamiento para asignar clientes potenciales a vendedores.

O. ¿Para qué sirve la funcionalidad Chatter?

Chatter es una aplicación de colaboración en tiempo real de Salesforce que permite a sus usuarios trabajar juntos, hablar entre ellos y compartir información. Chatter conecta, involucra y motiva a los usuarios a trabajar de manera eficiente en toda la organización, independientemente de su rol o ubicación.

Conceptos generales

A.	¿Qué significa SaaS?

El software como servicio (SaaS) es un modelo de entrega de software basado en la nube en el que el proveedor de la nube desarrolla y mantiene el software de las aplicaciones en la nube, proporciona actualizaciones automáticas del mismo y lo pone a disposición de sus clientes a través de Internet con un sistema de pago por uso. El proveedor de la nube pública administra todo el hardware y el software tradicional, incluidos middleware, software de aplicaciones y seguridad. De ese modo, los clientes de SaaS pueden reducir drásticamente los costos, implementar, ampliar y actualizar las soluciones empresariales con mayor rapidez de la que proporciona el mantenimiento de sistemas y software locales y predecir el coste total de propiedad con mayor precisión.

B.	¿Salesforce es Saas?

Salesforce es una compañía de PaaS (Plataforma como Servicio), un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio). Este modelo abarca el ciclo completo para desarrollar e implantar aplicaciones desde Internet.

C.	¿Qué significa que una solución sea Cloud?

la computación en la nube (cloud computing) es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local.

D.	¿Qué significa que una solución sea On-Premise?

El término on-premise o en local se refiere al tipo de instalación de una solución de software. Esta instalación se lleva a cabo dentro del servidor y la infraestructura (TIC) de la empresa. Es el modelo tradicional de aplicaciones empresariales.

E.	¿Qué es un pipeline de ventas?

El pipeline de ventas es, precisamente, el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.

F.	¿Qué es un funnel de ventas?

El embudo de ventas o conversión es una metáfora usada en mercadotecnia o administración de empresas para referirse a las fases de la venta. Es el proceso por el que las oportunidades potenciales de ventas son cualificadas y seleccionadas para convertirlas en oportunidades reales que terminan en transacciones reales.

G.	¿Qué significa Customer Experience?

El Customer Experience, también llamada experiencia del cliente o CX, es la experiencia que formará tu consumidor en función de sus interacciones con tu marca, que pueden ser positivas o negativas.

H.	¿Qué significa omnicanalidad?

Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado.

I.	¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?

*El B2B es un modelo de negocio que consiste en los servicios que una compañía entrega a otra con el objetivo de mejorar las ventas de los productos y bienes que ofrece. Es decir, una transacción comercial entre empresas.

*B2C es el acrónimo en inglés de “business to consumer” (empresa a consumidor). Es decir, es un modelo de negocio en el que una empresa le vende de forma directa al consumidor final. Este modelo es el de las empresas que ofrecen bienes y servicios de consumo masivo.

*Los “indicadores claves de desempeño” o KPIs (por sus siglas en inglés) son todas las variables, factores y unidades de medida para generar una estrategia de marketing. La palabra KPI proviene de las siglas de la frase “Key Performance Indicators”. Esto se traduce como “indicadores claves de desempeño”.

J.	¿Qué es una API y en qué se diferencia de una Rest API?

*Una API o interfaz de programación de aplicaciones es un conjunto de definiciones y protocolos que se usa para diseñar e integrar el software de las aplicaciones. Las API permiten que sus productos y servicios se comuniquen con otros, sin necesidad de saber cómo están implementados. Esto simplifica el desarrollo de las aplicaciones y permite ahorrar tiempo y dinero.

*Otra especificación es la Transferencia de Estado Representacional (REST). Las API web que funcionan con las limitaciones de arquitectura REST se llaman API de RESTful. La diferencia más básica entre ambas es que SOAP es un protocolo, mientras que REST es un estilo de arquitectura. Esto significa que no hay ningún estándar oficial para las API web de RESTful. Tal como se define en la tesis de Roy Fielding, "Architectural Styles and the Design of Network-based Software Architectures", las API son RESTful siempre que cumplan con las 6 limitaciones principales de un sistema RESTful:

Arquitectura cliente-servidor: la arquitectura REST está compuesta por clientes, servidores y recursos; y administra las solicitudes con HTTP.

K. ¿Qué es un Proceso Batch?

Se conoce como sistema por lotes, o modo batch, a la ejecución de un programa sin el control o supervisión directa del usuario que se denomina. Este tipo de programas se caracterizan porque su ejecución no precisa ningún tipo de interacción con el usuario.

L. ¿Qué es Kanban?

Kanban, cuyo significado es letrero o tarjeta en japonés, ​ es un sistema de información que controla de modo armónico la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos que tienen lugar tanto en el interior de la fábrica, como entre distintas empresas.

M. ¿Qué es un ERP? 

Abreviatura de Enterprise Resource Planning, ERP se traduce como un sistema de gestión empresarial. Una herramienta tecnológica que tiene como objetivo integrar y automatizar los principales procesos y datos de la empresa en una sola plataforma, facilitando la gestión de datos y la organización de la compañía.

N. ¿Salesforce es un ERP?

Salesforce es una solución de gestión de relaciones con clientes que une empresas y clientes. Es una plataforma CRM integrada que brinda a todos tus departamentos, incluidos marketing, ventas, comercio y servicios, una vista única y compartida de cada cliente.


<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

    ```ruby
      puts "Hello World"
    ```

</details> ```</p>

The Markdown will be collapsed by default.

![Rendered collapsed](/assets/images/help/writing/collapsed-section-view.png)

After a reader clicks <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-triangle-right" aria-label="The right triange icon" role="img"><path d="M6.427 4.427l3.396 3.396a.25.25 0 010 .354l-3.396 3.396A.25.25 0 016 11.396V4.604a.25.25 0 01.427-.177z"></path></svg>, the details are expanded.

![Rendered open](/assets/images/help/writing/open-collapsed-section.png)

## Leer más

- [GitHub Especificaciones del formato Markdown](https://github.github.com/gfm/)
- "[Sintaxis de escritura y formato básicos](/articles/basic-writing-and-formatting-syntax)"
