# QA Study Notes

### Enfoque: QA, Automatización e Infraestructura
### Licencia: MIT
### Entorno: Local / Cloud

Un repositorio centralizado de apuntes técnicos, guías de arquitectura, metodologías y scripts de automatización enfocados en la ingeniería de aseguramiento de calidad (QA). Diseñado para servir como base de conocimiento ágil, estructurada y de rápido acceso.

---

## Contenido del Repositorio

El proyecto está organizado de manera modular por tecnologías y capas de pruebas (Manual, API, Automation, Performance, Security e Infraestructura):

### Fundamentos y Gestión
*   **`curso-qa.html`**: Fundamentos de Aseguramiento de Calidad, ciclo PDCA, taxonomía de fallas y diseño de Test Plans.
*   **`curso-jira.html`**: Gestión ágil con Scrum/Kanban, flujos de trabajo e ingeniería del reporte de bugs.

### Automatización y Contratos
*   **`curso-cypress.html`**: Framework de automatización E2E, fixtures, API testing y auditorías de accesibilidad (A11y).
*   **`curso-playwright.html`**: Automatización E2E multiplataforma y multi-navegador con interactores inteligentes.
*   **`curso-postman.html`**: Pruebas automatizadas de APIs REST, aserciones en JavaScript y ejecución CLI con Newman.
*   **`curso-json.html`**: Estructuras de datos, modelado de tipos y validación de contratos mediante JSON Schema.

### Performance y Seguridad (Especializaciones)
*   **`curso-jmeter.html`**: Ingeniería de rendimiento, inyección de carga, análisis de latencia y métricas de throughput.
*   **`curso-owasp-zap.html`**: Pruebas dinámicas de seguridad (DAST), interceptación de tráfico y técnicas de Fuzzing.

### Infraestructura y DevOps
*   **`curso-aws.html`**: Emulación de servicios Cloud locales (S3, DynamoDB, SQS, Lambdas) usando LocalStack y Boto3.
*   **`curso-docker.html`**: Contenedores, aislamiento de entornos de prueba, Dockerfiles avanzados y Docker Compose.
*   **`curso-jenkins.html`**: Orquestación de pipelines de Integración y Entrega Continua (CI/CD) automatizados.

---

## Arquitectura del Proyecto

El repositorio mantiene una estructura plana, simple y desacoplada de dependencias pesadas, optimizada para su renderizado web inmediato:

```bash
qa-study-notes/
├── index.html              # Home autogestionado con buscador en tiempo real
├── curso-aws.html          # Apuntes de AWS & LocalStack
├── curso-cypress.html      # Apuntes de Cypress
├── curso-docker.html       # Apuntes de Docker
├── curso-jenkins.html      # Apuntes de Jenkins
├── curso-jira.html         # Apuntes de Jira Software
├── curso-jmeter.html       # Apuntes de Apache JMeter
├── curso-json.html         # Apuntes de JSON & JSON Schema
├── curso-owasp-zap.html    # Apuntes de OWASP ZAP
├── curso-playwright.html   # Apuntes de Playwright
├── curso-postman.html      # Apuntes de Postman & Newman
├── curso-qa.html           # Apuntes de Fundamentos de QA
└── LICENSE                 # Licencia de uso del repositorio

Cómo Utilizar este Repositorio

Al ser un proyecto estático construido con HTML5 y CSS moderno, no requiere compilación ni servidores complejos.
Opción 1: Uso Local Rápido

    Clona este repositorio en tu máquina local:
    Bash

    git clone [https://github.com/tu-usuario/qa-study-notes.git](https://github.com/tu-usuario/qa-study-notes.git)

    Navega al directorio del proyecto:
    Bash

    cd qa-study-notes

    Abre el archivo index.html en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).

Opción 2: Extensión Live Server (Recomendado en VS Code)

Si utilizas Visual Studio Code, instala la extensión Live Server, haz clic derecho sobre index.html y selecciona "Open with Live Server" para contar con recarga en vivo mientras editas tus notas.
Licencia

Este proyecto se encuentra bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
