# Discord Weather Bot

Este es un bot de Discord simple que utiliza un modelo de IA para clasificar el tiempo de una imagen adjunta. Puede responder a comandos básicos y realizar predicciones meteorológicas en imágenes.

## Configuración

1. **Requisitos Previos**
   - Asegúrate de tener Python 3.10 instalado.
   - Instala las dependencias necesarias ejecutando `pip install -r requirements.txt`.

2. **Configuración del Token de Discord**
   - Obtén tu token de Discord siguiendo las [instrucciones aquí](https://discordpy.readthedocs.io/en/latest/discord.html).
   - Reemplaza `"Acá va tu token"` en el código con tu token de Discord.

3. **Modelo de IA**
   - Asegúrate de tener el modelo de IA y el archivo de etiquetas (`keras_model.h5` y `labels.txt`) en el mismo directorio que tu script.

## Comandos

- `$hello`: Saludo básico del bot.
- `$heh [count_heh]`: Repite "he" varias veces (por defecto 5).
- `$check`: Verifica si se ha adjuntado una imagen en el mensaje y realiza una predicción meteorológica.

## Uso

1. Ejecuta el bot usando `python bot.py`.
2. Invita al bot a tu servidor de Discord.
3. Utiliza los comandos `$hello`, `$heh`, y `$check` según sea necesario.

## Contribuir

Si quieres contribuir a este proyecto, ¡eres bienvenido! Puedes abrir problemas, enviar solicitudes de extracción, o mejorar la documentación.
