
Versión 1 dos fallos (exec) //Solo ejecuta un comando con éxito, como hace directamente un exec, destruye el programa en curso y ejecuta el otro comando, si tecleas algo con un exec que falle sigue, por tanto lo del "éxito", y además falla con comando vacío.

Versión 2 dos corrige fallos (fork + exec) por el n_args lo de comando vacío

Versión  3 no tiene fallos (fixea los errores del 2)

2-3 pruebas a la vez permite deducir 1 y el 4 2 y el quinto terceor