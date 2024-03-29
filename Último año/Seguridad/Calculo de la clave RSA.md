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


El usuario B desea recibir un mensaje del usuario A cifrado con RSA, y además el usuario B genera sus claves utilizando como parametros p = 17 q = 31 y elige como clave pública e = 7.
Se pide que calcules las claves del usuario B:

**Paso 1**: Calcular nn y ϕ(n)ϕ(n) (también conocido como la función totiente o función de Euler). Dado p=17p=17 y q=31:

n=p×q 
ϕ(n)=(p−1)×(q−1) = 16 * 16 = 480

**Paso 2**: Confirmar que el exponente público es coprimo con ϕ(n). Ya has elegido e=7. Vamos a verificar que e y ϕ(n) son coprimos.

480 = 2^5 * 3 * 5 != 7 (Son coprimos)

**Paso 3**: Usar el algoritmo extendido de Euclides para encontrar el inverso multiplicativo de ee módulo ϕ(n). Este inverso será d, el exponente privado.

(d * e) mod ϕ(n) = 1 => (d * 7) mod 480 = 1

Hay que calcular el maximo comun divisor de 480 y el 7:

480 / 7 => 480 = 68 * 7 + 4
7/4 => 7 = 1 * 4 + 3
4/3 => 4 = 1 * 3 + 1
3/1 => 3 = 1 * 3 + 0                   

4 = 480 - 61 * 7
3 = 7 - 4 * 1
1 =  4 - 3 * 1

3 = 7 -1 * (480 - 68 * 7) = 69 * 7 - 1 * 480
1 = (480 - 68 * 7) -1 * (69 * 7 - 1 * 480)

1 = 2 * 480 - 137 * 7 => INV(7,480) = -137
(esto es porque da negativo)
-137 + 480 = 343 
INV(7,480) = 343


check 
(343 * 7) mod 480 = 1 o


Vamos a calcular n, ϕ(n) y d:

Trabajo finalizado

Mostrar detalles de ejecución

Los resultados son:

- n=527
- ϕ(n)=480
- d=343

Por lo tanto, la clave pública de B es (e,n)=(7,527) y la clave privada es (d,n)=(343,527)

