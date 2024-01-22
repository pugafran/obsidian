Componentes:
* Actividades
* Servicios
* Proveedores de contenido (Content Providers)
* Receptor de mensajes (Broadcast receivers: te despiertas haces algo y te apagas)

Una aplicación no puede activar directamente un componente de otra, por culpa del sandbox.

Cualquier aplicación puede invocar a través del sistema operativo un componente de cualquier otra.

Los componentes:
* Se ejecutan en el proceso de la aplicación a la que pertenecen.
* Se ejecutan con permisos restringidos.