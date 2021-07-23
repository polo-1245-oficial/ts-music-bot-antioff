# ts-music-bot-antioff

Este script sirve para los bots de música de TeamSpeak (en concreto SinusBot) ya que en Windows server 2019 el bot al cerrar la sesión RDP se apaga por lo cual este pequeño script
lo que hace es crea una sesión virtual RDP para que el bot crea que estás conectado pero en verdad no.
(para usarlo cada vez que te quieras salir de la vps solo ejecuta ese script, como al el limite de conexiones en RDP es de 1 te expulsará pero podrás volver a entrar
cuando quieras y cuando sales ejecutas el script y ya)
