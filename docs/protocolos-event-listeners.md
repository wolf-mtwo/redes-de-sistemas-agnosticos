# Event listeners

Código que reacciona automáticamente cuando ocurre un evento, sin tener que estar preguntando ("polling").

**Ejemplos:**

1. JavaScript
```javascript
socket.on('message', (datos) => console.log(datos));
```

2. Java
```java
emitter.addListener("mensaje", datos -> System.out.println(datos));
```

3. C#
```csharp
cliente.MessageReceived += (s, e) => Console.WriteLine(e.Mensaje);
```
