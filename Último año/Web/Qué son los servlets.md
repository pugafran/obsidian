Un servlet es un programa Java que acepta peticiones HTTP y genera respuestas utilizando también el protocolo HTTP.  

Principalmente se usan para la construcción de páginas web dinámicas.  

En Java se crea extendiendo la clase HTTPServlet, que forma parte de JEE.

Los servlets se ejecutan dentro de un contenedor de Servlets que está dentro de un servidor web.

Al trabajar con Servlets tenemos una solución técnica que nos facilita la gestión de la sesión: El objeto HttpSession:

• HttpSession almacena objetos en el lado del servidor  
• Cada usuario tendrá asociada un objeto HttpSession con un identificador único 
• En el cliente se crea una cookie con el identificador de la sesión  
• En cada petición, el cliente incluye su identificador de sesión

Los dos método más importantes, que nos permiten gestionar la inforamción guardada en la sesión son:

• setAttribute para registrar un atributo o modificar su valor 
• getAttribute para recuparar su valor

Contexto en servlets

Es común a todos los Servlets, nos permite compartir información y objetos entre los distintos usuarios.  

Se accede con el objeto ServletContext. Sus dos métodos más importantes son:
• setAttribute para registrar un atributo o modificar su valor 
• getAttribute para recuparar su valor