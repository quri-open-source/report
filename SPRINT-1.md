### 5.2.1. Sprint 1  

La implementación de la landing page de la plataforma Quri, estableciendo la presencia inicial y los puntos de contacto clave para los usuarios. El trabajo abarcó desde la estructura y el diseño visual hasta funcionalidades esenciales como la responsividad, internacionalización y accesibilidad. A continuación, se detallan la planificación, el backlog ejecutado, la evidencia de desarrollo y los aspectos de colaboración.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe-2SVfhMg88oDtMO_3QYWOO5uSdwJqhAP4-goRu09WZLItrz6fQridhrQKTKHOgDDmlhN9f-Uew18B1LujBxl5xHQ-rptqsELMORMVVwgpLSV40i9ytpJQr-6IfYxr6SCXCxbV?key=wLsuErVgqDz-qczrBI4kMctR)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdL9rdlqw1DW-dBuqIzMn-OjuMEsp3FtlvaYD47HOj8Xu0GnvDfl4Qy0ewUQepBKVET_sDQRPJL0K-YSsYP5ToF7jyxV1RbtstVnkuWcbX13-0UeJHE8CXSNsgY1iQx316dsHV3og?key=wLsuErVgqDz-qczrBI4kMctR)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXftU8ULy-Dv8cfDrLA9rdzxg1U7661kBBQXBlhCCJpOlA7KD6tM1zyrCbxkNYoEo-ZnNpa2fTy1ZljQXkroVefiKKiWppycJyL3jAeBf2x-2xr-h-xzT6QnK5waEW0cx6I9xqDy?key=wLsuErVgqDz-qczrBI4kMctR)

#### 5.2.1.1. Sprint Planning 1

El 31 de marzo de 2025, el equipo de QURI se reunió virtualmente a través de Google Meet para dar inicio al Sprint 1, la primera iteración enfocada en establecer las bases de la plataforma. Bajo la coordinación de Dante Alemán y con la participación de Jonatan Ariel Acuña Corahua, Fabrizio Contreras Peralta, Neil Curipaco Huayllani y Renzo Luque Minaya, revisamos el backlog, definimos el objetivo principal y acordamos las historias de usuario a abordar. Con un claro enfoque en la navegación accesible y coherente (header, footer y rutas clave), establecimos criterios de aceptación, validamos estimaciones que sumaron 118 puntos de historia y aseguramos el compromiso de todos para cumplir con la meta de ofrecer una experiencia inclusiva y fluida para nuestros usuarios.

| Sprint #                        | 1                                                            |
| ------------------------------- | ------------------------------------------------------------ |
| Sprint Planning Background      |                                                              |
| Date                            | March 31, 2025                                               |
| Time                            | 10:00 AM                                                     |
| Location                        | Google Meet                                                  |
| Prepared By                     | Dante Alemán                                                 |
| Attendees (to planning meeting) | Jonatan Ariel Acuña Corahua, Dante Mateo Aleman Romano, Fabrizio Alessandro Contreras Peralta, Neil Aldrin Wilhelm Curipaco Huayllani, Renzo Andres Luque Minaya |
| Sprint Goal & User Stories      |                                                              |
| Sprint 1 Goal                   | Our focus is on delivering an accessible and consistent navigation system including header, footer, and key routes.We believe it delivers a smoother and more inclusive browsing experience for end users.This will be confirmed when users can navigate through the main areas of the platform using visual and assistive technologies (e.g., screen readers, keyboard navigation). |
| Sprint 1 Velocity               | 148                                                          |
| Sum of Story Points             | 148                                                          |

#### 5.2.1.2. Aspect Leaders and Collaborators

En esta sección se presentan los principales aspectos funcionales considerados durante el Sprint 1 del desarrollo de la plataforma Quri. Cada aspecto corresponde a un subconjunto relevante del alcance funcional de la solución, tales como componentes de la interfaz (header, footer), características técnicas (internacionalización, accesibilidad), o elementos visuales y estructurales (carousel, diseño responsivo).

Para cada aspecto, se ha identificado a un responsable principal —denominado **Líder (L)**—, quien asumió el liderazgo técnico o de ejecución. Asimismo, se reconoce como **Colaborador (C)** a aquellos miembros del equipo que participaron activamente en la implementación, revisión o soporte de dicho aspecto.

