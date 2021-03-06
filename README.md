# Examen Backend Python Izder

_Respuestas al cuestionario de aplicaci贸n._

## Preguntas 馃搵

### 1. 驴Qu茅 es un microservicio?

```
Es un m贸dulo o una unidad de software de un sistema que se construy贸 con componentes independientes. El microservicio se ejecutar谩 como un solo servicio y con la finalidad de cumplir una sola funci贸n, tendr谩 comunicaci贸n con el sistema al que pertenece com煤nmente a trav茅s de apis.
```

### 2. Menciona cuales son las ventajas de una arquitectura de microservicios.

```
Nos ayuda a cumplir mejor el ciclo CI/CD. F谩cil implementaci贸n, escalado aut贸nomo y mejor organizaci贸n de equipos de desarrollo. Adem谩s de que es m谩s f谩cil corregir los errores en esta arquitectura sin afectar otros componentes.
```

### 3. 驴Qu茅 herramientas DevOps se usan en el desarrollo de microservicios?

```
Git, Github, Docker, Kubernetes, infraestructura en la nube o VPS para servidores de desarrollo, staging y producci贸n, planificador de tareas como Jira y software de automatizaci贸n para pruebas como Selenium.
```

### 4. 驴Qu茅 es el patr贸n Circuit Breaker en microservicios?

```
Es el patr贸n de dise帽o que usa com煤nmente en la arquitectura de microservicios para evitar que los recursos queden bloqueados ante un fallo del sistema o del m贸dulo. Con este patr贸n evitamos que el cliente o un sistema continue haciendo peticiones en lugar de seguir intentando.
Tiene 3 estados:  cerrado, semi abierto y abierto.
```

### 5. Describe los pasos y software que usas para realizar las pruebas unitarias a un microservicio.

```
He realizado pruebas unitarias en Python y Django usando la librer铆a PyTest y Swagger.
Normalmente creo la funci贸n de prueba al finalizar el desarrollo de alg煤n servicio, para eso se define la entrada 鈥渄ummy鈥? que tendr谩 el servicio, se genera una base de datos de pruebas y se ejecuta la funci贸n que probar谩 al servicio desarrollado. Las funciones de prueba pueden ir de la mano con los casos de uso y entonces habr谩 tantas funciones de prueba en Pytest como casos de uso tenga el proyecto. Se puede usar swagger para exponer las APIs y la documentaci贸n al cliente.
```

### 6. En un servicio REST 驴Qu茅 tipos de m茅todos se pueden usar?

```
Los m茅todos usados son los siguientes:
HEAD
GET: Obtener informaci贸n.
POST: Creaci贸n de nuevo registros.
PUT: Actualizar por completo la informaci贸n.
PATCH: Actualizar parcialmente la informaci贸n.
DELETE: Borrar informaci贸n.
OPTIONS: Obtener opciones de comunicaci贸n.
```

### 7. Menciona ventahas de usar el lenguaje de programaci贸n Python para web services.

```
Es un lenguaje OpenSource, tiene un est谩ndar de codificaci贸n ordenado y revisado. La comunidad del lenguaje es activa pues actualmente a煤n se contin煤a trabajando en exportar librer铆as de la versi贸n 2 a la versi贸n 3. Y es lenguaje interpretado por lo que su ejecuci贸n llega a ser m谩s r谩pida.
```

### 8. 驴Qu茅 es una funci贸n lambda?

```
En Python una funci贸n lambda es el equivalente a una funci贸n an贸nima. Se definen con la palabra lambda, la lista de par谩metros a recibir y la expresi贸n a evaluar.
En AWS, es un servicio que permite ejecutar c贸digo sin la necesidad de desplegar y configurar un servidor.
```

### 9. 驴Qu茅 funcionalidad tienen una API Gateway?

```
Es el punto de entrada y de comunicaci贸n entre los clientes (web, mobile, etc) y el backend. Aqu铆 solemos encontrar funciones de invocaci贸n autenticaci贸n y reglas de seguridad.
```

### 10. Menciona que m茅todos de autorizaci贸n se pueden aplicar para servicios REST.

```
Autenticaci贸n b谩sica: Encabezado HTTP (Authorization)
Autenticaci贸n por Token.
Autenticaci贸n por clave: Se genera y env铆a u  key y el secret del sistema.
Oauth 2.0
```




---
Escrito por Gustavo Hern谩ndez Mart铆nez. 鉂わ笍 
