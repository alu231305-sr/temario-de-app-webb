# temario-de-app-webb
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
<img width="319" height="160" alt="image" src="https://github.com/user-attachments/assets/3b2659de-7f84-4669-b995-6afa40b5883d" />

1.-Introducción al desarrollo web  
Historia y evolución del desarrollo web  
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA) 

## Historia y evolución del desarrollo web
El desarrollo web nació a principios de los años 90 con la creación de la World Wide Web y los primeros navegadores. Inicialmente, las páginas web eran simples documentos HTML estáticos. Con el tiempo, surgieron tecnologías como CSS y JavaScript, permitiendo mayor interactividad y diseño. Posteriormente, surgió el desarrollo backend, bases de datos, frameworks y arquitecturas avanzadas para soportar aplicaciones complejas. Actualmente, el desarrollo web abarca desde sitios estáticos hasta aplicaciones web progresivas y servicios en la nube.

## Tipos de aplicaciones web
- **Estáticas:** Contenido fijo, sin interacción con bases de datos (HTML, CSS).
- **Dinámicas:** El contenido se genera en tiempo real en función del usuario o base de datos (PHP, Node.js, etc.).
- **SPA (Single Page Application):** Aplicación de una sola página donde la navegación no recarga el sitio completo (React, Angular, Vue).
- **PWA (Progressive Web App):** Aplicaciones web que ofrecen experiencia similar a apps nativas, con capacidades offline y notificaciones.


2.Arquitectura de aplicaciones web  
Cliente-Servidor  
Arquitectura de tres capas (presentación, lógica, datos)  
REST y API-first design  

## Cliente-Servidor
Modelo donde el cliente (navegador) solicita recursos y servicios al servidor, que procesa y responde. Permite separar las responsabilidades de la presentación (frontend) y la lógica/datos (backend).

## Arquitectura de tres capas
- **Presentación:** Interfaz de usuario (HTML, CSS, JS).
- **Lógica de negocio:** Procesa datos y reglas de la aplicación (PHP, Node.js).
- **Datos:** Gestiona almacenamiento y recuperación de información (MySQL, MongoDB).

Esta separación facilita el mantenimiento y escalabilidad de las aplicaciones.

## REST y API-first design
- **REST:** Estilo de arquitectura que utiliza HTTP para crear APIs predecibles, simples y escalables, basadas en recursos y operaciones estándar (GET, POST, PUT, DELETE).
- **API-first design:** Estrategia donde la definición y diseño de la API es el primer paso antes de implementar frontend o backend, permitiendo desarrollo paralelo y mejor integración.

3. -Lenguajes y tecnologías fundamentales  
HTML, CSS, JavaScript, PHP, MySQL

- **HTML:** Lenguaje de marcado para estructurar contenido web.
- **CSS:** Lenguaje de estilos para el diseño y presentación visual.
- **JavaScript:** Lenguaje de programación que aporta interactividad y lógica en el navegador.
- **PHP:** Lenguaje de programación del lado del servidor para crear contenido dinámico.
- **MySQL:** Sistema de gestión de bases de datos relacional para almacenar y consultar información estructurada.
4.-Control de versiones  
Git y GitHub  
Flujo de trabajo con ramas (branching, merge, pull requests)

## Git y GitHub
- **Git:** Sistema de control de versiones distribuido, permite gestionar cambios en el código y la colaboración entre desarrolladores.
- **GitHub:** Plataforma basada en Git para alojar, compartir y colaborar en proyectos de software.

## Flujo de trabajo con ramas
- **Branching:** Crear ramas para desarrollar nuevas características o corregir errores sin afectar la rama principal.
- **Merge:** Unir cambios de diferentes ramas, integrando nuevas funcionalidades al proyecto base.
- **Pull Requests:** Solicitud de revisión y fusión de cambios en una rama hacia otra (por lo general, hacia la rama principal), facilitando la colaboración y revisión de código.

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
1.-Diseño e implementación del frontend  
Maquetación/Wireframe/Mockup
API

# 1. Diseño e Implementación del Frontend

## Maquetación / Wireframe / Mockup
- **Maquetación:** Proceso de estructurar visualmente la página usando HTML y CSS antes de añadir funcionalidad.
- **Wireframe:** Boceto simple para definir la estructura y jerarquía del contenido.
- **Mockup:** Diseño más detallado y visual, muestra colores, tipografías y el aspecto final antes de codificar.

## API
El frontend consume APIs para obtener y enviar datos al backend. Utiliza métodos HTTP (GET, POST, PUT, DELETE) para interactuar con servicios y mostrar información dinámica en la interfaz.

2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)

## Servidor
El backend se implementa en lenguajes como Node.js, PHP, Python, etc. Se encarga de procesar la lógica de negocio, servir archivos y gestionar la comunicación con la base de datos.

## Manejo de Peticiones y Respuestas HTTP
El servidor recibe solicitudes (peticiones) del cliente (frontend), las procesa y responde con datos o resultados. Se utilizan frameworks como Express (Node.js), Flask (Python), Laravel (PHP) para facilitar este proceso.