La Matriz LACX (Leadership and Collaboration Matrix) permite visualizar de manera clara y estructurada la distribución de responsabilidades dentro del equipo, promoviendo la trazabilidad del trabajo colaborativo realizado durante el Sprint.

A continuación, se presentan las tablas con los aspectos definidos y los roles asignados.

| **Team Member (Last Name, First Name)** | **GitHub Username** | **LI** | **RD** | **VP** | **NG** | **Ed** | **Ac** | **FQ** | **Tm** | **SM** | **GC** |
| --------------------------------------- | ------------------- | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Jonatan Ariel, Acuña Corahua            | JonatanFD           | L      |        | C      | C      | C      | C      |        | C      | C      |        |
| Luque Minaya, Renzo Andres              | renzoluquem         | C      | C      | L      | C      | C      | C      | C      | C      | C      | C      |
| Dante Mateo, Aleman Romano              | Matteo              |        | L      | C      | C      | L      |        |        | L      |        |        |
| Fabrizio Alessandro, Contreras Peralta  | Fabrizio Contreras  | C      | C      | C      |        |        |        | L      |        |        | L      |
| Neil Aldrin Wilhelm, Curipaco Huayllani | Neilcuri            |        |        | C      | L      |        | L      |        |        | L      |        |

**Nota.** LI = Language & Internationalization, RD = Responsive & Mobile Design, VP = Value Proposition & Company Info, Ng = Navigation: Header & Footer, Ed = Editor Access & Redirection, Ac = Accessibility (ARIA & Alt), FQ = FAQ & Legal Content, Tm = Team & Social Media Integration, SM = SEO & Meta, GC = Gallery & Carousel.

#### 5.2.1.3. Sprint Backlog 1

El presente Sprint se centra en establecer la base funcional y visual de la plataforma web de QURI, garantizando una primera versión navegable, multilingüe, accesible y preparada para futuras extensiones. El objetivo principal del Sprint 1 es construir una landing page responsive que integre los elementos principales de navegación (header y footer), funcionalidad de cambio de idioma, presentación del equipo y propuesta de valor, asegurando también el cumplimiento de criterios de accesibilidad (etiquetas ARIA, navegación asistida).

 A continuación, se presenta la tabla de control de estado del Sprint 1, la cual detalla los User Stories asignados, sus respectivas tareas (Work Items), descripciones funcionales, estimaciones en horas, responsables y estado actual.

