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

FC 16Gb/s o Ethernet 10 Gbit/s (ópticos) | Ethernet 1 Gbit/s (RJ-45) | RJ45 serie, micro usb, y usb-a | Mini SAS 4x12 Gb/s

Es un contenedor de discos gestionado por uno o dos expansores SAS.

Proporcionar un sistema de expansión para las cabinas de almacenamiento (sistemas con controlador) de modo que se pueda incrementar muy significativamente el numero de discos gestionados por un controlador.

Una bandeja de discos no puede operar en solitario: funciona siempre de forma subordinada a una cabina con controlador

Ancho: x4 (canales)

Estándar: SAS-3

Anchi de banda: 1200 MB/s

Ancho de banda total: 4 * 1200 = 4800 MB/s

Es un sistema formado por un controlador y una o más bandejas de discos interconectados mediante un bus SAS simple o múltiple.

Implementar infraestructuras de almacenamiento escalables en capacidad permitiendo alcanzar capacidades de almacenamiento extraordinariamente elevadas.

48/48 96/96 180/120 (Gestionar tal cantidad de discos para SSD sería demasiado para un solo controlador) btw es numero maximo de bandeja + cabina

Sí, las dos rutas gestionan tráfico simultaneamente.

Sí, aunque una de las rutas se rompa, el controlador puede continuar las comunicaciones por la otra ruta.

Se trata de una tecnología de comunicación de red tipo serie y bidireccional que utiliza como medio físico de transmisión canal de fibra óptica.

Redes de almacenamiento.

Es el protocolo de la capa de interfaz FC4 encargada de mapear el protocolo SCSI sobre la infraestructura de comunicación fiber channel.

Se basa en la utilización de switches fiber channel para la interconexión de dispositivos fiber channel. Los switches FC pueden interconectarse entre ellos formando topologías de interconexión complejas. 

Es el conjunto de switches y cables FC que forman una red FC.

Fibra óptica.

LC (Lucent connector)

Es un dispositivo que transforma las señales electricas manejadas en los puertos de los switches fiber channel en las señales de luz enviadas a través de los cables de fibra.

Iniciar el proceso de comunicación con un target y gobernar el proceso de acceso al mismo.

En un HBA de un servidor.