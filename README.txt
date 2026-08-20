# Diagnóstico de Gestión Documental

1. Abre `index.html` para probar la encuesta.
2. Para guardar respuestas, crea una Hoja de cálculo de Google y abre Extensiones > Apps Script.
3. Pega el contenido de `google_apps_script.gs`.
4. Implementa como aplicación web con acceso para cualquier persona que tenga el enlace.
5. Copia la URL `/exec` que te dé Google.
6. En `index.html`, reemplaza `PEGA_AQUI_TU_URL_DE_GOOGLE_APPS_SCRIPT` por esa URL.
7. Sube `index.html` a un hosting estático.

La página reproduce los 53 criterios de la lista de chequeo y calcula el porcentaje sobre los criterios aplicables, excluyendo N/A.
