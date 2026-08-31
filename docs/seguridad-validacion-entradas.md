# Validación de entradas

Nunca confiar en datos que vienen de fuera del sistema, para evitar inyección o corrupción de datos.

**Ejemplos:**

1. C#
```csharp
if (!int.TryParse(entrada, out var numero)) throw new ArgumentException();
```

2. Java (Bean Validation)
```java
@NotNull
@Size(max = 100)
private String nombre;
```

3. JavaScript — validar el cuerpo de una petición HTTP
```javascript
const esquema = z.object({ nombre: z.string().max(100) });
esquema.parse(req.body);
```
