# Scraping de Comentarios de YouTube

Este script de Python utiliza la API de YouTube para extraer comentarios de un video específico. Los comentarios se guardan en un archivo CSV para su posterior análisis o procesamiento.

## Requisitos

Antes de ejecutar este script, asegúrate de tener instaladas las siguientes dependencias:

- `google-api-python-client`: para interactuar con la API de YouTube.
- `configparser`: para leer la configuración desde un archivo INI.
- `pandas`: para trabajar con los datos y guardarlos en formato CSV.

Puedes instalar estas dependencias usando `pip`:

## Uso

1. Configuración:
   - Crea un archivo `config.ini` en la misma carpeta que este script y agrega tu clave de API de Google en el siguiente formato:
     [google]
     api_key = TU_CLAVE_DE_API_AQUI

2. Ejecución:
  - Abre una terminal o línea de comandos y navega hasta la ubicación de este script.
  - Ejecuta el script de Python

Asegúrate de reemplazar `TU_CLAVE_DE_API_AQUI` con tu propia clave de API de Google.

3. Resultados:
- El script solicitará comentarios del video especificado y los guardará en un archivo CSV en la misma carpeta con el nombre `youtube_comments.csv`.

## Personalización

Puedes personalizar este script cambiando los parámetros de consulta en la sección "Generando consulta por comentarios" del código. Por ejemplo, puedes cambiar el ID del video o ajustar el número máximo de comentarios a recuperar.

## Aviso Legal

Este script se proporciona únicamente con fines educativos y de aprendizaje. El uso de este script para extraer comentarios de YouTube puede estar sujeto a las políticas y términos de servicio de YouTube y Google. Asegúrate de cumplir con todas las políticas y regulaciones relevantes al utilizar este script.

¡Diviértete explorando los comentarios de YouTube con este script!
