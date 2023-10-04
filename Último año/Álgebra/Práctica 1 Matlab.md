Mayusculas distintas de minusculas
Variables predefinidas: pi, i, eps(número más pequeño que sumado a 1 nos da algo mayor que 1), 1/0(Inf) o indeterminacion(NaN).

1+eps/2 - 1 = 0

Si queremos mas decimales:
format long

format rat (número racional)

format short

Información de las variables:
whos

double => 64 bits => 8 bytes

declarar variables simbólicas:
syms x y
f(x,y)= 3 * x^2 + 2 * y^2 - 7

[a:h:b]

a => primera coordenada
h => diferencia entre dos coordenadas consecutivas
b => cota superior de la ultima coordenada

[2:3:13] 
[2:3:11]

(2 5 8 11)

linspace(Primera coordenada, segunda coordenada, número de coordenadas)


linspace(3.1, 4.3, 5) => (3.1 3.4 3.7 4 4.3)

v(end) me da la ultima

v(end-1) la penultima

u = [2:3:13]' = u traspuesta

sum(u) suma las coordenadas de un vector


u[2:2:end]

ones(2,3) matriz de 1s 2x3

ones(2,3)'  traspuesto

eye(5)

diagonal 1



M=randi([-3,5],5,6) matriz aleatoria de 5x6 entre -3 y 5

M(3,4) = 10

M(4,:) = 100 (cambia toda la fila 4 a 100)
M(:,3) = 700 (cambia toda la fila a 700)

[A:1:B] == [A:B]

B = M([1:3],[4:end])

det(B) = determinante de B

inversa de B = inv(B)

rank(B) rango de la matriz

B^2 (Matriz al cuadrado xd) B * B

Para elevar los elementos de la ma