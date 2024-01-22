Componentes:
* Actividades
* Servicios
* Proveedores de contenido (Content Providers)
* Receptor de mensajes (Broadcast receivers: te despiertas haces algo y te apagas)

Una aplicación no puede activar directamente un componente de otra, por culpa del sandbox.

Cualquier aplicación puede invocar a través del sistema operativo (intent) un componente de cualquier otra.

Los componentes:
* Se ejecutan en el proceso de la aplicación a la que pertenecen.
* Se ejecutan con permisos restringidos.

intent puede transportar información de una aplicación a otra, sirve para todo menos content providers.

Archivo de manifiesto:
Todas las aplicaciones tienen un xml con todos los componentes de la aplicación, no se puede ejecutar un componente si no está declarado.

También se usa para declarar los permisos que requiere la aplicación, el nivel de la API mínimo requerido por la aplicación, declarar requisitos de hardware/software, declarar bibliotecas y servicios