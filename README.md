**Español** · [English](README.en.md)

# Hola, soy Cristóbal Nanjarí

Ingeniero Civil en Informática y Telecomunicaciones titulado de la Universidad Diego Portales, Chile.

Me enfoco en el desarrollo full stack, la arquitectura de software, la integración de sistemas, el rendimiento y la automatización de procesos empresariales.

[Portafolio](https://cristobal-nanjari.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/crist%C3%B3bal-nanjar%C3%AD-100377109/) · [CV (PDF)](https://cristobal-nanjari.vercel.app/cv/cv.pdf)

## Proyectos destacados

### MavePOS
Sistema POS y suite ERP multisucursal para Windows con operación local sin internet y sincronización diferida entre tiendas. Operativo en dos sucursales (~5.500 productos por tienda); en una de ellas se registran más de 1.200 ventas al mes.

- Arquitectura modular en Electron con SQLite (WAL), catálogo en RAM optimizado (< 15 ms p95 en búsqueda F2/F10 hasta 50.000 SKU) e integración con periféricos comerciales.
- Sincronización multi-sucursal sin servidor backend propio, transferencias parciales y catálogo consolidado.
- 1.118 pruebas automatizadas aprobadas (99 suites) y auditoría automatizada de contraste y estabilidad visual (ver metodología en el showcase).

**Stack:** TypeScript, React, Electron, SQLite (WAL), Zustand, Tailwind CSS.

[Showcase técnico (código cerrado)](https://github.com/cristobal-nan/mavepos-showcase) · [Caso de estudio](https://cristobal-nanjari.vercel.app/projects/mavepos)

### Sistema de asistencia académica (UDP)
Plataforma full stack de registro presencial de asistencia para web, Android e iOS con tokens QR dinámicos firmados, confirmación en tiempo real por WebSocket, alertas por umbral e integración bidireccional con Canvas LMS. Proyecto de título (2025) probado en un piloto académico de 5 secciones (~40 estudiantes por sección).

**Stack:** Python, FastAPI, Flutter, Next.js, TypeScript, Firebase (Auth, Firestore, FCM).

[Repositorio](https://github.com/cristobal-nan/academic-attendance-system) · [Caso de estudio](https://cristobal-nanjari.vercel.app/projects/udp-attendance)

### Laminitas Tracker
Aplicación móvil offline para gestionar las 980 láminas del álbum FIFA World Cup 2026, con intercambio QR interoperable, motor de reglas para el *Update Set* (118 reemplazos), comparador de listas de texto y control de gastos.

**Stack:** Flutter, Dart, Riverpod, Hive.

[Repositorio](https://github.com/cristobal-nan/laminitas-tracker) · [Descargar APK v1.9.0](https://github.com/cristobal-nan/laminitas-tracker/releases/tag/v1.9.0) · [Caso de estudio](https://cristobal-nanjari.vercel.app/projects/collectibles-app)

### Portafolio profesional
Sitio estático bilingüe (ES/EN) con casos de estudio técnicos, diagramas de arquitectura, benchmarks y experiencia profesional.

**Stack:** Next.js 16 (Static Export), React 19, TypeScript, Tailwind CSS v4.

[Sitio web](https://cristobal-nanjari.vercel.app/) · [Código fuente](https://github.com/cristobal-nan/portafolio)

## Competencias técnicas

- **Lenguajes:** TypeScript, JavaScript, Python, SQL, Dart.
- **Frontend:** React, Next.js, Vue.js, Tailwind CSS.
- **Backend:** FastAPI, APIs REST, WebSockets.
- **Móvil y escritorio:** Flutter, Electron.
- **Bases de datos:** SQLite, PostgreSQL, MongoDB, Cloud Firestore, Hive.
- **Infraestructura y herramientas:** Docker, Linux, AWS, Vercel, Git.

## Contacto

- **Ubicación:** Santiago, Chile
- **Correo:** [cristobal.nan@gmail.com](mailto:cristobal.nan@gmail.com)
- **Idiomas:** Español (nativo) · Inglés (avanzado)
