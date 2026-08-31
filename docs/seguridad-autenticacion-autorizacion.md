# Autenticación y autorización

Verificar quién es el usuario (autenticación) y qué puede hacer (autorización).

**Ejemplos:**
1. C#: validar un JWT con `JwtSecurityTokenHandler().ValidateToken(...)`.
2. Java (Spring Security): `@PreAuthorize("hasRole('ADMIN')")` sobre un endpoint.
3. Comando: `curl -H "Authorization: Bearer <token>" https://api.example.com`.
