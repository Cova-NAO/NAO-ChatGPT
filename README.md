# NAO-ChatGPT
Steps to conect NAO to ChatGPT
Antes de empezar, asegúrate de cumplir con lo siguiente:
Conexión de NAO a la misma red que tu computadora.
Choregraphe 2.8.7.4 instalado y funcionando.
Python 3.12.7 instalado en tu PC.
Clave API de OpenAI (para conectar ChatGPT).
Dirección IP de NAO (apretando el botón en su pecho o en Choregraphe o en monitor).
Bloques de Choregraphe Necesarios
ALFaceDetection → Detecta cuando una persona se sienta frente a NAO. (se puede usar el incluido en Choregraphe)
ALSpeechRecognition → Activa el reconocimiento de voz. (se puede usar el incluido en Choregraphe)
ALMemory → Guarda el texto reconocido. (se puede incluir en otro script)
Python Script → Envia el texto a ChatGPT y recibe la respuesta.
ALTextToSpeech → Convierte la respuesta de ChatGPT en voz.
Loop y Wait → Para mantener la conversación fluida. (opcional)
