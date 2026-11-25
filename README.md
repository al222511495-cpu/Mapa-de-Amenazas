# Mapa de amenazas

Mapa mundial que muestra ataques informáticos en tiempo real como líneas animadas sobre un mapa oscuro. Tres tipos de ataque (DDoS, Malware, Intrusión), feed lateral con los últimos 8 y filtros por tipo

Demo en vivo: https://luisdg69.github.io/Mapa-de-Amenazas/

## Dos formas de usarlo...

### Demo estática (GitHub Pages, sin servidor)
Abre `docs/index.html` directamente en el navegador o usa el link de GitHub Pages.
No necesita Node ni llaves. Los ataques se generan en el navegador con datos simulados.

### Versión con servidor (datos reales de AbuseIPDB)
Requiere Node.js 18 o más nuevo.

1. Clona el repositorio y entra a la carpeta.
2. Instala las dependencias: `npm install`
3. Copia `.env.example` como `.env` y agrega tus llaves (opcional).
4. Arranca con `npm start` y abre http://localhost:3000

Para detenerlo: `Ctrl+C`.

## De dónde salen los datos

Con llave de AbuseIPDB el origen de cada ataque es real. El destino siempre es aleatorio porque AbuseIPDB no lo informa. Sin llaves, todo es simulado.

Llaves gratuitas:
- AbuseIPDB: https://www.abuseipdb.com/register
- IPinfo: https://ipinfo.io/signup
