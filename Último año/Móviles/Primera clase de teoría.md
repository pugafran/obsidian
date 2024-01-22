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

También se usa para declarar los permisos que requiere la aplicación, el nivel de la API mínimo requerido por la aplicación, declarar requisitos de hardware/software, declarar bibliotecas y servicios extra necesarios (Google Maps, ...)

Actividades:
Una actividad hereda de la clase Activity, debe implementar unos métodos que el S.O invocará cuando la actividad cambie de estado (callback methods).

Tienen una ventana en la que se puede dibujar, suele ser del tamaño de la pantalla, y puede ser menor, y "flotar" sobre otras ventanas.

![[Pasted image 20240122164811.png]]
Es importante que funcionen y gestionar todos los callback bien porque sino puede reventar la aplicación, te llaman por was y explosiona si no está bien gestionado como arriba.

![[Pasted image 20240122165703.png]]
Entras y le das al botón de atrás, entonces se cierra, vs darle al botón de home, lo del null es un bundle que a saber que coño es xd.

Cambio de configuración( lo de girar la pantalla y que se detruye y se recrea xD)

![[Pasted image 20240122165923.png]]
