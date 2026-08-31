# Convenciones de este repositorio

Guía de referencia para escribir temas y sub-temas en este silabo, de forma consistente con lo ya existente.

## Estructura general

- [README.md](README.md) contiene el temario completo: una nota sobre los lenguajes usados en los ejemplos, y una lista de temas (`### [Nombre del tema](docs/tema.md)`) con sus sub-temas como bullets enlazados (`- [Nombre del sub-tema](docs/tema-subtema.md)`).
- Cada tema y cada sub-tema vive en su propio archivo `.md` dentro de `docs/`. No se mezcla contenido de varios sub-temas en un mismo archivo.
- Nombres de archivo: `kebab-case`, prefijados por el tema al que pertenecen (ej. `binario-endianness.md`, `capas-transporte.md`, `criptografia-hashing.md`).

## Archivo de un tema (índice)

Formato de `docs/<tema>.md`:

```markdown
# Nombre del tema

Uno o dos párrafos de contexto histórico/introductorio: de dónde viene el concepto,
qué problema resolvió, por qué existe. Sirve de entrada a los sub-temas, no repite
su contenido.

## Sub-temas
- [Sub-tema 1](tema-subtema-1.md)
- [Sub-tema 2](tema-subtema-2.md)
```

Ejemplo real: [docs/capas-modelo-comunicacion.md](docs/capas-modelo-comunicacion.md), [docs/binario-hexadecimal.md](docs/binario-hexadecimal.md).

## Archivo de un sub-tema

Formato de `docs/<tema>-<subtema>.md`:

```markdown
# Nombre del sub-tema

Una sola frase que defina el sub-tema (qué es, no cómo se usa).

**Ejemplos:**

1. Etiqueta corta (lenguaje/herramienta/comando) — qué hace este ejemplo puntual
​```lenguaje
código o comando
​```

2. ...

3. ...
```

Reglas:
- Siempre **3 ejemplos** por sub-tema, cada uno usando una herramienta, un comando de terminal, o un lenguaje de programación.
- Los ejemplos de código van en bloque con fence y el lenguaje indicado (` ```csharp `, ` ```java `, ` ```javascript `, ` ```bash `), nunca como backticks inline dentro de una lista.
- Los lenguajes de programación usados son **C#, JavaScript y Java**, según qué encaje mejor con el ejemplo o la herramienta — no hay un lenguaje fijo por tema.
- Un ejemplo puede ser puramente conceptual/de herramienta (sin código), cuando el sub-tema no tiene una pieza de código representativa (ej. usar Wireshark, un multímetro).
- La descripción del sub-tema es breve (1 línea): el detalle vive en los ejemplos, no en párrafos explicativos largos.

Ejemplo real: [docs/criptografia-hashing.md](docs/criptografia-hashing.md), [docs/transporte-mqtt.md](docs/transporte-mqtt.md).

## Al agregar un tema o sub-temas nuevos

1. Crear el/los archivo(s) en `docs/` siguiendo los formatos de arriba.
2. Si es un tema nuevo, crear su archivo índice y enlazarlo desde `README.md` como una nueva sección `###`.
3. Si son sub-temas de un tema existente, agregarlos a la lista "## Sub-temas" del índice del tema y como bullets bajo esa sección en `README.md`.
