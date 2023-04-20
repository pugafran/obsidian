
Versión 1 dos fallos (exec) //Solo ejecuta un comando con éxito, como hace directamente un exec, destruye el programa en curso y ejecuta el otro comando, si tecleas algo con un exec que falle sigue, por tanto lo del "éxito", y además falla con comando vacío.

Versión 2 dos fallos (fork + exec)

Versión  3 no tiene fallos (fixea los errores del 2)