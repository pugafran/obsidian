El usuario B desea recibir un mensaje del usuario A cifrado con RSA B genera las claves usando p = 17 y q = 1 y elige como exponente público e = 7

1 - Calcula los elementos de las claves de B:
	n = p * q = 17 * 11 = 187
	mandangon(n) = (p - 1) * (q - 1) = 16 * 10 = 160
	El exponente de la clave pública ya se ha elegido e = 7, comprobar que "e" es coprimo con mandangon(n), 160 = 2^5 * 5 => No hay factores comunes con 7 => Son coprimos
	Determinar el exponente d de la clave privada resolviendo: (d * e) mod mandangon(n) = 1
	y (d * 7) mod 160 = 1
	MCD(160,7) con Alg de euclides
	k = 0 160/7 160 = 22 * 7 + 6 | 6 = 160 - 22 * 7
	k = 1 7/6 7 = 1 * 6 + 1.            | 1 = 7 - 1 * 6
	k = 2 6/1 6 = 6 * 1 + 0
	1 = 7 -1 * (160 -22 * 7*)
	1 = 7 - 1 * 160 + 22 * 7
	1 = 23 * 7 - 1 * 160
	d = 23
	d es la combinacion linea del 7 y el 160 creo xd


