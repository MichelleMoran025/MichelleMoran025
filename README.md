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




 
