Como saber si un sistema libre o ligado, subespacio generado por ese sistema de vectores
Viendo el rango de la matriz

escalonada reducida vectores por filas 


Coordenadas de un vector respecto de una base => va por columnas

( Matriz ) * (base vertical)

la ultima columna de esa matriz escalonad son las coordenadas en esa base(E(:,end))
ref(E)

matriz de cambio de base de base 1 a base 2 es la que tiene por columnas las coordenadas de la base 2 expresada en la base 1.

De canónica a B1, porque las coordenadas las conozco en esa base a funcion de la canónica, las pongo por columnas.

Osea lo hago por filas y luego traspuesta para ponerlo por columnas

B=(1 2 3; 4 5 6; 7 8 9)'


B1 y B2 ninguna es la canónica, hay que hacer la matriz de cambio de base de b1 a b2, al reves la inversa.

Bc b1 y Bc b2

La matriz R que tenga por columnas la base b1, la matriz S es b2 por columnas


RX = SY 

X = INV(R) * S * Y

APLICACION LINEAL (RELACIONA U CON SU IMAGEN EN V)
U -> V

PARA CADA BASE DE U Y V HAY UNA MATRIZ ASOCIADA A LA APLICACIÓN LINEAL, SI MODIFICAMOS U o V, u ambas, cambia la matriz asociada.

P, Q | A, N

x son las coordenadas de cualquier vector de U
x' son las coordenadas de x en V (O son dos bases que hay y ya idk)

Si B1' es la canonica de U, P que es? Pues de B1' a no canónica

Hay que ir de canonica a no canonica

Y = A * X => A = 
Y' = M * X'

Y' =Q * A * P-1*