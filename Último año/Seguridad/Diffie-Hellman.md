Permite el intercambio confidencial de claves entre dos personas que no ha ntenido un cotacto previo usando un canal de comunicación inseguro y de forma anónima.

Este algoritmo consituye el estándar PKCS#3 (Public Key Cryptography Standard)

Consiste en una serie de fases:
* La primera fase la hace una especie de administrador que selecciona un módulo y un generador, es algo hecho a priori. Una vez hecho dos usuarios van a utilizar ya el sistema base. Las operaciones que realizan los usuarios son las mismas, el primer elemento que necesita Alicia es una clave secreta, denominada KSa y es un numero aleatorio generado, a partir de ese numero Alicia lo que va a hacer es calcular su clave primaria y su clave publica con g^Ksa modulo p, luego lo envía a Benito y este va haciendo lo mismo, genera su clave secreta y pública y la envía, y luego hacen una clave secreta común que es KSc = KPb^KSa modulo p

Clave compartida secreta resumen = g^(KSb * KSa) mod p

Para hackiarlo hay que sacar KSa o KSB, y se llama el problema del logaritmo discreto.

p debe ser un numero primo grande de al menos 1024 bits

g debe ser una raíz primitva del módulo p

Al hacer el 2^Ks modulo p solo puede salir 1 en el último K = p-1

