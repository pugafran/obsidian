---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
"\r \n" => CRLF  ^zzJoTw7j

ASCII 13 ^IASnxGez

      CR
(Courage Return) ^7jtnrTRx

ASCII 10 ^MgsRw0sb

    LF
(Line Feed) ^QMgCV2pO

Sintaxis de los mensajes HTTP

Son el contenido de las peticiones y respuestas. Su estructura es la misma para ambas:

Primera línea terminada por \r\n
    En la petición contiene el método solicitado
    En la respuesta contiene el código de estado Campos de cabecera (la mayoría son opcionales)

Cada uno en una línea terminada por \r\n
    Una línea en blanco (\r\n) marca el fin de la cabecera

Contenido (formato libre, según su tipo). 
    Puede estar ausente ^iPoz7bwG

Lo único que importa realmente es el 200 ^2GAV0zp3

CRLFCRLF se acabó la cabecera

get no lleva cuerpo, la petición
puede o no llevar cuerpo, post
si lleva cuerpo.

content length es el cuerpo básicamente ^sKxRWreW

HEAD caga la cabecera
PUT necesita un puerto 
POST es enviar datos del servidor a algo.
OPTIONS te devuelve el servidor que verbos puedes usar. ^bvcFSPKC

CRUD
CREATE POST
READ GET
UPDATE PUT
DELETE DELETE ^HFRRJTGS

Códigos de estado:

100-199 información 
200-299 Éxito
300-399 Redirección
400-499 Error del cliente
500-599 Error del servidor ^8WY4xbn3

