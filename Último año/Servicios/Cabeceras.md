Las restantes lineas del sobre son cabeceras todas con la misma estructura, hay un estandar de como se ponen los datos, es insensible a mayuscula minusculas.

Tipos de cabecera:
* Generales (Peticiones y respuestas)
* Petición ()
* Respuesta
* Entidad (Peticiones y respuestas, metadata para describir el cuerpo)
* Extensión (Usos no estandarizados, para inventar tus propias cabeceras, se recomienda que empiecen por "x-" en plan "x-mamahuevo?:, no es una buena idea")

connection=>keep-alive lo hace el cliente para que el servidor no cierre el stream TCP 