PID - PPID 
UID real/propietario - GID real/propietario: El que originó el proceso, inicialmente vale 1 getuid getgid

UID efectivo - GID efectivo (Relevantes, con estos ya sabes que pasa, por defecto son iguales que los reales propietarios ¿son los actuales? geteuid getegid) Se pueden cambiar ediante una llamada al sistema o con el permiso especial s

UID guardado  - GID guardado

El root no es el administrador, es administrador cualquier usuario con uid 0

¿Que puede hacer un proceso que tiene privilegios "normales"? (UID != 0):
	- Llamadas al sistema que puedo usar
	- Acceso a memoria secundaria mediante los permisos UNIX

Para máximos privilegios se mira el UID efectivo. ( 0 Max privilegios != 0 no privilegios)

Permisos Unix

rwx | rwx | rwx (Usuario propietario) (Grupo propietario) (Resto de gente)
r => lectura  
w => escritura
x => ejecutable

Programación con llamadas al sistema: Práctica 1

1.  ¿Qué dos procesos especiales existen en UNIX? ¿Qué jerarquía tienen los procesos en UNIX y quién está en el tope de dicha jerarquía? Proceso Init y Kernel. En la parte superior de esta jerarquía se encuentra el proceso init, que es el padre de todos los procesos en el sistema. Todos los demás procesos en el sistema son hijos o nietos de este proceso.
    
2.  Cita TODOS los identificadores de proceso que existen en UNIX e indica cuáles están relacionados con la seguridad del sistema.
    
3.  Implementa el comando UNIX idproc que imprima en pantalla (con mensajes completos y claros) todos los identificadores del proceso.
    
4.  ¿Cuándo tiene un proceso máximos privilegios? Implementa un comando UNIX MaxPriv que cambie los privilegios de un proceso a privilegios de superusuario (máximos privilegios) y, posteriormente, vuelca a la pantalla información que verifique que se han obtenido tales privilegios.
    
5.  ¿Qué tres tipos de acceso (permisos) hay en UNIX? Explica cómo funcionan los tres tipos de permisos UNIX en ficheros y en directorios. ¿Qué hacen los comandos UNIX: chown, chgrp y chmod?
    
6.  Implementa un comando printenv que vuelque a la salida todo el entorno del proceso.