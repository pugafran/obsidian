Es inseguro, cuando pasa por MTAs, en el MTA solo está cifrado cuando se está enviando.

Entre MTAs tampoco va cifrado

MUA => Cliente de email (Mail user agent)

MUA => MTA => MTA => (...) = MTA => MUA


Comandos enviados por el cliente:
Esto es informacion del protocolo no de las cabeceras, hay un from en las cabeceras pero no esto vaya, normalmente coinciden pero no tiene por qué, lo que va en la cabecera es el remitante que va a ver el destinatario pero el del sobre no lo va a ver el remitente, se utiliza mientras se está transportando, es para el sobre no es para el cuerpo.

HELO (Es el primero) => HELO manolo
MAIL (MAIL FROM: )
RCPT (puede ser una lista de destinatarios por comas, puedes mandar varios, puedes poner uno, y luego volver a usar el comando)
DATA (A partir de aqui para el mensaje, y termina cuando le llegue '\r\n.\r\n")
QUIT