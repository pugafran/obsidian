DSA 

Genereación de claves
	fase 1 un administrador 
	fase 2 cada usuario
Firmar un mensaje

En DSA la clave primaria se utiliza para meterlo en una reformulacion matematica, no está cifrado, no es por cifrado de hash.


p q g Y=clave publica de quien firmó el mensaje con la clave privada(X)

El propio firmante puede verificar su firma antes de enviar.

El usuario A tiene que firmar un hash con el algoritmo DSA y enviar la firma a B, los usuarios usan p = 53 y q = 13, el usuario A ha elegido x = 8 y k = 6.

Calcula los elementos que faltan pra que A puedan firmar el hash (usa un valor beta de 31 para obtener un generador g)

1. Comprobar p y q:
	p debe de ser primo  => p=53 es primo => OK
	q debe de ser primo y divisor de p - 1 => 53 - 1 = 52 = 2^2 * 13 => q = 13 es primo y divisor de 52 => OK

2. Cáculo del generador (beta = 31)
	g = beta^((p -1)/q) modulo p = 49 != 1 => Es válido
	Comprobar que se verifica: g^q modulo p = 1 => 49^13 mod 53 = 1 => OK

3. Cálculo de la clave pública de A
	Y = g^x mod p => 49^8 mod 53 = 28

4. Calcula la firma del hash H=6
	r = (g^k mod p) mod q => (49^6 mod 53) mod 13 = 2
	s = (k ^-1 [H + X * r]) mod q
	Calculo del inverso modular de K = 6 en modulo k=13
	MCD(13,6) con Alg de Euclides
	K = 0.   13/6.   13 = 2 * 6 + 1 | 1 = 13 - 2 * 6 | 1 = 1 * (13) - 2 * (6)
	K = 1.    6/1.      6 = 6 * 1 + 0 |
	k^-1 = 13 y k = 6
	INV (6 y 13)=> -2