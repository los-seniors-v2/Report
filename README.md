# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS
![UPC](assets/img/upc-logo-transparente.png)

# APLICACIONES WEB (SV51)
## PROFESOR: Angel Augusto Velasquez Nuñez
## "INFORME DE TRABAJO FINAL APLICACIONES WEB"
## STARTUP: Gymfinity
## NOMBRE DEL PRODUCTO: FlexPal
- - -
### INTEGRANTES
- Miguel Angel Jesus Carpio Cornejo (U20221C360)
- Cueto Dominguez Juan Diego (U202012207)
- Fabrizio Alessandro Sanchez Zamora (U202213652)
- Pescorán Angulo Juan Fabritzzio (U20221C936)
- Luiggi Gianfranco Paredes Zapata (U202218996)
### FECHA: MARZO 2024

- - - 

# Registro de Versiones del Informe

| Versión | Fecha      | Autores            | Descripción de Modificación                                                                                                                                                                                                                                                                                             |
|---------|------------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | 10/04/2024 | - Juan Pescoran    | - Añadió contenido a todos los capítulos <br> - Aportó ideas para la creación de User Stories <br> - Realizó código para el despliegue de la Landing Page <br> - Adicionó las secciones que pertenecen al capítulo 1 hasta el 2.                                                                                        |
| 1       | 10/04/2024 | - Fabrizio Sanchez | - Realizó diseño de entrevistas <br> - Realizó análisis de entrevistas <br> - Realizó User Persona <br> - Realizó empathy mapping <br> - Realizó as is scenario mapping  <br>    - Realizó source code management <br> - Realizó source code style guide & conventions <br> - Realizó software deployment configuration |
| 1       | 10/04/2024 | - Juan Cueto       | - Implementó segmentos objetivos para el proyecto <br> - Implementó Landing Page UI Design, Mockups. <br> - Implementó Web Applications UX/UI Design, Web Applications Prototyping, Domain-Driven Software Architecture. <br> - Implementó las bases para el desarrollo de la lading page                               |
| 1       | 10/04/2024 | - Luiggi Paredes   | - Realizó diagramas de clase <br> - Realizó diagramas de base de datos <br> - Realizó entrevista para un segmento <br> - Aplicó el uso de conventional commits. <br> - Aportó con conocimiento sobre el nicho de membresías en el ámbito del gimnasio.                                                                  |
| 1       | 10/04/2024 | - Miguel Carpio    | - Culminó con el capítulo 3 agregando el impact map y product backlog <br> - Realizó entrevistas para un segmento objetivo <br> -Lideró impact map, user stories, product backlog.                                                                                                                                         |
| 2       | 29/04/2024 | - Juan Pescoran    | - Corrigió, mediante commits dirigidos al "refactor", el nombre de los archivos en assets <br> - Agregó el seguimiento que faltaba en la sección "Project Report Collaboration Insights" <br> - Investigó y se realizó de forma correcta los "Lean UX Assumptions" <br> - . . .                                         |
| 2       | 29/04/2024 | - Fabrizio Sanchez | -   Corrigió user task matrix <br> - Corrigío style guidelines <br> - Agregó descripciones faltantes en todos los capítulos <br> - Realizó componentes haciendo uso de primevue en conjunto con html, css y javascript                                                                                                  |
| 2       | 29/04/2024 | - Juan Cueto       | - Implementó los componenetes para las vistas de la aplicación web. <br> - Actualizó Web Applications UX/UI Design, Web Applications Prototyping, Domain-Driven Software Architecture.                                                                                                                                  |
| 2       | 29/04/2024 | - Luiggi Paredes   | - Realizó código en html, css y javascript para el desarrollo de componentes en vue. <br> - Implementó APIS en json server                                                                                                                                                                                              |
| 2       | 29/04/2024 | - Miguel Carpio    | - Realizo feats utilizando vue como framework <br> Actualizó user stories                                                                                                                                                                                                                                                                            |

- - -
# Project Report Collaboration Insights

El siguiente enlace lleva al URL del repositorio que se encuentra en nuestra
organización pública: https://github.com/Los-seniors/Informe

Aquí se encuentra el resultado del Project Report de la entrega correspondiente.

A continuación, se explicará todo a cerca del desarrollo de activades para la
elaboración del informe junto con capturas de los analíticos de colaboración y commits en Github.

