Un servlet es un programa Java que acepta peticiones HTTP y genera respuestas utilizando también el protocolo HTTP.  

Principalmente se usan para la construcción de páginas web dinámicas.  

En Java se crea extendiendo la clase HTTPServlet, que forma parte de JEE.

Los servlets se ejecutan dentro de un contenedor de Servlets que está dentro de un servidor web.

Al trabajar con Servlets tenemos una solución técnica que nos facilita la gestión de la sesión: El objeto HttpSession
• HttpSession almacena objetos en el lado del servidor  
• Cada usuario tendrá asociada un objeto HttpSession con un identificador único • En el cliente se crea una cookie con el identificador de la sesión  
• En cada petición, el cliente incluye su identificador de sesión