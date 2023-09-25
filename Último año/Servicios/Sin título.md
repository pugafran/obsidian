
DHCP utiliza udp y hace dora dora dora dora dora:

* Discovery, el cliente:
	* Usa un broadcast UDP al puerto 67 para descubrir un servidor
	* En el datagrama puede especificar que IP prefiere (la última usada)
	* Queda a la espera de respuestas en el puerto UDP 68
* Offer, el servidor:
	* Maneja un pool de IPs e información de configuración (DNS, router de salida, etc...)
	* Elige una IP para el cliente
	* Envía una oferta al cliente conteniendo la IP elegida
* Request, el cliente: 
	* Si no recibe respuestas puede reintentar el paso 1
	* Puede recibir varias ofertas
* Acknowledgement

[![Mobile - Jojo's Bizarre Adventure: Diamond Records - Crazy Diamond - The  Models Resource](https://www.models-resource.com/resources/big_icons/32/31147.png?updated=1556440592)