| User Story Id | User Story Title                                            | Task Id | Task Title                                    | Description                                                  | Estimation (Hours) | Assigned To | Status |
| ------------- | ----------------------------------------------------------- | ------- | --------------------------------------------- | ------------------------------------------------------------ | ------------------ | ----------- | ------ |
| US06          | Explore information about the company                       | 6       | Add About Us section                          | Display company background and mission in About section.     | 5                  | Fabrizio    | Done   |
| US07          | Redirect to the editor from the Landing Page                | 7       | Enable editor access from CTA                 | Redirect user to editor when clicking 'Start Designing'.     | 5                  | Mateo       | Done   |
| US08          | Configure navigation from the Landing Page to the editor    | 8       | Implement routing logic to editor             | Ensure smooth redirection and route handling to editor page. | 3                  | Mateo       | Done   |
| US09          | Display team information                                    | 9       | Show team member details                      | Add section with names, roles, and photos of team.           | 3                  | Neil        | Done   |
| US10          | Consult frequently asked questions                          | 10      | Design and display FAQ section                | Display and expand common service questions for user.        | 3                  | Fabrizio    | Done   |
| US11          | Implement ARIA tags for accessible navigation               | 11      | Add ARIA roles and labels                     | Enhance accessibility with ARIA attributes for navigation and content. | 5                  | Neil        | Done   |
| US12          | Access image descriptions for accessible navigation         | 12      | Add image alt descriptions                    | Include meaningful alt text and skip decorative images.      | 5                  | Neil        | Done   |
| US13          | Browse social networks                                      | 13      | Display social media icons                    | Show social media links in footer or section.                | 5                  | Neil        | Done   |
| US14          | Implement social media access points                        | 14      | Implement icon metadata and ARIA labels       | Add social links with metadata and accessibility labels.     | 5                  | Neil        | Done   |
| US15          | Implement custom SEO with robots                            | 15      | Create and configure robots.txt               | Enable indexing control with robots.txt file.                | 5                  | Mateo       | Done   |
| US16          | Navigate between sections from the header                   | 16      | Header links scroll or route to sections      | Enable section navigation from header items.                 | 8                  | Neil        | Done   |
| US17          | Implement header with navigation links                      | 17      | Add header with 6 accessible links            | Render QURI, FAQ, About, Team, Join, Login with accessibility. | 5                  | Neil        | Done   |
| US18          | Visualize the header visible while scrolling                | 18      | Ensure persistent header visibility           | Keep header visible while user scrolls page.                 | 8                  | Neil        | Done   |
| US19          | Set the header as sticky on top                             | 19      | Apply sticky positioning and margin fixes     | Keep header fixed using sticky layout.                       | 8                  | NCeil       | Done   |
| US20          | Visually distinguish header options                         | 20      | Style header links for clarity                | Use visual distinction and active state styles.              | 5                  | Neil        | Done   |
| US21          | Apply consistent styles to header links                     | 21      | Apply unified header link styles              | Ensure consistent font, spacing and hierarchy in nav links.  | 8                  | Neil        | Done   |
| US22          | View inspiring t-shirt examples                             | 22      | Add image gallery of designed shirts          | Display at least 3 examples of shirts built on platform.     | 5                  | Renzo       | Done   |
| US23          | Implement visual carousel of custom layouts                 | 23      | Develop t-shirt carousel                      | Create functional carousel for showcasing designs.           | 3                  | Fabrizio    | Done   |
| US24          | Access key sections from the footer                         | 24      | Footer nav to top sections                    | Add footer links to main platform sections.                  | 5                  | Renzo       | Done   |
| US25          | Implement bottom navigation in the footer                   | 25      | Add footer links to Community, About, Contact | Persistent access from footer to community and info pages.   | 3                  | Renzo       | Done   |
| US26          | Invite registration from anywhere on the page               | 26      | Add persistent registration CTA               | Ensure join CTA is always accessible.                        | 5                  | Renzo       | Done   |
| US27          | Show text with link to login and registration in the footer | 27      | Add static login/signup text in footer        | Add footer text with links to /login and /signup.            | 3                  | Renzo       | Done   |
| US28          | Show geographic location of the company                     | 28      | Display location on About section             | Indicate Lima, PE in company info section.                   | 3                  | Mateo       | Done   |
| US29          | Include geographical headquarters visible in the footer     | 29      | Show LIMA, PE in footer                       | Display headquarters in footer without obstructing content.  | 2                  | Fabrizio    | Done   |
| US30          | Access the privacy policy and legal conditions              | 30      | Implement legal access from footer            | Show Privacy Policy and Terms on request.                    | 2                  | Jonatan     | Done   |
| US31          | Link to legal documents from the footer                     | 31      | Add footer links to legal docs                | Label and route links to privacy and terms info.             | 3                  | Neil        | Done   |

 

#### 5.2.1.4. Development Evidence for Sprint Review

A continuación se presenta un registro detallado de los commits realizados en la rama develop del repositorio quri-open-source/landing-page durante el Sprint 1. Cada entrada incluye el identificador de commit, el mensaje descriptivo y la fecha de consolidación, mostrando la evolución de la estructura HTML inicial, los estilos responsivos, la inclusión de activos visuales, la implementación de i18n y los componentes clave (FAQ, equipo, carrusel). Este historial ilustra cómo el equipo transformó paso a paso la landing page, desde su esqueleto básico hasta una experiencia completa y accesible.

