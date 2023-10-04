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