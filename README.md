# registro-peso

Página estática (GitHub Pages) para que clientes registren su peso diario (kg). 
Los datos se guardan en Google Sheets mediante una Web App de Google Apps Script.

- Frontend: `index.html` (sin dependencias)
- Backend: Google Apps Script (doGet/doPost)
- Despliegue: GitHub Pages

## Configuración rápida
1. En `index.html`, sustituye `YOUR_WEB_APP_URL_HERE` por tu URL `/exec` de Apps Script.
2. Activa GitHub Pages: Settings ▸ Pages ▸ Deploy from a branch (main / root).
3. Abre: `https://TU-USUARIO.github.io/registro-peso/?userId=TU_ID&token=TU_TOKEN`
