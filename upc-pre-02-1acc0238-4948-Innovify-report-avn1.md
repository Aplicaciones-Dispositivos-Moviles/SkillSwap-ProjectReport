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
| U20241D958 | Lopez Montalvo, Kevin Edu |
| U201724692 | Komatsu Dueñas, David |

</div>

<p align="center">
<strong>Período 202620</strong>
</p>

<p align="center">
Septiembre 2026
</p>

<div style="page-break-after: always;"></div>

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **v.01.Avn1** | 10/09/2026 | Alberca, V., Becerra, L., Lopez, K., Komatsu, D. | Creación del documento para el curso de Aplicaciones para Dispositivos Móviles (Avance 1). Se incluyeron las secciones de Presentación (Startup Profile, Lean UX), Requirements Development and Software Solution Design, Conclusiones y Bibliografía. Se adaptaron los requerimientos hacia una arquitectura móvil nativa/cross-platform. |

<div style="page-break-after: always;"></div>

---

## Project Report Collaboration Insights

En esta sección se indica el URL del repositorio utilizado para la elaboración colaborativa del Informe de Trabajo Final, así como las evidencias de participación de cada integrante del equipo durante el desarrollo de la entrega AV1.

**URL del repositorio del Project Report (GitHub):**
[ https://github.com/orgs/Aplicaciones-Moviles-SkillSwap/repositories ]( https://github.com/orgs/Aplicaciones-Moviles-SkillSwap/repositories )

### AV1

Durante el desarrollo de la entrega AV1, el equipo distribuyó la elaboración del informe asignando capítulos y secciones específicas a cada integrante según sus áreas de responsabilidad. Cada miembro realizó sus aportes directamente en el repositorio de GitHub mediante commits en ramas individuales, siguiendo la convención de Conventional Commits y GitFlow. Todos los integrantes participaron activamente en la redacción de secciones del informe en formato Markdown, asegurando coherencia y calidad en el contenido entregado.

*(Nota: Insertar aquí las capturas de los analíticos de colaboración, branches y commits de GitHub correspondientes al avance 1).*

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET EAC - Student Outcome 7:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **La capacidad de adquirir y aplicar nuevos conocimientos...** | **Alberca Saavedra Víctor Manuel (AV1):** Lideré la investigación de la tecnología externa (SDK de videollamadas) a integrar en el proyecto móvil, evaluando sus requisitos técnicos y adaptándolos a la arquitectura móvil nativa. Participé en el diseño estratégico de los Bounded Contexts. | El equipo reconoce la necesidad del aprendizaje permanente al investigar e integrar de manera autónoma tecnologías no vistas en clase, como SDKs externos y persistencia local en dispositivos, aplicando conceptos de Domain-Driven Design al entorno móvil. |
| | **Becerra Ninahuanca Luis Angel (AV1):** Investigué patrones de diseño UI/UX específicos para aplicaciones móviles multiplataforma y colaboré en el análisis competitivo y el diseño de entrevistas enfocadas en la experiencia de movilidad de los estudiantes. | El equipo actualiza sus conocimientos sobre buenas prácticas de desarrollo móvil y requerimientos de usuarios para construir soluciones funcionales y pertinentes en dispositivos móviles. |
| | **Lopez Montalvo Kevin Edu (AV1):** Documenté el proceso Lean UX y apliqué el aprendizaje sobre persistencia de datos locales en dispositivos para el diseño de los requisitos, estructurando las User Stories bajo un enfoque Mobile-First. | El equipo aplica estrategias de aprendizaje eficaces para incorporar nuevos requerimientos técnicos a la solución de software, demostrando capacidad de adaptación. |
| | **Komatsu Dueñas, David (AV1):** Evalué diferentes estrategias de integración de servicios RESTful y modelé el flujo de mensajes entre los Bounded Contexts aplicando Domain Storytelling adaptado al consumo de APIs desde aplicaciones móviles. | Se evidencia la capacidad de asimilar nuevos paradigmas de comunicación y arquitectura de software, esenciales para el desarrollo profesional. |

<div style="page-break-after: always;"></div>

## Objetivos SMART

*   **Alberca Saavedra Víctor Manuel:** Completar un curso de especialización en arquitecturas móviles (Kotlin/Swift) para diciembre de 2026, logrando aplicar al menos 3 patrones de diseño avanzados en proyectos personales.
*   **Becerra Ninahuanca Luis Angel:** Obtener una certificación en integración de servicios Cloud para aplicaciones móviles en los próximos 6 meses, mejorando la seguridad y reduciendo la latencia en el consumo de APIs.
*   **Lopez Montalvo Kevin Edu:** Dominar herramientas de testing automatizado para aplicaciones multiplataforma (ej. Appium) antes de culminar la carrera, logrando automatizar el 80% de los flujos críticos de la aplicación.
*   **Komatsu Dueñas, David:** Desarrollar habilidades de liderazgo técnico gestionando al menos 2 proyectos de software open source orientados a móviles en GitHub durante el próximo año, implementando GitFlow y CI/CD de forma efectiva.

---

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
**Innovify** es una startup cuyo propósito es reducir la deserción académica conectando a estudiantes universitarios para que compartan conocimientos a través de sesiones de tutoría en una aplicación móvil. La plataforma facilita un aprendizaje sincrónico (videollamadas nativas) y asincrónico (recursos locales e integración en la nube), bajo un modelo B2C (donaciones voluntarias) y B2B (Dashboard Analítico institucional). 

El sistema asegura la identidad mediante correos institucionales (`.edu.pe`) e integra **almacenamiento local** para preferencias de estudio y caché de mensajes, acceso a un **recurso interno del dispositivo** (cámara/micrófono para tutorías en vivo), integración con nuestro **servicio RESTful** de desarrollo interno, y acceso a un **servicio externo de terceros** (SDK para videollamadas o pasarela de pagos). Todo fundamentado bajo una arquitectura orientada al dominio (Domain-Driven Design).

### 1.1.2. Perfiles de integrantes del equipo

<div align="center">

| Foto | Integrante | Carrera | Descripción |
| :---: | :--- | :--- | :--- |
| *(Foto)* | **Alberca Saavedra, Víctor Manuel**<br>(U201924127) | Ingeniería de Software | Aporta conocimientos sólidos en arquitectura de software, backend y bases de datos. Contribuye con liderazgo técnico y organización del equipo para la transición al desarrollo móvil. |
| *(Foto)* | **Becerra Ninahuanca, Luis Angel**<br>(U20231C792) | Ingeniería de Software | Especialista en lógica de negocio, integración de servicios y diseño de interfaces limpias. Aportará al diseño de la aplicación móvil y la Landing Page del modelo de negocio. |
| *(Foto)* | **Lopez Montalvo, Kevin Edu**<br>(U20241D958) | Ingeniería de Software | Aporta conocimientos en diseño móvil, UX/UI y metodologías ágiles. Se enfocará en la investigación aplicada y la creación de prototipos técnicos móviles. |
| *(Foto)* | **Komatsu Dueñas, David**<br>(U201724692) | Ingeniería de Software | Enfocado en investigación tecnológica, análisis de datos y control de calidad. Aportará con habilidades de comunicación asertiva y experiencia en levantamiento de requerimientos. |

</div>

<br>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática
En el Perú, el fracaso académico y la deserción universitaria afectan a miles de estudiantes. Según el MINEDU (2021), la tasa de interrupción de estudios en universidades licenciadas llegó a 11.5% en el ciclo 2021-1, siendo Lima una de las regiones más afectadas con 12.4%.

Un problema subyacente y desatendido es el **aislamiento del conocimiento**. Cada universidad funciona como una isla académica. Actualmente, no existe una aplicación móvil formal, segura y multiplataforma que conecte de manera inmediata y verificada a un estudiante que necesita ayuda con un par que domina esa área. Los alumnos se ven limitados a su círculo cercano o a grupos informales en redes sociales que carecen de seguridad institucional, lo que genera fricción al momento de coordinar desde sus smartphones.

*(Nota: En el documento final se expandirá la técnica de las 5W y 2H enfocada en el uso de dispositivos móviles).*

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
* The current state of **la educación colaborativa universitaria en Perú** has focused mainly on **estudiantes compartiendo documentos de forma aislada en plataformas web, o coordinando informalmente por WhatsApp sin garantías de calidad ni validación académica**.
* What existing products/services fail to address is **la necesidad de una conexión inmediata, segura y validada institucionalmente directamente desde los dispositivos móviles, que ofrezca tutorías en tiempo real y recompense económicamente el esfuerzo del tutor**.
* Our product/service will address this gap by **ofreciendo una aplicación móvil nativa/multiplataforma basada en Domain-Driven Design, que integre videollamadas, chat asíncrono y donaciones, asegurando la identidad mediante correos institucionales (.edu.pe)**.
* Our initial focus will be **estudiantes universitarios de pregrado de Lima y provincias clave, tanto los que buscan mejorar sus notas (Aprendices) como los que desean monetizar sus conocimientos (Tutores) mediante su teléfono**.
* We'll know we are successful when we see **una adopción continua de la app móvil, evidenciada por un aumento del 40% mensual en tutorías completadas y donaciones procesadas dentro del entorno móvil durante los primeros 6 meses**.

#### 1.2.2.2. Lean UX Assumptions
*   **Business Assumptions:** Creemos que el cobro del 5% de comisión por donación mediante pasarelas de pago integradas en la app hará que el modelo sea financieramente sostenible.
*   **Business Outcome Assumptions:** El éxito se medirá por la cantidad de sesiones de videollamada completadas íntegramente en la aplicación móvil, reduciendo la dependencia de enlaces externos.
*   **User Assumptions:** Nuestros usuarios son "móviles-nativos"; prefieren buscar tutores, coordinar, estudiar y realizar transferencias directamente desde sus smartphones por conveniencia y rapidez.
*   **User Outcome Assumptions:** Los aprendices mejorarán su rendimiento académico al tener ayuda en su bolsillo; los tutores generarán ingresos y desarrollarán habilidades pedagógicas.
*   **Feature Assumptions:** El soporte de notificaciones *push*, el acceso a la cámara/micrófono del dispositivo y el almacenamiento local de sesiones recientes son características críticas para la retención del usuario.

#### 1.2.2.3. Lean UX Hypothesis Statements
* We believe we will achieve **alta adopción, retención y confianza por parte de los usuarios**
* If **estudiantes universitarios (Aprendices y Tutores)**
* Attain **una experiencia fluida, rápida y segura para coordinar y realizar clases desde cualquier lugar**
* With **una aplicación móvil nativa/multiplataforma que integre notificaciones push, videollamadas utilizando APIs de terceros, almacenamiento local para acceso offline parcial y validación automática de identidad (.edu.pe)**.

#### 1.2.2.4. Lean UX Canvas
*(Nota: Insertar imagen del Lean UX Canvas adaptado a la solución móvil de SkillSwap).*

## 1.3. Segmentos objetivo

1.  **Estudiantes que quieran aprender (Aprendices):** Universitarios (18-25 años) que enfrentan dificultades académicas. Son altamente dependientes de sus dispositivos móviles para consumir contenido rápido. Buscan ayuda inmediata y verificada sin tener que encender una computadora.
2.  **Estudiantes que quieran enseñar (Tutores):** Universitarios en ciclos intermedios/avanzados con alto dominio de materias. Buscan monetizar sus conocimientos y valoran la flexibilidad de gestionar sus solicitudes de tutoría, horarios y billetera virtual directamente desde su celular mediante notificaciones en tiempo real.
3.  **Coordinador Institucional:** Personal universitario (30-55 años) interesado en acceder a un Dashboard (Web) con métricas de rendimiento y prevención de deserción, garantizando la integridad de la red.

---

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores

### 2.1.1. Análisis competitivo
*   **uDocz (Competidor Directo):** Plataforma web masiva centrada en el intercambio asíncrono de documentos (resúmenes, apuntes). No ofrece tutorías síncronas integradas en aplicaciones móviles.
*   **Knack (Competidor Directo):** Red de tutoría intra-universitaria. Aunque robusta, a menudo se limita a una sola universidad y sus procesos pueden ser burocráticos.
*   **GoPeer (Competidor Indirecto):** Universitarios enseñando a escolares. Su modelo y segmento de mercado (K-12) difiere del enfoque peer-to-peer universitario de Innovify.

### 2.1.2. Estrategias y tácticas frente a competidores
*   **Fuerte enfoque "Mobile-First":** A diferencia de uDocz que es principalmente web-based para lectura de PDFs, SkillSwap se enfocará en la inmediatez de la aplicación móvil, permitiendo coordinar y ejecutar la videollamada desde el smartphone.
*   **Networking Interuniversitario Valido:** Frente a modelos cerrados, Innovify utilizará validación automática por dominios `.edu.pe` para crear una red confiable a nivel nacional.
*   **Recompensa Económica Ágil:** Integración de SDKs de pago directamente en el dispositivo móvil para facilitar donaciones de un solo toque al finalizar la sesión.

## 2.2. Entrevistas
*(Nota: Documentar el diseño de las entrevistas, el registro en video y los análisis de características objetivas/subjetivas, enfocando las preguntas en el uso de smartphones, la comodidad de estudiar desde el celular y la disposición a usar pasarelas de pago móviles).*

## 2.3. Needfinding
*(Nota: Incluir en esta sección los User Personas actualizados, el User Task Matrix priorizando tareas móviles, el User Journey Mapping As-Is, el Empathy Mapping, el reporte del Big Picture EventStorming y el Ubiquitous Language en inglés).*

## 2.4. Requirements specification

### 2.4.1. User Stories
*(Nota: Adaptar la tabla de User Stories previa para incluir los requisitos del curso: persistencia local, acceso a hardware, consumo de API propia y SDK externo).*

**Ejemplos de User Stories clave para el entorno móvil:**
*   **US_Mobile01 (Permisos de Dispositivo):** *As a user, I want the app to request camera and microphone permissions before joining a session, so that I can securely broadcast my video and audio during the live tutoring.*
*   **US_Mobile02 (Almacenamiento Local):** *As a Learner, I want the app to locally store my search preferences and recent chat history using SQLite/Room/CoreData, so that the app loads faster and I can review messages even with a poor internet connection.*
*   **US_Mobile03 (Consumo SDK Externo):** *As a Tutor, I want to initiate a live video call directly within the app using an integrated third-party SDK (e.g., Agora or Jitsi), so that I don't have to share external links with the learner.*
*   **Spike Story (Investigación):** *Investigate and prototype the integration of the external Video SDK into the native mobile architecture, evaluating performance, battery consumption, and necessary device permissions.*

### 2.4.2. Impact Mapping
*(Nota: Insertar los diagramas de Impact Mapping conectando los Business Goals con los User Personas y las funcionalidades móviles).*

### 2.4.3. Product Backlog
*(Nota: Insertar la tabla del Product Backlog priorizado, estimando los Story Points de las historias adaptadas al desarrollo móvil).*

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming
*(Nota: Documentar las fases de Candidate Context Discovery y Domain Message Flows Modeling realizadas por el equipo).*

### 2.5.2. Context Mapping
*(Nota: Incluir el diagrama que muestra las relaciones entre los Bounded Contexts: Identity & Access, Workspace, Learning & Assessment, Reputation, Payments & Wallet, y Moderation).*

### 2.5.3. Software Architecture
**Software Architecture Context Level Diagram:**
Muestra la interacción de los usuarios (Aprendiz, Tutor, Coordinador) con el sistema central de SkillSwap y los servicios externos de terceros (SDK de videollamadas, Pasarela de Pagos, Servicio de Correos).

**Software Architecture Container Level Diagram:**
Detalla la estructura de contenedores:
1.  **Mobile Application (Native/Cross-Platform):** La interfaz principal para estudiantes, desarrollada con soporte de almacenamiento local y acceso a hardware.
2.  **Web Application (Landing Page & Admin Dashboard):** Sitio web estático para la presentación del negocio y panel SPA para los coordinadores.
3.  **API Gateway / RESTful Web Services:** El backend desarrollado internamente que orquesta la lógica de negocio.
4.  **Database:** Repositorio central de información.

**Software Architecture Deployment Diagram:**
Muestra cómo la aplicación móvil se despliega en los dispositivos físicos de los usuarios (iOS/Android), el Landing Page en un servicio de hosting estático, y el backend junto con la base de datos en una infraestructura Cloud.

## 2.6. Tactical-Level Domain-Driven Design
*(Nota: Por cada Bounded Context se definirán las capas tácticas: Domain Layer, Interface Layer, Application Layer, Infrastructure Layer. Se incluirán los C4 Component Diagrams, UML Class Diagrams y el Database Design Diagram adaptados para soportar los flujos de la aplicación móvil).*

---

# Conclusiones
*   La adaptación del modelo de negocio de SkillSwap hacia una aplicación móvil nativa/multiplataforma responde directamente a la necesidad de inmediatez y accesibilidad de los estudiantes universitarios.
*   La investigación confirma que la integración de herramientas de videollamada y pasarelas de pago dentro de la misma aplicación, junto con el almacenamiento local, reducirá la fricción actual de usar herramientas fragmentadas.
*   La arquitectura basada en Domain-Driven Design provee una estructura robusta para integrar de manera segura los servicios RESTful internos y los SDKs de terceros requeridos para el aprendizaje sincrónico en dispositivos móviles.

# Bibliografía
*(Nota: Insertar referencias en formato APA 7, asegurando incluir un mínimo de 4 papers académicos Q1/Q2 de los últimos dos años relacionados con educación y desarrollo de aplicaciones móviles).*

# Anexos
*(Nota: Insertar cuadros, matrices extensas de entrevistas o diagramas adicionales requeridos).*
**probando a er**