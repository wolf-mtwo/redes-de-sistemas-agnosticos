# Datos en tiempo real

Entregar datos al instante en que ocurren, en vez de que el cliente los pida periódicamente.

**Ejemplos:**
1. JavaScript: `new WebSocket('wss://example.com')` — canal bidireccional en tiempo real.
2. C#: `HubConnectionBuilder().WithUrl(url).Build()` (SignalR) — eventos en tiempo real.
3. Comando: `wscat -c wss://example.com` — conectarse a un WebSocket desde la terminal.
