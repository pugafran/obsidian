
SHA-512
Modificamos un hash inicial y lo convertimos en final y por en medio metemos el resumen, la información.

se añade un 1 al final del mensaje, Al final hay 128 bits dedicados a rellenar la longitud de la información real.

se hace en rotaciones y se combinan con otras
se suma en mod 2^64 de la combinacion de Ch y h

HMAC CMC