| Repository                                                   | Branch                                     | Commit Id | Commit Message                                               | Committed on (Date) |
| ------------------------------------------------------------ | ------------------------------------------ | --------- | ------------------------------------------------------------ | ------------------- |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | eb64cd1   | Feat: Add initial HTML structure for Quri landing page       | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 02e3826   | feat(css): add responsive support and improve general styles | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | ace0104   | feat(css): add base styles for carousel component            | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 87679b2   | Merge pull request #1 from quri-open-source/feat/style-carousel | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/style-faq            | ec01462   | feat(css): add base styles for faq component                 | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | a81517a   | Merge pull request #2 from quri-open-source/feat/style-faq   | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/fix/style-faq             | 186c2f9   | feat(css): add styles for contact section and responsive adjustments | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 1c556a9   | Merge pull request #3 from quri-open-source/fix/style-faq    | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/fix/style-carousel        | 24961a6   | style(css): refactor carousel styles for improved readability and organization | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 9263102   | Merge pull request #4 from quri-open-source/fix/style-carousel | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-about-page       | d440822   | feat(html): add about page with structured content and navigation | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | e38370a   | Merge pull request #5 from quri-open-source/feat/add-about-page | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-about-styles     | 00d309b   | feat(css): add styles for about page layout and responsiveness | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 135cb7c   | Merge pull request #6 from quri-open-source/feat/add-about-styles | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-hero-assets      | 0c32338   | feat(assets): add hero images for enhanced visual content    | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 6471c02   | Merge pull request #7 from quri-open-source/feat/add-hero-assets | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-features-assets  | 645b338   | feat(assets): add feature images for enhanced visual presentation | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 5.70E+08  | Merge pull request #8 from quri-open-source/feat/add-features-assets | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-team-page        | bbd8e0e   | feat(team): add team page with member profiles and descriptions | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-team-page        | a02c38c   | feat(team): create team CSS styles for layout and member presentation | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | c88e348   | Merge pull request #9 from quri-open-source/feat/add-team-page | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-i18n-about-page  | dcffc885  | feat(i18n): add English localization for about section       | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-i18n-about-page  | 4b053e3   | feat(i18n): add Spanish localization for about section       | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | be882c0   | Merge pull request #10 from quri-open-source/feat/add-i18n-about-page | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-main-assets      | d549e3e   | feat(assets): add our story image                            | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-main-assets      | 30d461a   | feat(assets): add Quri logo image                            | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-main-assets      | 680a52d   | feat(assets): add "What We Offer" image                      | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 71b833f   | Merge pull request #11 from quri-open-source/feat/add-main-assets | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-faq-page         | 9089425   | feat(faq): add FAQ page with common questions and contact information | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-faq-page         | c8c5010   | feat(styles): add main CSS styles for layout and responsive design | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 199c056   | Merge pull request #12 from quri-open-source/feat/add-faq-page | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-js-animations    | 63d4c38   | feat(carousel): implement carousel functionality with slide navigation | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 13d7947   | Merge pull request #13 from quri-open-source/feat/add-js-animations | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-i18n-js-logic    | a7775c8   | feat(i18n): add internationalization support with language toggle functionality | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feat/add-i18n-js-logic    | b18cd60   | feat(i18n): add English and Spanish translations for FAQ and team sections | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 0b52fdc   | Merge pull request #14 from quri-open-source/feat/add-i18n-js-logic | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | quri-open-source/feature/style-about-image | e82477b   | feat(styles): enhance image responsiveness and center align history section | May 12, 2025        |
| [github.com/quri-open-source/landing-page](http://github.com/quri-open-source/landing-page) | develop                                    | 201fff0   | Merge pull request #15 from quri-open-source/feature/style-about-image | May 12, 2025        |

Durante el Sprint 1, se crearon y utilizaron múltiples ramas de desarrollo, cada una correspondiente a una historia de usuario o tarea específica asignada dentro del backlog del Sprint. Estas ramas siguen el estándar de nomenclatura propuesto por GitFlow, utilizando el prefijo feature/ seguido de un identificador claro de funcionalidad, por ejemplo:

Cada rama fue creada desde develop, y al finalizar su implementación y revisión, se integró nuevamente mediante Pull Request (PR), garantizando revisión por pares y trazabilidad.

Participación de los usuarios

El trabajo fue distribuido entre los integrantes del equipo, quienes realizaron commits regulares con mensajes estructurados bajo la convención Conventional Commits, permitiendo un historial claro y comprensible. La participación individual fue trazable a través del historial de contribuciones de GitHub. 

Cada desarrollador utilizó su propia rama de trabajo, fusionando mediante Pull Requests revisados y aprobados por al menos un compañero del equipo, asegurando así un enfoque de calidad y mejora continua.

Commits y trazabilidad

- feat(login): implement login modal with validation

  

- fix(header): correct alignment in mobile view

  

- style(footer): improve spacing and color contrast

  

- refactor(cart): optimize rendering performance

  

Estos commits reflejan una combinación equilibrada entre nuevas funcionalidades (feat), correcciones (fix), mejoras visuales (style), y ajustes técnicos (refactor).

Pull Requests y revisiones

Cada funcionalidad fue subida mediante Pull Request, los cuales incluyen:

- Descripción de la tarea implementada.

  

- Enlaces a la historia de usuario correspondiente.

  

- Aprobaciones del equipo.

  

Las PRs se revisaron con enfoque colaborativo, promoviendo la detección temprana de errores, sugerencias de mejora y aprendizaje entre pares.

La estrategia de ramificación, uso disciplinado de commits, y trabajo colaborativo en GitHub garantizó una integración continua exitosa. La trazabilidad de cada historia de usuario, junto con la revisión estructurada por Pull Requests, permitió validar que todas las funcionalidades entregadas cumplen con los criterios de aceptación definidos. El equipo demostró dominio de herramientas de control de versiones, colaboración efectiva y capacidad para desarrollar en un entorno distribuido, tal como lo exige un proyecto profesional de desarrollo de software.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcvmMbDWjaZIOcuTuBVrzlvScJ4Wuxl5xHd2737cv2egu8RVATg9RtNQQcsuLi5jsX453QlF_VSRIhXj2_Zvv4_pd2RqSqWvd_7DOd0l-O1aymXdER5dz6zn__gYD1VBFcns8aDFQ?key=wLsuErVgqDz-qczrBI4kMctR)

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante el Sprint 1 del proyecto QURI se logró implementar la estructura base de la landing page, enfocándose en una experiencia accesible, responsiva y multilingüe. El equipo desarrolló y conectó los principales puntos de navegación mediante un **header funcional con enlaces activos** y un **footer informativo** con accesos a secciones clave.

