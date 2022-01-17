# EvaluacionPractica

Descripción del proyecto
Resolución de los ejercicios de la evaluación práctica.

Pre-requisitos
 - Instalar Visual Studio Code
 - Instalar Git y Git Bash
 - Instalar Postman

Resoluciones

Ejercicio 1
 - Instalar Visual Studio Code un IDE que muchos programadores utilizan debido a la versatilidad de lenguajes que admite, es completamente gratuito y se puede obtener de la página    oficial: https://code.visualstudio.com/download ![Instalación de Visual Studio Code](https://user-images.githubusercontent.com/93282584/148654506-67bebcdf-f503-4708-9d81-5471c69617c3.png)
 - Instalar Git y Git Bash un software control de versiones que permite almacenar los archivos de nuestro proyecto, es gratutito y se puede descagar de la página oficial:            https://git-scm.com/downloads ![Instalación de Git y Git Bash](https://user-images.githubusercontent.com/93282584/148654469-0d514e53-1c84-4f3d-a476-ce6b960be6ec.png)

Ejercicio 2
1.	¿Qué es un servidor HTTP? 
R:  (Protocolo de Transferencia de Hypertexto), es un programa que procesa las peticiones del cliente para la entrega y distibución de contenido web sean archivos o imágenes que forman parte de un sitio web.

2.	¿Qué son los verbos HTTP? Mencionar los más conocidos 
R: Son las distintas peticiones que se le pueden hacer a un servidor http, algunas de ellas son GET, POST, PUT, DELETE.

3.	¿Qué es un request y un response en una comunicación HTTP?
R: Request es la petición que realiza un cliente al servidor y response es la respuesta a esa petición por parte del servidor.

4.	¿Qué son los headers? 
R: Son las cabeceras entre la comuniación del cliente y servidor, esto permite dar un mayor detalle de una petición (request) o una respuesta (response).

5.	¿Qué es un queryString? (En el contexto de una url) 
R: Es la parte de la url que indica que datos debe jalar la aplicación web desde la base de datos dependiendo de la consulta o búsqueda del usuario en la aplicación.

6.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
R: Son los códigos de respuesta de una petición en un servidor, las posibles respuestas se dividen en grupos dependiendo de un rango de números, las posibles valores devuletos pueden ser respuestas informativas, respuestas satisfactorias, redirecciones, errores del cliente donde muchos usuarios tenemos relación con el error 404 y errores del servidor.

7.	¿Cómo se envía la data en un Get y cómo en un POST? 
R: La data en GET envía los datos visibles por medio de la URL y en POST los datos se envían de manera oculta.

8.	¿Qué verbo http utiliza el navegador cuando accedemos a una página? 
R: El método GET

9.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
R: Los archivos JSON son un formato ligero utilizado para reprentar e intercambiar información (datos) a través de colecciones. Los archivos XML son un formato de texto especial compuesto por un determinado número de etiquetas en estructura de árbol.

10.	Explicar brevemente el estándar SOAP
R: Es un protocolo que permite el intercambio de información entre procesos por medio de XML

11.	Explicar brevemente el estándar REST Full
R: Es un modelo de arquitectura web que permite el intercambio de información entre el cliente y servidor a través de estrcuturas de datos JSON, XML entre otras.

12.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
R: Los headers o cabeceras son la parte central de una petición y permiten mostrar la información a través del navegador del cliente. El Content-type se utiliza para indicar el medio del recurso.

Ejercicio 3

Antes de realizar este ejercicio es importante descargar Postman, un software que nos permite hacer pruebas de API para obtener una request, se puede obtener de su sitio oficial: https://www.postman.com/downloads/
1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![image](https://user-images.githubusercontent.com/93282584/148697949-6121fd04-0072-4849-bb53-07343934fa64.png)

2.	Realizar un request POST a la URL anterior, y con body:
![image](https://user-images.githubusercontent.com/93282584/148697980-2b5a32e8-1484-4168-8086-3bceb4d3d4b4.png)

3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![image](https://user-images.githubusercontent.com/93282584/148698000-ce66673a-3cc8-4613-9ae3-eacd24bbbe0e.png)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
Que en la primera llamada no se encuentra el registro de "francisco.lizarraga@procontacto.com.mx" debido a que eso fue realizado en el punto 2 con la request del método POST. Y al realizar el último GET como ya se había realizado la petición ya salío el registro.

Ejercicio 4

Para realizar la resolución de los ejercicios, primeramente se debe crear una cuenta de TrailHead con un correo eléctronico, una vez con la cuenta lo siguiente es leer los siguientes módulos y resolver sus retos o preguntas.

 ●	Fundamento de la plataforma Salesforce
 ●	Fundamentos de Apex y .NET
 ●	Modelado de datos
 ●	Fundamentos y base de datos de Apex
 ●	Desencadenadores de Apex
 ●	Apex Integration Services

URL del pérfil público: https://trailblazer.me/id/flizrraga

Ejercicio 5

Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:

 1.	Lead: es un cliente potencial que ha demostrado interés en algún servicio de la empresa.
 2.	Account: son las compañías con las que se realizan negocios.
 3.	Contact: son las personas que trabajan para dichas compañías (Account).
 4.	Opportunity: son acuerdos en curso, realizan un seguimiento de detalles acerca de acuerdos, incluyendo para qué cuentas son, quiénes son las personas implicadas y las cantidades de las ventas potenciales.
 5.	Product: son los elementos y servicios que distribuye a clientes.
 6.	PriceBook: es un objeto que se utiliza para marcar o actualizar precios de los productos que ofrece.
 7.	Quote: es el objeto que representa los precios propuestos para los productos o servicios que ofrece.
 8.	Asset:  los activos representan los productos específicos que han adquirido los clientes, almacenan información sobre los productos de los clientes.
 9.	Case: un caso es una inquietud de un cliente, puede ser una duda o un problema.
 10.	Article: son articulos de conocimientos, contienen información sobre puntos importantes como los procesos

