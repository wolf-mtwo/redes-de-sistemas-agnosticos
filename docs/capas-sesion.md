# Capa de sesión

Establecer, mantener y cerrar una sesión de comunicación entre dos sistemas.

**Ejemplos:**

1. C# — reutilizar cookies de sesión entre peticiones
```csharp
var client = new HttpClient(new HttpClientHandler { CookieContainer = new CookieContainer() });
```

2. Java — mantener el estado del usuario en una sesión web
```java
HttpSession sesion = request.getSession();
sesion.setAttribute("usuario", usuario);
```

3. Comando — mantener sesión entre peticiones
```bash
curl -c cookies.txt -b cookies.txt https://example.com
```
