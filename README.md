# ¡Hola! Soy Juan Carlos Lopez Ojeda 

Soy desarrollador Fullstack apasionado por crear soluciones eficientes y trabajar en equipo.

##  Tecnologías y Herramientas
* **Lenguajes:** JavaScript, Python, TypeScript
* **Frameworks/Libs:** React, Node.js, Express
* **Herramientas:** Git, GitHub, Docker, SQL, AWS

##  Proyectos y Colaboraciones Destacadas

Aunque no soy el propietario principal de algunos de estos repositorios, he sido colaborador clave en su desarrollo técnico:
###  [SaiaGym](https://github.com/almaGle/SaiaGym)
* **Descripción:** Este proyecto es tanto una pagina web como una app movil para el acompañamiento deportivo en el gym que puede registrar rutinas y darles un seguimiento personalizado
##  Arquitectura y Tecnologías Clave

###  Arquitectura Serverless Escalable
La lógica del backend fue diseñada para operar sin servidores dedicados, aprovechando el ecosistema de AWS para maximizar el rendimiento y optimizar recursos:
* **AWS Lambda:** Desacoplamiento de la lógica del servidor tradicional en funciones bajo demanda. Esto garantiza una escalabilidad automática y una reducción significativa de costos al eliminar la necesidad de mantener instancias activas permanentes (como EC2).
* **Amazon API Gateway:** Implementado como la puerta de entrada segura y centralizada para la API. Se encarga del enrutamiento de solicitudes, la validación estricta de peticiones y la protección contra ataques DDoS mediante políticas de *throttling*.

###  Seguridad y Gestión de Identidad
Se implementó una estrategia de seguridad robusta tanto a nivel de aplicación como de infraestructura de red:
* **Autenticación Dual:** Soporte fluido para inicio de sesión tradicional (local) y autenticación federada mediante **Google OAuth 2.0**.
* **Sesiones Stateless:** Orquestación de la identidad del usuario utilizando **Passport.js** y emisión de **JWT** (JSON Web Tokens), el estándar ideal para manejar autorizaciones en entornos serverless.
* **Aislamiento de Infraestructura:** Configuración de red estricta mediante **VPC** (Virtual Private Cloud) y **Security Groups**. La base de datos permanece completamente aislada de la red pública, siendo accesible única y exclusivamente a través de las funciones Lambda autorizadas.

###  Procesamiento de Datos de Alto Rendimiento
* **Manejo de Cargas Complejas (JSON Parsing):** Desarrollo de endpoints optimizados capaces de recibir y procesar estructuras de datos profundas en una sola petición (por ejemplo, rutinas de gimnasio completas que anidan múltiples ejercicios y series).
* **Optimización de Base de Datos:** Uso avanzado de la función `JSON_TABLE` en **MySQL** para descomponer objetos JSON masivos directamente en el motor de la base de datos. Esto permite normalizar la información al vuelo y ejecutar inserciones atómicas de alto rendimiento.

###  [inmobiliaria](https://github.com/OsvaldoMrn/inmobiliaria)
* **Descripción:** Una pagina web que simula ser la pagina web de una inmobiliaria 100% funcional.
* **Mi Rol y Contribuciones:**
  * Desarrolle los endpoints para dar de alta una propiedad, editarla y darla de baja.
  * Diseñe en figma parte del diseño de la pagina
  * Aplique el diseño en el frontend
* **Tecnologías usadas:** Node.js.
  
###  [BibliotecaApi](https://github.com/OsvaldoMrn/BibliotecaApi)
* **Descripción:** Este proyecto es un sistema de gestión para bibliotecas universitarias. Permite a los usuarios consultar, reservar y gestionar préstamos de libros, y a los administradores controlar el inventario y generar reportes.
* **Mi Rol y Contribuciones:**
  * Desarrolle el endpoints para agregar libros
  * Desarrole el enspoint para borrar libros
  * Desarrole el endpoint para actualizar los libros
* **Tecnologías usadas:** Node.js.
##  Cómo contactarme
* **LinkedIn:** https://www.linkedin.com/in/juan-carlos-lopez-ojeda-436116247/
* **Correo:** juancaloslopez0126@gmail.com