## Conexión a Bases de Datos (MySQL, PostgreSQL, MongoDB)
El backend gestiona conexiones a bases de datos relacionales (MySQL, PostgreSQL) o NoSQL (MongoDB) para almacenar y recuperar datos según las necesidades de la aplicación.

3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend

## Modelado de Datos y Relaciones
El modelado de datos define cómo se estructuran las entidades y sus relaciones (uno a uno, uno a muchos, muchos a muchos) usando diagramas entidad-relación (ERD).

## ORM (Object Relational Mapping)
Un ORM permite interactuar con la base de datos usando objetos y métodos del lenguaje de programación, evitando escribir SQL manualmente. Ejemplos: Sequelize (Node.js), Eloquent (Laravel), SQLAlchemy (Python).

## CRUD desde el Backend
El backend implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para manipular los datos en la base de datos a través de la API.

4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

# Interfaz de Usuario Frontend
La interfaz de usuario (UI) representa la parte visual con la que interactúan los usuarios. Se desarrolla usando tecnologías como HTML, CSS y JavaScript, y frameworks como React, Angular o Vue.js. El frontend se encarga de mostrar datos, recibir entradas del usuario y enviar solicitudes al backend.

## Manejo de API
El frontend se comunica con el backend a través de APIs (Interfaz de Programación de Aplicaciones), generalmente usando HTTP/HTTPS con peticiones AJAX o librerías como Axios o Fetch. El consumo de una API implica enviar datos (por ejemplo, formularios) y recibir respuestas (como mensajes de éxito, errores o datos para mostrar).

**Ejemplo:**
```js
fetch('https://api.misitio.com/usuarios', {
  method: 'GET'
})
.then(response => response.json())
.then(data => console.log(data));
```

## Proceso de Solicitud y Respuesta de Backend
El backend recibe las solicitudes del frontend, procesa la lógica de negocio, accede a bases de datos y devuelve respuestas. Generalmente incluye autenticación, validación y gestión de errores.

**Flujo típico:**
1. El usuario realiza una acción en la UI (por ejemplo, clic en un botón).
2. El frontend hace una solicitud HTTP al backend.
3. El backend procesa la solicitud y responde con datos o mensajes.
4. El frontend actualiza la UI según la respuesta.


2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

## Tipos de Servidores
- **Servidor Físico:** Hardware dedicado a una sola empresa o servicio.
- **Servidor Virtual (VPS):** Espacio virtualizado dentro de un servidor físico, compartido con otros usuarios.
- **Servidor en la nube:** Recursos virtualizados y escalables ofrecidos por plataformas como AWS, Google Cloud o Azure.

## Servidores y Servicios de Hosting
- **Hosting Compartido:** Varios sitios web en un mismo servidor físico, económico pero con recursos limitados.
- **Hosting VPS:** Más control, recursos dedicados y escalabilidad.
- **Hosting Dedicado:** Máximo control y recursos exclusivos.
- **Serverless:** No gestionas servidores directamente, solo subes el código (ej: AWS Lambda).

## Proveedores de Servicios de Almacenamiento
- **Amazon Web Services (AWS) S3:** Almacenamiento de objetos en la nube.
- **Google Cloud Storage:** Similar a S3, con integración a servicios de Google.
- **Azure Blob Storage:** Almacenamiento de archivos en la nube de Microsoft.
- **Otros:** DigitalOcean Spaces, Firebase Storage, etc.


3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto

## Optimización de Recursos (Imágenes, Scripts)
- **Imágenes:** Comprimir y cambiar el tamaño, usar formatos modernos (WebP, AVIF), cargar imágenes de forma diferida (lazy loading).
- **Scripts:** Minificar archivos, reducir dependencias, cargar scripts de forma asíncrona o diferida.

## Despliegue de Aplicaciones Web
- **Build:** Proceso de empaquetar y optimizar la app antes de subirla al servidor.
- **Deploy:** Subida de archivos al servidor o plataforma de hosting.
- **Herramientas comunes:** Vercel, Netlify, GitHub Pages, Heroku, Docker.

## CI/CD Básico
La Integración Continua y el Despliegue Continuo (CI/CD) automatizan pruebas y despliegue de aplicaciones.
- **CI:** Automatiza pruebas y compilación tras cada cambio en el código.
- **CD:** Automatiza el despliegue a producción tras pasar las pruebas.

**Ejemplo de CI/CD con GitHub Actions:**
```yaml
name: Deploy app
on: [push]
jobs:
  build-and-deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Instalar dependencias
        run: npm install
      - name: Ejecutar pruebas
        run: npm test
      - name: Desplegar
        run: npm run deploy
```

## Documentación del Proyecto
La documentación es esencial para mantener, escalar y colaborar en el proyecto. Debe incluir:
- **README.md:** Descripción general, instalación, uso, tecnologías usadas.
- **Guía de API:** Endpoints, ejemplos de solicitud y respuesta.
- **Manual de despliegue:** Pasos para desplegar la aplicación.
- **Guía de contribución:** Cómo contribuir, reporte de bugs, estilo de código.
