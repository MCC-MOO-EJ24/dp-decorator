# Decorator - Caso práctico

### Intención

Adjunta dinámicamente responsabilidades a un objeto. Los decoradores ofrecen una alternativa flexible a la subclasificación para extender funcionalidad.

### Clasificación

Patrón Estructural

### Vista Estructural

![image](https://user-images.githubusercontent.com/84739791/220203308-a4db3637-ee88-412d-a991-bb30ce05a289.png)

### Vista Dinámica

![image](https://user-images.githubusercontent.com/84739791/220203356-4d665854-4260-4663-ad2b-39c6ebb9e8f2.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Decorator crearemos una aplicación que nos permite procesar un mensaje en capas, donde cada capa se encargará de procesar un mensaje a diferente nivel. primero convertiremos un Objeto en XML, seguido, lo envolveremos en un mensaje SOAP para después encriptar el mensaje, finalmente obtendremos un mensaje SOAP totalmente encriptado, el cual podrá ser enviado de forma segura a un destinatario. Cada capa de procesamiento será implementada con un decorador, y cada decorador podrá cambiar de posición para obtener un resultado diferente, de la misma manera, podrá ser agregados nuevos decoradores en medio de cualquier paso..

Solución, sin el patrón Decorador:

![image](https://user-images.githubusercontent.com/84739791/220202752-991d28ac-8d58-4749-a17b-fe36db77fe02.png)

Solución, con el patrón Decorador:

![image](https://user-images.githubusercontent.com/84739791/220203478-848cf48a-186b-44c5-9880-670a209d2477.png)

![image](https://user-images.githubusercontent.com/84739791/220203552-62d8ea82-048b-448f-85ad-e8561dc06220.png)


* Programa principal:
```
Program.cs
```

# Compilación y Ejecución
```
dotnet run
```
