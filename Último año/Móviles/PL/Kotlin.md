
val mamahuevo = 20 (inmutable)
var mamahuevo = 20 (inmutable)
var mamahuevo: Int = 64 (especificar el tipo)

![[Pasted image 20240122182103.png]]

en el if, el else obligatorio 

para cosas que son null o no sabes a priori que va a ser porque da null o no tienes ni idea, haces un lateinit, que es una inicialización retrasada.

Extensiones, puedes añadirles a clases del propio android funciones, por ejemplo en TextView que será para ver el texto o algo en un input de android, añadirle la función .mayusculas y le metes la lógica, y luego funciona.

data class, son clases cuyo proposito es contener datos.

Propiedades delegadas:
* Lazy (Como el lateInit, pero mejor, se inicializa de manera perezosa, en el late tienes que inicializarlo tu con el tiempo, pero tú, con lazy lo hace el lenguaje)
* Observables
* Map
* Delegar a otra propiedad (...)

