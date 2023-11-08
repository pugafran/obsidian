Es inseguro, cuando pasa por MTAs, en el MTA solo está cifrado cuando se está enviando.

Entre MTAs tampoco va cifrado

MUA => Cliente de email (Mail user agent)

MUA => MTA => MTA => (...) = MTA => MUA


Comandos SMPT:

HELO (Es el primero)
MAIL
RCPT
DATA
QUIT