# Datos en tiempo real

Entregar datos al instante en que ocurren, en vez de que el cliente los pida periódicamente.

**Ejemplos:**

1. JavaScript — canal bidireccional en tiempo real
```javascript
const socket = new WebSocket('wss://example.com');
```

2. C# — eventos en tiempo real (SignalR)
```csharp
var connection = new HubConnectionBuilder().WithUrl(url).Build();
```

3. Comando — conectarse a un WebSocket desde la terminal
```bash
wscat -c wss://example.com
```
