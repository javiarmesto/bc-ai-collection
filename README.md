# Business Central & IA · colección de Javier Armesto

**[Abrir la web pública](https://javier-armesto-bc-ai-hub.vercel.app)** · [Perfil de GitHub](https://github.com/javiarmesto)

## ALDC · AL Agentic Engineering System

Mi proyecto principal: agentes especializados, skills reutilizables y controles humanos para trabajar desde los requisitos hasta la revisión de extensiones de Business Central. Distribuciones para Copilot Chat, Copilot CLI, Claude Code y Codex.

[Repositorio ALDC](https://github.com/javiarmesto/ALDC-AL-Development-Collection) · [Instalación](https://javiarmesto.github.io/ALDC-AL-Development-Collection/start-es/) · [Laboratorios](https://github.com/javiarmesto/aldc-workshop-lab)

## Conocimiento, evaluación e integración

| Recurso | Qué encontrarás |
|---|---|
| [BCQuality · original](https://github.com/microsoft/BCQuality) / [mi fork](https://github.com/javiarmesto/BCQuality) | Conocimiento y revisión AL con citas. Mi fork incorpora al-knowledge para diseño y especificación; conserva la autoría original. |
| [BC-Bench Guide EN/ES](https://github.com/javiarmesto/BC-Bench-Guide) | Guía propia para experimentos reproducibles con el [framework de Microsoft](https://github.com/microsoft/BC-Bench). |
| [Ático](https://github.com/javiarmesto/Atico-a-Business-Central-M365-Cowork-plugin-guide) | Integración de Business Central con Cowork mediante MCP. |
| [CIRCE](https://github.com/javiarmesto/CIRCE-Agent-Squad-for-Microsoft-Copilot-Studio) | Agentes de Copilot Studio y casos de negocio. |

## Sesiones y temas

| Edición | Temas y materiales |
|---|---|
| [Bizz Summit ES · 3 octubre 2026](https://github.com/javiarmesto/BizzSummit2026) | Copilot Studio desde VS Code, conocimiento y skills. [Demo de compras](https://github.com/javiarmesto/circe-compras-copilot-studio), con datos ficticios. |
| [Companial · 1 octubre 2026](https://github.com/javiarmesto/companial-workshop-2026) | ALDC, AL, skills, plugins y revisión BCQuality. Jornada con Roberto Corella. |
| SevillaERP Innovate · 22 septiembre 2026 | IA aplicada al ERP, Business Central y MCP. |
| Workshop París · 19 septiembre 2026 | IA agéntica enfocada a AL. |
| [Huelva Summit · 14 octubre 2026](https://huelvasummit.es/) · próxima | Mi equipo de agentes: asistentes, desarrollo agéntico e Intelligent UI. |
| [Directions EMEA 2026](https://github.com/javiarmesto/Directions26_Session) · en preparación | Deja de reinventar AL: ALDC, skills y comunidad. Con Fernando Artigas. |

Los proyectos propios y las contribuciones a iniciativas de comunidad se identifican por separado. Consulta los requisitos, licencias y límites de cada recurso en su repositorio.

[TechSphere Dynamics](https://techspheredynamics.com) · [Substack](https://javiarmesto.substack.com) · [YouTube](https://www.youtube.com/@techspheredynamics9753)

_Actualización: 10 de octubre de 2026._


## Mantener la web

Este repositorio contiene la colección y el sitio estático: `dist/index.html`, `dist/style.css` y `dist/app.js`. Sin dependencias, analítica ni conexiones empresariales. Datos de proyectos y sesiones en `dist/app.js`.

ALDC tiene el espacio principal. BCQuality y BC-Bench enlazan los originales; las contribuciones del fork y la guía propia se identifican expresamente. Los eventos futuros tienen su estado separado. La colección editorial complementa el [inventario documental](https://github.com/javiarmesto/ALDC-AL-Development-Collection/blob/main/docs/public-repositories.md), que conserva el detalle de la revisión.

La web está desplegada en Vercel y conectada a este repositorio. Los cambios en `main` se publican automáticamente. `vercel.json` configura Other, sin instalación ni build, con `dist` como directorio de salida. La versión anterior de Sites se conserva como referencia.

Diseño de cuaderno de ingeniería: retícula, mapa visual de ALDC e índice numerado de recursos. Filtros y búsqueda comprobados en la web desplegada.

Antes de publicar cambios: `node --check dist/app.js`; revisar enlaces, fechas y autores. Las licencias de los recursos enlazados se consultan en sus repositorios y no se amplían por aparecer en esta colección.

## Armesto World

El mapa jugable está integrado en la landing ES/EN y se sirve desde `dist/world/`, bajo `/world/`. La portada lo incluye en un iframe del mismo dominio; `/world/?embed=1` muestra la versión compacta y `/world/` abre la experiencia completa. No depende del Site privado de ChatGPT.

La experiencia interactiva está en español. Presenta seis proyectos, sus README, la ficha de Javier y hasta 30 eventos públicos disponibles de GitHub. Consulta la API pública sin token y conserva una copia fechada para fallos de red o límites de peticiones. El progreso y los 100 XP por proyecto visitado representan la exploración del visitante y se guardan en su navegador, no métricas de productividad de Javier.

Comprobar también `node --check dist/world/app.js` y `node --check dist/world/snapshot.js`. Probar la navegación de la landing, el iframe en escritorio/móvil, las fichas, los README y el regreso desde `/world/` al cuaderno público.
