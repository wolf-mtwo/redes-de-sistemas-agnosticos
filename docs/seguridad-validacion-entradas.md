# Validación de entradas

Nunca confiar en datos que vienen de fuera del sistema, para evitar inyección o corrupción de datos.

**Ejemplos:**
1. C#: `if (!int.TryParse(entrada, out var numero)) throw new ArgumentException();`.
2. Java (Bean Validation): `@NotNull @Size(max = 100) private String nombre;`.
3. JavaScript: usar una librería como `zod` o `joi` para validar el cuerpo de una petición HTTP.
