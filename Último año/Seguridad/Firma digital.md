DSA 

Genereación de claves
	fase 1 un administrador 
	fase 2 cada usuario
Firmar un mensaje

En DSA la clave primaria se utiliza para meterlo en una reformulacion matematica, no está cifrado, no es por cifrado de hash.


p q g Y=clave publica de quien firmó el mensaje con la clave privada(X)

El propio firmante puede verificar su firma antes de enviar.

El usuario A tiene que firmar un hash con el algoritmo DSA y enviar la firma a B, los usuarios usan p = 53 y q = 13, el usuario A ha elegido x = 8 y k = 6.

Calcula los elementos que faltan pra que A puedan firmar el hash (usa un valor beta)