# JSON

Formato de texto basado en pares clave-valor, el más usado hoy para APIs web.

**Ejemplos:**

1. JavaScript
```javascript
JSON.stringify({ nombre: "Ana" });
```

2. C#
```csharp
string json = System.Text.Json.JsonSerializer.Serialize(objeto);
```

3. Comando — ver y formatear una respuesta JSON
```bash
curl https://api.example.com | jq .
```
