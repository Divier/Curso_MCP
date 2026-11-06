## Credenciales (NO se suben a Git)

Cada sección (seccion_4 a seccion_7) necesita su propio `credentials.json`:

1. Ir a Google Cloud Console → APIs y servicios → Credenciales
2. Abrir el cliente OAuth y descargar el JSON
3. Guardarlo como `credentials.json` en la carpeta de la sección
   (puedes copiar `credentials.example.json` como guía)

Este archivo es la llave de acceso a Gmail. Está en `.gitignore`.
Si se filtra: rotar el Client Secret en Google Cloud Console.