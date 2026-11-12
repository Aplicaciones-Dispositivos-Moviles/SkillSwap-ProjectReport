# SkillSwap-ProjectReport

Informe de Trabajo Final del curso **1ACC0238 Aplicaciones para Dispositivos Móviles** (NRC 4948, período 202620) de la Universidad Peruana de Ciencias Aplicadas, Carrera de Ingeniería de Software. Docente: Eduardo Martin Reyes Rodriguez.

**Startup:** Innovify · **Producto:** SkillSwap, plataforma móvil B2C freemium de validación práctica de habilidades para estudiantes universitarios y jóvenes profesionales: rutas de certificación generadas con IA a partir de una meta en lenguaje natural, evaluaciones (quiz y miniproyecto), verificación entre pares por Verificadores habilitados por habilidad, SkillCredits, reputación y moderación.

| Código | Apellidos y nombres |
| :--- | :--- |
| U201924127 | Alberca Saavedra, Víctor Manuel |
| U20231C792 | Becerra Ninahuanca, Luis Angel |
| U201724692 | Komatsu Dueñas, David |
| U20241D958 | Lopez Montalvo, Kevin Edu |
| U202423711 | Sulca Sánchez, Piero Angel |

## Informe

Este `README.md` es el archivo principal del repositorio. El contenido completo del informe, con la carátula, está en [`upc-pre-02-1acc0238-4948-Innovify-report-avn2.md`](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md), a partir del cual se genera el PDF de cada entrega (AV1, TB1, AV2 y TB2). Las imágenes están en `images-doc/` y `public/assets/images-doc/`, y las fuentes PlantUML de los diagramas C4, de clases, de base de datos y del Context Mapping en `DB&C4/`.

- [Registro de Versiones del Informe](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#project-report-collaboration-insights)
- [Student Outcome](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#student-outcome)
- [Objetivos SMART](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#objetivos-smart)
- [Capítulo I: Presentación](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#capítulo-i-presentación)
- [Capítulo II: Requirements Development and Software Solution Design](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#capítulo-ii-requirements-development-and-software-solution-design)
- [Capítulo III: Solution UI/UX Design](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#capítulo-iii-solution-uiux-design)
- [Capítulo IV: Product Implementation & Validation](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#capítulo-iv-product-implementation--validation)
- [Conclusiones](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#conclusiones)
- [Glosario](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#glosario)
- [Bibliografía](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#bibliografía)
- [Anexos](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#anexos)

## Repositorios de la solución

| Producto | Repositorio |
| :--- | :--- |
| Web Services RESTful (Java / Spring Boot) | [SkillSwap-WebServices-Java](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices-Java) |
| Aplicación nativa del Estudiante (Kotlin / Jetpack Compose) | [SkillSwap-MobileApp](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp) |
| Aplicación del Verificador (Flutter / Dart) | [SkillSwap-MobileApp-Flutter](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp-Flutter) |
| Landing Page (HTML, CSS y JavaScript) | [SkillSwap-LandingPage](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-LandingPage) · [sitio publicado](https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/) |

## Convenciones del repositorio

- GitFlow: el trabajo se hace en ramas `feature/report-<tema>` creadas desde `develop` y se integra mediante Pull Requests hacia `develop`; `main` recibe `develop` en cada entrega.
- Conventional Commits con el tipo `docs` (por ejemplo, `docs(report): ...`).
- Cada cambio relevante se registra en el [Registro de Versiones del Informe](upc-pre-02-1acc0238-4948-Innovify-report-avn2.md#registro-de-versiones-del-informe).
