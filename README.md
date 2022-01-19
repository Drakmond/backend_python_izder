# Examen Backend Python Izder

_Respuestas al cuestionario de aplicación._

## Preguntas 📋

### 1. ¿Qué es un microservicio?

```
Es un módulo o una unidad de software de un sistema que se construyó con componentes independientes. El microservicio se ejecutará como un solo servicio y con la finalidad de cumplir una sola función, tendrá comunicación con el sistema al que pertenece comúnmente a través de apis.
```

### 2. Menciona cuales son las ventajas de una arquitectura de microservicios.

```
Nos ayuda a cumplir mejor el ciclo CI/CD. Fácil implementación, escalado autónomo y mejor organización de equipos de desarrollo. Además de que es más fácil corregir los errores en esta arquitectura sin afectar otros componentes.
```

### 3. ¿Qué herramientas DevOps se usan en el desarrollo de microservicios?

```
Git, Github, Docker, Kubernetes, infraestructura en la nube o VPS para servidores de desarrollo, staging y producción, planificador de tareas como Jira y software de automatización para pruebas como Selenium.
```

### 4. ¿Qué es el patrón Circuit Breaker en microservicios?

```
Es el patrón de diseño que usa comúnmente en la arquitectura de microservicios para evitar que los recursos queden bloqueados ante un fallo del sistema o del módulo. Con este patrón evitamos que el cliente o un sistema continue haciendo peticiones en lugar de seguir intentando.
Tiene 3 estados:  cerrado, semi abierto y abierto.
```

### 5. Describe los pasos y software que usas para realizar las pruebas unitarias a un microservicio.

```
He realizado pruebas unitarias en Python y Django usando la librería PyTest y Swagger.
Normalmente creo la función de prueba al finalizar el desarrollo de algún servicio, para eso se define la entrada “dummy” que tendrá el servicio, se genera una base de datos de pruebas y se ejecuta la función que probará al servicio desarrollado. Las funciones de prueba pueden ir de la mano con los casos de uso y entonces habrá tantas funciones de prueba en Pytest como casos de uso tenga el proyecto. Se puede usar swagger para exponer las APIs y la documentación al cliente.
```

### 6. En un servicio REST ¿Qué tipos de métodos se pueden usar?

```
Los métodos usados son los siguientes:
HEAD
GET: Obtener información.
POST: Creación de nuevo registros.
PUT: Actualizar por completo la información.
PATCH: Actualizar parcialmente la información.
DELETE: Borrar información.
OPTIONS: Obtener opciones de comunicación.
```

### 7. Menciona ventahas de usar el lenguaje de programación Python para web services.

```
Es un lenguaje OpenSource, tiene un estándar de codificación ordenado y revisado. La comunidad del lenguaje es activa pues actualmente aún se continúa trabajando en exportar librerías de la versión 2 a la versión 3. Y es lenguaje interpretado por lo que su ejecución llega a ser más rápida.
```

### 8. ¿Qué es una función lambda?

```
En Python una función lambda es el equivalente a una función anónima. Se definen con la palabra lambda, la lista de parámetros a recibir y la expresión a evaluar.
En AWS, es un servicio que permite ejecutar código sin la necesidad de desplegar y configurar un servidor.
```

### 9. ¿Qué funcionalidad tienen una API Gateway?

```
Es el punto de entrada y de comunicación entre los clientes (web, mobile, etc) y el backend. Aquí solemos encontrar funciones de invocación autenticación y reglas de seguridad.
```

### 10. Menciona que métodos de autorización se pueden aplicar para servicios REST.

```
Autenticación básica: Encabezado HTTP (Authorization)
Autenticación por Token.
Autenticación por clave: Se genera y envía u  key y el secret del sistema.
Oauth 2.0
```




---
Escrito por Gustavo Hernández Martínez. ❤️ 
