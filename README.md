Ejercicio 2 

Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son diagnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:

1. ¿Qué es un servidor HTTP? 

Es un software que por medio del protocolo HTTP se encarga de realizar peticiones de los clientes (conexión cliente/servidor). 

Estas peticiones pueden ser:

•	Intercambio de datos

•	Mostrar contenido de la Web

2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

Se encargan de indicar que acciones se requieren hacer sobre el servidor. 

Los más conocidos son:

•	GET: consulta

•	POST: agrega un nuevo recurso

•	PUT: modifica algún recurso existente

•	PATCH: actualiza los elementos de algún recurso

•	DELETE: elimina un recurso en especifíco

3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 

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




EJERCICIO 6

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
C. ¿Qué es un Page Layout?
D. ¿Qué es un Compact Layout?
E. ¿Qué es un Perfil?
F. ¿Qué es un Rol?
G. ¿Qué es un Validation Rule?
H. ¿Qué diferencia hay entre una relación Master Detail y Lookup?
I. ¿Qué es un Sandbox?
J. ¿Qué es un ChangeSet?
K. ¿Para qué sirve el import Wizard de Salesforce?
L. ¿Para qué sirve la funcionalidad Web to Lead?
M. ¿Para qué sirve la funcionalidad Web to Case?
N. ¿Para qué sirve la funcionalidad Omnichannel?
O. ¿Para qué sirve la funcionalidad Chatter?


Conceptos generales

A.	¿Qué significa SaaS?
B.	¿Salesforce es Saas?
C.	¿Qué significa que una solución sea Cloud?
D.	¿Qué significa que una solución sea On-Premise?
E.	¿Qué es un pipeline de ventas?
F.	¿Qué es un funnel de ventas?
G.	¿Qué significa Customer Experience?
H.	¿Qué significa omnicanalidad?
I.	¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?
J.	¿Qué es una API y en qué se diferencia de una Rest API?
K.	¿Qué es un Proceso Batch?
L.	¿Qué es Kanban?
M.	¿Qué es un ERP? 
N.	¿Salesforce es un ERP?



 
