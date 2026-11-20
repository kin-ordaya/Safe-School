# SafeSchool

Prototipo web de acompañamiento escolar para que estudiantes puedan orientarse y dar un primer paso para pedir ayuda, con la conversación mediante chatbot como funcionalidad principal.

> **Estado:** estructura inicial del repositorio. La nueva versión del sitio web está pendiente de implementación.

## Objetivo

- Ofrecer una experiencia simple y clara, con una guía rápida en la primera pantalla para usar el chatbot.
- Centralizar recursos de apoyo y orientación en un formato accesible.
- Mantener un sitio estático, fácil de mantener y desplegar (por ejemplo, en Netlify).

## Estructura del proyecto

```text
.
├── assets/                 # Recursos del sitio (cuando se implemente)
│   ├── css/
│   ├── img/
│   └── js/
├── docs/                   # Documentación y material de referencia (no desplegable)
│   ├── prototipo/
│   │   └── SafeSchool-1.html
│   ├── referencia/
│   │   └── SafeSchool_v3.pptx.pdf
│   └── README.md
├── .gitignore
└── README.md
```

## Material de referencia

- [`docs/prototipo/SafeSchool-1.html`](docs/prototipo/SafeSchool-1.html): prototipo HTML inicial.
- [`docs/referencia/SafeSchool_v3.pptx.pdf`](docs/referencia/SafeSchool_v3.pptx.pdf): referencia visual y de contenido (tono, mensajes y funcionalidad planteada, incluido el chatbot).
- Más detalle en [`docs/README.md`](docs/README.md).

## Estado actual

- [x] Repositorio inicializado.
- [x] Estructura base de carpetas creada.
- [x] Material de referencia organizado en `docs/`.
- [ ] Maquetación de la nueva landing (secciones, menú claro y guía rápida).
- [ ] Integración del chatbot.
- [ ] Ajustes de accesibilidad, responsive y optimización de recursos.
- [ ] Configuración y despliegue en Netlify.

## Desarrollo y despliegue (previsto)

Proyecto pensado como **sitio estático** (sin proceso de build complejo):

- **Local:** abrir `index.html` en el navegador una vez que exista la implementación.
- **Netlify:** publicar el directorio que contenga `index.html` (raíz del proyecto), sin comando de build.

## Nota importante

Este prototipo es una herramienta de orientación y no reemplaza el acompañamiento de adultos, profesionales ni de los servicios de emergencia. Ante una situación de riesgo inmediato, se debe buscar ayuda de un adulto de confianza o de los servicios de emergencia locales.
