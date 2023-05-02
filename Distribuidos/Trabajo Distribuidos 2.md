
Cada filósofo crea un socket servidor y se conecta al socket del siguiente filósofo

El filosofo 0 es el socket que inserta el token.

Comprobar el valor retornado por funciones de libreria y llamadas al sistema, por ejemplo pthread mutex lock 


token = token >> pos desplaza a la derecha los bits la cantidad de pos
00000010 >> 1
00000001

ocupado&= token (hace un AND de ocupado y token)

00000001 (ocupado)
00000001 (token)
<<<<<<<< (AND)
00000001

después de cada pthread_Cond_signal podrñias poner el unlock 

unsigned char token[2];
inicializar a 0 token[0] = token[1] = 0;

token 1 es palillos (Hay que comentarlo todo con los apartados //AOARTADO)