También se integró exitosamente la funcionalidad de **cambio de idioma**, permitiendo al usuario seleccionar su idioma preferido y conservar esta configuración durante su navegación. Se garantizaron criterios de **accesibilidad** a través de etiquetas ARIA, descripciones en imágenes y navegación por teclado.

Además, se diseñaron y habilitaron secciones como **Propuesta de Valor**, **Información de la Empresa**, **Preguntas Frecuentes (FAQ)**, **Equipo** y enlaces a redes sociales, incluyendo soporte visual responsivo para dispositivos móviles.

A continuación, se presentan capturas de las vistas más relevantes implementadas en este Sprint.
**Propuesta de Valor**
![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfxyrBS23yZ2TZz7vcUiwvROnqq_qujK3tFN6MRNEpPXpfp_9BojJe2udY-O6OXFgBKZorP4T1wpHLLA_sIs_O3fGkNDnf7_2ZWFG-NNS5cCquiXz9jUVulVrEbTd-e7dis080f4Q?key=wLsuErVgqDz-qczrBI4kMctR)
![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd2gAhfK1teKso62XWKtxXbyJWloFW9WQL8hMMJV4cC6OxIf9waA4ViAMh0lVBgW4jsnlfXSGg-hwpRsaWputRWYkq7tCrGyH-32qYcCAZ3h7-zgrZyweNlj24Wz1B0UdcfWh8mHA?key=wLsuErVgqDz-qczrBI4kMctR)

**Información de la Empresa**

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdwtTchSrxOyDPirYEUJ2N_hvZQMNUVlbMTIPrfXIucK_RQsnzRJiEVbSzXNRPHU0JxiuJrsG1-rLNXPonE8_IzYX-isIOjGSQ8Z7HEaKS5qptirSyyS-BQflYHpQQYkQgQLcP0PQ?key=wLsuErVgqDz-qczrBI4kMctR)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfddh3uuI0WuJJm_O-_ljPZJE67XhXlMnjCbSSdTkJztnEoPV2ssz4rDDqd9u1NVbGgiBiwWAPUPhNZ4_49XItwYqD-XpfyFaRp2QKYGSIGpcsrj3YCO6busqlbcRm7HVL1tL1K1Q?key=wLsuErVgqDz-qczrBI4kMctR)

**Preguntas Frecuentes (FAQ)**

**![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdbYsQWEwgH0J5tpDQX8_ZZfaZdvkobuch3DJoE2GWPbjgvmPZdT-b9mIPa5jzXBGESVGMHUAx_vI2uSxt0TW8ASXwd46YMJz2qetnzlSkYnIX2sLrmoBhJdVTTDzNKIIGesuetLg?key=wLsuErVgqDz-qczrBI4kMctR)**

