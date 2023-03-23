Una cabina de almacenamiento (Disk storage systems) es un equipo informático diseñado para contener discos duros y dispositivos SSD. Proporcionando mecanismos de gestión para los mismos, así como puertos de comunicación para acceder al espacio de almacenamiento que generan.

En los sistemas actuales este bus se implementa siguiendo el estandar SAS.

Son los elementos de conexión de la cabina de almacenamiento a la red de almacenamiento. Habitualmente serán ethernet, fibre channel, o SAS.

Elemento de conexión del sistema de almacenamiento a una consola de administración. Es de tipo ethernet.

Esta arquitectura requiere discos con doble puerto, por lo que deben ser de tipo SAS.

Mediante un nivel de RAID, habitualmente 0, 1, 10, 5, o 6.

Deben ser del mismo tipo (HDD o SDD), y es recomendable que sean de la misma capacidad.

Mediante una partición geométricamente idéntica en todos los discos de un grupo.

Mediante una LUN (Logical Unit Number)

Red de administración

Volúmenes

Los servidores

En principio todos los volúmenes configurados en una cabina de almacenamiento conectada a una red de almacenamiento son visibles(accesibles) a todos los servidores conectados a la misma red.

Como si fuera un disco interno del propio servidor.

La vinculación de un volumen es el proceso de registro del mismo por parte del sistema operativo de un servidor. Una vez registrado, el volumen se comporta como un disco interno del propio servidor.

Se trata de la capacidad de establecer los volúmenes (identificados por sus correspondientes LUN) que serán visibles a cada servidor conectado a la red. Esto facilita las tareas de configuración de los servidores  y evita errores innecesarios 

Se trata de la capacidad de mantener permanentemente replicados uno o varios volúmenes de una cabina de almacenamiento en otra cabina remota. La replicación entre cada volumen origen y remoto es coordinada automáticamente por las cabinas de almacenamiento.

FC 16Gb/s o Ethernet 10 Gbit/s (ópticos) 