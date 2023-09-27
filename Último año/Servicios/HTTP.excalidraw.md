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
			"version": 64,
			"versionNonce": 1366863946,
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
			"updated": 1695831118443,
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
			"version": 63,
			"versionNonce": 1561109962,
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
			"updated": 1695831119619,
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
			"version": 74,
			"versionNonce": 609228554,
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
			"updated": 1695831119619,
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
			"version": 105,
			"versionNonce": 1592835850,
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
			"updated": 1695831107702,
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
			"version": 118,
			"versionNonce": 1422482570,
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
			"updated": 1695831119620,
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
			"version": 131,
			"versionNonce": 82194954,
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
			"updated": 1695831163926,
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
			"version": 202,
			"versionNonce": 1230326678,
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
			"updated": 1695831163926,
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
			"version": 542,
			"versionNonce": 524556566,
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
			"updated": 1695831163803,
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
			"version": 992,
			"versionNonce": 118712534,
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
			"updated": 1695831163926,
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
			"version": 99,
			"versionNonce": 1933866965,
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
			"updated": 1695831553904,
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
			"id": "2GAV0zp3",
			"type": "text",
			"x": 167.95728213651523,
			"y": -41.48214751888477,
			"width": 416.19970703125,
			"height": 24,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 892582875,
			"version": 83,
			"versionNonce": 226342005,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695831667330,
			"link": null,
			"locked": false,
			"text": "Lo único que importa realmente es el 200",
			"rawText": "Lo único que importa realmente es el 200",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Lo único que importa realmente es el 200"
		},
		{
			"id": "sKxRWreW",
			"type": "text",
			"x": 186.1129632065149,
			"y": 24.71385963733084,
			"width": 395.1396484375,
			"height": 168,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 210248859,
			"version": 274,
			"versionNonce": 399223413,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695831668498,
			"link": null,
			"locked": false,
			"text": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente",
			"rawText": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CRLFCRLF se acabó la cabecera\n\nget no lleva cuerpo, la petición\npuede o no llevar cuerpo, post\nsi lleva cuerpo.\n\ncontent length es el cuerpo básicamente"
		},
		{
			"id": "bvcFSPKC",
			"type": "text",
			"x": -335.0133589706546,
			"y": 748.1135110591093,
			"width": 581.0594482421875,
			"height": 96,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 771838261,
			"version": 231,
			"versionNonce": 1956579611,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695831855934,
			"link": null,
			"locked": false,
			"text": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar.",
			"rawText": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar.",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "HEAD caga la cabecera\nPUT necesita un puerto \nPOST es enviar datos del servidor a algo.\nOPTIONS te devuelve el servidor que verbos puedes usar."
		},
		{
			"id": "HFRRJTGS",
			"type": "text",
			"x": 232.39681743514393,
			"y": 557.2572488888079,
			"width": 178.19992065429688,
			"height": 120,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 2143936373,
			"version": 79,
			"versionNonce": 1323517557,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695831917581,
			"link": null,
			"locked": false,
			"text": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE",
			"rawText": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CRUD\nCREATE POST\nREAD GET\nUPDATE PUT\nDELETE DELETE"
		},
		{
			"id": "8WY4xbn3",
			"type": "text",
			"x": -287.59682662825435,
			"y": 1007.6117084863769,
			"width": 269.05975341796875,
			"height": 168,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1088548149,
			"version": 199,
			"versionNonce": 2079121749,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832018898,
			"link": null,
			"locked": false,
			"text": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor",
			"rawText": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Códigos de estado:\n\n100-199 información \n200-299 Éxito\n300-399 Redirección\n400-499 Error del cliente\n500-599 Error del servidor"
		},
		{
			"id": "npN8BafV",
			"type": "text",
			"x": -657.7322315523862,
			"y": 1290.1656509975637,
			"width": 1098.51904296875,
			"height": 480,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1509042107,
			"version": 1575,
			"versionNonce": 1921535637,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832617936,
			"link": null,
			"locked": false,
			"text": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':",
			"rawText": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "`100 continue' => Es preguntarle al cliente si puede hacer algo (mandar un fichero)\ny que te diga, ok dale mi rey.\n\nEl cliente manda un post mediante cabeceras especiales para hacer lo del 100 continue.\n\n102 es por si quieres cambiar de http 1.1 a 2.0 o algo y que te diga, altoke mirey.\n\n'200 OK' La petición se ha completado con éxito' Junto con el cuerpo que es el recurso\nque le han pedido.\n\n'204 No content' La petición se ha completado con éxito pero no tiene necesidad de devolverle\nnada, por ejemplo si hace un DELETE, ha pasado, pero no tiene por qué mandarle nada, se borró y ya.\n\n'301 moved permanently' Redirección, el fichero estaba en un domicilio, vas y te dice que no que ahora vive\nen otro sitio, pues eso. El cliente solicita un recurso al servidor y este responde con 301, ya no está en esta\nURL sino en otra, y la URL válida la manda en una cabecera 'location', es posible que del nuevo URL surja\notra redirección. Un navegador sigue las redirecciones automáticamente. En este caso es , ya nunca va más a\nestar ahí, va a estar en el otro.\n\n'302 found':"
		},
		{
			"id": "M6URqLX3Wnl4AN6QRkmgB",
			"type": "arrow",
			"x": -618.4783686603103,
			"y": 1860.39931487537,
			"width": 357.979634732147,
			"height": 17.815056854626846,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 772518901,
			"version": 50,
			"versionNonce": 1393307861,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "6M1l7IRH"
				}
			],
			"updated": 1695832690455,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					357.979634732147,
					17.815056854626846
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"focus": -0.07475561703002366,
				"gap": 6.06576555826593
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "6M1l7IRH",
			"type": "text",
			"x": -549.3284560793932,
			"y": 1845.3068433026835,
			"width": 219.6798095703125,
			"height": 48,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 2103656021,
			"version": 46,
			"versionNonce": 987782491,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832680304,
			"link": null,
			"locked": false,
			"text": "Quiero entra al github\nget /mipagina",
			"rawText": "Quiero entra al github\nget /mipagina",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "M6URqLX3Wnl4AN6QRkmgB",
			"originalText": "Quiero entra al github\nget /mipagina"
		},
		{
			"id": "J1LHvgNa7ovsfWbT3lnt3",
			"type": "ellipse",
			"x": -698.1516038079092,
			"y": 1811.5341036410823,
			"width": 79.09048046587645,
			"height": 80.4160421714846,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 981132699,
			"version": 114,
			"versionNonce": 2039911061,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832664922,
			"link": null,
			"locked": false
		},
		{
			"id": "FIDBMLzjrfzve5OMQrY0z",
			"type": "ellipse",
			"x": -254.44136836321752,
			"y": 1819.598279342382,
			"width": 120.43733552470303,
			"height": 115.20485510782919,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 2000812539,
			"version": 335,
			"versionNonce": 1470870267,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "M6URqLX3Wnl4AN6QRkmgB",
					"type": "arrow"
				}
			],
			"updated": 1695832690455,
			"link": null,
			"locked": false
		},
		{
			"id": "GQPhFLsb",
			"type": "text",
			"x": -183.58742765943066,
			"y": 1732.525701299392,
			"width": 10,
			"height": 24,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1325260565,
			"version": 2,
			"versionNonce": 262342843,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1695832568636,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": ""
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
		"scrollX": 968.3856198787391,
		"scrollY": -1295.853665003672,
		"zoom": {
			"value": 0.9518370549345699
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