Para la entrega de la TB1, este es el análisis de colaboración, que presenta el número de contribuciones
hechas en el repositorio del informe.
![analytics-1-report](assets/img/analytics-screenshots-contributions-tb1.png)

En la primera semana del reporte, estos eran los commits totales realizados durante la semana 3:
![analytics-2-report](assets/img/analytics-screenshots-commits-mar24.png)

los commits totales realizados durante la semana 4:
![analytics-3-report](assets/img/analytics-screenshots-commits-mar31.png)

los commits totales realizados durante la semana 5:
![analytics-4-report](assets/img/analytics-screenshots-commits-apr7.png)

los commits totales realizados durante la semana 6:

![analytics-5-report](assets/img/analytics-screenshots-commits-apr14.png)


# Contenido
## Tabla de contenidos
#### [Capítulo I: Introducción](/chapter01.md)

[1.1. Startup Profile](/chapter01.md#11-startup-profile)

[1.1.1. Descripción de la Startup](/chapter01.md#111-descripción-de-la-startup)

[1.1.2. Perfiles de integrantes del equipo](/chapter01.md#112-perfiles-de-integrantes-del-equipo)

[1.2. Solution Profile](/chapter01.md#12-solution-profile)

[1.2,1 Antecedentes y problemática](/chapter01.md#121-antecedentes-y-problemática)

[1.2.2 Lean UX Process](/chapter01.md#122-lean-ux-process)
            
[1.2.2.1. Lean UX Problem Statements](/chapter01.md#1221-lean-ux-problem-statements)

[1.2.2.1. Lean UX Problem Statements](/chapter01.md#1221-lean-ux-problem-statements)

[1.2.2.2. Lean UX Assumptions](/chapter01.md#1222-lean-ux-assumptions)

[1.2.2.3. Lean UX Hypothesis Statements](/chapter01.md#1223-lean-ux-hypothesis-statements)

[1.2.2.4. Lean UX Canvas](/chapter01.md#1224-lean-ux-canvas)

[1.3. Segmentos objetivo](/chapter01.md#13-segmentos-objetivo)

#### [Capítulo II: Requirements Elicitation & Analysis](/chapter02.md#capítulo-ii--requirements-elicitation--analysis)

[2.1. Competidores](/chapter02.md#21-competidores)

[2.1.1. Análisis competitivo](/chapter02.md#211-análisis-competitivo)

[2.1.2. Estrategias y tácticas frente a competidores](/chapter02.md#212-estrategias-y-tácticas-frente-a-competidores)

[2.2. Entrevistas](/chapter02.md#22-entrevistas)

[2.2.1. Diseño de entrevistas](/chapter02.md#221-diseño-de-entrevistas)

[2.2.2. Registro de entrevistas](/chapter02.md#222-registro-de-entrevistas)

[2.2.3. Análisis de entrevistas.](/chapter02.md#223-análisis-de-entrevistas)

[2.3. Needfinding](/chapter02.md#23-needfinding)

[2.3.1. User Personas](/chapter02.md#23-needfinding)

[2.3.2. User Task Matrix](/chapter02.md#232-user-task-matrix)

[2.3.3. User Journey Mapping](/chapter02.md#233-user-journey-mapping)

[2.3.4. Empathy Mapping](/chapter02.md#233-user-journey-mapping)

[2.3.5. As-is Scenario Mapping](/chapter02.md#235-as-is-scenario-mapping)

[2.4. Ubiquitous Language](/chapter02.md#24-ubiquitous-language)

#### [Capítulo III: Requirements Specification](/chapter03.md#capítulo-iii-requirements-specification)

[3.1. To-Be Scenario Mapping](/chapter03.md#31-to-be-scenario-mapping)

[3.2. User Stories](/chapter03.md#32-user-stories)

[3.3. Impact Mapping](/chapter03.md#33-impact-mapping)

[3.4. Product Backlog](/chapter03.md#33-impact-mapping)

##### [Capítulo IV: Product Design](/chapter04.md#capítulo-iv-product-design)

[4.1. Style Guidelines](/chapter04.md#41-style-guidelines)

[4.1.1. General Style Guidelines](/chapter04.md#42-information-architecture)

[4.1.2. Web Style Guidelines](/chapter04.md#412-web-style-guidelines)

[4.2. Information Architecture](/chapter04.md#42-information-architecture)

[4.2.1. Organization Systems](/chapter04.md#421-organization-systems)

[4.2.2. Labeling Systems](/chapter04.md#422-labeling-systems)

[4.2.3. SEO Tags and Meta Tags](/chapter04.md#423-seo-tags-and-meta-tags)

[4.2.4. Searching Systems](/chapter04.md#424-searching-systems)

[4.2.5. Navigation Systems](/chapter04.md#425-navigation-systems)

[4.3. Landing Page UI Design](/chapter04.md#43-landing-page-ui-design)

[4.3.1. Landing Page Wireframe](/chapter04.md#431-landing-page-wireframe)

[4.3.2. Landing Page Mock-up](/chapter04.md#432-landing-page-mock-up)

[4.4. Web Applications UX/UI Design](/chapter04.md#44-web-applications-uxui-design)

[4.4.1. Web Applications Wireframes](/chapter04.md#441-web-applications-wireframes)

[4.4.2. Web Applications Wireflow Diagrams](/chapter04.md#442-web-applications-wireflow-diagrams)

[4.4.3. Web Applications Mock-ups](/chapter04.md#443-web-applications-mock-ups)

[4.4.4. Web Applications User Flow Diagrams](/chapter04.md#444-web-applications-user-flow-diagrams)

[4.5. Web Applications Prototyping](/chapter04.md#45-web-applications-prototyping)

[4.6. Domain-Driven Software Architecture](/chapter04.md#46-domain-driven-software-architecture)

[4.6.1. Software Architecture Context Diagram](/chapter04.md#461-software-architecture-context-diagram)

[4.6.2. Software Architecture Container Diagrams](/chapter04.md#462-software-architecture-container-diagrams)

[4.6.3. Software Architecture Components Diagrams](/chapter04.md#463-software-architecture-components-diagrams)

[4.7. Software Object-Oriented Design](/chapter04.md#47-software-object-oriented-design)

[4.7.1. Class Diagrams](/chapter04.md#471-class-diagrams)

[4.7.2. Class Dictionary](/chapter04.md#472-class-dictionary)

[4.8. Database Design](/chapter04.md#48-database-design)

[4.8.1. Database Diagram](/chapter04.md#481-database-diagram)

#### [Capítulo V: Product Implementation, Validation & Deployment](/chapter05.md#capítulo-v-product-implementation-validation--deployment)

[5.1. Software Configuration Management](/chapter05.md#51-software-configuration-management)

[5.1.1. Software Development Environment Configuration](/chapter05.md#512-source-code-management)

[5.1.2. Source Code Management](/chapter05.md#513-source-code-style-guide--conventions)

[5.1.3. Source Code Style Guide & Conventions](/chapter05.md#513-source-code-style-guide--conventions)

[5.1.4. Software Deployment Configuration](/chapter05.md#514-software-deployment-configuration)

[5.2. Landing Page, Services & Applications Implementation](/chapter05.md#52-landing-page-services--applications-implementation)

[5.2.1. Sprint 1](/chapter05.md#521-sprint-1)

[5.2.1.1. Sprint Planning n](/chapter05.md#5211-sprint-planning-1)

[5.2.1.2. Sprint Backlog n](/chapter05.md#5212-sprint-backlog-1)

[5.2.1.3. Development Evidence for Sprint Review](/chapter05.md#5213-development-evidence-for-sprint-review)

[5.2.1.4. Testing Suite Evidence for Sprint Review](/chapter05.md#5214-testing-suite-evidence-for-sprint-review)

[5.2.1.5. Execution Evidence for Sprint Review](/chapter05.md#5215-execution-evidence-for-sprint-review)

[5.2.1.6. Services Documentation Evidence for Sprint Review](/chapter05.md#5216-services-documentation-evidence-for-sprint-review)

[5.2.1.7. Software Deployment Evidence for Sprint Review](/chapter05.md#5217-software-deployment-evidence-for-sprint-review)

[5.2.1.8. Team Collaboration Insights during Sprint](/chapter05.md#5218-team-collaboration-insights-during-sprint)

[5.3. Validation Interviews](/chapter05.md)

[5.3.1. Diseño de Entrevistas](/chapter05.md)

[5.3.2. Registro de Entrevistas](/chapter05.md)

[5.3.3. Evaluaciones según heurísticas](/chapter05.md)

[5.4. Video About-the-Product](/chapter05.md)

[Conclusiones]()

[Conclusiones y recomendaciones]()

[Video About-the-Team]()

[Bibliografía]()

[Anexos]()

# Student Outcome


| Criterio Específico                                                                                                                                  | Acciones Ralizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Conclusiones                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | **-----------TB1-----------**<br>  **Juan Pescorán** <br> Realizó trabajos durante sesiones virtuales hechas en Microsoft Team, usando eficientemente las herramientas para las soluciones de Software. <br><br>**Juan Cueto** - Cordinó con el equipo para la creación de los repositorios, reuniones para el entendimiento de gitflow, y la creación de las respectivas ramas de cada repositorio a trabajar. De manera que, se obtuvo un desarrollo organizado en la forma de realizar las tareas asignadas al grupo, teniendo así un mejor control y registro en el contenido del proyecto. <br><br> **Luiggi Paredes** - Coordinó con el equipo las fechas para la entrega de avances, las reuniones, las partes que cada uno tenía que realizar. De manera que, se tuvo un desarrollo óptimo de la TB1 <br><br> **Fabrizio Sanchez**: Avanzó los elementos asignados a través de las reuniones grupales que fueron realizadas de manera diaria y semanal, por lo que pudo avanzar de la manera esperada. <br> <br> **Miguel Carpio**: Colaboró activamente en la resolución de problemas técnicos durante las sesiones virtuales, proporcionando soluciones efectivas y contribuyendo al avance del proyecto.  <br><br> **-----------TP1-----------**<br> **Fabrizio Sanchez**:<br> Colaboró y planficó eficazmente las actividades a realizar para la entrega parcial a traves de la herramienta Trello, la cual permitió al equipo avanzar de manera mas ordenada                                                                                                                                                                | **-----------TB1-----------**<br> El equipo demostró una sólida capacidad para trabajar de manera colaborativa y efectiva, utilizando herramientas virtuales de manera eficiente para coordinar, planificar y ejecutar las tareas del proyecto. La comunicación fluida, la organización adecuada y el compromiso con los objetivos del equipo permitieron un avance significativo y un desarrollo ordenado del proyecto. La participación activa de cada miembro, su capacidad para resolver problemas de manera eficiente durante las sesiones virtuales, así como su compromiso con los plazos y objetivos del proyecto, fueron fundamentales para el éxito del equipo. |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software                                                              | **-----------TB1-----------**<br>  **Juan Pescorán** <br> Utilizó frameworks como vue que crearán dominios locales: "localhost:1800" por ejemplo. También usaremos la herramienta GitHun Pages para que, al subir nuestra landing page a un repositorio, GitHub cree un dominio en internet donde se alojará nuestro index. <br><br>**Juan Cueto** - Investigó los posibles y actuales competidores de nuestro negocio. Con el fin de tener una retroalimentación y destacar los puntos que pueden impulsar y destacar entre los demas competidores. Obteniendo un resultado del entedimiento del dominio del problema que abarca este modelo de negocio.  <br><br> **Luiggi Paredes** - Investigó el dominio y aplicación del software a implementar, es por ello que todo el equipo participó de forma activa en el proceso de investigación de la problemática y la segmentación de nuestro público objetivo. <br><br>  **Fabrizio Sanchez**: Utilizó diferentes técnicas y herramientas para poder recaudar mas información de manera que ampliemos nuestro conocimiento de nuestros segmentos. <br> <br> **Miguel Carpio**: Realizó un análisis de la competencia para identificar fortalezas y oportunidades de mejora en el proyecto, contribuyendo así a la definición de estrategias competitivas. <br><br> **-----------TP1-----------**<br> **Fabrizio Sanchez**:<br> Investigó la correcta implementación del user task matrix, el cual permitió saber como priorizar las actividades hechas por lo usuarios, así como tambien al realizar el user style guideline pudo entender las guias que debe tener nuestra aplicación | **-----------TB1-----------**<br> El equipo demostró un profundo conocimiento del dominio de aplicación del proyecto, mediante la investigación exhaustiva de la problemática a abordar y la identificación de los competidores relevantes. Esta comprensión sólida del sector empresarial permitió identificar oportunidades y establecer estrategias competitivas adecuadas para el éxito del proyecto. La investigación detallada sobre competidores proporcionó información valiosa para diferenciar el proyecto y destacar entre la competencia, mientras que la comprensión clara del público objetivo garantizó un enfoque preciso y efectivo en el desarrollo de soluciones de software adaptadas a las necesidades del mercado. En resumen, el profundo conocimiento del dominio de aplicación del proyecto fue clave para la definición de estrategias efectivas y el éxito global del equipo en la implementación de soluciones de ingeniería de software.| 


