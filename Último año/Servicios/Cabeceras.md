Las restantes lineas del sobre son cabeceras todas con la misma estructura, hay un estandar de como se ponen los datos, es insensible a mayuscula minusculas.

Tipos de cabecera:
* Generales (Peticiones y respuestas)
* Petición ()
* Respuesta
* Entidad (Peticiones y respuestas, metadata para describir el cuerpo)
* Extensión (Usos no estandarizados, para inventar tus propias cabeceras, se recomienda que empiecen por "x-" en plan "x-mamahuevo?:, no es una buena idea")

connection=>keep-alive lo hace el cliente para que el servidor no cierre el stream TCP 

La cabecera host sirve por ejemplo si tienes un pc con dos servidores pero la misma ip y siendo el puerto 80 para http, como distingues un servidor/pagina web de otra? Pues con la cabecera host en plan host:epigijon host:campusvirtual.

User-agent te dice que navegador sistema operativo tiene el cliente.

accept => lista de tipos de MIME que el cliente puede usar

accept-encoding=> si soporta el cliente que acepta contenidos comprimidos, identity que no y gzip que si. (informacion)

Transfer encoding => es una cabecera opcional, si no está, está mandando una respuesta en el cuerpo, si está chunked ya no aparece content length, porque el propio servidor en ese momento no lo sabe, se está generando. El servid