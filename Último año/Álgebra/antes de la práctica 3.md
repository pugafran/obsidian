% Construir matriz B1
impares = 1:2:22; % Números impares entre 1 y 22
B1 = diag(impares);

% Construir matriz B2
B2 = ones(11, 7);

% Construir matriz B3
diagonal = 4 * ones(10, 1);
diagonalSuperior = 2.045 * ones(9, 1);
diagonalInferior = -3.25 * ones(9, 1);
B3 = diag(diagonal) + diag(diagonalSuperior, 1) + diag(diagonalInferior, -1);

% Calcular las dimensiones para la matriz nula de la esquina inferior izquierda de B
n = size(B2, 1); % número de filas de B2
m = size(B1, 2); % número de columnas de B1

% Construir matriz nula
matrizNula = zeros(n, m);

% Construir matriz B por bloques
B = [B1, matrizNula; B2, B3];

% Construir la matriz S a partir de las filas y columnas específicas de A
% Asumiendo que la matriz A ya ha sido definida como se proporciona
S = A([10, 11], [3, 10]);

