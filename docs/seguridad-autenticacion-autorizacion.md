# Autenticación y autorización

Verificar quién es el usuario (autenticación) y qué puede hacer (autorización).

**Ejemplos:**

1. C# — validar un JWT
```csharp
new JwtSecurityTokenHandler().ValidateToken(token, parametros, out var validado);
```

2. Java (Spring Security) — restringir un endpoint por rol
```java
@PreAuthorize("hasRole('ADMIN')")
public void endpointAdmin() { }
```

3. Comando
```bash
curl -H "Authorization: Bearer <token>" https://api.example.com
```
