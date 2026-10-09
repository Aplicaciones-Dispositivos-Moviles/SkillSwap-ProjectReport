<p align="center">
  <img src="public/assets/images-doc/Logo-Upc.png" alt="Logo UPC" width="150">
</p>

<h3 align="center">Universidad Peruana de Ciencias Aplicadas</h3>

<h3 align="center">Carrera de Ingeniería de Software</h3>

<br>

<p align="center">
<strong>1ACC0238</strong><br>
<strong>Aplicaciones para Dispositivos Móviles</strong>
</p>

<p align="center">
<strong>NRC</strong><br>
4948
</p>

<p align="center">
<strong>Docente</strong><br>
Eduardo Martin Reyes Rodriguez
</p>

<h2 align="center">Informe de Trabajo Final</h2>

<p align="center">
<strong>Equipo</strong><br>
Innovify
</p>

<p align="center">
<strong>Proyecto</strong><br>
SkillSwap
</p>

<h3 align="center">Integrantes</h3>

<div align="center">

| Código | Apellidos y nombres |
| :--- | :--- |
| U201924127 | Alberca Saavedra, Víctor Manuel |
| U20231C792 | Becerra Ninahuanca, Luis Angel |
| U201724692 | Komatsu Dueñas, David |
| U20241D958 | Lopez Montalvo, Kevin Edu |
| U202423711 | Sulca Sánchez, Piero Angel | 

</div>

<p align="center">
<strong>Período 202620</strong>
</p>

<p align="center">
Octubre 2026
</p>

<div style="page-break-after: always;"></div>

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **v.01.Avn1** | 10/09/2026 | Alberca Saavedra, Víctor Manuel<br>Becerra Ninahuanca, Luis Angel<br>Lopez Montalvo, Kevin Edu<br>Komatsu Dueñas, David<br>Sulca Sánchez, Piero Angel | Se agregaron los siguientes tópicos:<br><br>**Student Outcome**<br>**Objetivos SMART**<br><br>**Capítulo I: Presentación**<br>1.1. Startup Profile<br>1.1.1. Descripción de la Startup<br>1.1.2. Perfiles de integrantes del equipo<br>1.2. Solution Profile<br>1.2.1. Antecedentes y problemática<br>1.2.2. Lean UX Process<br>1.2.2.1. Lean UX Problem Statements<br>1.2.2.2. Lean UX Assumptions<br>1.2.2.3. Lean UX Hypothesis Statements<br>1.2.2.4. Lean UX Canvas<br>1.3. Segmentos objetivo<br><br>**Capítulo II: Requirements Development and Software Solution Design**<br>2.1. Competidores<br>2.1.1. Análisis competitivo<br>2.1.2. Estrategias y tácticas frente a competidores<br>2.2. Entrevistas<br>2.2.1. Diseño de entrevistas<br>2.2.2. Registro de entrevistas<br>2.2.3. Análisis de entrevistas<br>2.3. Needfinding<br>2.3.1. User Personas<br>2.3.2. User Task Matrix<br>2.3.3. User Journey Mapping<br>2.3.4. Empathy Mapping<br>2.3.5. As-Is Scenario Mapping<br>2.4. Requirements specification<br>2.4.1. User Stories<br>2.4.2. Impact Mapping<br>2.4.3. Product Backlog<br>2.5. Strategic-Level Domain-Driven Design<br>2.5.1. EventStorming<br>2.5.1.1. Candidate Context Discovery<br>2.5.1.2. Domain Message Flows Modeling<br>2.5.1.3. Bounded Context Canvases<br>2.5.2. Context Mapping<br>2.5.3. Software Architecture<br>2.5.3.1. Software Architecture Context Level Diagrams<br>2.5.3.2. Software Architecture Container Level Diagrams<br>2.5.3.3. Software Architecture Deployment Diagrams<br>2.6. Tactical-Level Domain-Driven Design (los 7 Bounded Contexts: Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Moderation & Disputes)<br>2.6.x.1. Domain Layer<br>2.6.x.2. Interface Layer<br>2.6.x.3. Application Layer<br>2.6.x.4. Infrastructure Layer<br>2.6.x.5. Bounded Context Software Architecture Component Level Diagrams<br>2.6.x.6. Bounded Context Software Architecture Code Level Diagrams<br>2.6.x.6.1. Bounded Context Domain Layer Class Diagrams<br>2.6.x.6.2. Bounded Context Database Design Diagram<br><br>**Conclusiones**<br>**Bibliografía** |
| **v.02.TB1** | 07/10/2026 |  Alberca Saavedra, Víctor Manuel<br>Becerra Ninahuanca, Luis Angel<br>Lopez Montalvo, Kevin Edu<br>Komatsu Dueñas, David<br>Sulca Sánchez, Piero Angel | Se corrigieron y actualizaron los siguientes tópicos, a partir de las decisiones reales tomadas durante la construcción del backend:<br><br>**Capítulo I: Presentación**<br>1.1.1. Descripción de la Startup (modelo de negocio: suscripción mensual vía Google Play Billing, SkillCredits no adquiribles)<br>1.1.2. Perfiles de integrantes del equipo<br>1.2.1. Antecedentes y problemática (corrección de Identity & Access: dominio institucional exigido desde el registro)<br>1.2.2. Lean UX Process (pasarela de pago unificada a Google Play Billing)<br>1.3. Segmentos objetivo<br><br>**Capítulo II: Requirements Development and Software Solution Design**<br>2.1. Competidores<br>2.4.1. User Stories (corrección de US05, US06, US18, US22, US24, US25, US26; se difirieron US07, US19, US20; se agregaron TS11 y TS12)<br>2.4.3. Product Backlog (55 → 57 historias, 204 → 211 Story Points; columna Sprint completada)<br>2.5.1. EventStorming (pasarela de pago y validación de correo institucional)<br>2.5.2. Context Mapping (pasarela de pago, mecanismo de eventos de dominio entre Assessment & Peer Review, Reputation y Recognition & Incentives)<br>2.5.3.1. Software Architecture Context Level Diagrams<br>2.5.3.2. Software Architecture Container Level Diagrams (colapso de los ocho Bounded Contexts en un único contenedor de API, consistente con el nivel de un Container Diagram)<br>2.5.3.3. Software Architecture Deployment Diagrams (MySQL → PostgreSQL, corrección del origen de la llamada a ML Kit)<br>2.6.4. Bounded Context: Assessment & Peer Review (reescritura completa al modelo mínimo realmente implementado)<br>2.6.4.5. Component Diagram de Assessment & Peer Review<br>2.6.5.5. Component Diagram de Reputation<br>2.6.6. Bounded Context: Recognition & Incentives (renombrado de Wallet & Incentives) y su Component Diagram<br>2.6.8. Bounded Context: Subscription & Billing (pasarela renombrada a Google Play Billing; `charge()` corregido a `verifyPurchase()`)<br>Diagrama de Clases general (eliminación de la clase `CreditPurchase`, corrección de `VerifierProfile`, `VerificationCase`, `CreditTransaction`, `Subscription`)<br>Diagrama de Base de Datos general (migración completa a PostgreSQL, corrección de índices únicos parciales, eliminación de `credit_purchases`)<br><br>**Student Outcome** (acumulado con el aporte de TB1 de los cinco integrantes)<br>**Objetivos SMART** (ajuste del objetivo de Alberca Saavedra, Víctor Manuel)<br>**Project Report Collaboration Insights** (acumulado con la evidencia de TB1)<br>**Conclusiones** (tres párrafos nuevos sobre las contradicciones resueltas entre el diseño y la implementación real)<br><br>Se agregaron los siguientes tópicos nuevos:<br><br>**Capítulo III: Solution UI/UX Design**<br>3.1.1. Style Guidelines<br>3.1.2. Information Architecture<br>3.1.3. Landing Page UI Design<br>3.1.4. Mobile Applications UX/UI Design<br><br>**Capítulo IV: Product Implementation & Validation**<br>4.1. Software Configuration Management<br>4.1.1. Software Development Environment Configuration<br>4.1.2. Source Code Management<br>4.1.3. Source Code Style Guide & Coding Conventions<br>4.1.4. Software Deployment Configuration<br>4.2. Landing Page, Services & Applications Implementation<br>4.2.1. Sprint 1<br>4.2.1.1. Sprint Planning 1<br>4.2.1.2. Aspect Leaders and Collaborators<br>4.2.1.3. Sprint Backlog 1<br>4.2.1.4. Development Evidence for Sprint Review<br>4.2.1.5. Testing Suite Evidence for Sprint Review<br>4.2.1.6. Execution Evidence for Sprint Review<br>4.2.1.7. Services Documentation Evidence for Sprint Review<br>4.2.1.8. Software Deployment Evidence for Sprint Review<br>4.2.1.9. Team Collaboration Insights during Sprint |
| **v.03.TB1** | 08/10/2026 | Komatsu Dueñas, David | Se corrigieron los siguientes tópicos:<br><br>**Capítulo I: Presentación**<br>1.1.1. Descripción de la Startup (modelo freemium, habilitación del Verificador en la primera versión y revisión del Verificador como decisión con observaciones)<br>1.1.2. Perfiles de integrantes del equipo (términos del Anexo F)<br>1.2.2.1. Lean UX Problem Statements (revisión del Verificador como decisión con observaciones, según el modelo implementado)<br><br>**Capítulo II: Requirements Development and Software Solution Design**<br>2.1. Competidores, 2.1.1. Análisis competitivo y 2.1.2. Estrategias y tácticas frente a competidores (roadmap.sh, Pluralsight y Platzi como competidores directos)<br>2.5.1. EventStorming (ajustes del modelo posteriores a la sesión)<br>2.3.3 y 2.3.4 (Journey Map y Empathy Map del segmento 2 alineados con el rol de Verificador)<br>2.6.4 y 2.6.8 (habilitación del Verificador al completar el nodo de la habilidad; pasarela de pago Google Play Billing)<br>1.1.1, 1.3, 2.3, 2.3.6, 2.4, 2.5 y 2.6 (el rol de Coordinador se integra en el Verificador, que asume la supervisión del proceso; nombres de User Persona unificados: Valeria Ramos y Rodrigo Castillo)<br>2.4.1. User Stories (57 historias: 45 User Stories y 12 Technical Stories; se agregó el Epic EP10)<br>2.4.3. Product Backlog (totales de 211 Story Points y 145 Story Points en el Sprint 1; captura y URL público del tablero en Trello)<br>2.6.x.6. Bounded Context Software Architecture Code Level Diagrams (encabezado agregado en los Bounded Contexts 2.6.2 a 2.6.8)<br><br>**Capítulo III: Solution UI/UX Design**<br>3.1.2, 3.1.3 y 3.1.4 (diseño para dos roles, Estudiante y Verificador, este último con las funciones de supervisión)<br>3.1.4.2. Mobile Applications Wireflow Diagrams (notas completas de los Wireflows)<br><br>**Capítulo IV: Product Implementation & Validation**<br>4.2.1.1. Sprint Planning 1 (Velocity y Sum of Story Points de 145)<br>4.2.1.3. Sprint Backlog 1 (captura y URL público del tablero en Trello)<br><br>**Objetivos SMART** (dos objetivos por integrante, orientados al desarrollo profesional después del egreso)<br>**Formato general** (niveles de encabezado, numeración de figuras y tablas, índices y tabla de contenidos)<br>**Bibliografía** (organizada por categorías)<br>**Anexos** (nomenclatura de archivos y enlaces de acceso a la solución)<br><br>Se agregaron los siguientes tópicos nuevos:<br><br>2.3.6. Ubiquitous Language<br>**Glosario** |
| **v.04.TB1** | 09/10/2026 | Sulca Sánchez, Piero Angel | Se alinearon los siguientes tópicos con el backend integrado en la rama `develop` de `SkillSwap-WebServices-Java` (PR #1 a #15, migraciones Flyway V1 a V10) y con el Landing Page publicado en GitHub Pages:<br><br>**Capítulos I y II:** modelo freemium con suscripción mensual vía RevenueCat; economía de SkillCredits por tipo de caso (40 por miniproyecto y 25 por quiz; ruta avanzada a 200 y certificado de contribución a 120); habilitación del Verificador al completar el nodo de la habilidad; User Stories y Product Backlog con 44 historias y 154 Story Points en el Sprint 1; EventStorming, Bounded Context Canvases, Context Mapping y diagramas C4 reconciliados con el modelo implementado; 2.6 con el modelo táctico del código (`Dispute` y `DisputesController` en Moderation & Disputes, `AdvancedPathUnlock` y `GeminiSkillTaxonomyMatcher` en Learning Path Engine, `ReviewDeadlinePolicy` en Assessment & Peer Review, `VerifierRank` y `SeniorVerifierPolicy` en Reputation, `ProcessedWebhookEvent` y `PlanLimits` en Subscription & Billing, verificación del correo con Brevo y notificaciones push con Firebase Cloud Messaging en Identity & Access) y diagramas de base de datos generados desde las migraciones<br><br>**Capítulo IV:** repositorios de las aplicaciones móviles, despliegue en Render desde `develop`, variables de entorno, Sprint Backlog con tareas de 4 a 8 horas asignadas según la autoría en Git, commits y merges de los PR #1 a #15 del backend y #1 a #8 del Landing Page, suite de 1978 pruebas y nuevas evidencias de ejecución, documentación y despliegue<br><br>**Project Report Collaboration Insights** (aportes de TB1), **Índice de Tablas y de Figuras** (numeración continua) y **Bibliografía** |

<div style="page-break-after: always;"></div>

---

## Project Report Collaboration Insights

En esta sección se indica el URL del repositorio utilizado para la elaboración colaborativa del Informe de Trabajo Final, así como las evidencias de participación de cada integrante del equipo durante el desarrollo de las entregas AV1 y TB1.

**URL del repositorio del Project Report (GitHub):**
[https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport)

### AV1

Durante el desarrollo de la entrega AV1, el equipo distribuyó la elaboración del informe asignando capítulos y secciones específicas a cada integrante según sus áreas de responsabilidad. Cada miembro realizó sus aportes directamente en el repositorio de GitHub mediante commits en ramas individuales, siguiendo la convención de Conventional Commits y GitFlow, integrando los cambios mediante Pull Requests hacia la rama `develop`. Todos los integrantes participaron activamente en la redacción de secciones del informe en formato Markdown, asegurando coherencia y calidad en el contenido entregado.

A continuación, se presentan las capturas de los analíticos de colaboración del repositorio del informe:

**Figura 1**

*Gráfico de contribuciones al repositorio del Project Report durante AV1*

<p align="center">
  <img src="public/assets/images-doc/PR1.png" alt="Analíticos de colaboración - Project Report" width="800">
</p>

*Nota.* Se evidencia la participación de todos los integrantes del equipo mediante commits realizados en el período correspondiente. Elaboración propia.

**Figura 2**

*Historial de commits en el repositorio del Project Report*

<p align="center">
  <img src="public/assets/images-doc/PR2.png" alt="Historial de commits - Project Report" width="800">
</p>

*Nota.* Se evidencian los aportes individuales de cada integrante con sus respectivos mensajes bajo la convención Conventional Commits. Elaboración propia.

### TB1

Durante el desarrollo de la entrega TB1, el equipo mantuvo el mismo esquema de colaboración de AV1, incorporando además la corrección sistemática del Capítulo I y II a partir de las decisiones reales tomadas durante la construcción del backend (pasarela de pago, modelo de Assessment & Peer Review, motor de matching, taxonomía de habilidades, entre otras), y la redacción del Capítulo IV con la evidencia del Sprint 1. Entre el 11 de septiembre y el 9 de octubre de 2026, sin contar los commits de merge, los aportes al repositorio se distribuyeron de la siguiente manera:

* **Becerra Ninahuanca, Luis Angel (44 commits):** Capítulo II (competidores, entrevistas, needfinding y As-Is / To-Be Scenario Mapping), perfiles del equipo y Capítulo III (wireframes, mock-ups y diseño de producto).
* **Komatsu Dueñas, David (33 commits):** User Stories, épicas, Impact Mapping, Product Backlog, lenguaje ubicuo, numeración APA de figuras y tablas, índice, glosario, bibliografía y registro de versiones.
* **Sulca Sánchez, Piero Angel (23 commits):** EventStorming (pasos 1 a 10), Candidate Context Discovery, Domain Message Flows, Bounded Context Canvases, Lean UX Canvas y alineación del informe con el backend Java y el modelo de negocio.
* **Alberca Saavedra, Víctor Manuel (19 commits):** pivote de los Capítulos I y II al modelo de verificación de habilidades, diagramas C4, Capítulo IV (configuración del software, evidencias del Sprint 1 y despliegue) y migración del informe a Java / Spring Boot.

**Figura 3**

*Gráfico de contribuciones al repositorio del Project Report durante TB1*

<p align="center">
  <img src="public/assets/images-doc/PR3-tb1.png" alt="Analíticos de colaboración - Project Report TB1" width="800">
</p>

*Nota.* Contribuciones semanales a la rama `main` del repositorio SkillSwap-ProjectReport entre el 10 de septiembre y el 8 de octubre de 2026, sin commits de merge (GitHub Insights). Elaboración propia.

**Figura 4**

*Historial de commits en el repositorio del Project Report durante TB1*

<p align="center">
  <img src="public/assets/images-doc/PR4-tb1.png" alt="Historial de commits - Project Report TB1" width="800">
</p>

*Nota.* Historial de commits de la rama `main` del Project Report durante el TB1, con los merges de los Pull Requests de cada integrante. Elaboración propia.




---

## Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [AV1](#av1)
  - [TB1](#tb1)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    - [1. Segmento: Personas que quieren aprender](#1-segmento-personas-que-quieren-aprender)
    - [2. Segmento: Personas que validan el conocimiento](#2-segmento-personas-que-validan-el-conocimiento)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-Is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.1. Bounded Context: Identity & Access](#261-bounded-context-identity--access)
    - [2.6.2. Bounded Context: Credential Verification](#262-bounded-context-credential-verification)
    - [2.6.3. Bounded Context: Learning Path Engine](#263-bounded-context-learning-path-engine)
    - [2.6.4. Bounded Context: Assessment & Peer Review](#264-bounded-context-assessment--peer-review)
    - [2.6.5. Bounded Context: Reputation](#265-bounded-context-reputation)
    - [2.6.6. Bounded Context: Recognition & Incentives](#266-bounded-context-recognition--incentives)
    - [2.6.7. Bounded Context: Moderation & Disputes](#267-bounded-context-moderation--disputes)
    - [2.6.8. Bounded Context: Subscription & Billing](#268-bounded-context-subscription--billing)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide & Coding Conventions](#413-source-code-style-guide--coding-conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page, Services & Applications Implementation](#42-landing-page-services--applications-implementation)
    - [4.2.1. Sprint 1](#421-sprint-1)
- [Conclusiones](#conclusiones)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Índice de Tablas](#índice-de-tablas)
  - [Índice de Figuras](#índice-de-figuras)
  - [Anexo A. Enlaces de Acceso a la Solución](#anexo-a-enlaces-de-acceso-a-la-solución)
  - [Anexo B. Videos de Exposiciones](#anexo-b-videos-de-exposiciones)
  - [Anexo C. Videos de la documentación](#anexo-c-videos-de-la-documentación)

<div style="page-break-after: always;"></div>

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET EAC - Student Outcome 7:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Alberca Saavedra, Víctor Manuel (AV1):** Lideré la investigación de la tecnología externa (ML Kit, SDK de reconocimiento de texto) a integrar en el proyecto móvil, evaluando sus requisitos técnicos y adaptándolos a la arquitectura móvil nativa. Participé en el diseño estratégico de los Bounded Contexts, incluyendo su rediseño tras el pivote del modelo de negocio.<br><br>**Alberca Saavedra, Víctor Manuel (TB1):** Implementé el backend de seis Bounded Contexts, primero en C# / ASP.NET Core y luego, cuando el curso exigió Java, lo migré a Java 21 con Spring Boot, Spring Data JPA (Hibernate), Spring Security con JWT y PostgreSQL, conservando el mismo esquema de base de datos y el mismo contrato de la API. En el proceso investigué y apliqué por primera vez tecnologías no vistas en clase: la API REST de Gemini para generación de contenido con reintentos y modelos de respaldo, la verificación de compras de Google Play Billing, almacenamiento privado de archivos con URLs firmadas en Cloudinary, y pruebas de integración con JUnit 5, MockMvc y Testcontainers contra una base PostgreSQL real. También investigué y resolví una limitación real de infraestructura: Render no ofrece MySQL administrado de forma nativa, lo que me llevó a migrar todo el diseño de persistencia a PostgreSQL antes de implementarlo.<br><br>**Becerra Ninahuanca, Luis Angel (AV1):** Investigué patrones de diseño UI/UX específicos para aplicaciones móviles multiplataforma y colaboré en el análisis competitivo y el diseño de entrevistas enfocadas en la experiencia de movilidad de los estudiantes.<br><br>**Becerra Ninahuanca, Luis Angel (TB1):** Al diseñar el Style Guide y los wireframes del Landing Page, tuve que investigar principios de Information Architecture (sistemas de organización, etiquetado y navegación) que no habíamos aplicado formalmente en AV1, y ajustar las decisiones visuales iniciales al constatar que algunas no se alineaban con el tono de comunicación definido para el segmento de Verificadores.<br><br>**Lopez Montalvo, Kevin Edu (AV1):** Documenté el proceso Lean UX y apliqué el aprendizaje sobre persistencia de datos locales en dispositivos para el diseño de los requisitos, estructurando las User Stories bajo un enfoque Mobile-First.<br><br>**Lopez Montalvo, Kevin Edu (TB1):** Al construir los Wireflow y User Flow Diagrams de las pantallas core (ruta de aprendizaje, resolución del quiz), tuve que aprender a representar formalmente las rutas alternativas (unhappy paths) del flujo —como qué pantalla ve el estudiante cuando un quiz no se aprueba— lo cual exigió coordinar con el diseño real del backend en vez de asumir un flujo ideal.<br><br>**Komatsu Dueñas, David (AV1):** Evalué diferentes estrategias de integración de servicios RESTful y modelé el flujo de mensajes entre los Bounded Contexts aplicando Domain Storytelling adaptado al consumo de APIs desde aplicaciones móviles.<br><br>**Komatsu Dueñas, David (TB1):** Reconocí que parte del flujo de interacción que había modelado con Domain Storytelling en AV1 ya no aplicaba tal cual al construir los prototipos de UI, porque el backend terminó resolviendo ciertos pasos (como la vinculación de certificados) de forma automática y no mediante una pantalla explícita, por lo que tuve que simplificar los mock-ups correspondientes.<br><br>**Sulca Sánchez, Piero Angel (AV1):** Estudié los fundamentos del diseño estratégico con Domain-Driven Design a partir del material del curso y de las plantillas de la comunidad ddd-crew, y los apliqué para elaborar el EventStorming de SkillSwap en sus diez pasos, el Candidate Context Discovery, los Domain Message Flows y los Bounded Context Canvases, modelados en Excalidraw. Para sustentar el problema del Capítulo I, investigué datos estadísticos sobre la brecha entre la certificación y el dominio práctico, los verifiqué en sus fuentes originales y los cité en formato APA 7.<br><br>**Sulca Sánchez, Piero Angel (TB1):** Al revisar el Context Mapping y los Bounded Context Canvases contra lo realmente implementado en el backend, identifiqué que varias relaciones que había modelado en AV1 (Customer/Supplier directo entre Assessment y Reputation) no correspondían al mecanismo real de eventos de dominio, y tuve que aprender el patrón Published Language para corregir los diagramas de forma consistente con el código. | (AV1) El equipo reconoce la necesidad del aprendizaje permanente al investigar e integrar de manera autónoma tecnologías no vistas en clase, como SDKs externos de reconocimiento de texto y persistencia local en dispositivos, aplicando conceptos de Domain-Driven Design al entorno móvil.<br><br>(TB1) El equipo confirma que ese aprendizaje autónomo se sostuvo al pasar del diseño a la implementación real: construir el backend exigió investigar APIs externas completas (Gemini, Google Play Billing) y resolver restricciones de infraestructura no anticipadas en el diseño original (disponibilidad de motores de base de datos en el proveedor de hosting elegido), evidenciando que actualizar conocimientos no se limita a la etapa de diseño sino que continúa durante la construcción del software. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | **Alberca Saavedra, Víctor Manuel (AV1):** Al enfrentar el pivote del modelo de negocio a mitad de ciclo, tuve que reevaluar y rediseñar desde cero la estrategia de Bounded Contexts que ya había avanzado, reconociendo que el conocimiento adquirido durante la investigación previa (SUNEDU, matching por embeddings) no era aplicable al nuevo alcance del curso y debía sustituirse por soluciones más simples y viables.<br><br>**Alberca Saavedra, Víctor Manuel (TB1):** Al construir el backend real, reconocí que varias decisiones documentadas en el diseño (rúbrica por criterio, examen de ingreso del Verificador, tres intentos de quiz, pasarela de pago) no eran viables o necesarias dentro del tiempo del Sprint, y que insistir en implementarlas tal cual hubiera significado no entregar un flujo completo y funcional. Reemplacé esas decisiones por un modelo mínimo igualmente riguroso, y luego tuve que volver sobre el propio informe para que el diseño documentado reflejara honestamente lo construido, en vez de dejar un documento que describiera un sistema distinto al que realmente funciona.<br><br>**Becerra Ninahuanca, Luis Angel (AV1):** Reconocí la necesidad de actualizar el análisis competitivo y las preguntas de entrevista previamente diseñadas, dado que el modelo de negocio original ya no reflejaba la propuesta de valor vigente del proyecto.<br><br>**Becerra Ninahuanca, Luis Angel (TB1):** Reconocí que el Style Guide definido en una primera versión debía replantearse al validarlo contra las pantallas reales de la app, en vez de darlo por cerrado solo porque ya existía un documento.<br><br>**Lopez Montalvo, Kevin Edu (AV1):** Identifiqué la necesidad de revisar y reestructurar la documentación de Lean UX ya elaborada para que reflejara el nuevo enfoque del proyecto, en lugar de darla por completa.<br><br>**Lopez Montalvo, Kevin Edu (TB1):** Reconocí que los User Flows no podían completarse sin antes confirmar con el backend qué reglas de negocio realmente existían (ej. que registrar un certificado no completa un nodo hasta que un Verificador lo valida), lo que me obligó a esperar y ajustar en vez de diseñar el flujo de forma aislada.<br><br>**Komatsu Dueñas, David (AV1):** Reconocí que los flujos de integración entre Bounded Contexts modelados inicialmente debían replantearse por completo tras el cambio de alcance, en vez de simplemente ajustar el software ya diseñado.<br><br>**Komatsu Dueñas, David (TB1):** Reconocí que modelar la interacción sin validarla contra la arquitectura final genera trabajo que luego hay que rehacer, y que coordinar antes con el equipo técnico habría evitado parte del reproceso en los mock-ups.<br><br>**Sulca Sánchez, Piero Angel (AV1):** Al alinear el Capítulo I con el modelo de negocio vigente, reconocí que partes ya redactadas del informe, como el segmento del Coordinador, el canje de SkillCredits y el enfoque en la deserción académica, respondían a un modelo anterior y debían reformularse en lugar de darse por terminadas. Durante el EventStorming, los puntos críticos identificados me llevaron a revisar decisiones del dominio, como la calificación por criterios y el segundo revisor, antes de trasladarlas al diseño, entendiendo que el modelo se refina de forma iterativa.<br><br>**Sulca Sánchez, Piero Angel (TB1):** Reconocí que un Context Mapping elaborado en una etapa temprana del diseño necesita revisarse una vez que el código revela el mecanismo real de comunicación entre contextos, y que mantenerlo actualizado es parte continua del trabajo, no una tarea de una sola vez. | (AV1) El equipo reconoce que el aprendizaje permanente no se limita a adquirir tecnologías nuevas, sino también a la capacidad de soltar y reformular conocimiento previamente validado cuando el contexto del proyecto cambia, como ocurrió tras el pivote del modelo de negocio de tutorías a verificación de habilidades.<br><br>(TB1) El equipo reconoce que ese mismo principio aplica entre el diseño y la implementación: un documento de arquitectura es una hipótesis de trabajo, no una verdad fija, y la disciplina de volver a corregirlo cuando la construcción revela una limitación real —en vez de dejarlo desactualizado— es en sí misma una forma de aprendizaje permanente aplicada al ciclo de vida completo del software. |

<div style="page-break-after: always;"></div>


## Objetivos SMART

Cada integrante del equipo formula dos objetivos SMART (específicos, medibles, alcanzables, relevantes y con plazo definido) orientados a su desarrollo profesional una vez culminada la carrera.

**Alberca Saavedra, Víctor Manuel**

1. Obtener la certificación AWS Certified Developer – Associate dentro de los 12 meses posteriores a mi egreso, aprobando el examen oficial con al menos 3 meses de preparación.
2. Conseguir un puesto de desarrollador backend con .NET o Java en una empresa de software dentro de los 6 meses posteriores a mi egreso, aplicando Domain-Driven Design en al menos un proyecto en producción durante mi primer año de trabajo.

**Becerra Ninahuanca, Luis Angel**

1. Obtener la certificación Google UX Design Professional Certificate dentro de los 8 meses posteriores a mi egreso, completando sus 7 cursos y un portafolio con al menos 3 casos de estudio.
2. Trabajar como diseñador UX/UI o desarrollador frontend en un equipo de producto digital dentro de los 6 meses posteriores a mi egreso, participando en al menos 2 lanzamientos de funcionalidades durante mi primer año.

**Komatsu Dueñas, David**

1. Obtener la certificación Microsoft Certified: Azure Data Fundamentals (DP-900) dentro de los 6 meses posteriores a mi egreso, para fortalecer mi perfil en análisis de datos y calidad de software.
2. Liderar técnicamente al menos 1 proyecto de software, en mi trabajo o como proyecto open source en GitHub, dentro de los 18 meses posteriores a mi egreso, aplicando GitFlow, Conventional Commits y revisiones de código mediante Pull Requests.

**Lopez Montalvo, Kevin Edu**

1. Obtener la certificación ISTQB Certified Tester Foundation Level dentro de los 9 meses posteriores a mi egreso, para respaldar mis conocimientos en pruebas de software.
2. Automatizar las pruebas de al menos 1 aplicación móvil en un entorno profesional dentro de los 12 meses posteriores a mi egreso, cubriendo con pruebas automatizadas como mínimo el 60% de sus flujos críticos.

**Sulca Sánchez, Piero Angel**

1. Publicar al menos 1 aplicación móvil desarrollada con Flutter en Google Play dentro de los 12 meses posteriores a mi egreso, con un mínimo de 100 descargas en sus primeros 3 meses.
2. Conseguir un puesto de desarrollador frontend o móvil (React, TypeScript o Flutter) dentro de los 6 meses posteriores a mi egreso y completar mi primer año en el puesto con una evaluación de desempeño satisfactoria.

---


# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Innovify es una startup tecnológica del sector educativo que desarrolla soluciones orientadas a la validación de habilidades. Su producto, SkillSwap, es una plataforma móvil dirigida principalmente a estudiantes universitarios y jóvenes profesionales que necesitan complementar sus credenciales con una demostración de que pueden aplicar las habilidades declaradas. La propuesta busca reducir la brecha entre completar una actividad formativa y demostrar el dominio práctico de los conocimientos adquiridos.

SkillSwap organiza la experiencia a partir del objetivo declarado por el Estudiante en lenguaje natural: un modelo de inteligencia artificial generativa lo interpreta y selecciona las habilidades correspondientes, siempre dentro de la taxonomía de habilidades de la plataforma, y a partir de ellas el sistema calcula lo que le falta demostrar y ordena los pasos según sus prerrequisitos para proponer una ruta de certificación, compuesta por nodos que se evalúan mediante un *quiz* o un miniproyecto; toda ruta incluye un mínimo de nodos con entrega práctica. El Estudiante puede incorporar certificados externos, cuyos datos se extraen mediante reconocimiento óptico de caracteres con ML Kit para facilitar su registro y análisis de riesgo documental. Esta extracción no demuestra por sí misma el dominio de la habilidad: la comprobación se realiza mediante esas evaluaciones aplicadas, cuya generación puede ser asistida por inteligencia artificial. Cuando la evaluación automática no resulta suficiente, el caso se asigna a un Verificador habilitado, quien revisa el trabajo guiándose por una rúbrica, decide si lo aprueba o lo rechaza y registra sus observaciones; si no lo aprueba, el Estudiante recibe esas observaciones para reforzar lo necesario. Al completar la ruta, el Estudiante presenta una demostración final asíncrona que también califica un Verificador habilitado, de modo que ninguna certificación se emite sin que una persona haya evaluado su trabajo. La certificación queda respaldada por el historial de evaluaciones y revisiones realizadas en la plataforma.

Para revisar casos de otros usuarios, el Estudiante debe habilitarse como Verificador de la habilidad que desea verificar, lo que ocurre al completar el nodo de esa habilidad en su propia ruta. Una vez habilitado, puede participar como Verificador y recibir SkillCredits por cada caso que resuelve, lo apruebe o lo rechace, según el tipo de caso: 40 SkillCredits por un miniproyecto y 25 por un *quiz*, porque revisar un miniproyecto exige más trabajo que revisar un *quiz*. Los SkillCredits constituyen unidades de reconocimiento no monetarias asociadas a su participación y experiencia como Verificador; nunca pueden comprarse con dinero ni transferirse, pero el Verificador puede canjearlos por beneficios dentro de la plataforma: una ruta avanzada, por 200 SkillCredits, o un certificado de contribución, por 120. Los precios se escalaron junto con los montos por caso para que obtener un beneficio siga requiriendo varios casos resueltos (5 miniproyectos u 8 *quizzes* para la ruta avanzada, y 3 miniproyectos o alrededor de 5 *quizzes* para el certificado); si solo hubieran subido los montos por caso, un beneficio costaría alrededor de un caso y perdería su valor. Por separado, el Verificador obtiene rangos visibles en su perfil profesional según la cantidad de casos de verificación que resuelve, no según su saldo de SkillCredits, de modo que canjear créditos nunca reduce su rango. Los rangos son tres: Bronce, de 0 a 29 casos resueltos; Plata, de 30 a 99; y Oro, desde 100 casos resueltos.

Innovify plantea para SkillSwap un modelo de negocio B2C freemium. Todo Estudiante empieza con un plan gratuito (S/ 0), que le permite tener 1 ruta activa a la vez y hasta 3 rutas en total, y escalar 3 casos al mes a un Verificador, que se revisan en un plazo de hasta 5 días hábiles. Cuando llega a uno de esos límites, la aplicación le muestra la pantalla "Alcanzaste el límite de tu plan", donde puede pasar al plan mensual o continuar con el plan gratuito. El plan mensual cuesta S/ 29,90 al mes, IGV incluido, se cobra mediante Google Play Billing, integrado a través de RevenueCat, y amplía esos límites: hasta 3 rutas activas a la vez, sin tope de rutas en total, y 10 escalamientos al mes a un Verificador, cuyos casos se revisan en 48 horas; además, reduce los tiempos de espera. La ruta avanzada que un Verificador obtiene al canjear SkillCredits no consume el cupo de rutas del plan gratuito. Ningún plan compra la aprobación: las evaluaciones y los criterios son los mismos para todos. No existen pagos directos ni comisiones entre Estudiantes y Verificadores. Además, la supervisión del proceso la ejercen los Verificadores senior, es decir, los Verificadores que alcanzaron el rango Oro y mantienen una confiabilidad de 90 o más, en la escala de 0 a 100 con la que la plataforma la mide: monitorean la confiabilidad de las revisiones, resuelven las disputas por certificados sospechosos y consultan métricas generales sobre la actividad del ecosistema. Las apelaciones, en cambio, las revisa un Verificador distinto del que tomó la decisión original.

La asignación de casos se realiza automáticamente considerando la habilidad requerida, el historial y la disponibilidad de los Verificadores. Asimismo, SkillSwap incorpora mecanismos de confianza como la verificación del correo electrónico, el historial auditable de las evaluaciones y la habilitación de Verificadores a partir de las certificaciones obtenidas dentro de la plataforma. Estos mecanismos buscan reducir la dependencia de declaraciones no comprobadas y favorecer un proceso de validación consistente.

#### Visión

Ser una plataforma de referencia en la validación práctica de habilidades, reconocida por ofrecer a estudiantes universitarios y jóvenes profesionales un proceso confiable, trazable y sostenible de certificación y verificación entre pares.

#### Misión

Facilitar que estudiantes universitarios y jóvenes profesionales demuestren el dominio práctico de sus habilidades mediante rutas de certificación, evaluaciones aplicadas apoyadas por tecnología y revisiones estructuradas entre pares. Innovify reconoce la contribución de los Verificadores mediante SkillCredits y mantiene mecanismos de moderación para supervisar la confiabilidad y el seguimiento del proceso de validación.


### 1.1.2. Perfiles de integrantes del equipo

**Tabla 1**

*Perfiles de los integrantes del equipo*

<div align="center">

| Foto | Integrante | Carrera | Descripción |
| :---: | :--- | :--- | :--- |
| <img src="public/assets/images-doc/image-perfil-victor.png" width="100"> | **Alberca Saavedra, Víctor Manuel**<br>(U201924127) | Ingeniería de Software | Aporta conocimientos sólidos en arquitectura de software, backend y bases de datos. Lidera la investigación e integración del SDK de reconocimiento de texto (ML Kit) y la adaptación de los Bounded Contexts al entorno móvil. |
| <img src="public/assets/images-doc/image-perfil-luis.png" width="100"> | **Becerra Ninahuanca, Luis Angel**<br>(U20231C792) | Ingeniería de Software | Especialista en lógica de negocio, integración de servicios e interfaces limpias. Investiga patrones de diseño UI/UX propios de aplicaciones móviles nativas/multiplataforma y lidera el análisis competitivo enfocado en apps del mismo rubro. |
| <img src="public/assets/images-doc/image-perfil-kevin.png" width="100"> | **Lopez Montalvo, Kevin Edu**<br>(U20241D958) | Ingeniería de Software | Aporta conocimientos en diseño móvil, UX/UI y marcos de trabajo ágiles. Documenta el proceso Lean UX y estructura las User Stories bajo un enfoque Mobile-First. |
| <img src="public/assets/images-doc/image-perfil-david.png" width="100"> | **Komatsu Dueñas, David**<br>(U201724692) | Ingeniería de Software | Enfocado en investigación tecnológica, análisis de datos y control de calidad. Lidera el modelado de flujos de mensajes entre Bounded Contexts y el diseño de diagramas de arquitectura. |
| <img src="public/assets/images-doc/image-perfil-piero.jpg" width="100" alt="Fotografía de Piero Angel Sulca Sánchez"> | **Sulca Sánchez, Piero Angel**<br>(U202423711) | Ingeniería de Software | Cuenta con experiencia en desarrollo web y trabajo en equipos pequeños. Se especializa en frontend y muestra interés por el diseño creativo de interfaces, especialmente en experiencias 3D, animaciones y productos digitales diferenciados. Aporta conocimientos en levantamiento de requisitos, diseño de interfaces, desarrollo web con React y TypeScript, y diseño de bases de datos, además de organización y colaboración en equipo. |

</div>

*Nota.* Elaboración propia.


<br>

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

En el mercado laboral peruano existe una brecha entre las habilidades requeridas por las organizaciones y las que encuentran entre los postulantes. La Encuesta de Habilidades al Trabajo 2017-2018 señala que el 47% de las empresas con vacantes tuvo dificultades para cubrirlas y que el 76% de las vacantes difíciles de cubrir se relacionó con la falta de habilidades de los candidatos (Novella et al., 2019). Estas cifras establecen el contexto de una brecha de habilidades que exige mecanismos más claros para demostrar las capacidades de los postulantes.

Paralelamente, el aprendizaje en línea y la obtención de credenciales digitales continúan expandiéndose. Coursera registra 1,7 millones de estudiantes peruanos en su plataforma y reporta un crecimiento interanual del 33% en las inscripciones a Certificados Profesionales en el país (Coursera, 2025). Un certificado de finalización acredita que una persona completó una actividad conforme a los criterios de su emisor; sin embargo, considerado de manera aislada, no necesariamente ofrece una demostración suficiente y verificable de cómo aplica la habilidad en un contexto práctico. En este sentido, los enfoques de contratación basados en habilidades proponen complementar las calificaciones y credenciales con mecanismos que permitan identificar y demostrar competencias específicas (Organisation for Economic Co-operation and Development [OECD], 2024).

A partir de este contexto, el problema identificado es la dificultad que enfrentan los Estudiantes para complementar sus certificados con un proceso que evalúe la aplicación práctica de las habilidades declaradas. La dispersión de certificados, proyectos y resultados agrava el seguimiento, pero no constituye la causa principal: el vacío central es la falta de una comprobación directa del desempeño y de criterios claros para determinar el dominio. Sin esa evaluación, el propio Estudiante puede desconocer qué aspectos necesita reforzar hasta enfrentarse a una tarea aplicada. Asimismo, los Verificadores necesitan un entorno estructurado para revisar entregables y registrar sus contribuciones, mientras que la plataforma requiere mecanismos para supervisar la confiabilidad de esas decisiones.

Esta situación dificulta que los Estudiantes reconozcan sus brechas antes de aplicar una habilidad y respalden sus credenciales con pruebas de desempeño comparables. También impide que terceros comprendan el proceso seguido para determinar el dominio. La oportunidad consiste, por tanto, en complementar la formación existente con un proceso de validación que articule credenciales, evaluaciones aplicadas, revisiones humanas y decisiones documentadas.

El contexto tecnológico favorece el planteamiento de una solución móvil: el 95,4% de los hogares peruanos cuenta con telefonía móvil, mientras que el 37,8% dispone de una computadora; además, el 89,0% de los usuarios de internet accede al servicio mediante un teléfono celular (Instituto Nacional de Estadística e Informática [INEI], 2025). Estas cifras respaldan la elección del canal móvil para acercar el proceso de validación a los segmentos objetivo.

Para analizar los antecedentes y delimitar la problemática, se aplica la técnica de las **5W y 2H**: *What*, *Why*, *Who*, *When*, *Where*, *How* y *How much*. Esta técnica permite identificar el problema, sus causas, los actores involucrados, las circunstancias en las que se manifiesta, su alcance y sus principales efectos.

#### What (¿Qué? / ¿Cuál?)
* **¿Cuál es el problema?** Los Estudiantes que obtienen certificados de finalización no siempre cuentan con un proceso complementario que les permita comprobar, mediante una tarea aplicada y un resultado verificable, que pueden utilizar las habilidades declaradas.
* **¿Qué alternativas existen actualmente?** Las plataformas de educación en línea permiten adquirir conocimientos y obtener credenciales; los portafolios permiten exhibir proyectos; y las redes profesionales permiten comunicar logros. En las alternativas analizadas, estos mecanismos no se articulan en un mismo proceso que relacione una credencial externa con una evaluación práctica, una eventual revisión por un par habilitado y la supervisión de la confiabilidad de la decisión.
* **¿Qué efectos produce el problema?** El Estudiante puede desconocer qué aspectos necesita reforzar hasta enfrentarse a una tarea real y debe complementar su credencial con demostraciones preparadas bajo criterios diversos. Por ello, un tercero no siempre puede reconstruir cómo se determinó el dominio de la habilidad. A su vez, la labor del Verificador puede quedar sin un registro que respalde su experiencia y la plataforma puede carecer de indicadores para supervisar la calidad de las decisiones.

#### Why (¿Por qué?)
* **¿Por qué ocurre el problema?** Una credencial de finalización registra el cumplimiento de los criterios definidos por su emisor. Cuando estos criterios se limitan a completar contenidos o aprobar una evaluación estandarizada centrada en reconocer o recordar información, no se observa el desempeño de la persona ante una tarea aplicada a un caso real. Por ello, relacionar mejor los documentos existentes no resuelve por sí solo la insuficiencia: es necesario comprobar la aplicación de la habilidad mediante criterios explícitos y dejar constancia de la decisión.

#### Who (¿Quién?)
* **¿Quiénes son los principales afectados?** Los Estudiantes universitarios y jóvenes profesionales que necesitan demostrar las habilidades adquiridas mediante cursos, certificaciones, proyectos o aprendizaje autónomo.
* **¿Qué otros actores están involucrados?** También intervienen los Verificadores con experiencia suficiente para revisar los entregables de sus pares, cuya calidad debe ser supervisada para sostener la confiabilidad del proceso.

#### When (¿Cuándo?)
* **¿Cuándo se manifiesta el problema?** Se hace visible después de obtener una credencial, al postular a prácticas o empleos y cuando el Estudiante necesita demostrar la aplicación de una habilidad ante una tarea o proyecto concreto.
* **¿Cuándo vuelve a presentarse?** Puede repetirse cada vez que el Estudiante incorpora una nueva habilidad o presenta una credencial ante un contexto que exige evidencia adicional de aplicación práctica.

#### Where (¿Dónde?)
* **¿En qué ámbitos se manifiesta?** En la educación universitaria, las plataformas de aprendizaje en línea, los procesos de formación autónoma y las etapas de incorporación al mercado laboral.
* **¿Dónde se produce la desconexión?** En la transición entre el espacio que emite la credencial y el contexto donde el Estudiante debe demostrar que puede aplicar la habilidad adquirida.

#### How (¿Cómo?)
* **¿Cómo se manifiesta actualmente?** El Estudiante puede presentar el certificado, sus proyectos y los resultados de evaluaciones previas, pero estos elementos no siempre comparten criterios ni permiten reconstruir mediante un registro verificable cómo se comprobó el dominio. En consecuencia, cada receptor debe interpretarlos por separado y el Estudiante carece de retroalimentación precisa sobre los aspectos que necesita reforzar.
* **¿Cómo puede abordarse?** Mediante una experiencia móvil que relacione las credenciales con pruebas aplicadas a la habilidad y, cuando sea necesario, con revisiones realizadas por Verificadores habilitados mediante rúbricas estructuradas y sujetas a una moderación posterior.

#### How much (¿Cuánto?)
* **¿Qué magnitud tiene la brecha de habilidades en el Perú?** El 47% de las empresas con vacantes tuvo dificultades para cubrirlas y el 76% de las vacantes difíciles de cubrir se relacionó con la falta de habilidades de los candidatos (Novella et al., 2019). Estas cifras dimensionan la necesidad de hacer visibles y comprobables las capacidades de los postulantes.
* **¿Qué alcance tiene el aprendizaje en línea entre usuarios peruanos?** En Coursera se registran 1,7 millones de estudiantes peruanos, equivalentes al 7% de la fuerza laboral del país, y un crecimiento interanual del 33% en las inscripciones a Certificados Profesionales (Coursera, 2025).
* **¿Qué alcance tiene la inadecuación ocupacional?** Rivas Cossio (2023) reporta una tasa de inadecuación ocupacional del 68,6% entre los jóvenes profesionales analizados en Lima Metropolitana, lo que evidencia dificultades de correspondencia entre formación y empleo dentro de esa población.
* **¿Qué importancia tiene la brecha para las organizaciones?** A nivel global, el 63% de los empleadores identifica las brechas de habilidades como una de las principales barreras para transformar sus negocios durante el periodo 2025-2030 (World Economic Forum, 2025).

#### Objetivo de la solución

Desarrollar una plataforma móvil que permita a Estudiantes universitarios y jóvenes profesionales complementar sus certificados con pruebas aplicadas, revisiones calificadas mediante rúbrica y una demostración final, todas provistas de un registro auditable, para demostrar el dominio práctico de sus habilidades. Asimismo, la solución organizará el proceso mediante rutas de certificación, reconocerá la participación de los Verificadores y ofrecerá mecanismos de apelación y de seguimiento de la confiabilidad que permitan moderar el desempeño de los Verificadores.

#### Restricciones del alcance

* SkillSwap complementa la formación obtenida en universidades, plataformas educativas y otros medios; no reemplaza esas fuentes ni imparte cursos o tutorías.
* La plataforma evalúa entregables dentro de su propio proceso, pero no garantiza la contratación laboral del Estudiante ni sustituye los procedimientos de selección de las organizaciones.
* La extracción de datos mediante OCR facilita el registro y el análisis de riesgo documental, pero no equivale a una comprobación oficial ante la entidad emisora; la plataforma no consulta registros externos de las entidades emisoras.
* La confiabilidad de la revisión entre pares depende de la disponibilidad de Verificadores previamente habilitados para cada habilidad.
* La inteligencia artificial generativa se utiliza como apoyo para producir contenido evaluativo, pero los resultados del proceso deben mantenerse sujetos a las reglas de validación y supervisión de la plataforma.
* El desarrollo se limita a las funcionalidades e integraciones seleccionadas para el periodo académico.

---
### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de la formación en línea y la certificación de habilidades en el Perú se ha enfocado principalmente en facilitar que estudiantes universitarios y jóvenes profesionales completen actividades formativas y obtengan credenciales emitidas por distintas instituciones y plataformas. La expansión de este flujo se refleja en el crecimiento de las inscripciones a Certificados Profesionales entre los usuarios peruanos de Coursera (Coursera, 2025), mientras que las dificultades para encontrar las habilidades requeridas en los postulantes evidencian una brecha persistente en el mercado laboral peruano (Novella et al., 2019). Esta situación afecta a los actores del proyecto de la siguiente manera:

* **Personas que quieren aprender — Estudiante:** necesita comprobar cómo aplica la habilidad adquirida, identificar los aspectos que debe reforzar y respaldar sus certificados mediante resultados verificables.
* **Personas que validan el conocimiento — Verificador:** necesita criterios estructurados para revisar los entregables de otros Estudiantes y un registro que reconozca la experiencia adquirida mediante esas revisiones.

Lo que los productos y servicios analizados no logran resolver de manera integrada es la validación práctica complementaria de una credencial previamente obtenida. Un certificado de finalización informa que una persona cumplió los criterios de su emisor, pero no necesariamente muestra cómo se desempeña ante un caso concreto. Las alternativas analizadas atienden por separado el aprendizaje, la presentación de proyectos o la comunicación de logros; la brecha consiste en articular la credencial con una prueba aplicada, una eventual revisión humana estructurada y la supervisión de la confiabilidad de la decisión. Esta necesidad es coherente con los enfoques basados en habilidades, que proponen complementar las calificaciones y credenciales con demostraciones de competencias específicas (OECD, 2024).

Nuestro producto abordará esta brecha mediante una experiencia móvil en la que el Estudiante definirá un objetivo y seguirá una ruta de certificación relacionada con las habilidades requeridas, que incluirá un mínimo de nodos con entrega práctica. El reconocimiento óptico de caracteres facilitará el registro y análisis documental de los certificados, mientras que la inteligencia artificial generativa apoyará la creación de evaluaciones adaptadas a cada habilidad. Cuando la evaluación automática no resulte suficiente, el caso se asignará a un Verificador habilitado que revisará el trabajo guiándose por una rúbrica y registrará su decisión con observaciones, de modo que, si no lo aprueba, el Estudiante sepa qué debe reforzar. Al completar la ruta, una demostración final asíncrona, también calificada por un Verificador, garantizará que ninguna certificación se emita sin revisión humana. A su vez, el Estudiante podrá apelar una vez la decisión que considere incorrecta: un Verificador distinto revisará de nuevo el caso y, si la decisión se revierte, la confiabilidad del Verificador original disminuirá, de modo que las revisiones deficientes se detecten a tiempo.

Nuestro foco inicial serán las personas que quieren aprender: Estudiantes universitarios y jóvenes profesionales de 18 a 30 años de Lima Metropolitana que utilizan recursos de formación en línea y necesitan presentar demostraciones prácticas con un registro verificable al incorporarse al mercado laboral.

Sabremos que tendremos éxito cuando, durante la validación del producto, al menos el 70% de los Estudiantes que registre un certificado complete la evaluación práctica asociada, al menos el 85% de los casos escalados por Estudiantes del plan mensual sea resuelto por un Verificador en un plazo máximo de 48 horas y menos del 3% de las decisiones emitidas por los Verificadores sea posteriormente revertido en la moderación.

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

* Creemos que existe un mercado de Estudiantes universitarios y jóvenes profesionales dispuesto a pagar una suscripción por complementar sus credenciales con un proceso de validación práctica.
* Creemos que la suscripción mensual de los Estudiantes puede sostener el modelo B2C como única fuente de ingresos, sin comisiones entre usuarios ni venta de SkillCredits.
* Creemos que el reconocimiento obtenido mediante SkillCredits y un historial de revisiones será suficiente para atraer y mantener Verificadores activos sin ofrecerles una retribución monetaria directa.
* Creemos que la evaluación automática resolverá una proporción suficiente de intentos para mantener sostenible la carga de revisión humana conforme aumente el número de Estudiantes.
* Creemos que el equipo cuenta con las capacidades técnicas para integrar extracción de datos mediante OCR e inteligencia artificial generativa dentro de una aplicación móvil.
* Creemos que los Estudiantes elegirán SkillSwap frente a alternativas centradas únicamente en formación, exhibición de credenciales o portafolios, porque integra evaluación aplicada, revisión por Verificadores habilitados y moderación de la calidad de esas revisiones en un mismo proceso.

##### Business Outcome Assumptions

* Creemos que la adopción será sostenible cuando la tasa de renovación mensual de la suscripción se mantenga por encima del 80%.
* Creemos que el modelo será rentable cuando el valor del ciclo de vida del Estudiante (LTV) supere el costo de adquisición de clientes (CAC) en una relación de 3 a 1.
* Creemos que la incorporación de credenciales será fluida cuando al menos el 85% de los Estudiantes que inicie la carga de un certificado complete el registro sin abandonarlo.
* Creemos que el proceso generará participación cuando al menos el 70% de los Estudiantes que registre un certificado complete la evaluación práctica asociada.
* Creemos que la operación será escalable cuando menos del 30% de los intentos de evaluación requiera la intervención de un Verificador.
* Creemos que la atención será oportuna cuando al menos el 85% de los casos escalados por Estudiantes del plan mensual sea resuelto por un Verificador en un plazo máximo de 48 horas.
* Creemos que el sistema de reconocimiento será sostenible cuando al menos el 60% de los Verificadores habilitados resuelva un caso durante cada mes de actividad.
* Creemos que la calidad del proceso será confiable cuando menos del 3% de las decisiones emitidas por Verificadores sea revertida en la moderación.
* Creemos que la supervisión será oportuna cuando al menos el 90% de las apelaciones sea resuelto en un plazo máximo de 72 horas.

##### User Assumptions

* Creemos que el usuario principal es un Estudiante universitario o joven profesional de 18 a 30 años de Lima Metropolitana que utiliza recursos de formación en línea y necesita demostrar la aplicación práctica de sus habilidades.
* Creemos que el Verificador es un Estudiante avanzado o joven profesional que ya demostró una habilidad y está dispuesto a revisar entregables de otros usuarios a cambio de reconocimiento profesional.
* Creemos que la confiabilidad del proceso exige moderar el desempeño de los Verificadores, de modo que las revisiones deficientes se detecten y se corrijan antes de afectar la credibilidad de las certificaciones emitidas.
* Creemos que un Estudiante puede convertirse en Verificador para una habilidad específica sin abandonar su participación como aprendiz en otras rutas.

##### User Outcome and Benefit Assumptions

* Creemos que el Estudiante obtiene valor cuando una ruta le muestra qué habilidades debe demostrar para alcanzar el objetivo declarado.
* Creemos que el Estudiante reduce esfuerzo y errores cuando puede incorporar un certificado sin transcribir manualmente todos sus datos.
* Creemos que el Estudiante obtiene valor cuando una evaluación aplicada le permite comprobar su desempeño e identificar los aspectos que debe reforzar.
* Creemos que el Estudiante confía más en una revisión cuando el Verificador ha demostrado previamente la misma habilidad en su propia ruta.
* Creemos que el futuro Verificador obtiene valor cuando puede acreditar formalmente que está habilitado para revisar una habilidad específica.
* Creemos que el Estudiante obtiene valor cuando recibe una revisión pertinente y oportuna si la evaluación automática no resulta suficiente.
* Creemos que el Estudiante obtiene valor cuando puede apelar la decisión que considere incorrecta y ve reflejadas las decisiones revertidas en la confiabilidad del Verificador.
* Creemos que el Verificador obtiene valor al construir una reputación comprobable mediante SkillCredits y un historial de casos resueltos.

##### Feature Assumptions

* Creemos que una ruta de certificación estructurada a partir del objetivo del Estudiante y de una taxonomía de habilidades ordenará las capacidades que debe demostrar.
* Creemos que la extracción mediante OCR recuperará los campos requeridos en al menos el 90% de los certificados cargados, reducirá el esfuerzo de registro y producirá un historial documental auditable.
* Creemos que los *quizzes* y miniproyectos adaptados a cada habilidad, con contenido evaluativo apoyado por inteligencia artificial generativa, permitirán observar el desempeño del Estudiante.
* Creemos que habilitar al Verificador solo cuando completa el nodo de una habilidad en su propia ruta permitirá habilitarlo únicamente para las habilidades que haya demostrado.
* Creemos que la asignación automática basada en la habilidad requerida, el historial y la disponibilidad reducirá el tiempo necesario para obtener una revisión pertinente.
* Creemos que los SkillCredits y el historial de casos resueltos mantendrán activo al Verificador sin necesidad de un pago directo.
* Creemos que permitir al Estudiante apelar la decisión que considere incorrecta hará visible el desempeño de cada Verificador dentro de la aplicación y sostendrá la calidad de las revisiones.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1: Ruta estructurada por objetivo y taxonomía de habilidades**

Creemos que alcanzaremos una tasa de renovación mensual superior al 80%<br>
si los Estudiantes universitarios y jóvenes profesionales de 18 a 30 años<br>
logran reconocer qué habilidades deben demostrar para alcanzar su objetivo<br>
mediante una ruta de certificación estructurada a partir del objetivo declarado y de una taxonomía de habilidades.

**Hipótesis 2: Registro asistido del certificado mediante OCR**

Creemos que lograremos que al menos el 85% de los Estudiantes que inicie la carga de un certificado complete el registro sin abandonarlo<br>
si los Estudiantes que incorporan una credencial externa<br>
logran reducir el esfuerzo y los errores asociados con el registro manual<br>
mediante la extracción de datos del certificado con OCR.

**Hipótesis 3: Evaluación aplicada a la habilidad**

Creemos que lograremos que menos del 30% de los intentos de evaluación requiera la intervención de un Verificador<br>
si los Estudiantes que necesitan demostrar una habilidad<br>
logran comprobar su desempeño e identificar los aspectos que deben reforzar<br>
mediante *quizzes* y miniproyectos adaptados a la habilidad, con contenido evaluativo apoyado por inteligencia artificial generativa.

**Hipótesis 4: Habilitación del Verificador**

Creemos que lograremos que menos del 3% de las decisiones de los Verificadores sea revertida en la moderación<br>
si los Estudiantes que aspiran a actuar como Verificadores<br>
logran acreditar formalmente que están preparados para revisar una habilidad específica<br>
mediante la habilitación del Verificador solo al completar el nodo de esa habilidad en su propia ruta.

**Hipótesis 5: Asignación automática de Verificador**

Creemos que lograremos que al menos el 85% de los casos escalados por Estudiantes del plan mensual sea resuelto en un plazo máximo de 48 horas<br>
si los Estudiantes cuya evaluación automática no resulte suficiente<br>
logran recibir una revisión pertinente y oportuna<br>
mediante la asignación automática basada en la habilidad requerida, el historial y la disponibilidad de los Verificadores.

**Hipótesis 6: SkillCredits e historial de revisiones**

Creemos que lograremos que al menos el 60% de los Verificadores habilitados resuelva un caso durante cada mes de actividad sin recibir un pago directo<br>
si los Verificadores<br>
logran construir una reputación comprobable por sus contribuciones<br>
mediante SkillCredits y un historial de casos resueltos.

**Hipótesis 7: Apelación de la decisión**

Creemos que lograremos que al menos el 90% de las apelaciones sea resuelto en un plazo máximo de 72 horas<br>
si los Estudiantes que reciben una revisión<br>
logran apelar la decisión que consideren incorrecta<br>
mediante una apelación que revisa un Verificador distinto y que se refleja en la confiabilidad del Verificador original.

#### 1.2.2.4. Lean UX Canvas

**Figura 5**

*Lean UX Canvas (v2)*

<p align="center">
  <img src="public/assets/images-doc/lean-ux-canvas.png" alt="Lean UX Canvas de Innovify" width="700">
</p>

*Nota.* En esta figura se presenta el Lean UX Canvas elaborado por el equipo, donde se relacionan el problema de negocio, los resultados comerciales esperados, los segmentos de usuarios, los beneficios que estos obtienen, las soluciones propuestas, las hipótesis formuladas y los experimentos definidos para validarlas. Elaboración propia.

---

## 1.3. Segmentos objetivo

### 1. Segmento: Personas que quieren aprender

Este segmento reúne a las personas que siguen una ruta de certificación en la plataforma y necesitan demostrar la aplicación práctica de las habilidades declaradas.

**Estudiante (aprendizaje y demostración de la habilidad)**

El foco inicial comprende a Estudiantes universitarios y jóvenes profesionales de 18 a 30 años de Lima Metropolitana que utilizan recursos de formación en línea. Este rango constituye una delimitación estratégica del proyecto y no pretende representar la edad de todas las personas que estudian mediante plataformas digitales. El segmento busca complementar sus credenciales con pruebas aplicadas, reconocer los aspectos que necesita reforzar y comunicar sus capacidades al incorporarse al mercado laboral.

La disposición a pagar una **suscripción mensual** por este proceso constituye un supuesto comercial que deberá validarse. La propuesta plantea ofrecer rutas relacionadas con el objetivo del Estudiante, *quizzes* o miniproyectos adaptados a cada habilidad y una revisión puntual cuando la evaluación automática no resulte suficiente.

Como referencia sobre el alcance de la formación digital, Coursera reporta 1,7 millones de usuarios registrados en el Perú, equivalentes al 7% de la fuerza laboral del país. Dentro de esa plataforma, los usuarios peruanos presentan una mediana de edad de 33 años, el 37% estudia desde un dispositivo móvil y las inscripciones a Certificados Profesionales crecieron 33% en un año (Coursera, 2025). Estas cifras corresponden al conjunto de usuarios peruanos de Coursera y permiten dimensionar un mercado relacionado, pero no representan de manera exacta el segmento de 18 a 30 años definido por el proyecto.

Asimismo, Rivas Cossio (2023) reporta una tasa de inadecuación ocupacional del 68,6% entre los jóvenes profesionales analizados en Lima Metropolitana. El indicador evidencia dificultades de correspondencia entre formación y empleo en la población estudiada, sin reducir el fenómeno únicamente a trabajar en un campo distinto del estudiado.

### 2. Segmento: Personas que validan el conocimiento

Este segmento agrupa a las personas que sostienen la confiabilidad de las habilidades verificadas dentro de la plataforma: estudiantes que ya certificaron una habilidad, revisan casos puntuales de otros y supervisan que ese proceso de verificación se mantenga riguroso. En la plataforma este segmento corresponde a un único rol, el Verificador. A diferencia del segmento de aprendizaje, aquí el problema compartido no es "cómo demuestro lo que sé" sino "cómo garantizo que lo que otro demuestra es real" — hoy no existe una forma confiable de comprobar que alguien realmente domina una habilidad que dice tener, y quienes están en posición de validarlo (por experiencia propia o por rol institucional) tampoco cuentan con las herramientas para hacerlo de forma estructurada.

Para comenzar a verificar, la persona primero deberá completar su propia *ruta de certificaciones*, en la cual tendrá que demostrar —mediante certificados validados y evaluaciones aprobadas por la IA— que posee los conocimientos necesarios sobre la habilidad que desea verificar en otros. Una vez habilitada, podrá participar en la *revisión de casos de verificación puntuales*, evaluando el proyecto o portafolio que el estudiante presenta como evidencia frente a una rúbrica estructurada. Por cada caso revisado y resuelto, obtiene *SkillCredits*, un sistema de reconocimiento interno de la plataforma —no monetario y no adquirible— que representa su experiencia y participación, y que también sirve para *demostrar profesionalmente su experiencia* (ej. publicación en LinkedIn).

Junto con esta labor de revisión caso por caso, el Verificador también necesita visibilidad y control a nivel de sistema: garantizar que las decisiones tomadas por los Verificadores sean confiables, resolver disputas cuando un certificado resulta sospechoso, revisar de nuevo un caso cuando un estudiante apela una decisión, y acceder a métricas agregadas de la plataforma —qué habilidades tienen mayor demanda, qué certificaciones son más frecuentes, qué áreas presentan mayor tasa de fallo— que solo tienen valor si el propio proceso de verificación detrás es confiable. Cuando un estudiante apela la decisión de un Verificador, un Verificador distinto del que tomó la decisión original revisa de nuevo el caso, protegiendo la integridad de todo lo que un estudiante certifica en la plataforma.

En conjunto, este segmento es el que sostiene la credibilidad del ecosistema completo: el Verificador la sostiene tanto caso por caso como a nivel de sistema, con un mismo objetivo — que una habilidad verificada en SkillSwap realmente signifique algo.

---

# Capítulo II: Requirements Development and Software Solution Design
 
## 2.1. Competidores

Innovify opera en el ecosistema de plataformas que orientan el aprendizaje de habilidades mediante rutas (roadmaps) y evaluaciones de nivel. SkillSwap no enseña contenido: organiza en una ruta de certificación los certificados que el estudiante obtiene en cualquier plataforma externa y comprueba su avance con evaluaciones generadas por IA y, cuando hace falta, con la revisión de Verificadores. A continuación se identifican los principales competidores directos e indirectos:

**roadmap.sh (Competidor Directo)**
roadmap.sh es la plataforma de roadmaps para desarrolladores más conocida a nivel mundial: su repositorio figura entre los proyectos con más estrellas de GitHub y reporta más de 3 millones de usuarios registrados (roadmap.sh, s. f.-a). Ofrece rutas visuales por rol y tecnología (frontend, backend, DevOps, IA, entre otras) en las que el usuario marca su progreso tema por tema y, desde fines de 2025, integra un AI Tutor que genera cursos y quizzes personalizados; el plan gratuito limita los quizzes y el plan Pro cuesta alrededor de US$ 8 al mes (roadmap.sh, s. f.-b). Su diferencia con SkillSwap es que los roadmaps son generales y no consideran los certificados que el estudiante ya obtuvo en otras plataformas, las evaluaciones son solo automáticas, sin revisión humana, y no cuenta con una aplicación móvil nativa. Además, se limita a roles de tecnología.

**Pluralsight (Competidor Directo)**
Pluralsight es una plataforma de aprendizaje tecnológico que combina rutas de aprendizaje (Paths) con evaluaciones de nivel. Su Skill IQ es un test adaptativo de 10 a 15 minutos y unas 25 preguntas que mide el dominio de una tecnología e indica en qué parte de la ruta debe comenzar el usuario, mientras que Role IQ mide el nivel frente a un rol completo y genera una ruta para cerrar las brechas (Pluralsight, s. f.). Es la propuesta más cercana a la lógica de SkillSwap de ubicar al estudiante en su ruta mediante un test. Su diferencia es que solo evalúa sobre su propio catálogo de cursos, no organiza certificados de otras plataformas, no tiene revisión humana de entregables y está orientada principalmente a empresas, con suscripciones individuales de alrededor de US$ 30 a US$ 55 al mes.

**Platzi (Competidor Directo)**
Platzi es la mayor plataforma de educación en línea creada en Latinoamérica, con más de 4 millones de estudiantes registrados. Organiza su oferta en escuelas y rutas de aprendizaje ordenadas, y cada curso y cada ruta tienen un examen: el examen final de un curso exige al menos 90 % para obtener el certificado, y el examen de la ruta otorga el certificado de la ruta (Platzi, s. f.). Es el competidor más cercano en mercado y público, porque se dirige a estudiantes y jóvenes profesionales de la región, en español. Su diferencia con SkillSwap es que solo certifica su propio contenido, no reconoce certificados de otras plataformas como Coursera o edX, sus exámenes son de opción múltiple sin revisión humana y su modelo exige pagar una suscripción anual para acceder a las rutas y sus certificados.

**Kritik (Competidor Indirecto)**
Kritik es una plataforma de evaluación entre pares con rúbrica estructurada usada dentro de instituciones educativas. Los estudiantes envían un trabajo, lo evalúan entre sí con criterios definidos y reciben retroalimentación anónima. Su diferencia con SkillSwap es que Kritik opera dentro del entorno académico formal — es una herramienta de evaluación en clase, no una plataforma de validación de habilidades para el mercado laboral. No verifica que quien evalúa domine lo que está revisando, no emite credenciales exportables a LinkedIn y no tiene un mecanismo de supervisión que garantice la confiabilidad del proceso.

---

### 2.1.1. Análisis competitivo

**Tabla 2**

*Análisis competitivo Landscape*

| Criterio de Análisis | **Innovify / SkillSwap** | **roadmap.sh** | **Pluralsight** | **Platzi** |
| :--- | :--- | :--- | :--- | :--- |
| **Overview** | Aplicación móvil que guía al estudiante con una ruta de certificación construida según su meta a partir de una taxonomía de habilidades, con apoyo de IA para interpretar esa meta, organiza en ella los certificados que obtiene en cualquier plataforma y comprueba su avance con evaluaciones y revisión de Verificadores. | Plataforma web de roadmaps para roles de tecnología, con seguimiento de progreso por tema y un AI Tutor que genera cursos y quizzes. | Plataforma de cursos de tecnología con rutas de aprendizaje (Paths) y evaluaciones de nivel (Skill IQ y Role IQ). | Plataforma latinoamericana de cursos en línea organizada en escuelas y rutas de aprendizaje, con exámenes y certificados propios. |
| **¿Guía el orden de aprendizaje (roadmap)?** | Sí. Ruta personalizada a partir de la meta declarada en lenguaje natural, que la IA interpreta seleccionando habilidades de la taxonomía de la plataforma, con nodos ordenados por prerrequisitos. | Sí. Roadmaps predefinidos por rol o tecnología; el AI Tutor puede generar cursos personalizados. | Sí. Paths predefinidos por tecnología y rutas por rol según el resultado de Role IQ. | Sí. Rutas de aprendizaje predefinidas dentro de cada escuela. |
| **¿Evalúa el nivel o el avance?** | Sí. Quiz o miniproyecto por nodo de la ruta, con diagnóstico por sub-tema y revisión de un Verificador si no aprueba. | Parcialmente. Quizzes generados por IA, limitados en el plan gratuito y sin efecto sobre la ruta. | Sí. Skill IQ (test adaptativo de unas 25 preguntas) ubica al usuario en la ruta; Role IQ mide el nivel frente a un rol. | Sí. Examen final por curso (mínimo 90 %) y examen por ruta para obtener el certificado. |
| **¿Reconoce certificados de otras plataformas?** | Sí. Registra certificados de Coursera, edX, Platzi u otras fuentes y los relaciona con los nodos de la ruta. | No. El progreso se marca manualmente sobre sus propios roadmaps. | No. Solo considera sus propios cursos y evaluaciones. | No. Solo certifica su propio contenido. |
| **¿Quién revisa?** | IA en la evaluación automática y un Verificador habilitado cuando el estudiante no aprueba. | Sistema automático (IA). Sin revisión humana. | Sistema automático. Sin revisión humana de entregables. | Sistema automático. Sin revisión humana. |
| **Mercado objetivo** | Estudiantes universitarios y jóvenes profesionales de 18 a 30 años de Lima Metropolitana que quieren saber qué aprender y demostrar su avance. | Desarrolladores y estudiantes de tecnología a nivel mundial. | Empresas que capacitan a sus equipos técnicos y profesionales de tecnología a nivel individual. | Estudiantes y profesionales de Latinoamérica, además de empresas mediante Platzi Business. |
| **Modelo de negocio y precios** | Freemium B2C: plan gratuito con 1 ruta activa, hasta 3 rutas en total y 3 escalamientos al mes, y suscripción mensual de S/ 29,90 (IGV incluido) mediante Google Play Billing, integrado con RevenueCat, con hasta 3 rutas activas, sin tope de rutas en total y 10 escalamientos al mes. SkillCredits no monetarios para los Verificadores. | Freemium. Roadmaps gratuitos y plan Pro de alrededor de US$ 8 al mes con quizzes ilimitados. | Suscripción individual de alrededor de US$ 30 a US$ 55 al mes y planes para empresas. | Suscripción con planes Basic y Expert (anual), con precios por país, y plan para empresas. |
| **Canales de distribución** | Aplicación móvil nativa (Android) y multiplataforma (Flutter), y Landing Page web. | Sitio web y comunidad en GitHub y Discord. | Sitio web y aplicaciones móviles. | Sitio web y aplicaciones móviles. |
| **Fortalezas (SWOT)** | Ruta personalizada que aprovecha los certificados que el estudiante ya tiene. Evaluación por nodo con diagnóstico por sub-tema. Revisión humana de Verificadores cuando la IA no basta. Experiencia móvil. | Gran comunidad y reconocimiento entre desarrolladores. Roadmaps gratuitos y actualizados por la comunidad. Bajo precio del plan Pro. | Evaluación de nivel madura y probada (Skill IQ). Amplio catálogo de cursos y relación con empresas. | Marca muy reconocida en Latinoamérica. Contenido en español. Rutas y certificados propios. |
| **Debilidades (SWOT)** | Marca nueva. Requiere una masa crítica inicial de Verificadores. No tiene contenido propio. | Solo cubre roles de tecnología. Evaluaciones sin revisión humana. No reconoce certificados externos. | Precio alto para estudiantes. Enfoque empresarial. No reconoce certificados externos. | Solo valida su propio contenido. Exámenes de opción múltiple. Suscripción anual para acceder a rutas y certificados. |
| **Oportunidades (SWOT)** | Estudiantes que acumulan certificados de varias plataformas sin un orden claro. Alianzas con universidades peruanas. | Integrar progreso con certificados externos o evaluaciones más rigurosas. | Ampliar su oferta a estudiantes con planes más accesibles. | Agregar evaluaciones prácticas y reconocimiento de aprendizaje externo. |
| **Amenazas (SWOT)** | Que roadmap.sh, Pluralsight o Platzi incorporen el reconocimiento de certificados externos o la revisión humana. | Plataformas que combinen roadmap con evaluación verificable. | Plataformas gratuitas o más económicas con evaluaciones de nivel. | Plataformas que organicen el aprendizaje de varias fuentes en una sola ruta. |

*Nota.* SkillSwap es la única propuesta que organiza en una ruta personalizada los certificados de cualquier plataforma y comprueba el avance con evaluaciones por nodo y revisión humana. Elaboración propia.

---

### 2.1.2. Estrategias y tácticas frente a competidores

A continuación se presentan las estrategias y tácticas que Innovify implementa para diferenciarse de las plataformas que orientan el aprendizaje mediante rutas y evaluaciones de nivel.

#### Estrategias

* **Una sola ruta para certificados de cualquier plataforma:** roadmap.sh, Pluralsight y Platzi guían el aprendizaje solo sobre sus propios roadmaps o cursos. SkillSwap parte de la meta del estudiante y organiza en una única ruta los certificados que ya obtuvo o que obtendrá en Coursera, edX, Platzi u otras fuentes, de modo que no tenga que empezar de cero ni adivinar qué estudiar a continuación.

* **Evaluación que ubica al estudiante en su ruta:** Pluralsight demuestra el valor de ubicar al usuario con un test de nivel, y Platzi y roadmap.sh evalúan con exámenes o quizzes automáticos. SkillSwap evalúa cada nodo de la ruta con un quiz o miniproyecto generado por IA, indica el sub-tema exacto que debe reforzar y, cuando la evaluación automática no basta, deriva el caso a un Verificador que ya demostró esa habilidad.

* **Habilitación por habilidad demostrada como garantía de calidad:** Ningún competidor verifica que quien revisa realmente sepa lo que evalúa. SkillSwap reduce ese riesgo exigiendo que todo Verificador complete en su propia ruta el nodo de la habilidad que revisará antes de poder revisar casos de otros. Eso crea un ecosistema de calidad garantizada que ningún competidor puede replicar sin cambiar radicalmente su modelo.

* **SkillCredits como incentivo único para el Verificador:** Ninguno de los competidores identificados ofrece un mecanismo de reconocimiento profesional verificable para quien revisa el trabajo de otros. Los SkillCredits son exportables a LinkedIn y acreditan experiencia de revisión técnica real — una credencial de liderazgo que los empleadores valoran y que actualmente no existe en el mercado.

* **Supervisión de Verificadores senior como capa de confianza:** roadmap.sh, Pluralsight y Platzi no tienen una capa de supervisión que resuelva disputas, revise certificados sospechosos ni acceda a métricas reales del proceso. En SkillSwap esa supervisión la ejercen los Verificadores senior, que alcanzaron el rango Oro (100 casos resueltos o más) y mantienen una confiabilidad de 90 o más, en una escala de 0 a 100, lo que hace que las credenciales de SkillSwap sean confiables no solo para el estudiante y el Verificador, sino también para empleadores e instituciones académicas.

#### Tácticas

* **Programa de Verificadores Fundadores:** Los primeros 100 Verificadores certificados reciben un badge exclusivo y mayor acumulación de SkillCredits por caso resuelto, para construir la masa crítica inicial que hace funcionar la plataforma.

* **Campaña "Ya aprendiste, ahora demuéstralo":** Dirigida a estudiantes que ya tienen certificados de otras plataformas pero sienten que no tienen peso real ante empleadores. El mensaje es claro: SkillSwap no te pide que vuelvas a aprender — te pide que demuestres lo que ya sabes.

* **Alianzas con universidades:** Acercarse a universidades peruanas para que promuevan SkillSwap entre sus estudiantes y reconozcan a sus Verificadores, dándole respaldo institucional al proceso y generando confianza en empleadores sobre la credibilidad de las certificaciones emitidas.

* **Plan gratuito como puerta de entrada:** Todo estudiante empieza en el plan gratuito, con el que puede declarar su meta, seguir su ruta, rendir evaluaciones y escalar casos a un Verificador dentro de los límites del plan (1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes), de modo que experimenta el modelo completo antes de decidir si pasa a la suscripción mensual. Esto reduce la barrera de entrada frente a Pluralsight y Platzi, que exigen una suscripción para acceder a sus rutas y certificados.
---
 
## 2.2. Entrevistas
 
### 2.2.1. Diseño de entrevistas
 
**Segmento objetivo #1: Personas que quieren aprender (Estudiantes)**
 
1. Para empezar, cuéntame sobre ti: ¿qué estudias o en qué trabajas, cuántos años tienes y en qué etapa de tu vida profesional te encuentras?
2. ¿Cómo describirías tu relación actual con el aprendizaje de nuevas habilidades? ¿Aprendes de forma autodidacta, con cursos online o de otra manera?
3. ¿Has tomado cursos online y obtenido certificados? Si es así, ¿cómo te has sentido con esos certificados al momento de buscar trabajo o prácticas?
4. Cuéntame de alguna vez que sentiste que tenías un certificado pero en realidad no dominabas del todo la habilidad. ¿Cómo fue esa situación?
5. Cuando te estancas en un tema específico que estás aprendiendo, ¿qué haces? ¿A quién o qué recurres para resolver ese bloqueo?
6. ¿Alguna vez has sentido inseguridad al aplicar algo que "aprendiste" en un curso cuando lo necesitabas en la práctica real? ¿Puedes contarme sobre eso?
7. Si existiera una plataforma que, además de darte un certificado, te exigiera demostrar que realmente dominas la habilidad mediante un quiz o un miniproyecto evaluado por un Verificador certificado, ¿cómo te parecería ese modelo?
8. ¿Qué tan dispuesto estarías a pagar una suscripción mensual por acceso a una ruta de aprendizaje personalizada por IA, con evaluaciones prácticas y la posibilidad de conectarte con un Verificador cuando te bloqueas?
9. ¿Qué necesitarías ver en el perfil de un Verificador para confiar en que realmente sabe lo que evalúa?
10. ¿Qué opinas de un sistema donde el Verificador también tuvo que demostrar su dominio antes de poder revisar a otros en la plataforma? ¿Eso te generaría más confianza?
11. Si al completar una ruta de certificación pudieras obtener una credencial verificable que muestra exactamente qué habilidades demostraste (no solo que tomaste un curso), ¿crees que eso tendría más peso ante un empleador?
12. ¿Qué herramientas digitales usas actualmente para aprender? ¿Qué es lo que más te frustra de ellas?
13. Imagina que puedes subir un certificado externo (de Coursera, por ejemplo) y la plataforma te genera un miniproyecto para validar que realmente adquiriste esa habilidad. ¿Eso te parecería valioso o innecesario?
14. ¿Preferirías recibir una revisión de un Verificador que sea experto exactamente en el sub-tema donde fallaste, en vez de tener que repasar todo el curso desde cero?

**Segmento objetivo #2: Personas que validan el conocimiento**

1. Para comenzar, cuéntame sobre ti: ¿qué estudias, en qué trabajas, o cuál es tu rol dentro de una institución universitaria? ¿En qué áreas tienes dominio sólido o qué responsabilidades tienes relacionadas con el aprendizaje de otros?
2. ¿Has ayudado, evaluado o supervisado de forma informal el aprendizaje de otras personas? ¿Cómo fue esa experiencia y qué te motivó a hacerlo?
3. ¿Cuáles son las principales frustraciones que has tenido al intentar validar que alguien realmente domina lo que dice saber?
4. ¿Estarías dispuesto a demostrar previamente, mediante tu propia ruta de certificación, que realmente dominas la habilidad antes de poder revisar a otros en la plataforma? ¿Qué te parecería ese modelo?
5. Si por cada caso resuelto acumularas SkillCredits que certifican tu nivel y puedes exhibirlos en LinkedIn como credencial verificable, ¿eso te motivaría más que recibir una compensación económica directa?
6. ¿Qué tan importante es para ti que la persona que revisas o supervisas haya demostrado un nivel mínimo previo de conocimiento? ¿Por qué?
7. ¿Qué herramientas usas actualmente cuando validas o supervisas el aprendizaje de alguien a distancia? ¿Qué limitaciones encuentras?
8. ¿Te molestaría que la plataforma te asigne automáticamente el caso más adecuado para ti según tu especialidad y el error específico detectado, en vez de elegir tú directamente a quién ayudar?
9. ¿Qué información necesitarías saber sobre el caso antes de revisarlo, para hacer tu evaluación más efectiva?
10. Si la plataforma te informara exactamente en qué pregunta o concepto falló la persona en su evaluación automática, ¿eso te ayudaría a revisar el caso de forma más quirúrgica y efectiva?
11. ¿Cómo te sentirías respecto a recibir un reconocimiento (SkillCredits) por cada caso resuelto y validado, en vez de un pago económico directo?
12. ¿Qué debería tener sí o sí una plataforma para que la consideres profesional y confiable para ejercer este rol?
13. Si pudieras exhibir en tu perfil de LinkedIn una credencial que dice "Verificador certificado en [habilidad], con X casos resueltos", ¿crees que eso tendría valor real para tu carrera profesional?
14. Más allá de resolver casos puntuales, ¿qué características o políticas debería tener una herramienta de este tipo para que confíes en que el proceso de verificación en general es riguroso, no solo caso por caso?
15. ¿Cuál es tu principal preocupación respecto a la legitimidad de certificados obtenidos en plataformas externas (Coursera, Udemy, etc.)?
16. Si detectaras que un certificado presentado por un estudiante es sospechoso o que la decisión de otro Verificador amerita revisión, ¿qué dificultades anticipas para resolver ese tipo de disputa dentro de tu día a día?
17. ¿Qué riesgos te preocuparían más en un sistema donde estudiantes de otras instituciones revisan o son revisados por otros usuarios de la plataforma?
18. Actualmente, ¿qué tan simple o complejo es verificar si un certificado o una decisión de revisión previa es legítima?
19. Imaginemos que le damos acceso a un panel de supervisión. Para que tu labor de validación fuera eficiente y segura, ¿qué funciones serían indispensables? (ej. historial de casos resueltos, indicadores de confiabilidad, historial de disputas, un solo clic para resolver, etc.).
20. Más allá de resolver casos y disputas puntuales, ¿qué otro tipo de información o control te gustaría tener para asegurar que la validación de conocimientos en la plataforma es, en conjunto, rigurosa y confiable?

---
 
### 2.2.2. Registro de entrevistas
 
#### Segmento objetivo #1: Personas que quieren aprender
 
Somos el equipo Innovify de la UPC y estamos desarrollando SkillSwap, una plataforma que valida habilidades prácticas mediante rutas de aprendizaje generadas por IA y revisión de casos por Verificadores certificados. Para este segmento entrevistamos a estudiantes universitarios y egresados recientes que buscan aprender y demostrar competencias reales ante el mercado laboral, con el objetivo de identificar sus principales frustraciones, hábitos de aprendizaje y percepción sobre un sistema de validación supervisado por pares certificados.
 
**Entrevista 1**
* **Nombres:** Mireya
* **Apellidos:** Perales Rodríguez
* **Edad:** 21 años
* **Distrito:** San Miguel

**Figura 6**

*Entrevista 1: Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s1-e1.png" alt="Entrevista Mireya" width="600">
</p>

*Nota.* En esta figura se aprecia la primera entrevista al segmento de personas que quieren aprender.

**URL:** https://www.youtube.com/watch?v=TdVTVb2Cj1s<br>**Inicio:** 0:00<br>**Duración:** 6:28 minutos
 
**Resumen descriptivo:**
En esta entrevista, Mireya estudia Ingeniería de Gestión Empresarial en la UPC y se encuentra en quinto ciclo. Recientemente consiguió sus primeras prácticas profesionales en el área de gestión en una empresa de consumo masivo. Describe su proceso de preparación como bastante autodidacta y de prueba y error: actualizó su CV múltiples veces usando plantillas de Canva, comparó con los de compañeras que ya habían practicado, y se preparó para entrevistas viendo videos de YouTube. Sin embargo, reconoce que siempre sintió que le faltaba alguien que le dijera si lo estaba haciendo bien.
 
Cuando tuvo la suerte de que una prima con experiencia laboral le revisara el CV por WhatsApp, notó la diferencia inmediatamente: le señaló que estaba incluyendo información poco relevante y que debía resaltar resultados concretos. Mireya destaca que avanzó rápido con esa ayuda, pero reconoce que fue suerte que su prima tuviera tiempo esa semana. Su mayor dificultad es no saber a quién más pedirle ese tipo de orientación, ya que sus compañeros de clase están en la misma situación que ella.
 
Respecto al uso de herramientas digitales, usa Canva para el diseño del CV, ChatGPT para redactar mejor sus experiencias y LinkedIn para buscar ofertas y contactar reclutadores, aunque casi nunca recibe respuesta. Considera que la IA funciona bien como primer filtro antes de llegar a una persona, pero no reemplaza la orientación personalizada.
 
Sobre el perfil del Verificador, Mireya es muy clara: prioriza que tenga experiencia real en su área — en qué empresa trabajó, cuánto tiempo lleva en el rubro y si estudió algo similar a su carrera — por encima de la cantidad de reseñas. Respecto al modelo de Innovify, valora especialmente la posibilidad de que la plataforma asigne automáticamente un mentor con conocimiento específico de su carrera, porque considera que buscar ayuda por su cuenta es lento y no siempre aplica a su situación. Está dispuesta a dar una donación voluntaria por la sesión si esta es realmente útil. Finalmente, prefiere que la videollamada esté integrada dentro de la misma plataforma, porque los links externos de Zoom se pierden en el chat y reducen el compromiso de ambas partes.

*Nota sobre esta entrevista.* La entrevista se realizó con la primera versión de la idea de negocio, basada en mentorías por videollamada y donaciones voluntarias. Por eso Mireya menciona un "mentor", la "donación" y la "videollamada". El modelo actual de SkillSwap reemplazó esas mentorías por la revisión de un Verificador con rúbrica y por la suscripción mensual. Aun así, sus respuestas se mantienen como evidencia, porque confirman dos necesidades que el modelo actual sí atiende: que una persona con experiencia real valide lo que el estudiante sabe y que la plataforma asigne automáticamente a esa persona según el área del estudiante.

**Entrevista 2**
* **Nombres:** Mathias
* **Apellidos:** Véliz
* **Edad:** 24 años
* **Distrito:** Cayma, Arequipa

**Figura 7**

*Entrevista 2: Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s1-e2.png" alt="Entrevista Mathias" width="600">
</p>

*Nota.* En esta figura se aprecia la segunda entrevista al segmento de personas que quieren aprender.

**URL:** https://www.youtube.com/watch?v=xt02A76wXNQ<br>**Inicio:** 0:00<br>**Duración:** 7:58 minutos
 
**Resumen descriptivo:**
Mathias es egresado de Administración de la Universidad Nacional de San Agustín de Arequipa y lleva ocho meses buscando empleo en marketing digital. Cuenta con tres certificados de Google Digital Garage, uno de HubSpot y un curso de Meta Ads completado en Udemy, pero en todas las entrevistas en las que ha participado le dicen que "le falta experiencia práctica". Describe esa situación como profundamente frustrante: siente que invirtió tiempo y dinero en aprender pero no puede demostrarlo de forma creíble ante nadie.
 
Cuando se estanca aprendiendo un tema nuevo, Mathias recurre a foros como Reddit y grupos de Facebook de marketing digital, aunque reconoce que los consejos que recibe son muy genéricos y a menudo no aplican a su situación específica. Ha intentado contactar a profesionales en LinkedIn pero rara vez recibe respuesta.
 
Respecto al modelo de Innovify, Mathias lo ve como la solución directa a su problema principal: no quiere más teoría ni más certificados estándar, quiere que alguien con experiencia real confirme que lo que sabe es suficiente. Le parece especialmente valioso el sistema de quizzes y miniproyectos evaluados por Verificadores certificados, porque eso le daría una credencial con peso real ante empleadores. Mathias está dispuesto a pagar una suscripción mensual y considera que exigir a los Verificadores demostrar primero su propio dominio es un diferencial clave que lo haría confiar en la plataforma.
 
**Entrevista 3**
* **Nombres:** Carlos
* **Apellidos:** Rojas Valverde
* **Edad:** 19 años
* **Distrito:** Miraflores

**Figura 8**

*Entrevista 3: Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s1-e3.png" alt="Entrevista Carlos" width="600">
</p>

*Nota.* En esta figura se aprecia la tercera entrevista al segmento de personas que quieren aprender.

**URL:** https://www.youtube.com/watch?v=wcjn0ionQ-8<br>**Inicio:** 0:00<br>**Duración:** 6:53 minutos
 
**Resumen descriptivo:**
Carlos estudia Diseño Gráfico en Toulouse Lautrec y se encuentra en tercer ciclo. Aprendió Figma de manera autodidacta viendo tutoriales en YouTube y practicando por su cuenta, y siente que tiene un nivel intermedio-avanzado en la herramienta. Sin embargo, cuando busca trabajos freelance o postula a prácticas, no tiene ninguna credencial formal que avale ese conocimiento — los cursos gratuitos de YouTube no emiten certificados y los certificados de plataformas pagadas son genéricos.
 
Su mayor frustración es no tener una ruta clara: no sabe exactamente qué debería aprender primero, en qué orden, y cómo saber cuándo ya domina suficientemente una habilidad para poder cobrar por ella. Usa Figma, Adobe Illustrator y Photoshop de forma cotidiana, pero se siente inseguro cuando tiene que describir su nivel de dominio a un cliente o empleador potencial.
 
Respecto al modelo de Innovify, Carlos valora especialmente la idea de la ruta de aprendizaje generada por IA: quiere que alguien le diga exactamente qué aprender, en qué orden, y cómo demostrar que lo dominó. Le parece muy útil la posibilidad de subir un certificado externo y que la plataforma le genere un miniproyecto para validarlo, porque eso le daría credibilidad real a lo que ya aprendió por su cuenta. Carlos está dispuesto a hacer quizzes y miniproyectos si al final obtiene una credencial verificable con peso ante clientes y empleadores. Lo que más valora del perfil del Verificador es que tenga proyectos reales en su portafolio, no solo títulos o años de experiencia.
 
---
 
#### Segmento objetivo #2: Personas que validan el conocimiento

**Entrevista 1**
* **Nombres:** Rodrigo
* **Apellidos:** Castillo Vega
* **Edad:** 26 años
* **Distrito:** San Isidro

**Figura 9**

*Entrevista 1: Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s2-e1.png" alt="Entrevista Rodrigo" width="600">
</p>

*Nota.* En esta figura se aprecia la primera entrevista al segmento de personas que validan el conocimiento.

* **URL:** [https://www.youtube.com/watch?v=n53WUVagpE4](https://www.youtube.com/watch?v=n53WUVagpE4)
* **Inicio:** 0:00
* **Duración:** 7:52

**Resumen descriptivo:**
Rodrigo estudia Ingeniería de Software en la PUCP y está en séptimo ciclo. Domina React, Node.js, PostgreSQL y arquitectura de microservicios, conocimientos que desarrolló combinando su formación universitaria con proyectos freelance y contribuciones a repositorios open source. Ha ayudado informalmente a varios compañeros de ciclos menores a resolver dudas puntuales de programación, pero siempre de forma desorganizada — por WhatsApp, sin estructura, sin que la persona llegue con un nivel mínimo establecido.

Su principal frustración al ayudar a otros es que llegan sin los fundamentos necesarios para aprovechar la revisión, lo que hace que pierda tiempo explicando conceptos básicos que debería dar por sabidos. También le molesta la falta de reconocimiento formal: dedica tiempo de calidad a revisar el trabajo de otros pero nadie lo sabe ni puede verificarlo.

Respecto al modelo de Innovify, Rodrigo está muy de acuerdo con que quien valida deba haber certificado previamente su propia ruta, porque considera que es la única forma de garantizar que quien revisa realmente sabe. Le parece especialmente atractivo el sistema de SkillCredits, porque le permitiría demostrar en LinkedIn no solo que sabe programar sino que sabe evaluar a otros. Le parece eficiente que la plataforma le informe exactamente en qué pregunta o concepto falló el estudiante en su evaluación automática antes de asignarle el caso, porque eso le permite emitir una revisión quirúrgica en vez de repasar todo el proyecto desde cero.

**Entrevista 2**
* **Nombres:** Lucía
* **Apellidos:** Vargas Flores
* **Edad:** 28 años
* **Distrito:** Surco

**Figura 10**

*Entrevista 2: Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s2-e2.png" alt="Entrevista Lucía" width="600">
</p>

*Nota.* En esta figura se aprecia la segunda entrevista al segmento de personas que validan el conocimiento.

* **URL:** [https://www.youtube.com/watch?v=h8Uh3w6U1qE](https://www.youtube.com/watch?v=h8Uh3w6U1qE)
* **Inicio:** 0:00
* **Duración:** 5:29

**Resumen descriptivo:**
Lucía es egresada de Contabilidad de la Universidad de Lima y trabaja hace dos años en una firma de auditoría. Domina Excel avanzado, Power BI y análisis financiero, habilidades que desarrolló en su trabajo y que sabe que son muy demandadas en el mercado. Ha ayudado informalmente a compañeros universitarios con estas herramientas, pero el modelo le resulta poco profesional y difícil de gestionar: tiene que coordinar por WhatsApp, no hay estructura, y las personas a veces no vienen preparadas.

Lo que más valora de Innovify es la posibilidad de que su participación sea reconocida de forma estructurada y profesional, sin tener que gestionar ella misma la logística. Sin embargo, lo que más la motiva es el sistema de SkillCredits: considera que demostrar que sabe evaluar Excel avanzado y Power BI a otros, con resultados verificables, es una credencial de liderazgo y comunicación que le abre puertas en su carrera profesional.

Está de acuerdo con que quien valida demuestre primero su propio dominio antes de revisar a otros, aunque reconoce que inicialmente puede parecer una barrera alta. Considera que esa barrera es precisamente lo que garantiza que los estudiantes reciban una revisión de calidad real.

**Entrevista 3**
* **Nombres:** Sebastián
* **Apellidos:** Mora Chávez
* **Edad:** 23 años
* **Distrito:** Barranco

**Figura 11**

*Entrevista 3: Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entrevista-s2-e3.png" alt="Entrevista Sebastián" width="600">
</p>

*Nota.* En esta figura se aprecia la tercera entrevista al segmento de personas que validan el conocimiento.

* **URL:** [https://www.youtube.com/watch?v=wtCs-bESKhI](https://www.youtube.com/watch?v=wtCs-bESKhI)
* **Inicio:** 0:00
* **Duración:** 7:07

**Resumen descriptivo:**
Sebastián es egresado de Comunicaciones de la UPC y trabaja como freelance en marketing de contenidos. Domina SEO técnico, copywriting y estrategia de redes sociales, habilidades que desarrolló en proyectos reales con clientes. Intentó enseñar en Preply pero lo abandonó porque la plataforma permite que cualquiera enseñe sin verificación, lo que deteriora la calidad percibida de todos los que ofrecen ayuda ahí.

Su principal motivación no es el dinero sino construir reputación profesional verificable. Sebastián entiende que en el mundo del marketing digital, el portafolio y las credenciales son todo, y actualmente no tiene ninguna forma de acreditar que sabe evaluar el trabajo de otros con criterio.

Respecto al modelo de Innovify, valora especialmente que la plataforma exija que quien valida haya certificado su propia ruta antes de revisar a otros, porque eso eleva la calidad del ecosistema completo y hace que pertenecer a él sea una credencial en sí misma. Le parece muy atractivo el sistema de SkillCredits y su integración con LinkedIn. También valora la asignación automática de casos, porque prefiere que le lleguen estudiantes cuyo vacío específico coincide con su área de mayor dominio, en vez de recibir cualquier solicitud genérica de marketing.

**Entrevista 4**
* **Nombres:** Armando
* **Apellidos:** Novoa
* **Edad:** 49 años
* **Distrito:** San Miguel

**Figura 12**

*Entrevista 4 Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entre-rafa.png" alt="Entrevista Armando" width="600">
</p>

*Nota.* En esta figura se aprecia la cuarta persona entrevistada del segmento de personas que validan el conocimiento.

* **URL:** [https://youtu.be/YDpJ_S8Ik2g](https://youtu.be/YDpJ_S8Ik2g)
* **Inicio:** 0:00
* **Duración:** 13 minutos con 54 segundos

**Resumen descriptivo:**
Esta entrevista fue realizada a un docente de Cálculo 2 de la Universidad Peruana de Ciencias Aplicadas (UPC). De acuerdo con lo conversado, el profesor considera que la propuesta es una muy buena idea y la percibe como fundamental para el desarrollo profesional de los estudiantes. Destaca la importancia de que los alumnos puedan validar sus conocimientos y demostrar habilidades reales, incluso frente a estudiantes de otras universidades, con el fin de adaptarse a un mercado laboral cada vez más exigente.

Asimismo, mostró cautela en sus declaraciones para no vulnerar su contrato con la universidad, pero enfatizó que las plataformas tecnológicas tienen un gran potencial siempre que se utilicen bajo un marco de ética y respeto a las normas institucionales. Señaló que la educación en valores debe prevalecer sobre la simple restricción del uso de la tecnología.

Finalmente, evidenció interés en la funcionalidad operativa de la propuesta, sugiriendo que la validación y el acceso a la información se gestionen por niveles académicos, con el objetivo de asegurar que el contenido sea adecuado y pertinente para cada etapa del estudiante.

**Entrevista 5**
* **Nombres:** Jesús
* **Apellidos:** Hernández
* **Edad:** 29 años
* **Distrito:** Cercado de Lima

**Figura 13**

*Entrevista 5 Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entrevista-victor3-1.png" alt="Entrevista Jesús" width="600">
</p>

*Nota.* En esta figura se aprecia la quinta persona entrevistada del segmento de personas que validan el conocimiento.

* **URL Parte 1:** [https://youtu.be/oRoAbwVAjxI](https://youtu.be/oRoAbwVAjxI) | **Inicio:** 0:00 | **Duración:** 10m 12s
* **URL Parte 2:** [https://youtu.be/tWd_sJHLAak](https://youtu.be/tWd_sJHLAak) | **Inicio:** 0:00 | **Duración:** 11m 50s

**Resumen descriptivo:**
Jesús Hernández, jefe de prácticas, señala que los principales desafíos de los alumnos son la gestión del tiempo, el acceso a información confiable y la dificultad en el trabajo en equipo. Sobre una plataforma interuniversitaria de validación de habilidades, considera esencial la verificación de alumnos, políticas claras de integridad académica y un sistema de trazabilidad. Destacó que la universidad se preocupa por evitar plagio, fraude académico y certificados falsos. Advirtió que la implementación de una plataforma con validación manual podría generar carga laboral y costos, sugiriendo procesos automatizados como reconocimiento facial. Propuso que el panel de supervisión permita buscar y resolver casos fácilmente, acceder al historial de un revisor y monitorear la confiabilidad de sus decisiones para asegurar una participación segura.

**Entrevista 6**
* **Nombres:** Raúl
* **Apellidos:** Pardo
* **Edad:** 34 años
* **Distrito:** San Borja

**Figura 14**

*Entrevista 6 Segmento Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/entrevista-david1.png" alt="Entrevista Raúl" width="600">
</p>

*Nota.* En esta figura se aprecia la sexta persona entrevistada del segmento de personas que validan el conocimiento.

* **URL:** [https://youtu.be/cP_YiYr2VD8](https://youtu.be/cP_YiYr2VD8)
* **Inicio:** 0:00
* **Duración:** 10 minutos con 40 segundos

**Resumen descriptivo:**
El profesor Raúl Pardo, docente en la Universidad de Lima, considera una muy buena idea y parte fundamental del desarrollo académico que los estudiantes validen mutuamente sus conocimientos. Destacó que las herramientas tecnológicas son productivas para este fin siempre que se les dé un buen uso, priorizando el aprendizaje sobre ventajas deshonestas. También mostró cierta preocupación por la carga que representa para un revisor validar casos constantemente, ya que siente que podría impactar negativamente en su propio tiempo y productividad, especialmente en estudiantes con muchas responsabilidades académicas.
 
---
 
### 2.2.3. Análisis de entrevistas

#### Segmento objetivo #1: Personas que quieren aprender

**1. Características objetivas**
* **Edad:** Estudiantes universitarios o egresados recientes, generalmente entre 19 y 24 años (100%).
* **Carrera:** Diversas carreras universitarias (Ingeniería de Sistemas, Administración, Diseño Gráfico) (100%).
* **Etapa:** Desde tercer ciclo hasta egresados recientes buscando su primera práctica o empleo (100%).
* **Experiencia con plataformas:**
  * Uso de plataformas de cursos online (Coursera, Udemy, YouTube) (100%).
  * Uso de herramientas de IA como ChatGPT para resolver dudas (100%).
  * Poca o nula experiencia con validación práctica supervisada por pares certificados (100%).

**2. Características subjetivas**
* **Frustración con los certificados actuales:**
  * Sienten que los certificados online no reflejan su dominio práctico real (100%).
  * Han enfrentado situaciones donde no pudieron aplicar lo que "aprendieron" en entrevistas técnicas o proyectos reales (100%).
  * No saben con certeza si están aprendiendo bien o solo memorizando (66%).
* **Dificultades para conseguir ayuda específica:**
  * No saben a quién recurrir cuando se bloquean en un sub-tema específico (100%).
  * Los recursos actuales (foros, ChatGPT) dan respuestas genéricas que no aplican a su situación exacta (66%).
  * Sus pares están en la misma situación y no pueden darles orientación de nivel superior (33%).
* **Valoración del modelo de validación práctica:**
  * Están dispuestos a pagar una suscripción mensual si garantiza evaluaciones prácticas y Verificadores certificados (100%).
  * Prefieren una credencial que muestre qué habilidades demostraron sobre un certificado estándar (100%).
  * Valoran que los Verificadores demuestren su propio dominio antes de revisar a otros como garantía de calidad (100%).
* **Preferencias sobre el Verificador:**
  * Priorizan que el Verificador tenga experiencia real en su área (proyectos, empresas) sobre la cantidad de casos resueltos (100%).
  * Prefieren una revisión enfocada en el sub-tema donde fallaron, no repetir el curso completo (100%).
  * Valoran ver portafolio de proyectos reales del Verificador antes de que les sea asignado (66%).

&nbsp;

**Tabla 3**

*Principales hallazgos de entrevistas a personas que quieren aprender*

| Característica | % Entrevistados | Fuente / Frase de entrevista |
| :--- | :--- | :--- |
| Frustración por brecha certificado vs. dominio real | 100% | "Tenía el certificado pero en la entrevista técnica me bloqueé." |
| Disposición a pagar suscripción mensual | 100% | "Pagaría si eso me garantiza Verificadores reales y evaluaciones prácticas." |
| Preferencia por credencial verificable sobre certificado estándar | 100% | "Eso tendría más peso ante un empleador que un PDF de Coursera." |
| Valoración de la habilitación previa de los Verificadores | 100% | "Eso me daría confianza de que realmente sabe lo que evalúa." |
| Preferencia por revisión quirúrgica (sub-tema específico) | 100% | "No quiero repasar todo el curso, solo donde fallé." |
| Uso de ChatGPT como apoyo de aprendizaje | 100% | "Lo uso para resolver dudas, pero no sé si la respuesta está bien." |
| Prioriza experiencia real del Verificador sobre cantidad de casos | 100% | "Prefiero que haya trabajado en mi área aunque tenga menos casos resueltos." |
| Necesidad de ruta estructurada de aprendizaje | 66% | "Quiero que alguien me diga qué aprender, en qué orden." |
| Inseguridad al aplicar lo aprendido en práctica real | 66% | "Aprendí Python pero no sé si lo que hago está bien o funciona de casualidad." |

*Nota.* Elaboración propia.

---

#### Segmento objetivo #2: Personas que validan el conocimiento

**1. Características objetivas**
* **Perfil:** El segmento agrupa dos tipos de persona dentro de un mismo rol de validación: estudiantes avanzados o egresados recientes que revisan casos puntuales de otros (Rodrigo, Lucía, Sebastián — 23 a 28 años), y profesionales académicos que supervisan la integridad del proceso (Armando, Jesús, Raúl — 29 a 53 años, docentes, coordinadores o jefes de práctica en universidades).
* **Experiencia previa:** El 100% tiene experiencia relacionada con validar, ayudar o supervisar el aprendizaje de otros de forma informal o institucional, aunque sin herramientas estructuradas para hacerlo.
* **Relación con tecnología:** Todos usan herramientas digitales de forma habitual (WhatsApp, Zoom, Drive, sistemas de control académico), pero ninguno cuenta con una plataforma dedicada a validar conocimiento de forma rigurosa.

**2. Características subjetivas**
* **Motivaciones para validar:**
  * Reconocimiento profesional verificable (SkillCredits en LinkedIn) como incentivo principal para quienes revisan casos puntuales (100%).
  * Garantizar la integridad académica y la calidad del ecosistema como motivación principal para quienes supervisan a nivel de sistema (100%).
  * El dinero es secundario frente al reconocimiento y la confiabilidad, en ambos tipos de perfil (100%).
* **Frustraciones con el modelo actual:**
  * Falta de estructura y reconocimiento formal al validar o ayudar a otros de forma informal (100%).
  * Recibir personas o casos sin el nivel mínimo necesario, haciendo la revisión ineficiente (66% — Rodrigo, Sebastián).
  * Preocupación por el fraude, la suplantación y los certificados falsos (100% — Armando, Jesús, Raúl).
  * Carga operativa de procesos de validación manual sin automatización (67% — Jesús, Raúl).
* **Valoración del modelo de Innovify:**
  * De acuerdo con que quien valida certifique previamente su propia ruta como garantía de calidad (100%).
  * Valoran recibir información precisa sobre el error específico antes de asignarles el caso (100% — Rodrigo, Lucía, Sebastián).
  * Consideran esencial la verificación de identidad, políticas claras y trazabilidad de las decisiones (100% — Armando, Jesús, Raúl).
  * Valoran un panel que permita resolver casos y disputas de forma centralizada, con historial de confiabilidad visible (100%).

**Tabla 4**

*Principales hallazgos de entrevistas al segmento de personas que validan el conocimiento*

| Característica | % Entrevistados | Fuente / Frase de entrevista |
| :--- | :--- | :--- |
| Motivación principal: reconocimiento profesional (SkillCredits) | 50% (3/6) | "Lo que más me atrae es poder demostrar en LinkedIn que sé enseñar, no solo que sé hacer." |
| Motivación económica como secundaria | 50% (3/6) | "Las comisiones están bien, pero no es mi principal motivación." |
| Acuerdo con la certificación previa exigida a quien valida | 50% (3/6) | "Eso es lo que le da valor al ecosistema, que no cualquiera puede entrar." |
| Frustración por personas/casos sin nivel mínimo | 33% (2/6) | "Pierdo tiempo explicando fundamentos que deberían ya saber." |
| Valoración de información previa sobre el error detectado | 50% (3/6) | "Si sé en qué falló puedo preparar algo quirúrgico, no repasar todo." |
| Preocupación por fraude, plagio o suplantación | 50% (3/6) | "La universidad se preocupa por evitar plagio, fraude académico y certificados falsos." |
| Validación de identidad como requisito crítico | 50% (3/6) | "Es esencial la verificación de alumnos y un sistema de trazabilidad." |
| Necesidad de automatizar la validación manual | 33% (2/6) | "La implementación con validación manual podría generar carga laboral y costos." |
| Preferencia por panel centralizado de resolución de casos/disputas | 100% (6/6) | "El panel debería permitir buscar y resolver casos fácilmente, con historial de confiabilidad." |
| Interés en supervisar proyectos avanzados o casos de mayor complejidad | 33% (2/6) | "Me interesaría supervisar proyectos finales, no solo revisiones puntuales." |

*Nota.* La tabla sintetiza las motivaciones, frustraciones y necesidades expresadas por las 6 personas entrevistadas en este segmento. Las citas se conservan tal como fueron registradas durante la entrevista original. Elaboración propia.

---
 
## 2.3. Needfinding
 
Para el proceso de needfinding se realizaron entrevistas a los dos segmentos principales de usuarios identificados: personas que quieren aprender (Estudiantes) y personas que validan el conocimiento (Verificadores). El objetivo principal fue indagar en las motivaciones, frustraciones y necesidades de todos los perfiles en relación con la validación práctica de habilidades y el reconocimiento profesional.
 
### 2.3.1. User Personas
 
Los User Personas fueron construidos a partir de los patrones identificados en las entrevistas realizadas a los segmentos objetivo. Cada arquetipo refleja las características demográficas, motivaciones, frustraciones y objetivos más representativos de su segmento, sirviendo como referencia central para las decisiones de diseño y desarrollo de la plataforma. Se presenta una ficha de User Persona por cada segmento objetivo: Valeria Ramos para las personas que quieren aprender y Rodrigo Castillo para las personas que validan el conocimiento, que en la plataforma corresponden al rol de Verificador.
 
**Segmento 1 — Personas que quieren aprender**
 
**Figura 15**

*User Persona - Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/user1-app.png" alt="User Persona Estudiante" width="800">
</p>

*Nota.* Elaboración propia.

El arquetipo de Valeria Ramos representa al segmento de estudiantes: estudiante universitaria de 22 años, con certificados online que no puede convertir en evidencia creíble de dominio práctico ante el mercado laboral. Sus objetivos son demostrar habilidades reales ante empleadores, seguir una ruta de aprendizaje estructurada por IA y recibir una revisión puntual de un Verificador cuando la evaluación automática no logra confirmar su dominio. Sus principales frustraciones son la brecha entre el certificado y el dominio real, no saber si está aprendiendo correctamente, y la dificultad de encontrar una forma confiable de validar sus conocimientos en áreas específicas.
 
**Segmento 2 — Personas que validan el conocimiento**

**Figura 16**

*User Persona - Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/user2-app.png" alt="User Persona Verificador" width="800">
</p>

*Nota.* Elaboración propia.

El arquetipo de Rodrigo Castillo representa al segmento de personas que validan el conocimiento: estudiante avanzado de Ingeniería de Software, 26 años, con dominio técnico sólido y experiencia informal ayudando a otros sin reconocimiento formal. Este perfil condensa las dos tareas que el Verificador asume en la plataforma: la revisión de casos puntuales entre pares y la supervisión y control a nivel de sistema, una necesidad que en las entrevistas también expresaron los perfiles académicos entrevistados (docentes y jefes de práctica). Sus objetivos son construir una reputación profesional verificable mediante SkillCredits, obtener casos que encajen con su especialidad mediante la asignación automática de la plataforma, y garantizar que el proceso de verificación completo —no solo su propia revisión— sea riguroso y confiable, resolviendo disputas o certificados sospechosos cuando corresponda. Sus principales frustraciones son la falta de estructura en los modelos informales de validación, recibir casos fuera de su área de dominio, la preocupación por el fraude y los certificados falsos, y la carga operativa de un proceso de verificación que hoy carece de herramientas automatizadas.
<br><br>

**En conjunto**, los arquetipos de usuario presentados permiten comprender de manera clara las necesidades, motivaciones y desafíos de los dos segmentos objetivo de Innovify. El perfil del Estudiante orienta el diseño hacia rutas de aprendizaje estructuradas, evaluaciones prácticas generadas por IA y acceso a una revisión puntual cuando se produce un bloqueo específico. El perfil de Rodrigo, en el segmento que valida el conocimiento, establece los lineamientos necesarios tanto para un sistema de reconocimiento profesional verificable y una asignación automática de casos, como para las herramientas de supervisión, resolución de disputas y monitoreo de confiabilidad que garantizan la integridad del ecosistema completo. En conjunto, estos arquetipos permiten alinear el desarrollo con usuarios reales, asegurando una solución centrada en la experiencia, la eficiencia operativa y el equilibrio entre aprendizaje y verificación.
 
---
 
### 2.3.2. User Task Matrix
 
En el User Task Matrix se consideran los dos segmentos objetivo evaluando sus tareas clave según frecuencia e importancia. Los estudiantes priorizan buscar recursos de aprendizaje, validar su nivel real y obtener una revisión puntual cuando se bloquean. Los Verificadores priorizan mantener su dominio técnico actualizado, construir su reputación profesional y garantizar la integridad del proceso de verificación.
 
#### Segmento objetivo #1: Personas que quieren aprender
 
 
**Tabla 5**

*Tareas y prioridades de las personas que quieren aprender*

| Tasks | Mireya<br>Frecuencia | Mireya<br>Importancia | Mathias<br>Frecuencia | Mathias<br>Importancia | Carlos<br>Frecuencia | Carlos<br>Importancia |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Buscar recursos de aprendizaje en internet | Muy alta | Alta | Muy alta | Alta | Muy alta | Alta |
| Tomar cursos online y obtener certificados | Alta | Alta | Alta | Muy alta | Media | Alta |
| Aplicar lo aprendido en proyectos o ejercicios prácticos | Media | Muy alta | Media | Muy alta | Alta | Muy alta |
| Validar sus conocimientos mediante evaluaciones prácticas | Media | Muy alta | Alta | Muy alta | Media | Alta |
| Prepararse para entrevistas técnicas o portfolios | Media | Muy alta | Alta | Muy alta | Media | Alta |
| Identificar exactamente en qué sub-tema está fallando | Baja | Muy alta | Baja | Muy alta | Baja | Alta |
| Validar que lo que aprendió es suficiente para el mercado | Media | Muy alta | Alta | Muy alta | Media | Muy alta |
 
*Nota.* Elaboración propia.
 
#### Segmento objetivo #2: Personas que validan el conocimiento

**Tabla 6**

*Tareas y prioridades del segmento de personas que validan el conocimiento*

| Tasks | Rodrigo<br>Frec. | Rodrigo<br>Imp. | Lucía<br>Frec. | Lucía<br>Imp. | Sebastián<br>Frec. | Sebastián<br>Imp. | Armando<br>Frec. | Armando<br>Imp. | Jesús<br>Frec. | Jesús<br>Imp. | Raúl<br>Frec. | Raúl<br>Imp. |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Mantener y actualizar el dominio técnico o académico propio | Muy alta | Muy alta | Alta | Muy alta | Muy alta | Muy alta | Media | Alta | Media | Alta | Media | Alta |
| Revisar o evaluar el caso/trabajo de otra persona | Media | Alta | Baja | Alta | Media | Alta | Media | Muy alta | Alta | Muy alta | Media | Alta |
| Construir reputación profesional o institucional verificable | Baja | Muy alta | Media | Muy alta | Alta | Muy alta | Baja | Media | Baja | Media | Baja | Media |
| Obtener reconocimiento (SkillCredits) por la participación | Baja | Alta | Alta | Muy alta | Media | Alta | N/A | N/A | N/A | N/A | N/A | N/A |
| Identificar el vacío específico antes de revisar el caso | Baja | Muy alta | Baja | Alta | Baja | Alta | Baja | Alta | Media | Alta | Baja | Media |
| Verificar la legitimidad de certificados o evidencias | Baja | Media | Baja | Media | Baja | Media | Alta | Muy alta | Alta | Muy alta | Media | Alta |
| Resolver disputas o casos escalados | N/A | N/A | N/A | N/A | N/A | N/A | Media | Alta | Media | Alta | Alta | Alta |
| Acceder a métricas o historial agregado del proceso | Baja | Media | Baja | Media | Baja | Media | Media | Alta | Alta | Alta | Alta | Muy alta |
| Gestionar logística/herramientas para ejercer el rol a distancia | Media | Media | Media | Alta | Media | Media | Media | Alta | Alta | Alta | Alta | Alta |

*Nota.* N/A indica que la tarea no aplica de forma directa al perfil de esa persona entrevistada, reflejando que el segmento agrupa dos dimensiones distintas del rol de validación. Elaboración propia.

---

#### Conclusión

Las tareas más frecuentes e importantes son:

* **Estudiantes:** Buscar recursos de aprendizaje y aplicar lo aprendido en proyectos prácticos son las más frecuentes. Identificar exactamente en qué sub-tema están fallando y validar que lo aprendido es suficiente para el mercado son las más importantes aunque poco frecuentes, porque actualmente no tienen herramientas para hacerlo.
* **Personas que validan el conocimiento:** Mantener el dominio propio y revisar el caso de otra persona son las tareas más transversales al segmento completo. Resolver disputas y verificar la legitimidad de certificados destacan como las de mayor importancia para la supervisión del sistema, mientras que construir reputación y obtener SkillCredits destacan en la revisión de casos puntuales — ambas tareas forman parte del mismo rol de Verificador.

Todos los segmentos coinciden en el uso intensivo de herramientas digitales y en la necesidad de conexión con personas de nivel verificado, aunque cada perfil dentro del segundo segmento lo aplica desde un ángulo distinto de la misma labor de validación.
 
---
 
### 2.3.3. User Journey Mapping
 
En esta sección se presentan los User Journey Maps As-Is de cada User Persona, mostrando el recorrido completo (end-to-end) de los usuarios en la situación actual, sin intervención de la solución de Innovify, lo que incluye procesos, puntos de dolor y oportunidades.

* **Segmento 1: Personas que quieren aprender.** Inicia con la decisión de aprender una habilidad específica, continúa con la búsqueda y toma de cursos online, la obtención de un certificado que no puede convertir en evidencia práctica, el bloqueo en sub-temas específicos sin saber a quién recurrir, y culmina con la frustración de no poder demostrar el dominio real ante empleadores o clientes.

* **Segmento 2: Personas que validan el conocimiento.** Comienza con la motivación de compartir el dominio propio y garantizar la integridad del aprendizaje ajeno, pero enfrenta la falta de estructura en los modelos informales de revisión, la dificultad para llegar a personas con nivel mínimo adecuado y la ausencia de reconocimiento formal por esa labor, al revisar casos puntuales; y la sobrecarga operativa, el riesgo de fraude o certificados falsos, y la dificultad de medir el impacto real de sus esfuerzos, al supervisar el sistema completo. Ambas tareas conviven en un mismo recorrido, el del Verificador: se comparte la falta de herramientas tecnológicas que automaticen y den estructura a la validación del conocimiento.

#### Segmento #1: Personas que quieren aprender
 
**Figura 17**

*User Journey Mapping – Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/jur1-app.png" alt="Journey Map Estudiante" width="800">
</p>

*Nota.* En esta figura se aprecia el Journey Mapping del primer segmento de SkillSwap. Elaboración propia.

En esta figura se observa el recorrido de Valeria a través de cinco etapas críticas: decisión de aprender, búsqueda de recursos, obtención del certificado, bloqueo en la práctica real y búsqueda de validación. El diagrama detalla la curva emocional del arquetipo, identificando puntos de dolor como la incertidumbre sobre si está aprendiendo correctamente, la frustración al no poder demostrar el dominio en situaciones reales y la dificultad para encontrar una forma confiable de validar exactamente el sub-tema donde se bloqueó.
 
#### Segmento #2: Personas que validan el conocimiento

**Figura 18**

*User Journey Mapping – Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/jur2-app.png" alt="Journey Map Verificador" width="800">
</p>

*Nota.* En esta figura se aprecia el Journey Mapping del segundo segmento de SkillSwap. Elaboración propia.

<br>

En esta figura se visualiza la experiencia del segmento que valida el conocimiento, combinando las dos tareas que asume el Verificador. El mapa describe el proceso desde la motivación inicial de compartir el dominio propio o garantizar la calidad académica, pasando por la gestión informal y desorganizada de esa labor —ya sea revisando casos de forma no estructurada o validando manualmente certificados e integridad académica—, la frustración por recibir personas o casos sin nivel mínimo, el riesgo constante de fraude y certificados falsos, hasta la ausencia total de reconocimiento formal, herramientas automatizadas o un panel único que centralice la resolución de casos y disputas.

<br>

**Entonces**, los mapas de experiencia presentados permiten comprender de manera integral cómo interactúan los distintos actores con el ecosistema de aprendizaje y validación de habilidades en la situación actual. Desde la perspectiva del estudiante, el recorrido está marcado por una inversión constante de tiempo y dinero en certificaciones que no generan evidencia creíble de competencia práctica, con bloqueos específicos que no tiene cómo resolver de forma dirigida. Desde el segmento que valida el conocimiento, la experiencia actual combina la desorganización de la revisión informal entre pares con la sobrecarga operativa de la supervisión académica manual, sin que exista hoy ningún mecanismo tecnológico que integre ambas dimensiones de la validación en un solo proceso confiable. En conjunto, estas perspectivas permiten diseñar una experiencia equilibrada, eficiente y segura para todos los participantes del ecosistema.

---
 
### 2.3.4. Empathy Mapping
 
Para profundizar en el entendimiento de los usuarios finales y diseñar una solución que responda a sus necesidades reales, se desarrollaron mapas de empatía para cada segmento identificado. Esta herramienta permite visualizar el entorno, las percepciones y las motivaciones de los actores clave, facilitando la identificación de puntos críticos y oportunidades de valor dentro del ecosistema de Innovify.
 
#### Segmento #1: Personas que quieren aprender
 
**Figura 19**

*Empathy Mapping - Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/Empati1-app.png" alt="Empathy Map Estudiante" width="800">
</p>

*Nota.* En esta figura se aprecia el Empathy Mapping del primer segmento de SkillSwap. Elaboración propia.

Se observa el mapa de empatía de Valeria, arquetipo que representa al segmento de estudiantes. El diagrama detalla su necesidad de demostrar habilidades prácticas reales ante un mercado laboral que exige competencias verificables, no solo certificados. Sus principales puntos de dolor son la ansiedad por no saber si lo que aprendió es suficiente, la frustración de tener certificados que nadie toma en serio y la incapacidad de identificar exactamente en qué sub-tema está fallando para pedir una revisión específica. Sus ganancias esperadas son una credencial verificable con peso real ante empleadores y acceso a un Verificador que resuelva exactamente el bloqueo que tiene, sin tener que repasar todo el curso desde cero.
 
#### Segmento #2: Personas que validan el conocimiento

**Figura 20**

*Empathy Mapping - Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/Empati2-app.png" alt="Empathy Map Verificador" width="800">
</p>

*Nota.* En esta figura se aprecia el Empathy Mapping del segundo segmento de SkillSwap. Elaboración propia.

<br>

En esta figura se detalla el mapa de empatía del segmento que valida el conocimiento, integrando las dos tareas que asume el Verificador: la revisión de casos puntuales entre pares y la supervisión de la integridad del sistema. El análisis subraya el deseo compartido de convertir el dominio propio —técnico o institucional— en un proceso de validación confiable y reconocido. Sus principales puntos de dolor son la falta de un mecanismo formal que acredite la capacidad de quien revisa, la desorganización de los modelos informales actuales, la frustración de recibir personas o casos sin nivel mínimo, y la preocupación constante por el fraude, los certificados falsos y la carga operativa de un proceso sin herramientas automatizadas. Sus ganancias esperadas son pertenecer a un ecosistema riguroso que eleve su estatus profesional o institucional, acumular reconocimiento verificable (SkillCredits e historial de confiabilidad), y contar con un panel centralizado que facilite tanto la revisión de casos puntuales como la resolución de disputas y el monitoreo general del sistema.

<br>

**Entonces**, los mapas de empatía permiten profundizar en las necesidades emocionales, motivaciones y dificultades de los dos segmentos objetivo de Innovify. En el caso del estudiante, se evidencia una motivación fuerte orientada a la empleabilidad y al reconocimiento real de sus capacidades, enfrentando frustraciones relacionadas con la superficialidad del modelo de certificación actual y la dificultad de encontrar una validación específica cuando se bloquea. En el segmento que valida el conocimiento, la motivación del Verificador combina el reconocimiento profesional por revisar casos puntuales con la responsabilidad de supervisar la integridad del sistema, junto con una fuerte preocupación por el fraude, la falta de estructura y la ausencia de herramientas tecnológicas que optimicen y centralicen el proceso de validación. En conjunto, estos mapas evidencian la importancia de diseñar una plataforma equilibrada que atienda tanto aspectos funcionales como emocionales, asegurando confianza, eficiencia y valor para todos los usuarios del ecosistema.

### 2.3.5. As-Is Scenario Mapping

En esta sección se presentan los As-Is Scenario Maps elaborados con la herramienta Miro para cada segmento objetivo, describiendo el recorrido actual del usuario sin la intervención de la solución de Innovify. El objetivo es identificar los puntos de dolor y las oportunidades de mejora en el flujo actual de cada actor.

**Segmento #1: Personas que quieren aprender**

**Figura 21**

*As-Is Scenario Mapping – Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/asis1-app.png" alt="As-Is Scenario Map Estudiante" width="800">
</p>

*Nota.* Elaborado con la herramienta Miro. Elaboración propia.

En el mapa se observa que Valeria comienza identificando una habilidad que quiere dominar, pero sin saber por dónde empezar elige un curso de forma intuitiva. Obtiene el certificado sintiéndose lista, pero cuando intenta aplicarlo en una entrevista real se bloquea y descubre que el certificado no refleja su dominio práctico. Al buscar ayuda solo encuentra respuestas genéricas en foros o ChatGPT que no resuelven su bloqueo específico. El principal punto de dolor es la brecha entre tener el certificado y poder demostrarlo en la práctica real.

&nbsp;

**Segmento #2: Personas que validan el conocimiento**

**Figura 22**

*As-Is Scenario Mapping – Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/asis2-app.png" alt="As-Is Scenario Map Verificador" width="800">
</p>

*Nota.* Elaborado con la herramienta Miro. Elaboración propia.

En el mapa se observa que Rodrigo quiere ayudar a otros con su habilidad pero no encuentra un modelo profesional que lo respalde. Coordina por WhatsApp con personas que llegan sin el nivel mínimo, hace la revisión por Zoom sin ninguna rúbrica ni criterio estructurado, y al terminar no tiene ninguna evidencia formal de lo que hizo. El principal punto de dolor es la ausencia de reconocimiento y estructura: dedica tiempo de calidad a revisar el trabajo de otros pero nadie puede verificarlo.


### 2.3.6. Ubiquitous Language

En esta sección se presenta el lenguaje ubicuo de SkillSwap: los términos del dominio de la validación de habilidades que el equipo y los stakeholders usan con un único significado, tanto en el informe como en el modelo de dominio y en la aplicación. Solo se incluyen términos del negocio, no términos técnicos de ingeniería de software. Cada término se presenta en inglés, con su equivalente en español y su definición.

**Tabla 7**

*Ubiquitous Language de SkillSwap*

| Term | Término (español) | Definición |
| :--- | :--- | :--- |
| Student | Estudiante | Usuario universitario o joven profesional que declara una meta, sigue una ruta de certificación y demuestra sus habilidades en la plataforma. |
| Verifier | Verificador | Estudiante que completó en su propia ruta el nodo de una habilidad; queda habilitado para revisar casos de esa habilidad. La supervisión de la calidad del proceso (resolver las disputas por certificados sospechosos y controlar la confiabilidad de otros Verificadores) corresponde al Verificador senior. |
| Senior Verifier | Verificador senior | Verificador que alcanzó el rango Oro y mantiene una confiabilidad de 90 o más, en la escala de 0 a 100; resuelve las disputas por certificados sospechosos. |
| Visitor | Visitante | Persona que consulta el Landing Page antes de descargar la aplicación o registrarse. |
| Institutional Email | Correo institucional | Correo con dominio universitario (.edu.pe) que se exige para registrarse como Estudiante. |
| Career Goal | Meta profesional | Habilidad u objetivo que el Estudiante describe con sus propias palabras y a partir del cual se construye su ruta. |
| Skill | Habilidad | Capacidad concreta y demostrable (por ejemplo, análisis de datos con pandas) que forma parte del catálogo de la plataforma. |
| Skill Taxonomy | Taxonomía de habilidades | Catálogo organizado de habilidades, con sus prerrequisitos, que se usa para interpretar la meta del Estudiante. Es la fuente de verdad de la ruta: solo se aceptan las habilidades que pertenecen a él. |
| Skill Gap | Brecha de habilidades | Conjunto de habilidades que le faltan demostrar al Estudiante para alcanzar su meta profesional. |
| Learning Path | Ruta de certificación | Secuencia ordenada de nodos que el Estudiante debe completar para demostrar las habilidades de su meta. |
| Paused Learning Path | Ruta pausada | Ruta de certificación que conserva su progreso, pero en la que el Estudiante no puede avanzar. Una ruta queda pausada cuando vence el plan mensual y el Estudiante tenía más rutas activas de las que permite el plan gratuito; vuelve a estar activa si el Estudiante pausa su ruta activa para reactivarla o si se suscribe de nuevo. |
| Path Node | Nodo de la ruta | Paso de la ruta asociado a una habilidad; puede estar bloqueado, disponible o completado. |
| Prerequisite | Prerrequisito | Nodo que debe completarse antes de que otro nodo quede disponible. |
| Certificate | Certificado | Credencial externa (por ejemplo, de Coursera) que el Estudiante registra como evidencia de una habilidad. Un certificado verificado completa el nodo de la habilidad que cubre; uno que solo superó el análisis de riesgo puede vincularse al nodo, pero no lo completa. |
| Document Risk Assessment | Análisis de riesgo documental | Evaluación de un certificado que detecta inconsistencias, como un titular distinto o fechas incoherentes, y determina su nivel de riesgo. |
| Suspicious Certificate | Certificado sospechoso | Certificado con riesgo documental alto que se escala a un Verificador senior, quien lo confirma como verificado o lo rechaza. |
| Duplicate Certificate | Certificado duplicado | Certificado cuyo archivo ya fue registrado antes en la plataforma y que no puede volver a usarse como evidencia. |
| Assessment | Evaluación | Prueba que comprueba el dominio de la habilidad de un nodo; puede ser un quiz o un miniproyecto. |
| Quiz | Quiz | Evaluación de cinco preguntas generada para la habilidad de un nodo, que se aprueba con al menos cuatro respuestas correctas (80%). |
| Mini-project | Miniproyecto | Entrega práctica que el Estudiante desarrolla para demostrar una habilidad de forma aplicada. |
| Assessment Attempt | Intento de evaluación | Cada vez que el Estudiante rinde la evaluación de un nodo, con su puntaje y resultado. |
| Sub-topic | Sub-tema | Parte específica de una habilidad que se usa para indicar al Estudiante qué debe reforzar. |
| Verification Case | Caso de verificación | Revisión que se abre cuando un intento no se aprueba y que se asigna a un Verificador habilitado. |
| Case Type | Tipo de caso | Clasificación de un caso de verificación según la evaluación que lo originó: quiz o miniproyecto. Determina cuántos SkillCredits recibe el Verificador al resolverlo. |
| Rubric | Rúbrica | Conjunto de criterios con los que el Verificador evalúa el trabajo del Estudiante y justifica su decisión. |
| Evidence | Evidencia | Material que respalda un caso, como el intento de evaluación o un enlace a un trabajo del Estudiante. |
| Case Deadline | Plazo del caso | Tiempo máximo que tiene un Verificador para decidir un caso; al vencer, el caso se reasigna. |
| Availability | Disponibilidad | Indicador de que un Verificador acepta recibir casos nuevos de sus habilidades habilitadas. |
| Verifier Reliability | Confiabilidad del Verificador | Indicador de la calidad de las decisiones de un Verificador, calculado a partir de sus casos resueltos y revertidos y expresado en una escala de 0 a 100. |
| Employability Score | Puntaje de empleabilidad | Indicador que resume las habilidades demostradas por un Estudiante dentro de la plataforma. |
| SkillCredits | SkillCredits | Unidades de reconocimiento no monetarias que recibe un Verificador por cada caso resuelto (40 SkillCredits por un miniproyecto y 25 por un quiz, lo apruebe o lo rechace); forman un saldo canjeable por beneficios de la plataforma y nunca se pueden comprar con dinero ni transferir. |
| Wallet | Billetera | Registro del saldo de SkillCredits de un usuario y de sus movimientos. |
| Redemption | Canje | Operación con la que el Verificador descuenta SkillCredits de su saldo a cambio de un beneficio canjeable. |
| Redeemable Benefit | Beneficio canjeable | Beneficio que el Verificador obtiene al canjear SkillCredits: la ruta avanzada (200 SkillCredits), que pone a su disposición una ruta de certificación avanzada, o el certificado de contribución (120 SkillCredits), que acredita su labor como Verificador. |
| Rank | Rango | Nivel visible en el perfil del Verificador que se alcanza según la cantidad de casos de verificación resueltos, no según el saldo de SkillCredits; por eso, canjear créditos no lo reduce. Hay tres rangos: Bronce (0 a 29 casos resueltos), Plata (30 a 99) y Oro (100 o más). |
| Subscription | Suscripción | Plan mensual opcional, de S/ 29,90 con IGV incluido y cobrado mediante Google Play Billing, integrado a través de RevenueCat, que amplía los límites del plan gratuito (1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes, revisados en hasta 5 días hábiles) a hasta 3 rutas activas a la vez, sin tope de rutas en total, y 10 escalamientos al mes, revisados en 48 horas, y reduce los tiempos de espera. |
| Dispute | Disputa | Caso que revisa un Verificador senior y que se abre cuando un certificado se registra como sospechoso. |
| Appeal | Apelación | Solicitud del Estudiante para que un Verificador distinto del original revise de nuevo un caso rechazado. Se permite una apelación por caso y, si la decisión se revierte, se registra en la confiabilidad del Verificador original. |
| Re-evaluation | Reevaluación | Nuevo intento que un Verificador senior habilita cuando existen dudas sobre un resultado. |
| Final Demonstration | Demostración final | Prueba integral que el Estudiante presenta al completar su ruta y que califica un Verificador. |

*Nota.* Elaboración propia.

---

## 2.4. Requirements specification

To-Be Scenario Mapping

En esta sección se presentan los To-Be Scenario Maps elaborados con la herramienta Miro para cada segmento objetivo, describiendo el recorrido ideal del usuario con la solución de Innovify implementada. El objetivo es evidenciar cómo la plataforma transforma cada punto de dolor del As-Is en una experiencia fluida, confiable y motivadora.

**Segmento #1: Personas que quieren aprender**

**Figura 23**

*To-Be Scenario Mapping – Personas que quieren aprender*

<p align="center">
  <img src="public/assets/images-doc/tobe1-app.png" alt="To-Be Scenario Map Estudiante" width="800">
</p>

*Nota.* Elaborado con la herramienta Miro. Elaboración propia.

En el mapa se observa que con Innovify, Valeria se registra con su correo institucional y la plataforma, con apoyo de la IA para interpretar su meta, le propone una ruta de aprendizaje clara desde el inicio. Sube sus certificados, rinde evaluaciones prácticas personalizadas y cuando falla una, un Verificador que ya sabe exactamente en qué punto se bloqueó la revisa de forma quirúrgica. Al completar la ruta obtiene una credencial verificable que muestra exactamente qué habilidades demostró, no solo que tomó un curso, con peso real ante cualquier empleador.

&nbsp;

**Segmento #2: Personas que validan el conocimiento**

**Figura 24**

*To-Be Scenario Mapping – Personas que validan el conocimiento*

<p align="center">
  <img src="public/assets/images-doc/tobe2-app.png" alt="To-Be Scenario Map Verificador" width="800">
</p>

*Nota.* Elaborado con la herramienta Miro. Elaboración propia.

En el mapa se observa que con Innovify, Rodrigo primero completa en su propia ruta el nodo de la habilidad que revisará, lo que garantiza que quien revisa realmente sabe. Recibe casos asignados automáticamente con información precisa del punto donde falló el estudiante, los revisa frente a una rúbrica estructurada y acumula SkillCredits verificables por cada caso resuelto. Estos SkillCredits los exporta a LinkedIn como credencial profesional, transformando su labor de revisión en reconocimiento real y verificable.

---

### 2.4.1. User Stories

En esta sección se especifican los requisitos funcionales y técnicos de SkillSwap, aplicación móvil nativa y multiplataforma, mediante User Stories agrupadas en Epics. Las historias se redactaron a partir de los hallazgos de las entrevistas, los User Personas, el User Task Matrix y los Journey Maps de los dos segmentos objetivo: **personas que quieren aprender (Estudiantes)** y **personas que validan el conocimiento (Verificadores)**, además de los visitantes de la Landing Page. En total se definen **57 historias**: 45 User Stories orientadas a los usuarios finales y 12 Technical Stories, redactadas con el rol *Developer*, que describen los servicios RESTful que consume la aplicación móvil.

#### Epics

**Tabla 8**

*Epics del proyecto*

| Epic ID | Título | Descripción |
| :--- | :--- | :--- |
| EP01 | Gestión de cuenta institucional y suscripción | Como usuario, quiero registrarme con mi correo institucional, acceder de forma segura y gestionar mi suscripción, para formar parte de un ecosistema de estudiantes reales y acceder a los beneficios de la plataforma. |
| EP02 | Ruta de aprendizaje personalizada | Como estudiante, quiero declarar en lenguaje natural la habilidad que deseo dominar y obtener una ruta de certificaciones construida con las habilidades de la taxonomía de la plataforma que la IA identifica en mi meta, para avanzar de forma estructurada sin conocer de antemano los nombres exactos de los cursos. |
| EP03 | Validación de certificados | Como estudiante, quiero subir mis certificados y que la plataforma extraiga, verifique y relacione su contenido con mi ruta, para que cada certificado cuente como evidencia confiable de una habilidad. |
| EP04 | Evaluaciones prácticas generadas por IA | Como estudiante, quiero demostrar cada habilidad certificada mediante quizzes y miniproyectos generados por IA, para comprobar que realmente la domino y conocer con precisión el sub-tema en el que fallo. |
| EP05 | Verificación de casos por pares | Como estudiante o Verificador, quiero que los intentos no aprobados se escalen a un Verificador habilitado que los revise frente a una rúbrica, para resolver cada caso de forma justa, rápida y trazable. |
| EP06 | Demostración final supervisada | Como estudiante, quiero demostrar el dominio integral de mi ruta completada mediante un proyecto avanzado o examen supervisado por video, para obtener una validación final con mayor rigor. |
| EP07 | SkillCredits y reconocimiento profesional | Como Verificador, quiero acumular, consultar, canjear y exhibir mis SkillCredits, para que mi labor de verificación se convierta en una credencial profesional verificable. |
| EP08 | Supervisión y calidad del proceso | Como Verificador senior (rango Oro y confiabilidad de 90 o más, en la escala de 0 a 100), quiero resolver disputas, habilitar reevaluaciones, controlar la actividad y confiabilidad de otros Verificadores y consultar métricas de la plataforma, para garantizar la integridad de todo el proceso de verificación. |
| EP09 | Landing Page | Como visitante, quiero conocer la propuesta de valor, los planes y la forma de participar en SkillSwap desde un sitio web público, para decidir si descargo la aplicación y me registro. |
| EP10 | Infraestructura y despliegue | Como developer, quiero desplegar los servicios RESTful y su base de datos en un entorno público, con validación del esquema al arrancar y documentación OpenAPI accesible, para que la aplicación móvil consuma el backend en producción. |

*Nota.* Elaboración propia.

#### User Stories y Technical Stories

**Tabla 9**

*User Stories y Technical Stories del proyecto*

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US01</td><td>Estudiante</td><td>Alta</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Registro con correo institucional</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero registrarme con mi correo institucional, para acceder a la plataforma como un usuario universitario verificado.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Registro con dominio institucional válido</strong><br><strong>Dado que</strong> el estudiante no tiene una cuenta registrada<br><strong>Cuando</strong> envía su nombre de usuario, contraseña y un correo con dominio .edu.pe<br><strong>Entonces</strong> el sistema crea la cuenta con el rol Student<br><strong>Y</strong> envía a la dirección registrada un correo con un enlace de verificación de un solo uso, válido por 24 horas<br><br><strong>Escenario 2: Registro con dominio no institucional</strong><br><strong>Dado que</strong> el estudiante no tiene una cuenta registrada<br><strong>Cuando</strong> envía un correo cuyo dominio no pertenece a una institución educativa (.edu.pe)<br><strong>Entonces</strong> el sistema rechaza el registro<br><strong>Y</strong> informa que solo se aceptan correos institucionales<br><br><strong>Escenario 3: Registro con correo ya utilizado</strong><br><strong>Dado que</strong> existe una cuenta asociada a un correo institucional<br><strong>Cuando</strong> otro registro se envía con ese mismo correo<br><strong>Entonces</strong> el sistema rechaza el registro<br><strong>Y</strong> informa que el correo ya se encuentra en uso</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US02</td><td>Estudiante</td><td>Alta</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Inicio de sesión</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero iniciar sesión con mis credenciales, para acceder a mi ruta, mis certificados y mis evaluaciones.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Inicio de sesión con credenciales válidas</strong><br><strong>Dado que</strong> el estudiante tiene una cuenta verificada<br><strong>Cuando</strong> envía su nombre de usuario y contraseña correctos<br><strong>Entonces</strong> el sistema autentica al estudiante<br><strong>Y</strong> le otorga acceso a los recursos asociados a su rol<br><br><strong>Escenario 2: Inicio de sesión con credenciales inválidas</strong><br><strong>Dado que</strong> el estudiante tiene una cuenta registrada<br><strong>Cuando</strong> envía una contraseña incorrecta<br><strong>Entonces</strong> el sistema deniega el acceso<br><strong>Y</strong> no revela si el error corresponde al usuario o a la contraseña<br><br><strong>Escenario 3: Inicio de sesión con cuenta no verificada</strong><br><strong>Dado que</strong> el estudiante no ha confirmado su correo institucional<br><strong>Cuando</strong> intenta iniciar sesión<br><strong>Entonces</strong> el sistema deniega el acceso<br><strong>Y</strong> reenvía el correo de verificación</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US03</td><td>Estudiante</td><td>Media</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Acceso mediante biometría del dispositivo</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero iniciar sesión con la huella o el reconocimiento facial de mi dispositivo, para acceder de forma rápida y segura sin escribir mi contraseña.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Activación del acceso biométrico</strong><br><strong>Dado que</strong> el estudiante tiene una sesión activa<br><strong>Y</strong> su dispositivo cuenta con un sensor biométrico configurado<br><strong>Cuando</strong> habilita el acceso biométrico<br><strong>Entonces</strong> la aplicación almacena de forma segura en el dispositivo la credencial asociada<br><br><strong>Escenario 2: Acceso biométrico exitoso</strong><br><strong>Dado que</strong> el estudiante tiene el acceso biométrico habilitado<br><strong>Cuando</strong> el sensor del dispositivo valida su identidad<br><strong>Entonces</strong> la aplicación inicia la sesión sin solicitar la contraseña<br><br><strong>Escenario 3: Dispositivo sin biometría disponible</strong><br><strong>Dado que</strong> el dispositivo no cuenta con un sensor biométrico configurado<br><strong>Cuando</strong> el estudiante intenta habilitar el acceso biométrico<br><strong>Entonces</strong> la aplicación mantiene el inicio de sesión mediante contraseña<br><strong>Y</strong> comunica que la funcionalidad no está disponible en el dispositivo</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US04</td><td>Estudiante</td><td>Media</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Configuración del perfil de intereses</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero registrar mi descripción y mis temas de interés en mi perfil, para que la plataforma personalice mis rutas y el emparejamiento con Verificadores.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Registro de temas de interés</strong><br><strong>Dado que</strong> el estudiante tiene una sesión activa<br><strong>Cuando</strong> registra uno o más temas de interés y una descripción<br><strong>Entonces</strong> el sistema guarda la información en su perfil<br><strong>Y</strong> la incorpora al vector de habilidades del estudiante<br><br><strong>Escenario 2: Actualización de intereses</strong><br><strong>Dado que</strong> el estudiante ya registró temas de interés<br><strong>Cuando</strong> modifica sus temas de interés<br><strong>Entonces</strong> el sistema reemplaza los temas anteriores<br><strong>Y</strong> recalcula su vector de habilidades</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US05</td><td>Estudiante</td><td>Alta</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Suscripción al plan mensual</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero suscribirme al plan mensual desde la aplicación mediante Google Play, para tener hasta 3 rutas activas a la vez, sin tope de rutas en total y 10 escalamientos al mes a un Verificador, cuyos casos se revisan en 48 horas, en lugar de los límites del plan gratuito.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Suscripción exitosa</strong><br><strong>Dado que</strong> el estudiante tiene una cuenta verificada en el plan gratuito<br><strong>Cuando</strong> completa la compra del plan mensual de S/ 29,90 (IGV incluido) mediante el SDK de RevenueCat, que opera sobre Google Play Billing<br><strong>Entonces</strong> el sistema confirma con RevenueCat que la compra fue validada ante Google Play<br><strong>Y</strong> activa su suscripción con la fecha de vencimiento del periodo<br><strong>Y</strong> le permite tener hasta 3 rutas activas a la vez, sin tope de rutas en total<br><strong>Y</strong> le permite escalar hasta 10 casos al mes a un Verificador, que se revisan en 48 horas<br><br><strong>Escenario 2: Compra no validada</strong><br><strong>Dado que</strong> el estudiante completó el flujo de compra en la aplicación<br><strong>Cuando</strong> RevenueCat no confirma una suscripción vigente para su cuenta<br><strong>Entonces</strong> el sistema no activa la suscripción<br><strong>Y</strong> informa el motivo del error<br><br><strong>Escenario 3: Renovación automática</strong><br><strong>Dado que</strong> el estudiante tiene una suscripción activa<br><strong>Cuando</strong> RevenueCat notifica al backend la renovación registrada por Google Play al finalizar el periodo<br><strong>Entonces</strong> el sistema extiende la fecha de vencimiento por un nuevo periodo<br><br><strong>Escenario 4: Cancelación de la suscripción</strong><br><strong>Dado que</strong> el estudiante canceló su suscripción y conserva el plan mensual hasta el fin del periodo ya pagado<br><strong>Cuando</strong> finaliza ese periodo<br><strong>Entonces</strong> el sistema lo devuelve al plan gratuito sin eliminar sus rutas, su progreso, sus certificados ni su historial<br><strong>Y</strong> mantiene en cada caso ya escalado el plazo que tenía al abrirse<br><strong>Y</strong> cuenta los casos que ya escaló en el mes calendario en curso contra el cupo de 3 escalamientos del plan gratuito, de modo que, si ya escaló 3 o más ese mes, no puede escalar otro caso hasta el mes siguiente o hasta que se suscriba de nuevo<br><strong>Y</strong> mantiene disponible la ruta avanzada canjeada con SkillCredits, que no se cuenta en el límite de rutas<br><br><strong>Escenario 5: Rutas activas al volver al plan gratuito</strong><br><strong>Dado que</strong> el estudiante tenía más de 1 ruta activa cuando vence su plan mensual<br><strong>Cuando</strong> vuelve al plan gratuito<br><strong>Entonces</strong> el sistema mantiene activa la ruta en la que avanzó más recientemente<br><strong>Y</strong> pasa sus demás rutas activas al estado pausada, que conserva su progreso pero no le permite avanzar en ellas<br><strong>Y</strong> le permite elegir otra ruta activa pausando la actual y reactivando la que prefiera, o reactivar sus rutas pausadas si se suscribe de nuevo<br><strong>Y</strong> no le permite crear nuevas rutas mientras tenga 3 o más rutas en total, aunque sí cambiar cuál de sus rutas existentes está activa<br><br><strong>Escenario 6: Límite de rutas del plan gratuito</strong><br><strong>Dado que</strong> el estudiante con plan gratuito ya tiene 1 ruta activa, o ya tiene 3 rutas en total<br><strong>Cuando</strong> intenta iniciar una nueva ruta<br><strong>Entonces</strong> la aplicación muestra la pantalla "Alcanzaste el límite de tu plan"<br><strong>Y</strong> le ofrece pasar al plan mensual o continuar con el plan gratuito<br><strong>Y</strong> una ruta avanzada canjeada con SkillCredits no se cuenta en ese límite<br><br><strong>Escenario 7: Límite de escalamientos del plan gratuito</strong><br><strong>Dado que</strong> el estudiante con plan gratuito ya escaló 3 casos a un Verificador en el mes<br><strong>Cuando</strong> envía un entregable que requiere la revisión de un Verificador<br><strong>Entonces</strong> el sistema no abre un nuevo caso<br><strong>Y</strong> la aplicación muestra la pantalla "Alcanzaste el límite de tu plan" con la opción de pasar al plan mensual o continuar con el plan gratuito</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US06</td><td>Estudiante</td><td>Alta</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Declaración de la meta en lenguaje natural</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero describir con mis propias palabras la habilidad que deseo aprender, para que el sistema la relacione con la taxonomía de habilidades sin que yo conozca el nombre exacto de cada certificación.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Meta interpretada correctamente</strong><br><strong>Dado que</strong> el estudiante no tiene una ruta activa<br><strong>Cuando</strong> declara la meta "quiero aprender a construir APIs REST con autenticación JWT"<br><strong>Entonces</strong> el sistema interpreta la meta con IA generativa y selecciona las habilidades correspondientes únicamente de la taxonomía de habilidades<br><strong>Y</strong> descarta cualquier habilidad propuesta que no pertenezca a la taxonomía<br><strong>Y</strong> genera una ruta de aprendizaje asociada a esa meta<br><br><strong>Escenario 2: Meta sin correspondencia en la taxonomía</strong><br><strong>Dado que</strong> el estudiante declara una meta<br><strong>Cuando</strong> ni la interpretación con IA ni la comparación por palabras clave identifican habilidades de la taxonomía en el texto declarado<br><strong>Entonces</strong> el sistema no genera la ruta<br><strong>Y</strong> solicita al estudiante precisar su meta<br><br><strong>Escenario 3: Servicio de IA no disponible</strong><br><strong>Dado que</strong> el estudiante declara una meta<br><strong>Cuando</strong> el servicio de IA falla, excede el tiempo de espera o no devuelve habilidades válidas de la taxonomía<br><strong>Entonces</strong> el sistema identifica las habilidades comparando las palabras clave de la meta con la misma taxonomía<br><strong>Y</strong> genera la ruta de aprendizaje asociada a esa meta</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US07</td><td>Estudiante</td><td>Media</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Confirmación de la habilidad interpretada</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero confirmar la habilidad que el sistema interpretó de mi meta cuando existen varias opciones posibles, para que mi ruta no se construya sobre una interpretación incorrecta.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Meta ambigua</strong><br><strong>Dado que</strong> la meta declarada por el estudiante coincide con más de una habilidad con similitud cercana<br><strong>Cuando</strong> el sistema procesa la meta<br><strong>Entonces</strong> el sistema presenta las habilidades candidatas, todas pertenecientes a la taxonomía de habilidades, ordenadas por similitud<br><strong>Y</strong> espera la confirmación del estudiante antes de generar la ruta<br><br><strong>Escenario 2: Confirmación de la habilidad</strong><br><strong>Dado que</strong> el sistema presentó habilidades candidatas<br><strong>Cuando</strong> el estudiante confirma una de ellas<br><strong>Entonces</strong> el sistema genera la ruta a partir de la habilidad confirmada</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US08</td><td>Estudiante</td><td>Alta</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de la ruta de aprendizaje</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero consultar mi ruta de aprendizaje con el estado de cada certificación, para saber qué he completado y cuál es mi siguiente paso.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de ruta activa</strong><br><strong>Dado que</strong> el estudiante tiene una ruta activa<br><strong>Cuando</strong> consulta su ruta<br><strong>Entonces</strong> el sistema retorna los nodos en su orden de prerrequisitos<br><strong>Y</strong> cada nodo indica su estado: bloqueado, disponible o completado<br><br><strong>Escenario 2: Desbloqueo del siguiente nodo</strong><br><strong>Dado que</strong> el estudiante completa un nodo de su ruta<br><strong>Cuando</strong> el sistema registra la aprobación del nodo<br><strong>Entonces</strong> el siguiente nodo de la secuencia cambia su estado a disponible<br><br><strong>Escenario 3: Ruta completada</strong><br><strong>Dado que</strong> el estudiante completa el último nodo pendiente<br><strong>Cuando</strong> el sistema registra la aprobación del nodo<br><strong>Entonces</strong> la ruta cambia su estado a completada<br><strong>Y</strong> el estudiante queda habilitado para la demostración final</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US09</td><td>Estudiante</td><td>Alta</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Reconocimiento de habilidades ya certificadas</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que la ruta considere los certificados que ya tengo validados, para no repetir certificaciones de habilidades que ya demostré.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Generación de ruta con certificados previos</strong><br><strong>Dado que</strong> el estudiante posee un certificado validado que cubre una habilidad requerida por su meta<br><strong>Cuando</strong> el sistema genera la ruta<br><strong>Entonces</strong> el nodo de esa habilidad se registra como completado<br><strong>Y</strong> se vincula al certificado validado<br><br><strong>Escenario 2: Recalculo tras un nuevo certificado</strong><br><strong>Dado que</strong> el estudiante tiene una ruta activa<br><strong>Cuando</strong> valida un nuevo certificado que cubre un nodo pendiente<br><strong>Entonces</strong> el sistema recalcula los nodos pendientes de la ruta<br><strong>Y</strong> conserva sin cambios los nodos ya completados</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US10</td><td>Estudiante</td><td>Media</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de la ruta sin conexión</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero consultar mi ruta de aprendizaje aunque no tenga conexión a internet, para revisar mi avance en cualquier momento.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Almacenamiento local de la ruta</strong><br><strong>Dado que</strong> el estudiante consulta su ruta con conexión a internet<br><strong>Cuando</strong> el sistema retorna la ruta<br><strong>Entonces</strong> la aplicación guarda una copia en la base de datos local del dispositivo<br><br><strong>Escenario 2: Consulta sin conexión</strong><br><strong>Dado que</strong> el estudiante tiene una copia local de su ruta<br><strong>Y</strong> el dispositivo no tiene conexión a internet<br><strong>Cuando</strong> consulta su ruta<br><strong>Entonces</strong> la aplicación retorna la copia local<br><strong>Y</strong> indica la fecha de su última sincronización<br><br><strong>Escenario 3: Sincronización al recuperar conexión</strong><br><strong>Dado que</strong> el dispositivo recupera la conexión a internet<br><strong>Cuando</strong> el estudiante consulta su ruta<br><strong>Entonces</strong> la aplicación actualiza la copia local con la versión del servidor</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US11</td><td>Estudiante</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Captura del certificado con la cámara</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero capturar mi certificado físico o impreso con la cámara del dispositivo, para registrarlo sin necesidad de escanearlo previamente.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Captura con permiso concedido</strong><br><strong>Dado que</strong> el estudiante concedió el permiso de cámara a la aplicación<br><strong>Cuando</strong> captura la imagen de su certificado<br><strong>Entonces</strong> la aplicación registra la imagen como documento del certificado<br><strong>Y</strong> inicia la extracción de sus datos<br><br><strong>Escenario 2: Permiso de cámara denegado</strong><br><strong>Dado que</strong> el estudiante denegó el permiso de cámara<br><strong>Cuando</strong> intenta capturar un certificado<br><strong>Entonces</strong> la aplicación no accede a la cámara<br><strong>Y</strong> ofrece registrar el certificado desde un archivo del dispositivo<br><br><strong>Escenario 3: Imagen ilegible</strong><br><strong>Dado que</strong> el estudiante captura una imagen borrosa o incompleta<br><strong>Cuando</strong> la extracción no reconoce texto suficiente<br><strong>Entonces</strong> la aplicación rechaza la imagen<br><strong>Y</strong> solicita una nueva captura</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US12</td><td>Estudiante</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Carga del certificado desde un archivo</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero subir mi certificado en formato PDF o imagen desde mi dispositivo, para validar certificados que obtuve en plataformas digitales.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Carga de formato válido</strong><br><strong>Dado que</strong> el estudiante tiene una sesión activa<br><strong>Cuando</strong> sube un archivo PDF, JPG o PNG de hasta 10 MB<br><strong>Entonces</strong> el sistema almacena el archivo en el almacenamiento en la nube<br><strong>Y</strong> registra el certificado en estado pendiente de verificación<br><br><strong>Escenario 2: Formato o tamaño no permitido</strong><br><strong>Dado que</strong> el estudiante tiene una sesión activa<br><strong>Cuando</strong> sube un archivo con un formato no permitido o mayor a 10 MB<br><strong>Entonces</strong> el sistema rechaza el archivo<br><strong>Y</strong> informa los formatos y el tamaño aceptados</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US13</td><td>Estudiante</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Extracción automática de datos del certificado</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que la aplicación extraiga automáticamente los datos de mi certificado, para no transcribir manualmente el curso, la institución y la fecha.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Extracción completa</strong><br><strong>Dado que</strong> el estudiante registró la imagen de un certificado<br><strong>Cuando</strong> el reconocimiento de texto on-device procesa la imagen<br><strong>Entonces</strong> el sistema obtiene el titular, la institución, el curso y la fecha de emisión<br><strong>Y</strong> conserva el texto completo extraído para auditoría<br><br><strong>Escenario 2: Extracción parcial</strong><br><strong>Dado que</strong> el reconocimiento de texto no identifica uno o más campos obligatorios<br><strong>Cuando</strong> finaliza la extracción<br><strong>Entonces</strong> la aplicación solicita al estudiante completar los campos faltantes antes de enviar el certificado<br><br><strong>Escenario 3: Titular distinto al usuario</strong><br><strong>Dado que</strong> el titular extraído no coincide con el nombre registrado del estudiante<br><strong>Cuando</strong> el sistema evalúa el riesgo del certificado<br><strong>Entonces</strong> el certificado se registra con estado sospechoso<br><strong>Y</strong> se escala a un Verificador senior</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US14</td><td>Estudiante</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Detección de certificados duplicados</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que la plataforma detecte certificados duplicados, para que ningún usuario obtenga una validación con un documento ya utilizado.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Certificado original</strong><br><strong>Dado que</strong> el hash del archivo no coincide con ningún certificado registrado<br><strong>Cuando</strong> el estudiante registra el certificado<br><strong>Entonces</strong> el sistema continúa con la evaluación de riesgo del certificado<br><br><strong>Escenario 2: Certificado duplicado del mismo usuario</strong><br><strong>Dado que</strong> el estudiante ya registró un archivo con el mismo hash<br><strong>Cuando</strong> intenta registrarlo nuevamente<br><strong>Entonces</strong> el sistema rechaza el registro<br><strong>Y</strong> referencia el certificado existente<br><br><strong>Escenario 3: Certificado registrado por otro usuario</strong><br><strong>Dado que</strong> otro usuario ya registró un archivo con el mismo hash<br><strong>Cuando</strong> el estudiante registra el certificado<br><strong>Entonces</strong> el sistema asigna el estado sospechoso al certificado<br><strong>Y</strong> escala el caso a un Verificador senior</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US15</td><td>Estudiante</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Correspondencia del certificado con la habilidad</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que la plataforma confirme que mi certificado realmente cubre la habilidad del nodo al que lo asocio, para que mi avance refleje lo que efectivamente estudié.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Certificado que cubre la habilidad</strong><br><strong>Dado que</strong> el estudiante asocia a un nodo de su ruta un certificado que superó el análisis de riesgo<br><strong>Cuando</strong> el sistema compara el contenido extraído con la habilidad del nodo<br><strong>Y</strong> la similitud supera el umbral definido<br><strong>Entonces</strong> el sistema vincula el certificado al nodo<br><strong>Y</strong> mantiene la evaluación práctica como requisito para completar el nodo<br><br><strong>Escenario 2: Certificado que no cubre la habilidad</strong><br><strong>Dado que</strong> el estudiante asocia a un nodo de su ruta un certificado que superó el análisis de riesgo<br><strong>Cuando</strong> la similitud entre el contenido extraído y la habilidad no supera el umbral definido<br><strong>Entonces</strong> el sistema no vincula el certificado al nodo<br><strong>Y</strong> sugiere los nodos de la ruta con los que el certificado sí guarda correspondencia</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US16</td><td>Estudiante</td><td>Media</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta del estado de verificación</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero conocer el estado de verificación de cada certificado que subí y recibir una notificación cuando se resuelva, para saber si ya cuenta como evidencia en mi ruta.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de certificados</strong><br><strong>Dado que</strong> el estudiante registró uno o más certificados<br><strong>Cuando</strong> consulta sus certificados<br><strong>Entonces</strong> el sistema retorna cada certificado con su estado: pendiente, verificado, sospechoso o rechazado<br><br><strong>Escenario 2: Notificación de resolución</strong><br><strong>Dado que</strong> el estudiante concedió el permiso de notificaciones<br><strong>Cuando</strong> uno de sus certificados alcanza el estado verificado o rechazado<br><strong>Entonces</strong> el sistema envía una notificación push al dispositivo del estudiante mediante Firebase Cloud Messaging<br><strong>Y</strong> la notificación incluye el motivo cuando el estado es rechazado<br><br><strong>Escenario 3: Permiso de notificaciones denegado</strong><br><strong>Dado que</strong> el estudiante denegó el permiso de notificaciones<br><strong>Cuando</strong> uno de sus certificados alcanza un estado definitivo<br><strong>Entonces</strong> el sistema no envía la notificación push<br><strong>Y</strong> el nuevo estado queda disponible en la consulta de sus certificados</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US17</td><td>Estudiante</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Generación del quiz de un nodo</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que la IA genere un quiz basado en la habilidad de mi nodo, para demostrar que adquirí el conocimiento y no solo el documento.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Generación de quiz</strong><br><strong>Dado que</strong> el estudiante tiene un nodo disponible en su ruta<br><strong>Cuando</strong> solicita su evaluación práctica<br><strong>Entonces</strong> el sistema genera un quiz sobre los sub-temas de la habilidad del nodo<br><strong>Y</strong> asocia el quiz al nodo<br><br><strong>Escenario 2: Nodo bloqueado</strong><br><strong>Dado que</strong> el nodo del estudiante se encuentra bloqueado<br><strong>Cuando</strong> solicita su evaluación práctica<br><strong>Entonces</strong> el sistema rechaza la solicitud<br><strong>Y</strong> indica el nodo prerrequisito pendiente<br><br><strong>Escenario 3: Nuevo intento con preguntas distintas</strong><br><strong>Dado que</strong> el estudiante ya rindió el quiz de un nodo<br><strong>Cuando</strong> solicita un nuevo intento<br><strong>Entonces</strong> el sistema genera un quiz con preguntas distintas a las del intento anterior</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US18</td><td>Estudiante</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Resolución del quiz con calificación en el servidor</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero rendir el quiz y conocer mi resultado de inmediato, para saber si demostré la habilidad del nodo.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Quiz aprobado</strong><br><strong>Dado que</strong> el estudiante rinde el quiz de un nodo<br><strong>Cuando</strong> envía sus respuestas<br><strong>Y</strong> acierta al menos 4 de las 5 preguntas (puntaje calculado en el servidor)<br><strong>Entonces</strong> el sistema registra el intento como aprobado<br><strong>Y</strong> marca el nodo como completado<br><br><strong>Escenario 2: Quiz no aprobado</strong><br><strong>Dado que</strong> el estudiante rinde el quiz de un nodo<br><strong>Cuando</strong> acierta menos de 4 de las 5 preguntas<br><strong>Entonces</strong> el sistema registra el intento como no aprobado<br><strong>Y</strong> abre un caso de verificación asociado al intento, si el estudiante aún tiene escalamientos disponibles en el mes según su plan<br><br><strong>Escenario 3: Reenvío sobre un blueprint ya resuelto</strong><br><strong>Dado que</strong> el estudiante ya envió respuestas para un blueprint<br><strong>Cuando</strong> intenta enviarlas nuevamente sobre el mismo blueprint<br><strong>Entonces</strong> el sistema rechaza el envío indicando que el intento ya fue registrado</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US19</td><td>Estudiante</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Entrega de un miniproyecto</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero desarrollar y entregar un miniproyecto generado para mi nodo, para demostrar la habilidad de forma práctica y no solo teórica.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Generación del enunciado</strong><br><strong>Dado que</strong> el estudiante tiene un nodo disponible cuya habilidad admite evaluación práctica<br><strong>Cuando</strong> solicita un miniproyecto<br><strong>Entonces</strong> el sistema genera un enunciado con su rúbrica de evaluación<br><br><strong>Escenario 2: Entrega dentro del plazo</strong><br><strong>Dado que</strong> el estudiante tiene un miniproyecto asignado<br><strong>Cuando</strong> entrega su repositorio o archivos dentro del plazo definido<br><strong>Entonces</strong> el sistema registra la entrega<br><strong>Y</strong> ejecuta la evaluación preliminar de la IA según la rúbrica<br><br><strong>Escenario 3: Evaluación preliminar insuficiente</strong><br><strong>Dado que</strong> la evaluación preliminar de la IA no alcanza el puntaje mínimo de la rúbrica o su nivel de confianza es bajo<br><strong>Cuando</strong> finaliza la evaluación<br><strong>Entonces</strong> el sistema abre un caso de verificación para la revisión de un Verificador</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US20</td><td>Estudiante</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Identificación del sub-tema débil</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero saber exactamente en qué sub-tema fallé, para reforzar solo esa parte en lugar de repetir todo el certificado.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Diagnóstico tras un intento no aprobado</strong><br><strong>Dado que</strong> el estudiante obtiene un intento no aprobado<br><strong>Cuando</strong> el sistema analiza los errores por sub-tema<br><strong>Entonces</strong> el sistema identifica los sub-temas con menor desempeño<br><strong>Y</strong> recomienda recursos específicos para cada uno<br><br><strong>Escenario 2: Intento aprobado con errores puntuales</strong><br><strong>Dado que</strong> el estudiante aprueba un intento con errores concentrados en un sub-tema<br><strong>Cuando</strong> el sistema registra el resultado<br><strong>Entonces</strong> el sistema informa el sub-tema a reforzar sin bloquear su avance</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US21</td><td>Estudiante</td><td>Media</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Conservación del avance ante pérdida de conexión</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero que mis respuestas se conserven si pierdo la conexión durante un quiz, para no perder mi avance.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Pérdida de conexión durante el quiz</strong><br><strong>Dado que</strong> el estudiante rinde un quiz<br><strong>Cuando</strong> el dispositivo pierde la conexión a internet<br><strong>Entonces</strong> la aplicación almacena localmente las respuestas registradas<br><br><strong>Escenario 2: Envío al recuperar la conexión</strong><br><strong>Dado que</strong> existen respuestas almacenadas localmente de un quiz en curso<br><strong>Cuando</strong> el dispositivo recupera la conexión antes del tiempo límite<br><strong>Entonces</strong> la aplicación sincroniza las respuestas con el servidor<br><strong>Y</strong> elimina la copia local tras la confirmación</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US22</td><td>Estudiante</td><td>Alta</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Habilitación como Verificador</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero habilitarme como Verificador de una habilidad cuyo nodo completé en mi propia ruta, para revisar casos de otros estudiantes.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Nodo completado</strong><br><strong>Dado que</strong> el estudiante tiene el nodo de una habilidad en estado completado<br><strong>Cuando</strong> solicita habilitarse como Verificador de esa habilidad<br><strong>Entonces</strong> el sistema crea su perfil de Verificador (si es la primera habilidad) o agrega la habilidad a su perfil existente<br><strong>Y</strong> lo habilita para recibir casos de esa habilidad<br><br><strong>Escenario 2: Nodo no completado</strong><br><strong>Dado que</strong> el estudiante no tiene completado el nodo de esa habilidad<br><strong>Cuando</strong> solicita habilitarse como Verificador<br><strong>Entonces</strong> el sistema rechaza la solicitud<br><strong>Y</strong> indica que debe completar el nodo primero<br><br><strong>Escenario 3: Habilidad ya habilitada</strong><br><strong>Dado que</strong> el estudiante ya está habilitado como Verificador de una habilidad<br><strong>Cuando</strong> vuelve a solicitar la habilitación de esa misma habilidad<br><strong>Entonces</strong> el sistema rechaza la solicitud por duplicada</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US23</td><td>Verificador</td><td>Media</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Gestión de disponibilidad</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero indicar si estoy disponible para recibir casos, para que solo se me asignen revisiones cuando puedo atenderlas.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Activación de disponibilidad</strong><br><strong>Dado que</strong> el Verificador está habilitado y no disponible<br><strong>Cuando</strong> activa su disponibilidad<br><strong>Entonces</strong> el sistema lo incluye en el proceso de asignación de casos<br><br><strong>Escenario 2: Desactivación de disponibilidad</strong><br><strong>Dado que</strong> el Verificador está disponible<br><strong>Cuando</strong> desactiva su disponibilidad<br><strong>Entonces</strong> el sistema deja de asignarle nuevos casos<br><strong>Y</strong> mantiene los casos que ya tiene asignados</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US24</td><td>Verificador</td><td>Alta</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Asignación automática de casos por disponibilidad</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero recibir automáticamente casos de las habilidades que tengo habilitadas, para revisar solo trabajos de lo que domino.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Asignación por menor carga</strong><br><strong>Dado que</strong> se abre un caso de verificación de una habilidad<br><strong>Y</strong> existen Verificadores disponibles y verificados habilitados en esa habilidad<br><strong>Cuando</strong> el sistema asigna el caso<br><strong>Entonces</strong> el sistema elige al candidato con menos casos abiertos en ese momento<br><strong>Y</strong>, en caso de empate, al de menor identificador de usuario<br><br><strong>Escenario 2: Exclusión del propio estudiante</strong><br><strong>Dado que</strong> el estudiante dueño del caso también está habilitado como Verificador de esa habilidad<br><strong>Cuando</strong> el sistema asigna el caso<br><strong>Entonces</strong> el sistema lo excluye como candidato, incluso si fuera el de menor carga<br><br><strong>Escenario 3: Sin Verificadores disponibles</strong><br><strong>Dado que</strong> no existen Verificadores disponibles para la habilidad del caso<br><strong>Cuando</strong> el sistema intenta asignar el caso<br><strong>Entonces</strong> el caso permanece pendiente<br><strong>Y</strong> se reintenta la asignación cuando un Verificador activa su disponibilidad o se habilita en esa habilidad</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US25</td><td>Verificador</td><td>Alta</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Revisión del caso con notas de rúbrica</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero evaluar el trabajo del estudiante y registrar mi decisión con notas justificativas, para emitir una resolución objetiva y trazable.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Caso aprobado</strong><br><strong>Dado que</strong> el Verificador asignado revisa un caso<br><strong>Cuando</strong> registra la decisión "Approved" junto con sus notas de rúbrica<br><strong>Entonces</strong> el sistema resuelve el caso como aprobado<br><strong>Y</strong> marca como completado el nodo del estudiante<br><br><strong>Escenario 2: Caso rechazado</strong><br><strong>Dado que</strong> el Verificador asignado revisa un caso<br><strong>Cuando</strong> registra la decisión "Rejected" junto con sus notas de rúbrica<br><strong>Entonces</strong> el sistema resuelve el caso como rechazado<br><strong>Y</strong> deja el nodo disponible para que el estudiante solicite una nueva evaluación<br><br><strong>Escenario 3: Notas de rúbrica faltantes</strong><br><strong>Dado que</strong> el Verificador asignado intenta resolver un caso<br><strong>Cuando</strong> no incluye notas de rúbrica<br><strong>Entonces</strong> el sistema rechaza la resolución e indica que las notas son obligatorias<br><br><strong>Escenario 4: Verificador no asignado</strong><br><strong>Dado que</strong> un Verificador distinto al asignado intenta resolver el caso<br><strong>Cuando</strong> envía su decisión<br><strong>Entonces</strong> el sistema rechaza la operación</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US26</td><td>Estudiante</td><td>Media</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Aporte de evidencia adicional</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero adjuntar un enlace con evidencia adicional a mi caso de verificación, para respaldar mejor el dominio de la habilidad.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Evidencia en caso abierto</strong><br><strong>Dado que</strong> el estudiante tiene un caso de verificación abierto<br><strong>Cuando</strong> adjunta la URL de su repositorio o portafolio<br><strong>Entonces</strong> el sistema asocia la evidencia al caso<br><strong>Y</strong> la pone a disposición del Verificador asignado<br><br><strong>Escenario 2: Reemplazo de evidencia</strong><br><strong>Dado que</strong> el estudiante ya adjuntó una URL de evidencia<br><strong>Cuando</strong> adjunta una nueva URL sobre el mismo caso<br><strong>Entonces</strong> el sistema reemplaza la evidencia anterior por la nueva<br><br><strong>Escenario 3: Caso ya resuelto</strong><br><strong>Dado que</strong> el caso de verificación del estudiante ya fue resuelto<br><strong>Cuando</strong> intenta adjuntar evidencia<br><strong>Entonces</strong> el sistema rechaza la operación</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US27</td><td>Estudiante</td><td>Media</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Apelación de la decisión del Verificador</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero apelar la decisión de un Verificador que considero injusta, para que otro Verificador revise mi caso.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Apelación de un caso rechazado</strong><br><strong>Dado que</strong> el caso del estudiante fue resuelto como rechazado<br><strong>Cuando</strong> registra una apelación<br><strong>Entonces</strong> el sistema reabre el caso<br><strong>Y</strong> lo asigna a otro Verificador habilitado, distinto del que lo rechazó<br><br><strong>Escenario 2: Caso no apelable</strong><br><strong>Dado que</strong> el caso del estudiante no fue resuelto como rechazado<br><strong>Cuando</strong> intenta registrar una apelación<br><strong>Entonces</strong> el sistema rechaza la apelación<br><strong>Y</strong> informa el motivo<br><br><strong>Escenario 3: Apelación duplicada</strong><br><strong>Dado que</strong> el estudiante ya registró una apelación para un caso<br><strong>Cuando</strong> intenta registrar otra sobre el mismo caso<br><strong>Entonces</strong> el sistema rechaza la nueva apelación</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US28</td><td>Estudiante</td><td>Baja</td><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">Programación de la demostración final</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero programar mi demostración final en un horario disponible de un Verificador, para validar el dominio integral de mi ruta completada.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Programación con ruta completada</strong><br><strong>Dado que</strong> el estudiante completó su ruta<br><strong>Cuando</strong> elige la modalidad (proyecto avanzado o examen supervisado) y un horario disponible<br><strong>Entonces</strong> el sistema registra la demostración<br><strong>Y</strong> asigna a un Verificador habilitado en la habilidad de la ruta<br><br><strong>Escenario 2: Ruta no completada</strong><br><strong>Dado que</strong> el estudiante tiene nodos pendientes en su ruta<br><strong>Cuando</strong> solicita programar la demostración final<br><strong>Entonces</strong> el sistema rechaza la solicitud</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US29</td><td>Estudiante</td><td>Baja</td><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">Demostración final por video</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como estudiante, quiero grabar y subir un video de mi demostración final dentro de la aplicación, para que el Verificador constate que la demostración es genuina.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Grabación del video</strong><br><strong>Dado que</strong> el estudiante completó todos los nodos de su ruta de aprendizaje<br><strong>Y</strong> concedió los permisos de cámara y micrófono<br><strong>Cuando</strong> graba el video de su demostración final desde la aplicación<br><strong>Entonces</strong> el sistema permite adjuntarlo como evidencia del caso de verificación<br><br><strong>Escenario 2: Permisos no concedidos</strong><br><strong>Dado que</strong> el estudiante no concedió los permisos de cámara o micrófono<br><strong>Cuando</strong> intenta grabar el video de demostración<br><strong>Entonces</strong> la aplicación no inicia la grabación<br><strong>Y</strong> solicita los permisos requeridos<br><br><strong>Escenario 3: Registro del resultado</strong><br><strong>Dado que</strong> el video de la demostración fue subido correctamente<br><strong>Cuando</strong> el Verificador revisa el video y registra su evaluación según la rúbrica<br><strong>Entonces</strong> el sistema registra el resultado de la demostración final en el perfil del estudiante</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US30</td><td>Verificador</td><td>Alta</td><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Acreditación de SkillCredits por caso resuelto</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero recibir SkillCredits por cada caso que resuelvo, para que mi labor de verificación sea reconocida.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Acreditación tras resolver un miniproyecto</strong><br><strong>Dado que</strong> el Verificador resuelve un caso de verificación de tipo miniproyecto<br><strong>Cuando</strong> el sistema registra la resolución<br><strong>Entonces</strong> el sistema acredita 40 SkillCredits en su billetera, sea que el caso se apruebe o se rechace<br><strong>Y</strong> registra una transacción de tipo ganado<br><br><strong>Escenario 2: Acreditación tras resolver un quiz</strong><br><strong>Dado que</strong> el Verificador resuelve un caso de verificación de tipo quiz<br><strong>Cuando</strong> el sistema registra la resolución<br><strong>Entonces</strong> el sistema acredita 25 SkillCredits en su billetera, sea que el caso se apruebe o se rechace<br><strong>Y</strong> registra una transacción de tipo ganado<br><br><strong>Escenario 3: Decisión revertida</strong><br><strong>Dado que</strong> otro Verificador aprueba, tras una apelación, un caso que el Verificador original había rechazado<br><strong>Cuando</strong> el sistema registra la reversión<br><strong>Entonces</strong> el sistema no acredita SkillCredits adicionales al Verificador original por ese caso<br><strong>Y</strong> reduce la confiabilidad del Verificador original</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US31</td><td>Verificador</td><td>Media</td><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de billetera e historial</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero consultar mi saldo de SkillCredits y el historial de movimientos, para conocer cuántos créditos gané y en qué los utilicé.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de saldo</strong><br><strong>Dado que</strong> el Verificador tiene una billetera<br><strong>Cuando</strong> consulta su billetera<br><strong>Entonces</strong> el sistema retorna el saldo actual de SkillCredits<br><br><strong>Escenario 2: Consulta de historial</strong><br><strong>Dado que</strong> el Verificador registra movimientos en su billetera<br><strong>Cuando</strong> consulta su historial<br><strong>Entonces</strong> el sistema retorna los movimientos ordenados del más reciente al más antiguo<br><strong>Y</strong> cada movimiento indica su tipo, cantidad y fecha</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US32</td><td>Verificador</td><td>Media</td><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Canje de SkillCredits en la tienda</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero canjear mis SkillCredits por beneficios de la tienda, para aprovechar el reconocimiento que acumulé.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Canje con saldo suficiente</strong><br><strong>Dado que</strong> el Verificador tiene un saldo mayor o igual al costo de un beneficio (200 SkillCredits la ruta avanzada o 120 el certificado de contribución)<br><strong>Cuando</strong> solicita el canje de ese beneficio<br><strong>Entonces</strong> el sistema descuenta el costo de su saldo<br><strong>Y</strong> registra una transacción de tipo canjeado<br><br><strong>Escenario 2: Canje con saldo insuficiente</strong><br><strong>Dado que</strong> el Verificador tiene un saldo menor al costo de un beneficio<br><strong>Cuando</strong> solicita el canje de ese beneficio<br><strong>Entonces</strong> el sistema rechaza el canje<br><strong>Y</strong> mantiene su saldo sin cambios</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US33</td><td>Verificador</td><td>Media</td><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Compartir logros en LinkedIn</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero compartir mis SkillCredits y habilidades verificadas en LinkedIn u otras redes profesionales, para exhibir mi experiencia como una credencial verificable.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Generación de la credencial</strong><br><strong>Dado que</strong> el Verificador tiene al menos una habilidad verificada<br><strong>Cuando</strong> solicita compartir su logro<br><strong>Entonces</strong> el sistema genera una credencial con un enlace público de verificación<br><br><strong>Escenario 2: Compartir mediante el sistema del dispositivo</strong><br><strong>Dado que</strong> el Verificador generó una credencial<br><strong>Cuando</strong> la comparte<br><strong>Entonces</strong> la aplicación envía el enlace de la credencial mediante el mecanismo nativo de compartir de Android hacia la aplicación de LinkedIn u otra aplicación instalada<br><br><strong>Escenario 3: Validación pública de la credencial</strong><br><strong>Dado que</strong> un tercero accede al enlace público de una credencial<br><strong>Cuando</strong> consulta su autenticidad<br><strong>Entonces</strong> el sistema retorna el titular, la habilidad, los SkillCredits y la fecha de emisión<br><strong>Y</strong> no expone datos personales adicionales</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US34</td><td>Verificador senior</td><td>Alta</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de disputas pendientes</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero consultar las disputas pendientes que tengo asignadas con su evidencia, para priorizar y resolver los casos que requieren mi decisión.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Listado de disputas pendientes</strong><br><strong>Dado que</strong> existen disputas en estado pendiente asignadas al Verificador senior<br><strong>Cuando</strong> el Verificador senior consulta sus disputas<br><strong>Entonces</strong> el sistema retorna las disputas pendientes ordenadas de la más antigua a la más reciente<br><strong>Y</strong> cada una indica su origen: la revisión de un certificado sospechoso<br><br><strong>Escenario 2: Consulta de evidencia</strong><br><strong>Dado que</strong> el Verificador senior consulta una disputa<br><strong>Cuando</strong> solicita su evidencia<br><strong>Entonces</strong> el sistema retorna los datos extraídos, la evaluación de riesgo y un enlace temporal al archivo del certificado</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US35</td><td>Verificador senior</td><td>Alta</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Resolución de certificados sospechosos</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero decidir sobre los certificados marcados como sospechosos, para evitar que documentos fraudulentos se validen en la plataforma.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Certificado legítimo</strong><br><strong>Dado que</strong> el Verificador senior revisa un certificado sospechoso<br><strong>Cuando</strong> lo resuelve como legítimo<br><strong>Entonces</strong> el certificado cambia a estado verificado<br><strong>Y</strong> el sistema completa los nodos de las rutas del estudiante cuya habilidad cubre el certificado<br><br><strong>Escenario 2: Certificado fraudulento</strong><br><strong>Dado que</strong> el Verificador senior revisa un certificado sospechoso<br><strong>Cuando</strong> lo resuelve como fraudulento<br><strong>Entonces</strong> el certificado cambia a estado rechazado<br><strong>Y</strong> el sistema notifica al estudiante el rechazo<br><br><strong>Escenario 3: Resolución sin observaciones</strong><br><strong>Dado que</strong> el Verificador senior resuelve una disputa<br><strong>Cuando</strong> no registra observaciones<br><strong>Entonces</strong> el sistema no aplica la resolución<br><strong>Y</strong> exige el registro de observaciones</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US36</td><td>Verificador</td><td>Alta</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Revisión de casos apelados</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador, quiero revisar los casos apelados que se me asignan, para corregir las decisiones incorrectas de otros Verificadores y mantener la confianza en el proceso.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Decisión confirmada</strong><br><strong>Dado que</strong> un caso apelado está asignado a un Verificador distinto del que lo rechazó<br><strong>Cuando</strong> el Verificador lo resuelve como rechazado con sus notas de rúbrica<br><strong>Entonces</strong> el caso queda rechazado<br><strong>Y</strong> el estudiante ya no puede volver a apelarlo<br><br><strong>Escenario 2: Decisión revertida</strong><br><strong>Dado que</strong> un caso apelado está asignado a un Verificador distinto del que lo rechazó<br><strong>Cuando</strong> el Verificador lo resuelve como aprobado con sus notas de rúbrica<br><strong>Entonces</strong> el caso cambia a aprobado y el nodo del estudiante se completa<br><strong>Y</strong> el sistema registra la reversión en la confiabilidad del Verificador original</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US37</td><td>Verificador senior</td><td>Alta</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Reevaluación de un resultado aprobado</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero ordenar la reevaluación de un resultado aprobado, para que el estudiante vuelva a demostrar su habilidad cuando existan dudas sobre ese resultado.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Reevaluación de un intento aprobado</strong><br><strong>Dado que</strong> el Verificador senior identifica dudas sobre un intento aprobado<br><strong>Cuando</strong> ordena una reevaluación con su justificación<br><strong>Entonces</strong> el nodo del estudiante vuelve a estado disponible<br><strong>Y</strong> el sistema genera una nueva evaluación y registra la justificación del Verificador senior<br><br><strong>Escenario 2: Reevaluación de un caso aprobado</strong><br><strong>Dado que</strong> el Verificador senior identifica dudas sobre un caso aprobado por un Verificador<br><strong>Cuando</strong> ordena su reevaluación con su justificación<br><strong>Entonces</strong> el sistema reabre el caso<br><strong>Y</strong> lo asigna a otro Verificador habilitado, distinto del que lo aprobó</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US38</td><td>Verificador senior</td><td>Media</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Suspensión de un Verificador con baja confiabilidad</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero suspender temporalmente la habilitación de un Verificador con baja confiabilidad, para asegurar la calidad de las revisiones.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Suspensión por baja confiabilidad</strong><br><strong>Dado que</strong> un Verificador tiene una confiabilidad menor al umbral definido por la plataforma<br><strong>Cuando</strong> el Verificador senior suspende su habilitación y registra su justificación<br><strong>Entonces</strong> el sistema deja de asignarle casos nuevos<br><strong>Y</strong> reasigna sus casos abiertos a otros Verificadores habilitados<br><br><strong>Escenario 2: Rehabilitación</strong><br><strong>Dado que</strong> un Verificador tiene la habilitación suspendida<br><strong>Cuando</strong> el Verificador senior revisa su desempeño y restablece la habilitación<br><strong>Entonces</strong> el sistema vuelve a asignarle casos de sus habilidades habilitadas<br><strong>Y</strong> conserva su historial de confiabilidad</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US39</td><td>Verificador senior</td><td>Media</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Definición del plazo de actividad de los Verificadores</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero definir el plazo máximo para resolver un caso asignado, para que los estudiantes no esperen indefinidamente una revisión.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Definición del plazo</strong><br><strong>Dado que</strong> el Verificador senior tiene una sesión activa<br><strong>Cuando</strong> define el plazo de resolución de cada plan: 48 horas para el plan mensual y hasta 5 días hábiles para el plan gratuito<br><strong>Entonces</strong> el sistema aplica a los casos asignados a partir de ese momento el plazo que corresponde al plan del estudiante<br><br><strong>Escenario 2: Caso vencido</strong><br><strong>Dado que</strong> un Verificador no resuelve un caso dentro del plazo definido<br><strong>Cuando</strong> el plazo vence<br><strong>Entonces</strong> el sistema reasigna el caso a otro Verificador disponible<br><strong>Y</strong> registra el incumplimiento en la confiabilidad del Verificador original</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US40</td><td>Verificador senior</td><td>Media</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de métricas de la plataforma</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como Verificador senior, quiero consultar métricas agregadas de estudiantes y Verificadores, para tomar decisiones informadas sobre la calidad y la demanda de habilidades.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Métricas de demanda</strong><br><strong>Dado que</strong> existen rutas registradas en la plataforma<br><strong>Cuando</strong> el Verificador senior consulta las métricas de demanda<br><strong>Entonces</strong> el sistema retorna las habilidades más solicitadas y las certificaciones más frecuentes en el periodo seleccionado<br><br><strong>Escenario 2: Métricas de dificultad</strong><br><strong>Dado que</strong> existen intentos de evaluación registrados<br><strong>Cuando</strong> el Verificador senior consulta las métricas de dificultad<br><strong>Entonces</strong> el sistema retorna las habilidades y sub-temas con mayor tasa de desaprobación<br><br><strong>Escenario 3: Métricas de Verificadores</strong><br><strong>Dado que</strong> existen casos resueltos<br><strong>Cuando</strong> el Verificador senior consulta el desempeño de los Verificadores<br><strong>Entonces</strong> el sistema retorna los Verificadores ordenados por confiabilidad<br><strong>Y</strong> el tiempo promedio de resolución de cada uno</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US41</td><td>Visitante</td><td>Alta</td><td>EP09</td></tr>
  <tr><th>Title</th><td colspan="3">Propuesta de valor para estudiantes</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como visitante, quiero conocer cómo SkillSwap me ayuda a demostrar mis habilidades más allá de un certificado, para decidir si la plataforma responde a mi necesidad.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Acceso a la propuesta de valor</strong><br><strong>Dado que</strong> el visitante accede a la landing page<br><strong>Cuando</strong> consulta la información dirigida a estudiantes<br><strong>Entonces</strong> el sitio presenta la propuesta de valor: rutas personalizadas según la meta, validación de certificados, evaluaciones prácticas asistidas por IA y verificación por pares<br><br><strong>Escenario 2: Explicación del proceso</strong><br><strong>Dado que</strong> el visitante consulta la información dirigida a estudiantes<br><strong>Cuando</strong> revisa el funcionamiento de la plataforma<br><strong>Entonces</strong> el sitio describe en orden los pasos: declarar la meta, subir certificados, rendir evaluaciones y obtener la validación final</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US42</td><td>Visitante</td><td>Media</td><td>EP09</td></tr>
  <tr><th>Title</th><td colspan="3">Información para futuros Verificadores</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como visitante, quiero conocer los requisitos y beneficios de ser Verificador, para saber cómo participar y qué reconocimiento puedo obtener.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Requisitos para ser Verificador</strong><br><strong>Dado que</strong> el visitante accede a la landing page<br><strong>Cuando</strong> consulta la información dirigida a Verificadores<br><strong>Entonces</strong> el sitio presenta el requisito de habilitación: haber certificado en su propia ruta la misma habilidad que desea revisar<br><br><strong>Escenario 2: Beneficios del Verificador</strong><br><strong>Dado que</strong> el visitante consulta la información dirigida a Verificadores<br><strong>Cuando</strong> revisa los beneficios<br><strong>Entonces</strong> el sitio explica qué son los SkillCredits, cómo se obtienen y cómo se comparten como credencial verificable</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US43</td><td>Visitante</td><td>Alta</td><td>EP09</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de planes y precios</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como visitante, quiero conocer los planes disponibles, sus precios y beneficios, para evaluar si me basta el plan gratuito o si la suscripción mensual se ajusta a mi presupuesto.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de los planes</strong><br><strong>Dado que</strong> el visitante accede a la landing page<br><strong>Cuando</strong> consulta los planes<br><strong>Entonces</strong> el sitio presenta el plan gratuito (S/ 0), con 1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes a un Verificador, cuyos casos se revisan en hasta 5 días hábiles<br><strong>Y</strong> el plan mensual a S/ 29,90 al mes, IGV incluido, con hasta 3 rutas activas a la vez, sin tope de rutas en total y 10 escalamientos al mes a un Verificador, cuyos casos se revisan en 48 horas<br><strong>Y</strong> aclara que ningún plan compra la aprobación de un certificado<br><br><strong>Escenario 2: Condiciones de la suscripción</strong><br><strong>Dado que</strong> el visitante consulta los planes<br><strong>Cuando</strong> revisa las condiciones<br><strong>Entonces</strong> el sitio informa que la suscripción se gestiona mediante Google Play y puede cancelarse en cualquier momento</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US44</td><td>Visitante</td><td>Alta</td><td>EP09</td></tr>
  <tr><th>Title</th><td colspan="3">Descarga de la aplicación</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como visitante, quiero acceder a la descarga de la aplicación desde la landing page, para instalarla en mi dispositivo sin buscarla manualmente.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Acceso a la descarga</strong><br><strong>Dado que</strong> el visitante accede a la landing page desde cualquier dispositivo<br><strong>Cuando</strong> selecciona "Descarga la app"<br><strong>Entonces</strong> el sitio lo lleva a la sección de descarga, que presenta la aplicación para Android y su disponibilidad en Google Play<br><br><strong>Escenario 2: Requisito de correo institucional</strong><br><strong>Dado que</strong> el visitante solicita descargar la aplicación<br><strong>Cuando</strong> el sitio presenta la información de registro<br><strong>Entonces</strong> el sitio informa que el registro requiere un correo institucional con dominio .edu.pe</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>US45</td><td>Visitante</td><td>Media</td><td>EP09</td></tr>
  <tr><th>Title</th><td colspan="3">Consulta de preguntas frecuentes</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como visitante, quiero consultar las preguntas frecuentes sobre la plataforma, para resolver mis dudas antes de registrarme.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de preguntas frecuentes</strong><br><strong>Dado que</strong> el visitante accede a la landing page<br><strong>Cuando</strong> consulta las preguntas frecuentes<br><strong>Entonces</strong> el sitio presenta respuestas sobre la validación de certificados, el rol del Verificador, los SkillCredits y la suscripción<br><br><strong>Escenario 2: Sitio adaptable</strong><br><strong>Dado que</strong> el visitante accede a la landing page desde un dispositivo móvil<br><strong>Cuando</strong> el sitio se carga<br><strong>Entonces</strong> el contenido se adapta al tamaño del dispositivo y permanece legible sin desplazamiento horizontal</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS01</td><td>Developer</td><td>Alta</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoint de registro de usuarios</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar el endpoint POST /api/v1/authentication/sign-up, para que la aplicación móvil registre usuarios validando el dominio institucional del correo.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Registro exitoso</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/authentication/sign-up está disponible<br><strong>Cuando</strong> se envía un request con username, email institucional y password válidos<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene el UserResource con id, username, email, role e isVerified<br><br><strong>Escenario 2: Dominio no institucional</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/authentication/sign-up está disponible<br><strong>Cuando</strong> se envía un request con un email cuyo dominio no es .edu.pe<br><strong>Entonces</strong> el response tiene el código 400 Bad Request<br><strong>Y</strong> el body contiene el mensaje de error de dominio no permitido<br><br><strong>Escenario 3: Email o username existente</strong><br><strong>Dado que</strong> ya existe un usuario con el mismo email o username<br><strong>Cuando</strong> se envía el request de registro<br><strong>Entonces</strong> el response tiene el código 409 Conflict</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS02</td><td>Developer</td><td>Alta</td><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoint de autenticación con JWT</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar el endpoint POST /api/v1/authentication/sign-in, para que la aplicación móvil obtenga un token JWT con el cual consumir los servicios protegidos.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Credenciales válidas</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/authentication/sign-in está disponible<br><strong>Cuando</strong> se envía un request con username y password válidos<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el AuthenticatedUserResource con el token JWT<br><br><strong>Escenario 2: Credenciales inválidas</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/authentication/sign-in está disponible<br><strong>Cuando</strong> se envía un request con credenciales incorrectas<br><strong>Entonces</strong> el response tiene el código 401 Unauthorized<br><br><strong>Escenario 3: Token ausente en un recurso protegido</strong><br><strong>Dado que</strong> un endpoint requiere autenticación<br><strong>Cuando</strong> se envía un request sin el header Authorization<br><strong>Entonces</strong> el response tiene el código 401 Unauthorized</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS03</td><td>Developer</td><td>Alta</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoint de registro de certificados</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar el endpoint POST /api/v1/certificates, para registrar los certificados (archivo y datos extraídos on-device) y disparar su evaluación de riesgo.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Registro de certificado</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/certificates está disponible<br><strong>Cuando</strong> se envía un formulario multipart/form-data con el archivo (JPG, PNG o PDF de hasta 10 MB) y los datos extraídos on-device<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene el certificado con su status y su evaluación de riesgo<br><br><strong>Escenario 2: Archivo duplicado del mismo propietario</strong><br><strong>Dado que</strong> el propietario ya registró un certificado con el mismo archivo (mismo hash, calculado en el servidor)<br><strong>Cuando</strong> se envía el request<br><strong>Entonces</strong> el response tiene el código 409 Conflict<br><br><strong>Escenario 3: Archivo no permitido</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/certificates está disponible<br><strong>Cuando</strong> se envía un archivo con un formato distinto de JPG, PNG o PDF, o mayor a 10 MB<br><strong>Entonces</strong> el response tiene el código 415 Unsupported Media Type o 413 Payload Too Large, según el caso</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS04</td><td>Developer</td><td>Media</td><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de consulta de certificados</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints GET /api/v1/certificates/{id} y GET /api/v1/certificates?ownerId={ownerId}, para que la aplicación móvil consulte el estado de los certificados.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta por id existente</strong><br><strong>Dado que</strong> existe un certificado con el id solicitado<br><strong>Cuando</strong> se envía un request GET /api/v1/certificates/{id}<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el detalle y el status del certificado<br><br><strong>Escenario 2: Consulta por id inexistente</strong><br><strong>Dado que</strong> no existe un certificado con el id solicitado<br><strong>Cuando</strong> se envía un request GET /api/v1/certificates/{id}<br><strong>Entonces</strong> el response tiene el código 404 Not Found<br><br><strong>Escenario 3: Listado por propietario</strong><br><strong>Dado que</strong> un estudiante registró certificados<br><strong>Cuando</strong> se envía un request GET /api/v1/certificates?ownerId={ownerId}<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene únicamente los certificados de ese propietario</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS05</td><td>Developer</td><td>Alta</td><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de generación y consulta de rutas</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints POST /api/v1/learning-paths y GET /api/v1/learning-paths/{studentId}, para generar la ruta a partir de la meta declarada y consultarla con el estado de sus nodos.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Generación de ruta</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/learning-paths está disponible<br><strong>Cuando</strong> se envía un DeclareGoalResource con una meta interpretable<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene la ruta con sus nodos ordenados y sus estados<br><br><strong>Escenario 2: Meta no interpretable</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/learning-paths está disponible<br><strong>Cuando</strong> se envía una meta sin correspondencia en la taxonomía de habilidades<br><strong>Entonces</strong> el response tiene el código 422 Unprocessable Entity<br><br><strong>Escenario 3: Consulta de ruta inexistente</strong><br><strong>Dado que</strong> el estudiante no tiene una ruta activa<br><strong>Cuando</strong> se envía un request GET /api/v1/learning-paths/{studentId}<br><strong>Entonces</strong> el response tiene el código 404 Not Found</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS06</td><td>Developer</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoint de generación de evaluaciones</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar el endpoint POST /api/v1/path-nodes/{nodeId}/assessment-blueprint, para generar mediante IA la evaluación correspondiente a un nodo disponible.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Nodo disponible</strong><br><strong>Dado que</strong> el nodo {nodeId} tiene estado available<br><strong>Cuando</strong> se envía el request POST /api/v1/path-nodes/{nodeId}/assessment-blueprint<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene el blueprint con sus preguntas sin exponer las respuestas correctas<br><br><strong>Escenario 2: Nodo bloqueado</strong><br><strong>Dado que</strong> el nodo {nodeId} tiene estado locked<br><strong>Cuando</strong> se envía el request<br><strong>Entonces</strong> el response tiene el código 409 Conflict<br><br><strong>Escenario 3: Servicio de IA no disponible</strong><br><strong>Dado que</strong> el servicio de generación de IA no responde<br><strong>Cuando</strong> se envía el request<br><strong>Entonces</strong> el response tiene el código 503 Service Unavailable<br><strong>Y</strong> el nodo mantiene su estado sin cambios</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS07</td><td>Developer</td><td>Alta</td><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de registro de intentos</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints POST /api/v1/assessment-attempts y GET /api/v1/assessment-attempts/{id}, para calificar los intentos en el servidor y abrir un caso de verificación cuando no se aprueban.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Intento aprobado</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/assessment-attempts está disponible<br><strong>Cuando</strong> se envía un SubmitAssessmentAttemptResource cuyas respuestas alcanzan el umbral<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene el score y passed con valor true<br><br><strong>Escenario 2: Intento no aprobado</strong><br><strong>Dado que</strong> el endpoint POST /api/v1/assessment-attempts está disponible<br><strong>Cuando</strong> se envía un request cuyas respuestas no alcanzan el umbral<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene passed con valor false y el id del VerificationCase abierto<br><br><strong>Escenario 3: Blueprint inexistente</strong><br><strong>Dado que</strong> el blueprintId enviado no existe<br><strong>Cuando</strong> se envía el request<br><strong>Entonces</strong> el response tiene el código 404 Not Found</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS08</td><td>Developer</td><td>Alta</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de gestión de casos de verificación</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints de VerificationCasesController y VerifierProfilesController, para que los Verificadores consulten sus casos, gestionen su disponibilidad y registren sus decisiones.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Listado de casos asignados</strong><br><strong>Dado que</strong> un Verificador tiene casos asignados<br><strong>Cuando</strong> el Verificador autenticado envía un request GET /api/v1/verification-cases<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene únicamente los casos asignados a ese Verificador<br><br><strong>Escenario 2: Registro de decisión</strong><br><strong>Dado que</strong> un caso está asignado al Verificador autenticado<br><strong>Cuando</strong> se envía un request PATCH /api/v1/verification-cases/{id}/decision con un ResolveCaseResource completo<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el caso cambia a estado resuelto<br><br><strong>Escenario 3: Decisión de un Verificador no asignado</strong><br><strong>Dado que</strong> un caso no está asignado al Verificador autenticado<br><strong>Cuando</strong> se envía el request PATCH /api/v1/verification-cases/{id}/decision<br><strong>Entonces</strong> el response tiene el código 403 Forbidden<br><br><strong>Escenario 4: Actualización de disponibilidad</strong><br><strong>Dado que</strong> el usuario autenticado tiene un perfil de Verificador<br><strong>Cuando</strong> se envía un request PATCH /api/v1/verifier-profiles/me/availability<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el valor actualizado de available</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS09</td><td>Developer</td><td>Media</td><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de billetera y canje de SkillCredits</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints de WalletsController y CreditTransactionsController, para consultar saldos, historial de movimientos y registrar canjes de SkillCredits.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de saldo</strong><br><strong>Dado que</strong> el usuario tiene una billetera<br><strong>Cuando</strong> se envía un request GET /api/v1/wallets/{userId}<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el balance actual<br><br><strong>Escenario 2: Consulta del historial</strong><br><strong>Dado que</strong> el usuario registra movimientos en su billetera<br><strong>Cuando</strong> se envía un request GET /api/v1/wallets/{userId}/transactions<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene los movimientos del más reciente al más antiguo<br><br><strong>Escenario 3: Canje con saldo suficiente</strong><br><strong>Dado que</strong> el saldo del usuario cubre el costo del beneficio<br><strong>Cuando</strong> se envía un request POST /api/v1/credit-transactions/redeem<br><strong>Entonces</strong> el response tiene el código 201 Created<br><strong>Y</strong> el body contiene la transacción de tipo REDEEMED<br><br><strong>Escenario 4: Canje con saldo insuficiente</strong><br><strong>Dado que</strong> el saldo del usuario no cubre el costo del beneficio<br><strong>Cuando</strong> se envía un request POST /api/v1/credit-transactions/redeem<br><strong>Entonces</strong> el response tiene el código 409 Conflict<br><strong>Y</strong> el balance permanece sin cambios</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS10</td><td>Developer</td><td>Alta</td><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de gestión de disputas</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints de DisputesController, para que el Verificador senior consulte las disputas que tiene asignadas, revise su evidencia y las resuelva.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de la evidencia</strong><br><strong>Dado que</strong> una disputa de revisión de certificado está asignada al Verificador autenticado<br><strong>Cuando</strong> se envía un request GET /api/v1/disputes/{disputeId}/evidence<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene la disputa con los datos extraídos, la evaluación de riesgo y el enlace temporal al archivo del certificado<br><br><strong>Escenario 2: Listado de pendientes por un Verificador</strong><br><strong>Dado que</strong> el usuario autenticado tiene un perfil de Verificador<br><strong>Cuando</strong> se envía un request GET /api/v1/disputes?status=pending<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene únicamente las disputas en estado PENDING asignadas a ese Verificador, de la más antigua a la más reciente<br><br><strong>Escenario 3: Acceso sin ser el revisor asignado</strong><br><strong>Dado que</strong> la disputa no está asignada al usuario autenticado<br><strong>Cuando</strong> se envía un request PATCH /api/v1/disputes/{disputeId}/resolve<br><strong>Entonces</strong> el response tiene el código 403 Forbidden<br><br><strong>Escenario 4: Resolución incoherente</strong><br><strong>Dado que</strong> el outcome enviado no es coherente con el sourceType de la disputa<br><strong>Cuando</strong> se envía el request PATCH /api/v1/disputes/{disputeId}/resolve<br><strong>Entonces</strong> el response tiene el código 400 Bad Request<br><strong>Y</strong> la disputa permanece en estado PENDING</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS11</td><td>Developer</td><td>Media</td><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Endpoints de consulta de reputación</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero implementar los endpoints de VerifierReliabilitiesController y StudentEmployabilityScoresController, para que el cliente consulte la confiabilidad de un Verificador y el Employability Score de un Estudiante.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Consulta de confiabilidad existente</strong><br><strong>Dado que</strong> existe un registro de confiabilidad para el verifierUserId solicitado<br><strong>Cuando</strong> se envía un request GET /api/v1/verifier-reliabilities/{verifierUserId}<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el puntaje vigente<br><br><strong>Escenario 2: Verificador sin casos resueltos todavía</strong><br><strong>Dado que</strong> el verifierUserId solicitado no tiene ningún caso resuelto registrado<br><strong>Cuando</strong> se envía el mismo request<br><strong>Entonces</strong> el response tiene el código 404 Not Found<br><br><strong>Escenario 3: Consulta de empleabilidad existente</strong><br><strong>Dado que</strong> existe un registro de empleabilidad para el studentId solicitado<br><strong>Cuando</strong> se envía un request GET /api/v1/student-employability-scores/{studentId}<br><strong>Entonces</strong> el response tiene el código 200 OK<br><strong>Y</strong> el body contiene el puntaje vigente<br><br><strong>Escenario 4: Consulta sin ser el dueño del recurso</strong><br><strong>Dado que</strong> el usuario autenticado no es el dueño del recurso<br><strong>Cuando</strong> intenta consultar la reputación de otro usuario<br><strong>Entonces</strong> el response tiene el código 403 Forbidden</td></tr>
</table>

<table>
  <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
  <tr><td>TS12</td><td>Developer</td><td>Alta</td><td>EP10</td></tr>
  <tr><th>Title</th><td colspan="3">Despliegue del backend en producción</td></tr>
  <tr><th colspan="4">Description</th></tr>
  <tr><td colspan="4">Como developer, quiero desplegar el backend en un contenedor Docker sobre Render, con la base de datos PostgreSQL administrada, el esquema versionado con Flyway y validado al arrancar, para que el servicio esté disponible públicamente con su documentación OpenAPI.</td></tr>
  <tr><th colspan="4">Acceptance Criteria</th></tr>
  <tr><td colspan="4"><strong>Escenario 1: Arranque con un esquema válido</strong><br><strong>Dado que</strong> la base de datos PostgreSQL está disponible<br><strong>Cuando</strong> el contenedor arranca<br><strong>Entonces</strong> Flyway aplica las migraciones pendientes (V1 a V10)<br><strong>Y</strong> Hibernate valida el esquema (`spring.jpa.hibernate.ddl-auto=validate`) sin modificarlo<br><strong>Y</strong> el endpoint GET /health responde 200 OK<br><br><strong>Escenario 2: Esquema incompleto</strong><br><strong>Dado que</strong> falta una tabla o columna que alguna entidad JPA necesita<br><strong>Cuando</strong> el contenedor arranca<br><strong>Entonces</strong> la validación de Hibernate falla y la aplicación no acepta tráfico, registrando el error en el log<br><br><strong>Escenario 3: Conversión de la URL de la base de datos</strong><br><strong>Dado que</strong> la variable DATABASE_URL tiene el formato postgres://usuario:clave@host:5432/db que entrega Render<br><strong>Cuando</strong> el contenedor arranca<br><strong>Entonces</strong> el sistema la convierte a una URL JDBC y se conecta a la base de datos<br><br><strong>Escenario 4: Configuración obligatoria ausente</strong><br><strong>Dado que</strong> no está definida TOKEN_SETTINGS_SECRET, GEMINI_API_KEY o alguna de las credenciales CLOUDINARY_*<br><strong>Cuando</strong> el contenedor arranca<br><strong>Entonces</strong> la aplicación no inicia y el log indica qué configuración falta</td></tr>
</table>

*Nota.* Elaboración propia.


### 2.4.2. Impact Mapping

El Impact Mapping de SkillSwap se elaboró en UXPressia con el objetivo de conectar los objetivos del negocio con los cambios de comportamiento que se esperan de los usuarios y con las funcionalidades que la aplicación debe ofrecer para provocarlos. Se definieron cuatro **Business Goals** bajo los criterios SMART, cuyas métricas se derivan de las hipótesis planteadas en la sección 1.2.2.3. Como **Actors** se emplearon los User Personas identificados en la sección 2.3.1 —Valeria Ramos (Estudiante), Rodrigo Castillo (Verificador)—, respondiendo a la pregunta *¿quiénes nos ayudarán a lograr la meta?*. La columna **Impacts** describe cómo se espera que cada persona cambie su comportamiento, la columna **Deliverables** responde a *¿qué puede hacer la plataforma para provocar esos impactos?*, y la columna **User Stories** reúne las historias de la sección 2.4.1 que permiten construir cada deliverable.

**Business Goal 1: Adopción y suscripción**

*Alcanzar 2,000 estudiantes universitarios con suscripción mensual activa en los primeros 6 meses desde el lanzamiento de la aplicación.*

Esta meta asegura el ingreso recurrente principal del modelo de negocio. Para lograrla se necesita que Valeria Ramos se registre con su correo institucional y se suscriba al plan mensual, y que declare su meta de aprendizaje y siga la ruta que la plataforma le propone. Para provocar estos comportamientos, la plataforma ofrece el registro con validación de dominio `.edu.pe`, la suscripción mediante Google Play Billing, el intérprete de metas en lenguaje natural y la ruta de aprendizaje personalizada (US01, US05, US06 y US08).

**Figura 25**

*Impact Map - Business Goal 1: Adopción y suscripción*

<p align="center">
  <img src="public/assets/images-doc/impact-map-1.png" alt="Impact Map - Adopción y suscripción" width="900">
</p>

*Nota.* Elaboración propia.

**Business Goal 2: Validación práctica de habilidades**

*Lograr que el 70 % de los estudiantes que suben un certificado rindan su evaluación práctica y que menos del 30 % de los intentos requiera la intervención de un Verificador, durante los primeros 6 meses de operación.*

Esta meta mide la propuesta de valor central de SkillSwap: que el certificado se complemente con una demostración práctica y que la IA resuelva la mayoría de los casos sin intervención humana. Se espera que Valeria suba sus certificados como evidencia, rinda voluntariamente la evaluación práctica de cada uno, refuerce solo el sub-tema en el que falla y, al completar su ruta, demuestre su dominio integral. Los deliverables asociados son la extracción automática de datos con ML Kit, la validación de correspondencia entre certificado y habilidad, los quizzes generados por IA con calificación inmediata, el diagnóstico del sub-tema débil y la demostración final supervisada por un verificador (US13, US15, US17, US18, US20 y US29).

**Figura 26**

*Impact Map - Business Goal 2: Validación práctica de habilidades*

<p align="center">
  <img src="public/assets/images-doc/impact-map-2.png" alt="Impact Map - Validación práctica de habilidades" width="900">
</p>

*Nota.* Elaboración propia.

**Business Goal 3: Red de Verificadores**

*Contar con 150 Verificadores habilitados que resuelvan el 85 % de los casos escalados por Estudiantes del plan mensual en menos de 48 horas, dentro de los primeros 8 meses desde el lanzamiento.*

La capacidad de la plataforma para resolver los casos que la IA no puede cerrar depende de contar con suficientes Verificadores activos. Para ello se necesita que Rodrigo Castillo se habilite al completar en su propia ruta el nodo de la habilidad, resuelva a tiempo los casos que se le asignan y se mantenga activo gracias al reconocimiento profesional. La plataforma lo impulsa mediante la habilitación por nodo de habilidad, la asignación automática de casos por afinidad, la rúbrica estructurada de evaluación, la acreditación de SkillCredits y la credencial verificable para compartir en LinkedIn (US22, US24, US25, US30 y US33).

**Figura 27**

*Impact Map - Business Goal 3: Red de Verificadores*

<p align="center">
  <img src="public/assets/images-doc/impact-map-3.png" alt="Impact Map - Red de Verificadores" width="900">
</p>

*Nota.* Elaboración propia.

**Business Goal 4: Calidad y confianza del proceso**

*Mantener la tasa de disputas y reevaluaciones por debajo del 5 % del total de evaluaciones realizadas y resolver el 90 % de las disputas en menos de 72 horas, durante el primer año de operación.*

Esta meta protege la credibilidad de todo lo que se certifica en la plataforma. Involucra a dos actores: Rodrigo Castillo, de quien se espera que, como Verificador senior, resuelva a tiempo las disputas pendientes y controle la calidad de las evaluaciones y de otros Verificadores; y Valeria, de quien se espera que confíe en el proceso y apele solo cuando lo considere necesario. Los deliverables correspondientes son el panel de disputas con evidencia, la revisión de los casos apelados por un Verificador distinto del original, la reevaluación de resultados aprobados, la suspensión temporal de Verificadores con baja confiabilidad y la apelación de una decisión (US34, US36, US37, US38 y US27).

**Figura 28**

*Impact Map - Business Goal 4: Calidad y confianza del proceso*

<p align="center">
  <img src="public/assets/images-doc/impact-map-4.png" alt="Impact Map - Calidad y confianza del proceso" width="900">
</p>

*Nota.* Elaboración propia.

En conjunto, los cuatro Impact Maps muestran cómo cada funcionalidad de la aplicación contribuye a un objetivo de negocio medible: los dos primeros se centran en el Estudiante como fuente de ingresos y como beneficiario de la validación práctica, mientras que los dos últimos aseguran que el segmento que valida el conocimiento —los Verificadores— sostenga la capacidad y la confiabilidad del proceso.

### 2.4.3. Product Backlog

El Product Backlog de SkillSwap reúne las 57 historias definidas en la sección 2.4.1, ordenadas según el valor que aportan al negocio y estimadas en Story Points con la escala de Fibonacci (1, 2, 3, 5 y 8), donde el valor refleja la complejidad, el esfuerzo y la incertidumbre relativa de cada historia.

La estimación total del Product Backlog asciende a **211 Story Points**. De ellos, **154 SP (73%)**, correspondientes a 44 de las 57 historias, se completaron en el Sprint 1 (TB1). Las 13 historias restantes (57 SP) no tienen Sprint asignado, lo que se indica con un guion (—) en la columna Sprint: cuatro corresponden a funcionalidades exclusivas del cliente móvil (US03, US10, US11 y US21) y nueve a funcionalidades que el backend no implementa (US07, US19, US20, US28, US29, US33, US37, US38 y US40).

**Tabla 10**

*Product Backlog*

| # Orden | User Story Id | Título | Story Points (1 / 2 / 3 / 5 / 8) | Sprint |
| :---: | :---: | :--- | :---: | :---: |
| 1 | US41 | Propuesta de valor para estudiantes | 2 | Sprint 1 |
| 2 | US43 | Consulta de planes y precios | 2 | Sprint 1 |
| 3 | US44 | Descarga de la aplicación | 1 | Sprint 1 |
| 4 | US42 | Información para futuros Verificadores | 2 | Sprint 1 |
| 5 | US45 | Consulta de preguntas frecuentes | 1 | Sprint 1 |
| 6 | TS05 | Endpoints de generación y consulta de rutas | 5 | Sprint 1 |
| 7 | US06 | Declaración de la meta en lenguaje natural | 8 | Sprint 1 |
| 8 | US08 | Consulta de la ruta de aprendizaje | 3 | Sprint 1 |
| 9 | TS03 | Endpoint de registro de certificados | 5 | Sprint 1 |
| 10 | US12 | Carga del certificado desde un archivo | 3 | Sprint 1 |
| 11 | US11 | Captura del certificado con la cámara | 3 | — |
| 12 | US13 | Extracción automática de datos del certificado | 8 | Sprint 1 |
| 13 | US15 | Correspondencia del certificado con la habilidad | 5 | Sprint 1 |
| 14 | TS06 | Endpoint de generación de evaluaciones | 5 | Sprint 1 |
| 15 | US17 | Generación del quiz de un nodo | 5 | Sprint 1 |
| 16 | TS07 | Endpoints de registro de intentos | 3 | Sprint 1 |
| 17 | US18 | Resolución del quiz con calificación en el servidor | 3 | Sprint 1 |
| 18 | US20 | Identificación del sub-tema débil | 5 | — |
| 19 | US05 | Suscripción al plan mensual | 5 | Sprint 1 |
| 20 | US09 | Reconocimiento de habilidades ya certificadas | 3 | Sprint 1 |
| 21 | US14 | Detección de certificados duplicados | 3 | Sprint 1 |
| 22 | TS04 | Endpoints de consulta de certificados | 2 | Sprint 1 |
| 23 | US16 | Consulta del estado de verificación | 3 | Sprint 1 |
| 24 | TS08 | Endpoints de gestión de casos de verificación | 5 | Sprint 1 |
| 25 | US24 | Asignación automática de casos por disponibilidad | 8 | Sprint 1 |
| 26 | US25 | Revisión del caso con notas de rúbrica | 5 | Sprint 1 |
| 27 | US22 | Habilitación como Verificador | 5 | Sprint 1 |
| 28 | US23 | Gestión de disponibilidad | 2 | Sprint 1 |
| 29 | US26 | Aporte de evidencia adicional | 2 | Sprint 1 |
| 30 | TS01 | Endpoint de registro de usuarios | 3 | Sprint 1 |
| 31 | US01 | Registro con correo institucional | 3 | Sprint 1 |
| 32 | TS02 | Endpoint de autenticación con JWT | 2 | Sprint 1 |
| 33 | US02 | Inicio de sesión | 2 | Sprint 1 |
| 34 | US19 | Entrega de un miniproyecto | 8 | — |
| 35 | TS10 | Endpoints de gestión de disputas | 5 | Sprint 1 |
| 36 | US34 | Consulta de disputas pendientes | 3 | Sprint 1 |
| 37 | US35 | Resolución de certificados sospechosos | 3 | Sprint 1 |
| 38 | US27 | Apelación de la decisión del Verificador | 3 | Sprint 1 |
| 39 | US36 | Revisión de casos apelados | 3 | Sprint 1 |
| 40 | US37 | Reevaluación de un resultado aprobado | 3 | — |
| 41 | TS09 | Endpoints de billetera y canje de SkillCredits | 3 | Sprint 1 |
| 42 | US30 | Acreditación de SkillCredits por caso resuelto | 3 | Sprint 1 |
| 43 | US31 | Consulta de billetera e historial | 2 | Sprint 1 |
| 44 | US33 | Compartir logros en LinkedIn | 3 | — |
| 45 | US38 | Suspensión de un Verificador con baja confiabilidad | 3 | — |
| 46 | US39 | Definición del plazo de actividad de los Verificadores | 3 | Sprint 1 |
| 47 | US40 | Consulta de métricas de la plataforma | 5 | — |
| 48 | US32 | Canje de SkillCredits en la tienda | 3 | Sprint 1 |
| 49 | US04 | Configuración del perfil de intereses | 2 | Sprint 1 |
| 50 | US07 | Confirmación de la habilidad interpretada | 3 | — |
| 51 | US10 | Consulta de la ruta sin conexión | 5 | — |
| 52 | US21 | Conservación del avance ante pérdida de conexión | 5 | — |
| 53 | US03 | Acceso mediante biometría del dispositivo | 3 | — |
| 54 | US28 | Programación de la demostración final | 3 | — |
| 55 | US29 | Demostración final por video | 8 | — |
| 56 | TS11 | Endpoints de consulta de reputación | 2 | Sprint 1 |
| 57 | TS12 | Despliegue del backend en producción | 5 | Sprint 1 |


*Nota.* Elaboración propia.

El Product Backlog se gestiona en Trello, en un tablero público con la lista Sprint 1. Cada tarjeta conserva el orden, el identificador, el título y los Story Points de la tabla anterior, e incluye en su descripción la historia, la prioridad, el usuario y el Epic.

**Figura 29**

*Product Backlog de SkillSwap en Trello*

<p align="center">
  <img src="public/assets/images-doc/product-backlog-trello.png" alt="Product Backlog de SkillSwap en Trello" width="500">
</p>

*Nota.* Tablero público del Product Backlog en Trello, con la lista Sprint 1 y las tarjetas de cada historia con su identificador, título y Story Points. Elaboración propia.

**URL público del Product Backlog (Trello):** [https://trello.com/b/sTMGwnPf/skillswap-product-backlog](https://trello.com/b/sTMGwnPf/skillswap-product-backlog)


## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming

El EventStorming se desarrolló siguiendo los diez pasos propuestos en el material del curso, a partir del modelo de negocio descrito en el Capítulo I. El objetivo fue identificar los eventos del dominio de SkillSwap, ordenarlos en el tiempo, reconocer los puntos críticos del proceso y agrupar los agregados resultantes en bounded contexts candidatos.

**Paso 1. Unstructured Exploration**

Las figuras de los pasos 1 a 8 registran el modelo tal como se trabajó en la sesión; las diferencias con el modelo implementado en el Sprint 1 se resumen al final de esta sección, en «Ajustes del modelo posteriores a la sesión».

En este primer paso se realizó una lluvia de ideas de los eventos de dominio relevantes para SkillSwap, redactados en tiempo pasado porque describen hechos que ya ocurrieron en el negocio. Se identificaron 64 eventos, que abarcan el registro y la suscripción del Estudiante, la generación de la ruta de certificación, el registro de certificados, la evaluación mediante quizzes y entregables prácticos, la revisión por parte de los Verificadores, la demostración final, la emisión de la certificación, la moderación de decisiones y la habilitación de nuevos Verificadores. En esta etapa los eventos se presentan sin orden, ya que el propósito es explorar el dominio antes de estructurarlo.

**Figura 30**

*EventStorming, paso 1: Unstructured Exploration*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-01-exploracion.png" alt="EventStorming paso 1: eventos de dominio de SkillSwap sin orden" width="900">
</p>

*Nota.* Eventos de dominio de SkillSwap identificados durante la exploración inicial, presentados sin orden cronológico. Elaboración propia.

**Paso 2. Timelines**

En el segundo paso, los eventos identificados se ordenaron en el tiempo. Por la cantidad de eventos, la línea de tiempo se organizó en carriles, uno por actor o ciclo de vida (Suscripción, Estudiante, Verificador y Moderación), y se dividió en tres fases del proceso. El carril de Moderación agrupa las actividades de supervisión del proceso, que en el diseño final realiza el Verificador senior. En cada carril, la fila superior muestra el camino exitoso y debajo se ubican los escenarios alternativos que se desprenden de cada evento.

No se modelaron caminos separados para el plan gratuito y el premium, porque los eventos son los mismos en ambos: lo que cambia son los límites de rutas y de escalamientos, que aparecen como ramas, y la duración de las esperas y los plazos de revisión. Mantener un solo camino deja a la vista que ningún plan ofrece más oportunidades de aprobar.

La primera fase abarca el registro, la suscripción y el registro de certificados. Cuando el Estudiante verifica su correo, se le asigna el plan gratuito, que puede evolucionar a una suscripción premium con su propio ciclo de cobro, renovación, rechazo del pago o cancelación. Luego declara su objetivo, recibe su ruta de certificación y sube sus certificados; si el riesgo documental resulta alto, el certificado se marca como sospechoso y su revisión pasa a Moderación.

**Figura 31**

*EventStorming, paso 2: Timelines (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-02a-registro.png" alt="EventStorming paso 2: registro, suscripción y certificados" width="900">
</p>

*Nota.* Línea de tiempo en carriles del registro, la suscripción y el registro de certificados. Las líneas punteadas indican el traspaso entre carriles. Elaboración propia.

La segunda fase corresponde a la evaluación de los nodos de la ruta. En los nodos de quiz, un intento desaprobado permite volver a intentarlo con preguntas nuevas hasta agotar los tres intentos, tras lo cual comienza un periodo de espera. En los nodos prácticos, el entregable enviado abre un caso de verificación que toma un Verificador en su propio carril; si el plazo de revisión vence, el caso se reasigna. La calificación que el Verificador registra por criterio es la que determina si el entregable se aprueba o si requiere cambios, en cuyo caso el Estudiante recibe los criterios no cumplidos y puede reenviar su entrega. Por cada revisión, el Verificador recibe SkillCredits, apruebe o rechace, y su confiabilidad se recalcula. Si el Estudiante reporta una decisión, se abre una disputa que resuelve Moderación; cuando la decisión se revierte, se aplica una sanción y la confiabilidad del Verificador vuelve a calcularse.

**Figura 32**

*EventStorming, paso 2: Timelines (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-02b-evaluacion.png" alt="EventStorming paso 2: evaluación de los nodos" width="900">
</p>

*Nota.* Línea de tiempo en carriles de la evaluación de los nodos de quiz y de los nodos prácticos. Elaboración propia.

La tercera fase cubre la demostración final, la certificación y la habilitación de nuevos Verificadores. Al completar la ruta, el Estudiante envía su demostración final, que califica un Verificador; esa calificación determina si la demostración se aprueba y se emite la certificación, o si se devuelven los criterios no cumplidos. Si el Estudiante reporta la calificación, se asigna un segundo revisor. La certificación emitida es, además, el requisito para que el Estudiante quede habilitado como Verificador para esa habilidad.

**Figura 33**

*EventStorming, paso 2: Timelines (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-02c-certificacion.png" alt="EventStorming paso 2: demostración final, certificación y nuevo Verificador" width="900">
</p>

*Nota.* Línea de tiempo en carriles de la demostración final, la emisión de la certificación y la habilitación de un Verificador. Elaboración propia.

**Paso 3. Pain Points**

En el tercer paso se revisó la línea de tiempo para identificar los puntos críticos del proceso: dudas, reglas que aún no están definidas y riesgos que el equipo debe resolver antes de implementar. Cada punto crítico se registró como un rombo rosado unido al evento en el que aparece. Se identificaron 15 puntos críticos, repartidos en las mismas tres fases del paso anterior.

En la fase de registro, suscripción y certificados, las dudas se concentran en la generación de la ruta y en la lectura de los certificados: cuántos nodos prácticos debe incluir como mínimo una ruta, qué ocurre si el OCR no logra leer un certificado y si un certificado marcado como sospechoso bloquea el avance del Estudiante mientras Moderación lo revisa. En la suscripción, surgieron dudas sobre los límites exactos del plan gratuito, que luego se fijaron en 1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes a un Verificador, y sobre si existe un periodo de gracia cuando falla el cobro.

**Figura 34**

*EventStorming, paso 3: Pain Points (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-03a-registro.png" alt="EventStorming paso 3: puntos críticos del registro, la suscripción y los certificados" width="900">
</p>

*Nota.* Puntos críticos, representados como rombos rosados, identificados sobre la línea de tiempo del registro, la suscripción y el registro de certificados. Elaboración propia.

En la fase de evaluación de los nodos aparece el mayor número de puntos críticos. En los quizzes, preocupa cómo controlar la calidad de las preguntas generadas por la inteligencia artificial, si se requiere un certificado para rendir un nodo y cuánto dura el periodo de espera en cada plan. En la revisión humana, quedan abiertas la situación del Estudiante del plan gratuito que alcanza su límite de escalamientos, el tratamiento de un Verificador que deja vencer varios plazos, los umbrales de cada rango de Verificador, medidos en casos resueltos, los umbrales de rango y confiabilidad que habilitan al Verificador senior y el destino de los casos que tenía asignados un Verificador sancionado. Más adelante, el equipo cerró tres de estas dudas: el Estudiante del plan gratuito que alcanza su límite ve la pantalla "Alcanzaste el límite de tu plan", con la opción de pasar al plan mensual o continuar gratis; los rangos son Bronce (0 a 29 casos resueltos), Plata (30 a 99) y Oro (100 o más); y el Verificador senior es el que tiene rango Oro y una confiabilidad de 90 o más, en la escala de 0 a 100.

**Figura 35**

*EventStorming, paso 3: Pain Points (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-03b-evaluacion.png" alt="EventStorming paso 3: puntos críticos de la evaluación de los nodos" width="900">
</p>

*Nota.* Puntos críticos, representados como rombos rosados, identificados sobre la línea de tiempo de la evaluación de los nodos de quiz y de los nodos prácticos. Elaboración propia.

En la fase de demostración final, certificación y nuevo Verificador, los puntos críticos se relacionan con la disponibilidad y la imparcialidad de la revisión: qué ocurre si no hay Verificadores habilitados para la habilidad, quién define los criterios y el umbral de aprobación de la rúbrica y si un Verificador puede revisar a alguien que conoce. Estas tres dudas aplican también a la revisión de los nodos prácticos, pero se ubicaron en esta fase para no recargar la figura anterior. Por último, quedó por definir qué requisito habilita a un Estudiante como Verificador.

**Figura 36**

*EventStorming, paso 3: Pain Points (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-03c-certificacion.png" alt="EventStorming paso 3: puntos críticos de la demostración final, la certificación y el nuevo Verificador" width="900">
</p>

*Nota.* Puntos críticos, representados como rombos rosados, identificados sobre la línea de tiempo de la demostración final, la emisión de la certificación y la habilitación de un Verificador. Elaboración propia.

**Paso 4. Pivotal Points**

En el cuarto paso se identificaron los eventos pivotales, es decir, aquellos después de los cuales el proceso entra en una fase distinta. Cada uno se marcó con una línea vertical ubicada inmediatamente después del evento, en su carril. Se identificaron seis eventos pivotales.

En la fase de registro, suscripción y certificados hay dos. El primero es "Correo verificado": a partir de ese momento el usuario deja de ser anónimo y puede operar en la plataforma. El segundo es "Ruta de certificación generada", que cierra el diagnóstico del objetivo y da inicio al recorrido de aprendizaje.

**Figura 37**

*EventStorming, paso 4: Pivotal Points (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-04a-registro.png" alt="EventStorming paso 4: eventos pivotales del registro, la suscripción y los certificados" width="900">
</p>

*Nota.* Las líneas verticales marcan los eventos pivotales que separan el registro, el diagnóstico del objetivo y el inicio del recorrido de aprendizaje. Elaboración propia.

En la fase de evaluación de los nodos, el evento pivotal es "Caso de verificación abierto". Hasta ese punto la evaluación es automática, porque los quizzes se corrigen solos; desde ese punto interviene un Verificador. Este cambio se repite en cada nodo práctico de la ruta.

**Figura 38**

*EventStorming, paso 4: Pivotal Points (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-04b-evaluacion.png" alt="EventStorming paso 4: evento pivotal de la evaluación de los nodos" width="900">
</p>

*Nota.* La línea vertical marca el paso de la evaluación automática a la revisión humana en los nodos prácticos. Elaboración propia.

En la fase de demostración final, certificación y nuevo Verificador hay tres eventos pivotales. "Ruta completada" cierra la evaluación de los nodos y habilita la demostración final. "Certificación emitida" cierra el recorrido del Estudiante, porque la habilidad queda certificada. Por último, "Verificador habilitado para la habilidad" marca el cambio de rol: desde ese momento, el Estudiante puede revisar el trabajo de otros.

**Figura 39**

*EventStorming, paso 4: Pivotal Points (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-04c-certificacion.png" alt="EventStorming paso 4: eventos pivotales de la demostración final, la certificación y el nuevo Verificador" width="900">
</p>

*Nota.* Las líneas verticales marcan el inicio de la demostración final, la emisión de la certificación y la habilitación del Estudiante como Verificador. Elaboración propia.

**Paso 5. Commands**

En el quinto paso se identificaron los comandos, es decir, las decisiones que producen cada evento. Cada comando se registró en un post-it azul a la izquierda del evento que dispara, con el actor que lo ejecuta en un post-it amarillo encima. En este paso solo se incluyen los comandos que ejecuta una persona; los que ejecuta el sistema se incorporan en el paso siguiente, junto con las políticas. El modelo tiene dos actores, el Estudiante y el Verificador. En esta sesión, la moderación se representó como un panel externo a la aplicación; en el diseño final, esas decisiones las toma el Verificador desde la propia aplicación, por lo que no se agrega un tercer actor.

En la fase de registro, suscripción y certificados, todos los comandos los ejecuta el Estudiante: registrarse, verificar su correo, iniciar sesión, declarar su objetivo y subir certificados, además de iniciar o cancelar la suscripción premium. La suscripción vencida y la suscripción cancelada son desenlaces independientes: la primera se produce cuando falla el cobro y la segunda, cuando el Estudiante lo decide.

**Figura 40**

*EventStorming, paso 5: Commands (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-05a-registro.png" alt="EventStorming paso 5: Commands, registro, suscripción y certificados" width="900">
</p>

*Nota.* Comandos, en azul, y actores, en amarillo, del registro, la suscripción y el registro de certificados. Elaboración propia.

En la evaluación de los nodos, el Estudiante envía los intentos de quiz, los entregables y sus reenvíos, y puede calificar la revisión recibida o reportar la decisión. El único comando del Verificador en esta fase es calificar el entregable: el Verificador no decide si el entregable se aprueba, sino que registra la calificación de cada criterio de la rúbrica.

**Figura 41**

*EventStorming, paso 5: Commands (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-05b-evaluacion.png" alt="EventStorming paso 5: Commands, evaluación de los nodos" width="900">
</p>

*Nota.* Comandos, en azul, y actores, en amarillo, de la evaluación de los nodos de quiz y de los nodos prácticos. Elaboración propia.

En la fase final, el Estudiante envía la demostración final y puede reportar su calificación, y el Verificador la califica con la rúbrica. Los comandos de habilitación como Verificador los ejecuta el Estudiante, aunque aparecen en el carril del Verificador, porque todavía no está habilitado como tal. Una vez habilitado, el Verificador actualiza su disponibilidad.

**Figura 42**

*EventStorming, paso 5: Commands (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-05c-certificacion.png" alt="EventStorming paso 5: Commands, demostración final, certificación y nuevo Verificador" width="900">
</p>

*Nota.* Comandos, en azul, y actores, en amarillo, de la demostración final, la emisión de la certificación y la habilitación de un Verificador. Elaboración propia.

**Paso 6. Policies**

En el sexto paso se agregaron las políticas, que representan las reacciones automáticas del sistema: cuando ocurre un evento, el sistema ejecuta un comando sin que intervenga una persona. Cada política se registró en un post-it morado sobre el comando que ejecuta. Con este paso aparecen en el tablero los comandos del sistema, que completan la cadena entre los eventos.

En la primera fase, las políticas envían el correo de verificación cuando el Estudiante se registra, asignan el plan gratuito cuando verifica su correo y generan la ruta de certificación cuando declara un objetivo. Cada certificado subido pasa por una cadena automática: se extraen sus datos, se evalúa el riesgo documental y, según el resultado, se registra o se escala a Moderación. En la suscripción, el cobro se ejecuta al inicio de cada periodo mensual y, si el pago se rechaza, la suscripción vence.

**Figura 43**

*EventStorming, paso 6: Policies (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-06a-registro.png" alt="EventStorming paso 6: Policies, registro, suscripción y certificados" width="900">
</p>

*Nota.* Políticas, en morado, y comandos del sistema del registro, la suscripción y el registro de certificados. Elaboración propia.

En la evaluación se concentran las reglas de negocio del modelo. El quiz se genera con preguntas nuevas al iniciar el nodo o al terminar el periodo de espera, y al agotar los intentos comienza la espera. Al enviar un entregable se abre un caso, siempre que el plan tenga escalamientos disponibles; al abrir el caso se asigna un Verificador y, si vence el plazo, el caso se reasigna. La política central es el cálculo de la aprobación: cuando el Verificador califica el entregable, el sistema calcula el resultado contra el umbral de la rúbrica y, si no lo alcanza, devuelve los criterios no cumplidos. Cada calificación acredita SkillCredits al Verificador según el tipo de caso (40 por un miniproyecto y 25 por un quiz), apruebe o rechace, y recalcula su confiabilidad; cuando la cantidad de casos resueltos por el Verificador cruza un umbral (30 casos para Plata y 100 para Oro), se otorga el rango correspondiente.

**Figura 44**

*EventStorming, paso 6: Policies (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-06b-evaluacion.png" alt="EventStorming paso 6: Policies, evaluación de los nodos" width="900">
</p>

*Nota.* Políticas, en morado, y comandos del sistema de la evaluación de los nodos. Elaboración propia.

En la fase final, completar todos los nodos completa la ruta y habilita la demostración final. La aprobación de la demostración también la calcula el sistema a partir de la calificación del Verificador y, cuando se aprueba, se emite la certificación. Si el Estudiante reporta la calificación, se asigna un segundo revisor. Por último, cumplir el requisito de habilitación convierte al Estudiante en Verificador para esa habilidad.

**Figura 45**

*EventStorming, paso 6: Policies (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-06c-certificacion.png" alt="EventStorming paso 6: Policies, demostración final, certificación y nuevo Verificador" width="900">
</p>

*Nota.* Políticas, en morado, y comandos del sistema de la demostración final, la emisión de la certificación y la habilitación de un Verificador. Elaboración propia.

**Paso 7. Read Models**

En el séptimo paso se identificaron los read models, es decir, la información que cada actor consulta antes de ejecutar un comando. Cada read model se registró en un post-it verde junto al comando que apoya.

En la primera fase, el Estudiante consulta su plan y sus límites antes de declarar un objetivo o de pasar a premium, el estado de sus certificados antes de subir uno nuevo y el estado de su suscripción antes de cancelarla.

**Figura 46**

*EventStorming, paso 7: Read Models (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-07a-registro.png" alt="EventStorming paso 7: Read Models, registro, suscripción y certificados" width="900">
</p>

*Nota.* Read models, en verde, que consulta el Estudiante durante el registro, la suscripción y el registro de certificados. Elaboración propia.

En la evaluación, el Estudiante consulta el quiz, el enunciado práctico con su rúbrica y los criterios no cumplidos antes de reenviar un entregable o de reportar una decisión. Antes de calificar una revisión, consulta el perfil público del Verificador. El Verificador, por su parte, trabaja sobre su cola de casos con plazos y sobre el formulario de la rúbrica.

**Figura 47**

*EventStorming, paso 7: Read Models (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-07b-evaluacion.png" alt="EventStorming paso 7: Read Models, evaluación de los nodos" width="900">
</p>

*Nota.* Read models, en verde, que consultan el Estudiante y el Verificador durante la evaluación de los nodos. Elaboración propia.

En la fase final, el Estudiante consulta el enunciado y la rúbrica de la demostración antes de enviarla, y su elegibilidad para habilitarse como Verificador. El Verificador califica la demostración sobre el formulario de la rúbrica.

**Figura 48**

*EventStorming, paso 7: Read Models (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-07c-certificacion.png" alt="EventStorming paso 7: Read Models, demostración final, certificación y nuevo Verificador" width="900">
</p>

*Nota.* Read models, en verde, de la demostración final y la elegibilidad para habilitarse como Verificador. Elaboración propia.

**Paso 8. External Systems**

En el octavo paso se incorporaron los sistemas externos, representados con post-its rojos. Algunos reciben órdenes del sistema, otros son notificados cuando ocurre un evento y uno de ellos, el panel de moderación, ejecuta comandos sobre el sistema. Este panel corresponde al modelado inicial de la sesión; en el diseño final sus funciones forman parte del rol de Verificador dentro de la aplicación.

En la primera fase intervienen el servicio de correo, que envía la verificación; el LLM, que interpreta la meta y selecciona habilidades del catálogo interno para generar la ruta de certificación; Cloudinary, que almacena los certificados; ML Kit, que extrae sus datos mediante OCR en el dispositivo, y Google Play Billing (vía RevenueCat), que ejecuta el cobro de la suscripción. El panel de moderación aparece como el sistema que resuelve la revisión de un certificado sospechoso. A partir de las habilidades que selecciona el LLM, el backend calcula la brecha y ordena los nodos según sus prerrequisitos; si el LLM no responde, recurre a la comparación por palabras clave sobre el mismo catálogo.

**Figura 49**

*EventStorming, paso 8: External Systems (registro, suscripción y certificados)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-08a-registro.png" alt="EventStorming paso 8: External Systems, registro, suscripción y certificados" width="900">
</p>

*Nota.* Sistemas externos, en rojo, que intervienen en el registro, la suscripción y el registro de certificados. Elaboración propia.

En la evaluación, el LLM genera las preguntas de cada intento, los enunciados prácticos y el enunciado nuevo cuando un nodo se reactiva. Cloudinary almacena los entregables y el servicio de correo notifica los criterios no cumplidos. La resolución de disputas y la aplicación de sanciones, apoyadas en una vista de reportes, disputas y confiabilidad, se modelaron en la sesión como un panel de moderación externo; en el diseño final las ejecuta el Verificador senior desde su panel de supervisión.

**Figura 50**

*EventStorming, paso 8: External Systems (evaluación de los nodos)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-08b-evaluacion.png" alt="EventStorming paso 8: External Systems, evaluación de los nodos" width="900">
</p>

*Nota.* Sistemas externos, en rojo, que intervienen en la evaluación de los nodos y en la moderación. Elaboración propia.

En la fase final, Cloudinary almacena la demostración final y el servicio de correo notifica tanto los criterios no cumplidos como la emisión de la certificación.

**Figura 51**

*EventStorming, paso 8: External Systems (demostración final, certificación y nuevo Verificador)*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-08c-certificacion.png" alt="EventStorming paso 8: External Systems, demostración final, certificación y nuevo Verificador" width="900">
</p>

*Nota.* Sistemas externos, en rojo, que intervienen en la demostración final y la emisión de la certificación. Elaboración propia.

**Paso 9. Aggregates**

En el noveno paso, los comandos y los eventos se agruparon en agregados, es decir, en los objetos del dominio que reciben los comandos, protegen las reglas de negocio y producen los eventos. Se identificaron 12 agregados. En la figura, cada agregado aparece como un post-it alto de color amarillo pálido, con los comandos que recibe a la izquierda, los eventos que produce a la derecha y su regla principal debajo.

Los agregados con más responsabilidad son VerificationCase, que concentra la revisión humana de los entregables y de la demostración final, incluidas la asignación, el plazo, el cálculo de la aprobación y las reentregas, y LearningPath, que gestiona la ruta y el avance de sus nodos. Certificate se mantiene separado de la ruta, porque registrar un certificado no completa ningún nodo (solo un certificado validado por un Verificador completa el nodo de la habilidad que cubre), y SkillCertification se modeló como un agregado propio, porque solo puede emitirse con la ruta completada y la demostración final aprobada. Wallet refleja que los SkillCredits solo se ganan revisando, que no se compran con dinero ni se transfieren y que solo se descuentan al canjearse por un beneficio.

**Figura 52**

*EventStorming, paso 9: Aggregates*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-09-agregados.png" alt="EventStorming paso 9: agregados de SkillSwap con sus comandos y eventos" width="900">
</p>

*Nota.* Agregados de SkillSwap, en amarillo pálido, con los comandos que reciben, los eventos que producen y la regla principal de cada uno. Elaboración propia.

**Paso 10. Bounded Contexts**

En el último paso, los agregados se agruparon en bounded contexts candidatos, según la cercanía de su funcionalidad y las políticas que los conectan. Se obtuvieron ocho contextos. Dos se consideran core, porque contienen la propuesta de valor de SkillSwap: Learning Path Engine, que convierte el objetivo del Estudiante en una ruta de certificación, y Assessment & Peer Review, que verifica el dominio de cada habilidad mediante la revisión con rúbrica. Credential Verification, Reputation, Recognition & Incentives y Moderation & Disputes son contextos de soporte, mientras que Identity & Access y Subscription & Billing son genéricos.

Las flechas moradas representan las políticas que conectan los contextos, y las flechas punteadas, las consultas. Assessment & Peer Review es el contexto con más relaciones: consulta a Subscription & Billing los escalamientos, la espera y el plazo que corresponden al plan, y notifica a Learning Path Engine, Reputation y Recognition & Incentives cada vez que se califica o se aprueba una entrega. Moderation & Disputes recibe los certificados sospechosos y, cuando revierte una decisión, notifica a Reputation y a Assessment & Peer Review.

**Figura 53**

*EventStorming, paso 10: Bounded Contexts*

<p align="center">
  <img src="public/assets/images-doc/eventstorming-paso-10-bounded-contexts.png" alt="EventStorming paso 10: bounded contexts candidatos de SkillSwap" width="900">
</p>

*Nota.* Bounded contexts candidatos de SkillSwap, delimitados con línea punteada. Los contextos core tienen borde grueso; las flechas moradas representan políticas y las punteadas, consultas. Elaboración propia.

**Ajustes del modelo posteriores a la sesión**

Al construir el backend del Sprint 1, el equipo simplificó dos decisiones modeladas en esta sesión, sin cambiar los eventos principales del dominio:

* **Revisión del Verificador:** en la sesión se modeló una calificación por criterio, cuyo puntaje determinaba la aprobación, y la asignación de un segundo revisor cuando el Estudiante reporta la calificación. En el diseño final, el Verificador revisa el trabajo guiándose por la rúbrica y registra una decisión de aprobación o rechazo con sus observaciones (`rubricNotes`); si el Estudiante está en desacuerdo, puede apelar y otro Verificador revisa el caso (ver 2.6.4 y 2.6.7). Los "criterios no cumplidos" que aparecen en los pasos anteriores corresponden, en el diseño final, a esas observaciones.
* **Intentos y habilitación:** en la sesión se modelaron tres intentos por nodo, un periodo de espera y una prueba adicional para habilitar al Verificador. En la plataforma implementada no hay límite de intentos, periodo de espera ni prueba adicional: cada intento no aprobado abre un caso, siempre que el plan del Estudiante tenga escalamientos disponibles en el mes, y la habilitación como Verificador exige completar en la propia ruta el nodo de la habilidad.
* **Reentregas, reportes y sanciones:** en la sesión se modelaron reenvíos de entregables, reportes de la decisión y sanciones a cuentas. En el diseño final, un caso rechazado deja el nodo disponible para una nueva evaluación, la apelación es el único mecanismo para cuestionar una decisión y una decisión revertida reduce la confiabilidad del Verificador original.
* **Moderación:** el panel de moderación externo del modelado inicial se reemplaza por la supervisión que ejercen los Verificadores senior desde la aplicación.

#### 2.5.1.1. Candidate Context Discovery

A partir del EventStorming, se realizó el descubrimiento de contextos candidatos para identificar los bounded contexts de SkillSwap. El proceso se desarrolló en tres iteraciones sobre una versión simplificada de la línea de tiempo, que conserva los eventos que mejor representan cada parte del proceso. En cada iteración se aplicó una de las técnicas propuestas: start-with-simple y look-for-pivotal-events para una primera división del dominio, un refinamiento del borrador según el lenguaje y las reglas de cada parte, y start-with-value para clasificar los contextos resultantes según su valor para el negocio.

**Iteración 1. Start-with-simple y look-for-pivotal-events**

En la primera iteración, la línea de tiempo se descompuso en pasos secuenciales, usando como límites los seis eventos pivotales identificados en el paso 4 del EventStorming: correo verificado, ruta de certificación generada, caso de verificación abierto, ruta completada, certificación emitida y Verificador habilitado para la habilidad. Así se obtuvieron siete fases, desde el registro hasta la revisión como Verificador, y a cada una se le asignó un contexto en borrador. Dentro de la fase de recorrido se separaron los certificados de la evaluación, porque registrar un certificado no completa ningún nodo de la ruta.

En esta iteración también se observó que algunos eventos no pertenecen a una sola fase. El cobro y el vencimiento de la suscripción, los SkillCredits, la confiabilidad del Verificador y las disputas aparecen en distintos momentos del proceso, por lo que se registraron aparte como candidatos a contextos transversales.

**Figura 54**

*Candidate Context Discovery, iteración 1: fases delimitadas por los eventos pivotales*

<p align="center">
  <img src="public/assets/images-doc/candidate-context-discovery-1-pivotales.png" alt="Línea de tiempo simplificada de SkillSwap dividida en fases por los eventos pivotales" width="900">
</p>

*Nota.* Línea de tiempo simplificada, dividida en fases por los eventos pivotales. Debajo de cada fase figura el contexto en borrador, y en la parte inferior, los eventos que aparecen en varias fases. Elaboración propia.

**Iteración 2. Refinamiento de los contextos candidatos**

En la segunda iteración, cada evento se ubicó en el carril del contexto candidato al que pertenece, manteniendo su posición en el tiempo. Los borradores se ajustaron según dos criterios: que los eventos de un mismo contexto compartan el lenguaje y las reglas de negocio, y que el contexto pueda evolucionar sin arrastrar a los demás.

Con este criterio, los borradores de evaluación, revisión y Verificadores se unieron en Assessment & Peer Review, porque comparten el mismo lenguaje de casos, rúbricas e intentos, y porque la habilitación del Verificador depende del resultado de esas evaluaciones. El borrador de certificación se integró a Learning Path Engine, porque la certificación es el resultado de completar la ruta; en ese mismo contexto quedó la generación del quiz, ya que el blueprint de evaluación se define junto con cada nodo. Los eventos transversales dieron lugar a cuatro contextos propios: Subscription & Billing, Reputation, Recognition & Incentives y Moderation & Disputes. La figura muestra que el flujo principal avanza entre Learning Path Engine y Assessment & Peer Review, mientras que los demás contextos intervienen en momentos puntuales.

**Figura 55**

*Candidate Context Discovery, iteración 2: línea de tiempo por contexto candidato*

<p align="center">
  <img src="public/assets/images-doc/candidate-context-discovery-2-contextos.png" alt="Eventos de SkillSwap organizados en carriles por contexto candidato" width="900">
</p>

*Nota.* Cada carril corresponde a un contexto candidato y cada evento conserva su posición en el tiempo. Las líneas verticales son los eventos pivotales; los carriles con borde grueso corresponden a los contextos core. Elaboración propia.

**Iteración 3. Start-with-value**

En la tercera iteración, los contextos candidatos se clasificaron según su aporte a la propuesta de valor de SkillSwap, que es demostrar que el Estudiante domina una habilidad y no solo que tiene un certificado. Se consideraron core Learning Path Engine y Assessment & Peer Review, porque sin la ruta y sin la verificación con rúbrica la plataforma no tendría una propuesta diferenciada. Credential Verification, Reputation, Recognition & Incentives y Moderation & Disputes se clasificaron como contextos de soporte, porque son específicos del negocio, pero existen para sostener a los contextos core. Identity & Access y Subscription & Billing se clasificaron como genéricos, porque resuelven necesidades comunes a cualquier aplicación y pueden apoyarse en soluciones existentes.

**Figura 56**

*Candidate Context Discovery, iteración 3: clasificación de los contextos por valor*

<p align="center">
  <img src="public/assets/images-doc/candidate-context-discovery-3-valor.png" alt="Contextos candidatos de SkillSwap clasificados en core, soporte y genéricos" width="900">
</p>

*Nota.* Contextos candidatos clasificados según su aporte a la propuesta de valor, con la responsabilidad principal de cada uno. Elaboración propia.

El resultado del proceso son ocho contextos candidatos, que se resumen en la tabla siguiente y que se desarrollan en las secciones 2.5.1.2 y 2.5.1.3.

**Tabla 11**

*Contextos candidatos de SkillSwap*

| Contexto candidato | Tipo | Responsabilidad | Eventos representativos |
|---|---|---|---|
| Learning Path Engine | Core | Convertir el objetivo del Estudiante en una ruta de certificación, seguir el avance de sus nodos y emitir la certificación | Ruta de certificación generada, Nodo completado, Ruta completada, Certificación emitida |
| Assessment & Peer Review | Core | Verificar el dominio de cada habilidad con quizzes, entregables y la demostración final revisados con rúbrica, y habilitar a los Verificadores | Caso de verificación abierto, Caso resuelto, Demostración final aprobada, Verificador habilitado para la habilidad |
| Credential Verification | Soporte | Registrar los certificados previos del Estudiante y detectar los sospechosos | Certificado registrado, Certificado marcado como sospechoso |
| Reputation | Soporte | Medir la confiabilidad de cada Verificador y la empleabilidad del Estudiante | Caso resuelto registrado, Decisión revertida registrada, Confiabilidad del Verificador recalculada |
| Recognition & Incentives | Soporte | Acreditar SkillCredits por cada revisión, registrar su canje por beneficios y otorgar rangos según los casos resueltos | SkillCredits acreditados, SkillCredits canjeados, Rango de Verificador alcanzado |
| Moderation & Disputes | Soporte | Resolver disputas y revisiones de certificados mediante la supervisión de los Verificadores senior | Disputa abierta, Decisión revertida, Revisión de certificado resuelta |
| Identity & Access | Genérico | Registrar al usuario, verificar su correo y autenticarlo | Estudiante registrado, Correo verificado |
| Subscription & Billing | Genérico | Gestionar los planes gratuito y premium y el cobro de la suscripción | Plan gratuito asignado, Pago de suscripción cobrado, Suscripción vencida |

*Nota.* Elaboración propia.


#### 2.5.1.2. Domain Message Flows Modeling

Una vez identificados los contextos candidatos, se modeló cómo colaboran entre sí para resolver los escenarios principales del negocio. Para ello se elaboraron diagramas de Domain Message Flow, una técnica de visualización basada en Domain Storytelling que muestra, para un escenario concreto, los mensajes que intercambian los actores, los bounded contexts y los sistemas externos.

Los diagramas siguen la notación de mensaje y contenido combinados. Los actores se representan con una figura de persona, los bounded contexts con una elipse morada y los sistemas externos con un engranaje. Cada mensaje es una tarjeta de color según su tipo: azul para los comandos, naranja para los eventos y verde para las consultas. La tarjeta indica el nombre del mensaje y sus datos más importantes, y el número en la parte superior, que también aparece sobre la flecha correspondiente, señala el orden en que ocurre dentro del escenario. Las flechas punteadas van del emisor al receptor.

Se modelaron seis escenarios, elegidos para que cada bounded context participe en al menos uno de ellos. Los diagramas parten del modelo trabajado en el EventStorming; cuando el modelo implementado en el Sprint 1 difiere, el texto de cada escenario lo indica.

El primer escenario muestra cómo colaboran Identity & Access y Subscription & Billing. El Estudiante se registra desde la aplicación, Identity & Access solicita al servicio de correo (Brevo) el envío de un enlace de verificación de un solo uso, que vence en 24 horas, y, cuando el Estudiante abre ese enlace y verifica su correo, publica el evento Correo verificado, al que Subscription & Billing reacciona asignando el plan gratuito. Si el Estudiante decide pasar al plan premium, compra el plan mensual en Google Play mediante el SDK de RevenueCat y la aplicación envía Iniciar suscripción premium con el `productId`; Subscription & Billing verifica la compra con Google Play Billing (vía RevenueCat), que responde con Compra verificada, y desde entonces RevenueCat notifica las renovaciones y los vencimientos mediante un webhook.

**Figura 57**

*Domain Message Flow: Registro del Estudiante y paso al plan premium*

<p align="center">
  <img src="public/assets/images-doc/message-flow-registro.png" alt="Domain Message Flow del escenario registro del estudiante y paso al plan premium" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de registro del Estudiante y paso al plan premium. Los números indican el orden de los mensajes. Elaboración propia.

En el segundo escenario, el Estudiante declara su objetivo y Learning Path Engine consulta a Subscription & Billing si el plan le permite abrir una nueva ruta. Con esa respuesta, solicita al LLM que interprete el objetivo y seleccione las habilidades correspondientes, solo entre las de la taxonomía interna de habilidades. Con esas habilidades, el propio contexto calcula la brecha de habilidades y ordena los nodos según sus prerrequisitos, respetando el mínimo de nodos prácticos; si el LLM no responde o no devuelve habilidades válidas, recurre a la comparación por palabras clave sobre la misma taxonomía. Finalmente publica el evento Ruta de certificación generada, con los nodos y el tipo de cada uno.

**Figura 58**

*Domain Message Flow: Declaración del objetivo y generación de la ruta*

<p align="center">
  <img src="public/assets/images-doc/message-flow-ruta.png" alt="Domain Message Flow del escenario declaración del objetivo y generación de la ruta" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de declaración del objetivo y generación de la ruta. Los números indican el orden de los mensajes. Elaboración propia.

El tercer escenario corresponde al flujo central de SkillSwap. El entregable del Estudiante se almacena en Cloudinary y se envía a Assessment & Peer Review, que consulta a Subscription & Billing los escalamientos disponibles y el plazo de revisión según el plan. Tras la asignación, el Verificador califica cada criterio de la rúbrica. Cuando el sistema calcula que el entregable se aprueba, Assessment & Peer Review publica el evento Entregable aprobado, que Learning Path Engine usa para completar el nodo, y el evento Entregable calificado por criterio, que Recognition & Incentives usa para acreditar SkillCredits y Reputation para recalcular la confiabilidad del Verificador. En el modelo implementado, el Verificador no registra un puntaje por criterio: aprueba o rechaza el caso con sus observaciones (`rubricNotes`), y Assessment & Peer Review publica el evento Caso resuelto (`VerificationCaseResolved`), al que reaccionan Learning Path Engine, Recognition & Incentives y Reputation.

**Figura 59**

*Domain Message Flow: Revisión de un entregable práctico aprobado*

<p align="center">
  <img src="public/assets/images-doc/message-flow-entregable.png" alt="Domain Message Flow del escenario revisión de un entregable práctico aprobado" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de revisión de un entregable práctico aprobado. Los números indican el orden de los mensajes. Elaboración propia.

El cuarto escenario muestra la moderación. El Estudiante reporta la decisión de un Verificador y Moderation & Disputes abre la disputa. Un Verificador senior, distinto del que tomó la decisión, consulta las disputas abiertas y ejecuta la resolución desde su panel de supervisión (en el diagrama, este rol aparece como el panel de moderación del modelado inicial). Cuando la decisión se revierte, Moderation & Disputes publica el evento Decisión revertida, que Reputation usa para recalcular la confiabilidad del Verificador y Assessment & Peer Review para aprobar el entregable, lo que a su vez completa el nodo en Learning Path Engine. En el modelo implementado, este escenario se resuelve con la apelación: el Estudiante apela una sola vez un caso rechazado, Assessment & Peer Review lo reasigna a un Verificador distinto del original y, si este lo aprueba, el evento Caso resuelto indica qué Verificador fue revertido para que Reputation reduzca su confiabilidad. Moderation & Disputes atiende las revisiones de certificados sospechosos.

**Figura 60**

*Domain Message Flow: Reporte de una decisión revertida por Moderación*

<p align="center">
  <img src="public/assets/images-doc/message-flow-disputa.png" alt="Domain Message Flow del escenario reporte de una decisión revertida por moderación" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de reporte de una decisión revertida por Moderación. Los números indican el orden de los mensajes. Elaboración propia.

En el quinto escenario, Learning Path Engine publica el evento Ruta completada, que habilita la demostración final en Assessment & Peer Review. El Estudiante envía su demostración, el Verificador la califica con la rúbrica y, cuando se aprueba, Assessment & Peer Review publica el evento Demostración final aprobada. Learning Path Engine emite entonces la certificación, notifica al Estudiante por correo y publica el evento Certificación emitida.

**Figura 61**

*Domain Message Flow: Demostración final y emisión de la certificación*

<p align="center">
  <img src="public/assets/images-doc/message-flow-demostracion.png" alt="Domain Message Flow del escenario demostración final y emisión de la certificación" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de demostración final y emisión de la certificación. Los números indican el orden de los mensajes. Elaboración propia.

El último escenario muestra el registro de un certificado. La aplicación extrae sus datos en el dispositivo con ML Kit y los envía a Credential Verification, que evalúa el riesgo documental. Si el riesgo es alto, publica el evento Certificado marcado como sospechoso, que Moderation & Disputes recibe para su revisión. Cuando el Verificador senior resuelve el caso (en el diagrama, el panel de moderación del modelado inicial), Moderation & Disputes devuelve el resultado a Credential Verification mediante el evento Revisión de certificado resuelta.

**Figura 62**

*Domain Message Flow: Registro de un certificado sospechoso*

<p align="center">
  <img src="public/assets/images-doc/message-flow-certificado.png" alt="Domain Message Flow del escenario registro de un certificado sospechoso" width="900">
</p>

*Nota.* Mensajes intercambiados entre actores, bounded contexts y sistemas externos en el escenario de registro de un certificado sospechoso. Los números indican el orden de los mensajes. Elaboración propia.

#### 2.5.1.3. Bounded Context Canvases

Con los contextos candidatos y sus flujos de mensajes definidos, se elaboró un Bounded Context Canvas para cada uno, usando la versión 5 de la plantilla de ddd-crew. Los contextos se trabajaron en orden de importancia, empezando por los core, y cada canvas se construyó de forma iterativa con los siguientes pasos:

1. **Context Overview Definition:** definir el nombre, el propósito y la clasificación estratégica del contexto (tipo de dominio, modelo de negocio, evolución y rol).
2. **Business Rules Distillation & Ubiquitous Language Capture:** extraer las reglas de negocio del EventStorming y registrar los términos propios del contexto.
3. **Capability Analysis:** identificar qué capacidades ofrece el contexto a partir de los comandos y consultas que recibe.
4. **Capability Layering:** cuando aplica, ordenar esas capacidades en capas según su nivel.
5. **Dependencies Capture:** registrar los mensajes de entrada y de salida y los colaboradores con los que se intercambian, a partir de los Domain Message Flows.
6. **Design Critique:** revisar el diseño, registrar los supuestos, las métricas para validarlo y las preguntas abiertas, y evaluar alternativas.

En los canvas, los comandos se muestran en azul, los eventos en amarillo y las consultas en verde, como en la plantilla original. Las preguntas abiertas recogen los puntos críticos identificados en el paso 3 del EventStorming.

Se trabajó primero Assessment & Peer Review, por ser el contexto que materializa la propuesta de valor. En la definición general se estableció su propósito, verificar el dominio de cada habilidad, y se clasificó como core, custom built y de ejecución. Al destilar las reglas se fijó que el quiz de cada nodo tiene cinco preguntas y se aprueba con cuatro, con calificación automática; que un intento no aprobado abre un caso solo si se escala dentro de la cuota mensual del plan; que el Verificador asignado aprueba o rechaza el caso con notas basadas en la rúbrica; que el plazo de revisión es de 48 horas en el plan mensual y de hasta 5 días hábiles en el gratuito, y que un caso vencido se reasigna; y que un caso rechazado puede apelarse una vez y lo revisa un Verificador distinto. En el análisis de capacidades se identificaron tres grupos, que corresponden a sus capas: la evaluación automática de los quizzes, la revisión humana de los casos escalados y la habilitación de Verificadores por habilidad, que exige completar el nodo de esa habilidad en la propia ruta. En la captura de dependencias se observó que recibe las evaluaciones generadas por Learning Path Engine, consulta a Subscription & Billing los límites del plan y notifica sus resultados a Learning Path Engine, Reputation y Recognition & Incentives. En la crítica del diseño se evaluó separar la habilitación de Verificadores en un contexto propio; se descartó porque comparte el lenguaje de casos, rúbricas e intentos.

**Figura 63**

*Bounded Context Canvas: Assessment & Peer Review*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-assessment-peer-review.png" alt="Bounded Context Canvas del contexto Assessment & Peer Review" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Assessment & Peer Review, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Learning Path Engine es el segundo contexto core. Su propósito es convertir el objetivo del Estudiante en una ruta de certificación y seguir su avance hasta emitir la certificación. Entre sus reglas destacan el mínimo de nodos prácticos por ruta, el límite de rutas del plan gratuito (1 ruta activa a la vez y hasta 3 en total, sin contar la ruta avanzada canjeada con SkillCredits) y la condición para emitir la certificación. Sus capacidades se organizan en dos capas: la generación de la ruta y de los blueprints de evaluación, que se apoya en el LLM, y el seguimiento del avance hasta la certificación. En la ruta, el LLM solo interpreta el objetivo y selecciona habilidades de la taxonomía interna (`skill-catalog.json`), que sigue siendo la fuente de verdad; el contexto calcula la brecha y ordena los nodos según sus prerrequisitos, y si el LLM falla recurre a la coincidencia por palabras clave sobre el mismo catálogo. En los blueprints, el LLM genera las preguntas de cada evaluación. En las dependencias se identificó una relación en ambos sentidos con Assessment & Peer Review, que se resuelve con eventos: Learning Path Engine publica los blueprints y la ruta completada, y reacciona a los nodos y demostraciones aprobados. En la crítica se evaluó trasladar la generación de blueprints a Assessment & Peer Review; se mantuvo aquí porque el blueprint se define junto con cada nodo de la ruta.

**Figura 64**

*Bounded Context Canvas: Learning Path Engine*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-learning-path-engine.png" alt="Bounded Context Canvas del contexto Learning Path Engine" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Learning Path Engine, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Credential Verification se clasificó como un contexto de soporte orientado al cumplimiento, porque protege la confianza en el perfil del Estudiante. Su regla central es que registrar un certificado no completa ningún nodo: el certificado registrado complementa el perfil como evidencia, y solo cuando un Verificador senior lo confirma como verificado cuenta como habilidad ya demostrada y completa el nodo que cubre. Su capacidad principal es el registro con evaluación del riesgo documental, apoyada en ML Kit para la extracción en el dispositivo y en Cloudinary para el almacenamiento. Su única dependencia de dominio es Moderation & Disputes, que revisa los certificados sospechosos. Un certificado sospechoso no bloquea la ruta: el Estudiante sigue avanzando con sus evaluaciones mientras el Verificador senior lo revisa.

**Figura 65**

*Bounded Context Canvas: Credential Verification*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-credential-verification.png" alt="Bounded Context Canvas del contexto Credential Verification" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Credential Verification, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Reputation es un contexto de análisis: no ejecuta el proceso principal, sino que interpreta sus resultados para medir la confiabilidad de cada Verificador. Se alimenta de los eventos de Assessment & Peer Review: cada caso resuelto, cada decisión revertida tras una apelación y cada plazo de revisión vencido, que restan 15 y 5 puntos, respectivamente, a una confiabilidad que parte de 100. Su resultado vuelve a Assessment & Peer Review, que lo sincroniza en el perfil del Verificador, y a Moderation & Disputes, que lo usa para identificar a los Verificadores senior. En la crítica se discutió unirlo con Recognition & Incentives; se mantuvieron separados porque la confiabilidad mide la calidad de las revisiones, mientras que los SkillCredits premian su cantidad.

**Figura 66**

*Bounded Context Canvas: Reputation*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-reputation.png" alt="Bounded Context Canvas del contexto Reputation" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Reputation, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Recognition & Incentives reconoce el trabajo de los Verificadores. Sus reglas reflejan decisiones del modelo de negocio: los SkillCredits se ganan por cada revisión, apruebe o rechace, para no incentivar decisiones en un sentido; el monto depende del tipo de caso, 40 por un miniproyecto y 25 por un quiz, porque revisar un miniproyecto exige más trabajo; nunca se compran con dinero ni se transfieren, y el Verificador puede canjearlos por los dos beneficios de la tienda: una ruta avanzada, por 200 SkillCredits, o un certificado de contribución, por 120, precios escalados para que un beneficio siga requiriendo varios casos resueltos. El rango no depende del saldo de SkillCredits, sino de la cantidad de casos resueltos, de modo que canjear créditos no lo reduce. Sus capacidades son acreditar SkillCredits, registrar su canje y otorgar rangos por umbral de casos resueltos, y la acreditación depende únicamente de los eventos de Assessment & Peer Review. Los umbrales de rango quedaron definidos así: Bronce, de 0 a 29 casos resueltos; Plata, de 30 a 99; y Oro, desde 100. El rango Oro, junto con una confiabilidad de 90 o más, habilita al Verificador senior.

**Figura 67**

*Bounded Context Canvas: Recognition & Incentives*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-recognition-incentives.png" alt="Bounded Context Canvas del contexto Recognition & Incentives" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Recognition & Incentives, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Moderation & Disputes resuelve las disputas y las revisiones de certificados. Una decisión de diseño importante es que la moderación no corresponde a un actor aparte: la ejercen los propios Verificadores desde la aplicación, y un caso nunca lo resuelve el mismo Verificador que tomó la decisión cuestionada. Su capacidad principal es resolver las revisiones de certificados sospechosos: asigna cada disputa al Verificador senior con menos carga, distinto del dueño del certificado, y devuelve el resultado a Credential Verification, que marca el certificado como verificado o rechazado. Si no hay un Verificador senior disponible, la disputa queda pendiente y su asignación se reintenta periódicamente.

**Figura 68**

*Bounded Context Canvas: Moderation & Disputes*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-moderation-disputes.png" alt="Bounded Context Canvas del contexto Moderation & Disputes" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Moderation & Disputes, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Subscription & Billing se clasificó como genérico, porque la gestión de planes y cobros es común a muchas aplicaciones y se apoya en Google Play Billing: la política de pagos de Google Play exige que las aplicaciones distribuidas en Play Store que venden suscripciones digitales usen su sistema de facturación (Google Play Console Help, s. f.-a), y Perú no figura entre los países elegibles para los programas de facturación alternativa ni de elección del usuario (Google Play Console Help, s. f.-b). La integración se realiza mediante RevenueCat, que valida la compra en el servidor y notifica al backend sus cambios de estado, sin reemplazar a Google Play Billing ni actuar como procesador de pagos (RevenueCat, s. f.). Su regla principal refleja el modelo de negocio: ningún plan compra la aprobación, ya que la cantidad de intentos es igual en ambos, y el plan premium solo reduce las esperas y los plazos y amplía las rutas y los escalamientos: pasa de 1 a 3 rutas activas, elimina el tope de 3 rutas en total, sube de 3 a 10 los escalamientos al mes y reduce la revisión de hasta 5 días hábiles a 48 horas. En las dependencias se observa que es un contexto muy consultado: Learning Path Engine y Assessment & Peer Review le preguntan por los límites del plan antes de actuar.

**Figura 69**

*Bounded Context Canvas: Subscription & Billing*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-subscription-billing.png" alt="Bounded Context Canvas del contexto Subscription & Billing" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Subscription & Billing, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

Por último, Identity & Access se clasificó como genérico, commodity y de tipo gateway, porque es la puerta de entrada a la aplicación. Registra a los usuarios validando que su correo pertenezca al dominio institucional (`.edu.pe`) y les envía, mediante Brevo, un enlace de verificación de un solo uso que vence en 24 horas; hasta que el Estudiante verifica su correo, no puede iniciar sesión. Un Verificador sigue siendo el mismo usuario que se registró como Estudiante, por lo que no existe un registro separado. Su dependencia principal es Subscription & Billing, que reacciona al correo verificado asignando el plan gratuito.

**Figura 70**

*Bounded Context Canvas: Identity & Access*

<p align="center">
  <img src="public/assets/images-doc/bounded-context-canvas-identity-access.png" alt="Bounded Context Canvas del contexto Identity & Access" width="900">
</p>

*Nota.* Bounded Context Canvas del contexto Identity & Access, elaborado con la plantilla v5 de ddd-crew. Elaboración propia.

### 2.5.2. Context Mapping

El Context Mapping de SkillSwap evidencia las relaciones estructurales entre los ocho Bounded Contexts que conforman la solución, aplicando los patrones de relación establecidos en Domain-Driven Design para gestionar las dependencias entre equipos y modelos de dominio, bajo el nuevo enfoque de la plataforma centrado en la verificación de habilidades mediante Inteligencia Artificial.

**Identity & Access** actúa como **Upstream** de todo el sistema bajo el patrón **Conformist**: su agregado `User` expone únicamente `userId` y `role` como datos públicos, y el resto de los Bounded Contexts (Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes) se conforman a ese modelo sin negociar cambios, referenciando el identificador de usuario como un dato externo dentro de su propio esquema de persistencia. La cuenta tiene un único rol, `Student`; el perfil de Verificador (`VerifierProfile`) pertenece a Assessment & Peer Review y se crea cuando el Estudiante completa el nodo de una habilidad, sin agregar un rol a nivel de autenticación.

**Credential Verification** mantiene una relación **Customer/Supplier** hacia **Learning Path Engine**: solo un certificado verificado completa los nodos de la habilidad que cubre, y uno que superó el análisis de riesgo puede vincularse a un nodo sin completarlo, por lo que Learning Path Engine actúa como Downstream, consumiendo el modelo de `Certificate` validado sin poder alterar las reglas de extracción o de detección de fraude definidas en el Upstream.

**Learning Path Engine**, como núcleo de negocio (Core Domain) de la plataforma, es **Supplier** de **Assessment & Peer Review** bajo el patrón **Customer/Supplier**: cada `PathNode` de la ruta generada define la especificación de la evaluación (habilidad a demostrar, nivel de exigencia) que Assessment & Peer Review debe ejecutar como Downstream, sin negociar el contenido de dicha especificación.

**Assessment & Peer Review**, como ejecutor del flujo de evaluación y revisión humana, es **Supplier** de **Reputation** (la resolución de un `VerificationCase` —aprobado o rechazado, y quién lo revisó— dispara el recálculo de la confiabilidad del Verificador y del Employability Score del estudiante) y de **Recognition & Incentives** (la resolución de un caso por parte de un Verificador dispara la acreditación de SkillCredits), ambas bajo el patrón **Customer/Supplier**.

**Subscription & Billing** opera de forma independiente al resto de los Bounded Contexts de negocio, sin ninguna relación Customer/Supplier hacia Recognition & Incentives: gestiona únicamente los planes del Estudiante, el gratuito y la suscripción mensual que amplía sus límites, sin intervenir en el balance ni la acreditación de SkillCredits, que permanecen como un sistema de reconocimiento estrictamente no monetario: no se adquieren con dinero ni se transfieren, y solo se canjean por beneficios dentro de la plataforma. Este Bounded Context mantiene una relación de **Anticorruption Layer (ACL)** hacia el servicio externo de terceros **Google Play Billing (vía RevenueCat)**, aislando el modelo de dominio interno `Subscription` de los contratos, webhooks y formatos propios de RevenueCat y de Google Play.

**Moderation & Disputes** se relaciona como **Customer/Supplier** con **Identity & Access**, cuyo usuario autenticado identifica al Verificador senior que resuelve la disputa, y con **Reputation**, a la que consulta qué Verificadores son senior (`SeniorVerifierPolicy`) para asignar cada disputa. Recibe de **Credential Verification** el evento `CertificateFlaggedSuspicious` y le devuelve el resultado de la revisión mediante `CredentialContextFacade`. Además, mantiene una relación de **Anticorruption Layer (ACL)** hacia **Assessment & Peer Review**: en lugar de depender del modelo interno de `VerificationCase`, consulta la carga de casos abiertos de cada Verificador mediante `VerifierWorkload`, para asignar la disputa al Verificador senior menos cargado.

Finalmente, **Credential Verification** mantiene una relación de **Anticorruption Layer (ACL)** hacia el servicio externo de terceros **ML Kit** (Text Recognition / Entity Extraction de Firebase, utilizado on-device para la extracción de datos del certificado), aislando el modelo de dominio interno `Certificate` de los contratos y formatos de respuesta propios del SDK externo. Del mismo modo, **Learning Path Engine** mantiene una relación de **Anticorruption Layer (ACL)** hacia la **Gemini API**: sus adaptadores traducen la respuesta del modelo a `skillTag` del catálogo interno y a preguntas del `AssessmentBlueprint`, descartando cualquier habilidad que no pertenezca al catálogo.

**Figura 71**

*Context Mapping de SkillSwap*

<p align="center">
  <img src="images-doc/context-mapping.png" alt="Context Mapping" width="900">
</p>

*Nota.* Se muestran las relaciones Conformist, Customer/Supplier y Anticorruption Layer entre los ocho Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes) y los sistemas externos ML Kit, Gemini API y Google Play Billing (vía RevenueCat). Elaboración propia.

### 2.5.3. Software Architecture

**Software Architecture Context Level Diagram:**
Muestra la interacción de los dos actores (Estudiante, Verificador) con el sistema central de SkillSwap y los servicios externos de terceros (extracción de datos de certificados vía ML Kit, procesamiento de la suscripción con Google Play Billing (vía RevenueCat), IA generativa con la Gemini API, almacenamiento de certificados en Cloudinary, envío de correos con Brevo y notificaciones push con Firebase Cloud Messaging).

**Software Architecture Container Level Diagram:**
Detalla la estructura de contenedores:
1. **Mobile Application (Native/Cross-Platform):** La interfaz principal para los dos actores, desarrollada con soporte de almacenamiento local, acceso a hardware (cámara para captura de certificados y biometría, ambas ejecutadas en el dispositivo junto con el OCR de ML Kit) y consumo del backend RESTful.
2. **Landing Page:** Sitio web estático para la presentación del modelo de negocio, accesible por ambos actores.
3. **API / RESTful Web Services:** El backend desarrollado internamente que expone los endpoints y orquesta la lógica de negocio de los ocho Bounded Contexts.
4. **Database:** Repositorio central de información, compartido por los ocho Bounded Contexts.

**Software Architecture Deployment Diagram:**
Muestra cómo la aplicación móvil se despliega en los dispositivos físicos de los usuarios (Android), el Landing Page en un servicio de hosting estático, y el backend junto con la base de datos en infraestructura Cloud.

#### 2.5.3.1. Software Architecture Context Level Diagrams

El diagrama de contexto (Context Diagram) bajo el enfoque C4 Model presenta al sistema SkillSwap como una caja central única, mostrando sus interacciones de alto nivel con los actores principales y los sistemas externos de terceros, sin exponer aún detalles de implementación.

El sistema es utilizado por dos actores principales: el **Estudiante**, quien sube sus certificados, demuestra sus habilidades a través de las evaluaciones generadas por la plataforma y la usa con el plan gratuito o con una suscripción mensual que amplía sus límites; y el **Verificador** (un perfil vinculado a un Estudiante que completó en su propia ruta el nodo de la habilidad que revisa), quien revisa los casos que la IA no puede resolver con suficiente confianza y, como Verificador senior, supervisa la calidad e integridad del proceso de verificación, resolviendo disputas y consultando métricas agregadas del ecosistema. Ambos actores interactúan con el sistema a través de la **aplicación móvil nativa (Android) y cross-platform (Flutter)**, así como del Landing Page.

A nivel de sistemas externos, SkillSwap se integra con: **ML Kit** (Firebase), utilizado on-device para la extracción de datos de los certificados subidos por el Estudiante (institución, curso, fecha) — esta es la tecnología que satisface el requisito de aprendizaje autónomo del curso; **Google Play Billing (vía RevenueCat)**, utilizado para el cobro recurrente de la suscripción mensual: Google Play procesa el pago y RevenueCat valida la compra y notifica sus cambios de estado al backend; la **Gemini API**, servicio de IA generativa que interpreta la meta del Estudiante seleccionando habilidades solo del catálogo interno (con coincidencia por palabras clave como respaldo si no responde) y genera las preguntas de las evaluaciones; **Cloudinary**, servicio de almacenamiento en la nube para los archivos de los certificados; **Brevo (Email API)**, con el que el backend envía el correo con el enlace de verificación del correo institucional `.edu.pe`; y **Firebase Cloud Messaging**, con el que el backend envía notificaciones push al dispositivo del Estudiante cuando su certificado queda verificado o rechazado.

**Figura 72**

*C4 Model: Context Diagram*

<p align="center">
  <img src="images-doc/SkillSwapSystemContext.svg" alt="System Context Diagram - Mobile" width="800">
</p>

*Nota.* Diagrama de contexto que muestra el sistema SkillSwap en el centro y sus interacciones directas con los dos actores principales (Estudiante, Verificador) a través de la aplicación móvil nativa, la aplicación cross-platform y el Landing Page, así como con los sistemas externos de terceros (ML Kit, Google Play Billing vía RevenueCat, Gemini API, Cloudinary, Brevo y Firebase Cloud Messaging). Elaboración propia.

#### 2.5.3.2. Software Architecture Container Level Diagrams

El diagrama de contenedores (Container Diagram) descompone el sistema SkillSwap en los bloques de alto nivel que lo conforman, mostrando las principales decisiones tecnológicas y cómo se comunican entre sí. A diferencia del Context Diagram, aquí se detalla la estructura interna del sistema como un conjunto de aplicaciones y almacenes de datos desplegables de forma independiente.

Los contenedores identificados son los siguientes:

- **Landing Page (Sitio Web Estático):** Presenta el modelo de negocio de SkillSwap al público general, implementado con HTML5, CSS3 y JavaScript.
- **Android Native Application:** Aplicación móvil nativa dirigida a los dos actores (Estudiante, Verificador), desarrollada en Kotlin con Jetpack Compose, que consume los Web Services RESTful del backend.
- **Cross-Platform Application (Flutter):** Aplicación móvil dirigida a Android, que replica las funcionalidades core para ambos actores, desarrollada en Flutter con Dart, consumiendo igualmente los Web Services RESTful expuestos por el backend.
- **API / RESTful Web Services:** Backend desarrollado bajo arquitectura RESTful en Java 21 con Spring Boot (Spring Web MVC, Spring Data JPA/Hibernate y Spring Security con JWT), actuando como Published Language único para los dos clientes móviles (Android Native App y Flutter App); el Landing Page es informativo y no consume la API. Este contenedor expone los endpoints del dominio y orquesta la lógica de negocio de los ocho Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes); el detalle interno de cada Bounded Context se desarrolla en su propio Component Diagram (ver 2.6.x.5).
- **Database:** Repositorio central de persistencia (instancia única de PostgreSQL), donde cada Bounded Context mantiene sus propias tablas siguiendo los principios de Domain-Driven Design.

Es importante resaltar que tanto la aplicación Android nativa como la aplicación Flutter cross-platform consumen el **mismo contrato de API RESTful** documentado con OpenAPI/Swagger, sin requerir endpoints adicionales ni lógica de backend duplicada, evidenciando así el desacoplamiento entre la capa de presentación y la capa de dominio/aplicación del sistema.

**Figura 73**

*C4 Model: Container Diagram*

<p align="center">
  <img src="images-doc/SkillSwapContainer.svg" alt="Container Diagram - Mobile" width="900">
</p>

*Nota.* Diagrama de contenedores que muestra el Landing Page, la Aplicación Android Nativa, la Aplicación Cross-Platform (Flutter), el backend de API/RESTful Web Services y la Base de Datos, junto con sus interacciones y los sistemas externos ML Kit, Google Play Billing (vía RevenueCat), Gemini API, Cloudinary, Brevo (Email API) y Firebase Cloud Messaging, este último con las notificaciones push hacia las aplicaciones móviles. El Landing Page es informativo y no consume la API. Los ocho Bounded Contexts se detallan a nivel de Component Diagram, no en este nivel de contenedor. Elaboración propia.


#### 2.5.3.3. Software Architecture Deployment Diagrams

El Deployment Diagram bajo el enfoque C4 Model muestra la distribución física de los contenedores de SkillSwap sobre la infraestructura de hardware y los entornos de ejecución, evidenciando cómo se despliega la solución en un ambiente real.

- **Dispositivos móviles de usuario final:** Los dispositivos Android de Estudiantes y Verificadores alojan localmente la Aplicación Android Nativa (Kotlin/Jetpack Compose) y la Aplicación Cross-Platform (Flutter, dirigida a Android), instaladas en el dispositivo físico. En estos dispositivos se ejecutan además **ML Kit**, de forma on-device, para la extracción de datos de los certificados, sin requerir una llamada a un servicio en la nube para dicho procesamiento, y la autenticación biométrica del sistema operativo.
- **Hosting estático:** Aloja el Landing Page, servido de forma estática desde **GitHub Pages**, de acceso público.
- **Servidor de aplicación (Cloud):** Aloja el backend de Web Services RESTful (Java 21 / Spring Boot), empaquetado como contenedor Docker y desplegado en **Render**, donde se ejecuta la lógica de negocio de los ocho Bounded Contexts en un único servicio, y se exponen los endpoints documentados con OpenAPI/Swagger, consumidos indistintamente por las dos aplicaciones móviles (Android Native App y Flutter App); el Landing Page es informativo y no consume la API.
- **Servidor de base de datos (Cloud):** Aloja una única instancia administrada de PostgreSQL desplegada en **Render**, compartida por los ocho Bounded Contexts, comunicándose con el servidor de aplicación mediante una conexión segura.
- **Servicios externos en la nube:** Servicio de almacenamiento (Cloudinary) para los archivos de los certificados, **Brevo (Email API)** para el envío del correo de verificación del correo institucional, **Firebase Cloud Messaging** para las notificaciones push al dispositivo del Estudiante, la **Gemini API** para interpretar la meta del Estudiante sobre el catálogo interno de habilidades y generar las preguntas de los quizzes, y **Google Play Billing (vía RevenueCat)** para el procesamiento del cobro recurrente de la suscripción mensual: la aplicación inicia la compra con el SDK de RevenueCat y RevenueCat notifica sus cambios al backend mediante un webhook.

Cada uno de estos nodos se comunica mediante protocolos HTTPS, garantizando la seguridad en la transmisión de datos entre los dispositivos cliente (móviles y navegador) y los servidores desplegados en la nube.

**Figura 74**

*C4 Model: Deployment Diagram*

<p align="center">
  <img src="images-doc/SkillSwapDeployment.svg" alt="Deployment Diagram - Mobile" width="900">
</p>

*Nota.* Diagrama de despliegue que muestra la distribución física de la solución, incluyendo los dispositivos móviles de usuario final (Android/Flutter) con ejecución on-device de ML Kit y de la biometría, el hosting estático del Landing Page, el servidor de aplicación en Render, la instancia única de PostgreSQL en Render y los servicios externos Cloudinary, Brevo (Email API), Firebase Cloud Messaging, Gemini API y Google Play Billing (vía RevenueCat), este último con la compra desde la aplicación y el webhook hacia el backend. Elaborado en PlantUML. Elaboración propia.

## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: Identity & Access

#### 2.6.1.1. Domain Layer

La capa de dominio de Identity & Access encapsula la lógica de negocio central para la gestión de identidades y seguridad, asegurando que las reglas de autenticación, autorización y verificación institucional sean independientes de las tecnologías externas.

**1. Aggregate Root: User**

Descripción: El agregado `User` actúa como la raíz del modelo y centraliza la información de la cuenta, garantizando que el registro y las credenciales se validen estrictamente antes de persistirse.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del usuario (autogenerado). |
| username | Username (VO) | Identificador de texto único utilizado para acceder al sistema. |
| email | Email (VO) | Correo electrónico validado contra el dominio institucional `.edu.pe`. |
| passwordHash | PasswordHash (VO) | Representación segura de la contraseña tras pasar por un algoritmo de encriptación. |
| role | UserRole (VO) | Rol de la cuenta: `Student` (único rol de cuenta; el Verificador es un perfil adicional). |
| isVerified | boolean | Indica si el estudiante confirmó su correo institucional mediante el enlace de verificación; una cuenta sin verificar no puede iniciar sesión. |
| fullName | string | Nombre completo registrado del estudiante (opcional, hasta 150 caracteres), con el que Credential Verification compara el titular leído en sus certificados. |
| bio | string | Descripción libre del perfil del usuario. |
| interestTopics | List&lt;string&gt; | Temas de interés del estudiante (de 1 a 10, hasta 60 caracteres cada uno, sin repetidos). |
| skillVector | List&lt;string&gt; | Etiquetas del catálogo interno de habilidades a las que se refieren los temas de interés y la descripción; se recalcula cada vez que cambian. |
| verificationTokenHash | string | Hash SHA-256 del token del enlace de verificación vigente; el token en claro nunca se almacena. |
| verificationTokenExpiresAt | Instant | Vencimiento del enlace de verificación vigente (24 horas por defecto). |
| verificationEmailSentAt | Instant | Momento del último correo de verificación enviado, que limita el reenvío a uno por intervalo de espera. |
| deviceToken | DeviceToken (VO) | Token de Firebase Cloud Messaging del dispositivo móvil del estudiante; es nulo cuando no concedió el permiso de notificaciones. |

Métodos

- `User(username, email, password, role)` (Constructor): Inicializa las propiedades del usuario y valida que el correo pertenezca al dominio institucional antes de crear la instancia.
- `verify()`: Cambia `isVerified` a `true` al confirmarse el correo institucional y elimina el token de verificación, de modo que cada enlace funciona una sola vez.
- `issueVerificationToken(String tokenHash, Instant expiresAt, Instant issuedAt)`: Registra el hash del nuevo token de verificación, su vencimiento y el momento del envío; un token nuevo reemplaza al anterior.
- `canReceiveVerificationEmail(Instant now, Duration cooldown)`: Indica si ya transcurrió el intervalo de espera desde el último correo de verificación.
- `isVerificationTokenExpired(Instant now)`: Indica si el enlace de verificación vigente ya venció.
- `updateBio(String bio)` y `replaceInterestTopics(List<String> topics)`: Actualizan la descripción y reemplazan los temas de interés del perfil.
- `updateSkillVector(List<String> skillTags)`: Reemplaza el vector de habilidades calculado a partir de los temas de interés y la descripción.
- `updateFullName(String fullName)`: Registra o elimina el nombre completo del estudiante.
- `registerDeviceToken(String token)` / `removeDeviceToken()`: Asocian u olvidan el token de Firebase Cloud Messaging del dispositivo móvil del estudiante.

**2. Value Object: Email**

Descripción: Representa un correo electrónico validado, garantizando que solo se acepten direcciones pertenecientes a un dominio institucional autorizado.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | string | Dirección de correo electrónico completa. |

Métodos

- `Email(String value)` (Constructor): Valida el formato del correo y que su dominio corresponda a `.edu.pe`, lanzando una excepción de dominio en caso contrario.

**3. Value Object: UserRole**

Descripción: Enumeración que restringe los valores válidos para el rol de una cuenta.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | Valor del rol: `Student`. Nota: el perfil de Verificador no es un valor de este enum — es un perfil adicional (`VerifierProfile`) que un usuario `Student` adquiere al completar en su propia ruta el nodo de una habilidad, gestionado en el Bounded Context Assessment & Peer Review. |

**4. Value Object: PasswordHash**

Descripción: Encapsula la representación cifrada de la contraseña, evitando que el valor en texto plano circule fuera de la capa de infraestructura.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | string | Cadena cifrada (hash) de la contraseña. |

**5. Value Object: DeviceToken**

Descripción: Token de registro que Firebase Cloud Messaging asigna a la instalación de la aplicación en el dispositivo del estudiante, usado para enviarle notificaciones push.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | string | Token de Firebase Cloud Messaging (hasta 512 caracteres). Si otra cuenta registra el mismo token, este pasa a la última cuenta que lo registró. |

**6. Domain Service: PasswordHasher**

Descripción: Define el contrato para el cifrado y verificación de contraseñas, desacoplando el dominio del algoritmo criptográfico concreto.

Métodos

- `hashPassword(String plainPassword)`: Recibe la contraseña en texto plano y la transforma en un hash mediante un algoritmo criptográfico para su almacenamiento seguro.
- `verifyPassword(String plainPassword, PasswordHash hash)`: Compara una contraseña en texto claro contra un hash almacenado para verificar si coinciden.

**7. Domain Service: EmailDomainValidator**

Descripción: Define el contrato para validar que un correo electrónico pertenezca a un dominio institucional autorizado antes de crear o actualizar un `User`.

Métodos

- `isInstitutionalDomain(Email email)`: Retorna verdadero si el dominio del correo corresponde a `.edu.pe`.

**8. Repository: UserRepository**

Descripción: Interfaz para la persistencia y recuperación de datos del agregado `User`, sin exponer detalles de la tecnología de almacenamiento subyacente.

Métodos

- `findByUsername(String username)`: Recupera un usuario por su nombre de usuario único.
- `findByEmail(Email email)`: Recupera un usuario por su correo electrónico.
- `findByVerificationTokenHash(String tokenHash)`: Recupera la cuenta a la que pertenece un enlace de verificación, a partir del hash de su token.
- `findByDeviceToken(DeviceToken deviceToken)`: Recupera las cuentas que registraron un token de dispositivo.
- `existsByEmail(Email email)`: Verifica la unicidad de un correo antes del registro.
- `save(User user)`: Persiste un usuario nuevo o actualizado.

En la Domain Layer de SkillSwap, específicamente dentro del Bounded Context de Identity & Access, se ha definido la gestión de identidades bajo un modelo de Domain-Driven Design (DDD). La clase `User` actúa como el Agregado raíz que centraliza la información de la cuenta y su asociación con su rol de cuenta (Student, el único rol; el perfil de Verificador se gestiona en Assessment & Peer Review), garantizando que el acceso y las credenciales se validen estrictamente a través de servicios de dominio como `PasswordHasher` y `EmailDomainValidator`. El agregado también controla la verificación del correo institucional (token de un solo uso con vencimiento), el perfil de intereses con su vector de habilidades, el nombre completo registrado y el token del dispositivo para las notificaciones push. Finalmente, la recuperación y persistencia de estas identidades se gestiona mediante el repositorio `UserRepository`.

#### 2.6.1.2. Interface Layer

En la Interface Layer de SkillSwap, específicamente para el contexto de Identity & Access, se definen los puntos de entrada para la comunicación externa. Esta capa utiliza controladores REST, recursos (DTOs) y ensambladores para desacoplar el modelo de dominio de las representaciones externas, facilitando el registro y la autenticación de los usuarios desde los clientes móviles.

**Resources**

| Nombre | Descripción |
|---|---|
| SignUpResource | DTO que encapsula los datos de entrada (username, email, password y, opcionalmente, fullName) para el registro de una nueva cuenta. |
| SignInResource | DTO que contiene las credenciales necesarias (username, password) para validar el acceso al sistema. |
| UserResource | DTO de salida que representa la información del usuario (id, username, email, role, isVerified, bio, fullName, interests y skillVector) tras una consulta exitosa. |
| AuthenticatedUserResource | Recurso que devuelve el token JWT generado y la información básica del usuario tras un inicio de sesión correcto. |
| VerifyEmailResource | DTO con el token del enlace de verificación del correo institucional. |
| ResendVerificationResource | DTO con el correo de la cuenta a la que se reenvía el enlace de verificación. |
| UpdateInterestProfileResource | DTO con los temas de interés del estudiante y, opcionalmente, su descripción. |
| UpdateUserFullNameResource | DTO con el nombre completo del estudiante. |
| RegisterDeviceTokenResource | DTO con el token de Firebase Cloud Messaging del dispositivo. |
| MessageResource | DTO de salida con un mensaje informativo, como la confirmación del reenvío del enlace de verificación. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| AuthenticationController | POST | `/api/v1/authentication/sign-up` (SignUpResource) | Expone el endpoint para crear una nueva cuenta, validando previamente el dominio institucional del correo. |
| AuthenticationController | POST | `/api/v1/authentication/sign-in` (SignInResource) | Gestiona la autenticación, verificando las credenciales y devolviendo el token de acceso JWT. Una cuenta sin verificar recibe 403 `EmailNotVerified` y se le reenvía el enlace de verificación. |
| AuthenticationController | POST | `/api/v1/authentication/verify-email` (VerifyEmailResource) | Verifica la cuenta con el token del enlace enviado por correo (`400` si el token es inválido o ya se usó, `410` si venció). |
| AuthenticationController | GET | `/api/v1/authentication/verify-email?token=` | Versión del mismo endpoint para el enlace del correo: verifica la cuenta y responde una página HTML con el resultado. |
| AuthenticationController | POST | `/api/v1/authentication/resend-verification` (ResendVerificationResource) | Reenvía el enlace de verificación respetando el intervalo de espera; responde 202 sin revelar si el correo está registrado. |
| UsersController | GET | `/api/v1/users/me` | Retorna el `UserResource` del usuario autenticado. |
| UsersController | GET | `/api/v1/users/{id}` | Retorna el `UserResource` de un usuario por su identificador. |
| UsersController | PATCH | `/api/v1/users/{id}/bio` | Actualiza la descripción del perfil del estudiante. |
| UsersController | PUT | `/api/v1/users/{id}/interests` (UpdateInterestProfileResource) | Registra o reemplaza los temas de interés del estudiante y recalcula su vector de habilidades. |
| UsersController | PATCH | `/api/v1/users/{id}/full-name` (UpdateUserFullNameResource) | Registra el nombre completo del estudiante, que se compara con el titular de sus certificados. |
| UsersController | PUT / DELETE | `/api/v1/users/me/device-token` (RegisterDeviceTokenResource) | Registra u olvida el token de Firebase Cloud Messaging del dispositivo del estudiante autenticado. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| UserResourceFromEntityAssembler | Convierte la entidad de dominio `User` en un `UserResource` para su envío a través de la API. |
| SignUpCommandFromResourceAssembler | Transforma los datos recibidos en `SignUpResource` en un `SignUpCommand` procesable por la capa de aplicación. |
| SignInCommandFromResourceAssembler | Convierte el `SignInResource` en el `SignInCommand` correspondiente para la validación de credenciales. |

Los controladores presentados no contienen reglas de negocio: delegan el procesamiento a la capa de dominio y de aplicación, actuando como una interfaz uniforme entre los clientes móviles (Android Nativo, Flutter) y la lógica de autenticación del sistema.

#### 2.6.1.3. Application Layer

En la Application Layer de SkillSwap, para el contexto de Identity & Access, los handlers son los encargados de procesar los comandos, orquestando la lógica necesaria para cumplir con los casos de uso de registro y autenticación, actuando como mediadores entre la Interface Layer y el Domain Layer.

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| SignUpCommandHandler | Procesa la creación de nuevas cuentas de usuario. | Valida que el email pertenezca al dominio institucional y no esté en uso, cifra la contraseña mediante `PasswordHasher`, instancia el agregado `User` y lo persiste a través de `UserRepository`. |
| SignInCommandHandler | Gestiona el proceso de inicio de sesión y autenticación. | Busca al usuario por `username`, verifica la contraseña comparándola con el hash almacenado mediante `PasswordHasher` y, si la cuenta está verificada, genera un token JWT para la sesión autenticada; si no lo está, deniega el acceso y reenvía el correo de verificación. |
| SendVerificationEmailEventHandler | Envía el correo de verificación tras el registro. | Reacciona al evento `EmailVerificationRequested`, emite un token aleatorio de 256 bits (`EmailVerificationIssuer`), guarda solo su hash SHA-256 con su vencimiento y envía el enlace mediante el puerto `EmailSender`. |
| VerifyEmailCommandHandler / ResendVerificationEmailCommandHandler | Procesan la verificación del correo y el reenvío del enlace (`EmailVerificationCommandServiceImpl`). | Buscan la cuenta por el hash del token y la verifican si el enlace no venció; el reenvío emite un token nuevo que reemplaza al anterior, como máximo una vez por intervalo de espera. |
| UpdateInterestProfileCommandHandler | Procesa la actualización del perfil de intereses. | Reemplaza los temas de interés y recalcula el vector de habilidades consultando el catálogo de habilidades a través de `SkillCatalogContextFacade` (Learning Path Engine). |
| RegisterDeviceTokenCommandHandler / RemoveDeviceTokenCommandHandler | Gestionan el token de notificaciones del dispositivo. | Asocian el token a la cuenta autenticada (retirándolo de otra cuenta que lo tuviera) o lo eliminan. |

**Outbound Services (puertos)**

| Nombre | Descripción |
|---|---|
| EmailSender | Puerto para enviar correos transaccionales (`EmailMessage`), que desacopla la aplicación del proveedor de correo. |
| PushNotificationSender | Puerto para enviar notificaciones push (`PushNotification`) a un token de dispositivo; nunca lanza excepciones y reporta el resultado como `PushDeliveryResult`. |

**Anti-Corruption Layer (fachada)**

| Nombre | Descripción |
|---|---|
| UserNotificationsContextFacade | Permite a los demás Bounded Contexts notificar a un usuario en su dispositivo sin depender del agregado `User`, de su token ni del proveedor de notificaciones. No envía nada si el usuario no registró un token y olvida los tokens que Firebase Cloud Messaging reporta como no registrados. Credential Verification la usa para avisar al estudiante cuando su certificado queda verificado o rechazado. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| UserDto | Objeto que transporta la información pública y operativa del usuario, incluyendo su rol e indicador de verificación. |
| AuthenticationDto | DTO especializado que encapsula la información básica del usuario junto con el token JWT tras una autenticación exitosa. |

En la Application Layer de Identity & Access, los handlers orquestan el flujo de autenticación asegurando que cada registro sea validado contra el dominio institucional antes de persistirse, y que el inicio de sesión solo emita un token JWT cuando las credenciales sean correctas.

#### 2.6.1.4. Infrastructure Layer

En la Infrastructure Layer de SkillSwap, para el contexto de Identity & Access, se implementan los detalles técnicos y las integraciones necesarias para la persistencia y la seguridad de las identidades.

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| UserRepositoryAdapter | Implementación concreta de `UserRepository` que realiza las operaciones CRUD sobre la tabla `users`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |

**Security Services Implementation**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| BCryptPasswordHasher | Implementación técnica de `PasswordHasher` encargada de proteger las contraseñas de los usuarios. | Utiliza el algoritmo BCrypt para generar hashes seguros y validar contraseñas durante el acceso. |
| JwtTokenGenerator | Servicio responsable de la generación de tokens de seguridad para sesiones autenticadas. | Implementa la generación de tokens JWT, codificando el `userId` y el `role` para la autorización de peticiones en los clientes móviles (Android Nativo, Flutter). |

**External Services Integration**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| BrevoEmailSenderAdapter | Implementación de `EmailSender` mediante la API HTTP de correo transaccional de Brevo. | Se usa la API HTTP porque el plan gratuito de Render bloquea el tráfico SMTP saliente. Requiere `BREVO_API_KEY` y `EMAIL_SENDER_ADDRESS`. |
| LoggingEmailSenderAdapter | Implementación de respaldo de `EmailSender`. | Cuando no se configura `BREVO_API_KEY`, escribe el correo con su enlace de verificación en el log en lugar de enviarlo. |
| FirebasePushNotificationAdapter | Implementación de `PushNotificationSender` con el SDK de Firebase Admin. | Envía la notificación al token del dispositivo mediante Firebase Cloud Messaging, con las credenciales de la cuenta de servicio en `FIREBASE_CREDENTIALS_BASE64`. |
| LoggingPushNotificationAdapter | Implementación de respaldo de `PushNotificationSender`. | Cuando no se configuran credenciales de Firebase válidas, escribe la notificación en el log. |

Estos componentes aseguran que la lógica de negocio de Identity & Access se ejecute sobre una infraestructura robusta, con los proveedores de correo (Brevo) y de notificaciones push (Firebase Cloud Messaging) aislados detrás de los puertos `EmailSender` y `PushNotificationSender`.

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 75**

*C4 Model: Component Diagram del Bounded Context Identity & Access*

<p align="center">
  <img src="images-doc/IdentityComponent.svg" alt="Component Diagram - Identity & Access" width="1000">
</p>

*Nota.* Se detalla la segregación entre `AuthenticationController` y `UsersController`, los Command/Query Services, `EmailVerificationIssuer` y los puertos `EmailSender` (Brevo) y `PushNotificationSender` (Firebase Cloud Messaging), evidenciando las relaciones con los demás Bounded Contexts: el evento `UserRegistered`, con el que Recognition & Incentives crea la billetera inicial; la consulta del catálogo de habilidades de Learning Path Engine para normalizar los intereses, y las fachadas `IamContextFacade` y `UserNotificationsContextFacade`, que Credential Verification usa para comparar el titular del certificado y notificar su resultado. La biometría se valida en el dispositivo. Elaboración propia.

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 76**

*Diagrama de Clases UML del Domain Layer de Identity & Access*

<p align="center">
  <img src="images-doc/class-identity-mobile.png" alt="Class Diagram - Identity & Access" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Identity & Access pertenece al agregado raíz `User`, junto con sus Value Objects `Username`, `Email`, `PasswordHash` y `DeviceToken`, y la enumeración `UserRole`, debido a que estos elementos concentran de forma exclusiva la información de cuenta, credenciales y estado de verificación institucional de cada usuario de la plataforma. Se destaca el Value Object `DeviceToken`, que guarda el token de Firebase Cloud Messaging con el que se envían las notificaciones push al dispositivo del estudiante, y los puertos `EmailSender` y `PushNotificationSender`, que desacoplan el envío del correo de verificación y de las notificaciones de sus proveedores.

##### 2.6.1.6.2. Bounded Context Database Design Diagram

**Figura 77**

*Diagrama de Base de Datos del Bounded Context Identity & Access*

<p align="center">
  <img src="images-doc/db-identity-mobile.png" alt="Database Diagram - Identity & Access" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Identity & Access pertenece a la tabla `users`, debido a que es la única tabla que persiste el agregado raíz `User` junto con sus Value Objects embebidos (`username`, `email`, `password_hash`, `role`, `device_token`), sin requerir tablas adicionales: los temas de interés (`interest_topics`) y el vector de habilidades (`skill_vector`) se guardan como arreglos `jsonb` en la misma fila, por lo que un único registro por usuario es suficiente para representar el agregado completo. Se destacan las columnas `verification_token_hash`, `verification_token_expires_at` y `verification_email_sent_at` (migración V6), que soportan el enlace de verificación de un solo uso con un índice único parcial sobre el hash, `full_name` (V9), con el que se compara el titular de los certificados, y `device_token`, que guarda el token de Firebase Cloud Messaging para las notificaciones push.


---


### 2.6.2. Bounded Context: Credential Verification

#### 2.6.2.1. Domain Layer

La capa de dominio de Credential Verification encapsula la lógica de negocio para el registro, extracción de datos y evaluación de riesgo de los certificados subidos por el Estudiante, manteniendo el modelo desacoplado de la tecnología concreta de OCR y de los mecanismos de verificación externos de cada emisor.

**1. Aggregate Root: Certificate**

Descripción: El agregado `Certificate` centraliza el documento subido por el Estudiante, los datos extraídos mediante OCR, y el estado de verificación resultante de la evaluación de riesgo. No conoce ni depende de la lógica específica de ningún emisor externo (SUNEDU, Coursera, etc.), dejando esa integración como un punto de extensión documentado pero fuera del alcance implementado del curso.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del certificado (autogenerado). |
| ownerId | int | Referencia al `User` (Estudiante) propietario del certificado, definido en Identity & Access. |
| holderName | string | Nombre del titular extraído del documento. |
| institutionName | string | Institución o emisor del certificado. |
| courseName | string | Nombre del curso, programa o certificación. |
| issueDate | date | Fecha de emisión del certificado. |
| durationHours | int (nullable) | Carga horaria, si el documento la incluye. |
| certificateNumber | string (nullable) | Número o código del certificado, si aparece. |
| verificationCode | string (nullable) | Código específico de validación, si aparece. |
| verificationUrl | string (nullable) | URL de verificación oficial, si aparece. |
| qrPayload | string (nullable) | Contenido decodificado del código QR, si existe. |
| ocrText | string | Texto completo extraído por OCR, conservado para auditoría y reprocesamiento. |
| fileHash | string | Hash criptográfico del archivo original, usado para detección de duplicados. |
| storageReference | string | Referencia al archivo almacenado en el servicio de almacenamiento en la nube. |
| status | VerificationStatus (VO) | Estado actual del certificado dentro del flujo de verificación. |
| verificationMethod | VerificationMethod (VO) | Mecanismo mediante el cual se intentó verificar el certificado. |
| riskAssessment | RiskAssessment (VO) | Resultado de la evaluación de riesgo aplicada al certificado. |
| holderNameMismatch | boolean | Indica si el titular leído en el certificado no coincide con el nombre completo registrado del estudiante. |
| createdAt | datetime | Fecha de registro del certificado en la plataforma. |
| verifiedAt | datetime (nullable) | Fecha en la que el certificado alcanzó un estado definitivo (`VERIFIED` o `REJECTED`). |

Métodos

- `Certificate(ownerId, fileHash, storageReference)` (Constructor): Registra el documento subido con estado inicial `PENDING`, antes de que se ejecute la extracción OCR.
- `applyExtractedData(holderName, institutionName, courseName, issueDate, durationHours, certificateNumber, verificationCode, verificationUrl, qrPayload, ocrText)`: Completa el agregado con los datos obtenidos por el servicio de extracción, una vez procesado el documento.
- `assessRisk(RiskAssessment riskAssessment)`: Asigna el resultado de la evaluación de riesgo y transiciona el estado del certificado: a `SUSPICIOUS` si el nivel es `HIGH_RISK`, o a `UNVERIFIED` si es `LOW_RISK` o `REVIEW` (a la espera de que el nivel `REVIEW` sea tratado manualmente en una futura iteración).
- `flagHolderNameMismatch()`: Marca que el titular leído en el certificado no coincide con el nombre completo registrado del estudiante; solo aplica a un certificado `PENDING` con titular.
- `resolveDispute(boolean isAuthentic)`: Aplica la decisión del Verificador senior tras la escalación a Moderation & Disputes, transicionando el certificado a `VERIFIED` o `REJECTED` y registrando `verifiedAt`.

**2. Value Object: RiskAssessment**

Descripción: Encapsula el resultado explicable (basado en reglas) de la evaluación de riesgo de un certificado, evitando que la lógica de scoring viva dispersa dentro del agregado.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| score | int | Puntaje acumulado según las reglas de riesgo aplicadas. |
| level | enum | Nivel derivado del score: `LOW_RISK` (0–19), `REVIEW` (20–49), `HIGH_RISK` (50+). |

Métodos

- `RiskAssessment(int score)` (Constructor): Calcula automáticamente el `level` correspondiente a partir del score recibido.

**3. Value Object: VerificationStatus**

Descripción: Enumeración que restringe los estados válidos del ciclo de vida de un certificado.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `PENDING`, `UNVERIFIED`, `SUSPICIOUS`, `VERIFIED`, `REJECTED`. |

**4. Value Object: VerificationMethod**

Descripción: Enumeración que documenta los mecanismos de verificación contemplados en el diseño. Para el alcance implementado en el curso solo se ejecutan `OCR_ONLY` y `MANUAL`; `QR`, `ISSUER_URL` y `OFFICIAL_REGISTRY` quedan documentados como extensión futura, sin lógica de integración activa.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `OCR_ONLY`, `QR`, `ISSUER_URL`, `OFFICIAL_REGISTRY`, `MANUAL`. |

**5. Domain Service: CertificateExtractionService**

Descripción: Define el contrato para extraer los datos estructurados de un documento de certificado, desacoplando el dominio de la tecnología concreta de OCR (ML Kit).

Métodos

- `extract(byte[] rawDocument)`: Recibe el documento crudo y retorna los campos extraídos (holderName, institutionName, courseName, issueDate, durationHours, certificateNumber, verificationCode, verificationUrl, qrPayload, ocrText) junto con el texto completo reconocido.

**6. Domain Service: CertificateRiskScorer**

Descripción: Define el contrato para calcular el `RiskAssessment` de un certificado a partir de un conjunto explicable de reglas, sin depender de fuentes de verificación externas.

Métodos

- `calculateRisk(boolean duplicateCertificateNumber, boolean duplicateVerificationCode, boolean duplicateFileHash, boolean ocrInconsistencies, boolean holderNameMismatch)`: Aplica las reglas de riesgo (+30 número de certificado duplicado, +30 código de verificación duplicado, +15 inconsistencias detectadas por OCR, +50 archivo ya registrado por otro estudiante y +50 titular distinto del nombre registrado del estudiante) y retorna el `RiskAssessment` resultante. Las dos últimas reglas bastan por sí solas para alcanzar el nivel `HIGH_RISK`.

**7. Domain Service: HolderNameMatcher**

Descripción: Compara el titular leído en el certificado con el nombre completo registrado del estudiante sin considerar tildes, mayúsculas ni el orden de los nombres, y admite un segundo nombre o apellido omitido y las iniciales. Si alguno de los dos nombres falta, no hay comparación.

**8. Domain Events: CertificateFlaggedSuspicious, CertificateVerified y CertificateVerificationResolved**

Descripción: `CertificateFlaggedSuspicious` se publica cuando un certificado queda `SUSPICIOUS`, con los motivos de la sospecha, y lo consume Moderation & Disputes para escalarlo a un Verificador senior. `CertificateVerified` se publica cuando un certificado queda `VERIFIED`, y lo consume Learning Path Engine para completar los nodos que el certificado cubre. `CertificateVerificationResolved` se publica cuando el certificado alcanza un estado definitivo (`VERIFIED` o `REJECTED`) y dispara la notificación push al estudiante.

**9. Repository: CertificateRepository**

Descripción: Interfaz para la persistencia y recuperación de datos del agregado `Certificate`, incluyendo las consultas necesarias para la detección de duplicados.

Métodos

- `findById(int id)`: Recupera un certificado por su identificador.
- `findByOwnerId(int ownerId)`: Recupera todos los certificados subidos por un Estudiante.
- `existsByCertificateNumber(String certificateNumber)`: Verifica si un número de certificado ya fue registrado por otro usuario.
- `existsByVerificationCode(String verificationCode)`: Verifica si un código de verificación ya fue registrado.
- `existsByFileHash(String fileHash)`: Verifica si el archivo ya fue registrado previamente.
- `existsByFileHashExcludingOwner(String fileHash, int ownerId)`: Verifica si otro estudiante ya registró el mismo archivo.
- `save(Certificate certificate)`: Persiste un certificado nuevo o actualizado.

En la Domain Layer de SkillSwap, dentro del Bounded Context de Credential Verification, la clase `Certificate` actúa como Agregado raíz que centraliza el documento subido y su estado de verificación, apoyándose en los servicios de dominio `CertificateExtractionService` para la extracción de datos y `CertificateRiskScorer` para la evaluación explicable de riesgo. La separación conceptual entre "qué certificado presentó el usuario" (`Certificate`), "qué mecanismo se usó para intentar verificarlo" (`VerificationMethod`) y "qué señales de riesgo se detectaron" (`RiskAssessment`) permite incorporar en el futuro nuevos verificadores oficiales sin modificar el agregado principal.

#### 2.6.2.2. Interface Layer

En la Interface Layer de SkillSwap, para el contexto de Credential Verification, se definen los puntos de entrada REST que permiten al Estudiante subir certificados y consultar su estado de verificación desde los clientes móviles.

**Resources**

| Nombre | Descripción |
|---|---|
| UploadCertificateResource | DTO que encapsula el archivo del certificado (imagen/PDF) y el identificador del propietario para su registro inicial. |
| CertificateResource | DTO de salida que representa un certificado con sus datos extraídos, estado de verificación y nivel de riesgo. |
| CertificateListResource | Colección de `CertificateResource` correspondiente a los certificados de un Estudiante. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| CertificateController | POST | `/api/v1/certificates` (UploadCertificateResource) | Registra un nuevo certificado y dispara su procesamiento (extracción OCR y evaluación de riesgo). |
| CertificateController | GET | `/api/v1/certificates/{id}` | Consulta el detalle y estado actual de un certificado específico. |
| CertificateController | GET | `/api/v1/certificates?ownerId={ownerId}` | Lista los certificados subidos por un Estudiante. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| CertificateResourceFromEntityAssembler | Convierte la entidad de dominio `Certificate` en un `CertificateResource` para su envío a través de la API. |
| UploadCertificateCommandFromResourceAssembler | Transforma los datos recibidos en `UploadCertificateResource` en un `UploadCertificateCommand` procesable por la capa de aplicación. |

Los controladores no contienen reglas de negocio: delegan el procesamiento de extracción y evaluación de riesgo a la capa de aplicación, actuando como interfaz uniforme entre los clientes móviles (Android Nativo, Flutter) y la lógica de verificación de certificados.

#### 2.6.2.3. Application Layer

En la Application Layer de SkillSwap, para el contexto de Credential Verification, los handlers orquestan el flujo completo desde la subida del documento hasta la determinación del estado de verificación, coordinando el servicio de extracción, el repositorio y el motor de riesgo.

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| UploadCertificateCommandHandler | Procesa la subida de un nuevo certificado. | Almacena el archivo mediante el servicio de infraestructura de almacenamiento, calcula el `fileHash`, consulta `CertificateRepository` para detectar duplicados (número de certificado, código de verificación y archivo registrado por otro estudiante), compara el titular con el nombre completo registrado del estudiante mediante `HolderNameMatcher`, invoca `CertificateRiskScorer` con dichos resultados, aplica `assessRisk` sobre el agregado y lo persiste. Si el estado resultante es `SUSPICIOUS`, publica `CertificateFlaggedSuspicious` para que Moderation & Disputes lo escale a un Verificador senior. |
| ResolveCertificateDisputeCommandHandler | Aplica la resolución de un certificado escalado. | Recibida la decisión del Verificador senior desde Moderation & Disputes (a través de `CredentialContextFacade`), invoca `resolveDispute` sobre el agregado y lo persiste con su estado definitivo (`VERIFIED` o `REJECTED`); publica `CertificateVerified` cuando queda verificado y `CertificateVerificationResolved` en ambos casos. |
| NotifyCertificateResolutionEventHandler | Notifica al estudiante la resolución de su certificado. | Reacciona a `CertificateVerificationResolved` y envía una notificación push en español mediante `UserNotificationsContextFacade` (Identity & Access), con el motivo cuando el certificado es rechazado; si el estudiante no concedió el permiso de notificaciones no se envía nada y el estado sigue disponible en la consulta de sus certificados. |

**Anti-Corruption Layer (fachada)**

| Nombre | Descripción |
|---|---|
| CredentialContextFacade | Expone a los demás Bounded Contexts los certificados validados de un estudiante y el contenido de un certificado (`CertificateEvidence`) para Learning Path Engine, la vista de un certificado en revisión (`CertificateReviewView`: datos extraídos, evaluación de riesgo y enlace temporal al archivo) y la resolución de un certificado sospechoso para Moderation & Disputes. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| CertificateDto | Objeto que transporta los datos extraídos y el estado operativo del certificado entre capas. |
| RiskAssessmentDto | DTO que transporta el score y nivel de riesgo calculado, previo a su persistencia como Value Object. |

En la Application Layer de Credential Verification, `UploadCertificateCommandHandler` asegura que ningún certificado quede sin una evaluación de riesgo antes de estar disponible como evidencia de habilidad para Learning Path Engine, y que todo certificado clasificado como `SUSPICIOUS` sea escalado a Moderation & Disputes en lugar de resolverse dentro del propio Bounded Context.

#### 2.6.2.4. Infrastructure Layer

En la Infrastructure Layer de SkillSwap, para el contexto de Credential Verification, se implementan los adaptadores técnicos para la persistencia, la extracción OCR y el almacenamiento de archivos.

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| CertificateRepositoryAdapter | Implementación concreta de `CertificateRepository` que realiza las operaciones CRUD sobre la tabla `certificates`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |

**OCR & Storage Services Implementation**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| MlKitCertificateExtractor | Implementación técnica de `CertificateExtractionService`. | Ejecuta el reconocimiento de texto (Text Recognition) y, cuando aplica, la decodificación de código QR (Barcode Scanning) de ML Kit, de forma on-device sobre el documento capturado desde la cámara del dispositivo. |
| CloudinaryStorageAdapter | Servicio responsable de almacenar el archivo original del certificado. | Sube la imagen/PDF a Cloudinary y retorna la referencia (`storageReference`) persistida en el agregado. |

Estos componentes aseguran que la lógica de negocio de Credential Verification permanezca independiente de ML Kit y de Cloudinary, de modo que ambos puedan sustituirse en el futuro sin modificar el Domain Layer ni la Application Layer.

#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 78**

*C4 Model: Component Diagram del Bounded Context Credential Verification*

<p align="center">
  <img src="images-doc/CredentialVerificationComponent.svg" alt="Component Diagram - Credential Verification" width="1000">
</p>

*Nota.* Se detalla la segregación entre el Controller, el Command/Query Service y los adaptadores de Persistencia, extracción OCR (ML Kit on-device) y almacenamiento de archivos (Cloudinary), evidenciando la escalación de certificados en estado SUSPICIOUS hacia Moderation & Disputes y la solicitud entrante de certificados verificados desde Learning Path Engine. Elaboración propia.

#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 79**

*Diagrama de Clases UML del Domain Layer de Credential Verification*

<p align="center">
  <img src="images-doc/class-credential-verification-mobile.png" alt="Class Diagram - Credential Verification" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Credential Verification pertenece al agregado raíz `Certificate`, junto con el Value Object `RiskAssessment` (y su enumeración asociada `RiskLevel`) y las enumeraciones `VerificationStatus` y `VerificationMethod`, debido a que estos elementos concentran de forma exclusiva el documento subido por el Estudiante, los datos extraídos mediante OCR, y el resultado explicable de la evaluación de riesgo — sin depender de la lógica específica de ningún emisor externo (SUNEDU, Coursera, etc.), la cual queda fuera del alcance implementado del curso y documentada únicamente a nivel de `VerificationMethod`.

##### 2.6.2.6.2. Bounded Context Database Design Diagram

**Figura 80**

*Diagrama de Base de Datos del Bounded Context Credential Verification*

<p align="center">
  <img src="images-doc/db-credential-verification-mobile.png" alt="Database Diagram - Credential Verification" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Credential Verification pertenece a la tabla `certificates`, debido a que es la única tabla que persiste el agregado raíz `Certificate` junto con los datos extraídos por OCR, el hash del archivo y el resultado de la evaluación de riesgo — al igual que en Identity & Access, no existe ninguna entidad hija ni colección propia dentro de este agregado, por lo que un único registro por certificado es suficiente. Se destacan los campos `ocr_text`, `qr_payload`, `file_hash` y `storage_reference`, incorporados para el soporte de la captura desde cámara y el procesamiento on-device mediante ML Kit, feature de aprendizaje autónomo del proyecto, y `holder_name_mismatch` (migración V9), que registra si el titular del certificado difiere del nombre registrado del estudiante.


---

### 2.6.3. Bounded Context: Learning Path Engine

#### 2.6.3.1. Domain Layer

La capa de dominio de Learning Path Engine concentra el núcleo de negocio de SkillSwap: interpretar la meta declarada por el Estudiante, comparar sus habilidades ya verificadas contra los requisitos de dicha meta, generar la ruta de aprendizaje personalizada, y producir dinámicamente la evaluación correspondiente a cada nodo de la ruta.

**1. Aggregate Root: LearningPath**

Descripción: El agregado `LearningPath` representa la ruta de aprendizaje personalizada de un Estudiante, compuesta por una secuencia ordenada de nodos (`PathNode`) que deben completarse progresivamente hacia la `CareerGoal` declarada.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único de la ruta (autogenerado). |
| studentId | int | Usuario con rol `Student`, propietario de la ruta. |
| careerGoal | CareerGoal (VO) | Meta profesional/habilidad declarada por el estudiante. |
| nodes | List\<PathNode\> | Secuencia ordenada de nodos que componen la ruta. |
| status | PathStatus (VO) | Estado general de la ruta: `active`, `paused` (conserva su progreso, pero no admite nuevas evaluaciones ni intentos; un caso de verificación ya abierto en ella todavía puede completar su nodo) o `completed`. |
| createdAt | timestamp | Fecha de generación de la ruta. |
| updatedAt | timestamp | Fecha de la última recalculación de la ruta. |
| lastProgressAt | timestamp | Fecha del último avance del Estudiante en la ruta. Cuando vence el plan mensual, se mantiene activa la ruta con el valor más reciente. |
| advanced | boolean | Indica si la ruta se inició con un desbloqueo de ruta avanzada canjeado con SkillCredits. Una ruta avanzada no se cuenta en las rutas activas ni en el total del plan, y nunca se pausa al volver al plan gratuito. |

Métodos

- `LearningPath(studentId, careerGoal, nodes)` (Constructor): Crea la ruta en estado `active` a partir del resultado de `LearningPathBuilder`.
- `recalculate(SkillGap updatedGap)`: Regenera la secuencia de nodos pendientes cuando el estudiante certifica una nueva habilidad (por ejemplo, al aprobar un `Certificate` en Credential Verification), sin alterar los nodos ya completados.
- `completeNode(int nodeId)`: Marca un `PathNode` como `completed` y, si era el último nodo pendiente, transiciona la ruta completa a `completed`.
- `recognizeCertifiedSkill(String skillTag, int certificateId)`: Completa el nodo pendiente de esa habilidad con un certificado validado por un Verificador, lo vincula al certificado y desbloquea los nodos siguientes, sin alterar los nodos ya completados.
- `associateCertificate(int nodeId, int certificateId)`: Vincula a un nodo pendiente un certificado cuyo contenido corresponde a su habilidad, como evidencia que habilita su evaluación práctica.
- `pause()`: Transiciona la ruta de `active` a `paused`, conservando el estado de sus nodos; se usa cuando el Estudiante vuelve al plan gratuito con más rutas activas de las que permite ese plan, o cuando pausa su ruta activa para reactivar otra.
- `resume()`: Transiciona la ruta de `paused` a `active`, siempre que el plan del Estudiante admita otra ruta activa.

**2. Entity: PathNode**

Descripción: Representa un paso individual dentro de la ruta, correspondiente a una habilidad específica que el estudiante debe demostrar.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del nodo. |
| skillTag | string | Habilidad asociada al nodo, referenciada contra la taxonomía interna de skills. |
| order | int | Posición del nodo dentro de la secuencia de la ruta. |
| status | NodeStatus (VO) | Estado del nodo: `locked`, `available`, `completed`. |
| linkedCertificateId | int (nullable) | Referencia al `Certificate` (Credential Verification) vinculado al nodo, como evidencia o como habilidad ya demostrada. |
| completedByCertificate | boolean | Indica si el nodo se completó con un certificado validado por un Verificador, a diferencia de un nodo completado al aprobar su evaluación. |
| assessmentBlueprintId | int (nullable) | Referencia al `AssessmentBlueprint` generado para demostrar este nodo, una vez solicitado. |

**3. Value Object: CareerGoal**

Descripción: Encapsula la meta declarada por el estudiante en texto libre junto con su traducción a la taxonomía interna de habilidades.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| rawText | string | Texto libre ingresado por el estudiante (ej. "quiero aprender APIs REST con autenticación JWT"). |
| mappedSkillTags | List\<String\> | Habilidades de la taxonomía interna resueltas a partir del texto libre. |

Métodos

- `CareerGoal(String rawText, List<String> mappedSkillTags)` (Constructor): Valida que exista al menos un `skillTag` resuelto; en caso contrario, lanza una excepción de dominio indicando que la meta no pudo interpretarse.

**4. Value Object: SkillGap**

Descripción: Representa la diferencia entre las habilidades ya verificadas del estudiante y las requeridas por su `CareerGoal`.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| verifiedSkillTags | List\<String\> | Habilidades que el estudiante ya demostró (vía certificado validado o nodo previamente completado). |
| missingSkillTags | List\<String\> | Habilidades pendientes de demostrar para alcanzar la `CareerGoal`. |

**5. Aggregate Root: AssessmentBlueprint**

Descripción: El agregado `AssessmentBlueprint` representa la especificación de la evaluación generada dinámicamente por IA para demostrar la habilidad de un `PathNode` específico. Es consumido como Downstream por Assessment & Peer Review para ejecutar el intento del estudiante y calificarlo, sin que dicho Bounded Context conozca cómo se generó el contenido.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del blueprint. |
| pathNodeId | int | Nodo de la ruta al que corresponde esta evaluación. |
| skillTag | string | Habilidad evaluada. |
| questions | List\<Question\> | Preguntas generadas dinámicamente por IA. |
| generatedAt | timestamp | Fecha de generación del blueprint. |

Métodos

- `AssessmentBlueprint(pathNodeId, skillTag, questions)` (Constructor): Registra el resultado producido por `QuestionGenerationService` para un nodo específico.

**6. Aggregate Root: AdvancedPathUnlock**

Descripción: Representa el derecho a iniciar una ruta avanzada que el estudiante obtiene al canjear ese beneficio con SkillCredits en Recognition & Incentives. Se crea un desbloqueo por canje y queda disponible hasta que el estudiante inicia la ruta avanzada con él.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del desbloqueo. |
| studentId | int | Estudiante que canjeó el beneficio. |
| redemptionId | int | Transacción de canje de Recognition & Incentives que otorgó el desbloqueo (referencia por id). |
| learningPathId | int (nullable) | Ruta avanzada iniciada con el desbloqueo; nula mientras está disponible. |
| grantedAt | timestamp | Fecha en que se otorgó el desbloqueo. |
| usedAt | timestamp (nullable) | Fecha en que se inició la ruta avanzada. |

Métodos

- `AdvancedPathUnlock(studentId, redemptionId)` (Constructor): Registra el desbloqueo disponible otorgado por un canje.
- `useFor(int learningPathId)`: Consume el desbloqueo al iniciar la ruta avanzada.
- `isAvailable()`: Indica si el desbloqueo todavía no se usó.

**7. Entity: Question**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| questionString | string | Enunciado de la pregunta generada. |
| answers | List\<String\> | Lista de 4 posibles respuestas. |
| correctAnswer | int | Índice (0 a 3) de la respuesta correcta. |

**8. Domain Service: SkillGapAnalyzer**

Descripción: Define el contrato para calcular el `SkillGap` de un estudiante comparando sus habilidades verificadas contra los requisitos de su `CareerGoal`.

Métodos

- `analyze(CareerGoal goal, List<String> verifiedSkillTags)`: Retorna el `SkillGap` resultante.

**9. Domain Service: LearningPathBuilder**

Descripción: Define el contrato para construir la secuencia ordenada de `PathNode` a partir de un `SkillGap`, respetando las dependencias/prerequisitos entre habilidades de la taxonomía interna.

Métodos

- `buildPath(SkillGap gap)`: Retorna la lista ordenada de `PathNode` en estado `locked`/`available` según sus dependencias.

**10. Domain Service: QuestionGenerationService**

Descripción: Define el contrato para generar dinámicamente las preguntas de un `AssessmentBlueprint` a partir de una habilidad declarada, desacoplando el dominio del proveedor concreto de IA generativa.

Métodos

- `generateQuestions(String skillTag)`: Retorna una lista de `Question` generadas para evaluar la habilidad indicada. En un nuevo intento recibe como exclusiones las preguntas de los blueprints anteriores del nodo, de modo que el estudiante no reciba preguntas repetidas.

**11. Repository: LearningPathRepository, AssessmentBlueprintRepository, AdvancedPathUnlockRepository**

Métodos

- `findByStudentId(int studentId)`, `save(LearningPath path)` (LearningPathRepository).
- `findByPathNodeId(int pathNodeId)`, `save(AssessmentBlueprint blueprint)` (AssessmentBlueprintRepository).
- `findByStudentId(int studentId)`, `existsByRedemptionId(int redemptionId)` y `save(AdvancedPathUnlock unlock)` (AdvancedPathUnlockRepository).

En la Domain Layer de SkillSwap, dentro del Bounded Context de Learning Path Engine, el agregado `LearningPath` centraliza la ruta personalizada del estudiante apoyándose en `SkillGapAnalyzer` y `LearningPathBuilder` para su construcción y recálculo, mientras que `AssessmentBlueprint` encapsula la generación de contenido evaluativo mediante `QuestionGenerationService`, manteniendo la separación entre "qué ruta necesita el estudiante" y "qué evaluación demuestra cada paso de esa ruta". `AdvancedPathUnlock` registra el beneficio canjeado con SkillCredits que permite iniciar una ruta avanzada fuera de los límites del plan.

#### 2.6.3.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| DeclareGoalResource | DTO de entrada con el texto libre de la meta declarada por el estudiante. |
| LearningPathResource | DTO de salida que representa la ruta completa con sus nodos y estados. |
| PathNodeResource | DTO de salida que representa un nodo individual de la ruta. |
| AssessmentBlueprintResource | DTO de salida que representa las preguntas generadas para un nodo, sin exponer `correctAnswer`. |
| LinkCertificateResource | DTO de entrada con el `certificateId` que el estudiante asocia a un nodo. |
| CertificateLinkResource | DTO de salida con la afinidad calculada, el umbral y si la evaluación del nodo quedó habilitada. |
| AdvancedPathUnlockResource | DTO de salida que representa un desbloqueo de ruta avanzada y si está disponible. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| LearningPathsController | POST | `/api/v1/learning-paths` (DeclareGoalResource) | Recibe la meta del estudiante, genera el `SkillGap` inicial y construye la ruta, siempre que el plan admita otra ruta activa y otra ruta en total (`409 PlanLimitReached` en caso contrario). Con `"advanced": true` inicia una ruta avanzada con un desbloqueo disponible, sin contarla en los límites del plan (`409 AdvancedPathUnlockRequired` si no tiene uno). |
| LearningPathsController | GET | `/api/v1/learning-paths/{studentId}` | Retorna la ruta más reciente del estudiante con el estado de cada nodo. |
| LearningPathsController | GET | `/api/v1/learning-paths?studentId={studentId}` | Retorna todas las rutas del estudiante (activas, pausadas y completadas), de la más reciente a la más antigua. Solo el propio estudiante. |
| LearningPathsController | PATCH | `/api/v1/learning-paths/{pathId}/pause` | Pausa una ruta activa del estudiante, que conserva su progreso. `409 PathNotActive` si la ruta no está activa. |
| LearningPathsController | PATCH | `/api/v1/learning-paths/{pathId}/resume` | Reactiva una ruta pausada si el plan admite otra ruta activa; en el plan gratuito, primero debe pausarse la ruta activa. `409 PathNotPaused` o `409 PlanLimitReached`. |
| AssessmentBlueprintsController | POST | `/api/v1/path-nodes/{nodeId}/assessment-blueprint` | Solicita la generación de la evaluación correspondiente a un nodo `available`. |
| PathNodeCertificatesController | POST | `/api/v1/path-nodes/{nodeId}/certificate` (LinkCertificateResource) | Compara el contenido del certificado verificado (curso y texto OCR) con la habilidad del nodo: con una afinidad de al menos 0,7 lo vincula y habilita la evaluación práctica; por debajo del umbral responde `422 CertificateSkillMismatch` con los nodos pendientes que el certificado sí cubre. |
| AdvancedPathUnlocksController | GET | `/api/v1/advanced-path-unlocks` | Lista los desbloqueos de ruta avanzada del estudiante autenticado, indicando cuáles están disponibles. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| LearningPathResourceFromEntityAssembler | Convierte `LearningPath` en `LearningPathResource`. |
| AssessmentBlueprintResourceFromEntityAssembler | Convierte `AssessmentBlueprint` en `AssessmentBlueprintResource`, omitiendo `correctAnswer` de cada pregunta. |
| DeclareGoalCommandFromResourceAssembler | Transforma `DeclareGoalResource` en `DeclareGoalCommand`. |

**Errores de los límites del plan**

`PlanLimitReached` (409), que reemplaza a `ActivePathAlreadyExists` del Sprint 1, incluye los campos `limit` (`ActiveRoutes` o `TotalRoutes`), `plan` (`Free` o `Premium`), `max`, `current` y `upgradeAvailable`, para que la aplicación muestre la pantalla "Alcanzaste el límite de tu plan". `PathNotActive` y `PathNotPaused` (409) protegen la pausa y la reanudación, y `PathPaused` (409) rechaza la generación de una evaluación en una ruta pausada.

#### 2.6.3.3. Application Layer

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| DeclareGoalCommandHandler | Procesa la declaración inicial de la meta del estudiante. | Interpreta el texto libre contra la taxonomía interna de skills mediante el puerto `SkillTaxonomyMatcher`, consulta a Credential Verification las habilidades ya respaldadas por certificados válidos, invoca `SkillGapAnalyzer` y `LearningPathBuilder`, instancia `LearningPath` y lo persiste. |
| RecognizeValidatedCertificateEventHandler | Procesa la actualización de la ruta tras un certificado validado. | Reacciona al evento `CertificateVerified` de Credential Verification y completa, en las rutas no completadas del estudiante, los nodos pendientes cuya habilidad cubre el certificado, desbloqueando los siguientes y conservando los nodos ya completados. |
| LinkCertificateToNodeCommandHandler | Procesa la asociación de un certificado a un nodo. | Obtiene el contenido del certificado mediante `CredentialContextFacade`, calcula su afinidad con la habilidad del nodo mediante el puerto `CertificateSkillAffinityScorer` y lo vincula si alcanza el umbral, o sugiere los nodos que sí cubre. |
| GrantAdvancedPathUnlockEventHandler | Otorga el desbloqueo de ruta avanzada. | Reacciona al evento `AdvancedPathUnlockRedeemed` de Recognition & Incentives y crea un `AdvancedPathUnlock` por canje, de forma idempotente. |
| GenerateAssessmentBlueprintCommandHandler | Procesa la solicitud de evaluación para un nodo. | Invoca `QuestionGenerationService` con el `skillTag` del nodo y las preguntas de los intentos anteriores como exclusiones, instancia `AssessmentBlueprint` y lo persiste, dejándolo disponible para que Assessment & Peer Review lo consuma. Si la variable `LEARNING_PATH_ASSESSMENT_REQUIRE_LINKED_CERTIFICATE` está activa, exige un certificado vinculado al nodo (`409 CertificateRequired`). |
| GetLearningPathQueryHandler | Recupera la ruta activa de un estudiante. | Consulta `LearningPathRepository.findByStudentId()`. |
| LearningPathCommandService.handle(PauseLearningPathCommand / ResumeLearningPathCommand) | Procesa la pausa y la reanudación de una ruta. | Valida que el estudiante sea el dueño y el estado de la ruta; al reanudar, consulta los límites del plan vigente y responde `PlanLimitReached` si el estudiante ya tiene el máximo de rutas activas. |
| EnforcePlanLimitsEventHandler | Reacciona al evento `SubscriptionExpired` de Subscription & Billing. | En una transacción propia, envía `EnforcePlanLimitsCommand`: mantiene activa la ruta con el `lastProgressAt` más reciente y pausa las demás rutas activas, sin eliminar nada; las rutas avanzadas nunca se pausan. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| LearningPathDto | Objeto que transporta la ruta y sus nodos entre capas. |
| AssessmentBlueprintDto | Objeto que transporta el blueprint generado, incluyendo `correctAnswer` únicamente hacia Assessment & Peer Review (nunca hacia el cliente). |

**Outbound Services**

| Nombre | Descripción |
|---|---|
| SkillTaxonomyMatcher | Puerto (interfaz) que traduce el texto libre de la meta a los `skillTag` de la taxonomía interna, desacoplando la Application Layer de la técnica de interpretación. Retorna una lista vacía cuando el texto no corresponde a ninguna habilidad del catálogo. Sus adaptadores se describen en la Infrastructure Layer. |
| CertificateSkillAffinityScorer | Puerto que calcula la afinidad (`SkillAffinity`, de 0 a 1) entre el contenido de un certificado y la habilidad de un nodo. |

Los límites del plan no se garantizan en la base de datos: la migración V4 eliminó el índice único parcial `ux_learning_paths_one_active_per_student`, y el servicio de aplicación valida, al declarar una meta y al reanudar una ruta, el límite de rutas activas y de rutas en total del plan vigente (1 activa y 3 en total en el plan gratuito; 3 activas y sin tope en el plan mensual). Las rutas completadas cuentan para el total de 3 del plan gratuito, y las rutas avanzadas iniciadas con un desbloqueo canjeado con SkillCredits no cuentan en ninguno de los dos límites. Los límites se obtienen de Subscription & Billing mediante `SubscriptionContextFacade.getPlanLimits(studentId)`, que retorna `PlanLimitsView` (Anticorruption Layer), y cada operación toma un bloqueo transaccional de PostgreSQL por estudiante (`pg_advisory_xact_lock`) para que dos solicitudes simultáneas no superen el límite. Una ruta pausada no admite nuevas evaluaciones ni intentos, pero acepta que se complete un nodo cuando se resuelve un caso de verificación que ya estaba en curso.

#### 2.6.3.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| LearningPathRepositoryAdapter | Implementación concreta de `LearningPathRepository` sobre las tablas `learning_paths` y `path_nodes`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| AssessmentBlueprintRepositoryAdapter | Implementación concreta de `AssessmentBlueprintRepository` sobre la tabla `assessment_blueprints`. | ORM del stack backend. La lista de preguntas se persiste mediante un converter JSON, siguiendo el mismo criterio que ya aplicaron en el `Quiz` del proyecto base. |

**AI Services Implementation**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| GeminiSkillTaxonomyMatcher | Adaptador principal del puerto `SkillTaxonomyMatcher` (Anticorruption Layer hacia la Gemini API), con el que el backend resuelve `CareerGoal.mappedSkillTags`. | Envía a Gemini la meta junto con el catálogo interno (`skill-catalog.json`), solicita una respuesta JSON con los `skillTag` seleccionados, descarta toda habilidad que no figure en el catálogo y conserva hasta 8. Si Gemini falla, excede el tiempo de espera (`GEMINI_GOAL_INTERPRETATION_TIMEOUT_SECONDS`, 20 segundos por defecto) o no selecciona ninguna habilidad válida, delega en `KeywordSkillTaxonomyMatcher`. |
| KeywordSkillTaxonomyMatcher | Adaptador de respaldo del puerto `SkillTaxonomyMatcher`; es el único que se usa cuando `GEMINI_GOAL_INTERPRETATION_ENABLED=false` o no hay clave de Gemini. | Compara el texto libre, normalizado sin mayúsculas ni tildes, contra las palabras clave de cada habilidad del catálogo interno, solo por palabra o frase completa, sin depender de un motor de embeddings/vector search ni de un servicio externo. |
| GeminiClient | Cliente compartido de la Gemini API. | Concentra la clave, la cadena de modelos de respaldo (`GEMINI_FALLBACK_MODELS`), los reintentos y los tiempos de espera; lo usan `GeminiSkillTaxonomyMatcher` y `GeminiQuestionGenerator`. |
| GeminiQuestionGenerator | Implementación técnica de `QuestionGenerationService`. | Invoca la Gemini API mediante `GeminiClient` con un prompt estructurado por `skillTag`, que incluye las preguntas ya usadas en el nodo como exclusiones, y solicita un formato de respuesta JSON con las preguntas, alternativas y respuesta correcta, para su conversión directa en objetos `Question`. Las preguntas repetidas se reemplazan con una nueva solicitud (hasta 2) y, si siguen faltando preguntas nuevas, responde `503 QuestionGenerationFailed` sin cambiar el nodo. |
| KeywordCertificateSkillAffinityScorer | Implementación de `CertificateSkillAffinityScorer` con las palabras clave del catálogo. | Afinidad 1,0 si el nombre del curso menciona la habilidad, 0,75 si el texto OCR menciona dos o más de sus palabras clave, 0,5 con una sola mención y 0 sin menciones; el umbral de correspondencia es 0,7. |

En ambos adaptadores de `SkillTaxonomyMatcher`, el catálogo de habilidades es la fuente de verdad: ninguna habilidad que no figure en él llega a la ruta, y el cálculo de la brecha y el orden de los nodos siguen a cargo de `SkillGapAnalyzer` y `LearningPathBuilder`, de forma determinista. Estos componentes garantizan que el algoritmo de matching de habilidades y el proveedor de IA generativa puedan sustituirse (por ejemplo, por un motor de embeddings) sin modificar el Domain Layer ni la Application Layer.

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 81**

*C4 Model: Component Diagram del Bounded Context Learning Path Engine*

<p align="center">
  <img src="images-doc/LearningPathEngineComponent.svg" alt="Component Diagram - Learning Path Engine" width="1000">
</p>

*Nota.* Se detalla la segregación entre los Controllers de `LearningPath` y `AssessmentBlueprint`, el Command/Query Service, el componente interno `SkillTaxonomy Matcher` (representado como un único componente; corresponde al puerto `SkillTaxonomyMatcher` descrito en 2.6.3.4, que solo selecciona habilidades del catálogo interno) y el adaptador de generación de preguntas `GeminiQuestionGenerator` hacia la Gemini API, evidenciando la solicitud de certificados verificados hacia Credential Verification, la notificación entrante de certificados verificados desde ese mismo Bounded Context, y las solicitudes entrantes de Assessment & Peer Review (blueprint del nodo y notificación de nodo demostrado), la consulta de los límites de rutas del plan a `SubscriptionContextFacade` y `EnforcePlanLimitsEventHandler`, que pausa las rutas activas adicionales al recibir `SubscriptionExpired`. Elaboración propia.

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 82**

*Diagrama de Clases UML del Domain Layer de Learning Path Engine*

<p align="center">
  <img src="images-doc/class-learning-path-engine-mobile.png" alt="Class Diagram - Learning Path Engine" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. El puerto `SkillTaxonomyMatcher` y sus adaptadores no aparecen porque pertenecen a las capas de aplicación e infraestructura. Elaboración propia.

El modelado de clases de Learning Path Engine pertenece a los agregados raíz `LearningPath` y `AssessmentBlueprint`, junto con la entidad `PathNode`, los Value Objects `CareerGoal` y `SkillGap`, y la entidad `Question` embebida en `AssessmentBlueprint`, debido a que estos elementos concentran de forma exclusiva el business core de la plataforma: la interpretación de la meta del estudiante, el cálculo de la brecha de habilidad, la secuencia de nodos de la ruta personalizada y el contenido evaluativo generado dinámicamente por IA para cada nodo.

##### 2.6.3.6.2. Bounded Context Database Design Diagram

**Figura 83**

*Diagrama de Base de Datos del Bounded Context Learning Path Engine*

<p align="center">
  <img src="images-doc/db-learning-path-engine-mobile.png" alt="Database Diagram - Learning Path Engine" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Learning Path Engine pertenece a las tablas `learning_paths`, `path_nodes`, `assessment_blueprints` y `advanced_path_unlocks`, debido a que persisten de forma normalizada la ruta de aprendizaje del estudiante (`learning_paths`), cada paso individual de dicha ruta con su estado de avance (`path_nodes`), la evaluación generada dinámicamente por IA para demostrar la habilidad de un nodo específico (`assessment_blueprints`) y los desbloqueos de ruta avanzada canjeados con SkillCredits (`advanced_path_unlocks`) — una relación uno a muchos entre rutas y nodos, y entre cada nodo y sus blueprints de evaluación. Se destacan `path_nodes.completed_by_certificate` (migración V8), que distingue un nodo completado con un certificado validado, y `learning_paths.is_advanced` (V10), que excluye la ruta avanzada de los límites del plan.

---

### 2.6.4. Bounded Context: Assessment & Peer Review

#### 2.6.4.1. Domain Layer

La capa de dominio de Assessment & Peer Review concentra las reglas de negocio de la ejecución de la evaluación generada por la IA, y la asignación y resolución de un Verificador cuando dicha evaluación no es aprobada, sin depender de ninguna sesión de comunicación en tiempo real entre los participantes. En esta versión, un Estudiante se habilita como Verificador de una habilidad al completar el nodo correspondiente de su ruta, y cada intento no aprobado abre un caso de verificación mientras el Estudiante tenga escalamientos disponibles en el mes según su plan; no existe un examen de ingreso ni un límite de intentos por nodo.

**1. Aggregate Root: AssessmentAttempt**

Descripción: El agregado `AssessmentAttempt` representa el intento de un Estudiante al resolver el `AssessmentBlueprint` de un nodo de su ruta, calculando el puntaje de forma centralizada en el servidor para evitar manipulación desde el cliente.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del intento (autogenerado). |
| blueprintId | int | Referencia al `AssessmentBlueprint` (Learning Path Engine) resuelto. Único: solo se acepta un intento por blueprint. |
| studentId | int | Usuario `Student` que resuelve la evaluación (sale del token, nunca del request). |
| selectedAnswers | List\<Integer\> | Índices seleccionados por el estudiante para cada pregunta. |
| score | Score (VO) | Puntaje obtenido. |
| passed | boolean | Indica si el puntaje alcanzó el umbral de aprobación (4 de 5). |
| completedAt | timestamp | Fecha y hora de finalización del intento. |

Métodos

- `AssessmentAttempt(blueprintId, studentId, selectedAnswers, blueprintQuestions)` (Constructor): Calcula el `score` comparando `selectedAnswers` contra `correctAnswer` de cada pregunta del blueprint, y determina `passed` cuando el puntaje alcanza 4 de 5 (umbral fijo del dominio, sin configuración por habilidad).

**2. Value Object: Score**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | int | Puntaje obtenido. |
| total | int | Puntaje máximo posible (5). |

**3. Aggregate Root: VerifierProfile**

Descripción: El agregado `VerifierProfile` representa la elegibilidad de un usuario `Student` (que ya completó el nodo correspondiente de su propia ruta) para revisar casos de otros estudiantes en esa misma habilidad.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del perfil de Verificador (autogenerado). |
| verifierUserId | int | Referencia al usuario `Student` (Identity & Access) que posee este perfil. Único. |
| skillTags | List\<String\> | Habilidades que el Verificador está habilitado para revisar, en el orden en que las fue habilitando. |
| available | boolean | Indica si el Verificador puede recibir nuevos casos asignados. |
| verified | boolean | Indica si el perfil se mantiene habilitado. Un perfil revocado (`false`) no puede reactivarse habilitando una nueva habilidad. |
| rating | double | Confiabilidad del Verificador (0 a 100), escrita exclusivamente por Reputation vía facade. |
| reviewCount | int | Cantidad de casos resueltos, incrementado por este mismo Bounded Context al resolver un caso. |
| createdAt | timestamp | Fecha de creación del perfil. |

Métodos

- `VerifierProfile(verifierUserId, skillTag)` (Constructor): Crea el perfil en estado `available` y `verified`, exigiendo que el estudiante tenga ese nodo de habilidad ya `COMPLETED` en su ruta.
- `AddSkill(String skillTag)`: Agrega una nueva habilidad habilitada para revisar, cuando el estudiante certifica un nodo adicional. Si el perfil no existe aún, esta operación lo crea (primera llamada → `201`; llamadas siguientes → `200`).
- `SetAvailability(boolean available)`: Actualiza si el Verificador puede recibir nuevos casos.
- `IncrementReviewCount()`: Incrementa el conteo de casos resueltos. Lo invoca este mismo Bounded Context al resolver un `VerificationCase`.
- `UpdateRating(double rating)`: Sincroniza la confiabilidad calculada por Reputation, vía `VerifierProfileContextFacade`.
- `revoke()`: Marca el perfil como no verificado y no disponible (`verified = false`, `available = false`), impidiendo que reciba nuevos casos.

**4. Aggregate Root: VerificationCase**

Descripción: El agregado `VerificationCase` representa el caso abierto cuando un `AssessmentAttempt` no alcanza el umbral de aprobación, gobernando su asignación a un Verificador disponible y la resolución con rúbrica estructurada.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del caso (autogenerado). |
| attemptId | int | Referencia al `AssessmentAttempt` que originó el caso. Único: un intento abre como máximo un caso. |
| studentId | int | Estudiante cuyo intento generó el caso. |
| verifierUserId | int (nullable) | Verificador asignado, nulo hasta la asignación o si no hay candidatos disponibles. |
| pathNodeId | int | Nodo de la ruta (Learning Path Engine) al que corresponde el caso. |
| skillTag | string | Habilidad en evaluación. |
| caseType | enum | Tipo de caso, según la evaluación del nodo que lo originó: `QUIZ` o `MINI_PROJECT`. Determina cuántos SkillCredits recibe el Verificador al resolverlo (25 o 40). |
| status | CaseStatus (VO) | Estado actual del caso. |
| decision | ReviewDecision (VO, nullable) | Resultado de la revisión, nulo hasta resolverse. |
| rubricNotes | string (nullable, 1-2000 caracteres) | Observaciones del Verificador al resolver el caso; obligatorias al resolver. |
| evidenceUrl | string (nullable, máx. 500 caracteres) | URL externa aportada por el estudiante como evidencia (portafolio/proyecto). Una URL nueva reemplaza la anterior; no es una subida de archivo. |
| openedAt | timestamp | Fecha de apertura del caso. |
| assignedAt | timestamp (nullable) | Fecha en que se asignó un Verificador. |
| resolvedAt | timestamp (nullable) | Fecha de resolución del caso. |
| reviewDueAt | timestamp (nullable) | Plazo de revisión del caso, fijado al abrirlo según el plan del Estudiante: el plazo que un Verificador senior definió para ese plan (`ReviewDeadlinePolicy`) o, si no definió ninguno, 48 horas en el plan mensual y 5 días hábiles en el plan gratuito. Los días hábiles excluyen sábados y domingos en la zona horaria `America/Lima`, sin considerar feriados. Un cambio de plan posterior no lo modifica; los casos abiertos antes de los planes no tienen plazo. |
| reviewDeadline | ReviewDeadline (VO, nullable) | Plazo con el que se abrió el caso (`reviewDeadlineAmount` y `reviewDeadlineUnit`: `Hours` o `BusinessDays`), que se vuelve a contar desde la reasignación cuando el caso pasa a otro Verificador. |
| deadlineMissedAt | timestamp (nullable) | Momento en que el Verificador asignado incumplió el plazo; se limpia al reasignar el caso. |
| reassignmentCount | int | Cantidad de veces que el caso se reasignó por un plazo vencido. |

Métodos

- `VerificationCase(attemptId, studentId, pathNodeId, skillTag, caseType, reviewDeadline)` (Constructor): Crea el caso en estado `PENDING`, inmediatamente después de un `AssessmentAttempt` fallido, y calcula `reviewDueAt` a partir del `ReviewDeadline` del plan. Solo se acepta un caso abierto por estudiante y nodo (`409 OpenCaseAlreadyExists` si ya existe uno sin resolver).
- `assignVerifier(int verifierUserId)`: Asigna un Verificador disponible, transiciona el estado a `ASSIGNED` y registra `assignedAt`. Sin candidatos disponibles, el caso permanece `PENDING`.
- `attachEvidence(String url)`: Registra o reemplaza la URL de evidencia aportada por el estudiante. Solo el estudiante dueño puede invocarlo, y solo mientras el caso siga abierto.
- `resolve(ReviewDecision decision, String rubricNotes)`: Registra la decisión del Verificador asignado, transiciona el estado a `RESOLVED` y registra `resolvedAt`. Solo el Verificador asignado puede resolverlo.
- `isOverdue(Instant now)`: Indica si el caso asignado superó su `reviewDueAt` sin resolverse.
- `recordMissedDeadline(Instant now)`: Registra el incumplimiento del plazo una sola vez por asignación.
- `reassignAfterMissedDeadline(int newVerifierUserId, ReviewDeadline deadline, Instant now)`: Asigna el caso vencido a otro Verificador con el mismo plazo, contado desde la reasignación, e incrementa `reassignmentCount`.

**5. Value Object: CaseStatus**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `PENDING`, `ASSIGNED`, `RESOLVED`. |

**6. Value Object: ReviewDecision**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `APPROVED`, `REJECTED`. |

**7. Aggregate Root: ReviewDeadlinePolicy**

Descripción: Representa el plazo de revisión que un Verificador senior define para un plan y que se aplica a los casos abiertos desde ese momento. Sin una política definida, cada plan conserva su plazo por defecto.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| plan | string | Plan al que aplica: `Free` o `Premium` (identificador de la política). |
| deadline | ReviewDeadline (VO) | Plazo definido (`amount` y `unit`): hasta 48 horas en el plan mensual y hasta 5 días hábiles en el plan gratuito. |
| updatedByUserId | int | Verificador senior que definió el plazo vigente. |
| updatedAt | timestamp | Fecha de la última definición. |

Métodos

- `ReviewDeadlinePolicy(plan, deadline, definedByUserId)` (Constructor) y `define(deadline, definedByUserId)`: Registran o actualizan el plazo del plan, validando que no supere el máximo permitido (`isValidFor`).
- `defaultFor(String plan)`: Retorna el plazo por defecto del plan (48 horas o 5 días hábiles).

**8. Domain Service: VerifierMatcher**

Descripción: Encapsula el algoritmo de asignación de un Verificador disponible a un `VerificationCase`: el Estudiante no elige a su revisor, sino que el sistema lo asigna automáticamente.

Métodos

- `findAvailableVerifier(String skillTag, int excludedStudentId, List<VerifierProfile> candidates)`: Filtra candidatos disponibles y verificados con el `skillTag` requerido, **excluyendo siempre al propio estudiante** que generó el caso (aunque tenga el perfil habilitado). Elige al candidato con **menos casos abiertos** en ese momento; en caso de empate, desempata por el `verifierUserId` menor (criterio determinístico). Retorna nulo si no hay candidatos, dejando el caso en `PENDING`.

**9. Application Service: CaseAssignmentService**

Descripción: Servicio interno de la Application Layer (`application/internal`) que orquesta la asignación inicial de un caso recién abierto, la reasignación de casos que quedaron `PENDING` sin Verificador disponible, activándose cuando un Verificador cambia su disponibilidad o habilita una nueva habilidad, y la reasignación de los casos vencidos al Verificador habilitado menos cargado, excluyendo al estudiante, al Verificador que incumplió y al que resolvió el caso antes de una apelación.

**10. Domain Event: VerificationCaseDeadlineMissed**

Descripción: Se publica una sola vez por asignación cuando el Verificador asignado no resuelve el caso dentro del plazo; Reputation lo consume para descontar 5 puntos de su confiabilidad.

**11. Repository: AssessmentAttemptRepository, VerifierProfileRepository, VerificationCaseRepository, ReviewDeadlinePolicyRepository**

Métodos

- `findById(int id)`, `save(AssessmentAttempt attempt)` (AssessmentAttemptRepository).
- `findByVerifierUserId(int verifierUserId)`, `findAvailableBySkillTag(String skillTag)`, `save(VerifierProfile profile)` (VerifierProfileRepository).
- `findById(int id)`, `findByVerifierUserId(int verifierUserId)`, `findOpenByStudentAndNode(int studentId, int pathNodeId)`, `findOverdueAssignedIds(Instant now)` y `save(VerificationCase verificationCase)` (VerificationCaseRepository).
- `findByPlan(String plan)` y `save(ReviewDeadlinePolicy policy)` (ReviewDeadlinePolicyRepository).

En la Domain Layer de SkillSwap, dentro del Bounded Context de Assessment & Peer Review, `AssessmentAttempt` centraliza el cálculo del puntaje sobre el blueprint generado por Learning Path Engine, mientras que `VerificationCase` gobierna el flujo de escalamiento hacia un humano cuando dicho intento no es aprobado, apoyándose en `VerifierMatcher` para la asignación algorítmica — que excluye siempre al propio estudiante y desempata de forma determinística — de un `VerifierProfile` disponible, sin recurrir a ninguna sesión de comunicación en tiempo real ni a la subida de archivos.

#### 2.6.4.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| SubmitAssessmentAttemptResource | DTO de entrada con el `blueprintId` y las respuestas seleccionadas por el estudiante. |
| AssessmentAttemptResource | DTO de salida con el resultado del intento (score, total, passed), el caso abierto (`verificationCaseId`, `verificationCaseStatus`) y `planLimitReached` cuando el intento no aprobó pero no abrió un caso porque el estudiante agotó los escalamientos del mes de su plan (`limit = MonthlyEscalations`, `plan`, `max`, `current`, `upgradeAvailable`). |
| VerificationCaseResource | DTO de salida que representa un caso con su estado, decisión, rúbrica y evidencia. Al consultar el detalle, incluye además el intento asociado y las preguntas falladas con la respuesta elegida por el estudiante (sin exponer la respuesta correcta). |
| ResolveCaseResource | DTO de entrada con la decisión (`Approved`/`Rejected`) y las notas de rúbrica (obligatorias). |
| AttachEvidenceResource | DTO de entrada con la URL de evidencia adjunta por el estudiante. |
| CreateVerifierProfileResource | DTO de entrada con el `skillTag` a habilitar. |
| VerifierAvailabilityResource | DTO de entrada para actualizar la disponibilidad del Verificador. |
| DefineReviewDeadlinesResource | DTO de entrada con el plazo de revisión de cada plan (cantidad y unidad). |
| ReviewDeadlinePolicyResource | DTO de salida con el plazo vigente de un plan, quién lo definió y cuándo. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| AssessmentAttemptsController | POST | `/api/v1/assessment-attempts` (SubmitAssessmentAttemptResource) | Registra el intento, calcula el puntaje y, si no aprueba, dispara la apertura de un `VerificationCase`. Si el estudiante agotó los escalamientos del mes, el intento igual se registra (`201`) con `planLimitReached` y no se abre caso. Solo `Student`. |
| AssessmentAttemptsController | GET | `/api/v1/assessment-attempts/{id}` | Retorna el resultado de un intento. Solo el estudiante dueño. |
| VerificationCasesController | GET | `/api/v1/verification-cases` | Lista los casos **del Verificador autenticado** (no admite filtrar por otro `verifierId`). |
| VerificationCasesController | GET | `/api/v1/verification-cases/{id}` | Retorna el detalle de un caso. Estudiante dueño o Verificador asignado. |
| VerificationCasesController | PUT | `/api/v1/verification-cases/{id}/evidence` (AttachEvidenceResource) | Registra evidencia adicional. Solo el estudiante dueño, y solo con el caso abierto. |
| VerificationCasesController | PATCH | `/api/v1/verification-cases/{id}/decision` (ResolveCaseResource) | Registra la decisión del Verificador asignado y resuelve el caso. |
| VerifierProfilesController | POST | `/api/v1/verifier-profiles` (CreateVerifierProfileResource) | Habilita al estudiante como Verificador de una habilidad, o agrega una habilidad a un perfil existente. |
| VerifierProfilesController | GET | `/api/v1/verifier-profiles/me` | Retorna el perfil de Verificador del usuario autenticado. |
| VerifierProfilesController | PATCH | `/api/v1/verifier-profiles/me/availability` (VerifierAvailabilityResource) | Actualiza la disponibilidad del propio Verificador. |
| ReviewDeadlinePoliciesController | GET | `/api/v1/review-deadline-policies` | Retorna el plazo de revisión vigente de cada plan a cualquier usuario autenticado. |
| ReviewDeadlinePoliciesController | PUT | `/api/v1/review-deadline-policies` (DefineReviewDeadlinesResource) | Define el plazo de revisión de cada plan, aplicado a los casos abiertos desde ese momento: hasta 48 horas en el plan mensual y hasta 5 días hábiles en el plan gratuito (`400` fuera de rango, `403` si no es un Verificador senior). |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| AssessmentAttemptResourceFromEntityAssembler | Convierte `AssessmentAttempt` en `AssessmentAttemptResource`. |
| VerificationCaseResourceFromEntityAssembler | Convierte `VerificationCase` (más el intento asociado y las preguntas falladas) en `VerificationCaseResource`. |
| SubmitAssessmentAttemptCommandFromResourceAssembler | Transforma `SubmitAssessmentAttemptResource` en `SubmitAssessmentAttemptCommand`. |
| ResolveCaseCommandFromResourceAssembler | Transforma `ResolveCaseResource` en `ResolveCaseCommand`. |

**Errores (`AssessmentError`)**

`InvalidAnswers`, `InvalidEvidenceUrl`, `InvalidSkillTag`, `InvalidDecision`, `InvalidAvailability`, `RubricNotesRequired`, `RubricNotesTooLong` (400) · `NotBlueprintOwner`, `NotAttemptOwner`, `NotCaseOwner`, `NotAssignedVerifier`, `NotAVerifier` (403) · `BlueprintNotFound`, `AttemptNotFound`, `CaseNotFound`, `VerifierProfileNotFound` (404) · `BlueprintOutdated`, `AttemptAlreadySubmitted`, `NodeNotAvailable`, `OpenCaseAlreadyExists`, `CaseAlreadyResolved`, `SkillNotCompleted`, `VerifierSkillAlreadyEnabled` (409) · `DatabaseError`, `InternalServerError` (500).

#### 2.6.4.3. Application Layer

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| SubmitAssessmentAttemptCommandHandler | Procesa el envío de respuestas del estudiante. | Exige que el `blueprintId` sea el más reciente del nodo y que el nodo siga disponible. Solicita a Learning Path Engine (vía `LearningPathContextFacade`) el blueprint con `correctAnswer` incluido, instancia `AssessmentAttempt` y lo persiste. Si `passed` es verdadero, completa el nodo vía la misma facade y publica el evento `AssessmentAttemptPassed`. Si es falso, cuenta los casos que el estudiante abrió en el mes calendario en curso (hora de Lima) y los compara con el cupo del plan vigente, obtenido con `SubscriptionContextFacade.getPlanLimits(studentId)`, bajo un bloqueo `pg_advisory_xact_lock` por estudiante; si quedan escalamientos, delega en `OpenVerificationCaseCommandHandler`, y si no, registra el intento sin abrir caso y retorna `planLimitReached`. El cupo se compara siempre con el plan actual: tras volver al plan gratuito, los casos ya abiertos en el mes cuentan contra el límite de 3. |
| OpenVerificationCaseCommandHandler | Abre y asigna un nuevo caso tras un intento fallido. | Instancia `VerificationCase` con `caseType = QUIZ` y el `reviewDueAt` del plan vigente, invoca `CaseAssignmentService` (que usa `VerifierMatcher.findAvailableVerifier()` excluyendo al propio estudiante) y persiste el caso, asignado o `PENDING` según haya candidatos. |
| AttachEvidenceCommandHandler | Procesa la evidencia adicional del estudiante. | Recupera el `VerificationCase`, valida que el estudiante sea el dueño y que el caso siga abierto, invoca `attachEvidence()` y lo persiste. |
| ResolveVerificationCaseCommandHandler | Procesa la decisión del Verificador asignado. | Recupera el caso, valida que el Verificador autenticado sea el asignado, invoca `resolve()` e `IncrementReviewCount()` sobre el `VerifierProfile`. Publica el evento `VerificationCaseResolved` (consumido por Reputation y Recognition & Incentives con independencia del resultado). Si la decisión es `Approved`, además completa el nodo vía `LearningPathContextFacade`. |
| CreateOrUpdateVerifierProfileCommandHandler | Procesa la habilitación como Verificador. | Exige que el nodo de esa habilidad esté `COMPLETED` en la ruta del estudiante. Crea el perfil (`201`) o agrega la habilidad a uno existente (`200`); un perfil revocado no se reactiva por este camino. |
| UpdateVerifierAvailabilityCommandHandler | Procesa el cambio de disponibilidad. | Recupera el `VerifierProfile` del usuario autenticado, invoca `SetAvailability()` y lo persiste; dispara `CaseAssignmentService` para reasignar casos `PENDING` compatibles. |
| GetVerificationCaseQueryHandler / GetAssessmentAttemptQueryHandler / ListCasesByVerifierQueryHandler | Recuperan el detalle o listado solicitado. | Consultan el repositorio correspondiente, filtrando siempre por el usuario del token. |
| DefineReviewDeadlinesCommandHandler | Procesa la definición del plazo de revisión por plan. | Verifica mediante `ReputationContextFacade.isSeniorVerifier()` que el usuario sea un Verificador senior (perfil habilitado, rango Oro y confiabilidad de al menos 90), valida el rango de cada plazo y persiste las `ReviewDeadlinePolicy`. `ReviewDeadlineResolver` aplica el plazo vigente al abrir cada caso. |
| ReassignOverdueCaseCommandHandler | Procesa un caso con el plazo vencido. | Invocado periódicamente por `OverdueCaseReassignmentScheduler`, bloquea el caso (`SELECT ... FOR UPDATE`), registra el incumplimiento, publica `VerificationCaseDeadlineMissed` y lo reasigna mediante `CaseAssignmentService`; sin reemplazo disponible, el caso sigue con su Verificador y se reintenta sin un segundo descuento. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| AssessmentAttemptDto | Objeto que transporta el resultado de un intento entre capas. |
| VerificationCaseDto | Objeto que transporta el estado y decisión de un caso entre capas. |

En la Application Layer de Assessment & Peer Review, `SubmitAssessmentAttemptCommandHandler` asegura que un estudiante nunca avance de nodo sin una evaluación real (automática o por Verificador), y `ResolveVerificationCaseCommandHandler` centraliza el único punto donde la resolución de un caso dispara los eventos de dominio hacia Reputation y Recognition & Incentives, completando además el nodo en Learning Path Engine cuando el resultado es favorable.

#### 2.6.4.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| AssessmentAttemptRepositoryAdapter | Implementación concreta de `AssessmentAttemptRepository` sobre la tabla `assessment_attempts`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| VerifierProfileRepositoryAdapter | Implementación concreta de `VerifierProfileRepository` sobre la tabla `verifier_profiles`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| VerificationCaseRepositoryAdapter | Implementación concreta de `VerificationCaseRepository` sobre la tabla `verification_cases`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| ReviewDeadlinePolicyRepositoryAdapter | Implementación concreta de `ReviewDeadlinePolicyRepository` sobre la tabla `review_deadline_policies`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |

**Scheduling**

| Nombre | Descripción |
|---|---|
| OverdueCaseReassignmentScheduler | Busca periódicamente (cada `REVIEW_DEADLINE_CHECK_INTERVAL`, 15 minutos por defecto) los casos asignados cuyo `reviewDueAt` venció y envía su reasignación. |

Este Bounded Context no integra ningún servicio de almacenamiento de archivos: la evidencia del estudiante es una URL externa que el propio dominio valida como texto (`evidenceUrl`), sin que el backend descargue, almacene o procese ningún archivo — a diferencia de Credential Verification, que sí integra Cloudinary para los certificados.

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 84**

*C4 Model: Component Diagram del Bounded Context Assessment & Peer Review*

<p align="center">
  <img src="images-doc/AssessmentPeerReviewComponent.svg" alt="Component Diagram - Assessment & Peer Review" width="1000">
</p>

*Nota.* Se detalla la segregación entre los Controllers de `AssessmentAttempt`, `VerificationCase` y `VerifierProfile`, el Command/Query Service y el componente interno `VerifierMatcher`, evidenciando la solicitud del blueprint hacia Learning Path Engine vía `LearningPathContextFacade`, la publicación de los eventos de dominio consumidos por Reputation y Recognition & Incentives, la exposición de `VerifierProfileContextFacade` para que Reputation sincronice la confiabilidad del Verificador y la consulta del cupo de escalamientos y del plazo de revisión del plan a `SubscriptionContextFacade`. Elaboración propia.

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 85**

*Diagrama de Clases UML del Domain Layer de Assessment & Peer Review*

<p align="center">
  <img src="images-doc/class-assessment-peer-review-mobile.png" alt="Class Diagram - Assessment & Peer Review" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Assessment & Peer Review pertenece a los agregados raíz `AssessmentAttempt`, `VerifierProfile`, `VerificationCase` y `ReviewDeadlinePolicy`, junto con los Value Objects `Score` y `ReviewDeadline`, debido a que estos elementos concentran de forma exclusiva la ejecución del intento del estudiante sobre la evaluación generada por la IA, la elegibilidad de un Estudiante como Verificador de otros, y el flujo de escalamiento hacia revisión humana cuando dicho intento no es aprobado — sin depender de ninguna sesión de comunicación en tiempo real, a diferencia del modelo de tutorías original.

##### 2.6.4.6.2. Bounded Context Database Design Diagram

**Figura 86**

*Diagrama de Base de Datos del Bounded Context Assessment & Peer Review*

<p align="center">
  <img src="images-doc/db-assessment-peer-review-mobile.png" alt="Database Diagram - Assessment & Peer Review" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Assessment & Peer Review pertenece a las tablas `assessment_attempts`, `verifier_profiles`, `verification_cases` y `review_deadline_policies`, debido a que estas tablas persisten de forma independiente los agregados raíz del Bounded Context. `assessment_attempts` guarda el `score` como texto (`"aciertos/total"`, ej. `"4/5"`) en una sola columna, con índice único en `blueprint_id`. `verification_cases` lleva un índice único **parcial** sobre `(student_id, path_node_id)` que solo aplica mientras `status <> 'Resolved'` — este índice es el que materializa la regla de negocio de un único caso abierto por estudiante y nodo. La tabla guarda además `case_type` (`Quiz` o `MiniProject`), `review_due_at`, el plazo con el que se abrió el caso (`review_deadline_amount` y `review_deadline_unit`), `deadline_missed_at` y `reassignment_count`; el índice `ix_verification_cases_student_id_opened_at` permite contar los casos que un estudiante abrió en el mes y el índice parcial `ix_verification_cases_assigned_review_due_at` permite encontrar los casos asignados vencidos. La tabla `review_deadline_policies` (migración V10) guarda el plazo definido por un Verificador senior para cada plan. Se destaca el campo `evidence_url`, que reemplaza por completo la infraestructura de chat en tiempo real del modelo de tutorías original, sin requerir integración con ningún servicio de almacenamiento de archivos.


---


### 2.6.5. Bounded Context: Reputation

#### 2.6.5.1. Domain Layer

La capa de dominio de Reputation concentra las reglas de negocio relacionadas con la confiabilidad del Verificador y el nivel de empleabilidad demostrado del Estudiante, calculadas ambas a partir de eventos internos del sistema — sin que ningún usuario califique directamente a otro, a diferencia del modelo de tutorías original.

**1. Aggregate Root: VerifierReliability**

Descripción: El agregado `VerifierReliability` representa la confiabilidad acumulada de un Verificador, calculada de forma explicable a partir de los casos que resolvió, las veces que su decisión fue revertida en una apelación, las sanciones aplicadas sobre su cuenta y los plazos de revisión que incumplió. También determina su rango y si es un Verificador senior.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del registro de confiabilidad (autogenerado). |
| verifierUserId | int | Referencia al usuario `Student` (Identity & Access) con perfil de Verificador. |
| resolvedCasesCount | int | Cantidad total de `VerificationCase` resueltos por el Verificador. |
| overturnedDecisionsCount | int | Cantidad de decisiones revertidas por otro Verificador tras una apelación. |
| sanctionsCount | int | Cantidad de sanciones aplicadas sobre la cuenta del Verificador. |
| missedDeadlinesCount | int | Cantidad de casos que el Verificador no resolvió dentro del plazo de revisión y que se reasignaron. |
| score | ReliabilityScore (VO) | Puntaje de confiabilidad vigente. |
| updatedAt | timestamp | Fecha del último recálculo. |

Métodos

- `VerifierReliability(verifierUserId)` (Constructor): Inicializa los contadores en cero y el `score` en el valor base máximo.
- `recordResolution()`: Incrementa `resolvedCasesCount` y recalcula el `score` mediante `VerifierReliabilityCalculator`.
- `recordOverturn()`: Incrementa `overturnedDecisionsCount` y recalcula el `score`, aplicando la penalización correspondiente.
- `applySanction()`: Incrementa `sanctionsCount` y recalcula el `score`, aplicando la penalización más severa del modelo.
- `recordMissedDeadline()`: Incrementa `missedDeadlinesCount` y recalcula el `score`, descontando 5 puntos.
- `getRank()`: Retorna el rango del Verificador (`VerifierRank`) según sus casos resueltos: Bronce de 0 a 29, Plata de 30 a 99 y Oro desde 100.
- `isSeniorVerifier()`: Indica si es un Verificador senior: rango Oro y confiabilidad de al menos 90.

**2. Aggregate Root: StudentEmployabilityScore**

Descripción: El agregado `StudentEmployabilityScore` representa el nivel de empleabilidad demostrado de un Estudiante, calculado a partir de la cantidad de habilidades que ha logrado certificar (ya sea por aprobación automática de la IA o por revisión de un Verificador).

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del registro (autogenerado). |
| studentId | int | Referencia al usuario `Student` (Identity & Access). |
| verifiedSkillsCount | int | Cantidad de habilidades certificadas hasta el momento. |
| score | EmployabilityScore (VO) | Puntaje de empleabilidad vigente. |
| updatedAt | timestamp | Fecha del último recálculo. |

Métodos

- `StudentEmployabilityScore(studentId)` (Constructor): Inicializa `verifiedSkillsCount` en cero y el `score` correspondiente.
- `recordSkillVerified()`: Incrementa `verifiedSkillsCount` y recalcula el `score` mediante `EmployabilityScoreCalculator`.

**3. Value Object: ReliabilityScore**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | int | Puntaje de confiabilidad, en el rango de 0 a 100. |

**4. Value Object: EmployabilityScore**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | int | Puntaje de empleabilidad, proporcional a la cantidad de habilidades certificadas. |

**5. Domain Service: VerifierReliabilityCalculator**

Descripción: Calcula el `ReliabilityScore` de un Verificador mediante un conjunto explicable de reglas, evitando una fórmula opaca difícil de sustentar.

Métodos

- `calculate(int resolvedCasesCount, int overturnedDecisionsCount, int sanctionsCount, int missedDeadlinesCount)`: Retorna el `ReliabilityScore` resultante, partiendo de un puntaje base de 100 y descontando 15 puntos por cada decisión revertida, 25 puntos por cada sanción y 5 puntos por cada plazo incumplido, sin bajar de 0.

**6. Domain Service: EmployabilityScoreCalculator**

Descripción: Calcula el `EmployabilityScore` de un Estudiante a partir de la cantidad de habilidades certificadas.

Métodos

- `calculate(int verifiedSkillsCount)`: Retorna el `EmployabilityScore` resultante, proporcional a `verifiedSkillsCount`.

**7. Value Object: VerifierRank y Domain Service: SeniorVerifierPolicy**

Descripción: `VerifierRank` (`Bronze`, `Silver`, `Gold`) se alcanza por la cantidad de casos resueltos, nunca por los SkillCredits, de modo que canjearlos no reduce el rango. `SeniorVerifierPolicy` define al Verificador senior (rango Oro y confiabilidad de al menos 90), criterio que consultan Assessment & Peer Review y Moderation & Disputes.

**8. Repository: VerifierReliabilityRepository, StudentEmployabilityScoreRepository**

Métodos

- `findByVerifierUserId(int verifierUserId)`, `save(VerifierReliability reliability)` (VerifierReliabilityRepository).
- `findByStudentId(int studentId)`, `save(StudentEmployabilityScore score)` (StudentEmployabilityScoreRepository).

En la Domain Layer de SkillSwap, dentro del Bounded Context de Reputation, `VerifierReliability` y `StudentEmployabilityScore` centralizan el recálculo explicable de sus respectivos puntajes mediante `VerifierReliabilityCalculator` y `EmployabilityScoreCalculator`, apoyándose exclusivamente en eventos internos generados por Assessment & Peer Review, sin exponer ningún endpoint donde un usuario califique directamente a otro.

#### 2.6.5.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| VerifierReliabilityResource | DTO de salida con el puntaje de confiabilidad y los contadores de un Verificador. |
| StudentEmployabilityResource | DTO de salida con el puntaje de empleabilidad y la cantidad de habilidades certificadas de un Estudiante. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| VerifierReliabilitiesController | GET | `/api/v1/verifier-reliabilities/{verifierUserId}` | Retorna el puntaje de confiabilidad vigente de un Verificador, con su rango y sus contadores (incluidos los plazos incumplidos). |
| StudentEmployabilityScoresController | GET | `/api/v1/student-employability-scores/{studentId}` | Retorna el puntaje de empleabilidad vigente de un Estudiante. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| VerifierReliabilityResourceFromEntityAssembler | Convierte `VerifierReliability` en `VerifierReliabilityResource`. |
| StudentEmployabilityResourceFromEntityAssembler | Convierte `StudentEmployabilityScore` en `StudentEmployabilityResource`. |

Reputation no expone ningún endpoint de creación consumido directamente por el cliente: ambos agregados se actualizan exclusivamente mediante los eventos descritos en la Application Layer.

#### 2.6.5.3. Application Layer

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| RecordCaseResolutionEventHandler | Procesa la resolución de un `VerificationCase` por un Verificador. | Recibe el evento desde Assessment & Peer Review, invoca `recordResolution()` sobre el `VerifierReliability` del Verificador; si la decisión fue `APPROVED`, invoca además `recordSkillVerified()` sobre el `StudentEmployabilityScore` del Estudiante. |
| RecordAutomaticApprovalEventHandler | Procesa la aprobación automática de un `AssessmentAttempt` sin intervención de un Verificador. | Recibe el evento desde Assessment & Peer Review, invoca `recordSkillVerified()` sobre el `StudentEmployabilityScore` del Estudiante. |
| RecordCaseResolutionEventHandler (reversión) | Procesa la reversión de una decisión de un Verificador. | Cuando el evento `VerificationCaseResolved` informa el Verificador cuya decisión se revirtió en una apelación, invoca `recordOverturn()` sobre su `VerifierReliability`. |
| RecordMissedDeadlineEventHandler | Procesa un plazo de revisión incumplido. | Recibe el evento `VerificationCaseDeadlineMissed` desde Assessment & Peer Review e invoca `recordMissedDeadline()` sobre el `VerifierReliability` del Verificador original. |
| GetVerifierReliabilityQueryHandler / GetStudentEmployabilityQueryHandler | Recuperan el puntaje vigente solicitado. | Consultan el repositorio correspondiente. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| VerifierReliabilityDto | Objeto que transporta el puntaje de confiabilidad entre capas. |
| StudentEmployabilityDto | Objeto que transporta el puntaje de empleabilidad entre capas. |

En la Application Layer de Reputation, los event handlers aseguran que tanto la confiabilidad del Verificador como la empleabilidad del Estudiante permanezcan sincronizadas con cada evento relevante ocurrido en Assessment & Peer Review, sin que Reputation dependa de una acción explícita del usuario final. La fachada `ReputationContextFacade` (`isSeniorVerifier`, `findSeniorVerifiers`) permite a Assessment & Peer Review y a Moderation & Disputes identificar a los Verificadores senior sin depender del agregado.

#### 2.6.5.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| VerifierReliabilityRepositoryAdapter | Implementación concreta de `VerifierReliabilityRepository` sobre la tabla `verifier_reliabilities`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| StudentEmployabilityScoreRepositoryAdapter | Implementación concreta de `StudentEmployabilityScoreRepository` sobre la tabla `student_employability_scores`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |

**Integration Services**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| VerifierProfileNotifierAdapter | Comunica el `ReliabilityScore` actualizado hacia el Bounded Context Assessment & Peer Review. | Consumo HTTP interno hacia el endpoint de actualización de `VerifierProfile.rating` / `reviewCount` en Assessment & Peer Review, tras cada recálculo de `VerifierReliability`. |

Este adaptador permite que Assessment & Peer Review mantenga sincronizado el `rating` y `reviewCount` de cada `VerifierProfile` con el puntaje calculado en Reputation, sin acoplar directamente el modelo de persistencia de ambos Bounded Contexts.

#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 87**

*C4 Model: Component Diagram del Bounded Context Reputation*

<p align="center">
  <img src="images-doc/ReputationComponent.svg" alt="Component Diagram - Reputation" width="1000">
</p>

*Nota.* Se detalla la segregación entre los Controllers de solo lectura (`VerifierReliability`, `StudentEmployability`), el Command/Query Service y el adaptador de sincronización hacia Assessment & Peer Review, evidenciando que toda escritura ocurre exclusivamente mediante eventos entrantes de Assessment & Peer Review (resolución de caso, reversión tras una apelación, aprobación automática y plazo de revisión incumplido), sin ningún endpoint de creación consumido directamente por el cliente, y la fachada `ReputationContextFacade`, que consultan Assessment & Peer Review y Moderation & Disputes para identificar a los Verificadores senior. Elaboración propia.

#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 88**

*Diagrama de Clases UML del Domain Layer de Reputation*

<p align="center">
  <img src="images-doc/class-reputation-mobile.png" alt="Class Diagram - Reputation" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Reputation pertenece a los agregados raíz `VerifierReliability` y `StudentEmployabilityScore`, junto con los Value Objects `ReliabilityScore`, `EmployabilityScore` y `VerifierRank`, debido a que estos elementos concentran de forma exclusiva el recálculo explicable de la confiabilidad de un Verificador y del nivel de empleabilidad demostrado de un Estudiante, calculados ambos a partir de eventos internos del sistema — sin que ningún usuario califique directamente a otro, a diferencia del modelo de tutorías original.

##### 2.6.5.6.2. Bounded Context Database Design Diagram

**Figura 89**

*Diagrama de Base de Datos del Bounded Context Reputation*

<p align="center">
  <img src="images-doc/db-reputation-mobile.png" alt="Database Diagram - Reputation" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Reputation pertenece a las tablas `verifier_reliabilities` y `student_employability_scores`, debido a que estas dos tablas persisten de forma independiente los dos agregados raíz del Bounded Context, cada uno con su propio puntaje y contadores recalculados por evento (incluido `missed_deadlines_count`, agregado en la migración V10) — sin una tabla intermedia de reseñas o calificaciones directas, ya que ese concepto no existe en el nuevo modelo.


---

### 2.6.6. Bounded Context: Recognition & Incentives

#### 2.6.6.1. Domain Layer

La capa de dominio de Recognition & Incentives concentra las reglas de negocio de la billetera de SkillCredits — créditos internos no monetarios — que un Verificador acumula al resolver casos de verificación (según el tipo de caso: 40 SkillCredits por un miniproyecto y 25 por un quiz, lo apruebe o lo rechace), y que ese mismo Verificador puede canjear por beneficios dentro de la plataforma; los SkillCredits nunca se compran con dinero ni se transfieren entre usuarios. A diferencia del modelo de tutorías original, no existe transferencia de dinero real entre usuarios ni comisión de plataforma.

**1. Aggregate Root: Wallet**

Descripción: El agregado `Wallet` representa la billetera de SkillCredits de un usuario, manteniendo su saldo disponible.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único de la billetera (autogenerado). |
| walletOwnerId | int | Usuario propietario de la billetera (único). |
| balance | int | Saldo actual disponible, en SkillCredits. |

Métodos

- `Wallet(walletOwnerId)` (Constructor): Crea la billetera con saldo inicial en cero, invocada al momento del registro del usuario en Identity & Access.
- `credit(Credits amount)`: Incrementa el saldo tras la acreditación de créditos ganados.
- `debit(Credits amount)`: Disminuye el saldo, validando que exista saldo suficiente antes del canje.

**2. Entity: CreditTransaction**

Descripción: Representa un movimiento realizado sobre una billetera, ya sea la acreditación de créditos ganados o el canje de créditos por un beneficio.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único de la transacción. |
| walletId | int | Billetera involucrada en el movimiento. |
| amount | Credits (VO) | Cantidad de créditos del movimiento. |
| type | TransactionType (VO) | Tipo de movimiento: `EARNED` o `REDEEMED`. |
| description | string | Descripción del movimiento (ej. "Caso de verificación resuelto", "Canje: certificado de contribución"). |
| redemptionItem | RedemptionItem (VO, nullable) | Beneficio comprado por un canje (solo en transacciones `REDEEMED`), que permite entregarlo. |
| createdAt | timestamp | Fecha y hora de la transacción. |

Métodos

- `CreditTransaction(walletId, amount, type, description)` (Constructor): Valida que el monto sea positivo antes de crear el registro.

**3. Value Object: Credits**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | int | Cantidad de SkillCredits del movimiento, validada como no negativa. |

Métodos

- `Credits(int value)` (Constructor): Valida que el valor no sea negativo, lanzando una excepción de dominio en caso contrario.

**4. Value Object: TransactionType**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `EARNED` (créditos ganados por resolver un caso) o `REDEEMED` (créditos canjeados por un beneficio). |

**5. Value Object: RedemptionItem**

Descripción: Enumeración de los dos beneficios que un Verificador puede canjear con sus SkillCredits.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `ADVANCED_PATH_UNLOCK` (ruta avanzada: habilita, es decir, pone a disposición del Verificador, una ruta de certificación avanzada, cuyos nodos se completan de la forma habitual), `CONTRIBUTION_CERTIFICATE` (certificado de contribución exportable, ej. para LinkedIn). |

**6. Domain Service: RedemptionPricing**

Descripción: Define el costo en SkillCredits de cada `RedemptionItem`, desacoplando el precio de canje del agregado `Wallet`.

Métodos

- `calculateCost(RedemptionItem item)`: Retorna la cantidad de `Credits` requerida para canjear el beneficio indicado: 200 SkillCredits para `ADVANCED_PATH_UNLOCK` (equivalentes a 5 miniproyectos u 8 quizzes) y 120 SkillCredits para `CONTRIBUTION_CERTIFICATE` (3 miniproyectos o alrededor de 5 quizzes).

**7. Repository: WalletRepository, CreditTransactionRepository**

Métodos

- `findByOwnerId(int userId)`, `save(Wallet wallet)` (WalletRepository).
- `save(CreditTransaction transaction)`, `findByWalletId(int walletId)` (CreditTransactionRepository).

En la Domain Layer de SkillSwap, dentro del Bounded Context de Recognition & Incentives, el agregado `Wallet` gestiona el saldo de SkillCredits de cada usuario, mientras que la entidad `CreditTransaction` registra cada movimiento validado por el Value Object `Credits`. El costo de cada beneficio canjeable se delega al Domain Service `RedemptionPricing`, manteniendo esta regla de negocio desacoplada del agregado — sin que exista, en ningún punto del dominio, un concepto de moneda real ni de comisión de plataforma.

#### 2.6.6.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| WalletResource | DTO de salida que representa el saldo actual de SkillCredits de una billetera. |
| CreditTransactionResource | DTO de salida que representa un movimiento (amount, type, description, createdAt). |
| RedeemResource | DTO de entrada con el `RedemptionItem` que el usuario desea canjear. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| WalletController | GET | `/api/v1/wallets/{userId}` | Retorna el saldo actual de SkillCredits de un usuario. |
| WalletController | GET | `/api/v1/wallets/{userId}/transactions` | Retorna el historial de movimientos de la billetera. |
| CreditTransactionController | POST | `/api/v1/credit-transactions/redeem` (RedeemResource) | Registra el canje de un `RedemptionItem`, descontando el costo correspondiente del saldo. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| WalletResourceFromEntityAssembler | Convierte `Wallet` en `WalletResource`. |
| CreditTransactionResourceFromEntityAssembler | Convierte `CreditTransaction` en `CreditTransactionResource`. |
| RedeemCommandFromResourceAssembler | Transforma `RedeemResource` en `RedeemCommand`. |

Del lado del cliente móvil, el endpoint de canje (`redeem`) requiere que el usuario complete la verificación mediante la API biométrica nativa del dispositivo (`BiometricPrompt` en Android, `local_auth` en Flutter) antes de que la aplicación invoque el endpoint; si el dispositivo no cuenta con lector de huella o no tiene huellas registradas, el propio sistema operativo ofrece automáticamente el PIN, patrón o contraseña del dispositivo como mecanismo alternativo de confirmación. A diferencia del modelo original, no existe endpoint de creación de billetera consumido por el cliente: `Wallet` se crea automáticamente al registrarse el usuario en Identity & Access.

#### 2.6.6.3. Application Layer

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| CreateWalletCommandHandler | Procesa la creación de la billetera inicial. | Recibe el evento desde Identity & Access tras el registro de un nuevo usuario, instancia `Wallet` con saldo en cero y lo persiste. |
| CreditVerifierCommandHandler | Procesa la acreditación de créditos ganados. | Recibe el evento desde Assessment & Peer Review tras la resolución de un `VerificationCase`, sea `APPROVED` o `REJECTED`, ejecuta `credit()` con el monto que `CreditRewards` asigna al `caseType` del caso (40 SkillCredits para `MINI_PROJECT` y 25 para `QUIZ`) sobre el `Wallet` del Verificador y registra la `CreditTransaction` de tipo `EARNED`. |
| RedeemCommandHandler | Procesa el canje de un beneficio. | Calcula el costo mediante `RedemptionPricing`, valida saldo suficiente, ejecuta `debit()` sobre el `Wallet` y registra la `CreditTransaction` de tipo `REDEEMED` con su `redemptionItem`. Si el beneficio es `ADVANCED_PATH_UNLOCK`, publica `AdvancedPathUnlockRedeemed`, con el que Learning Path Engine otorga el desbloqueo de la ruta avanzada; `RecognitionContextFacade` permite además sincronizar los canjes cuyo evento no llegó a procesarse. |
| GetWalletBalanceQueryHandler / GetWalletTransactionsQueryHandler | Recuperan el saldo o historial solicitado. | Consultan el repositorio correspondiente. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| WalletDto | Objeto que transporta el saldo operativo de una billetera entre capas. |
| CreditTransactionDto | Objeto que transporta el detalle de un movimiento entre capas. |

En la Application Layer de Recognition & Incentives, `CreditVerifierCommandHandler` es el único punto donde se acreditan créditos, y depende exclusivamente de un evento de Assessment & Peer Review — nunca de una acción directa de otro usuario, eliminando así el flujo de donación P2P y su comisión asociada que existían en el modelo de tutorías.

#### 2.6.6.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| WalletRepositoryAdapter | Implementación concreta de `WalletRepository` sobre la tabla `wallets`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |
| CreditTransactionRepositoryAdapter | Implementación concreta de `CreditTransactionRepository` sobre la tabla `credit_transactions`. | ORM del stack backend, instancia PostgreSQL desplegada en Render. |

Este Bounded Context no incluye integraciones con pasarelas de pago externas ni siquiera como trabajo futuro: al ser SkillCredits un mecanismo puramente interno y no monetario, no existe punto de extensión hacia una pasarela de pago, a diferencia de Credential Verification, donde sí se documentaron mecanismos de verificación oficial pendientes de integración.

#### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 90**

*C4 Model: Component Diagram del Bounded Context Recognition & Incentives*

<p align="center">
  <img src="images-doc/WalletIncentivesComponent.svg" alt="Component Diagram - Recognition & Incentives" width="1000">
</p>

*Nota.* Se detalla la segregación entre los Controllers de `Wallet` y `CreditTransaction`, el Command/Query Service y el Repository, evidenciando la creación de la billetera inicial solicitada por Identity & Access al registrarse, la acreditación de SkillCredits notificada por Assessment & Peer Review tras un caso resuelto, y la confirmación de biometría consultada hacia Identity & Access antes de un canje — sin ninguna integración con pasarelas de pago externas. Elaboración propia.

#### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 91**

*Diagrama de Clases UML del Domain Layer de Recognition & Incentives*

<p align="center">
  <img src="images-doc/class-wallet-incentives-mobile.png" alt="Class Diagram - Recognition & Incentives" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Recognition & Incentives pertenece al agregado raíz `Wallet`, junto con la entidad `CreditTransaction` y el Value Object `Credits`, debido a que estos elementos concentran de forma exclusiva el saldo de SkillCredits de cada usuario y el historial de movimientos — créditos ganados al resolver un caso de verificación, o canjeados por un beneficio — sin que exista, en ningún punto del dominio, un concepto de moneda real ni de comisión de plataforma.

##### 2.6.6.6.2. Bounded Context Database Design Diagram

**Figura 92**

*Diagrama de Base de Datos del Bounded Context Recognition & Incentives*

<p align="center">
  <img src="images-doc/db-wallet-incentives-mobile.png" alt="Database Diagram - Recognition & Incentives" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Recognition & Incentives pertenece a las tablas `wallets` y `credit_transactions`, debido a que la primera persiste el saldo vigente de SkillCredits de cada usuario y la segunda registra, en una relación uno a muchos, cada movimiento asociado a dicha billetera, con el beneficio canjeado en `redemption_item` (migración V10) — sin ninguna tabla de credenciales de tarjeta ni de integración con una pasarela de pago externa, a diferencia del modelo de tutorías original.

---

### 2.6.7. Bounded Context: Moderation & Disputes

#### 2.6.7.1. Domain Layer

La capa de dominio de Moderation & Disputes concentra las reglas de negocio de la escalación final ante un Verificador senior, es decir, un Verificador con rango Oro (100 casos resueltos o más) y una confiabilidad de 90 o más, en la escala de 0 a 100 que calcula Reputation. El modelo de `Dispute` contempla tres orígenes de escalación (un certificado marcado como `SUSPICIOUS` por Credential Verification, una apelación sobre la decisión de un Verificador y un reporte entre usuarios); el backend crea disputas del primer origen, la revisión de certificados sospechosos (US13 y US14), mientras que la apelación de un caso rechazado (US27) se resuelve dentro de Assessment & Peer Review, reasignando el caso a otro Verificador.

**1. Aggregate Root: Dispute**

Descripción: El agregado `Dispute` representa un caso que requiere la decisión final de un Verificador senior. Gobierna su asignación a un revisor y su resolución con observaciones obligatorias, sin depender de los modelos internos de `Certificate` o `VerificationCase`.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único del caso (autogenerado). |
| sourceType | DisputeSourceType (VO) | Origen de la escalación: `CERTIFICATE_REVIEW`, `VERIFIER_DECISION_APPEAL` o `USER_REPORT`. |
| sourceReferenceId | int | Identificador del `Certificate` (o del caso) en revisión, según el `sourceType`. Un certificado se escala una sola vez. |
| raisedByUserId | int (nullable) | Usuario que originó el caso; nulo cuando la escalación es automática (`CERTIFICATE_REVIEW`). |
| respondentUserId | int (nullable) | Usuario cuyo certificado, decisión o conducta se cuestiona; en una revisión de certificado, su propietario. |
| reason | string | Motivos de la escalación (hasta 500 caracteres), por ejemplo, el archivo ya registrado por otro estudiante o el titular distinto del nombre registrado. |
| status | DisputeStatus (VO) | Estado actual: `PENDING` o `RESOLVED`. |
| outcome | DisputeOutcome (VO, nullable) | Resultado de la resolución, nulo hasta que el revisor decide. |
| resolutionNotes | string (nullable) | Observaciones del revisor al resolver (obligatorias, hasta 2000 caracteres). |
| assignedVerifierUserId | int (nullable) | Verificador que revisa el caso; nulo mientras espera un revisor disponible. Nunca es el `respondentUserId`. |
| assignedToSenior | boolean | Indica si el revisor era un Verificador senior al asignarse o el Verificador de respaldo. |
| assignedAt | timestamp (nullable) | Fecha de asignación del revisor. |
| raisedAt | timestamp | Fecha de apertura del caso. |
| resolvedAt | timestamp (nullable) | Fecha de resolución del caso. |

Métodos

- `Dispute(sourceType, sourceReferenceId, raisedByUserId, respondentUserId, reason)` (Constructor): Crea el caso en estado `PENDING`.
- `certificateReview(int certificateId, int ownerId, List<String> reasons)`: Crea la disputa de revisión de un certificado sospechoso, con su propietario como `respondentUserId`.
- `assignReviewer(int verifierUserId, boolean senior)`: Asigna el revisor y registra si es un Verificador senior; rechaza a las partes de la disputa.
- `resolve(DisputeOutcome outcome, String resolutionNotes, DisputeResolutionValidator validator)`: Valida que el caso siga `PENDING` y que el `outcome` sea coherente con el `sourceType`, exige las observaciones, transiciona el estado a `RESOLVED` y registra `resolvedAt`.
- `isAssignedTo(int userId)` / `isParty(int userId)`: Indican si el usuario es el revisor asignado o una de las partes.

**2. Value Object: DisputeSourceType**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `CERTIFICATE_REVIEW`, `VERIFIER_DECISION_APPEAL`, `USER_REPORT`. |

**3. Value Object: DisputeStatus**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `PENDING`, `RESOLVED`. |

**4. Value Object: DisputeOutcome**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `UPHELD` (se confirma la decisión o el certificado original; en una revisión de certificado, el certificado es legítimo), `OVERTURNED` (se revierte; en una revisión de certificado, el certificado es fraudulento), `DISMISSED` (el reporte no amerita sanción), `SANCTIONED` (el reporte amerita sanción). |

**5. Domain Service: DisputeResolutionValidator**

Descripción: Valida que un caso solo pueda resolverse estando en estado `PENDING`, y que el `outcome` aplicado sea coherente con su `sourceType`: `CERTIFICATE_REVIEW` y `VERIFIER_DECISION_APPEAL` admiten `UPHELD` u `OVERTURNED`, y `USER_REPORT` admite `DISMISSED` o `SANCTIONED`.

Métodos

- `canResolve(Dispute dispute)`: Retorna verdadero si el caso se encuentra en estado `PENDING`.
- `isValidOutcome(DisputeSourceType sourceType, DisputeOutcome outcome)`: Retorna verdadero si la combinación es coherente según las reglas de negocio.

**6. Domain Service: DisputeReviewerSelector**

Descripción: Elige al revisor de una disputa entre los Verificadores disponibles (`ReviewerCandidate`, con su carga de casos de verificación abiertos y disputas pendientes): el Verificador senior menos cargado; si no hay ninguno disponible, el Verificador habilitado menos cargado, registrando que no es senior. Nunca elige a las partes de la disputa, y los empates se resuelven por el menor identificador de usuario.

Métodos

- `choose(Collection<Integer> excludedUserIds, List<ReviewerCandidate> candidates)`: Retorna la elección (`ReviewerChoice`: usuario y si es senior), o vacío si no hay candidatos.

**7. Repository: DisputeRepository**

Métodos

- `findById(int id)`, `findByIdForUpdate(int id)`, `findBySource(DisputeSourceType sourceType, int sourceReferenceId)`, `findByAssignedVerifier(int verifierUserId, DisputeStatus status)`, `findUnassignedPendingIds()`, `countPendingByVerifierUserIds(Collection<Integer> verifierUserIds)` y `save(Dispute dispute)`.

En la Domain Layer de SkillSwap, dentro del Bounded Context de Moderation & Disputes, el agregado `Dispute` modela bajo un único concepto los orígenes de escalación posibles, evitando que Moderation dependa directamente de los modelos internos de `Certificate` o `VerificationCase` — exactamente el rol de Anticorruption Layer que se definió en el Context Mapping. Las transiciones se validan mediante `DisputeResolutionValidator`, y `DisputeReviewerSelector` garantiza que la decisión final llegue a un Verificador senior siempre que exista uno disponible.

#### 2.6.7.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| DisputeResource | DTO de salida que representa un caso (sourceType, sourceReferenceId, reason, status, outcome, resolutionNotes, assignedVerifierUserId, assignedToSenior y sus fechas). |
| DisputeEvidenceResource | DTO de salida con la disputa y la evidencia del certificado en revisión (`CertificateEvidenceResource`: datos extraídos por OCR, evaluación de riesgo, si el titular difiere del nombre registrado y un enlace temporal al archivo). |
| ResolveDisputeResource | DTO de entrada con la decisión del revisor (`outcome`, `resolutionNotes`). |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| DisputesController | GET | `/api/v1/disputes?status=` | Retorna las disputas asignadas al Verificador autenticado, de la más antigua a la más reciente: las pendientes por defecto, o las resueltas o todas (`Resolved`, `All`). `403` si el usuario no es un Verificador habilitado. |
| DisputesController | GET | `/api/v1/disputes/{id}/evidence` | Retorna la disputa con la evidencia del certificado en revisión. Solo su revisor (`403` en otro caso). |
| DisputesController | PATCH | `/api/v1/disputes/{id}/resolve` (ResolveDisputeResource) | Aplica la resolución del revisor: en una revisión de certificado, `Upheld` lo verifica y `Overturned` lo rechaza. `400` si el `outcome` no es coherente con el origen o faltan las observaciones, `403` si no es el revisor asignado y `409` si la disputa ya se resolvió o el certificado ya no está en estado sospechoso. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| DisputeResourceAssemblers | Convierten `Dispute` (y la vista del certificado en revisión) en `DisputeResource` y `DisputeEvidenceResource`. |
| ModerationDisputesActionResultAssembler | Traduce el resultado de cada comando en la respuesta HTTP y su código de error. |

El endpoint de evidencia consulta directamente a Credential Verification, sin copiar en Moderation & Disputes la información del certificado.

#### 2.6.7.3. Application Layer

**Handlers**

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| EscalateCertificateReviewEventHandler | Procesa la escalación automática de un certificado `SUSPICIOUS`. | Reacciona al evento `CertificateFlaggedSuspicious` de Credential Verification y envía `EscalateCertificateReviewCommand`: crea la disputa con `sourceType = CERTIFICATE_REVIEW` (una sola por certificado, aunque el evento se entregue más de una vez) y le asigna un revisor mediante `DisputeReviewerSelector`, consultando a Assessment & Peer Review los Verificadores disponibles y su carga (`VerifierProfileContextFacade`) y a Reputation quiénes son senior (`ReputationContextFacade`). Sin revisor disponible, la disputa queda pendiente. |
| ResolveDisputeCommandHandler | Procesa la resolución del revisor. | Bloquea la disputa, valida que el usuario sea el revisor asignado y el `outcome` con `DisputeResolutionValidator`, invoca `resolve()` y, en la misma transacción, aplica la decisión sobre el certificado mediante `CredentialContextFacade.resolveSuspiciousCertificate()`: `VERIFIED` si es legítimo o `REJECTED` si es fraudulento. Un certificado verificado completa en Learning Path Engine los nodos que cubre, y el estudiante recibe la notificación push de la resolución. |
| AssignPendingDisputesCommandHandler | Reintenta la asignación de las disputas sin revisor. | Invocado periódicamente por `PendingDisputeAssignmentScheduler`, recorre las disputas pendientes sin revisor y les asigna uno cuando ya hay Verificadores disponibles. |
| GetDisputesByReviewerQueryHandler / GetDisputeByIdQueryHandler | Recuperan las disputas del revisor o una disputa con su evidencia. | Consultan `DisputeRepository` y, para la evidencia, la vista del certificado (`CertificateReviewView`) mediante `CredentialContextFacade`. |

En la Application Layer de Moderation & Disputes, `ResolveDisputeCommandHandler` es el único punto donde la decisión del revisor se traduce en efectos sobre otro Bounded Context, de modo que Credential Verification no necesita conocer la existencia de `Dispute` como concepto.

La apelación (US27) se implementa dentro de Assessment & Peer Review: `POST /api/v1/verification-cases/{id}/appeal` reabre el caso rechazado, que solo puede apelarse una vez, y lo reasigna a otro Verificador habilitado, distinto del que lo rechazó y del propio Estudiante.

#### 2.6.7.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| DisputeRepositoryAdapter | Implementación concreta de `DisputeRepository` sobre la tabla `disputes`, con bloqueo de fila (`SELECT ... FOR UPDATE`) al asignar o resolver. | Spring Data JPA, PostgreSQL. |

**Scheduling**

| Nombre | Descripción |
|---|---|
| PendingDisputeAssignmentScheduler | Reintenta cada `MODERATION_ASSIGNMENT_RETRY_INTERVAL` (15 minutos por defecto) la asignación de las disputas que se escalaron sin revisor disponible. |

**Integration (Anti-Corruption Layer)**

| Nombre | Descripción |
|---|---|
| CredentialContextFacade | Fachada de Credential Verification con la que Moderation & Disputes consulta la vista del certificado en revisión y aplica la resolución final. |
| VerifierProfileContextFacade | Fachada de Assessment & Peer Review con la que obtiene los Verificadores disponibles, su carga de trabajo y si un usuario es un Verificador habilitado. |
| ReputationContextFacade | Fachada de Reputation con la que identifica a los Verificadores senior. |

Estas fachadas permiten que Moderation & Disputes coordine la revisión de certificados sospechosos con Credential Verification, Assessment & Peer Review y Reputation sin duplicar en su propio modelo de persistencia la información de certificados, perfiles de Verificador ni confiabilidad.

#### 2.6.7.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 93**

*C4 Model: Component Diagram del Bounded Context Moderation & Disputes*

<p align="center">
  <img src="images-doc/ModerationDisputesComponent.svg" alt="Component Diagram - Moderation & Disputes" width="1000">
</p>

*Nota.* Se detalla la segregación entre `DisputesController`, el Command/Query Service, `EscalateCertificateReviewEventHandler`, `PendingDisputeAssignmentScheduler` y el repositorio, evidenciando la escalación automática de los certificados en estado SUSPICIOUS publicada por Credential Verification, la selección del revisor con las fachadas de Assessment & Peer Review (Verificadores disponibles) y Reputation (Verificadores senior), y la resolución final aplicada sobre el certificado mediante `CredentialContextFacade`. Elaboración propia.

#### 2.6.7.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.7.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 94**

*Diagrama de Clases UML del Domain Layer de Moderation & Disputes*

<p align="center">
  <img src="images-doc/class-moderation-disputes-mobile.png" alt="Class Diagram - Moderation & Disputes" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Moderation & Disputes pertenece al agregado raíz `Dispute`, junto con los Value Objects `DisputeSourceType`, `DisputeStatus` y `DisputeOutcome` y los servicios de dominio `DisputeResolutionValidator` y `DisputeReviewerSelector`, debido a que estos elementos modelan bajo un único concepto los orígenes de escalación hacia un Verificador senior (certificado sospechoso, apelación de una decisión de Verificador o reporte de usuario), evitando que Moderation dependa directamente de los modelos internos de `Certificate` o `VerificationCase` — el rol de Anticorruption Layer definido en el Context Mapping.

##### 2.6.7.6.2. Bounded Context Database Design Diagram

**Figura 95**

*Diagrama de Base de Datos del Bounded Context Moderation & Disputes*

<p align="center">
  <img src="images-doc/db-moderation-disputes-mobile.png" alt="Database Diagram - Moderation & Disputes" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Moderation & Disputes pertenece a la tabla `disputes` (migración V9), que persiste en un único modelo unificado cualquier caso que requiera la decisión final de un Verificador senior, identificado mediante `source_type` y `source_reference_id`. El índice único parcial `ux_disputes_certificate_review` garantiza que un certificado se escale una sola vez, el CHECK `ck_disputes_not_reviewed_by_respondent` impide que el propietario del certificado revise su propia disputa, y los índices sobre `assigned_verifier_user_id` y sobre las disputas pendientes sin revisor soportan la consulta del revisor y el reintento periódico de la asignación. Las columnas `resolution_notes`, `assigned_to_senior` y `assigned_at` registran las observaciones de la resolución y la asignación.

---

### 2.6.8. Bounded Context: Subscription & Billing

#### 2.6.8.1. Domain Layer

La capa de dominio de Subscription & Billing concentra las reglas de negocio de la suscripción mensual con la que el Estudiante amplía los límites del plan gratuito, manteniendo el modelo desacoplado de la pasarela de suscripciones concreta (Google Play Billing, integrado mediante RevenueCat) mediante un contrato de dominio propio. El plan gratuito (S/ 0) permite 1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes a un Verificador, cuyos casos se revisan en hasta 5 días hábiles; el plan mensual, de S/ 29,90 al mes con IGV incluido, permite hasta 3 rutas activas a la vez, sin tope de rutas en total y 10 escalamientos al mes a un Verificador, cuyos casos se revisan en 48 horas. La ruta avanzada canjeada con SkillCredits (`ADVANCED_PATH_UNLOCK`) no consume el cupo de rutas del plan gratuito, y ningún plan compra la aprobación de un certificado.

**1. Aggregate Root: Subscription**

Descripción: El agregado `Subscription` representa la suscripción mensual de un Estudiante, que amplía los límites del plan gratuito, gobernando las transiciones de estado de su ciclo de facturación mensual.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| id | int | Identificador único de la suscripción (autogenerado). |
| studentId | int | Referencia al usuario `Student` (Identity & Access) propietario de la suscripción. |
| plan | SubscriptionPlan (VO) | Plan contratado: nombre, producto de Google Play y precio. Se persiste aplanado en las columnas `plan_name`, `plan_product_id`, `plan_price` (`numeric(10,2)`) y `plan_currency`. |
| status | SubscriptionStatus (VO) | Estado actual del ciclo de facturación. |
| storeTransactionId | string (nullable) | Identificador de la transacción de Google Play que informa RevenueCat, usado para conciliar la suscripción con la compra original y para cancelar su renovación. |
| startedAt | timestamp | Fecha de activación de la suscripción. |
| currentPeriodEnd | timestamp | Fin del período ya pagado: la próxima renovación o, si la suscripción fue cancelada, el fin del plan mensual. |
| cancelledAt | timestamp (nullable) | Fecha en la que el Estudiante canceló la suscripción, si aplica. |
| expiredAt | timestamp (nullable) | Fecha en la que la suscripción venció y el Estudiante volvió al plan gratuito, si aplica. |
| updatedAt | timestamp | Fecha del último cambio de la suscripción. |

Métodos

- `Subscription(studentId, plan, storeTransactionId, currentPeriodEnd)` (Constructor): Crea la suscripción en estado `ACTIVE`, a partir de una compra cuyo entitlement ya verificó RevenueCat; exige que `currentPeriodEnd` sea una fecha futura.
- `renew(Instant newPeriodEnd, String storeTransactionId)`: Extiende `currentPeriodEnd` cuando RevenueCat informa un nuevo período. Nunca acorta el período, por lo que una notificación repetida o tardía no cambia nada; una suscripción vencida no puede renovarse.
- `cancel()`: Transiciona de `ACTIVE` a `CANCELLED` y registra `cancelledAt`, sin revocar el plan mensual hasta `currentPeriodEnd`.
- `uncancel()`: Revierte una cancelación hecha antes del fin del período (de `CANCELLED` a `ACTIVE`), cuando RevenueCat informa que Google Play volverá a renovar la suscripción.
- `expire()`: Transiciona el estado a `EXPIRED` y registra `expiredAt` cuando Google Play no renovó la suscripción o la revocó; el Estudiante vuelve al plan gratuito.
- `grantsPremiumAt(Instant moment)`: Indica si la suscripción otorga el plan mensual en ese momento: no está vencida y su período pagado no terminó, aunque todavía no se haya marcado como vencida.

**2. Value Object: SubscriptionPlan**

Descripción: Encapsula el nombre y el precio del plan contratado por el Estudiante.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| name | string | Nombre comercial del plan (ej. "Plan Mensual"). |
| productId | string | Identificador del producto de suscripción configurado en Google Play Console. |
| price | Money (VO) | Precio periódico del plan (ej. S/ 29,90 al mes, IGV incluido). |

**3. Value Object: Money**

Descripción: Encapsula un monto monetario junto con su moneda, evitando operaciones aritméticas ambiguas entre distintas divisas.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| amount | decimal | Cantidad numérica del monto. |
| currency | string | Código de moneda (ej. `PEN`). |

Métodos

- `Money(decimal amount, String currency)` (Constructor): Valida que el monto no sea negativo.

**4. Value Object: SubscriptionStatus**

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| value | enum | `ACTIVE`, `CANCELLED` (conserva el plan mensual hasta `currentPeriodEnd`) y `EXPIRED`, que se almacenan y exponen como `Active`, `Cancelled` y `Expired`. |

**5. Value Object: PurchaseVerification**

Descripción: Estado del entitlement pagado del Estudiante tal como lo informa la pasarela, única fuente de verdad sobre una compra: el backend nunca confía en lo que envía el cliente.

Atributos

| Atributo | Tipo | Descripción |
|---|---|---|
| active | boolean | Indica si el entitlement otorga el plan mensual en este momento, incluido el período de gracia. |
| productId | string (nullable) | Producto de Google Play que otorga el entitlement; nulo si no está vigente. |
| expiresAt | timestamp (nullable) | Fin del período pagado o de su período de gracia; nulo si no está vigente. |
| willRenew | boolean | Indica si la tienda renovará la suscripción al terminar el período (falso una vez cancelada). |
| storeTransactionId | string (nullable) | Transacción de Google Play de la compra, si la pasarela la informa. |
| sandbox | boolean | Indica si es una compra de prueba. |

**6. Domain Service: PaymentGateway**

Descripción: Define el contrato con la pasarela externa que conoce el estado real de las compras, desacoplando el dominio de la tecnología concreta (Google Play Billing, integrado mediante RevenueCat) y permitiendo sustituirla o simularla sin modificar el resto del Bounded Context.

Métodos

- `verifyPurchase(int studentId, String productId)`: Consulta el estado real del plan pagado del Estudiante, cuyo id es el app user id en RevenueCat, y retorna un `PurchaseVerification`. Un `productId` nulo acepta cualquier producto que otorgue el entitlement.
- `cancelRenewal(int studentId, String storeTransactionId)`: Solicita a la tienda que deje de renovar la suscripción; en RevenueCat corresponde a `POST /v1/subscribers/{app_user_id}/subscriptions/{store_transaction_id}/cancel`. El plan se conserva hasta el fin del período.

Ambos métodos lanzan `PaymentGatewayException` cuando la pasarela no responde.

**7. Domain Events: SubscriptionActivated y SubscriptionExpired**

`SubscriptionActivated` (`subscriptionId`, `studentId`, `currentPeriodEnd`) se publica cuando la pasarela confirma una compra y el Estudiante obtiene el plan mensual. `SubscriptionExpired` (`subscriptionId`, `studentId`, `expiredAt`) corresponde al evento Suscripción vencida: el Estudiante vuelve al plan gratuito, no se elimina nada suyo y los demás Bounded Contexts se adaptan a los límites de ese plan.

**8. Entity: ProcessedWebhookEvent**

Registra cada notificación del webhook ya aplicada (`eventId`, `eventType`, `appUserId`, `environment`, `processedAt`). RevenueCat reintenta una notificación con el mismo id hasta recibir un `200`, por lo que el `eventId` único hace idempotente el procesamiento.

**9. Repository: SubscriptionRepository, ProcessedWebhookEventRepository**

Métodos

- `findById(int id)`, `findCurrentByStudentId(int studentId)` (la suscripción no vencida del Estudiante; como máximo una), `findCurrentByStudentIdForUpdate(int studentId)` (la misma consulta con bloqueo de fila, para que un webhook y una solicitud de la app no modifiquen a la vez la misma suscripción), `findDueForExpiration(Instant moment)` (suscripciones no vencidas cuyo período pagado terminó) y `save(Subscription subscription)` (SubscriptionRepository).
- `existsByEventId(String eventId)`, `save(ProcessedWebhookEvent event)` (ProcessedWebhookEventRepository).

En la Domain Layer de SkillSwap, dentro del Bounded Context de Subscription & Billing, el agregado `Subscription` centraliza el ciclo de vida de la suscripción mensual, apoyándose en el Domain Service `PaymentGateway` para desacoplar el dominio del proveedor concreto de suscripciones, y en el Value Object `Money` para representar montos en moneda real de forma segura.

Cuando el Estudiante cancela, conserva el plan mensual hasta el fin del período ya pagado (`currentPeriodEnd`). Al vencer, `expire()` marca la suscripción como `EXPIRED`, se publica `SubscriptionExpired` (Suscripción vencida) y el Estudiante vuelve al plan gratuito sin perder sus rutas, su progreso, sus certificados ni su historial. Learning Path Engine reacciona a ese evento mediante `EnforcePlanLimitsEventHandler`, que mantiene activa la ruta con el `lastProgressAt` más reciente y pausa las demás rutas activas. Los casos ya escalados mantienen el plazo que tenían al abrirse (`reviewDueAt`), y el cupo de escalamientos se calcula siempre con el plan vigente: los casos abiertos en el mes calendario en curso se cuentan contra el límite de 3 del plan gratuito, por lo que, si el Estudiante ya escaló 3 o más ese mes, no puede escalar otro caso hasta el mes siguiente o hasta que se suscriba de nuevo.

#### 2.6.8.2. Interface Layer

**Resources**

| Nombre | Descripción |
|---|---|
| CreateSubscriptionResource | DTO de entrada que la aplicación envía tras completar la compra con el SDK de RevenueCat. Solo contiene un `productId` opcional: el cliente no envía la transacción ni el token de compra, porque el backend verifica el entitlement en RevenueCat usando el id del usuario autenticado como app user id, y cualquier otro campo se ignora. |
| RevenueCatWebhookResource | DTO de entrada con `api_version` y el `event` del webhook de RevenueCat (`id`, `type`, `app_user_id`, `original_app_user_id`, `aliases`, `environment`, entre otros). Solo se usan el id, el tipo y el usuario del evento: el estado se vuelve a leer de RevenueCat. |
| SubscriptionResource | DTO de salida con la suscripción: `planName`, `productId`, `price`, `currency`, `status`, `storeTransactionId`, `startedAt`, `currentPeriodEnd`, `cancelledAt` y `expiredAt`. |
| StudentPlanResource | DTO de salida con el plan vigente del Estudiante (`Free` o `Premium`), sus límites (`PlanLimitsResource`: rutas activas, rutas en total, escalamientos al mes y plazo de revisión) y la suscripción no vencida, o `null` en el plan gratuito. |
| WebhookAcknowledgementResource | DTO de salida del webhook con `outcome`: `Processed`, `Duplicate` (reintento de un evento ya aplicado) o `Ignored`. |

**Controllers**

| Nombre | Método HTTP | Ruta / Resource | Descripción |
|---|---|---|---|
| SubscriptionsController | POST | `/api/v1/subscriptions` (CreateSubscriptionResource) | Verifica el entitlement del Estudiante autenticado en RevenueCat y activa la suscripción con el período que informa RevenueCat; si el webhook ya la activó, la retorna actualizada. `201`; `400 InvalidProduct`; `422 PurchaseNotVerified` (RevenueCat no informa una compra vigente); `503 PaymentGatewayUnavailable`. |
| SubscriptionsController | GET | `/api/v1/subscriptions/{studentId}` | Retorna `StudentPlanResource`: el plan vigente (`Free` o `Premium`), sus límites y la suscripción no vencida, o `null`. Solo el propio Estudiante; `403` en otro caso. |
| SubscriptionsController | PATCH | `/api/v1/subscriptions/{id}/cancel` | Cancela la renovación en Google Play (vía RevenueCat); el plan se conserva hasta `currentPeriodEnd`. Es idempotente: cancelar dos veces no cambia nada. `200`; `403`; `404`; `409 SubscriptionNotActive` (ya vencida); `503` (RevenueCat no respondió y nada cambia). |
| RevenueCatWebhookController | POST | `/api/v1/subscriptions/webhooks/revenuecat` (RevenueCatWebhookResource) | Recibe los eventos de RevenueCat sin token: compara el encabezado `Authorization` con el secreto configurado (hash SHA-256 y comparación en tiempo constante). Cada `event.id` se aplica una sola vez y los eventos `TEST` se confirman y se ignoran. `200` con `{outcome: Processed\|Duplicate\|Ignored}`; `401 InvalidWebhookAuthorization`; `400 InvalidWebhookEvent`; `503` para que RevenueCat reintente. |

**Transformers / Assemblers**

| Nombre | Descripción |
|---|---|
| SubscriptionResourceFromEntityAssembler | Convierte `Subscription` en `SubscriptionResource`, y el plan vigente con sus límites en `StudentPlanResource`. |
| CreateSubscriptionCommandFromResourceAssembler | Transforma `CreateSubscriptionResource` en `CreateSubscriptionCommand`, tomando siempre el `studentId` del usuario autenticado y nunca del cuerpo de la solicitud. |
| SubscriptionBillingActionResultAssembler | Traduce los errores de `SubscriptionBillingError` a códigos HTTP (`400`, `401`, `403`, `404`, `409`, `422`, `503`). |

Los controladores no validan las compras: delegan en la capa de aplicación, que consulta el estado del Estudiante mediante el adaptador de infraestructura de RevenueCat, de modo que los tokens de compra de Google Play no llegan al backend ni circulan por el dominio. `RevenueCatWebhookController` solo comprueba el secreto del encabezado `Authorization`, comparando su hash SHA-256 en tiempo constante, antes de delegar el evento.

#### 2.6.8.3. Application Layer

**Handlers**

Siguiendo la convención del repositorio, no hay clases `…CommandHandler` separadas: `SubscriptionCommandService` expone un método `handle(...)` sobrecargado por cada comando, implementado en `SubscriptionCommandServiceImpl`, y `SubscriptionQueryService` hace lo mismo con las consultas.

| Nombre | Descripción | Resumen de Lógica |
|---|---|---|
| SubscriptionCommandService.handle(CreateSubscriptionCommand) | Procesa la activación de una suscripción ya comprada en la aplicación. | Invoca `PaymentGateway.verifyPurchase()` con el id del Estudiante autenticado y el `productId` opcional; si el entitlement está vigente, instancia `Subscription` en estado `ACTIVE`, la persiste y publica `SubscriptionActivated`, o actualiza la suscripción existente si el webhook ya la había activado. Falla con `InvalidProduct`, `PurchaseNotVerified` o `PaymentGatewayUnavailable`. |
| SubscriptionCommandService.handle(CancelSubscriptionCommand) | Procesa la cancelación de una suscripción. | Valida que el Estudiante sea el dueño; si la suscripción ya estaba cancelada, la retorna sin cambios. En otro caso, invoca `PaymentGateway.cancelRenewal()` y luego `cancel()`, y la persiste. Falla con `SubscriptionNotFound`, `NotSubscriptionOwner`, `SubscriptionNotActive` o `PaymentGatewayUnavailable`. |
| SubscriptionCommandService.handle(ExpireSubscriptionCommand) | Revisa una suscripción cuyo período pagado terminó sin noticias de la pasarela. | Lo envía `SubscriptionExpirationScheduler` cada hora, como red de seguridad ante un webhook perdido. Consulta a la pasarela: si informa un nuevo período, invoca `renew()`; si no, invoca `expire()` y publica `SubscriptionExpired`, al que reacciona Learning Path Engine. |
| SubscriptionCommandService.handle(ProcessRevenueCatEventCommand) | Procesa una notificación del webhook de RevenueCat. | Registra el `event_id` en `processed_webhook_events` para aplicarlo una sola vez (un reintento responde `Duplicate`). Los eventos `TEST`, los de un entorno no admitido y los de usuarios que no son estudiantes de la plataforma se ignoran. Para los demás no confía en el payload: vuelve a leer el estado del suscriptor con `GET /v1/subscribers/{app_user_id}`, como recomienda RevenueCat, y aplica la activación, la renovación (`renew()`), la cancelación (`cancel()`), su reversión (`uncancel()`) o el vencimiento (`expire()`) que corresponda. |
| SubscriptionQueryService.handle(GetCurrentSubscriptionByStudentIdQuery / GetPlanLimitsByStudentIdQuery) | Recupera la suscripción no vencida y los límites del plan vigente. | Consulta `SubscriptionRepository.findCurrentByStudentId()`; el plan es `Premium` mientras una suscripción lo otorgue (`grantsPremiumAt`) y `Free` en otro caso. |

**Internal DTOs**

| Nombre | Descripción |
|---|---|
| WebhookEventOutcome | Resultado del procesamiento de una notificación del webhook: `PROCESSED`, `DUPLICATE` o `IGNORED`. |
| PlanLimitsView | Límites del plan vigente del Estudiante (`plan`, `maxActiveRoutes`, `maxTotalRoutes`, `monthlyEscalations` y el plazo de revisión en horas o en días hábiles), tal como los consumen otros Bounded Contexts. |

En la Application Layer de Subscription & Billing, el procesamiento del webhook mantiene el acceso del Estudiante sincronizado con el estado real de la suscripción en Google Play, informado por RevenueCat, sin que este Bounded Context intervenga en ningún momento sobre el balance de SkillCredits del usuario. Learning Path Engine y Assessment & Peer Review leen el plan del Estudiante mediante `SubscriptionContextFacade.getPlanLimits(studentId)`, que retorna `PlanLimitsView` (Anticorruption Layer), sin depender de las suscripciones ni de la pasarela de pagos.

#### 2.6.8.4. Infrastructure Layer

**Persistence (Repository Implementation)**

| Nombre | Descripción | Tecnologías / Herramientas |
|---|---|---|
| SubscriptionRepositoryAdapter | Implementación concreta de `SubscriptionRepository` sobre la tabla `subscriptions`. Un índice único parcial (`ux_subscriptions_one_current_per_student`, `WHERE status <> 'Expired'`) permite una sola suscripción no vencida por Estudiante; las vencidas quedan como historial. | ORM del stack backend, instancia PostgreSQL desplegada en Render; esquema creado por la migración Flyway V3. |
| ProcessedWebhookEventRepositoryAdapter | Implementación concreta de `ProcessedWebhookEventRepository` sobre la tabla `processed_webhook_events`, cuyo índice único sobre `event_id` hace idempotente el procesamiento del webhook. | ORM del stack backend, instancia PostgreSQL desplegada en Render; esquema creado por la migración Flyway V3. |

**Payment Services Implementation**

| Nombre | Descripción | Resumen de Implementación |
|---|---|---|
| RevenueCatGatewayAdapter | Implementación técnica de `PaymentGateway` mediante la API REST de RevenueCat, que valida las compras ante Google Play Billing. Se usa cuando la variable `REVENUECAT_API_KEY` está configurada. | `verifyPurchase` consulta `GET /v1/subscribers/{app_user_id}` usando el id del usuario como app user id y verifica que el entitlement configurado (`REVENUECAT_ENTITLEMENT_ID`, por defecto `premium`) esté vigente; `cancelRenewal` invoca `POST /v1/subscribers/{app_user_id}/subscriptions/{store_transaction_id}/cancel`. Los cambios de estado (compra, renovación, cancelación y vencimiento) llegan de forma asíncrona por el webhook `POST /api/v1/subscriptions/webhooks/revenuecat`, protegido con un secreto en el encabezado `Authorization`. |
| SimulatedPaymentGatewayAdapter | Implementación simulada de `PaymentGateway`, usada cuando `REVENUECAT_API_KEY` no está configurada. | Aprueba la compra de un período de `BILLING_SIMULATED_PERIOD` (por defecto 30 días), que se renueva hasta cancelarse. Guarda su estado en memoria, por lo que se pierde al reiniciar la aplicación: sirve solo para desarrollo y demostraciones, y nunca cobra nada. |
| RevenueCatWebhookAuthorization | Implementación de `WebhookAuthorizationVerifier`. | Compara el hash SHA-256 del encabezado `Authorization` con el del valor de `REVENUECAT_WEBHOOK_AUTH` mediante `MessageDigest.isEqual` (comparación en tiempo constante); si la variable no está configurada, rechaza todas las notificaciones. |
| SubscriptionExpirationScheduler | Tarea programada que actúa como red de seguridad ante un webhook perdido. | Cada `BILLING_EXPIRATION_CHECK_INTERVAL` (por defecto 1 hora) busca las suscripciones no vencidas cuyo período pagado terminó (`findDueForExpiration`) y envía un `ExpireSubscriptionCommand` por cada una. |

RevenueCat no es un procesador de pagos ni reemplaza a Google Play Billing: el cobro lo sigue procesando Google Play, como exige su política de pagos (Google Play Console Help, s. f.-a), y RevenueCat solo valida la compra en el servidor, notifica sus cambios de estado y expone el estado del suscriptor (RevenueCat, s. f.). Así, el equipo no implementa a mano la validación con la Google Play Developer API ni las notificaciones en tiempo real (RTDN) vía Pub/Sub. RevenueCat no tiene costo hasta US$ 2500 de ingresos mensuales registrados; a partir de ese monto cobra el 1%.

*Nota de alcance:* la integración se implementó con los dos adaptadores del contrato `PaymentGateway`: `RevenueCatGatewayAdapter` cuando `REVENUECAT_API_KEY` está configurada y `SimulatedPaymentGatewayAdapter` en caso contrario, de modo que la aplicación funciona sin una cuenta de RevenueCat y sin alterar el Domain Layer ni la Application Layer. El adaptador simulado guarda su estado en memoria, por lo que solo sirve para desarrollo y demostraciones.

#### 2.6.8.5. Bounded Context Software Architecture Component Level Diagrams

**Figura 96**

*C4 Model: Component Diagram del Bounded Context Subscription & Billing*

<p align="center">
  <img src="images-doc/SubscriptionBillingComponent.svg" alt="Component Diagram - Subscription & Billing" width="1000">
</p>

*Nota.* Se detalla la segregación entre `SubscriptionsController`, `RevenueCatWebhookController`, el Command/Query Service, `SubscriptionExpirationScheduler` y el puerto `PaymentGateway` con sus adaptadores `RevenueCatGatewayAdapter` y `SimulatedPaymentGatewayAdapter`, evidenciando el registro idempotente de los eventos del webhook en `processed_webhook_events`, la publicación de `SubscriptionExpired` hacia Learning Path Engine y `SubscriptionContextFacade`, por la que Learning Path Engine y Assessment & Peer Review leen los límites del plan. Este Bounded Context opera de forma completamente independiente de Recognition & Incentives. Elaboración propia.

#### 2.6.8.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.8.6.1. Bounded Context Domain Layer Class Diagrams

**Figura 97**

*Diagrama de Clases UML del Domain Layer de Subscription & Billing*

<p align="center">
  <img src="images-doc/class-subscription-billing-mobile.png" alt="Class Diagram - Subscription & Billing" width="800">
</p>

*Nota.* Diagrama de clases del Domain Layer de este Bounded Context, alineado con el código del backend. Elaboración propia.

El modelado de clases de Subscription & Billing pertenece únicamente al agregado raíz `Subscription`, junto con los Value Objects `SubscriptionPlan` y `Money`, debido a que este Bounded Context gestiona exclusivamente el ciclo de vida del cobro recurrente de la mensualidad, desacoplado del proveedor concreto de pagos mediante el Domain Service `PaymentGateway`, definido en el Context Mapping como el límite de Anticorruption Layer hacia Google Play Billing (vía RevenueCat). El atributo `storeTransactionId` guarda la referencia de la transacción de Google Play que informa RevenueCat.

##### 2.6.8.6.2. Bounded Context Database Design Diagram

**Figura 98**

*Diagrama de Base de Datos del Bounded Context Subscription & Billing*

<p align="center">
  <img src="images-doc/db-subscription-billing-mobile.png" alt="Database Diagram - Subscription & Billing" width="800">
</p>

*Nota.* Diagrama elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

El modelado de base de datos de Subscription & Billing pertenece a la tabla `subscriptions`, debido a que es la única tabla que persiste el agregado raíz `Subscription`, incluyendo el plan contratado aplanado en columnas simples (`plan_name`, `plan_product_id`, `plan_price` de tipo `numeric(10,2)` y `plan_currency`) y la referencia `store_transaction_id` de la transacción de Google Play — al igual que en Identity & Access y Credential Verification, no existe ninguna entidad hija ni colección propia, por lo que un único registro por suscripción es suficiente. Un índice único parcial (`WHERE status <> 'Expired'`) garantiza una sola suscripción no vencida por Estudiante. A ella se suma la tabla `processed_webhook_events`, que registra cada evento del webhook ya aplicado con un índice único sobre `event_id`, para que los reintentos de RevenueCat no se apliquen dos veces. No se persiste el método de pago ni datos sensibles de tarjeta, delegados por completo a Google Play Billing.


---

A continuación se presenta el diagrama relacional completo de SkillSwap, mostrando la totalidad de las tablas y sus relaciones entre los ocho Bounded Contexts.

**Figura 99**

*Diagrama de Base de Datos completo de SkillSwap*

<p align="center">
  <img src="images-doc/db-full-mobile.svg" alt="Diagrama de Base de Datos Completo" width="1000">
</p>

*Nota.* Se muestra la totalidad de las tablas correspondientes a los ocho Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes), en el esquema que resulta de aplicar las migraciones Flyway V1 a V10: el campo device_token y las columnas de verificación del correo, intereses y nombre completo sobre la tabla users, los campos file_hash, storage_reference, ocr_text, qr_payload y holder_name_mismatch sobre la tabla certificates, las tablas subscriptions y processed_webhook_events de la suscripción mensual, advanced_path_unlocks, review_deadline_policies y disputes. Las líneas continuas representan las dos únicas claves foráneas físicas (`path_nodes → learning_paths` y `credit_transactions → wallets`) y las discontinuas, las referencias por identificador entre Bounded Contexts. Elaborado en PlantUML a partir de las migraciones Flyway V1–V10. Elaboración propia.

En síntesis, el diagrama relacional evidencia una estructura de base de datos coherente, donde una única base de datos PostgreSQL (`skillswap_db`) aloja de forma organizada las tablas de los ocho Bounded Contexts, manteniendo alta cohesión dentro de cada contexto (por ejemplo, `assessment_attempts` y `verification_cases` en Assessment & Peer Review) y bajo acoplamiento entre ellos: las únicas claves foráneas unen tablas de un mismo agregado (`path_nodes` con `learning_paths` y `credit_transactions` con `wallets`), y entre Bounded Contexts las tablas se referencian solo por identificador (por ejemplo, `users.id`, `certificates.id` o `credit_transactions.id`). La incorporación del campo `device_token` y de los campos de extracción sobre `certificates` demuestra la extensión del modelo de datos original para soportar las funcionalidades propias de los clientes móviles nativo y cross-platform, mientras que la tabla `subscriptions` evidencia el modelo de negocio freemium (suscripción mensual opcional sobre el plan gratuito), completamente independiente del sistema interno no monetario de SkillCredits, que solo se gana mediante participación como Verificador y no admite ninguna forma de adquisición directa.


A continuación se presenta el diagrama de clases UML completo de SkillSwap, mostrando la totalidad del modelo de dominio y su segmentación entre los ocho Bounded Contexts.

**Figura 100**

*Diagrama de Clases UML completo de SkillSwap*

<p align="center">
  <img src="images-doc/SkillSwap_ClassDiagram_Mobile.svg" alt="Diagrama de Clases Completo" width="1000">
</p>

*Nota.* Se presenta la totalidad del modelo de dominio, evidenciando cómo el modelo global ha sido segmentado en los ocho Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes), incluyendo el Value Object `DeviceToken` y los puertos `EmailSender` y `PushNotificationSender` en Identity & Access, los atributos de extracción OCR (`ocrText`, `qrPayload`, `fileHash`) en `Certificate` (Credential Verification), los agregados `AdvancedPathUnlock` (Learning Path Engine), `ReviewDeadlinePolicy` (Assessment & Peer Review), `Dispute` (Moderation & Disputes) y `Subscription` (Subscription & Billing). Elaborado en PlantUML. Elaboración propia.

En síntesis, el diagrama de clases evidencia un modelo de dominio coherente, donde cada Bounded Context mantiene sus propios agregados raíz (`User`, `Certificate`, `LearningPath`, `AssessmentBlueprint`, `AdvancedPathUnlock`, `AssessmentAttempt`, `VerifierProfile`, `VerificationCase`, `ReviewDeadlinePolicy`, `VerifierReliability`, `StudentEmployabilityScore`, `Wallet`, `Subscription`, `Dispute`) manteniendo alta cohesión dentro de cada contexto y bajo acoplamiento entre ellos, sin referencias directas de clase a clase entre Bounded Contexts distintos — toda referencia cruzada se resuelve mediante un identificador entero (`int`). La incorporación del Value Object `DeviceToken` en Identity & Access y de los atributos de extracción de `Certificate` en Credential Verification demuestra la extensión del modelo de dominio original para soportar las funcionalidades propias de los clientes móviles nativo y cross-platform, en particular la captura desde cámara y el procesamiento on-device mediante ML Kit que constituye el feature de aprendizaje autónomo del proyecto. Por su parte, el agregado `Subscription` en Subscription & Billing, junto con los Value Objects `SubscriptionPlan` y `Money`, evidencia el desacoplamiento entre el cobro recurrente al Estudiante y el sistema interno no monetario de SkillCredits en Recognition & Incentives, ambos Bounded Contexts operando de forma completamente independiente entre sí y desacoplados del proveedor concreto de pagos (Google Play Billing, integrado mediante RevenueCat) mediante el Domain Service `PaymentGateway`.

---

# Capítulo III: Solution UI/UX Design


## 3.1. Product design

En esta sección se presenta el diseño del producto como parte integral de la arquitectura del sistema, detallando las decisiones que determinan la interacción entre los usuarios (Estudiante y Verificador) y SkillSwap, alineadas con los principios y elementos de diseño adoptados por el equipo.

### 3.1.1. Style Guidelines

#### 3.1.1.1. General Style Guidelines

En esta sección se presentan las decisiones visuales base que rigen la identidad de SkillSwap, aplicadas de manera consistente tanto en el Landing Page como en las aplicaciones móviles: paleta de colores, tipografía, espaciado y tono de comunicación.

**Figura 101**

*Style Guidelines de SkillSwap*

<p align="center">
  <img src="images-doc/style-guidelines.png" alt="Style Guidelines de SkillSwap" width="900">
</p>

*Nota.* La lámina resume el Design System del producto. En la aplicación móvil, el color primario es el azul `#0022AA` (contraste 11.6:1 sobre blanco), acompañado de un azul oscuro `#001580` para el onboarding y los encabezados, y un contenedor `#E6EAFF` para el indicador de la navbar y los chips seleccionados; el texto principal es `#111827` (17.7:1) y el secundario `#4B5563` (7.6:1). Los estados usan colores semánticos con ícono y texto, nunca solo color: éxito `#15803D`, error `#B91C1C`, advertencia y SkillCredits `#B45309`, y el violeta `#5B21B6` para todo lo generado por IA. El Landing Page usa el azul institucional `#193B69` con el ámbar `#FFC107` para los llamados a la acción. Ambos productos usan la familia **Inter**: en la app con la escala Display 28/36 (ExtraBold), H1 24/32 y H2 20/28 (Bold), Title 16/24 (SemiBold), Body 16/24 y Body-S 14/20 (Regular), Label 14/20 y Caption 12/16 (Medium); el código de los quizzes usa JetBrains Mono. El espaciado sigue una grilla de 8 px (margen lateral de 24 px, 32 px entre secciones, 24 px entre campos y 8–12 px entre un label y su componente) y los radios son de 8 px en chips, 12 px en inputs, 16 px en cards y 26 px en botones. El tono de comunicación adoptado es profesional pero cercano, en segunda persona y orientado a la acción, evitando tecnicismos del dominio en el contenido dirigido al usuario y comunicando los resultados negativos sin tono punitivo ("Aún no alcanzas el mínimo"), siempre con el siguiente paso a seguir, coherente con el carácter riguroso pero accesible que busca transmitir la plataforma frente a sus dos segmentos objetivo (Estudiantes y Verificadores). Elaboración propia.

### 3.1.2. Information Architecture

#### 3.1.2.1. Organization Systems

Esta sección describe cómo se organiza el contenido en el Landing Page y en la aplicación móvil, de modo que el visitante o usuario encuentre la información sin esfuerzo.

La información del Landing Page se organiza de forma **secuencial** en la sección "¿Cómo funciona SkillSwap?", que presenta el flujo en 3 pasos numerados (1. Sube tus certificados → 2. La IA arma tu ruta → 3. Demuestra la habilidad), reflejando el orden real en que el Estudiante interactúa con la plataforma. La sección de roles aplica una organización **por audiencia**, agrupando el contenido en dos tarjetas, una por segmento objetivo: Estudiante y Verificador. El resto del contenido (pitch de valor, socios institucionales, contacto) sigue una organización **jerárquica visual**, donde cada sección ocupa un bloque completo de pantalla en orden descendente de relevancia para el visitante.

En la aplicación móvil, la información se organiza **por rol**, ya que cada perfil tiene tareas distintas: Estudiante y Verificador. Dentro de cada rol, el contenido se agrupa **por tarea** en los cuatro destinos de la barra de navegación, y la ruta de aprendizaje del Estudiante sigue una organización **secuencial**, donde cada nodo se desbloquea al cumplir el anterior según sus prerrequisitos (US08). Los casos asignados al Verificador se ordenan **por urgencia**, según el plazo de resolución, para que lo más importante aparezca primero.

#### 3.1.2.2. Labelling Systems

Esta sección detalla las etiquetas utilizadas para representar los conjuntos de información de la plataforma, buscando simplicidad y evitando confusión para el visitante o usuario.

Las etiquetas del menú principal se mantienen como sustantivos cortos y directos: "Plataforma" (ancla a la demostración visual de la app), "Alianzas" (página para universidades), "Sobre nosotros" (equipo), "Iniciar Sesión" y "Registrarse" como acciones. Dentro del contenido, las etiquetas evitan tecnicismos del dominio (ej. no se usa "Bounded Context" ni "VerificationCase") y se comunican en lenguaje natural para el visitante: "Revisión automática con IA", "Employability Score", "Case review" (en la versión en inglés). La tarjeta de rol se etiqueta como "Verificador" y explica que este rol revisa los casos que la IA no logra resolver y gana SkillCredits por ello, sin necesidad de explicar la distinción técnica interna.

En la aplicación móvil se usa el mismo vocabulario del dominio en todas las pantallas, sin sinónimos: "ruta", "nodo", "certificado", "quiz", "caso", "rúbrica", "apelación", "sub-tema" y "SkillCredits". Las etiquetas de la barra de navegación son sustantivos cortos con ícono: "Mi ruta", "Certificados", "Evaluaciones" y "Perfil" (Estudiante); y "Casos", "Historial", "SkillCredits" y "Perfil" (Verificador). Los botones usan verbos de acción ("Generar mi ruta", "Rendir quiz", "Agregar evidencia"), y los formularios muestran labels visibles sobre cada campo, en lugar de usar el placeholder como etiqueta.

#### 3.1.2.3. SEO Tags and Meta Tags

Esta sección presenta los elementos de optimización para motores de búsqueda configurados en cada página del Landing Page, así como los elementos ASO (App Store Optimization) correspondientes a la publicación de la aplicación móvil.

**Tabla 12**

*SEO Tags y Meta Tags del Landing Page*

| Página | Title | Meta Description | Keywords |
|---|---|---|---|
| Home (`index.html`) | SkillSwap \| Verificación de Habilidades con IA | SkillSwap verifica tus habilidades con IA: sube tus certificados, recibe una ruta de certificación personalizada y demuestra lo que sabes. | verificación de habilidades, inteligencia artificial, certificaciones, ruta de aprendizaje, estudiantes universitarios, SkillSwap, Perú, empleabilidad |
| Sobre Nosotros (`aboutUs.html`) | SkillSwap \| Sobre Nosotros | Conoce a Innovify, el equipo detrás de SkillSwap, nuestra misión, visión y las personas que hacen posible la red interuniversitaria más grande del Perú. | — |
| Alianzas (`partnerships.html`) | SkillSwap \| Alianzas Institucionales | Afilia tu universidad a SkillSwap y ofrece a tus estudiantes verificación de habilidades con IA y certificaciones confiables. | — |
| Registro (`signup.html`) | SkillSwap \| Registro | Regístrate en SkillSwap, sube tus certificados y deja que la IA arme tu ruta de certificación. | — |
| Iniciar Sesión (`login.html`) | SkillSwap \| Verificación de Habilidades con IA | Inicia sesión en SkillSwap y sigue tu ruta de certificación de habilidades generada por IA. | — |

*Nota.* Elaboración propia.

El Landing Page implementa además **SEO bilingüe** mediante etiquetas `hreflang` (es/en/x-default) y un selector de idioma (ES/EN) que actualiza dinámicamente el `<title>` y el `<meta name="description">` según el idioma seleccionado, persistiendo la preferencia en `localStorage`. El `author` declarado es "Innovify", nombre de la startup.

Para la publicación de la aplicación móvil en Google Play se definieron los siguientes elementos ASO:

**Tabla 13**

*Elementos ASO de la aplicación móvil*

| Elemento ASO | Contenido |
|---|---|
| App Title | SkillSwap: Valida tus habilidades |
| App Subtitle (descripción corta) | Convierte tus certificados en habilidades verificadas con IA y revisión de pares. |
| App Keywords | verificación de habilidades, certificados, ruta de aprendizaje, quiz con IA, empleabilidad, estudiantes universitarios, prácticas, Perú |
| App Description | SkillSwap ayuda a los estudiantes universitarios a demostrar lo que saben, no solo lo que estudiaron. Declara tu meta profesional y la IA arma una ruta de certificación con tus certificados previos; valida cada habilidad con quizzes generados por IA y, si lo necesitas, con la revisión de un Verificador. Los Verificadores ganan SkillCredits por cada caso resuelto y los Verificadores senior revisan las apelaciones para cuidar la calidad del proceso. |
| Categoría | Educación |

*Nota.* Elaboración propia.

#### 3.1.2.4. Searching Systems

Esta sección describe los mecanismos de búsqueda disponibles para que el visitante o usuario encuentre información sin sentirse perdido entre el volumen de contenido.

El Landing Page **no implementa un sistema de búsqueda**, por tratarse de un sitio informativo de una sola sección por pantalla (scroll continuo) más 3 páginas adicionales (Alianzas, Sobre Nosotros, Registro/Login) — el volumen de contenido no lo justifica. El sistema de búsqueda real del producto corresponde a la aplicación móvil, donde el Estudiante declara su meta en lenguaje natural y el backend la relaciona con el catálogo interno de habilidades: Gemini interpreta la meta y selecciona habilidades solo de ese catálogo, con la coincidencia por palabras clave como respaldo (ver 2.6.3, `SkillTaxonomyMatcher`).

En la aplicación, ese mecanismo se presenta en la pantalla **Declarar meta**: un campo de texto libre con dictado por voz y chips con metas de otros estudiantes, para que el Estudiante reconozca un ejemplo en lugar de tener que recordar el nombre exacto de un curso. La IA devuelve como máximo tres habilidades candidatas ordenadas por afinidad, con la opción de reformular la meta si ninguna se ajusta. Además, el Estudiante cuenta con una **búsqueda dentro de su ruta** (ícono de lupa en "Mi ruta") para encontrar un nodo o sub-tema sin recorrerla completa; si no hay resultados, la pantalla lo indica y sugiere otra palabra, y si el nodo encontrado está bloqueado, explica qué nodo debe completar antes. En las pantallas del Verificador se usan **filtros** (por ejemplo, el periodo "Últimos 30 días" en su historial de casos) en lugar de un buscador, porque el volumen de casos es acotado.

#### 3.1.2.5. Navigation Systems

Esta sección explica las acciones y técnicas que guían al visitante o usuario a través del Landing Page y la aplicación, permitiéndole cumplir sus metas de forma satisfactoria.

La navegación del Landing Page combina una **barra superior persistente** (logo + menú horizontal, con versión de menú hamburguesa para mobile) con **anclas internas** dentro de la misma página (ej. "Plataforma" lleva a `#seccion-screenshots` sin cambiar de URL) y **enlaces a páginas independientes** para contenido extenso (Alianzas, Sobre Nosotros, Registro, Login). Los *call-to-action* ("¡Empieza tu ruta ahora!", "Empieza tu ruta — tarda 2 minutos", "Create my free account") se repiten en varios puntos de scroll para no depender de que el visitante recuerde volver al menú. El footer centraliza los enlaces legales (Términos y Condiciones, Política de Privacidad) y de contacto.

En la aplicación móvil, cada rol cuenta con una **barra de navegación inferior** de Material Design 3 con cuatro destinos y un indicador del destino activo, de modo que el usuario siempre sabe dónde está. Los flujos de tarea (registro, subida de certificado, quiz, revisión de un caso o envío de una apelación) ocultan la barra y usan una **app bar con "Volver" o "Cerrar"**, para que el usuario se concentre en terminar la tarea. Las acciones que avanzan una tarea se muestran como botón principal en la parte inferior, al alcance del pulgar, y las confirmaciones y errores se presentan con diálogos, hojas inferiores y snackbars que incluyen una acción directa para continuar (por ejemplo, "Rendir" cuando el certificado queda validado).

### 3.1.3. Landing Page UI Design

La sección presenta cómo se tradujeron las decisiones de diseño y arquitectura de información al Landing Page de SkillSwap, correspondiente a las historias US41 a US45 (propuesta de valor, planes y precios, descarga de la app, información para Verificadores, preguntas frecuentes).

#### 3.1.3.1. Landing Page Wireframe

Esta sección presenta los wireframes de baja fidelidad del Landing Page, en sus versiones para Desktop Web Browser y Mobile Web Browser, elaborados en Figma antes de definir el diseño visual final.

Los wireframes del Landing Page se elaboraron en Figma y definen la estructura de bloques en el orden en que el visitante recorre la página: barra de navegación, sección Hero con la propuesta de valor y el llamado a la acción, flujo de 3 pasos, roles (Estudiante y Verificador), pitch de valor, capturas de la plataforma, universidades aliadas y contacto. Se presentan a continuación:

**Figura 102**

*Wireframe del Landing Page de SkillSwap (Desktop Web Browser)*

<p align="center">
  <img src="images-doc/cap3-landing-wireframe.png" alt="Wireframe Landing Page" width="900">
</p>

*Nota.* Wireframe de baja fidelidad del Landing Page, presentado en tres columnas que se leen de izquierda a derecha y de arriba hacia abajo. Se definió primero la jerarquía de contenido (Hero, "¿Cómo funciona?", roles, pitch, funcionalidades, socios, video y contacto), seguida de la página para universidades (beneficios, proceso de afiliación y formulario), "Sobre nosotros" (equipo y video) y las pantallas de inicio de sesión y registro. Se usaron únicamente tonos de gris y marcadores de imagen para validar la estructura y los llamados a la acción antes del diseño visual. El archivo editable está disponible en [https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo](https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo). Elaboración propia.

**Figura 103**

*Wireframe del Landing Page de SkillSwap (Mobile Web Browser)*

<p align="center">
  <img src="images-doc/cap3-landing-wireframe-mobile.png" alt="Wireframe Landing Page Mobile" width="900">
</p>

*Nota.* Wireframes de baja fidelidad del Landing Page en un navegador móvil, con las secciones Inicio (Hero), "Cómo funciona", Precios, "Para Verificadores" y Preguntas frecuentes. El contenido se reorganiza en una sola columna y el menú horizontal se reemplaza por un ícono de menú, para mantener la legibilidad en pantallas angostas. Se aplicó el mismo orden de lectura que en la versión de escritorio (arquitectura de información de 3.1.2) y los principios de diseño inclusivo: botones de ancho completo al alcance del pulgar, áreas táctiles de al menos 48 px, un solo llamado a la acción principal por sección ("Descargar la app", "Empieza tu ruta como Estudiante") y etiquetas visibles en lugar de íconos sin texto. Elaboración propia.

#### 3.1.3.2. Landing Page Mock-up

Esta sección presenta el mock-up final del Landing Page, resultado de aplicar el Design System definido en 3.1.1 sobre la arquitectura de información descrita en 3.1.2.

**Figura 104**

*Mock-up del Landing Page de SkillSwap (escritorio)*

<p align="center">
  <img src="images-doc/index-new.png" alt="Mock-up Landing Page - Home" width="900">
</p>

*Nota.* Diseño final del Landing Page de SkillSwap, aplicando el Design System del proyecto: sección Hero con propuesta de valor ("Demuestra lo que sabes..."), flujo de 3 pasos (subir certificado → ruta por IA → demostrar la habilidad), presentación de los dos segmentos objetivo (Estudiante y Verificador), comparación de valor frente a otras plataformas, y sección de universidades aliadas. Implementado en HTML5/CSS3/JavaScript, con soporte bilingüe (ES/EN). Elaboración propia.

**Figura 105**

*Mock-up del Landing Page de SkillSwap (versión responsive)*

<p align="center">
  <img src="images-doc/index-responsive.png" alt="Mock-up Landing Page - Responsive" width="900">
</p>

*Nota.* Versión móvil del Landing Page (390 px de ancho), con el menú hamburguesa, el Hero, la sección "¿Cómo funciona SkillSwap?", las tarjetas de roles y las universidades aliadas, reorganizadas en una sola columna. Elaboración propia.

El Landing Page está desplegado en: [https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/](https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/)

### 3.1.4. Mobile Applications UX/UI Design

Esta sección presenta el diseño visual y de interacción de las aplicaciones móviles (Android Nativo y Flutter), cubriendo las pantallas core de los dos roles: registro, suscripción e inicio de sesión, declaración de la meta, carga de certificado, consulta de la ruta de aprendizaje y resolución del quiz (Estudiante); y gestión de casos de verificación, SkillCredits y examen de ingreso (Verificador). Las apelaciones y los certificados con riesgo documental alto los revisa un Verificador senior.

#### 3.1.4.1. Mobile Applications Wireframes

Esta sección presenta los wireframes de baja fidelidad de las pantallas principales de la aplicación, elaborados en Figma sobre un frame Android de 412 × 917 px. En esta etapa se definió la estructura de cada pantalla (jerarquía, ubicación de la barra de navegación, botones principales y campos de formulario) sin aplicar todavía colores ni tipografía final, para validar los flujos antes del diseño visual.

Los wireframes cubren las pantallas principales de los dos roles: onboarding, registro, inicio de sesión, declaración de meta, ruta de aprendizaje, detalle del nodo, quiz, resultados y perfil (Estudiante); y casos, revisión con rúbrica y SkillCredits (Verificador). Se presentan a continuación:

**Figura 106**

*Wireframes de las pantallas principales de la aplicación móvil*

<p align="center">
  <img src="images-doc/cap3-mobile-wireframes.png" alt="Wireframes aplicación móvil" width="900">
</p>

*Nota.* Wireframes de baja fidelidad (frame Android de 412 × 917 px) de doce pantallas representativas: onboarding, registro, inicio de sesión, declaración de meta, ruta de aprendizaje, detalle del nodo, quiz y resultado no aprobado (Estudiante); casos, revisión con rúbrica y SkillCredits (Verificador); y perfil (Estudiante). En cada una se fijó la ubicación de la barra de navegación inferior, el botón principal al alcance del pulgar y la agrupación de campos y tarjetas, de acuerdo con la arquitectura de información de 3.1.2. El conjunto completo de wireframes está disponible en [https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo](https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo). Elaboración propia.

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

Esta sección presenta los Wireflows de la aplicación, uno por cada User Goal relevante de los dos roles. Cada Wireflow combina los mock-ups de las pantallas con flechas que indican la acción que lleva de una pantalla a otra: en azul el camino principal (happy path) y en rojo las rutas alternativas y de error, con las pantallas de error resaltadas. En total se elaboraron 37 Wireflows en Figma; a continuación se presentan los correspondientes a los User Goals principales de cada rol.

**Figura 107**

*Wireflow de registro de nuevo usuario*

<p align="center">
  <img src="images-doc/cap3-wireflow-01-registro.png" alt="WF-01 - Registro de nuevo usuario" width="1000">
</p>

*Nota.* User goal: Crear una cuenta con su correo institucional para empezar a validar sus habilidades. Persona: Valeria Ramos (Estudiante) · US01. Valeria recorre las tres páginas del onboarding y completa el registro. Si usa un correo que no termina en .edu.pe, el campo muestra el error en el mismo formulario; al corregirlo, la validación de la contraseña le pide reforzarla. Con los datos válidos llega a la selección de rol. Elaboración propia.

**Figura 108**

*Wireflow de suscripción mensual*

<p align="center">
  <img src="images-doc/cap3-wireflow-32-suscripcion.png" alt="WF-32 - Suscripción mensual" width="1000">
</p>

*Nota.* User goal: Elegir con qué plan empezar a usar SkillSwap. Persona: Valeria Ramos (nueva usuaria) · US05. Tras crear su cuenta, la aplicación le presenta el plan mensual de S/ 29,90 (IGV incluido, cobrado mediante Google Play) con sus beneficios y, como opción secundaria visible, "Continuar con el plan gratuito", que indica los límites del plan gratuito: 1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes a un Verificador, cuyos casos se revisan en hasta 5 días hábiles; el plan mensual, en cambio, permite hasta 3 rutas activas a la vez, sin tope de rutas en total y 10 escalamientos al mes, revisados en 48 horas. Si elige el plan mensual y paga con Google Play Billing, su suscripción queda activa y continúa a la selección de rol; si el banco rechaza el pago, cambia de método y reintenta, y si no tiene método de pago, agrega una tarjeta en Google Play y continúa. Si elige el plan gratuito, continúa directamente a la selección de rol. Más adelante, cuando un Estudiante del plan gratuito alcanza uno de sus límites (por ejemplo, si ya tiene 1 ruta activa e intenta iniciar otra), la pantalla "Alcanzaste el límite de tu plan" le indica el límite alcanzado y le ofrece pasar al plan mensual o continuar con el plan gratuito (soft paywall). El diseño incorpora la opción de continuar con el plan gratuito y la pantalla de límite alcanzado. Elaboración propia.

**Figura 109**

*Wireflow de inicio de sesión y biometría*

<p align="center">
  <img src="images-doc/cap3-wireflow-02-login.png" alt="WF-02 - Inicio de sesión y biometría" width="1000">
</p>

*Nota.* User goal: Entrar a su cuenta de forma rápida y segura para continuar con su ruta. Persona: Valeria Ramos (Estudiante) · US02, US03. Desde el login, Valeria puede entrar con usuario y contraseña o con su huella; en ambos casos llega a la Home de su rol. Si las credenciales no coinciden, un diálogo lo explica sin revelar qué dato falló y le ofrece reintentar o recuperar la contraseña. Elaboración propia.

**Figura 110**

*Wireflow para declarar una meta de aprendizaje*

<p align="center">
  <img src="images-doc/cap3-wireflow-03-declarar-meta.png" alt="WF-03 - Declarar una meta de aprendizaje" width="1000">
</p>

*Nota.* User goal: Describir con sus palabras lo que quiere aprender y obtener una ruta de certificación personalizada. Persona: Valeria Ramos (Estudiante) · US06, US07. Valeria escribe su meta y la IA propone habilidades afines, todas tomadas del catálogo interno de habilidades, ordenadas por afinidad. Al confirmar una, el sistema calcula la brecha y genera su ruta. Si ninguna se ajusta, o la meta es demasiado general, vuelve al campo con un mensaje que le pide precisarla. Elaboración propia.

**Figura 111**

*Wireflow para subir y validar un certificado*

<p align="center">
  <img src="images-doc/cap3-wireflow-05-certificado.png" alt="WF-05 - Subir y validar un certificado" width="1000">
</p>

*Nota.* User goal: Registrar su certificado de Coursera como evidencia del nodo para habilitar el quiz. Persona: Valeria Ramos (Estudiante) · US11, US12, US13, US14, US15, US16. Valeria sube la foto o el archivo y ML Kit extrae los datos en su dispositivo. Si todo es correcto, el quiz se habilita. Hay tres caminos alternativos: el archivo ya estaba registrado (duplicado), el contenido no cubre la habilidad del nodo (afinidad baja) o el análisis detecta riesgo documental y el caso pasa a un Verificador senior. Elaboración propia.

**Figura 112**

*Wireflow para rendir el quiz de un nodo*

<p align="center">
  <img src="images-doc/cap3-wireflow-06-quiz.png" alt="WF-06 - Rendir el quiz de un nodo" width="1000">
</p>

*Nota.* User goal: Demostrar con un quiz que domina la habilidad del nodo y saber qué reforzar. Persona: Valeria Ramos (Estudiante) · US17, US18, US20, US21. Con el certificado validado, Valeria rinde el quiz de cinco preguntas. Si responde correctamente al menos cuatro (80%), aprueba y ve su diagnóstico por sub-tema. Si pierde la conexión, sus respuestas se guardan en el dispositivo y se sincronizan al volver. Si no alcanza el mínimo, ve el sub-tema exacto a reforzar y se abre el caso SK-2057 para un Verificador. Elaboración propia.

**Figura 113**

*Wireflow para recibir y resolver casos (Verificador)*

<p align="center">
  <img src="images-doc/cap3-wireflow-11-casos-verificador.png" alt="WF-11 - Recibir y resolver casos" width="1000">
</p>

*Nota.* User goal: Recibir casos de su especialidad y resolverlos con la rúbrica dentro del plazo. Persona: Rodrigo Castillo (Verificador) · US23, US24, US25. Rodrigo activa su disponibilidad y recibe por afinidad el caso SK-2041. Lo evalúa con la rúbrica, lo aprueba, suma SkillCredits y el caso pasa a su historial. Si un caso vence sin decisión, se reasigna automáticamente a otro Verificador. Elaboración propia.

#### 3.1.4.3. Mobile Applications Mock-ups

Esta sección presenta los mock-ups de alta fidelidad de la aplicación, resultado de aplicar el Design System de 3.1.1 sobre los wireframes. Las pantallas siguen los componentes de Material Design 3 (top app bar, botones filled y outlined, outlined text fields con label visible, chips, segmented buttons, switches, navigation bar y cards) y cumplen los criterios de accesibilidad WCAG 2.2 AA: contraste de texto de al menos 4.5:1, contraste de componentes de al menos 3:1, áreas táctiles de 48 px o más y estados comunicados con ícono y texto además del color.

**Figura 114**

*Mock-ups de la aplicación móvil · Estudiante*

<p align="center">
  <img src="images-doc/cap3-mobile-mockups-estudiante.png" alt="Mock-ups de la aplicación móvil - Estudiante" width="1000">
</p>

*Nota.* Pantallas del Estudiante. El registro valida el dominio `.edu.pe` en línea para prevenir errores; la declaración de meta acepta lenguaje natural y voz, con chips de ejemplo; la ruta muestra los nodos completados, disponibles y bloqueados con ícono, número o candado; la verificación del certificado muestra en una checklist cada paso que realiza la IA; el quiz incluye temporizador y autoguardado visible; y los resultados entregan un diagnóstico por sub-tema, comunicando el no aprobado sin tono punitivo y con el caso de revisión ya abierto. Elaboración propia.

**Figura 115**

*Mock-ups de la aplicación móvil · Verificador*

<p align="center">
  <img src="images-doc/cap3-mobile-mockups-verificador.png" alt="Mock-ups de la aplicación móvil - Verificador" width="1000">
</p>

*Nota.* Pantallas del Verificador. El acceso al rol se habilita al completar en la propia ruta el nodo de la habilidad; el home prioriza los casos por urgencia del plazo y aplica revisión ciega ("Estudiante anónimo") para reducir el sesgo; la revisión del caso combina la evidencia, el puntaje preliminar de la IA con su nivel de confianza y una rúbrica de 4 niveles que sirve de guía para la decisión, que el Verificador registra como aprobación o rechazo con sus observaciones; y la billetera muestra los SkillCredits ganados, su historial y la tienda de beneficios, que ofrece dos beneficios canjeables: la ruta avanzada (200 SkillCredits) y el certificado de contribución (120 SkillCredits). Elaboración propia.

#### 3.1.4.4. Mobile Applications User Flow Diagrams

Esta sección presenta los User Flows de la aplicación, uno por cada User Goal principal, consistentes con los Wireflows de 3.1.4.2. Cada diagrama parte de un punto de inicio, muestra los mock-ups de las pantallas involucradas y representa con rombos las decisiones o condiciones del sistema, de modo que se distingue el happy path (en azul) de las rutas alternativas y de error (en rojo) hasta el punto de fin.

**Figura 116**

*User Flow para registrarse y activar el plan*

<p align="center">
  <img src="images-doc/cap3-userflow-01-registro-suscripcion.png" alt="User Flow para registrarse y activar el plan" width="1000">
</p>

*Nota.* User goal: Crear una cuenta con su correo institucional y elegir el plan con el que empieza su ruta (Estudiante · US01, US05). El flujo parte del registro. Si el correo no termina en `.edu.pe` o la contraseña es débil, se muestra la pantalla de error correspondiente y el Estudiante corrige el dato. Con datos válidos, la aplicación le presenta el plan mensual de S/ 29,90 (IGV incluido, mediante Google Play) con sus beneficios y la opción secundaria "Continuar con el plan gratuito", que indica los límites de ese plan: 1 ruta activa a la vez, hasta 3 rutas en total y 3 escalamientos al mes a un Verificador, cuyos casos se revisan en hasta 5 días hábiles. Si continúa con el plan gratuito, pasa directamente a la selección de rol. Si elige el plan mensual y no tiene un método de pago, lo agrega antes de continuar; si Google Play rechaza el pago, puede cambiar de método y reintentar. Con el pago aprobado, la suscripción queda activa y continúa a la selección de rol. Cuando un Estudiante del plan gratuito alcanza un límite, por ejemplo al intentar iniciar una segunda ruta activa o un cuarto escalamiento en el mes, la pantalla "Alcanzaste el límite de tu plan" le ofrece pasar al plan mensual o continuar con el plan gratuito (soft paywall, WF-32). El diseño incorpora la opción de continuar con el plan gratuito. Elaboración propia.

**Figura 117**

*User Flow para declarar una meta y obtener la ruta*

<p align="center">
  <img src="images-doc/cap3-userflow-02-declarar-meta.png" alt="User Flow para declarar una meta y obtener la ruta" width="1000">
</p>

*Nota.* User goal: Describir con sus palabras lo que quiere aprender y obtener una ruta de certificación personalizada (Estudiante · US06, US07). El Estudiante escribe su meta y la IA propone habilidades del catálogo interno ordenadas por afinidad (si la IA no responde, la propuesta se obtiene por coincidencia de palabras clave sobre el mismo catálogo). Si alguna se ajusta, la confirma y se genera su ruta; si ninguna se ajusta o la meta es muy general, se le pide reformularla y vuelve a recibir propuestas. Elaboración propia.

**Figura 118**

*User Flow para subir y validar un certificado*

<p align="center">
  <img src="images-doc/cap3-userflow-03-subir-certificado.png" alt="User Flow para subir y validar un certificado" width="1000">
</p>

*Nota.* User goal: Registrar su certificado para que la plataforma lo valide y le habilite el quiz del nodo (Estudiante · US11 a US16). Desde el nodo disponible, el Estudiante toma una foto o sube el archivo y la verificación avanza de forma automática. Si el certificado es validado, se habilita el quiz. Las rutas alternativas cubren un archivo ya usado (duplicado), un certificado que no cubre la habilidad del nodo (afinidad baja, con opción de subir otro) y un riesgo documental alto, que deriva el certificado a revisión manual de un Verificador senior. Elaboración propia.

**Figura 119**

*User Flow para rendir el quiz de un nodo*

<p align="center">
  <img src="images-doc/cap3-userflow-04-rendir-quiz.png" alt="User Flow para rendir el quiz de un nodo" width="1000">
</p>

*Nota.* User goal: Demostrar con un quiz que domina la habilidad del nodo y saber exactamente qué reforzar (Estudiante · US17, US18, US20, US21). Con el certificado validado, el Estudiante rinde el quiz. Si pierde la conexión, sus respuestas se guardan en el dispositivo y el quiz continúa al recuperarla. El quiz tiene cinco preguntas: si responde correctamente al menos cuatro (80%), aprueba el nodo; si no alcanza el mínimo, ve el sub-tema exacto a reforzar y se abre automáticamente un caso de revisión asignado a un Verificador. Elaboración propia.

**Figura 120**

*User Flow para recibir y resolver un caso*

<p align="center">
  <img src="images-doc/cap3-userflow-05-resolver-caso.png" alt="User Flow para recibir y resolver un caso" width="1000">
</p>

*Nota.* User goal: Recibir casos de su especialidad y resolverlos con la rúbrica dentro del plazo para ganar SkillCredits (Verificador · US23, US24, US25). El Verificador activa su disponibilidad y recibe un caso por afinidad. Si decide dentro del plazo, el caso queda resuelto y se le acreditan SkillCredits; si el plazo vence sin una decisión, el caso se marca como vencido y se reasigna a otro Verificador. Elaboración propia.

#### 3.1.4.5. Mobile Applications Prototyping

Esta sección presenta el prototipo navegable de la aplicación, elaborado en Figma a partir de los mock-ups. El prototipo reúne 125 pantallas conectadas mediante más de 350 interacciones, que cubren tanto el happy path como las rutas alternativas y de error de los Wireflows. Cuenta con cuatro puntos de inicio: "SkillSwap App" (desde el onboarding), "SkillSwap Landing", y un acceso directo por cada rol ("Rol Estudiante" y "Rol Verificador"). Después del inicio de sesión, la pantalla "¿Cómo quieres entrar?" permite elegir el rol cuando la cuenta tiene más de uno. Las pantallas de carga y confirmación avanzan de forma automática, y en las pantallas con varias salidas el clic sigue el happy path, mientras que las teclas 1, 2 y 3 muestran las rutas alternativas (por ejemplo, el error de credenciales en el inicio de sesión o el certificado duplicado durante la verificación).

**Figura 121**

*Vista del prototipo navegable de SkillSwap en Figma*

<p align="center">
  <img src="images-doc/prototype-screenshot.png" alt="Screenshot del prototipo navegable" width="1000">
</p>

*Nota.* Vista de las conexiones del prototipo correspondientes al recorrido principal del Estudiante: onboarding, registro y suscripción, inicio de sesión, declaración de la meta, ruta, carga y verificación del certificado, quiz y resultados, junto con sus pantallas de error. Elaboración propia.

* **URL del prototipo:** [https://www.figma.com/design/XRhtNjbOaSHmJAs4ebmPuR/Sin-t%C3%ADtulo?node-id=1-3310](https://www.figma.com/design/XRhtNjbOaSHmJAs4ebmPuR/Sin-t%C3%ADtulo?node-id=1-3310)
* **URL del video de interacción:** [https://www.youtube.com/watch?v=PGg34acJh6g](https://www.youtube.com/watch?v=PGg34acJh6g)

---



# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management

### 4.1.1. Software Development Environment Configuration

**Tabla 14**

*Herramientas del entorno de desarrollo de software*

| Herramienta | Propósito | Ruta de referencia / descarga |
|---|---|---|
| IntelliJ IDEA | Desarrollo del backend en Java / Spring Boot | [https://www.jetbrains.com/idea/](https://www.jetbrains.com/idea/) |
| JDK 21 + Apache Maven | Compilación, gestión de dependencias y ejecución del backend | [https://adoptium.net/](https://adoptium.net/), [https://maven.apache.org/](https://maven.apache.org/) |
| Android Studio | Desarrollo de la aplicación móvil nativa (Kotlin / Jetpack Compose) | [https://developer.android.com/studio](https://developer.android.com/studio) |
| Visual Studio Code | Desarrollo del Landing Page (HTML5 / CSS3 / JavaScript) | [https://code.visualstudio.com/](https://code.visualstudio.com/) |
| Git | Control de versiones | [https://git-scm.com/](https://git-scm.com/) |
| GitHub (organización `Aplicaciones-Dispositivos-Moviles`) | Alojamiento de los repositorios, gestión de Pull Requests y publicación del Landing Page (GitHub Pages) | [https://github.com/Aplicaciones-Dispositivos-Moviles](https://github.com/Aplicaciones-Dispositivos-Moviles) |
| PostgreSQL 16 / pgAdmin o DBeaver | Base de datos local de desarrollo y pruebas de integración | [https://www.postgresql.org/](https://www.postgresql.org/), [https://www.pgadmin.org/](https://www.pgadmin.org/) |
| Postman | Pruebas manuales de los endpoints REST durante el desarrollo | [https://www.postman.com/](https://www.postman.com/) |
| springdoc-openapi (Swagger UI) | Documentación interactiva de la API (OpenAPI) | Integrado en el proyecto (`springdoc-openapi-starter-webmvc-ui` 3.1.1), expuesto en `/swagger-ui/index.html` — [https://skillswap-webservices-java.onrender.com/swagger-ui/index.html](https://skillswap-webservices-java.onrender.com/swagger-ui/index.html) |
| JUnit 5 / AssertJ / Spring Boot Test (MockMvc) / Testcontainers | Pruebas unitarias y de integración de la API contra una instancia real de PostgreSQL levantada en Docker | Integrado en el proyecto (`spring-boot-starter-test`, `testcontainers-postgresql`) — [https://junit.org/junit5/](https://junit.org/junit5/), [https://assertj.github.io/doc/](https://assertj.github.io/doc/), [https://testcontainers.com/](https://testcontainers.com/) |
| Docker Desktop | Ejecución de las pruebas de integración con Testcontainers y construcción local de la imagen antes de desplegar en Render | [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/) |
| Render | Hosting del backend (Web Service) y de la base de datos PostgreSQL administrada | [https://render.com/](https://render.com/) |
| Trello | Gestión del Product Backlog y Sprint Backlog (Requirements Management) | [https://trello.com/](https://trello.com/) |
| Figma | Wireframes, mock-ups y prototipo navegable del Landing Page y la aplicación móvil (UX/UI Design) | [https://www.figma.com/](https://www.figma.com/) |
| Google Meet / Discord | Reuniones de Sprint Planning y coordinación del equipo | [https://meet.google.com/](https://meet.google.com/), [https://discord.com/](https://discord.com/) |
| Markdown + GitHub (`SkillSwap-ProjectReport`) | Redacción y versionado del informe del proyecto (Software Documentation) | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport) |



### 4.1.2. Source Code Management

El equipo utiliza **GitHub** como plataforma y sistema de control de versiones, bajo la organización pública `Aplicaciones-Dispositivos-Moviles`. Los repositorios por producto son:

| Producto | Repositorio |
|---|---|
| Web Services (backend Java / Spring Boot, incluye proyecto y pruebas unitarias y de integración) | [`SkillSwap-WebServices-Java`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices-Java) |
| Landing Page | [`SkillSwap-LandingPage`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-LandingPage) |
| Aplicación móvil Android nativa (Kotlin) | [`SkillSwap-MobileApp`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp) |
| Aplicación móvil cross-platform (Flutter) | [`SkillSwap-MobileApp-Flutter`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp-Flutter) |
| Informe del proyecto | [`SkillSwap-ProjectReport`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport) |

El backend se construyó primero en C# / ASP.NET Core, en el repositorio [`SkillSwap-WebServices`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices); cuando el curso estableció Java con Spring Boot como tecnología obligatoria para los Web Services, el equipo lo migró a `SkillSwap-WebServices-Java`, conservando el mismo esquema de base de datos, los mismos endpoints y las mismas reglas de negocio. Desde esa migración, `SkillSwap-WebServices-Java` es el único repositorio vigente del backend y el anterior se conserva solo como historial.

En el Sprint 1, el trabajo sobre la aplicación móvil consistió en el diseño de las pantallas core en Figma (ver 4.2.1.3, tareas T20 y T21); los repositorios `SkillSwap-MobileApp` y `SkillSwap-MobileApp-Flutter` contienen únicamente su `README.md`.

**Flujo de trabajo (GitFlow):**
- `main`: rama estable. En el Landing Page es la rama que publica GitHub Pages.
- `develop`: rama de integración, donde se mergean las ramas `feature/*` mediante Pull Request. En el backend es la rama que despliega Render.
- `feature/<bounded-context>`: una rama por Bounded Context (ej. `feature/iam-identity-access`, `feature/credential-verification`, `feature/learning-path-engine`, `feature/assessment-peer-review`, `feature/reputation`, `feature/recognition-incentives`). Los cambios transversales usan los prefijos `refactor/` y `chore/` (ej. `refactor/remove-coordinator-role`, `chore/deploy-render`, `chore/swagger`).
- `release/x.y.z` y `hotfix/x.y.z`: ramas que define GitFlow para preparar una entrega y para corregir errores críticos; se crean desde `develop` y `main`, respectivamente, y se mergean a ambas.

**Versionado:** el equipo adopta *Semantic Versioning 2.0.0* (`MAJOR.MINOR.PATCH`) como convención de versionado.

**Convenciones de commits:** Conventional Commits (`tipo(alcance): descripción`), con el Bounded Context y la capa como alcance (ej. `iam-domain`, `credential-infrastructure`, `learning-path-interfaces`, `assessment-application`, `reputation`, `recognition-incentives`, `shared`, `deploy`, `docs`). Tipos usados: `feat`, `refactor`, `test` y `chore`. El equipo sigue la convención de **un commit por capa** (Domain, Application, Infrastructure, Interface) dentro de cada Bounded Context, de modo que el historial de commits evidencie el proceso de construcción capa por capa; las pruebas automatizadas de cada capa se incluyen en el mismo commit que la capa que validan, y el tipo `test` se reserva para commits que solo agregan pruebas.

**Flujo de integración:** los Pull Requests hacia `develop` se mergean con la estrategia *"Create a merge commit"* (sin squash), preservando el historial de commits individuales que exige la evidencia de Development/Testing de cada Sprint. El flujo de trabajo local sigue el orden commit → build → test, y solo se hace push al repositorio remoto cuando todo pasa, agrupando varios commits antes de subirlos.

**Secretos:** `application.properties` no contiene ningún secreto: solo documenta, en comentarios, los nombres de las variables de entorno que la aplicación necesita. En desarrollo esas variables se definen en la configuración de ejecución del IDE o en la terminal, y en producción como variables de entorno en Render (ver 4.1.4). El archivo `.dockerignore` excluye `.env` y `.env.*` de la imagen Docker.

### 4.1.3. Source Code Style Guide & Coding Conventions

Todo el código —clases, métodos, variables, paquetes, tablas y nombres de las pruebas— se nombra en **inglés**, conforme al Anexo F del enunciado; el tipo y el alcance de cada commit también van en inglés, mientras que la descripción de los commits del backend se redactó en español. Cada lenguaje del proyecto adopta una guía estándar:

| Lenguaje / artefacto | Guía adoptada |
|---|---|
| Java / Spring Boot (backend) | *Google Java Style Guide* y buenas prácticas de *Spring Boot Features* |
| Kotlin (aplicación móvil) | *Kotlin Coding Conventions* de JetBrains/Google |
| HTML / CSS / JavaScript (Landing Page) | *Google HTML/CSS Style Guide* y *HTML Style Guide and Coding Conventions* |

**Backend (Java):** clases, interfaces y enums en `PascalCase`; métodos, parámetros y variables locales en `camelCase`; constantes en `UPPER_SNAKE_CASE`; paquetes en minúsculas bajo `com.innovify.skillswap.<bounded-context>`. Las interfaces se nombran **sin prefijo `I`** (ej. `PaymentGateway`, con su implementación en la capa Infrastructure). Los servicios siguen la nomenclatura `*CommandService` / `*QueryService`, los controladores `*Controller` y los recursos de la API `*Resource`.

**Base de datos:** las tablas y columnas siguen `snake_case` (ej. `verifier_user_id`), y los enums se persisten como texto (no como enteros), para mantener legibilidad directa en consultas SQL.

**Pruebas:** las clases de prueba replican el paquete de la clase que validan y terminan en `Test` (ej. `EmailTest`, `CertificatesApiIntegrationTest`); los métodos describen la operación, la condición y el resultado esperado con el patrón `metodo_condicion_resultado` (ej. `constructor_withInvalidEmail_throwsDomainException`, `uploadOfAFileOverTenMegabytes_returns413`), y las pruebas de integración que trasladan escenarios de aceptación usan `@DisplayName` con el nombre del escenario (ej. "Reject a file larger than 10 MB").

### 4.1.4. Software Deployment Configuration

El despliegue abarca los tres productos digitales de la solución:

- **Web Services:** contenedor **Docker** en **Render** (plan gratuito), junto con una base de datos **PostgreSQL 16** también administrada por Render (plan gratuito), en la misma región.
- **Landing Page:** sitio estático (HTML5/CSS3/JavaScript) publicado con **GitHub Pages** desde la rama `main` del repositorio `SkillSwap-LandingPage`.
- **Aplicación móvil:** en el Sprint 1 se entregan sus pantallas core como prototipo en Figma; los repositorios `SkillSwap-MobileApp` y `SkillSwap-MobileApp-Flutter` contienen únicamente su `README.md`.

**Dockerfile del backend:** build multi-etapa. La etapa de compilación parte de la imagen `maven:3.9-eclipse-temurin-21` y ejecuta `mvn -B -q -DskipTests package`, que genera un único JAR ejecutable de Spring Boot (`skillswap-platform-*.jar`); las pruebas no se ejecutan dentro de la imagen porque requieren Docker (Testcontainers) y se corren localmente antes de cada push. La etapa de ejecución usa la imagen `eclipse-temurin:21-jre`, que solo contiene el JRE y ese JAR, y ejecuta la aplicación con un usuario sin privilegios (`skillswap`). La variable `JAVA_TOOL_OPTIONS` limita la memoria de la JVM al 75 % de la disponible y reinicia el proceso ante un `OutOfMemoryError`, pensando en las instancias de 512 MB del plan gratuito. La aplicación escucha en el puerto de la variable de entorno `PORT` que asigna Render (`server.port=${PORT:8080}`, por defecto `8080`). El archivo `.dockerignore` excluye `target/`, `.git/`, `.idea/`, `.vscode/`, `docs/`, los archivos `.env` / `.env.*` y los logs.

**Rama de despliegue:** Render construye la imagen Docker desde la rama `develop` del repositorio `SkillSwap-WebServices-Java`, y cada despliegue se lanza manualmente desde el panel de Render.

**Variables de entorno del backend** (solo nombres; los valores no se exponen en el informe ni en el repositorio; en producción se definen en Render):

**Tabla 15**

*Variables de entorno del backend*

| Variable | Propósito |
|---|---|
| `DATABASE_URL` | URL interna de la base de datos PostgreSQL de Render (`postgres://usuario:clave@host:5432/db`); la aplicación la convierte a una URL JDBC |
| `TOKEN_SETTINGS_SECRET` | Secreto para la firma de los tokens JWT (obligatorio, mínimo 32 caracteres) |
| `TOKEN_SETTINGS_EXPIRATION_DAYS` | Vigencia del token en días (opcional, por defecto 7) |
| `CLOUDINARY_CLOUD_NAME` / `CLOUDINARY_API_KEY` / `CLOUDINARY_API_SECRET` | Credenciales de la integración con Cloudinary (obligatorias: sin ellas la aplicación no arranca) |
| `GEMINI_API_KEY` | Clave de la API de Gemini para la generación de preguntas y la interpretación de la meta (obligatoria) |
| `GEMINI_MODEL`, `GEMINI_FALLBACK_MODELS` | Modelo principal (por defecto `gemini-3.5-flash`) y modelos de respaldo, separados por comas (opcionales) |
| `GEMINI_GOAL_INTERPRETATION_ENABLED` | Si la meta se interpreta con Gemini (por defecto `true`); con `false` solo se usa la comparación por palabras clave |
| `GEMINI_GOAL_INTERPRETATION_TIMEOUT_SECONDS` | Tiempo máximo de espera de la interpretación de la meta con Gemini (por defecto 20 segundos) |
| `LEARNING_PATH_ASSESSMENT_REQUIRE_LINKED_CERTIFICATE` | Si la evaluación de un nodo exige un certificado vinculado (por defecto `false`) |
| `BREVO_API_KEY` | Clave de la API de correo transaccional de Brevo; sin ella, los correos de verificación se escriben en el log |
| `EMAIL_SENDER_ADDRESS` / `EMAIL_SENDER_NAME` | Dirección remitente verificada en Brevo (obligatoria junto con `BREVO_API_KEY`) y nombre del remitente (por defecto `SkillSwap`) |
| `APP_VERIFICATION_BASE_URL` | URL pública del backend con la que se arma el enlace de verificación (`<url>/api/v1/authentication/verify-email`) |
| `APP_VERIFICATION_TOKEN_TTL` | Vigencia del enlace de verificación (por defecto `24h`) |
| `APP_VERIFICATION_RESEND_COOLDOWN` | Tiempo mínimo entre dos correos de verificación a una misma cuenta (por defecto `2m`) |
| `FIREBASE_CREDENTIALS_BASE64` | JSON de la cuenta de servicio del proyecto de Firebase, en Base64, para enviar notificaciones push con Firebase Cloud Messaging; sin ella, las notificaciones se escriben en el log |
| `REVENUECAT_API_KEY` | Clave secreta de RevenueCat; sin ella, las compras se simulan con `SimulatedPaymentGatewayAdapter` y no se cobra nada |
| `REVENUECAT_WEBHOOK_AUTH` | Valor exacto del encabezado `Authorization` del webhook; sin ella se rechazan todas las notificaciones |
| `REVENUECAT_ENTITLEMENT_ID` / `REVENUECAT_ACCEPT_SANDBOX` | Entitlement que otorga el plan mensual (por defecto `premium`) y si se aplican las compras de prueba (por defecto `true`) |
| `BILLING_EXPIRATION_CHECK_INTERVAL` / `BILLING_SIMULATED_PERIOD` | Frecuencia de la revisión de suscripciones vencidas (por defecto `1h`) y duración del período del adaptador simulado (por defecto `30d`) |
| `REVIEW_DEADLINE_CHECK_INTERVAL` | Frecuencia de la búsqueda de casos con el plazo de revisión vencido (por defecto `15m`) |
| `MODERATION_ASSIGNMENT_RETRY_INTERVAL` | Frecuencia del reintento de asignación de las disputas sin revisor (por defecto `15m`) |
| `CORS_ALLOWED_ORIGINS` | Orígenes permitidos para el consumo de la API desde el Landing Page y la aplicación |

*Nota.* Elaboración propia.

**Esquema de base de datos:** al arrancar, la aplicación convierte `DATABASE_URL` al formato JDBC; el esquema se gestiona con **Flyway** mediante las migraciones versionadas V1 a V10 (`src/main/resources/db/migration`), y Hibernate valida que las tablas y columnas coincidan con las entidades JPA (`spring.jpa.hibernate.ddl-auto=validate`), sin crear ni modificar el esquema; si falta algo, la aplicación no arranca. V1 es el esquema base que creó la primera versión del backend en la base de PostgreSQL de Render, por lo que Flyway lo registra como baseline sin ejecutarlo (`spring.flyway.baseline-on-migrate=true`, `baseline-version=1`); en una base vacía, como la de las pruebas o la local, V1 crea todo el esquema. Las demás migraciones agregan `case_type` (V2), `subscriptions` y `processed_webhook_events` (V3), el estado `Paused`, `last_progress_at` y la eliminación del índice de una sola ruta activa (V4), `review_due_at` (V5), las columnas de verificación del correo (V6), los intereses y el vector de habilidades (V7), `completed_by_certificate` (V8), `full_name`, `holder_name_mismatch` y la tabla `disputes` (V9), y `redemption_item`, `is_advanced`, `advanced_path_unlocks`, `review_deadline_policies` y las columnas de plazo e incumplimiento (V10). No se crea ninguna cuenta inicial: toda cuenta se registra como `Student` mediante `POST /api/v1/authentication/sign-up`.

**Observabilidad y disponibilidad:** el endpoint `GET /health` (anónimo, sin acceso a la base de datos) se usa tanto para el health check de Render como para un ping de mantenimiento cada 10 minutos, dado que el plan gratuito de Render suspende el servicio tras 15 minutos sin tráfico. Swagger UI permanece activo también en producción (`/swagger-ui/index.html`, con el documento OpenAPI en `/v3/api-docs`), y tanto la raíz (`/`) como `/swagger` redirigen automáticamente a la documentación.

**Limitación conocida:** la base de datos PostgreSQL gratuita de Render expira 30 días después de creada, con 14 días de gracia.

**Figura 122**

*Deployment Diagram de SkillSwap (C4 Model)*

<p align="center">
  <img src="images-doc/c4-deployment-diagram.svg" alt="Deployment Diagram de SkillSwap" width="900">
</p>

*Nota.* Aplicaciones Android nativa y cross-platform como clientes de la API y Landing Page estático en GitHub Pages, API Spring Boot en un contenedor Docker con JRE 21 sobre Render, PostgreSQL administrado, y los servicios externos Cloudinary, Brevo (Email API), Firebase Cloud Messaging, Gemini API y Google Play Billing (vía RevenueCat). Elaboración propia.

---

## 4.2. Landing Page, Services & Applications Implementation

### 4.2.1. Sprint 1

#### 4.2.1.1. Sprint Planning 1

El Sprint 1 corresponde a la primera iteración de desarrollo del proyecto, enfocada en construir la base funcional del backend en sus ocho Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation, Recognition & Incentives, Subscription & Billing y Moderation & Disputes) y en avanzar el diseño UI/UX de la Landing Page y las pantallas core de la aplicación móvil. La reunión de planificación definió el Sprint Goal, la velocidad del equipo y las historias que entran al Sprint.

**Tabla 16**

*Sprint Planning 1*

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-10-04 |
| Time | 11:00 AM |
| Location | Virtual (Google Meet / Discord) |
| Prepared By | Alberca Saavedra, Víctor Manuel |
| Attendees (to planning meeting) | Alberca Saavedra, Víctor Manuel / Becerra Ninahuanca, Luis Angel / Komatsu Dueñas, David / Lopez Montalvo, Kevin Edu / Sulca Sánchez, Piero Angel |
| Sprint n − 1 Review Summary | No aplica — es el primer Sprint del proyecto. |
| Sprint n − 1 Retrospective Summary | No aplica — es el primer Sprint del proyecto. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on construir el núcleo funcional de SkillSwap: registro con verificación del correo institucional y autenticación, carga y validación de certificados con escalamiento de los sospechosos a un Verificador senior, generación de rutas de aprendizaje a partir de la taxonomía de habilidades (con la meta interpretada por Gemini y la comparación por palabras clave como respaldo) con evaluaciones asistidas por IA, el ciclo completo de evaluación y revisión por pares con plazos de revisión por plan, la suscripción mensual con sus límites y la billetera de SkillCredits. We believe it delivers a un Estudiante la posibilidad de demostrar una habilidad de principio a fin dentro de la plataforma, y a un Verificador la posibilidad de revisar casos reales. This will be confirmed when el backend esté desplegado públicamente, documentado con OpenAPI, y un Estudiante pueda completar el flujo registro → certificado → ruta → evaluación → caso resuelto sin intervención manual. |
| Sprint 1 Velocity | 154 SP |
| Sum of Story Points | 154 SP |

*Nota.* Elaboración propia.

**Figura 123**

*Reunión de Sprint Planning 1*

<p align="center">
  <img src="images-doc/sprint-planning-1-meeting.png" alt="Reunión de Sprint Planning 1" width="900">
</p>

*Nota.* Reunión de Sprint Planning 1 realizada por Google Meet. Elaboración propia.

#### 4.2.1.2. Aspect Leaders and Collaborators

El equipo organizó el Sprint 1 en tres frentes: el backend, dividido por Bounded Context junto con su despliegue en Render; la Landing Page; y el diseño UX/UI de la aplicación móvil. Cada aspecto tiene un Líder responsable y, cuando corresponde, colaboradores. La matriz es coherente con la asignación de tasks del Sprint Backlog (4.2.1.3): la base del backend en seis Bounded Contexts y su despliegue (T01–T17 y T22) están a cargo de Alberca Saavedra, Víctor Manuel; Subscription & Billing, Moderation & Disputes, las migraciones con Flyway y las funcionalidades que se agregaron sobre los demás Bounded Contexts (T23–T43) están a cargo de Sulca Sánchez, Piero Angel; la implementación del Landing Page se repartió entre ambos (T18 y T19), y el diseño de la aplicación móvil en Figma (T20 y T21) estuvo a cargo de Becerra Ninahuanca, Luis Angel.

**Tabla 17**

*Leadership-and-Collaboration Matrix del Sprint 1*

| Team Member (Last Name, First Name) | GitHub Username | Identity & Access | Credential Verification | Learning Path Engine | Assessment & Peer Review | Reputation | Recognition & Incentives | Subscription & Billing | Moderation & Disputes | Despliegue (Render) | Landing Page UI | Mobile App UX/UI |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Alberca Saavedra, Víctor Manuel | Agnizzz | L | L | L | L | L | L | | | L | C | C |
| Becerra Ninahuanca, Luis Angel | blafyy | | | | | | | | | | L | L |
| Lopez Montalvo, Kevin Edu | lopescamos | | | | | | | | | | C | C |
| Komatsu Dueñas, David | dakoduz | | | | | | | | | | C | C |
| Sulca Sánchez, Piero Angel | psulca | C | C | C | C | C | C | L | L | C | C | C |

*Nota.* L = Leader, C = Collaborator. Elaboración propia.

#### 4.2.1.3. Sprint Backlog 1

El objetivo del Sprint 1 es entregar el backend funcional de los ocho Bounded Contexts, desplegado y documentado con OpenAPI, junto con la Landing Page y el diseño de las pantallas core de la aplicación móvil. El tablero del Sprint se gestionó en Trello con las columnas To-Do / In-Process / To-Review / Done.

**Figura 124**

*Sprint Backlog 1 en Trello*
<p align="center">
  <img src="images-doc/sprint1-board.png" alt="Sprint Backlog Board - Sprint 1" width="300">
</p>

*Nota.* Lista Sprint 1 del tablero del Product Backlog en Trello, con las historias del Sprint 1. URL público del Board: [https://trello.com/b/sTMGwnPf/skillswap-product-backlog](https://trello.com/b/sTMGwnPf/skillswap-product-backlog)

**Tabla 18**

*Sprint Backlog 1*

| Sprint # | Sprint 1 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | **Work-Item / Task** | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| TS01 | Endpoint de registro de usuarios | T01 | Domain Layer de Identity & Access | Agregado `User`, Value Objects (`Username`, `Email`, `PasswordHash`, `DeviceToken`) y servicios de dominio (`PasswordHasher`, `EmailDomainValidator`) | 8 | Alberca Saavedra, Víctor Manuel | Done |
| TS01 / TS02 | Endpoint de registro / autenticación JWT | T02 | Application + Interface Layer de autenticación | `UserCommandServiceImpl` (sign-up / sign-in), `AuthenticationController`, `JwtTokenGenerator`, `BCryptPasswordHasher`, `SecurityConfig` con `JwtAuthenticationFilter` | 8 | Alberca Saavedra, Víctor Manuel | Done |
| TS03 | Endpoint de registro de certificados | T03 | Agregado `Certificate` de Credential Verification | Agregado `Certificate`, enumeración `VerificationStatus` y transiciones de estado del certificado | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS03 | Endpoint de registro de certificados | T04 | Evaluación de riesgo del certificado | Value Object `RiskAssessment`, enumeración `RiskLevel` y servicio de dominio `CertificateRiskScorer` | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS03 / TS04 | Endpoints de certificados | T05 | Application Layer de Credential Verification | `CertificateCommandServiceImpl`, `CertificateQueryService` y `CredentialContextFacade` para los demás Bounded Contexts | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS03 / TS04 | Endpoints de certificados | T06 | Infrastructure Layer de Credential Verification | Persistencia JPA y `CloudinaryStorageService` (almacenamiento privado, URL firmada) | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS05 | Endpoints de generación y consulta de rutas | T07 | Domain Layer de Learning Path Engine | Agregado `LearningPath`, entidad `PathNode` y servicios de dominio `LearningPathBuilder` y `SkillGapAnalyzer` | 6 | Alberca Saavedra, Víctor Manuel | Done |
| TS05 | Endpoints de generación y consulta de rutas | T08 | Taxonomía de habilidades | Catálogo de 55 habilidades (`skill-catalog.json`), puerto `SkillTaxonomyMatcher` y adaptador `KeywordSkillTaxonomyMatcher` | 6 | Alberca Saavedra, Víctor Manuel | Done |
| TS06 | Endpoint de generación de evaluaciones | T09 | Agregado `AssessmentBlueprint` | Agregado `AssessmentBlueprint` y endpoint `POST /api/v1/path-nodes/{nodeId}/assessment-blueprint` | 4 | Alberca Saavedra, Víctor Manuel | Done |
| TS06 | Endpoint de generación de evaluaciones | T10 | Integración con Gemini API | `GeminiQuestionGenerator` con modelo principal y cadena de modelos de respaldo | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS07 / TS08 | Endpoints de intentos y casos de verificación | T11 | Agregados de intentos y casos de verificación | Agregados `AssessmentAttempt` y `VerificationCase` con sus transiciones de estado | 7 | Alberca Saavedra, Víctor Manuel | Done |
| TS07 / TS08 | Endpoints de intentos y casos de verificación | T12 | Perfil del Verificador y asignación | Agregado `VerifierProfile` y servicio de dominio `VerifierMatcher` | 7 | Alberca Saavedra, Víctor Manuel | Done |
| TS07 / TS08 | Endpoints de intentos y casos de verificación | T13 | Application Layer de Assessment & Peer Review | Command/Query Services, `CaseAssignmentService` (servicio interno de la Application Layer) y eventos `AssessmentAttemptPassed` / `VerificationCaseResolved` | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS07 / TS08 | Endpoints de intentos y casos de verificación | T14 | Interface Layer de Assessment & Peer Review | `AssessmentAttemptsController`, `VerificationCasesController` y `VerifierProfilesController`, con sus resources y assemblers | 5 | Alberca Saavedra, Víctor Manuel | Done |
| TS11 | Endpoints de consulta de reputación | T15 | Domain + Application Layer de Reputation | Agregados `VerifierReliability`, `StudentEmployabilityScore`; event handlers de Assessment & Peer Review | 8 | Alberca Saavedra, Víctor Manuel | Done |
| TS09 | Endpoints de billetera y canje | T16 | Domain + Application Layer de Recognition & Incentives | Agregados `Wallet`, `CreditTransaction`; event handlers de Identity & Access y Assessment & Peer Review | 8 | Alberca Saavedra, Víctor Manuel | Done |
| TS12 | Despliegue del backend en producción | T17 | Dockerfile + configuración de Render | Build multi-etapa (Maven + JRE 21), variables de entorno, validación del esquema al arrancar, `GET /health` y Swagger UI público | 6 | Alberca Saavedra, Víctor Manuel | Done |
| US41 / US42 / US45 | Landing Page | T18 | Implementación del Landing Page | HTML5/CSS3/JS, imágenes y diseño responsive, publicado en GitHub Pages desde `main` (PR #1 a #6 de `SkillSwap-LandingPage`) | 5 | Alberca Saavedra, Víctor Manuel | Done |
| US43 / US44 | Consulta de planes y precios / Descarga de la aplicación | T19 | Sección de planes y llamado a descargar la app | Sección de precios del modelo freemium, CTA "Descarga la app" y flujo "¿Cómo funciona?" (PR #7 y #8 de `SkillSwap-LandingPage`) | 5 | Sulca Sánchez, Piero Angel | Done |
| — | Pantallas core de la app móvil | T20 | Wireframes y mock-ups de la app móvil | Wireframes y mock-ups en Figma de las pantallas de registro, ruta de aprendizaje, quiz y casos de verificación | 6 | Becerra Ninahuanca, Luis Angel | Done |
| — | Pantallas core de la app móvil | T21 | Prototipo navegable de la app móvil | Prototipo navegable en Figma con los flujos del Estudiante y del Verificador | 6 | Becerra Ninahuanca, Luis Angel | Done |
| US27 | Apelación de la decisión del Verificador | T22 | Apelación de casos de verificación | `AppealVerificationCaseCommand` y `VerificationCase.appeal()` (una sola apelación por caso), reasignación a otro Verificador habilitado mediante `CaseAssignmentService` y endpoint `POST /api/v1/verification-cases/{id}/appeal` | 6 | Alberca Saavedra, Víctor Manuel | Done |
| TS12 | Despliegue del backend en producción | T23 | Migraciones versionadas con Flyway | `spring-boot-starter-flyway`, `V1__baseline_schema.sql` registrado como baseline sobre la base existente (`baseline-on-migrate`) y pruebas de integración con el esquema que crea Flyway | 5 | Sulca Sánchez, Piero Angel | Done |
| US30 / US32 | Acreditación y canje de SkillCredits | T24 | Tipo de caso y economía de SkillCredits | `CaseType` (`Quiz` / `MiniProject`) en `VerificationCase`, 40 y 25 SkillCredits por caso resuelto, precios de canje de 200 y 120 SkillCredits y migración V2 | 6 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T25 | Domain Layer de Subscription & Billing | Agregado `Subscription`, Value Objects `SubscriptionPlan`, `Money` y `PlanLimits`, eventos `SubscriptionActivated` / `SubscriptionExpired` y migración V3 | 8 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T26 | Integración con RevenueCat | Puerto `PaymentGateway` con `RevenueCatGatewayAdapter` y `SimulatedPaymentGatewayAdapter`, `SubscriptionsController` (`POST /api/v1/subscriptions`, `GET /{studentId}`, `PATCH /{id}/cancel`) | 8 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T27 | Webhook de RevenueCat y vencimiento de suscripciones | `RevenueCatWebhookController` idempotente (`processed_webhook_events`), `SubscriptionExpirationScheduler` y `SubscriptionContextFacade` con los límites del plan | 6 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T28 | Límites del plan en las rutas | `PathStatus.PAUSED`, pausa y reanudación de rutas, `409 PlanLimitReached`, bloqueo `pg_advisory_xact_lock` por estudiante, `EnforcePlanLimitsEventHandler` y migración V4 | 8 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T29 | Cupo de escalamientos y plazo de revisión por plan | Cupo mensual de 3 o 10 escalamientos, `planLimitReached` en la respuesta del intento y `review_due_at` según el plan (migración V5) | 6 | Sulca Sánchez, Piero Angel | Done |
| US01 / US02 | Registro e inicio de sesión | T30 | Verificación del correo institucional | `EmailVerificationCommandService`, token de un solo uso guardado como SHA-256, `POST`/`GET /api/v1/authentication/verify-email`, `POST /resend-verification`, `403 EmailNotVerified` y migración V6 | 8 | Sulca Sánchez, Piero Angel | Done |
| US01 | Registro con correo institucional | T31 | Envío de correos con Brevo | Puerto `EmailSender`, `BrevoEmailSenderAdapter`, `LoggingEmailSenderAdapter` y `VerificationEmailComposer` | 5 | Sulca Sánchez, Piero Angel | Done |
| US16 | Consulta del estado de verificación | T32 | Notificaciones push con Firebase Cloud Messaging | Puerto `PushNotificationSender`, `FirebasePushNotificationAdapter`, `PUT`/`DELETE /api/v1/users/me/device-token`, `UserNotificationsContextFacade` y `NotifyCertificateResolutionEventHandler` | 8 | Sulca Sánchez, Piero Angel | Done |
| US04 | Configuración del perfil de intereses | T33 | Perfil de intereses con vector de habilidades | `PUT /api/v1/users/{id}/interests`, cálculo del vector con `SkillCatalogContextFacade` y migración V7 | 5 | Sulca Sánchez, Piero Angel | Done |
| US06 / TS05 | Declaración de la meta en lenguaje natural | T34 | Interpretación de la meta con Gemini | `GeminiSkillTaxonomyMatcher` con respaldo en `KeywordSkillTaxonomyMatcher` y `GeminiClient` compartido con el generador de preguntas | 8 | Sulca Sánchez, Piero Angel | Done |
| US09 | Reconocimiento de habilidades ya certificadas | T35 | Certificados validados en la ruta | Evento `CertificateVerified`, `RecognizeValidatedCertificateEventHandler`, `completedByCertificate` y migración V8 | 6 | Sulca Sánchez, Piero Angel | Done |
| US15 | Correspondencia del certificado con la habilidad | T36 | Vinculación del certificado a un nodo | `POST /api/v1/path-nodes/{nodeId}/certificate`, puerto `CertificateSkillAffinityScorer` con umbral 0,7 y `422 CertificateSkillMismatch` con los nodos sugeridos | 6 | Sulca Sánchez, Piero Angel | Done |
| US17 | Generación del quiz de un nodo | T37 | Nuevo intento sin preguntas repetidas | Preguntas anteriores del nodo como exclusiones en `GeminiQuestionGenerator` y reemplazo de las repetidas | 4 | Sulca Sánchez, Piero Angel | Done |
| US13 / US14 | Detección de certificados sospechosos | T38 | Titular distinto y archivo de otro estudiante | `HolderNameMatcher`, `users.full_name` y `PATCH /api/v1/users/{id}/full-name`, `certificates.holder_name_mismatch` y evento `CertificateFlaggedSuspicious` | 6 | Sulca Sánchez, Piero Angel | Done |
| TS10 / US34 | Endpoints de gestión de disputas | T39 | Domain + Application Layer de Moderation & Disputes | Agregado `Dispute`, `DisputeReviewerSelector`, `DisputeResolutionValidator`, `EscalateCertificateReviewEventHandler`, `PendingDisputeAssignmentScheduler` y migración V9 | 8 | Sulca Sánchez, Piero Angel | Done |
| TS10 / US34 / US35 | Consulta y resolución de disputas | T40 | Interface Layer de Moderation & Disputes | `DisputesController` (`GET /api/v1/disputes`, `GET /{id}/evidence`, `PATCH /{id}/resolve`) y resolución del certificado mediante `CredentialContextFacade` | 6 | Sulca Sánchez, Piero Angel | Done |
| US05 | Suscripción al plan mensual | T41 | Ruta avanzada canjeada con SkillCredits | Agregado `AdvancedPathUnlock`, evento `AdvancedPathUnlockRedeemed`, `credit_transactions.redemption_item`, `"advanced": true` en `POST /api/v1/learning-paths` y `GET /api/v1/advanced-path-unlocks` | 8 | Sulca Sánchez, Piero Angel | Done |
| US39 | Definición del plazo de actividad de los Verificadores | T42 | Plazo de revisión definido por el Verificador senior | Agregado `ReviewDeadlinePolicy`, `ReviewDeadlinePoliciesController` (`GET`/`PUT /api/v1/review-deadline-policies`), `SeniorVerifierPolicy` y migración V10 | 6 | Sulca Sánchez, Piero Angel | Done |
| US39 | Definición del plazo de actividad de los Verificadores | T43 | Reasignación de casos vencidos | `OverdueCaseReassignmentScheduler`, evento `VerificationCaseDeadlineMissed` y descuento de 5 puntos de confiabilidad (`missed_deadlines_count`) | 6 | Sulca Sánchez, Piero Angel | Done |

*Nota.* Elaboración propia.

Las tareas T01 a T17 y T22 construyeron la base del backend en seis Bounded Contexts, integrada a `develop` mediante los PR #1 a #10 del repositorio `SkillSwap-WebServices-Java`. Sobre esa base, las tareas T23 a T29 corresponden a los PR #11 a #14, apilados uno sobre otro: las migraciones con Flyway (#11, `chore/flyway-migrations`), el tipo de caso y la economía de SkillCredits (#12, `feature/verification-case-type`), Subscription & Billing con RevenueCat (#13, `feature/subscription-billing`) y la aplicación de los límites del plan (#14, `feature/plan-limits-enforcement`). Las tareas T30 a T43 se desarrollaron en tres ramas creadas desde `feature/plan-limits-enforcement`: `feature/iam-email-verification-push` (verificación del correo con Brevo, notificaciones push con Firebase Cloud Messaging y perfil de intereses), `feature/learning-path-gemini-matcher` (interpretación de la meta con Gemini, certificados validados en la ruta, correspondencia del certificado con el nodo y nuevos intentos sin preguntas repetidas) y `feature/certificate-escalation-and-deadlines` (escalamiento de certificados sospechosos mediante Moderation & Disputes, ruta avanzada canjeada con SkillCredits y plazos de revisión por plan con reasignación de casos vencidos). Las tres ramas se integraron en `feature/complete-acceptance-scenarios`, que llegó a `develop` mediante el PR #15; con ello el esquema queda definido por las migraciones V1 a V10 y la suite completa suma 1978 pruebas. Las tareas T18 y T19 corresponden a los PR #1 a #6 y #7 a #8 del repositorio `SkillSwap-LandingPage`, respectivamente.

#### 4.2.1.4. Development Evidence for Sprint Review

El equipo organizó el desarrollo del backend Java / Spring Boot en una rama `feature/<bounded-context>` por Bounded Context, más ramas `refactor/` y `chore/` para los cambios transversales, siguiendo Conventional Commits con un commit por capa (Domain, Application, Infrastructure, Interface). Cada rama se integró a `develop` mediante un Pull Request mergeado con la estrategia "Create a merge commit" (PR #1 a #10 del repositorio `SkillSwap-WebServices-Java`). Sobre esa base, los PR #11 a #14 se apilan uno sobre otro, y las ramas `feature/iam-email-verification-push`, `feature/learning-path-gemini-matcher` y `feature/certificate-escalation-and-deadlines` se integran en `feature/complete-acceptance-scenarios`, que llega a `develop` mediante el PR #15. La tabla incluye todos los commits de desarrollo del Sprint 1 y los merges de los PR #1 a #15; los commits que solo agregan pruebas se detallan en 4.2.1.5.

**Tabla 19**

*Commits de desarrollo del backend en el Sprint 1*

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| SkillSwap-WebServices-Java | main | `04eb1ce` | chore: initialize project | Proyecto Spring Boot con Maven Wrapper, `pom.xml` y la clase `SkillswapPlatformApplication`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `09f0027` | chore(shared): agrega Result, eventos de dominio, i18n, CORS, health y conversión de DATABASE_URL | Shared kernel: `Result`, `DomainEvent` / `DomainEventPublisher`, resolución del idioma es-419, `CorsConfig`, `HealthController` y `PostgresUrlConverter`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `2cc5384` | chore(shared): elimina carpeta test duplicada fuera de src | Retira una copia duplicada de las pruebas del shared kernel que había quedado fuera de `src/test`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `8618574` | feat(iam-domain): agrega User, value objects, commands, queries y servicios de dominio | Agregado `User`; Value Objects `Username`, `Email`, `PasswordHash`, `DeviceToken` y `UserRole`; evento `UserRegistered`; servicios `PasswordHasher` y `EmailDomainValidator`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `88de188` | feat(iam-application): implementa UserCommandService y UserQueryService con mensajes en inglés y es-419 | Servicios de comando y consulta de usuarios; mensajes de error en `messages.properties` y `messages_es_419.properties`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `9237915` | feat(iam-infrastructure): agrega persistencia JPA, BCrypt, JWT, seguridad stateless y seeder del coordinador | Repositorio JPA y converters, `BCryptPasswordHasher`, `JwtTokenGenerator`, `SecurityConfig` stateless con `JwtAuthenticationFilter`. El seeder se retiró después en `52ec296` y `de8709b`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `b8c0c0a` | feat(iam-interfaces): agrega AuthenticationController, UsersController, resources y manejo de errores ProblemDetail | Endpoints de sign-up, sign-in y perfil, resources, assemblers y `RestExceptionHandler` con respuestas ProblemDetail. | 2026-10-08 |
| SkillSwap-WebServices-Java | develop | `9d19a92` | Merge pull request #1 from Aplicaciones-Dispositivos-Moviles/feature/iam-identity-access | Integración de `feature/iam-identity-access` a `develop`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `ed0c022` | feat(credential-domain): agrega agregado Certificate, evaluación de riesgo y puertos de dominio | Agregado `Certificate`, `RiskAssessment`, `RiskLevel`, `VerificationStatus` y `CertificateRiskScorer`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `e140823` | feat(credential-application): implementa servicios de comando y consulta, facade y mensajes de verificación de certificados | `CertificateCommandService`, `CertificateQueryService` y `CredentialContextFacade` para los demás Bounded Contexts. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `5a0bc00` | feat(credential-infrastructure): agrega persistencia JPA, conversores y almacenamiento en Cloudinary vía REST | Repositorio JPA, converters y `CloudinaryStorageService` (archivo privado y URL firmada). | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `7501882` | feat(credential-interfaces): expone endpoints REST de certificados con carga multipart y manejo de errores | `CertificatesController` con carga `multipart/form-data` y respuestas 409, 413 y 415. | 2026-10-08 |
| SkillSwap-WebServices-Java | develop | `5f7f25f` | Merge pull request #2 from Aplicaciones-Dispositivos-Moviles/feature/credential-verification | Integración de `feature/credential-verification` a `develop`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `dab0945` | feat(learning-path-domain): agrega agregados, value objects y servicios de dominio de la ruta de aprendizaje | Agregados `LearningPath` y `AssessmentBlueprint`, entidad `PathNode`, `CareerGoal`, `SkillGap`, `LearningPathBuilder` y `SkillGapAnalyzer`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `73f6dd3` | feat(learning-path-application): agrega servicios de comando y consulta, fachada ACL y mensajes de la ruta de aprendizaje | Servicios de rutas y blueprints, `LearningPathContextFacade` y puerto `SkillTaxonomyMatcher`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `db58943` | feat(learning-path-infrastructure): agrega persistencia JPA, catalogo de skills, matcher y generador Gemini | Persistencia JPA, `skill-catalog.json` (55 habilidades), `KeywordSkillTaxonomyMatcher` y `GeminiQuestionGenerator` con modelos de respaldo. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `88acb17` | feat(learning-path-interfaces): agrega controllers REST, resources y tests de la API | `LearningPathsController`, `AssessmentBlueprintsController`, resources y assemblers. | 2026-10-08 |
| SkillSwap-WebServices-Java | develop | `d42fc4b` | Merge pull request #3 from Aplicaciones-Dispositivos-Moviles/feature/learning-path-engine | Integración de `feature/learning-path-engine` a `develop`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `d7902d6` | feat(assessment-application): agrega servicios de comando, consulta, asignación de casos y ACL | Servicios de intentos, casos y perfiles de Verificador; `CaseAssignmentService` y `VerifierProfileContextFacade`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `5be2825` | feat(assessment-infrastructure): agrega persistencia JPA, converters y repositorios del BC | Persistencia JPA de `AssessmentAttempt`, `VerificationCase` y `VerifierProfile`. | 2026-10-08 |
| SkillSwap-WebServices-Java | refactor/remove-coordinator-role | `52ec296` | refactor(learning-path): leer el learning path solo como dueño | La ruta solo la consulta su dueño; se eliminan las clases de semilla de la cuenta Coordinator. | 2026-10-08 |
| SkillSwap-WebServices-Java | refactor/remove-coordinator-role | `501df84` | refactor(credential): acceso a certificados solo para el dueño | El listado y el detalle de certificados quedan restringidos a su dueño. | 2026-10-08 |
| SkillSwap-WebServices-Java | refactor/remove-coordinator-role | `de8709b` | refactor(iam): eliminar el rol Coordinator y su seed, Student es el único rol | `UserRole` queda solo con `Student`; el Verificador es un perfil adicional del Estudiante. | 2026-10-08 |
| SkillSwap-WebServices-Java | develop | `e65c51d` | Merge pull request #4 from Aplicaciones-Dispositivos-Moviles/refactor/remove-coordinator-role | Integración de `refactor/remove-coordinator-role` a `develop`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `48cdc39` | feat(assessment-peer-review): dominio y aplicación de la apelación de casos | `AppealVerificationCaseCommand`: el caso rechazado se reabre y se asigna a otro Verificador. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `ebfa3f3` | feat(assessment-peer-review): endpoints REST de intentos, casos de verificación, apelación y perfil de verificador | `AssessmentAttemptsController`, `VerificationCasesController` (incluye `POST /{id}/appeal`) y `VerifierProfilesController`. | 2026-10-08 |
| SkillSwap-WebServices-Java | develop | `d827cfd` | Merge pull request #5 from Aplicaciones-Dispositivos-Moviles/feature/assessment-peer-review | Integración de `feature/assessment-peer-review` a `develop`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `37978e0` | feat(assessment-peer-review): publicar el verificador revertido en VerificationCaseResolved | El evento `VerificationCaseResolved` informa qué Verificador fue revertido por una apelación. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `18dc046` | feat(reputation): dominio de confiabilidad del verificador y empleabilidad del estudiante | Agregados `VerifierReliability` y `StudentEmployabilityScore` con sus calculadoras. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `5e0ff30` | feat(reputation): servicios de aplicación y handlers de eventos de reputación | `ReputationCommandService`, servicios de consulta y handlers de `AssessmentAttemptPassed` y `VerificationCaseResolved`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `5e5cb77` | feat(reputation): persistencia JPA y cableado de eventos de reputación | Persistencia JPA y suscripción de los handlers a los eventos de dominio. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `628a9a7` | feat(reputation): endpoints REST de empleabilidad y confiabilidad | `VerifierReliabilitiesController` y `StudentEmployabilityScoresController`. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `3b8a601` | Merge pull request #6 from Aplicaciones-Dispositivos-Moviles/feature/reputation | Integración de `feature/reputation` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `44ab707` | feat(recognition-incentives): dominio de wallet, créditos y canje | Agregado `Wallet`, entidad `CreditTransaction`, Value Objects `Credits` y `RedemptionItem`, servicio `RedemptionPricing`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `e1d2dca` | feat(recognition-incentives): servicios de aplicación y handlers de eventos de billetera | Servicios de billetera y handlers que crean la wallet y acreditan SkillCredits al Verificador. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `e7b63c5` | feat(recognition-incentives): persistencia JPA, bloqueo de wallet y cableado de eventos | Persistencia JPA con bloqueo de la wallet al actualizar el saldo. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `6b4db93` | feat(recognition-incentives): endpoints REST de billetera y canje de beneficios | `WalletsController` y `CreditTransactionsController` (`POST /redeem`). | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `db593a1` | Merge pull request #7 from Aplicaciones-Dispositivos-Moviles/feature/recognition-incentives | Integración de `feature/recognition-incentives` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/deploy-render | `a4a1d8a` | chore(deploy): Dockerfile y guía de despliegue en Render | `Dockerfile` multi-etapa (Maven + JRE 21), `.dockerignore` y guía `docs/deploy-render.md`. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `823c58b` | Merge pull request #8 from Aplicaciones-Dispositivos-Moviles/chore/deploy-render | Integración de `chore/deploy-render` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger | `fba59d8` | feat(docs): documentación Swagger con autenticación JWT | `OpenApiConfig` con el esquema `bearerAuth` y `RootController`, que redirige `/` y `/swagger` a Swagger UI. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `61db21a` | Merge pull request #9 from Aplicaciones-Dispositivos-Moviles/chore/swagger | Integración de `chore/swagger` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger-tags | `c307b2a` | chore(swagger): group endpoints under readable names and descriptions | `OpenApiTagsConfig`, que agrupa los endpoints de Swagger UI por Bounded Context con nombres y descripciones legibles. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `654b9a7` | Merge pull request #10 from Aplicaciones-Dispositivos-Moviles/chore/swagger-tags | Integración de `chore/swagger-tags` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/flyway-migrations | `a23ed44` | chore(db): migraciones versionadas con Flyway y esquema base V1 | Dependencias de Flyway, `V1__baseline_schema.sql` con el esquema existente, `baseline-on-migrate` para la base de Render y pruebas de integración con el esquema de Flyway. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `5a75d49` | Merge pull request #11 from Aplicaciones-Dispositivos-Moviles/chore/flyway-migrations | Integración de `chore/flyway-migrations` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/verification-case-type | `7daa868` | feat(assessment-peer-review): tipo de caso de verificación y recompensas por tipo | `CaseType` (`Quiz`, `MiniProject`) en `VerificationCase`, 40 y 25 SkillCredits por tipo de caso, precios de canje de 200 y 120 y migración V2. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `512dcd3` | Merge pull request #12 from Aplicaciones-Dispositivos-Moviles/feature/verification-case-type | Integración de `feature/verification-case-type` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/subscription-billing | `03c29cd` | feat(subscription-billing): suscripción mensual con RevenueCat y límites por plan | Bounded Context Subscription & Billing: agregado `Subscription`, `PaymentGateway` con RevenueCat y adaptador simulado, endpoints de suscripción, webhook idempotente, revisión periódica de vencimientos y migración V3. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `20daffc` | Merge pull request #13 from Aplicaciones-Dispositivos-Moviles/feature/subscription-billing | Integración de `feature/subscription-billing` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/plan-limits-enforcement | `7e86af6` | feat(plan-limits): límites del plan en rutas de aprendizaje y escalamientos | Estado `Paused`, pausa y reanudación de rutas, `PlanLimitReached`, bloqueo por estudiante, cupo mensual de escalamientos, `review_due_at` y migraciones V4 y V5. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `68e3161` | Merge pull request #14 from Aplicaciones-Dispositivos-Moviles/feature/plan-limits-enforcement | Integración de `feature/plan-limits-enforcement` a `develop`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `e778439` | feat(iam): verificación del correo institucional con Brevo | Enlace de verificación de un solo uso (solo se guarda su SHA-256), `403 EmailNotVerified` con reenvío, endpoints `verify-email` y `resend-verification`, puerto `EmailSender` con Brevo y migración V6. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `3f7ec24` | feat(notifications): notificaciones push con Firebase Cloud Messaging | Endpoints del token del dispositivo, puerto `PushNotificationSender` con Firebase, `UserNotificationsContextFacade` y notificación de la resolución de un certificado (US16). | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `a7cd7ce` | feat(iam): perfil de intereses con vector de habilidades | `PUT /api/v1/users/{id}/interests`, vector de habilidades calculado con el catálogo interno y migración V7. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/learning-path-gemini-matcher | `bebe9d8` | feat(credential-verification): evento CertificateVerified y certificados como evidencia para Learning Path Engine | Evento `CertificateVerified` y consultas de certificados validados y de su contenido en `CredentialContextFacade`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/learning-path-gemini-matcher | `ec51fa9` | feat(learning-path): meta interpretada con Gemini, certificados validados y quiz sin preguntas repetidas | `GeminiSkillTaxonomyMatcher` con respaldo por palabras clave y `GeminiClient` compartido, nodos completados por certificados validados (V8), `POST /api/v1/path-nodes/{nodeId}/certificate` y exclusión de preguntas repetidas. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `4babdcd` | feat(moderation-disputes): escalamiento de certificados sospechosos a un Verificador senior | Titular distinto del nombre registrado y archivo de otro estudiante como certificado sospechoso, Bounded Context Moderation & Disputes con asignación a un Verificador senior y endpoints de disputas. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `7175877` | feat(learning-path-engine): ruta avanzada canjeada con SkillCredits fuera de los límites del plan | `AdvancedPathUnlock` otorgado por el canje, ruta avanzada excluida de los límites del plan y `GET /api/v1/advanced-path-unlocks`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `ac2e271` | feat(assessment-peer-review): plazo de revisión por plan y reasignación de casos vencidos | `ReviewDeadlinePolicy` definida por un Verificador senior, `OverdueCaseReassignmentScheduler` y descuento de 5 puntos de confiabilidad por plazo incumplido. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `acbf0a5` | chore(merge): integrate IAM email verification, push notifications and interests | Merge de la rama de la funcionalidad en `feature/complete-acceptance-scenarios`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `b1b23b3` | chore(merge): integrate Learning Path Gemini matcher and CertificateVerified event | Merge de la rama de la funcionalidad en `feature/complete-acceptance-scenarios`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `b194d42` | chore(merge): integrate certificate escalation, disputes and review deadlines | Merge de la rama de la funcionalidad en `feature/complete-acceptance-scenarios`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `56f5a13` | refactor(moderation-disputes): rename coordinatorNotes to resolutionNotes | Las observaciones de la resolución de una disputa pasan a llamarse `resolutionNotes` (columna `resolution_notes`). | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `c95372b` | chore(db): renumber escalation and advanced path migrations to V9 and V10 | Las migraciones quedan numeradas de forma contigua de V1 a V10. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `8cb3afc` | test(moderation-disputes): end-to-end resolution of a certificate dispute | `CertificateDisputeResolutionFlowIntegrationTest`: la resolución de una disputa verifica o rechaza el certificado, notifica al estudiante y completa el nodo cubierto. | 2026-10-09 |
| SkillSwap-WebServices-Java | develop | `521486c` | Merge pull request #15 from Aplicaciones-Dispositivos-Moviles/feature/complete-acceptance-scenarios | Integración de `feature/complete-acceptance-scenarios` a `develop`. | 2026-10-09 |

*Nota.* Commits del repositorio [`SkillSwap-WebServices-Java`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices-Java): de `04eb1ce` a `654b9a7` (PR #1 a #10), de Alberca Saavedra, Víctor Manuel (`Agnizzz`); de `a23ed44` a `521486c` (PR #11 a #15), de Sulca Sánchez, Piero Angel (`psulca`). La columna *Commit Message Body* resume el contenido de cada commit. Elaboración propia.

El Landing Page se implementó en el repositorio `SkillSwap-LandingPage` y se publicó en GitHub Pages; su desarrollo (tareas T18 y T19) se integró mediante los Pull Requests #1 a #8, y GitHub Pages publica el sitio desde `main`.

**Tabla 20**

*Commits de desarrollo del Landing Page*

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| SkillSwap-LandingPage | main | `3a25955` | Initial commit | Creación del repositorio con su `README.md`. | 2026-08-31 |
| SkillSwap-LandingPage | feature/initial-landing-setup | `5701364` | feat: add initial landing page project files | Página principal (`index.html`), páginas Sobre nosotros, Alianzas, Registro e Inicio de sesión, hojas de estilo, imágenes y video del Landing Page. | 2026-09-18 |
| SkillSwap-LandingPage | main | `f10d4b3` | Merge pull request #1 from Aplicaciones-Dispositivos-Moviles/feature/initial-landing-setup | Integración del Landing Page inicial a `main`. | 2026-09-18 |
| SkillSwap-LandingPage | feature/fix-pages-structure | `26ac21f` | fix: move public content to root for github pages | Mueve el contenido de `public/` a la raíz del repositorio para que GitHub Pages sirva el sitio. | 2026-09-18 |
| SkillSwap-LandingPage | main | `c98fd9a` | Merge pull request #2 from Aplicaciones-Dispositivos-Moviles/feature/fix-pages-structure | Integración de la corrección de estructura, publicada en GitHub Pages. | 2026-09-18 |
| SkillSwap-LandingPage | feature/victor/add-landing-images | `1bded7f` | feat(landing): add images and improve responsive design | Imágenes del Landing Page y mejoras del diseño responsive. | 2026-10-09 |
| SkillSwap-LandingPage | develop | `d9ff904` | Merge pull request #3 from Aplicaciones-Dispositivos-Moviles/feature/victor/add-landing-images | Integración de las imágenes y el diseño responsive a `develop`. | 2026-10-09 |
| SkillSwap-LandingPage | main | `135f997` | Merge pull request #4 from Aplicaciones-Dispositivos-Moviles/develop | Publicación de `develop` en `main` (GitHub Pages). | 2026-10-09 |
| SkillSwap-LandingPage | fix/replace-coordinator-with-verifier | `767a8cd` | fix(landing): replace coordinator with verifier | Reemplaza el rol de Coordinador por el de Verificador en el contenido del sitio. | 2026-10-09 |
| SkillSwap-LandingPage | develop | `abbcfd6` | Merge pull request #5 from Aplicaciones-Dispositivos-Moviles/fix/replace-coordinator-with-verifier | Integración de la corrección de roles a `develop`. | 2026-10-09 |
| SkillSwap-LandingPage | main | `6940188` | Merge pull request #6 from Aplicaciones-Dispositivos-Moviles/develop | Publicación de `develop` en `main` (GitHub Pages). | 2026-10-09 |
| SkillSwap-LandingPage | feature/pricing-section | `b19922f` | feat(landing): add freemium pricing section and drop coordinator role | Sección de planes y precios del modelo freemium (plan gratuito y suscripción mensual). | 2026-10-09 |
| SkillSwap-LandingPage | feature/pricing-section | `6a0712b` | feat(landing): add optimized app screens in webp | Pantallas de la aplicación optimizadas en formato WebP. | 2026-10-09 |
| SkillSwap-LandingPage | feature/pricing-section | `098e2ab` | feat(landing): add app download CTA and how-it-works flow | Llamado a la acción "Descarga la app", flujo "Cómo funciona" en 5 pasos y preguntas frecuentes sobre la disponibilidad. | 2026-10-09 |
| SkillSwap-LandingPage | develop | `6f672f0` | Merge pull request #7 from Aplicaciones-Dispositivos-Moviles/feature/pricing-section | Integración de la sección de precios y el CTA de descarga a `develop`. | 2026-10-09 |
| SkillSwap-LandingPage | main | `0674faf` | Merge pull request #8 from Aplicaciones-Dispositivos-Moviles/develop | Publicación de `develop` en `main` (GitHub Pages). | 2026-10-09 |

*Nota.* Commits del repositorio [`SkillSwap-LandingPage`](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-LandingPage): de `3a25955` a `6940188` (PR #1 a #6), de Alberca Saavedra, Víctor Manuel (`Agnizzz`); de `b19922f` a `0674faf` (PR #7 y #8), de Sulca Sánchez, Piero Angel (`psulca`). Elaboración propia.


#### 4.2.1.5. Testing Suite Evidence for Sprint Review

El backend se valida con dos niveles de pruebas automatizadas, ubicadas en `src/test/java/com/innovify/skillswap/` y organizadas por Bounded Context y por capa, igual que el código de producción:

- **Pruebas unitarias** de dominio y de aplicación con **JUnit 5** (incluidas pruebas parametrizadas con `@ParameterizedTest`) y **AssertJ**. Las pruebas de la capa de aplicación usan dobles de prueba escritos a mano (`FakeCertificateRepository`, `FakeDomainEventPublisher`, `FakeFileStorageService`, entre otros) en lugar de una librería de mocks.
- **Pruebas de integración** con **Spring Boot Test** y **MockMvc** (con Spring Security Test), que levantan la aplicación completa y ejercitan la API REST con el filtro de seguridad, los servicios reales, BCrypt, JWT y una base **PostgreSQL 16** real creada por **Testcontainers** (imagen `postgres:16-alpine`). Estas pruebas heredan de `PostgresIntegrationTest`, crean el esquema con las mismas migraciones de Flyway que producción y Hibernate solo lo valida; los servicios externos (Cloudinary, Gemini, RevenueCat, Brevo y Firebase Cloud Messaging) se reemplazan por dobles en memoria o por un servidor falso local, como `FakeGeminiServer`. Si Docker no está disponible, se omiten automáticamente (`DockerAvailableCondition`).

Todas las dependencias de prueba están declaradas en el `pom.xml` del repositorio (`spring-boot-starter-test`, los starters de prueba de Data JPA, Security, Validation y Web MVC, y `testcontainers-postgresql`). En la rama `develop`, que integra el trabajo del Sprint 1 tras el merge del PR #15, el repositorio contiene 158 clases de prueba con 1575 métodos de prueba (`@Test` y `@ParameterizedTest`), de las cuales 29 son pruebas de integración contra PostgreSQL, y la suite completa ejecuta 1978 pruebas sin fallos. Las pruebas se ejecutan con `./mvnw test` antes de cada push; la imagen Docker no las ejecuta porque requieren Docker.

Los criterios de aceptación de las historias del Sprint 1 se automatizan como pruebas de integración de la API con JUnit 5, MockMvc y Testcontainers; en las de Credential Verification y Learning Path Engine, cada método lleva en `@DisplayName` el nombre del escenario de aceptación que verifica.

**Tabla 21**

*Pruebas de integración de la API y su trazabilidad con el Product Backlog*

| Bounded Context | Clase de prueba | Historias | Comportamiento que valida |
|---|---|---|---|
| Identity & Access | `AuthenticationFlowIntegrationTest`, `SecurityIntegrationTest` | US01, US02, US04, TS01, TS02 | Registro con correo `.edu.pe`, inicio de sesión con JWT, perfil propio y público, actualización de la biografía; acceso a `/health` sin token y rechazo (401) de tokens ausentes, inválidos o de usuarios inexistentes |
| Credential Verification | `CertificatesApiIntegrationTest` | US12, US14, US16, TS03, TS04 | Carga en JPEG, PNG y PDF (estado `Unverified`), rechazo de formatos no permitidos (415), de archivos de más de 10 MB (413) y de solicitudes sin archivo (400), duplicados (409), nivel de riesgo y acceso exclusivo del dueño |
| Learning Path Engine | `LearningPathApiIntegrationTest` | US06, US08, US17, TS05, TS06 | Declaración de la meta, una sola ruta activa, consulta de la ruta propia, generación de la evaluación de un nodo disponible con preguntas nuevas en cada intento, rechazo de nodos bloqueados y conservación del estado si la IA no está disponible |
| Assessment & Peer Review | `AssessmentPeerReviewApiIntegrationTest` | US18, US22, US23, US24, US25, US26, US27, TS07, TS08 | Calificación del intento, apertura y asignación del caso, perfil y disponibilidad del Verificador, revisión sin exponer las respuestas correctas, decisión, evidencia y apelación ante otro Verificador |
| Reputation | `ReputationApiIntegrationTest` | TS11 | Employability Score tras una aprobación o un rechazo y confiabilidad del Verificador, incluido el descuento cuando su decisión se revierte por apelación |
| Recognition & Incentives | `RecognitionIncentivesApiIntegrationTest` | US30, US31, US32, TS09 | Acreditación de SkillCredits al resolver un caso (apruebe o rechace), billetera vacía al registrarse, historial de movimientos y canje con saldo suficiente o insuficiente (409) |
| Identity & Access | `EmailVerificationIntegrationTest` | US01, US02 | Envío del enlace de verificación al registrarse, verificación con el token, reenvío con intervalo de espera y rechazo (403 `EmailNotVerified`) del inicio de sesión de una cuenta sin verificar |
| Credential Verification | `CertificateNotificationsIntegrationTest` | US16 | Notificación push al quedar un certificado verificado o rechazado, con el motivo del rechazo, y ausencia de notificación sin token de dispositivo |
| Learning Path Engine | `GoalInterpretationApiIntegrationTest`, `CertificateEvidenceApiIntegrationTest`, `PlanLimitsEnforcementIntegrationTest`, `AdvancedPathUnlockIntegrationTest` | US05, US06, US09, US15, US17, TS05 | Meta interpretada por Gemini con respaldo por palabras clave, nodos completados por certificados validados, correspondencia del certificado con el nodo (umbral 0,7), límites de rutas del plan y ruta avanzada fuera de esos límites |
| Assessment & Peer Review | `ReviewDeadlinesIntegrationTest` | US39 | Definición del plazo de cada plan por un Verificador senior (403 si no lo es) y reasignación de un caso vencido con descuento de confiabilidad |
| Subscription & Billing | `SubscriptionBillingApiIntegrationTest` | US05 | Activación de la suscripción a partir del estado de RevenueCat, webhook idempotente (un mismo evento se aplica una vez), vencimiento que devuelve al plan gratuito, cancelación que conserva el plan mensual hasta el fin del periodo y consulta del plan con sus límites |
| Moderation & Disputes | `CertificateEscalationApiIntegrationTest`, `CertificateDisputeResolutionFlowIntegrationTest` | US13, US14, US34, US35, TS10 | Escalamiento del certificado con titular distinto o archivo de otro estudiante a un Verificador senior, consulta de disputas y evidencia, observaciones obligatorias y resolución que verifica o rechaza el certificado |
| Shared | `ApiDocumentationIntegrationTest` | TS12 | Redirección de la raíz a Swagger UI, documento OpenAPI accesible sin token y endpoints de la API protegidos |

*Nota.* Elaboración propia a partir de las clases de prueba del repositorio `SkillSwap-WebServices-Java`.

**Código de las pruebas (selección representativa)**

*Identity & Access — `EmailTest` (prueba unitaria de dominio).* Valida el Value Object `Email`: acepta solo correos institucionales `.edu.pe`, los normaliza y rechaza cualquier otro formato con una `DomainException`.

```java
class EmailTest {

    @ParameterizedTest
    @ValueSource(strings = {"ana@upc.edu.pe", "ana.perez@pucp.edu.pe", "u202012345@upc.edu.pe"})
    void constructor_withInstitutionalEmail_createsEmail(String value) {
        assertThat(new Email(value).value()).isEqualTo(value);
    }

    @Test
    void constructor_normalizesToLowercaseAndTrims() {
        assertThat(new Email("  Ana@UPC.EDU.PE ").value()).isEqualTo("ana@upc.edu.pe");
    }

    @ParameterizedTest
    @ValueSource(strings = {"", "   ", "ana@gmail.com", "ana@upc.edu", "ana@edu.pe",
            "ana@upc.edu.pe.com", "ana upc@upc.edu.pe", "upc.edu.pe"})
    void constructor_withInvalidEmail_throwsDomainException(String value) {
        assertThatThrownBy(() -> new Email(value)).isInstanceOf(DomainException.class);
    }
}
```

*Credential Verification — `CertificatesApiIntegrationTest` (prueba de integración, US12).* Ejercita `POST /api/v1/certificates` contra PostgreSQL real; cada método lleva el nombre del escenario de aceptación.

```java
@DisplayName("Upload a file in an accepted format")
@ParameterizedTest
@ValueSource(strings = {"JPEG", "PNG", "PDF"})
void uploadInAnAcceptedFormat_returns201Unverified(String format) throws Exception {
    MvcResult result = switch (format) {
        case "JPEG" -> upload(anaToken, jpeg("format-jpeg"), "image/jpeg", Map.of());
        case "PNG" -> upload(anaToken, png("format-png"), "image/png", Map.of());
        default -> upload(anaToken, pdf("format-pdf"), "application/pdf", Map.of());
    };

    assertThat(result.getResponse().getStatus()).isEqualTo(201);
    assertThat(field(result, "$.status")).isEqualTo("Unverified");
}

@Test
@DisplayName("Reject a file in a format that is not allowed")
void uploadOfATextFile_returns415WithTheMessage() throws Exception {
    MvcResult result = upload(anaToken, "plain text".getBytes(StandardCharsets.UTF_8), "text/plain", Map.of());

    assertThat(result.getResponse().getStatus()).isEqualTo(415);
    assertThat(field(result, "$.title")).isEqualTo("InvalidFileType");
    assertThat(field(result, "$.detail")).isEqualTo("Only JPG, PNG and PDF files are accepted.");
}
```

*Assessment & Peer Review — `AssessmentPeerReviewApiIntegrationTest` (prueba de integración, US25 y US27).* Recorre el ciclo completo de una apelación: el caso rechazado por un Verificador se reasigna a otro, el primero deja de tener acceso y la aprobación del segundo completa el nodo del estudiante.

```java
@Test
void appeal_goesToAnotherVerifierWhoseApprovalCompletesTheNode() throws Exception {
    enroll(bob, bobToken);
    enroll(carla, carlaToken);
    int caseId = failAssessment(ana, anaToken);
    assertThat(status(decide(bobToken, caseId, "Rejected", "Needs work."))).isEqualTo(200);

    MvcResult appealed = appeal(anaToken, caseId);

    assertThat(status(appealed)).as(body(appealed)).isEqualTo(200);
    assertThat((String) read(appealed, "$.status")).isEqualTo("Assigned");
    assertThat((int) read(appealed, "$.verifierUserId")).isEqualTo(carla.getId());
    assertThat((int) read(appealed, "$.appealCount")).isEqualTo(1);

    // The first verifier is no longer a party of the case, and cannot decide it again.
    assertThat(status(getCase(bobToken, caseId))).isEqualTo(403);
    assertThat(status(decide(bobToken, caseId, "Approved", "Second thoughts."))).isEqualTo(403);

    MvcResult resolved = decide(carlaToken, caseId, "Approved", "It does meet the rubric.");
    assertThat(status(resolved)).isEqualTo(200);
    assertThat(nodeStatus(ana, anaToken)).isEqualTo("Completed");
}
```

*Las 158 clases de prueba completas se encuentran en el repositorio del backend, dentro de `src/test/java/com/innovify/skillswap/<bounded-context>/`.*

**Tabla 22**

*Pruebas unitarias y de integración por Bounded Context y capa*

| Bounded Context | Capa | Clases de prueba | Clases y comportamientos que cubren |
|---|---|---|---|
| Identity & Access | Domain | `UserTest`, `EmailTest`, `UsernameTest`, `PasswordHashTest`, `UserRoleTest`, `DefaultEmailDomainValidatorTest`, `IamErrorTest` | Agregado `User`, Value Objects (dominio `.edu.pe`, longitud de usuario y contraseña) y rol `Student` |
| Identity & Access | Application / Infrastructure / Interface | `UserCommandServiceImplTest`, `UserQueryServiceImplTest`, `IamMessagesTest`, `BCryptPasswordHasherTest`, `JwtTokenGeneratorTest`, `JwtAuthenticationFilterTest`, `UserPersistenceTest`, `SecurityIntegrationTest`, `AuthenticationControllerTest`, `UsersControllerTest`, `IamRestTest`, `AuthenticationFlowIntegrationTest` | Registro y autenticación, mensajes en inglés y es-419, hash de contraseñas, emisión y validación de JWT, persistencia, seguridad y endpoints REST |
| Credential Verification | Domain | `CertificateTest`, `RiskAssessmentTest`, `DefaultCertificateRiskScorerTest`, `VerificationEnumsTest`, `CredentialVerificationErrorTest` | Agregado `Certificate` y cálculo del nivel de riesgo |
| Credential Verification | Application / Infrastructure / Interface | `CertificateCommandServiceImplTest`, `CertificateQueryServiceImplTest`, `CredentialContextFacadeImplTest`, `CredentialVerificationMessagesTest`, `CloudinarySettingsTest`, `CloudinaryStorageServiceTest`, `CertificateConvertersTest`, `CertificatePersistenceTest`, `CertificatesControllerTest`, `CertificatesApiIntegrationTest` | Subida y consulta de certificados, facade para otros contextos, almacenamiento en Cloudinary, persistencia y endpoints |
| Learning Path Engine | Domain | `LearningPathTest`, `LearningPathBuilderTest`, `SkillGapAnalyzerTest`, `CareerGoalAndSkillGapTest`, `QuestionAndBlueprintTest`, `LearningPathErrorTest` | Agregados `LearningPath` y `AssessmentBlueprint` y análisis de brecha de habilidades |
| Learning Path Engine | Application / Infrastructure / Interface | `LearningPathCommandServiceImplTest`, `LearningPathQueryServicesTest`, `AssessmentBlueprintCommandServiceImplTest`, `LearningPathContextFacadeImplTest`, `LearningPathMessagesTest`, `GeminiQuestionGeneratorTest`, `GeminiSettingsTest`, `SkillCatalogTest`, `SkillTaxonomyTest`, `LearningPathConvertersTest`, `LearningPathPersistenceTest`, `LearningPathServicesIntegrationTest`, `LearningPathActionResultAssemblerTest`, `LearningPathResourceAssemblersTest`, `LearningPathApiIntegrationTest` | Declaración de meta, generación de evaluaciones con Gemini y modelos de respaldo, catálogo de 55 habilidades, persistencia y endpoints |
| Assessment & Peer Review | Domain | `AssessmentAttemptTest`, `ScoreTest`, `ReviewDecisionTest`, `VerificationCaseTest`, `VerifierMatcherTest`, `VerifierProfileTest` | Regla de aprobación, ciclo del caso (asignación, decisión y apelación) y emparejamiento de Verificador |
| Assessment & Peer Review | Application / Infrastructure / Interface | `AssessmentAttemptCommandServiceImplTest`, `CaseAssignmentServiceImplTest`, `VerificationCaseCommandServiceImplTest`, `VerifierProfileCommandServiceImplTest`, `VerifierProfileContextFacadeImplTest`, `QueryServicesImplTest`, `AssessmentPeerReviewMessagesTest`, `AssessmentPeerReviewConvertersTest`, `AssessmentPeerReviewPersistenceTest`, `AssessmentPeerReviewServicesIntegrationTest`, `AssessmentPeerReviewActionResultAssemblerTest`, `AssessmentPeerReviewResourceAssemblersTest`, `AssessmentPeerReviewApiIntegrationTest` | Intentos, asignación, resolución y apelación de casos, persistencia y endpoints REST |
| Reputation | Domain | `VerifierReliabilityTest`, `StudentEmployabilityScoreTest`, `ReputationCalculatorsTest`, `ScoreValueObjectsTest` | Agregados de reputación y calculadoras de confiabilidad y empleabilidad |
| Reputation | Application / Infrastructure / Interface | `ReputationCommandServiceImplTest`, `ReputationQueryServicesImplTest`, `ReputationEventHandlersTest`, `ReputationMessagesTest`, `ReputationEventWiringTest`, `ReputationPersistenceTest`, `ReputationActionResultAssemblerTest`, `ReputationResourceAssemblersTest`, `ReputationApiIntegrationTest` | Reacción a eventos de dominio, persistencia y endpoints |
| Recognition & Incentives | Domain | `WalletTest`, `CreditTransactionTest`, `CreditsTest`, `RecognitionIncentivesServicesTest` | Agregado `Wallet`, movimientos y precios de canje (200 y 120 SkillCredits) |
| Recognition & Incentives | Application / Infrastructure / Interface | `WalletCommandServiceImplTest`, `WalletQueryServiceImplTest`, `RecognitionIncentivesEventHandlersTest`, `RecognitionIncentivesMessagesTest`, `RecognitionIncentivesEventWiringTest`, `RecognitionIncentivesPersistenceTest`, `RecognitionIncentivesActionResultAssemblerTest`, `RecognitionIncentivesResourceAssemblersTest`, `RecognitionIncentivesApiIntegrationTest` | Acreditación por eventos, canje, persistencia y endpoints |
| Identity & Access | Application / Infrastructure / Interface | `SendVerificationEmailEventHandlerTest`, `EmailVerificationCommandServiceImplTest`, `EmailVerificationIssuerTest`, `VerificationEmailComposerTest`, `IamConfigTest`, `BrevoEmailSenderAdapterTest`, `EmailSettingsTest`, `EmailVerificationIntegrationTest`, `UserNotificationsContextFacadeImplTest`, `FirebasePushNotificationAdapterTest` | Verificación del correo institucional, envío con Brevo y su respaldo en el log, notificaciones push con Firebase Cloud Messaging |
| Credential Verification | Domain / Application / Integration | `HolderNameMatcherTest`, `NotifyCertificateResolutionEventHandlerTest`, `CertificateNotificationsIntegrationTest` | Comparación del titular con el nombre registrado y notificación de la resolución del certificado |
| Learning Path Engine | Domain / Application / Infrastructure / Interface | `GeminiSkillTaxonomyMatcherTest`, `SkillTaxonomyMatcherWiringTest`, `GoalInterpretationApiIntegrationTest`, `CertificateRecognitionTest`, `LearningPathCertificateCommandsTest`, `KeywordCertificateSkillAffinityScorerTest`, `CertificateEvidenceApiIntegrationTest`, `AssessmentRetakeAndCertificateConditionTest`, `SkillCatalogContextFacadeImplTest`, `AdvancedPathUnlockTest`, `AdvancedPathUnlockIntegrationTest`, `PlanLimitsEnforcementIntegrationTest` | Interpretación de la meta con Gemini y respaldo por palabras clave, certificados validados y su correspondencia con el nodo, nuevos intentos sin preguntas repetidas, ruta avanzada y límites del plan |
| Assessment & Peer Review | Domain / Application / Integration | `ReviewDeadlineTest`, `ReviewDeadlinePolicyTest`, `ReviewDeadlinePolicyCommandServiceImplTest`, `ReviewDeadlinesIntegrationTest` | Plazo de revisión por plan, definición por un Verificador senior y reasignación de casos vencidos |
| Reputation | Domain / Application | `SeniorVerifierPolicyTest`, `ReputationContextFacadeImplTest` | Criterio del Verificador senior (rango Oro y confiabilidad de al menos 90) |
| Subscription & Billing | Domain / Application / Infrastructure / Interface | `SubscriptionTest`, `BillingValueObjectsTest`, `SubscriptionCommandServiceImplTest`, `SubscriptionQueryServiceImplTest`, `SubscriptionBillingMessagesTest`, `RevenueCatGatewayAdapterTest`, `RevenueCatWebhookAuthorizationTest`, `SimulatedPaymentGatewayAdapterTest`, `SubscriptionBillingPersistenceTest`, `SubscriptionBillingActionResultAssemblerTest`, `SubscriptionBillingApiIntegrationTest` | Agregado `Subscription`, verificación de compras con RevenueCat, webhook idempotente, vencimiento y endpoints |
| Moderation & Disputes | Domain / Application / Integration | `DisputeTest`, `DisputeReviewerSelectorTest`, `DisputeCommandServiceImplTest`, `ModerationDisputesMessagesTest`, `CertificateEscalationApiIntegrationTest`, `CertificateDisputeResolutionFlowIntegrationTest` | Agregado `Dispute`, selección del revisor, escalamiento y resolución de certificados sospechosos de principio a fin |
| Shared | — | `ResultTest`, `ErrorCodesTest`, `CorsPropertiesTest`, `SpringDomainEventPublisherTest`, `LatinAmericanSpanishLocaleResolverTest`, `JsonTest`, `DatabaseDefaultsTest`, `PostgresUrlConverterTest`, `HealthControllerTest`, `RootControllerTest`, `ApiDocumentationIntegrationTest` | Tipo `Result`, CORS, publicador de eventos, idioma es-419, conversión de `DATABASE_URL`, health check y documentación OpenAPI |

*Nota.* La tabla corresponde a la rama `develop`, que integra el trabajo del Sprint 1; las filas que siguen a las de cada Bounded Context original agrupan las clases de prueba agregadas en los PR #11 a #14 y en las ramas `feature/iam-email-verification-push`, `feature/learning-path-gemini-matcher` y `feature/certificate-escalation-and-deadlines`. Elaboración propia.

**Tabla 23**

*Commits del Sprint 1 que incorporan pruebas automatizadas*

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| SkillSwap-WebServices-Java | feature/iam-identity-access | `09f0027` | chore(shared): agrega Result, eventos de dominio, i18n, CORS, health y conversión de DATABASE_URL | `ResultTest`, `CorsPropertiesTest`, `SpringDomainEventPublisherTest`, `LatinAmericanSpanishLocaleResolverTest`, `DatabaseDefaultsTest`, `PostgresUrlConverterTest`, `HealthControllerTest`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `8618574` | feat(iam-domain): agrega User, value objects, commands, queries y servicios de dominio | `UserTest`, `EmailTest`, `UsernameTest`, `PasswordHashTest`, `UserRoleTest`, `DefaultEmailDomainValidatorTest`, `IamErrorTest`, `ErrorCodesTest`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `88de188` | feat(iam-application): implementa UserCommandService y UserQueryService con mensajes en inglés y es-419 | `UserCommandServiceImplTest`, `UserQueryServiceImplTest`, `IamMessagesTest`. | 2026-10-07 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `9237915` | feat(iam-infrastructure): agrega persistencia JPA, BCrypt, JWT, seguridad stateless y seeder del coordinador | `BCryptPasswordHasherTest`, `JwtTokenGeneratorTest`, `JwtAuthenticationFilterTest`, `UserPersistenceTest`, `SecurityIntegrationTest` y la base `PostgresIntegrationTest` con Testcontainers (además de las pruebas del seeder, retiradas en `52ec296`). | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/iam-identity-access | `b8c0c0a` | feat(iam-interfaces): agrega AuthenticationController, UsersController, resources y manejo de errores ProblemDetail | `AuthenticationControllerTest`, `UsersControllerTest`, `IamRestTest`, `AuthenticationFlowIntegrationTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `ed0c022` | feat(credential-domain): agrega agregado Certificate, evaluación de riesgo y puertos de dominio | `CertificateTest`, `RiskAssessmentTest`, `DefaultCertificateRiskScorerTest`, `VerificationEnumsTest`, `CredentialVerificationErrorTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `e140823` | feat(credential-application): implementa servicios de comando y consulta, facade y mensajes de verificación de certificados | `CertificateCommandServiceImplTest`, `CertificateQueryServiceImplTest`, `CredentialContextFacadeImplTest`, `CredentialVerificationMessagesTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `5a0bc00` | feat(credential-infrastructure): agrega persistencia JPA, conversores y almacenamiento en Cloudinary vía REST | `CloudinarySettingsTest`, `CloudinaryStorageServiceTest`, `CertificateConvertersTest`, `CertificatePersistenceTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `7501882` | feat(credential-interfaces): expone endpoints REST de certificados con carga multipart y manejo de errores | `CertificatesControllerTest`, `CertificatesApiIntegrationTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `dab0945` | feat(learning-path-domain): agrega agregados, value objects y servicios de dominio de la ruta de aprendizaje | `LearningPathTest`, `LearningPathBuilderTest`, `SkillGapAnalyzerTest`, `CareerGoalAndSkillGapTest`, `QuestionAndBlueprintTest`, `LearningPathErrorTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `73f6dd3` | feat(learning-path-application): agrega servicios de comando y consulta, fachada ACL y mensajes de la ruta de aprendizaje | `LearningPathCommandServiceImplTest`, `LearningPathQueryServicesTest`, `AssessmentBlueprintCommandServiceImplTest`, `LearningPathContextFacadeImplTest`, `LearningPathMessagesTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `db58943` | feat(learning-path-infrastructure): agrega persistencia JPA, catalogo de skills, matcher y generador Gemini | `GeminiQuestionGeneratorTest`, `GeminiSettingsTest`, `SkillCatalogTest`, `SkillTaxonomyTest`, `LearningPathConvertersTest`, `LearningPathPersistenceTest`, `LearningPathServicesIntegrationTest`, `JsonTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `88acb17` | feat(learning-path-interfaces): agrega controllers REST, resources y tests de la API | `LearningPathApiIntegrationTest`, `LearningPathActionResultAssemblerTest`, `LearningPathResourceAssemblersTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `d7902d6` | feat(assessment-application): agrega servicios de comando, consulta, asignación de casos y ACL | Pruebas de dominio (`AssessmentAttemptTest`, `ScoreTest`, `ReviewDecisionTest`, `VerificationCaseTest`, `VerifierMatcherTest`, `VerifierProfileTest`) y de aplicación (`CaseAssignmentServiceImplTest`, servicios de comando y consulta). | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `5be2825` | feat(assessment-infrastructure): agrega persistencia JPA, converters y repositorios del BC | `AssessmentPeerReviewConvertersTest`, `AssessmentPeerReviewPersistenceTest`, `AssessmentPeerReviewServicesIntegrationTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `1b483a7` | test(assessment-peer-review): persistencia e integración de la apelación | Casos de apelación agregados a `AssessmentPeerReviewServicesIntegrationTest` y `AssessmentPeerReviewPersistenceTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `ebfa3f3` | feat(assessment-peer-review): endpoints REST de intentos, casos de verificación, apelación y perfil de verificador | `AssessmentPeerReviewApiIntegrationTest`, `AssessmentPeerReviewActionResultAssemblerTest`, `AssessmentPeerReviewResourceAssemblersTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `18dc046` | feat(reputation): dominio de confiabilidad del verificador y empleabilidad del estudiante | `VerifierReliabilityTest`, `StudentEmployabilityScoreTest`, `ReputationCalculatorsTest`, `ScoreValueObjectsTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `5e0ff30` | feat(reputation): servicios de aplicación y handlers de eventos de reputación | `ReputationCommandServiceImplTest`, `ReputationQueryServicesImplTest`, `ReputationEventHandlersTest`, `ReputationMessagesTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `5e5cb77` | feat(reputation): persistencia JPA y cableado de eventos de reputación | `ReputationEventWiringTest`, `ReputationPersistenceTest`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `628a9a7` | feat(reputation): endpoints REST de empleabilidad y confiabilidad | `ReputationApiIntegrationTest`, `ReputationActionResultAssemblerTest`, `ReputationResourceAssemblersTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `44ab707` | feat(recognition-incentives): dominio de wallet, créditos y canje | `WalletTest`, `CreditTransactionTest`, `CreditsTest`, `RecognitionIncentivesServicesTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `e1d2dca` | feat(recognition-incentives): servicios de aplicación y handlers de eventos de billetera | `WalletCommandServiceImplTest`, `WalletQueryServiceImplTest`, `RecognitionIncentivesEventHandlersTest`, `RecognitionIncentivesMessagesTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `e7b63c5` | feat(recognition-incentives): persistencia JPA, bloqueo de wallet y cableado de eventos | `RecognitionIncentivesEventWiringTest`, `RecognitionIncentivesPersistenceTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `6b4db93` | feat(recognition-incentives): endpoints REST de billetera y canje de beneficios | `RecognitionIncentivesApiIntegrationTest`, `RecognitionIncentivesActionResultAssemblerTest`, `RecognitionIncentivesResourceAssemblersTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger | `fba59d8` | feat(docs): documentación Swagger con autenticación JWT | `ApiDocumentationIntegrationTest`, `RootControllerTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger-tags | `c307b2a` | chore(swagger): group endpoints under readable names and descriptions | `ApiDocumentationIntegrationTest` valida la agrupación de los endpoints en el documento OpenAPI. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/subscription-billing | `03c29cd` | feat(subscription-billing): suscripción mensual con RevenueCat y límites por plan | `SubscriptionTest`, `BillingValueObjectsTest`, `SubscriptionCommandServiceImplTest`, `SubscriptionQueryServiceImplTest`, `SubscriptionBillingMessagesTest`, `RevenueCatGatewayAdapterTest`, `RevenueCatWebhookAuthorizationTest`, `SimulatedPaymentGatewayAdapterTest`, `SubscriptionBillingPersistenceTest`, `SubscriptionBillingActionResultAssemblerTest`, `SubscriptionBillingApiIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/plan-limits-enforcement | `7e86af6` | feat(plan-limits): límites del plan en rutas de aprendizaje y escalamientos | `ReviewDeadlineTest`, `PlanLimitsEnforcementIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `e778439` | feat(iam): verificación del correo institucional con Brevo | `SendVerificationEmailEventHandlerTest`, `EmailVerificationCommandServiceImplTest`, `EmailVerificationIssuerTest`, `VerificationEmailComposerTest`, `IamConfigTest`, `BrevoEmailSenderAdapterTest`, `EmailSettingsTest`, `EmailVerificationIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `3f7ec24` | feat(notifications): notificaciones push con Firebase Cloud Messaging | `NotifyCertificateResolutionEventHandlerTest`, `CertificateNotificationsIntegrationTest`, `UserNotificationsContextFacadeImplTest`, `FirebasePushNotificationAdapterTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `a7cd7ce` | feat(iam): perfil de intereses con vector de habilidades | `SkillCatalogContextFacadeImplTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/learning-path-gemini-matcher | `ec51fa9` | feat(learning-path): meta interpretada con Gemini, certificados validados y quiz sin preguntas repetidas | `AssessmentRetakeAndCertificateConditionTest`, `LearningPathCertificateCommandsTest`, `CertificateRecognitionTest`, `GeminiSkillTaxonomyMatcherTest`, `SkillTaxonomyMatcherWiringTest`, `KeywordCertificateSkillAffinityScorerTest`, `CertificateEvidenceApiIntegrationTest`, `GoalInterpretationApiIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `4babdcd` | feat(moderation-disputes): escalamiento de certificados sospechosos a un Verificador senior | `HolderNameMatcherTest`, `ModerationDisputesMessagesTest`, `DisputeCommandServiceImplTest`, `DisputeReviewerSelectorTest`, `DisputeTest`, `CertificateEscalationApiIntegrationTest`, `ReputationContextFacadeImplTest`, `SeniorVerifierPolicyTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `7175877` | feat(learning-path-engine): ruta avanzada canjeada con SkillCredits fuera de los límites del plan | `AdvancedPathUnlockTest`, `AdvancedPathUnlockIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `ac2e271` | feat(assessment-peer-review): plazo de revisión por plan y reasignación de casos vencidos | `ReviewDeadlinePolicyTest`, `ReviewDeadlinePolicyCommandServiceImplTest`, `ReviewDeadlinesIntegrationTest`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `8cb3afc` | test(moderation-disputes): end-to-end resolution of a certificate dispute | `CertificateDisputeResolutionFlowIntegrationTest`. | 2026-10-09 |

*Nota.* Por la convención de un commit por capa, las pruebas de cada capa se incorporan en el mismo commit que la capa que validan; `1b483a7` y `8cb3afc` son los únicos commits que solo agregan pruebas. La columna *Commit Message Body* lista las clases de prueba que agrega cada commit. Elaboración propia.


#### 4.2.1.6. Execution Evidence for Sprint Review

Durante el Sprint 1 se implementaron y verificaron en ejecución, sobre el backend Java / Spring Boot desplegado en [https://skillswap-webservices-java.onrender.com](https://skillswap-webservices-java.onrender.com), los flujos core del backend: registro y autenticación con dominio institucional, subida y evaluación de riesgo de un certificado, declaración de meta y generación de ruta de aprendizaje, generación y resolución de una evaluación, habilitación como Verificador, y el ciclo completo de un caso de verificación desde su apertura hasta su resolución.


**Figura 125**

*Registro con correo institucional*

<p align="center">
  <img src="images-doc/execution-sign-up.png" alt="Ejecución - Registro con correo institucional" width="800">
</p>

*Nota.* Registro de una cuenta `Student` con un correo `.edu.pe` (`201 Created`) e inicio de sesión con el token JWT retornado (`200 OK`), ejecutados desde Swagger UI con datos de demostración. Elaboración propia.

**Figura 126**

*Subida de un certificado y evaluación de riesgo*

<p align="center">
  <img src="images-doc/execution-certificate-upload.png" alt="Ejecución - Subida de certificado" width="800">
</p>

*Nota.* Subida de un certificado de demostración desde Swagger UI, con el `riskLevel` calculado (`LowRisk`) y el estado resultante (`Unverified`). Elaboración propia.

**Figura 127**

*Declaración de la meta y generación de la ruta*

<p align="center">
  <img src="images-doc/execution-learning-path.png" alt="Ejecución - Generación de ruta" width="800">
</p>

*Nota.* Declaración de la meta en lenguaje natural y ruta generada: el nodo prerrequisito en estado `Available` y el nodo meta en estado `Locked`. Elaboración propia.

**Figura 128**

*Evaluación generada por IA para un nodo*

<p align="center">
  <img src="images-doc/execution-assessment-blueprint.png" alt="Ejecución - Evaluación generada por IA" width="800">
</p>

*Nota.* Evaluación de un nodo disponible generada por Gemini mediante `POST /api/v1/path-nodes/{nodeId}/assessment-blueprint`: la respuesta incluye las preguntas y sus alternativas sin exponer las respuestas correctas. Elaboración propia.

**Figura 129**

*Ciclo de un caso de verificación*

<p align="center">
  <img src="images-doc/execution-assessment-case.png" alt="Ejecución - Caso de verificación" width="800">
</p>

*Nota.* Intento no aprobado que abre un `VerificationCase`, asignado automáticamente a un Verificador y resuelto con sus observaciones en `rubricNotes`. Elaboración propia.

**Figura 130**

*SkillCredits acreditados al Verificador*

<p align="center">
  <img src="images-doc/execution-wallet.png" alt="Ejecución - Billetera del Verificador" width="800">
</p>

*Nota.* Billetera del Verificador y su historial de movimientos tras resolver el caso de verificación: la transacción `Earned` registra los SkillCredits acreditados y el caso que los originó. Elaboración propia.

**Figura 131**

*Video de ejecución del Sprint 1*

<p align="center">
  <img src="images-doc/execution-video-thumbnail.png" alt="Video de ejecución - Sprint 1" width="800">
</p>

**Video de ejecución:** [https://youtu.be/p7NnDLr2VXs](https://youtu.be/p7NnDLr2VXs)

*Nota.* El video recorre en orden el flujo completo de punta a punta: (1) registro de una cuenta `Student` validando el dominio `.edu.pe`; (2) subida de un certificado y evaluación automática de riesgo; (3) declaración de la meta en lenguaje natural y generación de la ruta de aprendizaje; (4) generación de la evaluación de un nodo disponible y envío del intento; (5) apertura y asignación automática del `VerificationCase` cuando el intento no aprueba; (6) resolución del caso por el Verificador asignado, con la acreditación de SkillCredits y el recálculo de confiabilidad/empleabilidad como consecuencia.


#### 4.2.1.7. Services Documentation Evidence for Sprint Review

Todos los endpoints del Sprint 1 están documentados con **OpenAPI 3.1** (`SkillSwap Platform API` v1), generado por **springdoc-openapi** a partir de los controllers de Spring, con autenticación mediante el esquema `bearerAuth` (JWT): el botón *Authorize* de Swagger UI recibe el token que devuelve `POST /api/v1/authentication/sign-in`. La documentación interactiva está disponible en [https://skillswap-webservices-java.onrender.com/swagger-ui/index.html](https://skillswap-webservices-java.onrender.com/swagger-ui/index.html) y el documento OpenAPI en [https://skillswap-webservices-java.onrender.com/v3/api-docs](https://skillswap-webservices-java.onrender.com/v3/api-docs).

**Tabla 24**

*Endpoints documentados en el Sprint 1*

| Verbo | Endpoint | Acción | Auth | Parámetros | Respuestas |
|---|---|---|---|---|---|
| POST | `/api/v1/authentication/sign-up` | sign-up | No | Body: `username`, `email` (`.edu.pe`), `password`, `fullName` (opcional) | `201` `UserResource` (cuenta sin verificar; se envía el enlace de verificación) · `400` datos inválidos · `409` usuario o correo ya existe |
| POST | `/api/v1/authentication/sign-in` | sign-in | No | Body: `username`, `password` | `200` `AuthenticatedUserResource` (incluye `token`) · `401` credenciales inválidas · `403` `EmailNotVerified` (se reenvía el enlace de verificación) |
| POST | `/api/v1/authentication/verify-email` | verify-email | No | Body: `token` | `200` `UserResource` verificado · `400` `InvalidVerificationToken` · `410` `VerificationTokenExpired` |
| GET | `/api/v1/authentication/verify-email` | verify-email-link | No | Query: `token` | `200` página HTML con el resultado de la verificación |
| POST | `/api/v1/authentication/resend-verification` | resend-verification | No | Body: `email` | `202` `MessageResource` (la misma respuesta para cualquier correo) |
| GET | `/api/v1/users/me` | get-current-user | Sí | — | `200` `UserResource` |
| GET | `/api/v1/users/{id}` | get-user-by-id | Sí | Path: `id` | `200` `UserResource` si es el dueño; `PublicUserResource` (sin email) para cualquier otro usuario autenticado · `404` |
| PATCH | `/api/v1/users/{id}/bio` | update-bio | Sí | Path: `id`; Body: `bio` | `200` `UserResource` · `400` · `403` no es el dueño · `404` |
| PUT | `/api/v1/users/{id}/interests` | update-interests | Sí | Path: `id`; Body: `topics` (1 a 10 temas), `description` (opcional) | `200` `UserResource` con `interests` y `skillVector` · `400` · `403` · `404` |
| PATCH | `/api/v1/users/{id}/full-name` | update-full-name | Sí | Path: `id`; Body: `fullName` (máx. 150) | `200` `UserResource` · `400` · `403` · `404` |
| PUT | `/api/v1/users/me/device-token` | register-device-token | Sí | Body: `token` (token de Firebase Cloud Messaging) | `204` · `400` `InvalidDeviceToken` |
| DELETE | `/api/v1/users/me/device-token` | remove-device-token | Sí | — | `204` |
| POST | `/api/v1/certificates` | upload-certificate | Sí (Student) | `multipart/form-data`: `file` (JPG, PNG o PDF, máx. 10 MB) y, opcionalmente, `holderName`, `institutionName`, `courseName`, `issueDate`, `durationHours`, `certificateNumber`, `verificationCode`, `verificationUrl`, `qrPayload`, `ocrText` | `201` `CertificateResource` · `400` · `403` · `409` archivo duplicado · `413` · `415` |
| GET | `/api/v1/certificates` | list-certificates | Sí | Query: `ownerId` (opcional; debe ser el id del propio estudiante) | `200` arreglo de `CertificateResource` · `403` |
| GET | `/api/v1/certificates/{id}` | get-certificate-by-id | Sí | Path: `id` | `200` `CertificateResource` · `403` · `404` |
| POST | `/api/v1/learning-paths` | declare-goal | Sí (Student) | Body: `goal` (texto libre, máx. 500), `advanced` (opcional) | `201` `LearningPathResource` · `400` · `403` · `409` `PlanLimitReached` (con `limit`, `plan`, `max`, `current` y `upgradeAvailable`) o `AdvancedPathUnlockRequired` · `422` meta sin habilidades en la taxonomía |
| GET | `/api/v1/learning-paths/{studentId}` | get-learning-path | Sí | Path: `studentId` | `200` `LearningPathResource` · `403` · `404` |
| GET | `/api/v1/learning-paths` | list-learning-paths | Sí | Query: `studentId` (debe ser el id del propio estudiante) | `200` arreglo de `LearningPathResource` (activas, pausadas y completadas) · `403` |
| PATCH | `/api/v1/learning-paths/{pathId}/pause` | pause-learning-path | Sí (Student dueño) | Path: `pathId` | `200` `LearningPathResource` · `403` · `404` · `409` `PathNotActive` |
| PATCH | `/api/v1/learning-paths/{pathId}/resume` | resume-learning-path | Sí (Student dueño) | Path: `pathId` | `200` `LearningPathResource` · `403` · `404` · `409` `PathNotPaused` o `PlanLimitReached` |
| POST | `/api/v1/path-nodes/{nodeId}/assessment-blueprint` | generate-blueprint | Sí (Student) | Path: `nodeId` | `201` `AssessmentBlueprintResource` (sin respuestas correctas ni preguntas de intentos anteriores) · `403` · `404` · `409` nodo bloqueado o completado · `503` IA no disponible |
| POST | `/api/v1/path-nodes/{nodeId}/certificate` | link-certificate | Sí (Student dueño) | Path: `nodeId`; Body: `certificateId` | `200` `CertificateLinkResource` (`affinity`, `threshold`, `assessmentEnabled`) · `403` · `404` · `409` `CertificateNotVerified` o `NodeAlreadyCompleted` · `422` `CertificateSkillMismatch` con `suggestedNodes` |
| GET | `/api/v1/advanced-path-unlocks` | list-advanced-path-unlocks | Sí (Student) | — | `200` arreglo de `AdvancedPathUnlockResource` |
| POST | `/api/v1/assessment-attempts` | submit-attempt | Sí (Student) | Body: `blueprintId`, `selectedAnswers` (5 enteros entre 0 y 3) | `201` `AssessmentAttemptResource` (con `passed` y, si no aprueba, `verificationCaseId`; con `planLimitReached` y sin caso si se agotaron los escalamientos del mes) · `400` · `403` · `404` · `409` |
| GET | `/api/v1/assessment-attempts/{attemptId}` | get-attempt | Sí | Path: `attemptId` | `200` `AssessmentAttemptResource` · `403` · `404` |
| GET | `/api/v1/verification-cases` | list-my-cases | Sí (Verificador) | — | `200` arreglo de `VerificationCaseResource` |
| GET | `/api/v1/verification-cases/{caseId}` | get-case-detail | Sí | Path: `caseId` | `200` `VerificationCaseDetailResource` (caso, intento y preguntas falladas) · `403` · `404` |
| PUT | `/api/v1/verification-cases/{caseId}/evidence` | attach-evidence | Sí (Student) | Path: `caseId`; Body: `evidenceUrl` (http/https, máx. 500) | `200` `VerificationCaseResource` · `400` · `403` · `404` · `409` caso resuelto |
| PATCH | `/api/v1/verification-cases/{caseId}/decision` | resolve-case | Sí (Verificador asignado) | Path: `caseId`; Body: `decision` (`Approved` o `Rejected`), `rubricNotes` (máx. 2000) | `200` `VerificationCaseResource` · `400` · `403` · `404` · `409` |
| POST | `/api/v1/verification-cases/{caseId}/appeal` | appeal-case | Sí (Student dueño del caso) | Path: `caseId` | `200` `VerificationCaseResource` (reasignado a otro Verificador o `Pending`) · `403` · `404` · `409` caso no rechazado o ya apelado |
| POST | `/api/v1/verifier-profiles` | create-verifier-profile | Sí (Student) | Body: `skillTag` | `201` perfil creado · `200` habilidad agregada · `400` · `403` · `409` |
| GET | `/api/v1/verifier-profiles/me` | get-my-verifier-profile | Sí | — | `200` `VerifierProfileResource` · `404` |
| PATCH | `/api/v1/verifier-profiles/me/availability` | update-availability | Sí (Verificador) | Body: `available` (booleano) | `200` `VerifierProfileResource` · `400` · `403` |
| GET | `/api/v1/review-deadline-policies` | get-review-deadlines | Sí | — | `200` arreglo de `ReviewDeadlinePolicyResource` (plazo vigente de cada plan) |
| PUT | `/api/v1/review-deadline-policies` | define-review-deadlines | Sí (Verificador senior) | Body: `premiumPlanHours` (máx. 48), `freePlanBusinessDays` (máx. 5) | `200` arreglo de `ReviewDeadlinePolicyResource` · `400` fuera de rango · `403` no es Verificador senior |
| GET | `/api/v1/disputes` | list-my-disputes | Sí (Verificador) | Query: `status` (`Pending` por defecto, `Resolved` o `All`) | `200` arreglo de `DisputeResource` asignadas al usuario · `400` · `403` no es Verificador habilitado |
| GET | `/api/v1/disputes/{id}/evidence` | get-dispute-evidence | Sí (revisor asignado) | Path: `id` | `200` `DisputeEvidenceResource` (disputa y certificado en revisión) · `403` · `404` |
| PATCH | `/api/v1/disputes/{id}/resolve` | resolve-dispute | Sí (revisor asignado) | Path: `id`; Body: `outcome` (`Upheld` u `Overturned` en una revisión de certificado), `resolutionNotes` (obligatorias, máx. 2000) | `200` `DisputeResource` · `400` `InvalidOutcome`, `ResolutionNotesRequired` o `ResolutionNotesTooLong` · `403` · `404` · `409` ya resuelta o certificado no sospechoso |
| GET | `/api/v1/verifier-reliabilities/{verifierUserId}` | get-reliability | Sí | Path: `verifierUserId` | `200` `VerifierReliabilityResource` · `403` · `404` |
| GET | `/api/v1/student-employability-scores/{studentId}` | get-employability | Sí | Path: `studentId` | `200` `StudentEmployabilityResource` · `403` · `404` |
| GET | `/api/v1/wallets/{userId}` | get-wallet | Sí | Path: `userId` | `200` `WalletResource` · `403` · `404` |
| GET | `/api/v1/wallets/{userId}/transactions` | list-transactions | Sí | Path: `userId` | `200` arreglo de `CreditTransactionResource` · `403` · `404` |
| POST | `/api/v1/credit-transactions/redeem` | redeem-credits | Sí | Body: `item` (`AdvancedPathUnlock` = 200 o `ContributionCertificate` = 120 SkillCredits) | `201` `CreditTransactionResource` · `400` · `404` · `409` saldo insuficiente |
| POST | `/api/v1/subscriptions` | create-subscription | Sí (Student) | Body: `productId` (opcional) | `201` `SubscriptionResource` · `400` `InvalidProduct` · `422` `PurchaseNotVerified` · `503` `PaymentGatewayUnavailable` |
| GET | `/api/v1/subscriptions/{studentId}` | get-student-plan | Sí (Student) | Path: `studentId` (debe ser el id del propio estudiante) | `200` `StudentPlanResource` (plan, límites y suscripción no vencida o `null`) · `403` |
| PATCH | `/api/v1/subscriptions/{id}/cancel` | cancel-subscription | Sí (Student dueño) | Path: `id` | `200` `SubscriptionResource` (idempotente) · `403` · `404` · `409` `SubscriptionNotActive` · `503` |
| POST | `/api/v1/subscriptions/webhooks/revenuecat` | revenuecat-webhook | No (encabezado `Authorization` con el secreto configurado) | Body: evento del webhook de RevenueCat | `200` `{outcome: Processed\|Duplicate\|Ignored}` · `400` `InvalidWebhookEvent` · `401` `InvalidWebhookAuthorization` · `503` para que RevenueCat reintente |
| GET | `/health` | health-check | No | — | `200` `HealthResource` |

*Nota.* Endpoints de la rama `develop` del repositorio `SkillSwap-WebServices-Java`, que integra el trabajo del Sprint 1. Elaboración propia.

**Ejemplos de uso con datos de muestra**

*Registro (`POST /api/v1/authentication/sign-up`).*

```json
{ "username": "maria.quispe", "email": "maria.quispe@upc.edu.pe", "password": "Segura#2026" }
```
Respuesta `201 Created`:
```json
{ "id": 7, "username": "maria.quispe", "email": "maria.quispe@upc.edu.pe", "role": "Student", "isVerified": false, "bio": "", "fullName": null, "interests": [], "skillVector": [] }
```
La cuenta se crea con rol `Student` y sin verificar, y se envía el enlace de verificación al correo institucional; con un correo fuera del dominio `.edu.pe` la API responde `400`.

*Intento de evaluación fallido (`POST /api/v1/assessment-attempts`).*

```json
{ "blueprintId": 12, "selectedAnswers": [1, 0, 2, 3, 1] }
```
Respuesta `201 Created`:
```json
{ "id": 31, "blueprintId": 12, "studentId": 7, "score": 3, "totalQuestions": 5, "passed": false, "completedAt": "2026-10-02T15:42:10Z", "verificationCaseId": 9, "verificationCaseStatus": "Assigned" }
```
Con 3 de 5 respuestas correctas el nodo no se completa: se abre el caso `9` y se asigna a un Verificador disponible.

*Resolución del caso (`PATCH /api/v1/verification-cases/9/decision`).*

```json
{ "decision": "Approved", "rubricNotes": "Demostró dominio de los conceptos fallidos en la entrevista." }
```
Respuesta `200 OK`: el caso pasa a estado resuelto con `decision: "Approved"`, el nodo del estudiante se completa y se acreditan SkillCredits al Verificador.

*Nota.* Elaboración propia.


**Figura 132**

*Documentación de los Web Services en Swagger*

<p align="center">
  <img src="images-doc/swagger-public.png" alt="Swagger público del backend" width="900">
</p>

*Nota.* Swagger UI del backend Java desplegado en Render, con los endpoints agrupados por Bounded Context. Elaboración propia.

**Figura 133**

*Autorización con JWT en Swagger UI*

<p align="center">
  <img src="images-doc/swagger-authorize.png" alt="Swagger UI - Autorización con JWT" width="900">
</p>

*Nota.* Autorización en Swagger UI con el esquema `bearerAuth`: el token JWT que devuelve `POST /api/v1/authentication/sign-in` se ingresa en *Authorize* para invocar los endpoints protegidos. Elaboración propia.


**Commits relacionados con la documentación**

springdoc-openapi genera el documento OpenAPI automáticamente a partir de las anotaciones de Spring MVC de cada controller (ruta, verbo, parámetros y resources de entrada y salida), por lo que los commits de la capa Interface de cada Bounded Context son los que definen los endpoints documentados. El commit `fba59d8` incorpora la dependencia `springdoc-openapi-starter-webmvc-ui`, el esquema de seguridad `bearerAuth` y la redirección a Swagger UI, y la prueba `ApiDocumentationIntegrationTest` verifica que el documento sea accesible sin token.

**Tabla 25**

*Commits relacionados con la documentación de los Web Services*

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| SkillSwap-WebServices-Java | feature/iam-identity-access | `b8c0c0a` | feat(iam-interfaces): agrega AuthenticationController, UsersController, resources y manejo de errores ProblemDetail | Endpoints de autenticación y usuarios, con sus resources y las respuestas de error en formato ProblemDetail. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/credential-verification | `7501882` | feat(credential-interfaces): expone endpoints REST de certificados con carga multipart y manejo de errores | Endpoints de certificados, incluida la carga `multipart/form-data`. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/learning-path-engine | `88acb17` | feat(learning-path-interfaces): agrega controllers REST, resources y tests de la API | Endpoints de rutas de aprendizaje y de generación de evaluaciones. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/assessment-peer-review | `ebfa3f3` | feat(assessment-peer-review): endpoints REST de intentos, casos de verificación, apelación y perfil de verificador | Endpoints de intentos, casos de verificación, apelación y perfiles de Verificador. | 2026-10-08 |
| SkillSwap-WebServices-Java | feature/reputation | `628a9a7` | feat(reputation): endpoints REST de empleabilidad y confiabilidad | Endpoints de solo lectura de confiabilidad del Verificador y Employability Score. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/recognition-incentives | `6b4db93` | feat(recognition-incentives): endpoints REST de billetera y canje de beneficios | Endpoints de billetera, historial de movimientos y canje. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger | `fba59d8` | feat(docs): documentación Swagger con autenticación JWT | `OpenApiConfig` (título, descripción y esquema `bearerAuth`), `RootController` y apertura de `/swagger-ui/**` y `/v3/api-docs/**` en `SecurityConfig`. | 2026-10-09 |
| SkillSwap-WebServices-Java | chore/swagger-tags | `c307b2a` | chore(swagger): group endpoints under readable names and descriptions | `OpenApiTagsConfig`: los endpoints de Swagger UI se agrupan por Bounded Context con nombres y descripciones legibles. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/subscription-billing | `03c29cd` | feat(subscription-billing): suscripción mensual con RevenueCat y límites por plan | Endpoints de suscripción y webhook de RevenueCat. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/plan-limits-enforcement | `7e86af6` | feat(plan-limits): límites del plan en rutas de aprendizaje y escalamientos | Listado, pausa y reanudación de rutas y respuesta `PlanLimitReached`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `e778439` | feat(iam): verificación del correo institucional con Brevo | Endpoints `verify-email` y `resend-verification`. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `3f7ec24` | feat(notifications): notificaciones push con Firebase Cloud Messaging | Endpoints del token del dispositivo. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/iam-email-verification-push | `a7cd7ce` | feat(iam): perfil de intereses con vector de habilidades | Endpoint de intereses. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/learning-path-gemini-matcher | `ec51fa9` | feat(learning-path): meta interpretada con Gemini, certificados validados y quiz sin preguntas repetidas | Endpoint de vinculación de un certificado a un nodo. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `4babdcd` | feat(moderation-disputes): escalamiento de certificados sospechosos a un Verificador senior | Endpoints de disputas y del nombre completo del usuario. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `7175877` | feat(learning-path-engine): ruta avanzada canjeada con SkillCredits fuera de los límites del plan | Endpoint de desbloqueos de ruta avanzada y campo `advanced` al declarar la meta. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/certificate-escalation-and-deadlines | `ac2e271` | feat(assessment-peer-review): plazo de revisión por plan y reasignación de casos vencidos | Endpoints de plazos de revisión por plan. | 2026-10-09 |
| SkillSwap-WebServices-Java | feature/complete-acceptance-scenarios | `56f5a13` | refactor(moderation-disputes): rename coordinatorNotes to resolutionNotes | Campo `resolutionNotes` en la resolución de disputas. | 2026-10-09 |

*Nota.* Elaboración propia.

#### 4.2.1.8. Software Deployment Evidence for Sprint Review

Durante el Sprint 1 se configuró y verificó el despliegue completo del backend Java en Render: creación del servicio web con *Runtime: Docker* a partir del `Dockerfile` del repositorio, conexión con la base de datos PostgreSQL administrada, variables de entorno (ver 4.1.4) y health check en `/health`. El procedimiento está documentado en `docs/deploy-render.md` del repositorio `SkillSwap-WebServices-Java`.

**Figura 134**

*Servicio web desplegado en Render*

<p align="center">
  <img src="images-doc/render-dashboard.png" alt="Dashboard de Render - Servicio web activo" width="900">
</p>

*Nota.* Servicio web del backend en Render (*Runtime: Docker*, rama `develop`) y su historial de despliegues. Elaboración propia.

**Figura 135**

*Logs del arranque en Render*

<p align="center">
  <img src="images-doc/render-startup-logs.png" alt="Logs del arranque en Render" width="900">
</p>

*Nota.* Logs del arranque del contenedor en Render: inicio de Spring Boot 4.1.1 sobre Java 21. Elaboración propia.

**Figura 136**

*Dockerfile del backend*

<p align="center">
  <img src="images-doc/deploy-dockerfile.png" alt="Dockerfile del backend" width="900">
</p>

*Nota.* `Dockerfile` multi-etapa de la rama `develop` del repositorio `SkillSwap-WebServices-Java`: compilación con Maven y JDK 21, y ejecución con el JRE 21 y un usuario sin privilegios. Elaboración propia.

**Figura 137**

*Health check del backend en Render*

<p align="center">
  <img src="images-doc/deploy-health.png" alt="Health check del backend" width="900">
</p>

*Nota.* Respuesta `200` de `GET /health` del backend desplegado en Render, con el estado `Healthy`. Elaboración propia.

**Figura 138**

*Landing Page publicado en GitHub Pages*

<p align="center">
  <img src="images-doc/landing-github-pages.png" alt="Landing Page en GitHub Pages" width="900">
</p>

*Nota.* Landing Page publicado en GitHub Pages desde la rama `main` del repositorio `SkillSwap-LandingPage`, con el llamado a la acción "Descarga la app". Elaboración propia.

El backend está desplegado públicamente en: [https://skillswap-webservices-java.onrender.com](https://skillswap-webservices-java.onrender.com) (Swagger UI en `/swagger-ui/index.html`).

*(Limitación conocida, declarada también en Conclusiones: el plan gratuito de Render suspende el servicio tras 15 minutos de inactividad, con la primera petición posterior tardando hasta cerca de un minuto; se configuró un ping de mantenimiento cada 10 minutos a `/health` para mitigarlo. La base de datos PostgreSQL gratuita expira 30 días después de creada, con 14 días de gracia.)*

#### 4.2.1.9. Team Collaboration Insights during Sprint

**Figura 139**

*Historial de commits del repositorio SkillSwap-WebServices-Java durante el Sprint 1*

<p align="center">
  <img src="images-doc/github-insights-sprint1.png" alt="Analíticos de colaboración del Sprint 1 - SkillSwap-WebServices-Java" width="900">
</p>

*Nota.* Historial de commits de la rama `develop` del repositorio `SkillSwap-WebServices-Java` durante el Sprint 1 (GitHub Insights). Elaboración propia.


Durante el Sprint 1, el backend se construyó entre dos integrantes. Alberca Saavedra, Víctor Manuel migró el backend de C# / ASP.NET Core a Java / Spring Boot y construyó la base de seis Bounded Contexts (Identity & Access, Credential Verification, Learning Path Engine, Assessment & Peer Review, Reputation y Recognition & Incentives) con un commit por capa, junto con el despliegue en Render y la documentación con Swagger (PR #1 a #10). Sulca Sánchez, Piero Angel incorporó las migraciones con Flyway, Subscription & Billing, Moderation & Disputes y las funcionalidades agregadas sobre los demás Bounded Contexts —verificación del correo con Brevo, notificaciones push, interpretación de la meta con Gemini, escalamiento de certificados sospechosos, ruta avanzada y plazos de revisión— (PR #11 a #15), y la sección de precios y el CTA de descarga del Landing Page (PR #7 y #8 de `SkillSwap-LandingPage`). El diseño UX/UI de la aplicación móvil y el avance del Capítulo III se documentan en el repositorio `SkillSwap-ProjectReport` (ver Project Report Collaboration Insights).



---


# Conclusiones

**Sobre el pivote del proyecto y lo que aprendimos de él**

Uno de los aprendizajes más grandes del ciclo no vino del código, sino de una decisión de negocio. Nuestra idea original de SkillSwap giraba en torno a tutorías entre estudiantes de distintas universidades, con donaciones voluntarias y comisión de plataforma. Cuando el docente publicó el anexo de temas excluidos y "tutorías en línea" apareció ahí, tuvimos que replantear el core del producto ya iniciado el ciclo, no desde cero. Lo que nos salvó gran parte del trabajo fue haber construido la arquitectura de forma modular desde el principio: de los 7 Bounded Contexts originales, 4 se mantuvieron prácticamente intactos (Identity & Access, Reputation, Recognition & Incentives, Moderation & Disputes) y solo tuvimos que rediseñar el core (Discovery, Workspace y Learning & Assessment se fusionaron y se dividieron en los nuevos Credential Verification, Learning Path Engine y Assessment & Peer Review). El aprendizaje concreto: diseñar con límites de contexto bien definidos no solo ayuda a repartir trabajo en equipo, también protege el proyecto cuando el negocio cambia a mitad de camino.

**Sobre decidir conscientemente qué no implementar**

Al diseñar Credential Verification, la propuesta inicial contemplaba verificar certificados contra fuentes oficiales como SUNEDU o Coursera. Nos dimos cuenta a tiempo de que esas integraciones no son viables en un ciclo académico —no existen APIs públicas para eso, y hacerlo por scraping no era una opción seria— así que documentamos esos mecanismos en el modelo (`VerificationMethod`) pero solo implementamos los dos que sí eran alcanzables: extracción OCR on-device y revisión manual por un par. Lo mismo pasó con el matching entre estudiante y Verificador: la idea original hablaba de un sistema de recomendación híbrido con embeddings de habilidades, y terminamos simplificándolo a una asignación por disponibilidad y carga de casos. Aprendimos que reconocer a tiempo la diferencia entre "lo que el producto podría tener" y "lo que el equipo puede sostener en 15 semanas" evita quedar con funcionalidades a medio implementar al final del ciclo.

**Sobre reutilizar investigación real en vez de descartarla**

Cuando tuvimos que reestructurar el segmento de "personas que quieren enseñar", nuestra primera reacción fue pensar que había que volver a grabar entrevistas desde cero. En vez de eso, revisamos las 6 entrevistas ya grabadas (3 de mentores, 3 de coordinadores) y nos dimos cuenta de que los hallazgos reales seguían siendo válidos bajo la nueva propuesta: por ejemplo, más de un entrevistado ya nos había dicho que su motivación principal no era el dinero sino el reconocimiento profesional, lo cual terminó siendo exactamente el fundamento de SkillCredits. Reetiquetar en vez de regrabar nos permitió mantener el rigor de la investigación de campo sin perder semanas de trabajo ya hecho.

**Sobre el proceso Lean UX en contraste con el diseño técnico**

Contrastar el Problem Statement con nuestro propio diseño de arquitectura nos obligó a revisar más de una vez si el texto seguía describiendo el problema o ya se había colado la solución —un error común que el propio docente del ciclo pasado ya nos había advertido. Ese ida y vuelta constante entre Capítulo I y Capítulo II terminó siendo, en la práctica, la forma más efectiva de detectar inconsistencias: cualquier mención a "comisión", "videollamada de enseñanza" o "mentor" en el texto de negocio era una señal inmediata de que ese párrafo todavía no reflejaba el modelo que ya habíamos cerrado en el diseño técnico.

**Sobre lo que el diseño no puede anticipar hasta que se construye**

Al implementar Assessment & Peer Review descubrimos que nuestro propio informe tenía dos versiones contradictorias del mismo Bounded Context: una en la sección táctica (un modelo simple, de rúbrica con notas libres) y otra en el EventStorming y las User Stories (tres intentos de quiz, examen de ingreso del Verificador, rúbrica por criterio, segundo revisor). Construir el backend nos obligó a decidir entre ambas versiones, y optamos por el modelo mínimo como el oficial: es el que de verdad resuelve el flujo completo dentro del tiempo del Sprint, y mantener el modelo largo solo como "visión" sin marcarlo como tal habría dejado un documento que describía un sistema distinto al que realmente funciona. Aprendimos que un informe de arquitectura puede estar internamente contradicho sin que nadie lo note hasta que alguien intenta implementarlo literalmente — la construcción real terminó siendo, en los hechos, la revisión más rigurosa que le hicimos al propio diseño.

**Sobre investigar la tecnología externa antes de comprometerla en el diseño**

La pasarela de pago pasó por tres decisiones distintas a lo largo del proyecto: primero Stripe (descartada porque no opera en Perú), luego Culqi o Mercado Pago (considerados durante el modelado inicial), y finalmente Google Play Billing, que terminó siendo la opción correcta no por preferencia sino porque es un requisito real de Google para suscripciones distribuidas vía Play Store. Llegar a esa conclusión nos obligó además a corregir el propio modelo de dominio: a diferencia de Stripe, el backend nunca "cobra" directamente, solo verifica una compra ya realizada del lado del cliente, lo que cambió el método `charge()` original por `verifyPurchase()`. Después adoptamos RevenueCat sobre Google Play Billing para no implementar a mano la validación de compras ni las notificaciones RTDN, entendiendo que RevenueCat no reemplaza la facturación de Google: Google Play sigue procesando el cobro y RevenueCat solo valida la compra y notifica sus cambios al backend. De forma parecida, al intentar desplegar en Render descubrimos que la plataforma no ofrece MySQL como base de datos administrada —solo PostgreSQL de forma nativa— y tuvimos que migrar todo el diseño de persistencia antes de escribir una sola línea de código de infraestructura. En ambos casos, la lección fue la misma: las restricciones reales de las tecnologías y plataformas externas solo aparecen cuando uno intenta usarlas de verdad, y conviene descubrirlas investigando a tiempo en vez de durante el despliegue.

**Sobre migrar el backend de .NET a Java sin perder lo construido**

El backend del Sprint 1 se construyó primero en C# / ASP.NET Core, y cuando el curso estableció Java con Spring Boot como tecnología obligatoria para los Web Services, tuvimos que migrarlo a mitad del Sprint. Lo que hizo viable la migración fue que el diseño no dependía del framework: los Bounded Contexts, los agregados, las reglas de negocio, el contrato de los endpoints y el esquema de PostgreSQL se trasladaron casi uno a uno, y el backend Java reutiliza la misma base de datos, que Hibernate solo valida al arrancar. Las pruebas cambiaron de herramienta (de xUnit y Reqnroll a JUnit 5, MockMvc y Testcontainers) pero no de propósito: los mismos escenarios de aceptación se volvieron a automatizar contra una base PostgreSQL real. La lección fue que separar el modelo de dominio de la infraestructura no es solo una buena práctica teórica: es lo que permite cambiar de lenguaje y de framework sin rediseñar el producto. También aprendimos que una migración obliga a revisar toda la evidencia del informe, porque capturas, commits y referencias que eran correctas para la primera versión dejan de serlo apenas cambia el repositorio.

**Sobre mantener el informe honesto con el código a medida que el proyecto avanza**

Terminado el Sprint 1, nos sentamos a comparar sistemáticamente lo que el backend realmente hacía contra lo que el informe decía, Bounded Context por Bounded Context. Encontramos decenas de diferencias pequeñas (nombres de clases, rutas de endpoints, campos que no existían) y varias de fondo (registrar un certificado no completa un nodo por sí solo, sino solo cuando un Verificador lo valida; la evidencia de un caso es solo una URL y no un archivo subido, Identity & Access exige el dominio institucional desde el registro y no mediante un código posterior). Ninguna de esas diferencias era un error del código: eran decisiones reales que tomamos durante la construcción y que el documento de diseño simplemente no había alcanzado a reflejar todavía. Corregirlas todas de una sola vez, en vez de ir parchando el informe mientras programábamos, nos permitió entregar un documento consistente de principio a fin — y nos dejó claro que, en un proyecto de este tamaño, el informe de arquitectura necesita su propio ciclo de mantenimiento, igual que el código.


# Glosario

En esta sección se definen los términos técnicos, abreviaturas y acrónimos de ingeniería de software usados en el informe. Los términos propios del dominio de SkillSwap se definen en la sección 2.3.6 (Ubiquitous Language).

* **a11y:** Abreviatura de *accessibility* (accesibilidad): práctica de diseñar productos que puedan usar personas con distintas capacidades.
* **Aggregate (Agregado):** En Domain-Driven Design, grupo de objetos de dominio que se trata como una unidad de consistencia, con una entidad raíz que controla el acceso.
* **Anti-Corruption Layer (ACL):** Patrón de Domain-Driven Design que traduce el modelo de otro contexto o sistema externo para no contaminar el modelo propio.
* **API:** *Application Programming Interface*: conjunto de operaciones que un sistema expone para que otros sistemas lo consuman.
* **ASO:** *App Store Optimization*: optimización de los textos y metadatos de una aplicación para mejorar su visibilidad en una tienda de aplicaciones.
* **BDD:** *Behavior-Driven Development*: enfoque de desarrollo en el que las pruebas describen el comportamiento esperado en lenguaje natural, por ejemplo con Gherkin.
* **Bounded Context:** En Domain-Driven Design, límite dentro del cual un modelo de dominio y su lenguaje tienen un significado único y consistente.
* **C4 Model:** Modelo de diagramación de arquitectura de software en cuatro niveles: contexto, contenedores, componentes y código.
* **Context Mapping:** Técnica de Domain-Driven Design que representa las relaciones entre Bounded Contexts mediante patrones como Customer/Supplier, Conformist o Anti-Corruption Layer.
* **Conventional Commits:** Convención para redactar mensajes de commit con un tipo (feat, fix, docs, test, etc.) y una descripción breve.
* **Docker:** Plataforma para empaquetar una aplicación y sus dependencias en contenedores que se ejecutan de forma aislada.
* **Domain-Driven Design (DDD):** Enfoque de diseño de software que organiza el sistema alrededor del dominio del negocio y de su lenguaje.
* **Domain Event (Evento de dominio):** Hecho relevante para el negocio que ya ocurrió, como un caso de verificación resuelto, y que otros contextos pueden consumir.
* **Domain Storytelling:** Técnica de modelado que describe, mediante historias visuales, cómo colaboran los actores y los sistemas en un escenario del negocio.
* **Epic:** Agrupación de User Stories relacionadas con un mismo objetivo funcional.
* **EventStorming:** Técnica colaborativa que modela un dominio a partir de sus eventos, ordenados en el tiempo, para descubrir procesos, agregados y Bounded Contexts.
* **Gherkin:** Lenguaje estructurado (Given-When-Then; en español, Dado que-Cuando-Entonces) para escribir criterios de aceptación y escenarios de prueba.
* **GitFlow:** Modelo de ramas de Git que separa el trabajo en ramas main, develop, feature, release y hotfix.
* **i18n:** Abreviatura de *internationalization* (internacionalización): preparación de un producto para varios idiomas y regiones.
* **JWT:** *JSON Web Token*: token firmado que identifica a un usuario autenticado al consumir servicios protegidos.
* **Landing Page:** Sitio web estático que presenta el modelo de negocio y la propuesta de valor del producto a los visitantes.
* **Lean UX:** Enfoque de diseño centrado en el usuario que trabaja con supuestos e hipótesis que se validan de forma iterativa.
* **ML Kit:** SDK de Google para ejecutar modelos de aprendizaje automático en el dispositivo; en SkillSwap se usa para reconocer el texto de los certificados.
* **Mock-up:** Representación visual de alta fidelidad de una pantalla, con colores, tipografía y contenido finales.
* **OCR:** *Optical Character Recognition*: reconocimiento óptico de caracteres, que convierte el texto de una imagen en texto editable.
* **OpenAPI / Swagger:** Especificación estándar para documentar servicios REST; Swagger UI permite consultarla y probarla de forma interactiva.
* **Product Backlog:** Lista ordenada por valor de negocio de todas las historias que forman el alcance del producto.
* **Prototype (Prototipo):** Representación navegable de la aplicación que simula la interacción entre pantallas.
* **REST / RESTful:** Estilo de arquitectura para servicios web basado en recursos identificados por URL y operaciones HTTP (GET, POST, PUT, PATCH, DELETE).
* **Semantic Versioning:** Convención de versionado MAYOR.MENOR.PARCHE para identificar el tipo de cambio de cada versión.
* **SEO:** *Search Engine Optimization*: optimización de un sitio web para mejorar su posición en los buscadores.
* **Spike Story:** Historia orientada a investigar o probar la viabilidad de una tecnología antes de implementar una funcionalidad.
* **Sprint:** Iteración de duración fija en Scrum, durante la cual el equipo construye un incremento del producto.
* **Sprint Backlog:** Conjunto de historias y tareas que el equipo se compromete a completar en un Sprint.
* **Story Points:** Unidad relativa de estimación del esfuerzo, la complejidad y la incertidumbre de una historia.
* **Technical Story:** Historia que describe una funcionalidad sin interacción directa con el usuario final, como un endpoint REST, redactada con el rol Developer.
* **User Flow:** Diagrama que muestra los pasos y decisiones que sigue un usuario para cumplir un objetivo, incluyendo rutas alternativas.
* **User Story:** Descripción breve de una funcionalidad desde la perspectiva del usuario, con el formato Como… quiero… para…, acompañada de criterios de aceptación.
* **Value Object (Objeto de valor):** En Domain-Driven Design, objeto sin identidad propia que se define por sus atributos, como un correo electrónico.
* **WCAG:** *Web Content Accessibility Guidelines*: pautas internacionales de accesibilidad para contenidos digitales.
* **Wireflow:** Diagrama que combina wireframes o mock-ups con flechas para mostrar cómo se pasa de una pantalla a otra.
* **Wireframe:** Representación de baja fidelidad de una pantalla que define su estructura y jerarquía sin diseño visual final.

# Bibliografía

Las referencias se organizan en las tres categorías de recursos bibliográficos que establece el enunciado del trabajo final: dominio de negocio; métodos y técnicas de ingeniería de software; y lenguajes, frameworks y herramientas.

**Dominio de negocio**

* Coursera. (2025). *Global skills report 2025*. [https://www.coursera.org/skills-reports/global](https://www.coursera.org/skills-reports/global)
* Instituto Nacional de Estadística e Informática. (2025). *Estadísticas de las tecnologías de información y comunicación en los hogares: II trimestre 2025* (Informe Técnico N.° 03). [https://www.inei.gob.pe/media/MenuRecursivo/boletines/informetecnico_tics_iit25.pdf](https://www.inei.gob.pe/media/MenuRecursivo/boletines/informetecnico_tics_iit25.pdf)
* Novella, R., Alvarado, A., Rosas, D., & González-Velosa, C. (2019). *Encuesta de habilidades al trabajo (ENHAT) 2017-2018: Causas y consecuencias de la brecha de habilidades en Perú* (Nota Técnica N.° IDB-TN-1652). Banco Interamericano de Desarrollo. [https://proyectos.inei.gob.pe/iinei/srienaho/Descarga/DocumentosMetodologicos/2017-18/6-ENHAT_2017-2018_Caus_y_consec_de_la_brecha_de_habil_en_Peru.pdf](https://proyectos.inei.gob.pe/iinei/srienaho/Descarga/DocumentosMetodologicos/2017-18/6-ENHAT_2017-2018_Caus_y_consec_de_la_brecha_de_habil_en_Peru.pdf)
* Organisation for Economic Co-operation and Development. (2024). *Bridging talent shortages in tech: Skills-first hiring, micro-credentials and inclusive outreach*. OECD Publishing. [https://doi.org/10.1787/f35da44f-en](https://doi.org/10.1787/f35da44f-en)
* Platzi. (s. f.). *Todo lo que debes saber sobre certificados en Platzi*. Recuperado el 8 de octubre de 2026, de [https://platzi.com/blog/todo-lo-que-debes-saber-sobre-certificados-en-platzi/](https://platzi.com/blog/todo-lo-que-debes-saber-sobre-certificados-en-platzi/)
* Pluralsight. (s. f.). *Skill IQ*. Recuperado el 8 de octubre de 2026, de [https://www.pluralsight.com/product/skill-iq](https://www.pluralsight.com/product/skill-iq)
* Rivas Cossio, R. E. (2023). La inadecuación ocupacional de jóvenes en Perú. *Políticas Públicas, 16*(2), 39–59. [https://doi.org/10.35588/pp.v16i2.6201](https://doi.org/10.35588/pp.v16i2.6201)
* roadmap.sh. (s. f.-a). *About roadmap.sh*. Recuperado el 8 de octubre de 2026, de [https://roadmap.sh/about](https://roadmap.sh/about)
* roadmap.sh. (s. f.-b). *roadmap.sh Premium*. Recuperado el 8 de octubre de 2026, de [https://roadmap.sh/premium](https://roadmap.sh/premium)
* World Economic Forum. (2025). *The future of jobs report 2025*. [https://www.weforum.org/publications/the-future-of-jobs-report-2025/](https://www.weforum.org/publications/the-future-of-jobs-report-2025/)

**Métodos y técnicas de ingeniería de software**

* Adzic, G. (2012). *Impact mapping: Making a big impact with software products and projects*. Provoking Thoughts.
* Brandolini, A. (2021). *Introducing EventStorming*. Leanpub. [https://leanpub.com/introducing_eventstorming](https://leanpub.com/introducing_eventstorming)
* Brown, S. (s. f.). *The C4 model for visualising software architecture*. Recuperado el 8 de octubre de 2026, de [https://c4model.com/](https://c4model.com/)
* Cohn, M. (2004). *User stories applied: For agile software development*. Addison-Wesley.
* Conventional Commits. (s. f.). *Conventional Commits 1.0.0*. Recuperado el 8 de octubre de 2026, de [https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)
* Driessen, V. (2010). *A successful Git branching model*. [https://nvie.com/posts/a-successful-git-branching-model/](https://nvie.com/posts/a-successful-git-branching-model/)
* Evans, E. (2003). *Domain-driven design: Tackling complexity in the heart of software*. Addison-Wesley.
* Gothelf, J., & Seiden, J. (2021). *Lean UX: Creating great products with agile teams* (3.ª ed.). O'Reilly Media.
* Hofer, S., & Schwentner, H. (2021). *Domain storytelling: A collaborative, visual, and agile way to build domain-driven software*. Addison-Wesley.
* Preston-Werner, T. (s. f.). *Semantic Versioning 2.0.0*. Recuperado el 8 de octubre de 2026, de [https://semver.org/](https://semver.org/)
* Schwaber, K., & Sutherland, J. (2020). *The Scrum guide*. [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html)
* Vernon, V. (2013). *Implementing domain-driven design*. Addison-Wesley.
* World Wide Web Consortium. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. [https://www.w3.org/TR/WCAG22/](https://www.w3.org/TR/WCAG22/)

**Lenguajes, frameworks y herramientas**

* Adoptium. (s. f.). *Eclipse Temurin*. Recuperado el 9 de octubre de 2026, de [https://adoptium.net/temurin/](https://adoptium.net/temurin/)
* Android Developers. (s. f.-a). *Google Play's billing system*. Recuperado el 8 de octubre de 2026, de [https://developer.android.com/google/play/billing](https://developer.android.com/google/play/billing)
* Android Developers. (s. f.-b). *Jetpack Compose*. Recuperado el 8 de octubre de 2026, de [https://developer.android.com/compose](https://developer.android.com/compose)
* Apache Software Foundation. (s. f.). *Apache Maven documentation*. Recuperado el 9 de octubre de 2026, de [https://maven.apache.org/guides/](https://maven.apache.org/guides/)
* AssertJ. (s. f.). *AssertJ documentation*. Recuperado el 9 de octubre de 2026, de [https://assertj.github.io/doc/](https://assertj.github.io/doc/)
* Cloudinary. (s. f.). *Cloudinary documentation*. Recuperado el 8 de octubre de 2026, de [https://cloudinary.com/documentation](https://cloudinary.com/documentation)
* Docker. (s. f.). *Docker docs*. Recuperado el 8 de octubre de 2026, de [https://docs.docker.com/](https://docs.docker.com/)
* Flutter. (s. f.). *Flutter documentation*. Recuperado el 8 de octubre de 2026, de [https://docs.flutter.dev/](https://docs.flutter.dev/)
* Google. (s. f.). *Material Design 3*. Recuperado el 8 de octubre de 2026, de [https://m3.material.io/](https://m3.material.io/)
* Google AI for Developers. (s. f.). *Gemini API documentation*. Recuperado el 8 de octubre de 2026, de [https://ai.google.dev/gemini-api/docs](https://ai.google.dev/gemini-api/docs)
* Google for Developers. (s. f.). *Text recognition v2 | ML Kit*. Recuperado el 8 de octubre de 2026, de [https://developers.google.com/ml-kit/vision/text-recognition/v2](https://developers.google.com/ml-kit/vision/text-recognition/v2)
* Google Play Console Help. (s. f.-a). *Understanding Google Play's Payments policy*. Recuperado el 9 de octubre de 2026, de [https://support.google.com/googleplay/android-developer/answer/9858738](https://support.google.com/googleplay/android-developer/answer/9858738)
* Google Play Console Help. (s. f.-b). *Understanding user choice billing on Google Play*. Recuperado el 9 de octubre de 2026, de [https://support.google.com/googleplay/android-developer/answer/13821247](https://support.google.com/googleplay/android-developer/answer/13821247)
* Hibernate. (s. f.). *Hibernate ORM documentation*. Recuperado el 9 de octubre de 2026, de [https://hibernate.org/orm/documentation/](https://hibernate.org/orm/documentation/)
* JUnit Team. (s. f.). *JUnit 5 user guide*. Recuperado el 9 de octubre de 2026, de [https://junit.org/junit5/docs/current/user-guide/](https://junit.org/junit5/docs/current/user-guide/)
* jwtk. (s. f.). *JJWT: Java JWT*. Recuperado el 9 de octubre de 2026, de [https://github.com/jwtk/jjwt](https://github.com/jwtk/jjwt)
* OpenAPI Initiative. (s. f.). *OpenAPI Specification*. Recuperado el 8 de octubre de 2026, de [https://spec.openapis.org/oas/latest.html](https://spec.openapis.org/oas/latest.html)
* Oracle. (s. f.). *Java SE 21 documentation*. Recuperado el 9 de octubre de 2026, de [https://docs.oracle.com/en/java/javase/21/](https://docs.oracle.com/en/java/javase/21/)
* PostgreSQL Global Development Group. (s. f.). *PostgreSQL documentation*. Recuperado el 8 de octubre de 2026, de [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)
* Render. (s. f.). *Render docs*. Recuperado el 8 de octubre de 2026, de [https://render.com/docs](https://render.com/docs)
* RevenueCat. (s. f.). *RevenueCat documentation*. Recuperado el 9 de octubre de 2026, de [https://www.revenuecat.com/docs](https://www.revenuecat.com/docs)
* Spring. (s. f.-a). *Spring Boot reference documentation*. Recuperado el 9 de octubre de 2026, de [https://docs.spring.io/spring-boot/](https://docs.spring.io/spring-boot/)
* Spring. (s. f.-b). *Spring Data JPA reference documentation*. Recuperado el 9 de octubre de 2026, de [https://docs.spring.io/spring-data/jpa/reference/](https://docs.spring.io/spring-data/jpa/reference/)
* Spring. (s. f.-c). *Spring Security reference documentation*. Recuperado el 9 de octubre de 2026, de [https://docs.spring.io/spring-security/reference/](https://docs.spring.io/spring-security/reference/)
* springdoc-openapi. (s. f.). *springdoc-openapi documentation*. Recuperado el 9 de octubre de 2026, de [https://springdoc.org/](https://springdoc.org/)
* Testcontainers. (s. f.). *Testcontainers for Java*. Recuperado el 9 de octubre de 2026, de [https://java.testcontainers.org/](https://java.testcontainers.org/)

# Anexos

* **Wireframes (Figma):** [https://www.figma.com/design/l6Z6APfbLoci4YMSaZkILK/Wireframes-camino-feliz?node-id=121-1250&t=91cAQ4Kz2gcFrsPc-1](https://www.figma.com/design/l6Z6APfbLoci4YMSaZkILK/Wireframes-camino-feliz?node-id=121-1250&t=91cAQ4Kz2gcFrsPc-1)

* **Miro:** [https://miro.com/welcomeonboard/K0ozbG1wZXpCVmZ5NTN5NnJnekhrZEZJc3lIdDVqbEtYRWdBY1hhOW5uY1lyYUE3a05hbE9iU3JsNkhFZTVsNExoRXZZNkFvazROOTBSWTYrMVozTEczbHovZEd6MU1XUFNQdEZvWlVKUDBzL3VRTTJFT0p5OXhsaEcrR0dLOEJBS2NFMDFkcUNFSnM0d3FEN050ekl3PT0hdjE=?share_link_id=729861756205 ](https://miro.com/welcomeonboard/K0ozbG1wZXpCVmZ5NTN5NnJnekhrZEZJc3lIdDVqbEtYRWdBY1hhOW5uY1lyYUE3a05hbE9iU3JsNkhFZTVsNExoRXZZNkFvazROOTBSWTYrMVozTEczbHovZEd6MU1XUFNQdEZvWlVKUDBzL3VRTTJFT0p5OXhsaEcrR0dLOEJBS2NFMDFkcUNFSnM0d3FEN050ekl3PT0hdjE=?share_link_id=729861756205 )

* **Enlace de Lucidchart para los Bounded Contexts:** [https://lucid.app/lucidspark/5af3ee09-0b57-4a3a-9e9d-a0973c7463ae/edit?viewport_loc=-4867%2C-5483%2C15325%2C7900%2C0_0&invitationId=inv_0faec9a9-417f-47ae-8bde-c6aa100ce397](https://lucid.app/lucidspark/5af3ee09-0b57-4a3a-9e9d-a0973c7463ae/edit?viewport_loc=-4867%2C-5483%2C15325%2C7900%2C0_0&invitationId=inv_0faec9a9-417f-47ae-8bde-c6aa100ce397)

* **Landing Page (GitHub Pages):**
[https://github.com/Aplicaciones-Dispositivos-Moviles](https://github.com/Aplicaciones-Dispositivos-Moviles)

link: [https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/](https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/)

**Papers:**
Alasmari, T. (2024). Reshaping vocational training: A study on the recognition of micro-credentials in job markets. Education + Training. [https://doi.org/10.1108/ET-07-2023-0282](https://doi.org/10.1108/ET-07-2023-0282)

Grevisse, C., Pavlou, M. A., & Schneider, J. (2024). Docimological quality analysis of LLM-generated multiple choice questions in computer science and medicine. SN Computer Science, 5. [https://doi.org/10.1007/s42979-024-02963-6](https://doi.org/10.1007/s42979-024-02963-6)

---

## Índice de Tablas

Tabla 1. *Perfiles de los integrantes del equipo*<br>
Tabla 2. *Análisis competitivo Landscape*<br>
Tabla 3. *Principales hallazgos de entrevistas a personas que quieren aprender*<br>
Tabla 4. *Principales hallazgos de entrevistas al segmento de personas que validan el conocimiento*<br>
Tabla 5. *Tareas y prioridades de las personas que quieren aprender*<br>
Tabla 6. *Tareas y prioridades del segmento de personas que validan el conocimiento*<br>
Tabla 7. *Ubiquitous Language de SkillSwap*<br>
Tabla 8. *Epics del proyecto*<br>
Tabla 9. *User Stories y Technical Stories del proyecto*<br>
Tabla 10. *Product Backlog*<br>
Tabla 11. *Contextos candidatos de SkillSwap*<br>
Tabla 12. *SEO Tags y Meta Tags del Landing Page*<br>
Tabla 13. *Elementos ASO de la aplicación móvil*<br>
Tabla 14. *Herramientas del entorno de desarrollo de software*<br>
Tabla 15. *Variables de entorno del backend*<br>
Tabla 16. *Sprint Planning 1*<br>
Tabla 17. *Leadership-and-Collaboration Matrix del Sprint 1*<br>
Tabla 18. *Sprint Backlog 1*<br>
Tabla 19. *Commits de desarrollo del backend en el Sprint 1*<br>
Tabla 20. *Commits de desarrollo del Landing Page*<br>
Tabla 21. *Pruebas de integración de la API y su trazabilidad con el Product Backlog*<br>
Tabla 22. *Pruebas unitarias y de integración por Bounded Context y capa*<br>
Tabla 23. *Commits del Sprint 1 que incorporan pruebas automatizadas*<br>
Tabla 24. *Endpoints documentados en el Sprint 1*<br>
Tabla 25. *Commits relacionados con la documentación de los Web Services*<br>

---

## Índice de Figuras

Figura 1. *Gráfico de contribuciones al repositorio del Project Report durante AV1*<br>
Figura 2. *Historial de commits en el repositorio del Project Report*<br>
Figura 3. *Gráfico de contribuciones al repositorio del Project Report durante TB1*<br>
Figura 4. *Historial de commits en el repositorio del Project Report durante TB1*<br>
Figura 5. *Lean UX Canvas (v2)*<br>
Figura 6. *Entrevista 1: Personas que quieren aprender*<br>
Figura 7. *Entrevista 2: Personas que quieren aprender*<br>
Figura 8. *Entrevista 3: Personas que quieren aprender*<br>
Figura 9. *Entrevista 1: Segmento Personas que validan el conocimiento*<br>
Figura 10. *Entrevista 2: Segmento Personas que validan el conocimiento*<br>
Figura 11. *Entrevista 3: Segmento Personas que validan el conocimiento*<br>
Figura 12. *Entrevista 4 Segmento Personas que validan el conocimiento*<br>
Figura 13. *Entrevista 5 Segmento Personas que validan el conocimiento*<br>
Figura 14. *Entrevista 6 Segmento Personas que validan el conocimiento*<br>
Figura 15. *User Persona - Personas que quieren aprender*<br>
Figura 16. *User Persona - Personas que validan el conocimiento*<br>
Figura 17. *User Journey Mapping – Personas que quieren aprender*<br>
Figura 18. *User Journey Mapping – Personas que validan el conocimiento*<br>
Figura 19. *Empathy Mapping - Personas que quieren aprender*<br>
Figura 20. *Empathy Mapping - Personas que validan el conocimiento*<br>
Figura 21. *As-Is Scenario Mapping – Personas que quieren aprender*<br>
Figura 22. *As-Is Scenario Mapping – Personas que validan el conocimiento*<br>
Figura 23. *To-Be Scenario Mapping – Personas que quieren aprender*<br>
Figura 24. *To-Be Scenario Mapping – Personas que validan el conocimiento*<br>
Figura 25. *Impact Map - Business Goal 1: Adopción y suscripción*<br>
Figura 26. *Impact Map - Business Goal 2: Validación práctica de habilidades*<br>
Figura 27. *Impact Map - Business Goal 3: Red de Verificadores*<br>
Figura 28. *Impact Map - Business Goal 4: Calidad y confianza del proceso*<br>
Figura 29. *Product Backlog de SkillSwap en Trello*<br>
Figura 30. *EventStorming, paso 1: Unstructured Exploration*<br>
Figura 31. *EventStorming, paso 2: Timelines (registro, suscripción y certificados)*<br>
Figura 32. *EventStorming, paso 2: Timelines (evaluación de los nodos)*<br>
Figura 33. *EventStorming, paso 2: Timelines (demostración final, certificación y nuevo Verificador)*<br>
Figura 34. *EventStorming, paso 3: Pain Points (registro, suscripción y certificados)*<br>
Figura 35. *EventStorming, paso 3: Pain Points (evaluación de los nodos)*<br>
Figura 36. *EventStorming, paso 3: Pain Points (demostración final, certificación y nuevo Verificador)*<br>
Figura 37. *EventStorming, paso 4: Pivotal Points (registro, suscripción y certificados)*<br>
Figura 38. *EventStorming, paso 4: Pivotal Points (evaluación de los nodos)*<br>
Figura 39. *EventStorming, paso 4: Pivotal Points (demostración final, certificación y nuevo Verificador)*<br>
Figura 40. *EventStorming, paso 5: Commands (registro, suscripción y certificados)*<br>
Figura 41. *EventStorming, paso 5: Commands (evaluación de los nodos)*<br>
Figura 42. *EventStorming, paso 5: Commands (demostración final, certificación y nuevo Verificador)*<br>
Figura 43. *EventStorming, paso 6: Policies (registro, suscripción y certificados)*<br>
Figura 44. *EventStorming, paso 6: Policies (evaluación de los nodos)*<br>
Figura 45. *EventStorming, paso 6: Policies (demostración final, certificación y nuevo Verificador)*<br>
Figura 46. *EventStorming, paso 7: Read Models (registro, suscripción y certificados)*<br>
Figura 47. *EventStorming, paso 7: Read Models (evaluación de los nodos)*<br>
Figura 48. *EventStorming, paso 7: Read Models (demostración final, certificación y nuevo Verificador)*<br>
Figura 49. *EventStorming, paso 8: External Systems (registro, suscripción y certificados)*<br>
Figura 50. *EventStorming, paso 8: External Systems (evaluación de los nodos)*<br>
Figura 51. *EventStorming, paso 8: External Systems (demostración final, certificación y nuevo Verificador)*<br>
Figura 52. *EventStorming, paso 9: Aggregates*<br>
Figura 53. *EventStorming, paso 10: Bounded Contexts*<br>
Figura 54. *Candidate Context Discovery, iteración 1: fases delimitadas por los eventos pivotales*<br>
Figura 55. *Candidate Context Discovery, iteración 2: línea de tiempo por contexto candidato*<br>
Figura 56. *Candidate Context Discovery, iteración 3: clasificación de los contextos por valor*<br>
Figura 57. *Domain Message Flow: Registro del Estudiante y paso al plan premium*<br>
Figura 58. *Domain Message Flow: Declaración del objetivo y generación de la ruta*<br>
Figura 59. *Domain Message Flow: Revisión de un entregable práctico aprobado*<br>
Figura 60. *Domain Message Flow: Reporte de una decisión revertida por Moderación*<br>
Figura 61. *Domain Message Flow: Demostración final y emisión de la certificación*<br>
Figura 62. *Domain Message Flow: Registro de un certificado sospechoso*<br>
Figura 63. *Bounded Context Canvas: Assessment & Peer Review*<br>
Figura 64. *Bounded Context Canvas: Learning Path Engine*<br>
Figura 65. *Bounded Context Canvas: Credential Verification*<br>
Figura 66. *Bounded Context Canvas: Reputation*<br>
Figura 67. *Bounded Context Canvas: Recognition & Incentives*<br>
Figura 68. *Bounded Context Canvas: Moderation & Disputes*<br>
Figura 69. *Bounded Context Canvas: Subscription & Billing*<br>
Figura 70. *Bounded Context Canvas: Identity & Access*<br>
Figura 71. *Context Mapping de SkillSwap*<br>
Figura 72. *C4 Model: Context Diagram*<br>
Figura 73. *C4 Model: Container Diagram*<br>
Figura 74. *C4 Model: Deployment Diagram*<br>
Figura 75. *C4 Model: Component Diagram del Bounded Context Identity & Access*<br>
Figura 76. *Diagrama de Clases UML del Domain Layer de Identity & Access*<br>
Figura 77. *Diagrama de Base de Datos del Bounded Context Identity & Access*<br>
Figura 78. *C4 Model: Component Diagram del Bounded Context Credential Verification*<br>
Figura 79. *Diagrama de Clases UML del Domain Layer de Credential Verification*<br>
Figura 80. *Diagrama de Base de Datos del Bounded Context Credential Verification*<br>
Figura 81. *C4 Model: Component Diagram del Bounded Context Learning Path Engine*<br>
Figura 82. *Diagrama de Clases UML del Domain Layer de Learning Path Engine*<br>
Figura 83. *Diagrama de Base de Datos del Bounded Context Learning Path Engine*<br>
Figura 84. *C4 Model: Component Diagram del Bounded Context Assessment & Peer Review*<br>
Figura 85. *Diagrama de Clases UML del Domain Layer de Assessment & Peer Review*<br>
Figura 86. *Diagrama de Base de Datos del Bounded Context Assessment & Peer Review*<br>
Figura 87. *C4 Model: Component Diagram del Bounded Context Reputation*<br>
Figura 88. *Diagrama de Clases UML del Domain Layer de Reputation*<br>
Figura 89. *Diagrama de Base de Datos del Bounded Context Reputation*<br>
Figura 90. *C4 Model: Component Diagram del Bounded Context Recognition & Incentives*<br>
Figura 91. *Diagrama de Clases UML del Domain Layer de Recognition & Incentives*<br>
Figura 92. *Diagrama de Base de Datos del Bounded Context Recognition & Incentives*<br>
Figura 93. *C4 Model: Component Diagram del Bounded Context Moderation & Disputes*<br>
Figura 94. *Diagrama de Clases UML del Domain Layer de Moderation & Disputes*<br>
Figura 95. *Diagrama de Base de Datos del Bounded Context Moderation & Disputes*<br>
Figura 96. *C4 Model: Component Diagram del Bounded Context Subscription & Billing*<br>
Figura 97. *Diagrama de Clases UML del Domain Layer de Subscription & Billing*<br>
Figura 98. *Diagrama de Base de Datos del Bounded Context Subscription & Billing*<br>
Figura 99. *Diagrama de Base de Datos completo de SkillSwap*<br>
Figura 100. *Diagrama de Clases UML completo de SkillSwap*<br>
Figura 101. *Style Guidelines de SkillSwap*<br>
Figura 102. *Wireframe del Landing Page de SkillSwap (Desktop Web Browser)*<br>
Figura 103. *Wireframe del Landing Page de SkillSwap (Mobile Web Browser)*<br>
Figura 104. *Mock-up del Landing Page de SkillSwap (escritorio)*<br>
Figura 105. *Mock-up del Landing Page de SkillSwap (versión responsive)*<br>
Figura 106. *Wireframes de las pantallas principales de la aplicación móvil*<br>
Figura 107. *Wireflow de registro de nuevo usuario*<br>
Figura 108. *Wireflow de suscripción mensual*<br>
Figura 109. *Wireflow de inicio de sesión y biometría*<br>
Figura 110. *Wireflow para declarar una meta de aprendizaje*<br>
Figura 111. *Wireflow para subir y validar un certificado*<br>
Figura 112. *Wireflow para rendir el quiz de un nodo*<br>
Figura 113. *Wireflow para recibir y resolver casos (Verificador)*<br>
Figura 114. *Mock-ups de la aplicación móvil · Estudiante*<br>
Figura 115. *Mock-ups de la aplicación móvil · Verificador*<br>
Figura 116. *User Flow para registrarse y activar el plan*<br>
Figura 117. *User Flow para declarar una meta y obtener la ruta*<br>
Figura 118. *User Flow para subir y validar un certificado*<br>
Figura 119. *User Flow para rendir el quiz de un nodo*<br>
Figura 120. *User Flow para recibir y resolver un caso*<br>
Figura 121. *Vista del prototipo navegable de SkillSwap en Figma*<br>
Figura 122. *Deployment Diagram de SkillSwap (C4 Model)*<br>
Figura 123. *Reunión de Sprint Planning 1*<br>
Figura 124. *Sprint Backlog 1 en Trello*<br>
Figura 125. *Registro con correo institucional*<br>
Figura 126. *Subida de un certificado y evaluación de riesgo*<br>
Figura 127. *Declaración de la meta y generación de la ruta*<br>
Figura 128. *Evaluación generada por IA para un nodo*<br>
Figura 129. *Ciclo de un caso de verificación*<br>
Figura 130. *SkillCredits acreditados al Verificador*<br>
Figura 131. *Video de ejecución del Sprint 1*<br>
Figura 132. *Documentación de los Web Services en Swagger*<br>
Figura 133. *Autorización con JWT en Swagger UI*<br>
Figura 134. *Servicio web desplegado en Render*<br>
Figura 135. *Logs del arranque en Render*<br>
Figura 136. *Dockerfile del backend*<br>
Figura 137. *Health check del backend en Render*<br>
Figura 138. *Landing Page publicado en GitHub Pages*<br>
Figura 139. *Historial de commits del repositorio SkillSwap-WebServices-Java durante el Sprint 1*<br>

## Anexo A. Enlaces de Acceso a la Solución

| Producto | Descripción | Enlace |
| :--- | :--- | :--- |
| **Landing Page — Sitio desplegado** | Sitio web estático de presentación del modelo de negocio Innovify (SkillSwap), publicado en GitHub Pages. | [https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/](https://aplicaciones-dispositivos-moviles.github.io/SkillSwap-LandingPage/) |
| **Landing Page — Repositorio** | Código fuente del Landing Page (HTML5, CSS3 y JavaScript). | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-LandingPage](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-LandingPage) |
| **Android Native Application** | Aplicación móvil nativa (Kotlin / Jetpack Compose) donde interactúan Estudiantes y Verificadores. | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp) |
| **Cross-Platform Application (Flutter)** | Aplicación móvil multiplataforma (Flutter / Dart, dirigida a Android). | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp-Flutter](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-MobileApp-Flutter) |
| **Prototipo y mock-ups (Figma)** | Archivo de diseño con el prototipo y los mock-ups de la aplicación móvil para los roles Estudiante y Verificador (Capítulo III). | [https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo?node-id=3-959](https://www.figma.com/design/KPBI1lj3uu2vLccOcJOFBG/Sin-t%C3%ADtulo?node-id=3-959) |
| **Backend — Swagger UI** | Documentación interactiva (OpenAPI) de los Web Services RESTful (Java 21 / Spring Boot), desplegados en Render. | [https://skillswap-webservices-java.onrender.com/swagger-ui/index.html](https://skillswap-webservices-java.onrender.com/swagger-ui/index.html) |
| **Backend — Repositorio** | Código fuente de los Web Services RESTful en Java / Spring Boot, organizados por Bounded Context (seis implementados en el Sprint 1). | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices-Java](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-WebServices-Java) |
| **Base de Datos** | Base de datos relacional única (PostgreSQL administrado en Render), compartida por los ocho Bounded Contexts. | Ver el Diagrama de Base de Datos completo de SkillSwap en la sección 2.6. |
| **Product Backlog (Trello)** | Tablero público del Product Backlog, organizado por Sprint. | [https://trello.com/b/sTMGwnPf/skillswap-product-backlog](https://trello.com/b/sTMGwnPf/skillswap-product-backlog) |
| **Project Report (GitHub)** | Repositorio del informe del proyecto. | [https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport](https://github.com/Aplicaciones-Dispositivos-Moviles/SkillSwap-ProjectReport) |
| **Video About-the-Team** | Video que resume el proceso de trabajo del equipo a lo largo del ciclo de vida del proyecto. | Pendiente (primera versión en AV2). |
| **Video About-the-Product** | Video promocional dirigido a visitantes de la Landing Page y usuarios de la aplicación. | Pendiente (primera versión en AV2). |

---

## Anexo B. Videos de Exposiciones

| Entrega | Características del video | Enlace del video |
| :--- | :--- | :--- |
| **AV1** | **Nombre del archivo:** upc-pre-202620-1acc0238-4948-Innovify-expo-av1.mp4 <br> **Duración:** | |
| **TB1** | **Nombre del archivo:** upc-pre-202620-1acc0238-4948-Innovify-expo-tb1.mp4 <br> **Duración:** | |
| **AV2** | **Nombre del archivo:** upc-pre-202620-1acc0238-4948-Innovify-expo-av2.mp4 <br> **Duración:** | |
| **TB2** | **Nombre del archivo:** upc-pre-202620-1acc0238-4948-Innovify-expo-tb2.mp4 <br> **Duración:** | |

<div style="page-break-after: always;"></div>

---

## Anexo C. Videos de la documentación

| Sección | Características del video | Sobre el contenido | Integración y entrega |
| :--- | :--- | :--- | :--- |
| **Needfinding Interviews** | Cantidad de videos: 1<br><br>Nomenclatura: upc-pre-202620-1acc0238-4948-Innovify-needfinding-tb1.mp4<br><br>Formato: .mp4<br><br>Duración: de 3 a 5 minutos de edición por entrevista. | Consolida todas las entrevistas a los segmentos objetivo, con títulos que indican el entrevistado, el segmento y la fecha de cada entrevista. | Video en el OneDrive del docente. Registro de cada entrevista en la sección 2.2.2. |
| **Prototype / Product Navigation** | Cantidad de videos: 1<br><br>Nomenclatura: upc-pre-202620-1acc0238-4948-Innovify-prototypenavigation-tb1.mp4<br><br>Formato: .mp4<br><br>Duración: de 3 a 5 minutos de edición por aplicación. | Demuestra el flujo de navegación del Landing Page y de la aplicación móvil, priorizando los user flows del core business. | Video en el OneDrive del docente. Referenciado en la sección 3.1.4.5. |
| **Validation Interviews** | Cantidad de videos: 1<br><br>Nomenclatura: upc-pre-202620-1acc0238-4948-Innovify-validation-av2.mp4<br><br>Formato: .mp4<br><br>Duración: de 3 a 5 minutos de edición por entrevista. | Consolida las sesiones de validación en las que usuarios de los segmentos objetivo interactúan con el Landing Page y la aplicación móvil y comparten sus observaciones. | Pendiente (a partir de AV2). |
| **About the Product** | Cantidad de videos: 1<br><br>Nomenclatura: upc-pre-202620-1acc0238-4948-Innovify-about-the-product-av2.mp4<br><br>Formato: .mp4<br><br>Duración: de 1 a 2 minutos. | Video promocional que resume el modelo de negocio, las características y beneficios del producto, con escenas de uso y al menos una opinión por segmento objetivo. | Pendiente (a partir de AV2). Se publicará en el OneDrive del docente y en YouTube, e irá incrustado en el Landing Page. |
| **About the Team** | Cantidad de videos: 1<br><br>Nomenclatura: upc-pre-202620-1acc0238-4948-Innovify-about-the-team-av2.mp4<br><br>Formato: .mp4<br><br>Duración: según el contenido (unos 5 minutos de retrospectiva y 1 minuto por testimonio). | Resume el proceso de trabajo del equipo con escenas de sesiones reales y narración, e incluye el testimonio de cada integrante sobre sus actividades y el logro del student outcome. | Pendiente (a partir de AV2). Se publicará en el OneDrive del docente y en YouTube, e irá incrustado en el Landing Page. |
