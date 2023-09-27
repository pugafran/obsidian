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
location: login ^g0t984IR

get /login ^24KGZrrp

200 OK
 ^gfncqweZ

POST /datoslogin
(envías los datos) ^jORWENHj

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
			"width": 357.7465700172807,
			"height": 14.566539289542334,
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
			"version": 135,
			"versionNonce": 946510773,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "6M1l7IRH"
				}
			],
			"updated": 1695832982839,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					357.7465700172807,
					14.566539289542334
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"focus": 0.0586109857031189,
				"gap": 2.9479142258097397
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"gap": 6.107631523864745,
				"focus": -0.07475561703002366
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
			"x": -925.6063635749709,
			"y": 1811.2421247268246,
			"width": 307,
			"height": 81,
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
			"version": 165,
			"versionNonce": 1306912283,
			"isDeleted": false,
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
				}
			],
			"updated": 1695832982839,
			"link": null,
			"locked": false
		},
		{
			"id": "AAhomlSP",
			"type": "text",
			"x": -782.8472438059537,
			"y": 1839.6043000887694,
			"width": 21.399978637695312,
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
			"seed": 1725484309,
			"version": 50,
			"versionNonce": 1234652539,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832982838,
			"link": null,
			"locked": false,
			"text": "Yo",
			"rawText": "Yo",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "J1LHvgNa7ovsfWbT3lnt3",
			"originalText": "Yo"
		},
		{
			"id": "FIDBMLzjrfzve5OMQrY0z",
			"type": "ellipse",
			"x": -254.722700600866,
			"y": 1819.2007068962967,
			"width": 312,
			"height": 116,
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
			"version": 411,
			"versionNonce": 709100571,
			"isDeleted": false,
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
				}
			],
			"updated": 1695832972653,
			"link": null,
			"locked": false
		},
		{
			"id": "FsCpORzq",
			"type": "text",
			"x": -129.96132825356509,
			"y": 1865.1885135874768,
			"width": 62.85993957519531,
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
			"seed": 1332543477,
			"version": 74,
			"versionNonce": 1280092507,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832959585,
			"link": null,
			"locked": false,
			"text": "Github",
			"rawText": "Github",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FIDBMLzjrfzve5OMQrY0z",
			"originalText": "Github"
		},
		{
			"id": "xoCE_KYmd0Vc_Z57gigyJ",
			"type": "arrow",
			"x": -211.03856310851162,
			"y": 1919.9317712118807,
			"width": 469.3052461139737,
			"height": 200,
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
			"seed": 1814001045,
			"version": 588,
			"versionNonce": 1049474005,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "g0t984IR"
				}
			],
			"updated": 1695832986772,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-236.98816505420018,
					75.80205872799797
				],
				[
					-469.3052461139737,
					-26.75490709314954
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"focus": -0.08895811440645074,
				"gap": 2.315150745017789
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"focus": 0.01172898438291013,
				"gap": 8.80400759566814
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "g0t984IR",
			"type": "text",
			"x": -605.6365914439617,
			"y": 1923.7338299398784,
			"width": 356.0797119140625,
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
			"seed": 1920418619,
			"version": 185,
			"versionNonce": 1896795285,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832985738,
			"link": null,
			"locked": false,
			"text": "301\n(Vuelve a pedirmelo que no tengo ni \nputisima idea de quién eres tonto, \nvete aquí al formulario del login)\nlocation: login",
			"rawText": "301\n(Vuelve a pedirmelo que no tengo ni putisima idea de quién eres tonto, vete aquí al formulario del login)\nlocation: login",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xoCE_KYmd0Vc_Z57gigyJ",
			"originalText": "301\n(Vuelve a pedirmelo que no tengo ni putisima idea de quién eres tonto, vete aquí al formulario del login)\nlocation: login"
		},
		{
			"id": "uaFI_CRDUKjgTGJhnBPfo",
			"type": "arrow",
			"x": -868.0077930231862,
			"y": 1893.8958284185333,
			"width": 705.4280323027556,
			"height": 322.8456626114689,
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
			"seed": 694485755,
			"version": 439,
			"versionNonce": 1939234107,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "24KGZrrp"
				}
			],
			"updated": 1695832986885,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					416.5830305191631,
					322.8456626114689
				],
				[
					705.4280323027556,
					37.4045121061456
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"focus": 0.9268734226321574,
				"gap": 10.311317164372305
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"focus": 0.05467088489911619,
				"gap": 1.1654407241412983
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "24KGZrrp",
			"type": "text",
			"x": -497.59472252599573,
			"y": 2204.741491030002,
			"width": 92.33992004394531,
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
			"seed": 503151835,
			"version": 17,
			"versionNonce": 416295067,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832986815,
			"link": null,
			"locked": false,
			"text": "get /login",
			"rawText": "get /login",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uaFI_CRDUKjgTGJhnBPfo",
			"originalText": "get /login"
		},
		{
			"id": "LQVF_W4YA2eIvZSf590yw",
			"type": "arrow",
			"x": -99.2174622838827,
			"y": 1938.2404042851538,
			"width": 842.1114428739647,
			"height": 498.57286495670223,
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
			"seed": 615150581,
			"version": 456,
			"versionNonce": 1187878133,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "gfncqweZ"
				}
			],
			"updated": 1695832982838,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-374.0262177405001,
					423.03023184463905
				],
				[
					-842.1114428739647,
					-75.54263311206319
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"focus": -0.32563932595251555,
				"gap": 3.0399869943400617
			},
			"endBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 14.12154956014006,
				"focus": 1.1285020692749073
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "gfncqweZ",
			"type": "text",
			"x": -499.0297773994147,
			"y": 2337.268756003371,
			"width": 78.53996276855469,
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
			"seed": 1260970005,
			"version": 54,
			"versionNonce": 1291132603,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832970718,
			"link": null,
			"locked": false,
			"text": "200 OK\n",
			"rawText": "200 OK\n",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "LQVF_W4YA2eIvZSf590yw",
			"originalText": "200 OK\n"
		},
		{
			"id": "pzbdo3BQgxo3ngcsydz_N",
			"type": "arrow",
			"x": -957.4524175278,
			"y": 1861.0996502262215,
			"width": 908.4893166990478,
			"height": 688.021308602235,
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
			"seed": 1827790651,
			"version": 741,
			"versionNonce": 104472795,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "jORWENHj"
				}
			],
			"updated": 1695832982838,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					503.5981425478642,
					688.021308602235
				],
				[
					908.4893166990478,
					73.90130959023054
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "J1LHvgNa7ovsfWbT3lnt3",
				"gap": 11.375617578428013,
				"focus": 1.2223346193126232
			},
			"endBinding": {
				"elementId": "FIDBMLzjrfzve5OMQrY0z",
				"focus": -0.5470574383915014,
				"gap": 2.8081988482673808
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "jORWENHj",
			"type": "text",
			"x": -544.5741999066936,
			"y": 2525.1209588284564,
			"width": 181.43984985351562,
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
			"seed": 309104821,
			"version": 62,
			"versionNonce": 1590564347,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1695832973310,
			"link": null,
			"locked": false,
			"text": "POST /datoslogin\n(envías los datos)",
			"rawText": "POST /datoslogin\n(envías los datos)",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pzbdo3BQgxo3ngcsydz_N",
			"originalText": "POST /datoslogin\n(envías los datos)"
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
		},
		{
			"id": "gWp9jhB8",
			"type": "text",
			"x": -199.3037289296445,
			"y": 1864.9696397601167,
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
			"seed": 1423687573,
			"version": 4,
			"versionNonce": 1616436603,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1695832694139,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FIDBMLzjrfzve5OMQrY0z",
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
		"scrollX": 1346.6016161290072,
		"scrollY": -1550.0988624830197,
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