`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)
y que te diga, ok dale mi rey.

El cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.

102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.

'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso
que le han pedido.

'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle
nada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.

'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive
en otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta
URL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja
otra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a
estar ahí, va a estar en el otro.

'302 found': ^npN8BafV

Quiero entra al github
get /mipagina ^6M1l7IRH

Yo ^AAhomlSP

Github ^FsCpORzq

301
(Vuelve a pedirmelo que no tengo ni putisima idea de quién eres tonto, vete aquí al formulario del login)
location: login
(toma el login) ^g0t984IR

get /login
(dame el login) ^24KGZrrp

200 OK
(bai bai toma toma) ^gfncqweZ

POST /datoslogin
(envías los datos) ^jORWENHj

302 
location: /mipagina_pugafran
(toma ya sé quien eres, la dirección de
la página es esta.) ^YYz7DqQf

get /mipagina_pugafran
(dámela) ^kjhJTfrY

200 OK
(toma la página) ^E6O7OpyT

302 ya no se usa se usaba
en http 1.0, ahora se usa
el 303 y 307, porque 302 era
ambigüo. ^u7vncDmu

Esto pasa porque en el 302 no sabías
que iba a devolver. ^TvBhQNH2

303 siempre devuelve el verbo get

307 devuelve que vuelvas a hacer el mismo
verbo. ^T7RT41Kd

500 internal server error => cascó un hilo por ejemplo
501 not implemented => servidor nuevo, apache por ejemplo, mientras estaban implementando se iba haciendo
poco a poco y si el cliente pedía algo que todavía no estaba implementado caga el 501, imagina que tienes get
pero no delete entonces si haces delete te sale eso.
502 bad gateaway => es cuando el servidor realmente no es quien computa la respuesta, sino el servidor de aplicaciones
que yo que se si está arrancando no tira y el servidor te dice, 502. ^XZ5KTBSW

Cliente ^vaOzb2Gy

Servidor
HTTP ^QS42kx73

Servidor de aplicaciones ^eddHftwk


# Embedded files
d321decfa643ee695ee8d6e20bd7a0da0be64d5b: [[Pasted Image 20230929004635_321.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.8.19",
	"elements": [
		{
			"type": "text",
			"version": 65,
			"versionNonce": 73517525,
			"isDeleted": false,
			"id": "zzJoTw7j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -274,
			"y": -112.8125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 162.9999542236328,
			"height": 24,
			"seed": 2041295050,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "_lE5J6bSk-sPvU52ucdNp",
					"type": "arrow"
				},
				{
					"id": "4Ld5i9La4TixvZDk8Bkr0",
					"type": "arrow"
				}
			],
			"updated": 1695833221603,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "\"\\r \\n\" => CRLF ",
			"rawText": "\"\\r \\n\" => CRLF ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\"\\r \\n\" => CRLF "
		},
		{
			"type": "arrow",
			"version": 64,
			"versionNonce": 1121462779,
			"isDeleted": false,
			"id": "_lE5J6bSk-sPvU52ucdNp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260.9765625,
			"y": -82.12890625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62.378194875418444,
			"height": 115.98046875,
			"seed": 674412054,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "zzJoTw7j",
				"focus": 0.6641597433339615,
				"gap": 6.68359375
			},
			"endBinding": {
				"elementId": "IASnxGez",
				"focus": -0.15778669998442443,
				"gap": 5.1796875
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-62.378194875418444,
					115.98046875
				]
			]
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 362006325,
			"isDeleted": false,
			"id": "IASnxGez",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -369.0546875,
			"y": 39.03125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 88.99995422363281,
			"height": 24,
			"seed": 1192680982,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "_lE5J6bSk-sPvU52ucdNp",
					"type": "arrow"
				},
				{
					"id": "5iJoA5f4NkkXYpHqGzqnp",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ASCII 13",
			"rawText": "ASCII 13",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ASCII 13"
		},
		{
			"type": "text",
			"version": 106,
			"versionNonce": 332870299,
			"isDeleted": false,
			"id": "7jtnrTRx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -441.03125,
			"y": 133.99609375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 168.37985229492188,
			"height": 48,
			"seed": 1324931798,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "5iJoA5f4NkkXYpHqGzqnp",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "      CR\n(Courage Return)",
			"rawText": "      CR\n(Courage Return)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "      CR\n(Courage Return)"
		},
		{
			"type": "arrow",
			"version": 119,
			"versionNonce": 509548693,
			"isDeleted": false,
			"id": "5iJoA5f4NkkXYpHqGzqnp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -333.3915548127065,
			"y": 67.640625,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.982263427964995,
			"height": 60.15625,
			"seed": 2137865418,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "IASnxGez",
				"focus": 0.03908548488332477,
				"gap": 4.609375
			},
			"endBinding": {
				"elementId": "7jtnrTRx",
				"focus": -0.14947304630058475,
				"gap": 6.19921875
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-24.982263427964995,
					60.15625
				]
			]
		},
		{
			"type": "arrow",
			"version": 132,
			"versionNonce": 1294739259,
			"isDeleted": false,
			"id": "4Ld5i9La4TixvZDk8Bkr0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -134.51767739265293,
			"y": -80.328125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.626749253204224,
			"height": 100.54296875,
			"seed": 224396426,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "zzJoTw7j",
				"focus": -0.520218492950217,
				"gap": 8.484375
			},
			"endBinding": {
				"elementId": "MgsRw0sb",
				"focus": 0.21637756457365262,
				"gap": 10.04296875
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					58.626749253204224,
					100.54296875
				]
			]
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 142163445,
			"isDeleted": false,
			"id": "MgsRw0sb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -118.7656021118164,
			"y": 30.2578125,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.13995361328125,
			"height": 24,
			"seed": 1013975318,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "Fga_xsRiZP5b3A10tZrqD",
					"type": "arrow"
				},
				{
					"id": "4Ld5i9La4TixvZDk8Bkr0",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ASCII 10",
			"rawText": "ASCII 10",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ASCII 10"
		},
		{
			"type": "text",
			"version": 543,
			"versionNonce": 1161398235,
			"isDeleted": false,
			"id": "QMgCV2pO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -63.77976989746094,
			"y": 130.97060315863695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 106.43991088867188,
			"height": 48,
			"seed": 1290716938,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "Fga_xsRiZP5b3A10tZrqD",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "    LF\n(Line Feed)",
			"rawText": "    LF\n(Line Feed)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "    LF\n(Line Feed)"
		},
		{
			"type": "arrow",
			"version": 993,
			"versionNonce": 1793570645,
			"isDeleted": false,
			"id": "Fga_xsRiZP5b3A10tZrqD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -51.5934651353478,
			"y": 66.79482190863695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.899345218741573,
			"height": 57.9765625,
			"seed": 1401718422,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "MgsRw0sb",
				"focus": -0.2813554325752103,
				"gap": 12.537009408636948
			},
			"endBinding": {
				"elementId": "QMgCV2pO",
				"focus": -0.14947304630058475,
				"gap": 6.19921875
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					20.899345218741573,
					57.9765625
				]
			]
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 1645335675,
			"isDeleted": false,
			"id": "iPoz7bwG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -509.27526075000037,
			"y": 246.81035937825493,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 978.4391479492188,
			"height": 312,
			"seed": 938075222,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Sintaxis de los mensajes HTTP\n\nSon el contenido de las peticiones y respuestas. Su estructura es la misma para ambas:\n\nPrimera línea terminada por \\r\\n\n    En la petición contiene el método solicitado\n    En la respuesta contiene el código de estado Campos de cabecera (la mayoría son opcionales)\n\nCada uno en una línea terminada por \\r\\n\n    Una línea en blanco (\\r\\n) marca el fin de la cabecera\n\nContenido (formato libre, según su tipo). \n    Puede estar ausente",
			"rawText": "Sintaxis de los mensajes HTTP\n\nSon el contenido de las peticiones y respuestas. Su estructura es la misma para ambas:\n\nPrimera línea terminada por \\r\\n\n    En la petición contiene el método solicitado\n    En la respuesta contiene el código de estado Campos de cabecera (la mayoría son opcionales)\n\nCada uno en una línea terminada por \\r\\n\n    Una línea en blanco (\\r\\n) marca el fin de la cabecera\n\nContenido (formato libre, según su tipo). \n    Puede estar ausente",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Sintaxis de los mensajes HTTP\n\nSon el contenido de las peticiones y respuestas. Su estructura es la misma para ambas:\n\nPrimera línea terminada por \\r\\n\n    En la petición contiene el método solicitado\n    En la respuesta contiene el código de estado Campos de cabecera (la mayoría son opcionales)\n\nCada uno en una línea terminada por \\r\\n\n    Una línea en blanco (\\r\\n) marca el fin de la cabecera\n\nContenido (formato libre, según su tipo). \n    Puede estar ausente"
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1610613941,
			"isDeleted": false,
			"id": "2GAV0zp3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 167.95728213651523,
			"y": -41.48214751888477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 416.19970703125,
			"height": 24,
			"seed": 892582875,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Lo único que importa realmente es el 200",
			"rawText": "Lo único que importa realmente es el 200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Lo único que importa realmente es el 200"
		},
		{
			"type": "text",
			"version": 275,
			"versionNonce": 595037467,
			"isDeleted": false,
			"id": "sKxRWreW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 186.1129632065149,
			"y": 24.71385963733084,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 395.1396484375,
			"height": 168,
			"seed": 210248859,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente",
			"rawText": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente"
		},
		{
			"type": "text",
			"version": 232,
			"versionNonce": 459777557,
			"isDeleted": false,
			"id": "bvcFSPKC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -335.0133589706546,
			"y": 748.1135110591093,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 581.0594482421875,
			"height": 96,
			"seed": 771838261,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar.",
			"rawText": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar."
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 1826435515,
			"isDeleted": false,
			"id": "HFRRJTGS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.39681743514393,
			"y": 557.2572488888079,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 178.19992065429688,
			"height": 120,
			"seed": 2143936373,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE",
			"rawText": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE"
		},
		{
			"type": "text",
			"version": 200,
			"versionNonce": 1075059573,
			"isDeleted": false,
			"id": "8WY4xbn3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.59682662825435,
			"y": 1007.6117084863769,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 269.05975341796875,
			"height": 168,
			"seed": 1088548149,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor",
			"rawText": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor"
		},
		{
			"type": "text",
			"version": 1576,
			"versionNonce": 258294363,
			"isDeleted": false,
			"id": "npN8BafV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -657.7322315523862,
			"y": 1290.1656509975637,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1098.51904296875,
			"height": 480,
			"seed": 1509042107,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':",
			"rawText": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':"
		},
		{
			"type": "arrow",
			"version": 356,
			"versionNonce": 2100109558,
			"isDeleted": false,
			"id": "M6URqLX3Wnl4AN6QRkmgB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -623.5441237274797,
			"y": 1862.1860141935026,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 362.9455891480648,
			"height": 11.153092728240836,
			"seed": 772518901,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6M1l7IRH"
				}
			],
			"updated": 1696856980627,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 2.9479142258097397,
				"focus": 0.0586109857031189
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 6.107631523864745,
				"focus": -0.07475561703002366
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					362.9455891480648,
					11.153092728240836
				]
			]
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 958053973,
			"isDeleted": false,
			"id": "6M1l7IRH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -551.9112141039046,
			"y": 1843.762543196368,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 219.6798095703125,
			"height": 48,
			"seed": 2103656021,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695941134697,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Quiero entra al github\nget /mipagina",
			"rawText": "Quiero entra al github\nget /mipagina",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "M6URqLX3Wnl4AN6QRkmgB",
			"originalText": "Quiero entra al github\nget /mipagina"
		},
		{
			"type": "ellipse",
			"version": 238,
			"versionNonce": 1154918299,
			"isDeleted": false,
			"id": "J1LHvgNa7ovsfWbT3lnt3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1150.606363574971,
			"y": 1811.2421247268246,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 532,
			"height": 81,
			"seed": 981132699,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "AAhomlSP"
				},
				{
					"id": "xoCE_KYmd0Vc_Z57gigyJ",
					"type": "arrow"
				},
				{
					"id": "uaFI_CRDUKjgTGJhnBPfo",
					"type": "arrow"
				},
				{
					"id": "LQVF_W4YA2eIvZSf590yw",
					"type": "arrow"
				},
				{
					"id": "pzbdo3BQgxo3ngcsydz_N",
					"type": "arrow"
				},
				{
					"id": "M6URqLX3Wnl4AN6QRkmgB",
					"type": "arrow"
				},
				{
					"id": "4B-XLgDlkp-0Zv89QzFQC",
					"type": "arrow"
				},
				{
					"id": "w_62iYnNZ_UJPft65NNz7",
					"type": "arrow"
				},
				{
					"id": "K7xKKijMvDE1_WttJkAZg",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 385708949,
			"isDeleted": false,
			"id": "AAhomlSP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -895.3967566894403,
			"y": 1839.6043000887694,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.399978637695312,
			"height": 24,
			"seed": 1725484309,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Yo",
			"rawText": "Yo",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "J1LHvgNa7ovsfWbT3lnt3",
			"originalText": "Yo"
		},
		{
			"type": "ellipse",
			"version": 444,
			"versionNonce": 2020932667,
			"isDeleted": false,
			"id": "FIDBMLzjrfzve5OMQrY0z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -254.97865379802886,
			"y": 1819.2007068962967,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 525,
			"height": 116,
			"seed": 2000812539,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "M6URqLX3Wnl4AN6QRkmgB",
					"type": "arrow"
				},
				{
					"type": "text",
					"id": "FsCpORzq"
				},
				{
					"id": "xoCE_KYmd0Vc_Z57gigyJ",
					"type": "arrow"
				},
				{
					"id": "uaFI_CRDUKjgTGJhnBPfo",
					"type": "arrow"
				},
				{
					"id": "pzbdo3BQgxo3ngcsydz_N",
					"type": "arrow"
				},
				{
					"id": "LQVF_W4YA2eIvZSf590yw",
					"type": "arrow"
				},
				{
					"id": "4B-XLgDlkp-0Zv89QzFQC",
					"type": "arrow"
				},
				{
					"id": "w_62iYnNZ_UJPft65NNz7",
					"type": "arrow"
				},
				{
					"id": "K7xKKijMvDE1_WttJkAZg",
					"type": "arrow"
				}
			],
			"updated": 1695833221604,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 848574709,
			"isDeleted": false,
			"id": "FsCpORzq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -24.02415364709526,
			"y": 1865.1885135874768,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62.85993957519531,
			"height": 24,
			"seed": 1332543477,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Github",
			"rawText": "Github",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FIDBMLzjrfzve5OMQrY0z",
			"originalText": "Github"
		},
		{
			"type": "arrow",
			"version": 803,
			"versionNonce": 269062710,
			"isDeleted": false,
			"id": "xoCE_KYmd0Vc_Z57gigyJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -155.93862561591823,
			"y": 1924.6541779874956,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 599.2083521516406,
			"height": 200,
			"seed": 1814001045,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "g0t984IR"
				}
			],
			"updated": 1696856980628,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 2.315150745017789,
				"focus": -0.08895811440645074
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 8.80400759566814,
				"focus": 0.01172898438291013
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-292.08810254679355,
					71.07965195238307
				],
				[
					-599.2083521516406,
					-29.421908693508612
				]
			]
		},
		{
			"type": "text",
			"version": 229,
			"versionNonce": 1410719909,
			"isDeleted": false,
			"id": "g0t984IR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -706.3165230845868,
			"y": 1935.7338299398787,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 516.57958984375,
			"height": 120,
			"seed": 1920418619,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695907448571,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "301\n(Vuelve a pedirmelo que no tengo ni putisima idea de\nquién eres tonto, vete aquí al formulario del login)\nlocation: login\n(toma el login)",
			"rawText": "301\n(Vuelve a pedirmelo que no tengo ni putisima idea de quién eres tonto, vete aquí al formulario del login)\nlocation: login\n(toma el login)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xoCE_KYmd0Vc_Z57gigyJ",
			"originalText": "301\n(Vuelve a pedirmelo que no tengo ni putisima idea de quién eres tonto, vete aquí al formulario del login)\nlocation: login\n(toma el login)"
		},
		{
			"type": "arrow",
			"version": 608,
			"versionNonce": 2092454954,
			"isDeleted": false,
			"id": "uaFI_CRDUKjgTGJhnBPfo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -825.8274579361921,
			"y": 1903.272617034023,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 745.4659077752531,
			"height": 313.46887399597927,
			"seed": 694485755,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "24KGZrrp"
				}
			],
			"updated": 1696856980628,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 12.220482609333175,
				"focus": 0.010239473076643548
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 1.1654407241412983,
				"focus": 0.05467088489911619
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					374.402695432169,
					313.46887399597927
				],
				[
					745.4659077752531,
					29.710245312525103
				]
			]
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 154249259,
			"isDeleted": false,
			"id": "24KGZrrp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -521.2547032999215,
			"y": 2192.741491030002,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 139.65988159179688,
			"height": 48,
			"seed": 503151835,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695907448571,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "get /login\n(dame el login)",
			"rawText": "get /login\n(dame el login)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uaFI_CRDUKjgTGJhnBPfo",
			"originalText": "get /login\n(dame el login)"
		},
		{
			"type": "arrow",
			"version": 724,
			"versionNonce": 867188458,
			"isDeleted": false,
			"id": "LQVF_W4YA2eIvZSf590yw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -9.60881819043783,
			"y": 1938.291733498244,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 860.6886082920232,
			"height": 456.1461050493772,
			"seed": 615150581,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "gfncqweZ"
				}
			],
			"updated": 1696856980629,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 3.218372106316721,
				"focus": -0.18483472157656688
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 12.579569325140199,
				"focus": 0.11853699325606895
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-463.86823092547564,
					422.60600072890134
				],
				[
					-860.6886082920232,
					-33.54010432047585
				]
			]
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 440173573,
			"isDeleted": false,
			"id": "gfncqweZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.2669737374955,
			"y": 2336.8977342271455,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 197.57984924316406,
			"height": 48,
			"seed": 1260970005,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695907448571,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200 OK\n(bai bai toma toma)",
			"rawText": "200 OK\n(bai bai toma toma)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "LQVF_W4YA2eIvZSf590yw",
			"originalText": "200 OK\n(bai bai toma toma)"
		},
		{
			"type": "arrow",
			"version": 986,
			"versionNonce": 147184502,
			"isDeleted": false,
			"id": "pzbdo3BQgxo3ngcsydz_N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -937.5683343650653,
			"y": 1904.4006077365261,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 987.1387701197775,
			"height": 644.7203510919303,
			"seed": 1827790651,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "jORWENHj"
				}
			],
			"updated": 1696856980629,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 13.132730275341245,
				"focus": 0.3453854990083606
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 4.125393660408896,
				"focus": -0.3471669491388415
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					483.71405938512953,
					644.7203510919303
				],
				[
					987.1387701197775,
					34.14803772703681
				]
			]
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 159971163,
			"isDeleted": false,
			"id": "jORWENHj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -544.5741999066936,
			"y": 2525.1209588284564,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181.43984985351562,
			"height": 48,
			"seed": 309104821,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833221604,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "POST /datoslogin\n(envías los datos)",
			"rawText": "POST /datoslogin\n(envías los datos)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pzbdo3BQgxo3ngcsydz_N",
			"originalText": "POST /datoslogin\n(envías los datos)"
		},
		{
			"type": "arrow",
			"version": 338,
			"versionNonce": 1302789302,
			"isDeleted": false,
			"id": "4B-XLgDlkp-0Zv89QzFQC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120.61827412572995,
			"y": 1933.8783457280447,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1110.1803412929362,
			"height": 785.6036950330997,
			"seed": 1758375419,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "YYz7DqQf"
				}
			],
			"updated": 1696856980629,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 4.564675140933403,
				"focus": -0.587546770835285
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 7.791310777245215,
				"focus": 0.5067426702311622
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-571.736880891049,
					748.0696414710296
				],
				[
					-1110.1803412929362,
					-37.534053562070085
				]
			]
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 415328971,
			"isDeleted": false,
			"id": "YYz7DqQf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -644.6684572291863,
			"y": 2633.9479871990743,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 387.0997009277344,
			"height": 96,
			"seed": 1940074581,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695907448571,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "302 \nlocation: /mipagina_pugafran\n(toma ya sé quien eres, la dirección de\nla página es esta.)",
			"rawText": "302 \nlocation: /mipagina_pugafran\n(toma ya sé quien eres, la dirección de\nla página es esta.)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4B-XLgDlkp-0Zv89QzFQC",
			"originalText": "302 \nlocation: /mipagina_pugafran\n(toma ya sé quien eres, la dirección de\nla página es esta.)"
		},
		{
			"type": "arrow",
			"version": 367,
			"versionNonce": 31248810,
			"isDeleted": false,
			"id": "w_62iYnNZ_UJPft65NNz7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1037.5922979358193,
			"y": 1901.3863766448976,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1202.9177937399381,
			"height": 1033.7469234348805,
			"seed": 92537397,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "kjhJTfrY"
				}
			],
			"updated": 1696856980629,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 18.391237395055157,
				"focus": 0.6790661640571964
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 5.555353805157637,
				"focus": -0.7139299720008404
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					589.835074077082,
					1033.7469234348805
				],
				[
					1202.9177937399381,
					27.189408639371777
				]
			]
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 1431385877,
			"isDeleted": false,
			"id": "kjhJTfrY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -563.5971286438935,
			"y": 2911.133300079778,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 231.6798095703125,
			"height": 48,
			"seed": 1582833499,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833232207,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "get /mipagina_pugafran\n(dámela)",
			"rawText": "get /mipagina_pugafran\n(dámela)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "w_62iYnNZ_UJPft65NNz7",
			"originalText": "get /mipagina_pugafran\n(dámela)"
		},
		{
			"type": "arrow",
			"version": 184,
			"versionNonce": 877786614,
			"isDeleted": false,
			"id": "K7xKKijMvDE1_WttJkAZg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 203.41643885923503,
			"y": 1930.0556707981095,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1328.538668672582,
			"height": 1254.5139280613434,
			"seed": 1175027483,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "E6O7OpyT"
				}
			],
			"updated": 1696856980630,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 16.285369203271117,
				"focus": -0.8496193302145255
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 12.807848054546156,
				"focus": 0.9554953879425331
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-654.0644282388694,
					1203.162819780121
				],
				[
					-1328.538668672582,
					-51.35110828122242
				]
			]
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 1584905061,
			"isDeleted": false,
			"id": "E6O7OpyT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -530.7479268185991,
			"y": 3109.2184905782306,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 160.1998748779297,
			"height": 48,
			"seed": 1895841045,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695907448572,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200 OK\n(toma la página)",
			"rawText": "200 OK\n(toma la página)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "K7xKKijMvDE1_WttJkAZg",
			"originalText": "200 OK\n(toma la página)"
		},
		{
			"type": "text",
			"version": 201,
			"versionNonce": 2128882998,
			"isDeleted": false,
			"id": "u7vncDmu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 319.1648190956083,
			"y": 2830.1881543089266,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 307.1198425292969,
			"height": 96,
			"seed": 214137147,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696857016409,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "302 ya no se usa se usaba\nen http 1.0, ahora se usa\nel 303 y 307, porque 302 era\nambigüo.",
			"rawText": "302 ya no se usa se usaba\nen http 1.0, ahora se usa\nel 303 y 307, porque 302 era\nambigüo.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "302 ya no se usa se usaba\nen http 1.0, ahora se usa\nel 303 y 307, porque 302 era\nambigüo."
		},
		{
			"type": "text",
			"version": 143,
			"versionNonce": 72898870,
			"isDeleted": false,
			"id": "TvBhQNH2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 312.8673553888832,
			"y": 3076.0731421925866,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 390.23974609375,
			"height": 48,
			"seed": 794151637,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696857013063,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Esto pasa porque en el 302 no sabías\nque iba a devolver.",
			"rawText": "Esto pasa porque en el 302 no sabías\nque iba a devolver.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Esto pasa porque en el 302 no sabías\nque iba a devolver."
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 1007594325,
			"isDeleted": false,
			"id": "T7RT41Kd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 314.8553270881232,
			"y": 2960.419970352431,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 429.7596435546875,
			"height": 96,
			"seed": 2012833371,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695833509406,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "303 siempre devuelve el verbo get\n\n307 devuelve que vuelvas a hacer el mismo\nverbo.",
			"rawText": "303 siempre devuelve el verbo get\n\n307 devuelve que vuelvas a hacer el mismo\nverbo.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "303 siempre devuelve el verbo get\n\n307 devuelve que vuelvas a hacer el mismo\nverbo."
		},
		{
			"type": "image",
			"version": 269,
			"versionNonce": 1603833013,
			"isDeleted": false,
			"id": "uHHFt288tf1zrmZOtnYif",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -721.065065914953,
			"y": 968.1675703661065,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 357.7505330437114,
			"height": 218.79815209340032,
			"seed": 540683189,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1695941298680,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "d321decfa643ee695ee8d6e20bd7a0da0be64d5b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 600,
			"versionNonce": 620908813,
			"isDeleted": false,
			"id": "XZ5KTBSW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -15.95037574848459,
			"y": 3339.7421673812496,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1209.218994140625,
			"height": 144,
			"seed": 108410605,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696252313220,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "500 internal server error => cascó un hilo por ejemplo\n501 not implemented => servidor nuevo, apache por ejemplo, mientras estaban implementando se iba haciendo\npoco a poco y si el cliente pedía algo que todavía no estaba implementado caga el 501, imagina que tienes get\npero no delete entonces si haces delete te sale eso.\n502 bad gateaway => es cuando el servidor realmente no es quien computa la respuesta, sino el servidor de aplicaciones\nque yo que se si está arrancando no tira y el servidor te dice, 502.",
			"rawText": "500 internal server error => cascó un hilo por ejemplo\n501 not implemented => servidor nuevo, apache por ejemplo, mientras estaban implementando se iba haciendo\npoco a poco y si el cliente pedía algo que todavía no estaba implementado caga el 501, imagina que tienes get\npero no delete entonces si haces delete te sale eso.\n502 bad gateaway => es cuando el servidor realmente no es quien computa la respuesta, sino el servidor de aplicaciones\nque yo que se si está arrancando no tira y el servidor te dice, 502.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "500 internal server error => cascó un hilo por ejemplo\n501 not implemented => servidor nuevo, apache por ejemplo, mientras estaban implementando se iba haciendo\npoco a poco y si el cliente pedía algo que todavía no estaba implementado caga el 501, imagina que tienes get\npero no delete entonces si haces delete te sale eso.\n502 bad gateaway => es cuando el servidor realmente no es quien computa la respuesta, sino el servidor de aplicaciones\nque yo que se si está arrancando no tira y el servidor te dice, 502."
		},
		{
			"type": "rectangle",
			"version": 35,
			"versionNonce": 1936722221,
			"isDeleted": false,
			"id": "Uun_Ts7mI2RGLWU72Yj4X",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -82.50132787285008,
			"y": 3556.315627040508,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 265,
			"height": 126,
			"seed": 1671919117,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "vaOzb2Gy"
				},
				{
					"id": "p3KN2m8o2Y79m9iNdOTy3",
					"type": "arrow"
				}
			],
			"updated": 1696252281660,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 8,
			"versionNonce": 1741362157,
			"isDeleted": false,
			"id": "vaOzb2Gy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 17.478706001661635,
			"y": 3607.315627040508,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 65.03993225097656,
			"height": 24,
			"seed": 1630155373,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696252218179,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Cliente",
			"rawText": "Cliente",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Uun_Ts7mI2RGLWU72Yj4X",
			"originalText": "Cliente"
		},
		{
			"type": "rectangle",
			"version": 101,
			"versionNonce": 531723043,
			"isDeleted": false,
			"id": "MJpUVhGqSM8O6-XITNsQW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.7024344651037,
			"y": 3556.5065216032194,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 265,
			"height": 126,
			"seed": 701270275,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "QS42kx73"
				},
				{
					"id": "p3KN2m8o2Y79m9iNdOTy3",
					"type": "arrow"
				},
				{
					"id": "laszENIset_Zvy9dPgPei",
					"type": "arrow"
				}
			],
			"updated": 1696252284356,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 422828333,
			"isDeleted": false,
			"id": "QS42kx73",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 326.40247718971307,
			"y": 3595.5065216032194,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.59991455078125,
			"height": 48,
			"seed": 232701101,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696252228238,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Servidor\nHTTP",
			"rawText": "Servidor\nHTTP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "MJpUVhGqSM8O6-XITNsQW",
			"originalText": "Servidor\nHTTP"
		},
		{
			"type": "rectangle",
			"version": 105,
			"versionNonce": 738006723,
			"isDeleted": false,
			"id": "iRF2QcgOi3-q2UO57mqMS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 569.0225432255866,
			"y": 3566.5900395728795,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 516,
			"height": 103,
			"seed": 1463880451,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "eddHftwk"
				},
				{
					"id": "laszENIset_Zvy9dPgPei",
					"type": "arrow"
				}
			],
			"updated": 1696252284356,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 764115085,
			"isDeleted": false,
			"id": "eddHftwk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 710.6326506474616,
			"y": 3606.0900395728795,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 232.77978515625,
			"height": 24,
			"seed": 1740028653,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1696252251439,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Servidor de aplicaciones",
			"rawText": "Servidor de aplicaciones",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "iRF2QcgOi3-q2UO57mqMS",
			"originalText": "Servidor de aplicaciones"
		},
		{
			"type": "arrow",
			"version": 18,
			"versionNonce": 1652125814,
			"isDeleted": false,
			"id": "p3KN2m8o2Y79m9iNdOTy3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 198.82275243882245,
			"y": 3620.6317948149913,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.43848368711909,
			"height": 0,
			"seed": 1567613635,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1696856980630,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Uun_Ts7mI2RGLWU72Yj4X",
				"gap": 16.32408031167256,
				"focus": 0.020891551975926122
			},
			"endBinding": {
				"elementId": "MJpUVhGqSM8O6-XITNsQW",
				"gap": 11.441198339162156,
				"focus": -0.017861479551934203
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					22.43848368711909,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 51,
			"versionNonce": 1810123510,
			"isDeleted": false,
			"id": "laszENIset_Zvy9dPgPei",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 513.8389692414809,
			"y": 3623.3980914605972,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41.5748263420744,
			"height": 3.0543130033811394,
			"seed": 203337667,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1696856980631,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "MJpUVhGqSM8O6-XITNsQW",
				"gap": 16.136534776377175,
				"focus": 0.203634940698697
			},
			"endBinding": {
				"elementId": "iRF2QcgOi3-q2UO57mqMS",
				"gap": 13.60874764203129,
				"focus": 0.2512291246790149
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					41.5748263420744,
					-3.0543130033811394
				]
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 499.96209238139534,
		"scrollY": -2367.950580327962,
		"zoom": {
			"value": 0.9672394180297853
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"colorPalette": {},
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%