**![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeBAKN7hmN-fRKPXo3QY_Vr6GB9mYjD_hyBpxRZ-GSwWnwgb9fvBqMH0SeoQK0_yk2s4JfHPP3HH7EDwHHE28jZh7wmG-xBj1lrsKwEBOysMFUWUR1p1QG6SUL94tVtRB8k8fDNfg?key=wLsuErVgqDz-qczrBI4kMctR)**

 **Equipo**

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXebHY-GOKFtWN5BLqIsIF8FamztX7vZl0kYtdxCAx5lchH_8UsINFrRy9YnWqgXcJ4SX-7f5XuxOMnTX1N6hOZdvR_gBCiiFaOYjocfDmLVw1hAe7EZvkE2U4p2WCEh2Eq3NmijXw?key=wLsuErVgqDz-qczrBI4kMctR)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdZr80oFRJhcpRKUKkON3bvbSVhwQUSv33OsAH8EknAvUz7AaWBhomOFvzGFZgj7fhl3buazRQ7EQVn0RCBY7OMgxK1QAUA1n2i5-q9vC638XpEOhb47o_PrywVnN1jO--fVIhy?key=wLsuErVgqDz-qczrBI4kMctR)

Link del video [upc-pre-202510-1asi0730-4350-quri-product-navigation-sprint-1 ](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231b866_upc_edu_pe/EUt6PjaYjKdCrlfYfu8kISUBWaIJHZ2pE2f9z1m1SAyZPg?e=WeKdLc&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 1, el foco del desarrollo estuvo centrado exclusivamente en la implementación de la interfaz gráfica del sistema, particularmente en el diseño, maquetación y despliegue funcional de la Landing Page. En esta etapa, no se desarrollaron aún servicios de backend ni endpoints de API RESTful, por lo cual no corresponde documentación técnica de servicios para este Sprint.

Estado actual:

No se han implementado controladores (controllers) ni servicios de aplicación (application services).

No se han definido endpoints HTTP ni documentación Swagger u OpenAPI.

No se han activado microservicios ni lógica de negocio en la capa backend.

El proyecto se encuentra en etapa de diseño visual, internacionalización y diseño responsivo.

Justificación:

El enfoque del Sprint 1 responde a las épicas EP04 - Landing page y visibilidad de productos, EP06 - Internacionalización (i18n), EP10 - Responsive UI, y EP07 - Accesibilidad (a11y), las cuales no requieren integración con lógica de negocio. La implementación de servicios comenzará a partir del Sprint 2, con la activación del Create Module y el diseño de los primeros flujos funcionales del dominio (Design, Projects, Orders).

Próximos pasos:

A partir del siguiente Sprint, se documentarán:

Interfaces REST y contratos de servicios (DesignService, TemplateService, etc.).

Especificaciones OpenAPI (Swagger) para endpoints públicos y protegidos.

Diagrama de Componentes (C4 level 3) mostrando la relación entre servicios.

Integración de pruebas Postman o herramientas similares para validación.

#### 5.1.2.7. Software Deployment Evidence for Sprint Review

Esta sección resume los procesos de despliegue llevados a cabo durante el Sprint 1. Durante este sprint, nuestro enfoque principal fue establecer la presentación inicial de la plataforma Q2, la cual incluye navegación básica y características de accesibilidad. Esto implicó la configuración inicial del proyecto en un proveedor de la nube para asegurar su publicación y accesibilidad.

Para iniciar la construcción y el despliegue de la plataforma Q2, utilizamos Netlify como nuestro proveedor de la nube. Se creó un proyecto y se vinculó a nuestro repositorio de desarrollo, permitiendo así despliegues automatizados de las actualizaciones.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXekQn436aRg51yMs91jHYhOHDgWN6rlxU5eZAm5X-bmtyXx0RP61GWqs9hBbEZeXuAo0Du3MGoUxD4LG1tLVJOCQfDvEUr44bngzD_xi6xwaEyp5cXyZw0evOwanEsfZ6tAupWgaQ?key=wLsuErVgqDz-qczrBI4kMctR)

Captura de la Landing Page en producción, accesible en https://quri.netlify.app.



#### 5.1.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 1 del proyecto QURI, las actividades de implementación se organizaron en torno a tres frentes de trabajo: **Landing Page**, **Web Applications** y **Web Services**. Cada uno de los miembros del equipo participó activamente en el desarrollo de los entregables asignados, garantizando una distribución equilibrada del esfuerzo técnico.

La implementación se llevó a cabo mediante la creación e integración de diversos componentes y estilos. Inicialmente, se abordó la **estructura visual y la responsiveness** del sitio a través de la implementación de Cascading Style Sheets (CSS) para distintas secciones clave como la **"About" page**, la **"team" section**, el **"FAQ" page** y un **"carousel"** interactivo. Esto aseguró una presentación adecuada en diferentes dispositivos.

