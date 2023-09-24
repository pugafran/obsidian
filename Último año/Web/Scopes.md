| Alcance           | Duración                                                                                                           | Ejemplo                                                                                     | Uso en la práctica                                                                                                   |
|-------------------|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| `@RequestScoped`  | Solo durante una petición-respuesta del cliente.                                                                   | Un estudiante intenta iniciar sesión.                                                       | Para datos temporales en operaciones como formularios de envío.                                                       |
| `@ViewScoped`     | Mientras el usuario esté en la misma vista (página).                                                               | Un estudiante ve una lista de tareas pendientes.                                            | Para páginas con múltiples interacciones sin salir de la vista, especialmente con AJAX.                               |
| `@SessionScoped`  | Desde que el usuario inicia sesión hasta que cierra sesión o la sesión expira.                                     | Información de perfil de un estudiante tras iniciar sesión.                                 | Datos que persisten durante la sesión del usuario, como información de perfil o carrito de compras.                   |
| `@ApplicationScoped` | Durante todo el ciclo de vida de la aplicación.                                                                 | Todos los estudiantes acceden a la misma lista de cursos.                                   | Para datos comunes a todos los usuarios y que no cambian con frecuencia.                                              |
| `@CustomScoped`   | Depende de cómo se defina el alcance personalizado.                                                                | Estudiantes formando grupos de estudio con un espacio con duración limitada.                | Casos especiales donde los otros alcances no son adecuados.                                                            |


Claro! Vamos a abordar el concepto de scope (alcance) en el contexto de JSF (JavaServer Faces) y usar ejemplos simples para cada uno. Imagina que estás construyendo una aplicación web para un colegio:

@RequestScoped:

Qué es: Dura solo una petición-respuesta del cliente.
Ejemplo: Cuando un estudiante intenta iniciar sesión, se crea un bean de solicitud para gestionar ese inicio de sesión. Una vez que la respuesta se ha enviado de vuelta (ya sea éxito o fracaso), ese bean se descarta.
En práctica: Usualmente, cuando necesitas un bean para almacenar datos temporales para una sola operación, como un formulario de envío.

@ViewScoped:

Qué es: Dura mientras el usuario esté en la misma vista (página). Se descarta si el usuario navega a una página diferente.
Ejemplo: Un estudiante está viendo una lista de sus tareas pendientes. Mientras siga en esa página, cualquier interacción o actualización de la lista se maneja con el mismo bean. Pero si el estudiante navega a una página diferente, como su perfil, el bean se descarta.
En práctica: Muy útil cuando trabajas con AJAX o tienes una página donde el usuario puede interactuar múltiples veces sin salir de esa vista.

@SessionScoped:

Qué es: Dura toda la sesión del usuario. Desde que inicia sesión hasta que cierra sesión o la sesión expira.
Ejemplo: Una vez que el estudiante inicia sesión, su información de perfil se almacena en un bean de sesión. Este bean se usa para personalizar su experiencia (como saludar al estudiante por su nombre) en todas las páginas hasta que cierre sesión.
En práctica: Perfecto para datos que deben persistir durante todo el tiempo que el usuario está interactuando con la aplicación, como información del perfil, carrito de compras, etc.

@ApplicationScoped:

Qué es: Dura todo el tiempo de vida de la aplicación. Se crea cuando se inicia la aplicación y se destruye cuando se apaga la aplicación.
Ejemplo: Todos los estudiantes tienen acceso a la misma lista de cursos disponibles. Esta lista se almacena en un bean de aplicación, así que no importa quién inicie sesión, todos ven la misma lista.
En práctica: Ideal para datos que son comunes a todos los usuarios y no cambian con frecuencia.

@CustomScoped:

Qué es: Permite definir un alcance personalizado, no es muy común y es más avanzado.
Ejemplo: Imagina un escenario donde los estudiantes pueden formar grupos de estudio y cada grupo tiene su propio espacio con una duración limitada.
En práctica: Para casos especiales donde los otros alcances no se adaptan a tus necesidades.

Conclusión: Piensa en el "alcance" como la "longevidad" o "duración de vida" de tus beans. 
Dependiendo de cuánto tiempo necesites que duren los datos, eliges el alcance adecuado. Desde el corto tiempo de un solo clic (@RequestScoped) hasta todo el tiempo que tu aplicación esté ejecutándose (@ApplicationScoped). ¡Espero que estos ejemplos te ayuden a entenderlo mejor!

| Scoope | Longevidad |
| -------| --------- |
| @RequestScoped | Dura solo una petición |