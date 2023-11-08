Es inseguro, cuando pasa por MTAs, en el MTA solo está cifrado cuando se está enviando.

Entre MTAs tampoco va cifrado

MUA => Cliente de email (Mail user agent)

MUA => MTA => MTA => (...) = MTA => MUA


Comandos enviados por el cliente:
Esto es informacion del protocolo no de las cabeceras, hay un from en las cabeceras pero no este
HELO (Es el primero) => HELO manolo
MAIL (MAIL FROM: )
RCPT
DATA
QUIT