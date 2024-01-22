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