Posteriormente, se procedió a la **incorporación de contenido esencial**, con la creación de la **"About" page** y el **"FAQ" page**, estableciendo su estructura básica y la forma en que se mostraría la información.

Para mejorar la **experiencia visual**, se integraron diversos elementos gráficos, incluyendo **"hero images"**, la imagen representativa de **"What We Offer"** y otras **"feature images"**.

Se añadió **interactividad** al sitio mediante la implementación de un **"carousel"** con funcionalidad de **slide navigation**.

Finalmente, se dieron los **primeros pasos hacia la internacionalización** (**i18n**) con la inclusión de lógica JavaScript específica y la traducción al español de la **"About" section**, sentando las bases para futuras adaptaciones a otros idiomas.

La colaboración se gestionó mediante GitHub, empleando ramas por feature, commits convencionales y pull requests. A continuación, se detalla el enfoque de participación por producto:



![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXehJvJ9PeeY8vfzqreZjx_CVzwS7XU-wUMbz1D_77_nUrqGu_LxL5LAuYPQCKT42zSVQLWxHfh3scVsc6rcp7qi_cV52RxDzMxgOQeRfhtyB9JTfnYt5jAMiVMRQo7vp0ffdk9TeA?key=wLsuErVgqDz-qczrBI4kMctR)
Capturas de los commits 
![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdR_GcJnXmR-DyM9FS98w2eDGZrU9gTSmf8zQBKoqjT3MCdNBNbtRaF7uQrVK0lIFYfb0zMNF0mG4WZXp1ZM5xl1Kdkpsjuy46HO4tvjALXfluBPFba8W0NG5oBIOORYku3eOkwrA?key=wLsuErVgqDz-qczrBI4kMctR)

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeF58hFMvVUPZ_Cu7uoN4fADVwT-ICWpO0TomXyZ-WmwxgU6QkNOgfdzqNcze8ld0BEJo2_8XBgPfgS6cTqya5oOuQCWCS2lI1W0auqPuLWQOGyEjyjyGXIwhshxy3i31BFOnrHYQ?key=wLsuErVgqDz-qczrBI4kMctR)

Dado que hemos podido solucionar el problema del manejo de Gitflow se espera que para las próximas entregas se desarrolle sin este problema y con normalidad.


**Neil Curipaco**

**Estructuración HTML:** Se encargó de la creación de las estructuras HTML base para la landing page, sentando las bases del contenido.

**Mejora de formularios y registros:** Realizó correcciones en los formularios de entrevistas para optimizar la recopilación de datos y actualizó los registros audiovisuales para una mejor presentación de los hallazgos.

**Mateo Alemán**

**Estilos y diseño visual:** Desarrolló los estilos CSS que dieron vida a la interfaz de la landing page, asegurando una estética coherente y atractiva.

**Optimización de documentación:** Revisó y corrigió a fondo los antecedentes y la problemática del proyecto, mejorando la redacción y alineación con los hallazgos. Además, reestructuró y perfeccionó el Lean UX Process y sus componentes clave.

**Ajuste de arquitectura de información:** Realizó correcciones en la arquitectura de información para mejorar la estructura y la accesibilidad del contenido de la landing page.

**Jonatan Acuña**

**Implementación de i18n:** Se encargó de la implementación de la internacionalización (i18n) para la landing page, facilitando su adaptación a diferentes idiomas y regiones.

**Renzo Luque**

**Aseguramiento de accesibilidad:** Trabajó en garantizar que la landing page fuera accesible para todos los usuarios, cumpliendo con estándares de usabilidad importantes.

**Fabrizio Contreras**

**SEO y Meta Tags:** Implementó estrategias de SEO y configuró los meta tags para optimizar la visibilidad de la landing page en los motores de búsqueda.

**Diseño de interfaz:** Lideró el diseño de la interfaz de la landing page, creando tanto el wireframe como el mock-up, definiendo su estructura y apariencia final.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcKwz-F5KQUH4qgNAVyOZXIW8c0P-qI0ydpoqF6IVqZobavZ8xUyyUFnhv57BLsZs1MH0W3ZE_fFYxV_uDj67ve4QzEVqAL_9U0L9fT5sS9H6f9dthhvpCAL0M7p1-Qn4XgH7KOZA?key=wLsuErVgqDz-qczrBI4kMctR)