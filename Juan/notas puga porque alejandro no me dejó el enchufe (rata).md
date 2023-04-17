## Regresión logística
- Se buscan los parámetros que maximicen la probabilidad que se busca (máxima verosimilitud)
- Se utiliza el descenso del gradiente como fórmula de actualización: ahora la regresión logística es no lineal.
- En la regresión lineal, el resultado es un número contínuo, mientras que en regresión logística se devuelve una probabilidad entre 0 y 1. (repetido)
- Me estoy cagando encima

# Algoritmos de aprendizaje generativo
- Los algoritmos que tratan de discriminar la clase de un dato en base a unos parámetros se llaman *algoritmos de aprendizaje discriminativo*.
- Los *algoritmos de aprendizaje generativo* tratan de modelar `p(x|y)` en lugar de `p(y|x)`.
- Se utiliza la fórmula de Bayes.

### Análisis discriminante gausiano (GDA)
1. Obtener ejemplos de las distribuciones de las clases.
2. Realizar gausianas de tantas variables como las descripciones de los ejemplos de entrada.
3. Se establece una aproximación del número de casos en cada clase mediante Bernoulli.
4. Se aplican las fórmulas sin optimizaciones ni hiperparámetros.

## GDA y regresión logística
- La probabilidad de y condicionado a x `p(x|y)` sigue una función logística.
- El modelo gausiano es teóricamente perfecto con muchos datos, pero prácticamente no (principalmente con pocos datos)
