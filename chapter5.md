# **Capítulo V: Product Implementation, Validation & Deployment.**
La implementación, validación y despliegue del producto son esenciales para asegurar que la visión del producto se convierta en una realidad funcional y accesible para nuestros usuarios. Estas etapas nos permiten transformar el diseño conceptual en una aplicación real, probada y lista para su uso, lo que nos ayuda a validar nuestras ideas, identificar posibles problemas y ofrecer una experiencia de usuario óptima.
## 5.1. Software Configuration Management.
La gestión de la configuración del software es crucial para nuestro trabajo, ya que nos permite mantener un control preciso sobre los elementos de nuestro proyecto, como el código fuente, los documentos de diseño y los activos digitales. Esto garantiza que todos los miembros del equipo estén trabajando con la misma versión de los archivos y facilita la colaboración entre desarrolladores, diseñadores y otros profesionales involucrados en el proyecto.
### 5.1.1. Software Development Environment Configuration

- ### Project Management:
    * ### Trello:
      Una aplicación de gestión de proyectos que facilita el seguimiento de las tareas individuales de cada miembro del equipo de manera sencilla. <br>
      [Link De Registro o Inicio De Sesión](https://trello.com/es)<br>
      Imagen para mostrar evidencia de uso:
      ![trello-image-grupo](assets/img/project-management-trello.png)
      *  ### Microsoft Teams
       una plataforma unificada de comunicación y colaboración que combina chat persistente en el lugar de trabajo, reuniones de video, almacenamiento de archivos e integración de aplicaciones. <br>
        [Link De Registro o Inicio De Sesión](https://www.microsoft.com/es-pe/)
      Imagen para mostrar evidencia de uso:
      ![microsoft-teams-image-userpersona](assets/img/evidencia-microsoft-teams.png)

- ### Requirement Management:
    * ### Miro:
      Un sistema que ofrece una amplia gama de plantillas diseñadas para abordar diversos aspectos en la creación y gestión de proyectos. <br>
      [Link De Registro o Inicio De Sesión](https://miro.com/es/login/)
      Imagen para mostrar evidencia de uso:
      ![Miro-image-userpersona](assets/img/evidencia-miro.png)
    * ### UXPressia:
      Es una herramienta en línea que simplifica el proceso de mapeo y comprensión de las necesidades del cliente en un proyecto determinado. <br>
      [Link De Registro o Inicio De Sesión](https://uxpressia.com)
      Imagen para mostrar evidencia de uso:
      ![uxpressia-image-userpersona](assets/img/evidencia-uxpressia.png)
    * ### Structurizr:
      Se trata de una suite de herramientas que posibilita la creación colaborativa de modelos C4 para representar de forma gráfica nuestros productos. <br>
      [Link De Registro o Inicio De Sesión](https://structurizr.com)
- ###  Product UX/UI Design:
    * ### Figma:
      Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups. <br>
      [Link De Registro, Inicio De Sesión y Descarga](https://www.figma.com/downloads/)
    * ### LucidChart:
      Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow. <br>
      [Link De Registro o Inicio De Sesión ](https://www.lucidchart.com/pages/es)
      Imagen para mostrar evidencia de uso:
      ![lucidchart-image-userpersona](assets/img/evidencia-lucidchart.png)
- ###  Software Development:
    * ### HTML5:
      Es un lenguaje de etiquetado utilizado para crear la estructura a páginas web. Lo utilizamos para incluir componentes como texto, imágenes, enlaces, botones y videos en nuestras páginas web. <br>
      [Información Relacionada](https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20estándar,%2C%20estilo%20de%20letra%2C%20etc.)
      Imagen para mostrar evidencia de uso:
      ![uxpressia-image-userpersona](assets/img/html-evidencia.png)
    * ### CSS:
      Un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de un documento escrito en HTML. <br>
      [Información Relacionada](https://developer.mozilla.org/es/docs/Web/CSS)
      Imagen para mostrar evidencia de uso:
      ![uxpressia-image-userpersona](assets/img/evidencia-css.png)
    * ### JavaScript:
      Un lenguaje de programación orientado a objetos dinámico que utilizamos para implementar funcionalidades en un documento HTML. <br>
      [Información Relacionada]( https://developer.mozilla.org/es/docs/Web/JavaScript )
      Imagen para mostrar evidencia de uso:
      ![uxpressia-image-userpersona](assets/img/evidencia-uxpressia.png)
    * ### WebStorm:
      Un entorno de desarrollo integrado (IDE) que emplearemos para trabajar con JavaScript. <br>
      [Link De Descarga]( https://www.jetbrains.com/es-es/webstorm/)

- ###  Software Testing:
    * ### Lenguaje Gherkin:
      Se trata de un Lenguaje Específico de Dominio (DSL), diseñado específicamente para abordar un problema particular. Es un lenguaje comprensible para los desarrolladores, destinado a resolver necesidades concretas. <br>
- ###  Software Documentation:
    * ### Github:
      Se trata de una plataforma utilizada para el alojamiento de versiones del código fuente de un proyecto. Es una herramienta ampliamente popular en el trabajo colaborativo de programadores. <br>
      [Link De Descarga]( https://desktop.github.com)
      [Link De Registro o Inicio De Sesión](https://github.com/login)
- ###  Software Deployment:
    * ### GitHub Pages: 
      Una plataforma que posibilita la realización de despliegues simples directamente desde un repositorio de GitHub. <br>

### 5.1.2. Source Code Management.
Landing Page Repository: [Landing Page Repository](https://github.com/los-seniors-v2/LandingPageFlexPal.git)
- #### GitFlow Implementation:
Para implementar el flujo de trabajo Gitflow utilizando Git como nuestra herramienta de control de versiones, nos basamos en la entrada de blog "A successful Git branching model" de Vincent Driessen. Esta referencia nos permitió establecer las convenciones detalladas que serán aplicadas en nuestro proyecto 
![gitflow](assets/img/team_collab_ins.png)

### **Master o Main branch**
La rama principal de desarrollo del proyecto es la Master branch. En esta rama reside el código que actualmente se encuentra en producción.
#### Notación: master o main

### **Develop branch**
La rama "Develop" albergará las más recientes actualizaciones y cambios agregados que serán incluidos en la próxima versión del proyecto. Esta rama sirve como un espacio para la integración y prueba continua de los cambios antes de ser fusionados con la rama principal "Master" para su despliegue en producción.
#### Notación: develop

### **Release branch**
La rama de lanzamiento (Release branch) facilitará la preparación de una nueva versión del producto. Esta rama permitirá la corrección de errores y permitirá que la rama Develop reciba más actualizaciones.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse con la rama Develop y Master.
#### Notación: release


### **Feature branch**
Las ramas de características (Feature branches) serán empleadas para desarrollar nuevas funcionalidades o características del producto que se agregarán en la siguiente versión o en versiones futuras. Estas funcionalidades deberán fusionarse eventualmente con la rama Develop.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse de vuelta a la rama Develop.
#### Notación: release


### **Hotfix branch**
La rama de corrección rápida (Hotfix branch) se empleará para resolver y actuar de manera inmediata ante posibles errores en la versión en producción del producto. La característica principal de esta rama es que permite preparar una solución rápida mientras el resto del equipo continúa trabajando en otras funcionalidades o mejoras.
<br>Debe derivarse de la rama Master
<br>Debe fusionarse con la rama Develop y Master
#### Notación: hotfix

### **Support branch**
### **Conventional Commits**
"Conventional Commits" es una convención para estructurar los mensajes de confirmación (commits) en un formato estándar y semántico. Este formato ayuda a comunicar claramente los cambios realizados en el código y facilita la generación de registros de cambios automáticos. Los "Conventional Commits" suelen seguir un formato que incluye un encabezado, un cuerpo opcional y un pie de página opcional, y se utilizan para describir de manera sucinta y clara los cambios realizados en el código, lo que facilita su seguimiento y comprensión por parte de los desarrolladores y otros miembros del equipo.
<br>
La estructura de un commit debe seguir las siguientes pautas:
~~~
git commit -m “<type>[optional scope]: <title>“ -m “<description”
~~~
**Tipos De Conventional Commits**
~~~
1. feat: Used to describe a new feature or functionality added to the code.
2. fix: Indicates a bug fix or solution to a problem.
3. docs: Employed for changes or improvements in code documentation.
4. style: Describes changes related to the code's formatting, such as whitespace, indentation, etc., that do not affect its functionality.
5. refactor: Used for modifications to the code that do not fix bugs or add new features, but rather improve its structure or readability.
6. test: Indicates the addition or modification of unit tests or functional tests.
7. chore: Used for changes in the build process or maintenance tasks that are not directly related to the code itself.
8. perf: Describes performance improvements in the code.
~~~


### 5.1.3. Source Code Style Guide & Conventions.
Como norma general, se espera que todo el código desarrollado por los miembros del equipo esté completamente redactado en inglés.
- ### HTML 
    - #### Use Lowercase Element Names:
        Es recomendable utilizar minúsculas o lowercase para los nombres de los elementos HTML.
        ~~~ 
      <body>
            <p>This is a paragraph</p>
      <body>
       ~~~
    - #### Close All HTML Elements:
        Es recomendable cerrar todos los elementos HTML correctamente.
        ~~~ 
      <body>
            <p>This is a paragraph</p>
            <p>This is another paragraph</p>
      <body>
       ~~~
    - #### Use Lowercase Attribute Names:
        Es recomendable utilizar minúsculas para los nombres de los atributos HTML.
      ~~~ 
      <a href="https://www.w3schools.com/html/">Visit our HTMLtutorial</a>
       ~~~
    - #### Always Specify alt, width, and height for Images:
      Es recomendable seguir estas convenciones en caso de que la imagen no se pueda mostrar, lo que ayuda a mejorar la accesibilidad del contenido.
      ~~~ 
      <img src="html5.gif" alt="HTML5" 
      style="width:128px;height:128px">
      ~~~ 
    - #### Spaces and Equal Signs:
      Se recomienda no utilizar espacios en blanco entre las entidades para mejorar la legibilidad.
      ~~~ 
      <link rel="stylesheet" href="styles.css">
      ~~~ 
- ### CSS
    - #### ID and Class Naming
      Es recomendable utilizar nombres de clases e id's significativos que expresen claramente el propósito del elemento.
      ~~~ 
      #gallery {}
      #login {}
      .video {}
       ~~~
    - #### ID and Class Name Style
      Se recomienda utilizar nombres cortos para nombrar ids o clases, pero lo suficientemente descriptivos para entender su propósito.
      ~~~ 
      #nav {}
      .author {}
      ~~~
    - #### Shorthand Properties
      Se recomienda utilizar propiedades CSS de forma abreviada siempre que sea posible para hacer el código más eficiente y comprensible.
       ~~~ 
       border-top: 0;
       font: 100%/1.6 palatino, georgia, serif;
       padding: 0 1em 2em;
       ~~~ 
    - #### 0 and Units
      Es recomendable evitar especificar la unidad después del valor 0 en propiedades que lo permitan, ya que esto ayuda a reducir el tamaño del código y mejora su legibilidad.
       ~~~ 
       margin: 0;
       padding: 0;
       ~~~
     - #### Declaration Order
       Se recomienda ordenar las declaraciones en orden alfabético para facilitar el mantenimiento y la recordación del código.
       ~~~ 
        background: fuchsia;
        border: 1px solid;
        border-radius: 4px;
        color: black;
        text-align: center;
        text-indent: 2em;
       ~~~  
- ### JAVASCRIPT
     - #### Use expanded syntax
       Cada línea de JavaScript debería estar en una nueva línea, con la llave de apertura en la misma línea de su declaración y la llave de cierre en una nueva línea al final.
       ~~~ 
       function myFunc() {
        console.log('Hello!');
       };
       ~~~
     - #### Variable naming
       Para el nombre de las variables, se recomienda utilizar lowerCamelCase. 
       ~~~ 
       let playerScore = 0;
       let speed = distance / time;
       ~~~  
     - #### Declaring variables
       Para la declaración de variables, es recomendable utilizar las palabras reservadas let y const en lugar de var.
       ~~~ 
       const myName = 'Chris';
       console.log(myName);
       let myAge = '40';
       myAge++;
       console.log('Happy birthday!');
       ~~~ 
     - #### Function naming
       Para el nombre de las funciones, se recomienda utilizar lowerCamelCase.
       ~~~ 
       function sayHello() {
       alert('Hello!');
       };
       ~~~ 
- ### C#
    - #### PascalCase
      Mayúscula al principio de cada palabra para nombres de clases y métodos.
      ~~~ 
      public class MyClass {
          public void ExampleMethod() {
              // Method code
          }
      }
      ~~~
    - #### camelCase
      Minúscula al principio con mayúsculas para cada palabra subsiguiente para variables y parámetros.
      ~~~ 
      public class MyClass {
          public void ExampleMethod(int exampleNumber) {
              string exampleName = "Example";
              // Method code     
          }
      }
      ~~~
      - #### Reasonable line length
        Mantener líneas de código con longitud adecuada para mejorar la legibilidad.
        ~~~ 
        public class MyClass {
            public void ExampleMethod() {
                string message = "This is an example message that spans multiple lines " +
                                 "to demonstrate how to maintain a reasonable length.";
                 Console.WriteLine(message);  
          }
        }
        ~~~ 
      - #### Clear comments:
          Utilizar comentarios para explicar el propósito del código de manera concisa.
          ~~~ 
          public class MyClass {
              // This method performs an addition operation and returns the result.
              public int Add(int a, int b) {
                return a + b;
               }
          }
          ~~~
    - #### Single responsibility:
      Cada clase o método debe tener una única función bien definida.
      ~~~ 
      // Class responsible for handling basic mathematical operations
      public class MathematicalOperations {
          // Method to add two numbers
          public int Add(int a, int b) {
              return a + b; 
          } 
       
          // Method to subtract two numbers
          public int Subtract(int a, int b) { 
              return a - b; 
          } 
      }
      ~~~
- ### LENGUAJE GHERKIN
    - #### Descriptive and concise titles for scenarios
      Utilizar títulos descriptivos y concisos para los escenarios.
      ~~~ 
      Feature: Login
        Scenario: Successful login
          Given a user is on the login page     
          When they enter valid credentials     
          Then they should be logged in successfully      
      ~~~
    - #### Follow the Given-When-Then structure consistently.
      Seguir la estructura de Given-When-Then de manera consistente.
      ~~~ 
      Scenario: Adding items to the shopping cart
        Given the user is on the shopping page
        When they add an item to the cart
        Then the item should appear in the cart 
      ~~~
    - #### Focus on business-readable language
      Centrarse en un lenguaje legible para el negocio, evitando detalles técnicos de implementación.
      ~~~ 
      Scenario: Changing user settingst
        Given the user is logged in
        When they navigate to the settings page
        Then they should be able to update their profile
      ~~~
    - ####  Utilize Scenario Outline for scenarios with multiple similar cases.
      Utilizar Scenario Outline para escenarios con múltiples casos similares.
      ~~~ 
      Scenario Outline: Searching for products
        Given the user is on the search page
        When they search for "<product>"
        Then they should see search results for "<product>"
      
      Examples:
        | product  |
        | Laptop   |
        | Smartphone |
      ~~~
    - #### Add comments to provide additional context
      Agregar comentarios para proporcionar contexto adicional o explicaciones cuando sea necesario.
      ~~~ 
      # This scenario checks the functionality of the logout feature
      Scenario: User logout
        Given the user is logged in
        When they click on the logout button
        Then they should be redirected to the login page      
      ~~~
      
### 5.1.4. Software Deployment Configuration.
- Creación Landing Page:<br>
1. Se crea un repositorio remoto en GitHub
![creation-of-repository-lp](assets/img/Creacion_repo.png)
2. Agregar a participantes
![adding-members-screenshot-lp](assets/img/miembros_repo.png)
3. Habilitamos GitHub Pages en branch "master" y ruta "/(root)"
![deploying-repository-in-github-pages-lp](assets/img/Github_pages.png)

- Creación Front End App:<br>
1. Creación de repositorio dentro de nuestra organización:
![creation-of-repository-lp](assets/img/creacion-repositorio-frontendapp.png)
2. Agregar a participantes:
![adding-members-screenshot-lp](assets/img/miembros_repo.png)


## 5.2. Landing Page, Services & Applications Implementation.
La implementación de la página de inicio, los servicios y las aplicaciones es un paso fundamental en nuestro proceso de desarrollo. Nos permite materializar el diseño y la funcionalidad planificados, transformando los conceptos en productos tangibles y listos para su uso. Esta fase nos permite traducir las especificaciones y requisitos en código, desarrollando la estructura de la página, los servicios y las aplicaciones de acuerdo con las necesidades identificadas.
### 5.2.1. Sprint 1
El primer sprint es un hito importante en nuestro proceso de desarrollo ágil. Durante este período, nos enfocamos en la implementación de las características y funcionalidades prioritarias identificadas en la planificación inicial. Esto implica traducir los requisitos y especificaciones en código funcional, desarrollando las bases de nuestro producto de manera iterativa.
#### 5.2.1.1. Sprint Planning 1.
El sprint planning es una reunión en la metodología ágil donde el equipo planifica las actividades del próximo sprint. Define qué trabajo se hará, cuánto tiempo tomará y quién será responsable. El objetivo es establecer un plan claro y alcanzable para el equipo, fomentando la colaboración y asegurando que todos estén alineados en cuanto a objetivos y prioridades.
<table  style="text-align: center;">
    <tbody>
        <tr>
			<td colspan="1">Sprint #</td>
            <td colspan="1"> Sprint 1  </td>
		</tr>
        <tr>
			<td colspan="2">Sprint Planning Background </td>
		</tr>
        <tr>
			<td colspan="1">Date</td>
            <td colspan="1"> 2024-04-10 </td>
		</tr>
        <tr>
			<td colspan="1">Time</td>
            <td colspan="1"> 11:00 PM </td>
		</tr>
        <tr>
			<td colspan="1">Location</td>
            <td colspan="1">Microsoft Teams (Reunion virtual)</td>
		</tr>
        <tr>
			<td colspan="1">Prepared By</td>
            <td colspan="1">Pescoran Angulo, Juan Fabritzzio</td>
		</tr>
        <tr>
			<td colspan="1"> Attendees (to planning meeting)</td>
            <td colspan="1">Carpio Cornejo, Miguel Angel Jesus / Cueto Dominguez, Juan Diego / Sanchez Zamora Fabrizio Alessandro / Paredes Zapata, Luiggi Gianfranco </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 – 1 Review Summary </td>
            <td colspan="1">Se alcanzaron los objetivos del producto como la realización de todos los capítulos, el despliegue completo de la Landing Pague y la mayoría de información necesaria dentro del reporte, sin embargo, una de las tareas/objetivos más importantes que se debía alcanzar fue la presentación de un informa en formato pdf y word.</td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 – 1 Retrospective Summary </td>
            <td colspan="1">El sprint 1 fue ineficiente en términos de cooperación, se organizó mal el uso del tiempo y esto dio como resultado la entrega de un producto incompleto y para nada profesional. Juan Pescorán como Team Leader mencionó puntos de mejora, siendo estos: "Más dedicación por parte de todo el equipo, reuniones diarias para analizar el desarrollo de vida del proyecto de software, más comunicación entre los integrantes del equipo y maximizar el uso de herramientas de software para manejar las tareas pendientes de cada sprint."</td>
		</tr>
         <tr>
			<td colspan="2">Sprint Goal & User Stories </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 Goal</td>
            <td colspan="1">Para este sprint se requiere el cumplimiento de los siguientes objetivos: Finalización de reporte y despliegue sin problemas de la Landing Page que se encuentran en nuestro repositorio. La métrica de cumplimiento se basará en el proceso de cómo nuestro "Board de Trello" luzca con el paso del tiempo, nuestro resultado final debe de mostrar todas las tareas en el lado derecho de la herramienta, ubicándolos en la columna "Terminado"</td>
		</tr>
        <tr>
			<td colspan="1">Sprint 1 Velocity </td>
            <td colspan="1">Para este sprint se han elegido 5 User Stories que tienen 5 Story points cada uno.</td>
		</tr>
        <tr>
			<td colspan="1">Sum of Story Points </td>
            <td colspan="1">25</td>
		</tr>
</tbody>
</table>

#### 5.2.1.2. Sprint Backlog 1.

En este primer sprint, nos enfocamos en la implementación de las funcionalidades básicas de la Landing Page, incluyendo la estructura general, el diseño visual y la navegación básica, también se ha creado un reporte que muestra el ciclo de vida de todo nuestro proyecto de software. Estas características son fundamentales para establecer las bases de nuestro producto y proporcionar una experiencia de usuario sólida y coherente.
A continuación el sprint backlog 1 y el Trello donde se repartieron los trabajos: 

[Link para ingresar al board del primer sprint](https://trello.com/b/OVQC9ARc/task-app-web)

![trello-screenshot](assets/img/evidencia-trello-sprint-1.png)

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 1</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK001</td>
			<td>Remote environment creation for Report and Landing Page</td>
			<td>Organization, repositories and branch creation in GitHub</td>
			<td>0</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK002</td>
			<td>Conclude Chapter01</td>
			<td>Finish all section and add the respective information in chapter01</td>
			<td>5</td>
			<td>Juan Pescoran</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK003</td>
			<td>Conclude Chapter02</td>
			<td>Finish all section and add the respective information in chapter02</td>
			<td>3</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK004</td>
			<td>Conclude Chapter03</td>
			<td>Finish all section and add the respective information in chapter03</td>
			<td>5</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK005</td>
			<td>Conclude Chapter04</td>
			<td>Finish all section and add the respective information in chapter04</td>
			<td>19</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK006</td>
			<td>Conclude Chapter05</td>
			<td>Finish all section and add the respective information in chapter05</td>
			<td>3</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
    <tbody>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.
En esta sección se explica y presenta los avances en implementación con relación a los productos de la solución según el alcance del Sprint: Landing Page, Web Applications, Web Services.

Primero, se mostrarán los commits más importantes para el Reporte, los cuales muestran el ciclo de vida del proyecto, y toda la información que se usó, usa y usará para el desarrollo del proyecto:

| Repository          | Branch  | Commit ID                                | Commit Message                           | Commit Message Body                                                                                                                                 | Commited on (Date) |
|---------------------|---------|------------------------------------------|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| JuanPescoran/Report | develop | 98783487238973c5dd4a8097197adb2cf70af00a | feat: added content in chapter IV        | added content in all sections of chapter04                                                                                                          | 4/9/2024           |
| JuanPescoran/Report | master  | 889cdc0229a96aa9fca4641ebfccccd71f0d7a5a | feat(assets)                             | added img to master branch                                                                                                                          | 4/9/2024           |


A continuación se presentan los commits más importantes para la Landing Page, los cuales muestran todo el contenido visual y funcionalidades implementadas en el Sprint 2:

| Repository                      | Branch                | Commit ID                                | Commit Message                   | Commit Message Body                                                                                                                                 | Commited on (Date) |
|---------------------------------|-----------------------|------------------------------------------|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| JDu202012207/LandingPageFlexPal | feat-bienvenida       | 563de4f7bde5ef4a20ce639bc4f6bd881d205856 | feat(welcome-container)          | implemented cta in section home, added slogan and banner.                                                                                           | 4/9/2024           |
| Fabrizio0711/LandingPageFlexPal | feature-testimonios   | d3d404bfa4c98d4bd3311d54d2edca3c2b7f6f51 | feat: added testimonials section | added testimonials section with user feedback                                                                                                       | 4/9/2024           |
| JDu202012207/LandingPageFlexPal | feature-header-footer | f8351fb08d1718af912437127ac10d350a6b0d2c | feat(header-footer)              | implemented logo in header and information in footer.                                                                                               | 4/9/2024           |
| JDu202012207/LandingPageFlexPal | feature-contacto      | c8d979e154ceec2e6b7e924b6aa16137199f743d | feat(contact-us)                 | implemented form, description and labels                                                                                                            | 4/9/2024           |
| JuanPescoran/LandingPageFlexPal | feature-contenido     | db8e4a108071eeed824a148623bf34e7785ea982 | feat(assets): added images       | feat(assets): added all information for hero content, about us, subscriptions and other sections Also, added images for banners and everything else | 4/9/2024           |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en una etapa posterior del desarrollo.
#### 5.2.1.5. Execution Evidence for Sprint Review.

En esta entrega, el equipo de desarrolladores de FlexPal ha completado con éxito la implementación y el lanzamiento de la página de la Landing Page. Esta página presenta diferentes secciones que brindan información detallada sobre nuestro producto.
![Evidencia1](assets/img/Evidencia1.png)
![Evidencia2](assets/img/Evidencia2.png)
![Evidencia3](assets/img/Evidencia3.png)
![Evidencia4](assets/img/Evidencia4.png)
![Evidencia5](assets/img/Evidencia5.png)
![Evidencia6](assets/img/Evidencia6.png)
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en una etapa posterior del desarrollo.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en una etapa posterior del desarrollo.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
A continuación todos los analíticos que nos proporciona Github, en su apartado de Insights, sobre la colaboración del equipo durante el Sprint 1:

![team-collab-ins-sprint2](assets/img/analytics-collaboration-insights-sprint2.png)


- - -

### 5.2.2. Sprint 2
En esta sección se registra y explica el avance en términos de producto y trabajo colaborativo para el Sprint 2. Incluye como secciones internas: Sprint Planning 2, Sprint Backlog 2, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, junto con Team Collaboration Insights during Sprint
#### 5.2.2.1.Sprint Planning 2.

<table  style="text-align: center;">
    <tbody>
        <tr>
			<td colspan="1">Sprint #</td>
            <td colspan="1"> Sprint 2  </td>
		</tr>
        <tr>
			<td colspan="2">Sprint Planning Background </td>
		</tr>
        <tr>
			<td colspan="1">Date</td>
            <td colspan="1"> 2024-04-28 </td>
		</tr>
        <tr>
			<td colspan="1">Time</td>
            <td colspan="1"> 11:00 PM </td>
		</tr>
        <tr>
			<td colspan="1">Location</td>
            <td colspan="1">Microsoft Teams (Reunion virtual)</td>
		</tr>
        <tr>
			<td colspan="1">Prepared By</td>
            <td colspan="1">Pescoran Angulo, Juan Fabritzzio</td>
		</tr>
        <tr>
			<td colspan="1"> Attendees (to planning meeting)</td>
            <td colspan="1">Carpio Cornejo, Miguel Angel Jesus / Cueto Dominguez, Juan Diego / Sanchez Zamora Fabrizio Alessandro / Paredes Zapata, Luiggi Gianfranco </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 2 – 1 Review Summary </td>
            <td colspan="1">Se alcanzaron los objetivos: el mejoramiento del reporte según las pautas del profesor, el arreglo del código en nuestra landing page y también el despliegue de la primera versión de nuestra Front End App que se planea seguir desarrollando en etapas posteriores.</td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 – 1 Retrospective Summary </td>
            <td colspan="1">El sprint 2 fue mucho mejor comparado al sprint 1, a pesar de tener menos tiempo para la presentación de una versión mejorada del producto presentado en la etapa anterior y también adicionar la creación de nuestra Web Application, el equipo ha podido mantener su resiliencia, mejorando el rendimiento de todos los integrantes, su cooperación y manejo de herramientas que mejoraron la presentación del trabajo. En palabras de Fabrizio Sánchez: "Nos fue mejor, pues supimos utilizar el tiempo que se nos dio para completar una tarea que fue completada con sencillez gracias al trabajo en equipo."</td>
		</tr>
         <tr>
			<td colspan="2">Sprint Goal & User Stories </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 Goal</td>
            <td colspan="1">Para este sprint se requiere el cumplimiento de los siguientes objetivos: Mejoramiento de información dentro del reporte y adición de información que faltó agregar en el sprint anterior, arreglo de código fuente de nuestra landing page (mayormente convenciones y cambio de lenguaje en variables y valores) y por último despliegue de nuestra primera versión completa de la Front End App</td>
		</tr>
        <tr>
			<td colspan="1">Sprint 1 Velocity </td>
            <td colspan="1">Para este sprint se han elegido 11 User Stories que tienen 2,3 y 5 Story points cada uno: 2 User Stories con el valor de 2 Story Points, 7 USer Stories con el valor de 3 Story Points y 2 User Stories con el valor de 5 Story Points.</td>
		</tr>
        <tr>
			<td colspan="1">Sum of Story Points </td>
            <td colspan="1">35</td>
		</tr>
</tbody>
</table>

#### .2.2.2.Sprint Backlog 2.

En este segundo sprint el equipo se ha enfocado en el mejoramiento de la Landing Page, el reporte y la implementación de la Front End Application. A continuación, se presenta el backlog de tareas para el Sprint 2:
[Link para ingresar al board del segundo Sprint](https://trello.com/b/gGX8tUs5/tareas-para-aplicaciones-web)

![trello-screenshot](assets/img/trello-screenshot.png)

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 2</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK008</td>
			<td>Remote environment creation for Front End App</td>
			<td>repositories and branch creations for Web Application in GitHub</td>
			<td>0</td>
			<td>Juan Pescoran</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK009</td>
			<td>Update Chapter01</td>
			<td>add the respective information resulting from the observations made in the review in chapter01</td>
			<td>5</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK010</td>
			<td>Update Chapter02</td>
			<td>add the respective information resulting from the observations made in the review in chapter02</td>
			<td>1</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK011</td>
			<td>Update Chapter03</td>
			<td>add the respective information resulting from the observations made in the review in chapter03</td>
			<td>2</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK012</td>
			<td>Update Chapter04</td>
			<td>add the respective information resulting from the observations made in the review in chapter04</td>
			<td>6</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td>TSK013</td>
			<td>Update Chapter05</td>
			<td>add the respective information resulting from the observations made in the review in chapter02</td>
			<td>4</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
    <tbody>
</table>

#### 5.2.2.3.Development Evidence for Sprint Review.

En la primera tabla
En la segunda tabla se ve el commit que realizó el cambio de lenguaje en la Landing Page.

Primero, se mostrarán los commits más importantes para el arreglo según las observaciones hechas al reporte:

| Repository          | Branch  | Commit ID                                | Commit Message                                                                         | Commit Message Body        | Commited on (Date) |
|---------------------|---------|------------------------------------------|----------------------------------------------------------------------------------------|----------------------------|--------------------|
| JDu202012207/Report | develop | 771e52970c40273864623683573ae900bda62fd8 | Merge branch 'feat-chapter01' of https://github.com/los-seniors-v2/Report into develop | -                          | 4/29/2024          |
| JDu202012207/Report | develop | 219b131d79d8a800f0c5175b9c05b69ff87646cc | Merge: merging chapter02 features.                                                     | -                          | 4/29/2024          |
| JDu202012207/Report | develop | 271962ab497af6c8fd38596dc9dd6a576c6d6501 | Merge branch 'feat-chapter03' of https://github.com/los-seniors-v2/Report into develop | -                          | 4/29/2024          |
| JDu202012207/Report | develop | 7bca55d1ecdb7cb94597e8680a455c5b12b7138d | Merge: merging chapter04 features.                                                     | -                          | 4/29/2024          |
| JDu202012207/Report | develop | 5c076afbe3f51057e7ef3a7631c50fe109ed895c | Merge branch 'feat-chapter05' of https://github.com/los-seniors-v2/Report into develop | -                          | 4/29/2024          |

Ahora, se mostrarán los commits más importantes para el arreglo según las observaciones hechas a la Landing Page:

| Repository                   | Branch | Commit ID                                | Commit Message | Commit Message Body                    | Commited on (Date) |
|------------------------------|--------|------------------------------------------|----------------|----------------------------------------|--------------------|
| s4ck1to99/LandingPageFlexPal | master | 51d1e22858cd8356c12bc86d530eda3935e6b3e5 | refactor       | Language spanish to english index.html | 25/9/2024          |

Por último, se mostrarán los commits más importantes para la implementación de la Front End Application:

| Repository               | Branch  | Commit ID                                | Commit Message                                                                                              | Commit Message Body | Commited on (Date) |
|--------------------------|---------|------------------------------------------|-------------------------------------------------------------------------------------------------------------|---------------------|--------------------|
| JDu202012207/FrontEndApp | develop | b42abd3bba01d16451479486cdf2f645a04ee0b8 | Merge branch 'develop-feat-calendar' of https://github.com/los-seniors-v2/FrontEndApp into develop-features | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | 0c71952838b8b24354a85f080a5e5d5c61296f6f | Merge(coach-book-a-session): merging develop-features.                                                      | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | b60a6a683a57fd1846c92a34dc178398222c197d | feat(coach-register): merging develop-features.                                                             | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | a462141f1691d2088990c2f1368e90fe2aeb6d92 | feat(food-items): merging develop-features.                                                                 | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | d7e07b9e25701116aadadf8aa1d5899d27fb60e2 | feat(membership): merging develop-features.                                                                 | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | ebd6d62b629882a357f5b253c07b6d34439ee16a | feat(routines): merging develop-features.                                                                   | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | 7ef52c3ca1034b0d81cc3bf170dc0b325b314408 | fix: fixed merging develop-features.                                                                        | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | e78c9c50638df5b9078dc3b50d0762c06bea697d | Merge branch 'develop-feat-session' of https://github.com/los-seniors-v2/FrontEndApp into develop-features  | -                   | 4/29/2024          |
| JDu202012207/FrontEndApp | develop | 4d6b89ce8efb40d60e614c3b133f65f06eb5859c | fix: fixed merging develop-features.                                                                        | -                   | 4/29/2024          |


#### 5.2.2.4.Testing Suite Evidence for Sprint Review.
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page y la Front End Application. Se ofrecerá más información sobre la aplicación en una etapa posterior del desarrollo.
#### 5.2.2.5.Execution Evidence for Sprint Review.
En esta entrega, el equipo de desarrolladores de FlexPal ha completado con éxito la implementación y el lanzamiento de la página de la Landing Page. Esta página presenta diferentes secciones que brindan información detallada sobre nuestro producto.
![Evidencia1](assets/img/evidencia-landing-page-home-sprint2.png)
![Evidencia2](assets/img/evidencia-landing-page-aboutus-sprint2.png)
![Evidencia3](assets/img/evidencia-landing-page-subscriptions-sprint2.png)
![Evidencia4](assets/img/evidencia-landing-page-user-testimonials-sprint2.png)
![Evidencia5](assets/img/evidencia-landing-page-contact-us-sprint2.png)
![Evidencia6](assets/img/evidencia-landing-page-footer-content-sprint2.png)

También se ha completado la implementación de la Front End Application, que presenta una interfaz de usuario interactiva y funcionalidades básicas para los usuarios. A continuación, se presentan algunas capturas de pantalla de la aplicación en funcionamiento:
![Evidencia7](assets/img/evidencia-food-list-frontendapp.png)
![Evidencia8](assets/img/evidencia-frontendapp-1.png)
![Evidencia9](assets/img/evidencia-frontendapp-2.png)
![Evidencia10](assets/img/evidencia-frontendapp-3.png)
![Evidencia11](assets/img/evidencia-frontendapp-4.png)
![Evidencia12](assets/img/evidencia-frontendapp-5.png)

#### 5.2.2.6.Services Documentation Evidence for Sprint Review.
En este sprint, hemos podido desplegar una Web Application que consume json como data para mostrárselos al usuario, a continuación se muestra el código de la aplicación:

| Nombre del Endpoint        | Acciones Implementadas | Sintaxis de Llamada                                                   | Especificación de Parámetros                         | Ejemplo de Llamada                                                                                                                                                                                                                                                                                                             | Explicación del Response                                                                                                                      |
|----------------------------|------------------------|-----------------------------------------------------------------------|------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| member-api.service.json    | GET                    | (Not used)                                                            | Ya que es un GET, los parámetros que se piden son id | Language spanish to english index.html                                                                                                                                                                                                                                                                                         | En este caso, se está devolviendo el valor de todos los objetos "coaches" alojados en el json con el nombre 'member-api.service.json'.        |
| coach-api.service.json     | GET                    | ```axios.get("src/app/services/coach-api.service.json")```            | Ya que es un GET, los parámetros que se piden son id | ```fetchCoaches() {```<br>```axios.get("src/app/services/coach-api.service.json")```<br>```.then(response => {```<br>```console.log(response.data);```<br>```this.coaches = response.data.coaches;```<br>```})```<br>```.catch(error => {```<br>```console.error('Error fetching coaches:', error);```<br>```});```<br>```}``` | En este caso, se está devolviendo el valor de todos los objetos "coaches" alojados en el json con el  nombre 'coach-api.service.json'. |
| routines-api.service.json  | GET                    | ```fetch('src/app/routines/services/routines-api.service.json')```    | Ya que es un GET, los parámetros que se piden son id | ```fetch('src/app/routines/services/routines-api.service.json')```<br>```.then(response => response.json())```<br>```.then(data => {```<br>```this.routines = data;```<br>```});```                                                                                                                                            | En este caso, se está devolviendo el valor de todos los objetos "routines" alojados en el json con el nombre 'routines-api.service.json'. |
| food-item-api.service.json | GET                    | ```fetch('/src/app/food-item/services/food-item-api.service.json')``` | Ya que es un GET, los parámetros que se piden son id | ```fetch('/src/app/food-item/services/food-item-api.service.json')```<br>```.then(response => response.json())```<br>```.then(data => {```<br>```this.foodItems = data;```<br>```});```                                                                                                                                        | En este caso, se está devolviendo el valor de todos los objetos "food-item" alojados en el json con el nombre 'food-item-api.service.json'.   |

A continuación, fotos de como lucen los endpoints dentro de nuestro código y el lugar donde se está consumiendo la data en nuestra web application:

## Coach

![Evidencia7](assets/img/endpoint-screenshot-coachs.png)
![Evidencia12](assets/img/evidencia-frontendapp-5.png)

## Food card

![Evidencia8](assets/img/endpoint-screenshot-food.png)
![Evidencia7](assets/img/evidencia-food-list-frontendapp.png)

## Member
![Evidencia9](assets/img/endpoint-screenshot-member.png)

## Routine
![Evidencia10](assets/img/endpoint-screenshot-routines.png)
![Evidencia9](assets/img/evidencia-frontendapp-2.png)


- - -

### 5.2.3. Sprint 3
En esta sección se registra y explica el avance en términos de producto y trabajo colaborativo para el Sprint 3. Incluye como secciones internas: Sprint Planning 3, Sprint Backlog 3, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, junto con Team Collaboration Insights during Sprint
#### 5.2.3.1.Sprint Planning 2.

<table  style="text-align: center;">
    <tbody>
        <tr>
			<td colspan="1">Sprint #</td>
            <td colspan="1"> Sprint 3 </td>
		</tr>
        <tr>
			<td colspan="2">Sprint Planning Background </td>
		</tr>
        <tr>
			<td colspan="1">Date</td>
            <td colspan="1"> 2024-06-01 </td>
		</tr>
        <tr>
			<td colspan="1">Time</td>
            <td colspan="1"> 10:00 PM </td>
		</tr>
        <tr>
			<td colspan="1">Location</td>
            <td colspan="1">Microsoft Teams (Reunion virtual)</td>
		</tr>
        <tr>
			<td colspan="1">Prepared By</td>
            <td colspan="1">Pescoran Angulo, Juan Fabritzzio</td>
		</tr>
        <tr>
			<td colspan="1"> Attendees (to planning meeting)</td>
            <td colspan="1">Carpio Cornejo, Miguel Angel Jesus / Cueto Dominguez, Juan Diego / Sanchez Zamora Fabrizio Alessandro / Paredes Zapata, Luiggi Gianfranco /  Velasquez Chambi, Ruben Genaro </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 2 – 1 Review Summary </td>
            <td colspan="1">Se alcanzaron los objetivos: Funcionamiento y despliegue de nuestra Web API, </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 1 – 1 Retrospective Summary </td>
            <td colspan="1">Comparado a otros sprints, este es el más trabajoso comparado a los demás, pues se necesitaba la parte de Backend, teniendo terminado el report, el Front End, y la landing page. En palabras de nuestro nuevo integrante Ruben: "No podemos descuidarnos, solo tenemos esta revisión para luego tener nuestro producto listo, no podemos desaprovechar ello."</td>
		</tr>
         <tr>
			<td colspan="2">Sprint Goal & User Stories </td>
		</tr>
         <tr>
			<td colspan="1">Sprint 3 Goal</td>
            <td colspan="1">Para este sprint se requiere el cumplimiento de los siguientes objetivos: Mejoramiento de la Front End, añadiendo la implementación de los mockups pertenecientes al reporte y el cumplimiento total dela creación del backend.</td>
		</tr>
        <tr>
			<td colspan="1">Sprint 3 Velocity </td>
            <td colspan="1">Para este sprint se han elegido 10 Technical Stories que tienen 5 Story points cada uno.</td>
		</tr>
        <tr>
			<td colspan="1">Sum of Story Points </td>
            <td colspan="1">50</td>
		</tr>
</tbody>
</table>

#### 5.2.3.2.Sprint Backlog 3.

En este tercer sprint el equipo se ha enfocado en el mejoramiento de la Landing Page, el reporte, Front End Application y el Back End. A continuación, se presenta el backlog de tareas para el Sprint 3:
[Link para ingresar al board del tecer Sprint](https://trello.com/b/5bsUVC3d/flexpal-sprint-2)

![trello-screenshot](assets/img/img.png)

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 3</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>TS037</td>
			<td>Implementar Autenticación de Dos Factores</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, quiero implementar la autenticación de dos factores, para mejorar la seguridad de la plataforma.</td>
			<td>6</td>
			<td>All team members</td>
			<td>To-Do</td>
		</tr>
		<tr>
			<td>TS038</td>
			<td>Desarrollar Funcionalidad de Notificaciones</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, quiero desarrollar la funcionalidad de notificaciones, para mantener a los usuarios informados sobre eventos importantes.</td>
			<td>6</td>
			<td>All team members</td>
			<td>To-Do</td>
		</tr>
		<tr>
			<td>TS033</td>
			<td>Corregir Errores Reportados por QA</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, quiero corregir los errores reportados por el equipo de control de calidad (QA), para mejorar la calidad del software.</td>
			<td>2</td>
			<td>All team members</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>TS039</td>
			<td>Crear Herramientas de Monitoreo y Depuración</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero crear herramientas de monitoreo y depuración, Para facilitar la identificación y resolución de problemas.</td>
			<td>2</td>
			<td>All team members</td>
			<td>To-Review</td>
		</tr>
		<tr>
			<td>TS040</td>
			<td>Implementar Pruebas de Integración Continua</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero implementar pruebas de integración continua, Para garantizar la estabilidad del sistema durante el desarrollo.	</td>
			<td>2</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>TS036 </td>
			<td>Refactorizar Código para Mejorar Mantenibilidad</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero refactorizar el código existente, Para mejorar su estructura y facilitar el mantenimiento futuro.</td>
			<td>8</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>TS035</td>
			<td> Integrar Sistema con Servicio Externo</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero integrar el sistema con un servicio externo, Para ampliar la funcionalidad y mejorar la interoperabilidad.</td>
			<td>4</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>TS034</td>
			<td>Optimizar el Rendimiento del Sistema</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero optimizar el rendimiento del sistema, Para garantizar una experiencia fluida para los usuarios.	</td>
			<td>8</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>TS032</td>
			<td>Implementar Funcionalidad Esencial</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero implementar la funcionalidad esencial del sistema, Para tener una base funcional sobre la cual construir.</td>
			<td>8</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>TS031</td>
			<td>Configurar Entorno de Desarrollo</td>
			<td></td>
			<td></td>
			<td>Como desarrollador, Quiero configurar mi entorno de desarrollo local, Para poder comenzar a trabajar en el proyecto.</td>
			<td>1</td>
			<td>All team members</td>
			<td>Done</td>
		</tr>        
    <tbody>
</table>

#### 5.2.3.3.Development Evidence for Sprint Review.

<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="27" align="center">https://github.com/los-seniors-v2/flex-pal-platform</td>
    <td align="center"> main</td>
    <td align="center">eb600a8210920d357cca6c316d4eb5f8dc607123</td>
    <td align="center"> chore: initial commit</td>
    <td align="center">---</td>
    <td align="center"> 29/05/2024</td>
  </tr>

  <tr>
    <td align="center">develop</td>
    <td align="center" > 714a1a596469dd157fcc2341f1e471def2c7d989</td>
    <td align="center"> chore: Added basic dependencies</td>
    <td align="center">---</td>
    <td align="center"> 29/05/2024</td>
  </tr>

   <tr>
    <td align="center">develop</td>
    <td align="center" > 0db0fb88782353a2fd5a185ac38dc800a7de4f83</td>
    <td align="center"> feat: implement bounded context shared</td>
    <td align="center"> ---</td>
    <td align="center"> 29/05/2024</td>
  </tr>

   <tr>
    <td align="center">feature/profiles</td>
    <td align="center" > 85f2f70a1ef4def24179cefad1f87747159215cb</td>
    <td align="center">feat(domain): add profile model</td>
    <td align="center">--- </td>
    <td align="center"> 30/05/2024</td>
  </tr>

   <tr>
    <td align="center">feature/profiles</td>
    <td align="center">c9377ce962d28ea7e2221f0fd562d686ddc74916</td>
    <td align="center">feat: add infrastructure layer and interfaces without API controller implementation </td>
    <td align="center"> ---</td>
    <td align="center"> 30/05/2024</td>
  </tr>

  <tr>
    <td align="center">feature/profiles</td>
    <td align="center" > 982bf7a7f2b596ced87e6e76d06b1015ec82b65b</td>
    <td align="center">feat(profile): add PUT method in bounded context</td>
    <td align="center"> ---</td>
    <td align="center"> 30/05/2024</td>
  </tr>

   <tr>
    <td align="center">feature/iam</td>
    <td align="center" > 7fd2c641b79a56f520671013685fbc21a5d99017</td>
    <td align="center">feat(iam): add application and domain layers to bounded context</td>
    <td align="center"> ---</td>
    <td align="center"> 31/05/2024</td>
  </tr>

   <tr>
    <td align="center">feature/iam</td>
    <td align="center" > 609588dcb68103d64f55336dcc53df2540048601</td>
    <td align="center">feat(iam): implement register logic using ACL between IAM and profile, needs refactoring</td>
    <td align="center"> ---</td>
    <td align="center"> 01/05/2024</td>
  </tr>

  <tr>
    <td align="center">feature/couseling</td>
    <td align="center" > 66bad6ff146c2343539b7ce0b9925814a998908a</td>
    <td align="center">feat(counseling): add directories for DDD</td>
    <td align="center"> ---</td>
    <td align="center"> 01/05/2024</td>
  </tr>

   <tr>
    <td align="center">feature/profile</td>
    <td align="center" > 94269d701fac07ff153e16a383e9c44f56e1d470</td>
    <td align="center">refactor(profile): add documentation and error handling</td>
    <td align="center"> ---</td>
    <td align="center"> 02/05/2024</td>
  </tr>

  <tr>
    <td align="center">feature/couseling</td>
    <td align="center" > ca7d8bbf6e1daff1f935c755cc72b23b7365ff0a</td>
    <td align="center">feat(counseling): add required DDD classes</td>
    <td align="center"> ---</td>
    <td align="center"> 02/05/2024</td>
  </tr>

</table>

#### 5.2.3.4.Testing Suite Evidence for Sprint Review.
Se ha omitido esta sección, puesto que aún no se dispone con el conocimiento para realizar pruebas de tests automatizados, que están planeadas en realizarse en el siguiente sprint.
#### 5.2.3.5.Execution Evidence for Sprint Review.
En esta entrega, el equipo de desarrolladores de FlexPal ha completado con éxito la implementación de la página del Back end Application. Esta página presenta diferentes secciones que brindan información detallada sobre nuestro producto.

![Web-API-screenshot1](assets/img/img_1.png)
![Web-API-screenshot1](assets/img/img_2.png)
![Web-API-screenshot1](assets/img/img_3.png)
![Web-API-screenshot1](assets/img/img_4.png)
![Web-API-screenshot1](assets/img/img_5.png)
![Web-API-screenshot1](assets/img/img_6.png)

Por parte de la base de datos:

![Database](assets/img/img_7.png)

#### 5.2.3.6.Services Documentation Evidence for Sprint Review.
En este sprint, hemos podido desplegar una Web Application que consume json como data para mostrárselos al usuario, a continuación se muestra el código de la aplicación:

| Nombre del Endpoint | Acciones Implementadas | Sintaxis de Llamada                                                                                                                                                                                        | Especificación de Parámetros                                                                                                                                                                                                                                                    | Ejemplo de Llamada | Explicación del Response                                                                                                                 |
|---------------------|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Coach               | POST, GET              | POST: ```/api/v1/coaches```, GET: ```/api/v1/coaches/{coachId}```                                                                                                                                          | GET: ```"id": int```, POST: ```"firstName": "string", "lastName": "string", "email": "string", "phone": "string", "knowledge": "string"```                                                                                                                                      | -                  | En este caso, se está devolviendo el valor de todos los objetos "coaches" alojados en el json con el nombre 'api/v1/coach'.              |
| FitnessPlan         | POST, GET              | POST: ```/api/v1/fitness-plans```, ```/api/v1/fitness-plans{fitnessPlanId}/routine-items```, ```/api/v1/fitness-plans{fitnessPlanId}/nutritional-meals```  GET: ```/api/v1/fitness-plans{fitnessPlanId}``` | GET: ```"id": int```, POST: ```"profileId": 0, "coachId": 0```, ```"name": "string", "sets": 100, "reps": 100, "type": "string", "restTime": 600```, ```"name": "string", "weight": 10000```                                                                                    | -                  | En este caso, se está devolviendo el valor de todos los objetos "fitness-plan" alojados en el json con el  nombre 'api/v1/fitness-plan'. |
| Profiles            | POST, GET, PUT         | POST: ```/api/v1/profiles```, GET: ```/api/v1/profiles```, ```/api/v1/profiles/{profileId}```, PUT: ```/api/v1/profiles/{profileId}```                                                                     | GET: ```"id": int```, POST: ```"firstName": "string", "lastName": "string", "email": "string", "weight": "string", "height": "string", "phone": "string", "role": "string"```, PUT: ```"id": 0, "email": "string", "weight": "string", "height": "string", "phone": "string"``` | -                  | En este caso, se está devolviendo el valor de todos los objetos "perfiles" alojados en el json con el nombre 'api/v1/profiles'.          |
| Users               | POST, GET              | POST: ```/api/v1/users```, ```/api/v1/users/register```, ```/api/v1/users/login```, GET: ```/api/v1/users/{userId}```                                                                                      | GET: ```"id": int```, POST: ``````                                                                                                                                                                                                                                              | -                  | En este caso, se está devolviendo el valor de todos los objetos "user" alojados en el json con el nombre 'api/v1/users'.                 |

#### 5.2.3.7.Software Deployment Evidence for Sprint Review.

Para el despliegue de nuestra Front End App, se usó: 

![Netlify](assets/img/img_9.png)
![Netlify2](assets/img/img_10.png)

Para el despliegue de nuestra aPI se usó: [SmarterAsp](https://www.smarterasp.net/)

![SmarterASP](assets/img/img_8.png)

#### 5.2.3.8.Team Collaboration Insights during Sprint.
A continuación todos los analíticos que nos proporciona Github, en su apartado de Insights, sobre la colaboración del equipo durante el Sprint 3:
![analytics-5-report](assets/img/img_11.png)


### 5.2.4. Sprint 4
En esta sección se explicaran los detalles presentados y analizados durante la reunión del Sprint Planning para el número 4. El objetivo principal de esta reunión es establecer un plan claro y realista para el sprint, identificando las tareas a realizar y comprometiéndose con un conjunto de entregables concretos que contribuyan al avance del proyecto. A continuación, se presenta el resumen del Sprint Planning Meeting, que proporcionará una visión general de los temas discutidos y las decisiones tomadas durante la reunión. <br>
#### 5.2.4.1. Sprint Planning 4.
En esta sección se explicaran los detalles presentados y analizados durante la reunión del Sprint Planning para el número 4. El objetivo principal de esta reunión es establecer un plan claro y realista para el sprint, identificando las tareas a realizar y comprometiéndose con un conjunto de entregables concretos que contribuyan al avance del proyecto. A continuación, se presenta el resumen del Sprint Planning Meeting, que proporcionará una visión general de los temas discutidos y las decisiones tomadas durante la reunión. <br>
<br>Tabla del planeamiento a profundidad del Sprint 4. <br>

<table>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 4</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>22-06-2024</td>
        </tr>
          <tr>
            <td>Time</td>
            <td>20:52</td>
        </tr>
            <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
            <tr>
            <td>Prepared by</td>
            <td>Sanchez Zamora, Fabrizio Alessandro</td>
        </tr>
            <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Carpio Cornejo, Miguel Angel Jesus / Cueto Dominguez, Juan Diego / Sanchez Zamora Fabrizio Alessandro / Paredes Zapata, Luiggi Gianfranco / Velasquez Chambi, Ruben Genaro</td>
        </tr>
            <tr>
            <td>Sprint 4 Review Summary</td>
            <td>Para este Sprint 4, nuestro enfoque principal fue mejorar e implementar características que se habían desarrollado en entregables anteriores. En el lado del frontend de nuestra aplicación, trabajamos en temas como la navegación por rutas y la refactorización de componentes mínimos. Por otro lado, en el backend, nos centramos en la autenticación del usuario mediante Json Web Token y en la creación de rutinas para cada usuario. En resumen, en este sprint 4 se han agregado tanto detalles mínimos pendientes como aspectos clave para nuestra aplicación web.</td>
        </tr>
            <tr>
            <td>Sprint 4 Retrospective Summary</td>
            <td> En la retrospectiva del Sprint 4, evaluamos en grupo la planificacíon de nuestro tiempo para llegar a una correcta organización. Hicimos uso de la herramienta Trello nuevamente para asignar tareas y coordinarlas, lo que tuvo como resultado un mejor control sobre nuestro proyecto. Además, optamos por dividir las tareas en procesos más pequeños para trabajar de manera más eficiente. Esta estrategia nos ayudó a abordar nuestro proyecto grande dividiéndolo en partes más manejables.       </td>
            </tr>
            <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
              <tr>
            <td>Sprint 4 Goal</td>
            <td>Para este últimos sprint, se tuvo como objetivo culminar con los puntos pendientes mejorar nuestro reporte del trabajo, asi como un enfoque especia en el desarrollo de funcionalidades finales del lado fronted y backend de nuestra aplicación. Dichos objetivos se lograron gracias a las reuniones semanales que se hicieron a lo largo del plazo dado para este entregable.  </td>
        </tr>
              <tr>
            <td>Sprint 4 Velocity</td>
            <td>Para este Sprint 4, nuestro Sprint 4 Velocity es de 8 puntos.</td>
        </tr>
              <tr>
            <td>Sum of Story Points</td>
            <td>La suma de las historias de usuario para el Sprint 4, alcanza un valor de 65 puntos en total</td>
        </tr>
    </table>

#### 5.2.4.2. Sprint Backlog 4.
En esta sección se revisará todo el proceso dado para el Sprint Backlog 4, en el cual nuestro equipo de trabajo se centró principalmente en la implementación de los puntos faltantes de la entrega anterior tales como autenticacion de usuarios y funcionalidades del lado backend, además de haber realizado una correcta comunicación entre el FrontEnd y el BackEnd de manera estable. Para este sprint, hemos separado toda la construcción de la aplicación en 7 historias de usuario, donde cada integrante del grupo hizo al menos uno. Gracias a este proceso, para el final del Sprint Backlog 4, hemos conseguido tener una página web estable, con buenos modelos de interfaz, conexiones con APIs externas, y entre otros. <br>

*Tabla principal del planeamiento del Sprint Backlog 4.* <br>

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 4</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>US01</td>
			<td>Iniciar Sesión</td>
			<td>TS01</td>
			<td>Implementacion de inicio de sesion del usuario</td>
            <td>Como usuario registrado, Quiero poder iniciar sesión en la plataforma, Para acceder a mi cuenta y utilizar las funciones disponibles.	</td>
			<td>4</td>
			<td>Ruben</td>
			<td>Done</td>
		</tr >
        <tr>
			<td>US02</td>
			<td>Recuperar Contraseña	</td>
			<td>TS02</td>
			<td>Funcion para recuperar una contraseña en caso el usuario la olvide</td>
            <td>Como usuario de la plataforma, Quiero poder recuperar mi contraseña olvidada, Para poder acceder nuevamente a mi cuenta.		</td>
			<td>1</td>
			<td>Ruben</td>
			<td>Done</td>
		</tr>
        <tr>
			<td>US010</td>
			<td>Programar Sesiones de Entrenamiento</td>
			<td>TS03</td>
			<td>Funcionalidad que permite a los usurios crear sesiones de entrenamiento</td>
            <td>Como usuario, Quiero programar una sesión de entrenamiento con un coach, Para recibir orientación personalizada.		</td>
			<td>4</td>
			<td>Luiggi</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>US011</td>
			<td>Seguir Rutinas de Ejercicio	</td>
			<td>TS04</td>
			<td>Sección que permite a los usuarios visualizar las rutinas recomendadas por los coach de entrenamiento</td>
            <td>Como usuario, Quiero poder seguir rutinas de ejercicio recomendadas por mi coach, Para mejorar mi rendimiento físico.</td>
			<td>2</td>
			<td>Juan Diegp</td>
			<td>Done</td>
		</tr>
        <tr>
			<td>US015	</td>
			<td>Visualizar Planes de Nutrición	</td>
			<td>TS05</td>
			<td>Sección de la app que contiene los diversos planes de nutricion disponibles</td>
            <td>Como usuario, Quiero visualizar los planes de nutrición personalizados, Para tener una guía alimentaria adaptada a mis necesidades.	</td>
			<td>2.5</td>
			<td>Miguel</td>
			<td>Done</td>
		</tr>
        <tr>
			<td>BS019	</td>
			<td>Visualizar Calendario de Sesiones		</td>
			<td>TS06</td>
			<td>Funcionalidad que se encuentra en el sector de perfil y permite ver el calendario de sesiones programadas</td>
            <td>Como coach, Quiero visualizar un calendario con las sesiones programadas de mis clientes, Para organizar mi agenda y planificar las sesiones.		</td>
			<td>3</td>
			<td>Fabrizio</td>
			<td>Done</td>
		</tr>
        <tr>
			<td>BS028	</td>
			<td>Gestionar Información del Perfil</td>
			<td>TS07</td>
			<td>Seccion destinada a gestionar informacion  del cliente en caso lo necesite </td>
            <td>Como coach, Quiero gestionar la información de mi perfil, Para mantener actualizados mis datos personales y de contacto.			</td>
			<td>1</td>
			<td>Juan Pescoran</td>
			<td>Done</td>
		</tr>
     <tbody>
</table>

Con el fin de que la lista de tareas en el sprint pueda ser visualizada a más profundidad, se mostrara un enlace directo a la sección de trabajo designada por el equipo junto a todas las actividades de forma completa. Hemos usado Trello como nuestra herramienta para planificar actividades: [Link Para ingresar a trello](https://trello.com/invite/b/gGX8tUs5/ATTI7e8b3e5d487b49012e6ef9ae6f2da419F8FE8291/tareas-para-aplicaciones-web) <br><br>
![trello-screenshot](assets/img/img_12.png)

#### 5.2.4.3. Development Evidence for Sprint Review.
En esta sección, se describen los avances en la implementación de los productos de la solución relacionados con los Web Services, según el alcance del Sprint 4. Aquí se presentarán los commits ya implementados en el repositorio de GitHub, junto con toda la información relevante y los cambios realizados.

Tabla de los commits realizados y relacionados con el desarrollo de todas las secciones del Sprint Backlog 4.

| Repository         | Branch                | Commit Id                                         | Commit Message                                                                    | Commit Message Body                                  | Commited on (Date) |
|--------------------|-----------------------|---------------------------------------------------|-----------------------------------------------------------------------------------|------------------------------------------------------|--------------------|
| LamdingPageFlexPal | master                | fcfc3a4efbdb2aa1e9663fbb64c172caaa409740          | feat: added videos and hyperlink button                                           | Adding Videos and Hyperlinks to the evidence section | 17/06/2024         |
| LamdingPageFlexPal | master                | 0ea58cf3cb7e83da6e0eede3a673dd4189845725          | refactor: login link updated.                                                     | Updating login link from navbar                      | 18/06/2024         |
| LamdingPageFlexPal | master                | d98dd3d9b2491638cd06b1a1edd6264f4c781ab6          | fix: login url fixed.                                                             | Fixing login link                                    | 18/06/2024         |
|    FrontEndApp      | develop-fixing        | cc14c8459cd01b03f41b03fc26284cb2db01b65d          | refactor: login and register components updated.                                  | Adding Componnets for login and register             | 18/06/2024         |
|    FrontEndApp      | develop               | 125dab7                                           | feat(app-login): merging with backend                                             | Merging with Backend                                 | 23/06/2024         |
|    FrontEndApp      | develop               | feat: implemented connections to the app-service. | feat: implemented connections to the app-service.                                 | Adding Connections to the app-service                | 23/06/2024         |
| flex-pal-platform  | feature/iam           | 25a39204236e3b47f354bf82f799e875b48b24ff          | feat: Create and develop iam bounded context, and functional                      | Adding Bounded Context Iam                           | 17/06/2024         |
| flex-pal-platform  | feature/iam           | 3b3c50915ed47381e1bc6bbcbd0d3e8516180d88          | fix: Role cannot be null fixed                                                    | Fixing Role error                                    | 17/06/2024         |
| flex-pal-platform  | feature/iam           | 1ef812b7dd0ec4301b365888088c3014c2760414          | fix: Post sign-in fixed with builder of tokensettings                             | Fixing POST Sign In error                            | 17/06/2024         |
| flex-pal-platform  | feature/susbscription | 4ac3884ec19944ec5f144571bb25184c3a55b287          | refactor: database conection schema name is flex-pal-wa and password 12345678     | Adding Database Connection                           | 17/06/2024         |
| flex-pal-platform  | feature/susbscription | 626018e9aeb08778de1fc4af94aaa69991af977b          | feat(subscription): added services and entities tables for subscription aggregate | Adding Services and entitites tables                 | 17/06/2024         |
| flex-pal-platform  | feature/susbscription | acc8d61ea101b39366d827971f3d2214b708cefa          | fix: post method in controller                                                    | Adding Post Method controller                        | 17/06/2024         |
| flex-pal-platform  | feature/susbscription | 0f7832dc6dff0b4f0e801d74b0584b5957b2ab6c          | feat: add procfile to deploy                                                      | Adding Profile Deployment                            | 18/06/2024         |






#### 5.2.4.4. Testing Suite Evidence for Sprint Review.
#### 5.2.4.5. Execution Evidence for Sprint Review.
#### 5.2.4.6. Services Documentation Evidence for Sprint Review.
En esta sección, se describen los EndPoints documentados con OpenAPI mediante la herramienta Swagger para el sprint 4. Esto permite una visualización clara de los puntos de acceso de la API y sus características. Además, se adjuntan evidencias de la implementación de dichos EndPoints. <br><br>
![Swagger_Imagw1](assets/img/service01.png)
![Swagger_Imagw2](assets/img/service02.png)

| Nombre del Endpoint | Acciones Implementadas | Sintaxis de Llamada                                                                                                                                                                                        | Especificación de Parámetros                                                                                                                                                                                                                                                    | Ejemplo de Llamada | Explicación del Response                                                                                                                 |
|---------------------|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Coach               | POST, GET              | POST: ```/api/v1/coaches```, GET: ```/api/v1/coaches/{coachId}```                                                                                                                                          | GET: ```"id": int```, POST: ```"firstName": "string", "lastName": "string", "email": "string", "phone": "string", "knowledge": "string"```                                                                                                                                      | -                  | En este caso, se está devolviendo el valor de todos los objetos "coaches" alojados en el json con el nombre 'api/v1/coach'.              |
| FitnessPlan         | POST, GET              | POST: ```/api/v1/fitness-plans```, ```/api/v1/fitness-plans{fitnessPlanId}/routine-items```, ```/api/v1/fitness-plans{fitnessPlanId}/nutritional-meals```  GET: ```/api/v1/fitness-plans{fitnessPlanId}``` | GET: ```"id": int```, POST: ```"profileId": 0, "coachId": 0```, ```"name": "string", "sets": 100, "reps": 100, "type": "string", "restTime": 600```, ```"name": "string", "weight": 10000```                                                                                    | -                  | En este caso, se está devolviendo el valor de todos los objetos "fitness-plan" alojados en el json con el  nombre 'api/v1/fitness-plan'. |
| Profiles            | POST, GET, PUT         | POST: ```/api/v1/profiles```, GET: ```/api/v1/profiles```, ```/api/v1/profiles/{profileId}```, PUT: ```/api/v1/profiles/{profileId}```                                                                     | GET: ```"id": int```, POST: ```"firstName": "string", "lastName": "string", "email": "string", "weight": "string", "height": "string", "phone": "string", "role": "string"```, PUT: ```"id": 0, "email": "string", "weight": "string", "height": "string", "phone": "string"``` | -                  | En este caso, se está devolviendo el valor de todos los objetos "perfiles" alojados en el json con el nombre 'api/v1/profiles'.          |
| Users               | POST, GET              | POST: ```/api/v1/users```, ```/api/v1/users/register```, ```/api/v1/users/login```, GET: ```/api/v1/users/{userId}```                                                                                      | GET: ```"id": int```, POST: ``````                                                                                                                                                                                                                                              | -                  | En este caso, se está devolviendo el valor de todos los objetos "user" alojados en el json con el nombre 'api/v1/users'.                 |
#### 5.2.4.7. Software Deployment Evidence for Sprint Review.
Para este sprint 4, se realizo un deploy de los elementos faltantes, como la autenticación de usuarios y funcionalidades del lado backend. Se logró una correcta comunicación entre el FrontEnd y el BackEnd de manera estable.<br><br>

### Fronted Deployment
![Netlify](assets/img/img_9.png)
![Netlify2](assets/img/img_10.png)
### Backend Deployment
![Image1](assets/img/DP01.jpg)
![Image2](assets/img/DP02.jpg)
### Database Deployment
![Image3](assets/img/DP03.jpg)
![Image4](assets/img/DP04.jpg)
![Image5](assets/img/DP05.jpg)
![Image6](assets/img/DP06.jpg)
#### 5.2.4.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.
#### Saludo y presentación
Comenzamos con una introducción breve de los entrevistados para recordar quiénes son ya que han sido entrevistados anteriormente.

1. ¿Cómo se llama?
2. ¿Cuántos años tiene?
3. ¿En qué distrito vive?

#### Preguntas
Estas preguntas nos ayudarán a saber cuál es la experiencia de usuario, si nuestro producto llenó las expectativas del usuario, y también saber las posibles mejoras, comentarios y quejas sobre nuestro producto.

1. ¿Qué piensas de la interfaz de usuario de la aplicación web? ¿Es fácil de navegar?
2. ¿Encuentras que las funciones de la aplicación web son intuitivas y fáciles de usar?
4. ¿Hay alguna función que crees que debería estar en la aplicación web que actualmente no está?
5. ¿Cómo calificarías la experiencia general de uso de la aplicación web?
6. ¿Qué te gusta más y qué te gusta menos de la aplicación web?
7. ¿Te sentirías cómodo usando regularmente nuestra aplicación web?
8. ¿Cómo crees que nuestra aplicación web se comparan con otras similares que hayas utilizado?
9. ¿Hay algo que te confunda o te resulte difícil de entender en la aplicación web?
10. ¿Considerarías recomendarnos a tus amigos o familiares?
11. ¿Tienes alguna sugerencia para mejorar la experiencia del usuario en nuestra aplicación web?

#### 5.3.2. Registro De Entrevistas
![RegistroEntrevistas](assets/img/img_8.png) <br> <br>
https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/EZMU38BmzmtDmzICiRP9ypgBmH5pYGdeA2ogPTberO5h1g?e=CHMn4l&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

#### 5.3.3. Evaluaciones según heurísticas.

### 5.4 Video About-the-Product.

![AboutProduct](assets/img/img_8.png) <br>
#### YouTube
https://youtu.be/7yi8_0qWF7k



### Conclusiones y Recomendaciones
- Durante el desarrollo de la Landing Page, el equipo de FlexPal ha logrado implementar con éxito las funcionalidades y características planificadas, proporcionando una experiencia de usuario sólida y coherente.
- La implementación de la Landing Page ha permitido al equipo demostrar su capacidad para traducir los requisitos y especificaciones en código funcional, desarrollando una estructura sólida y un diseño visual atractivo.
- La colaboración y el trabajo en equipo han sido fundamentales para el éxito del proyecto, permitiendo a los miembros del equipo compartir conocimientos, habilidades y recursos para lograr los objetivos establecidos.
- La implementación de la Landing Page ha sentado las bases para el desarrollo de la Web Application, que se espera completar en etapas posteriores del proyecto.
- El uso de herramientas de gestión de proyectos como Trello y GitHub ha facilitado la planificación, el seguimiento y la colaboración en el desarrollo del proyecto, permitiendo al equipo mantenerse organizado y enfocado en los objetivos.
- El proceso de desarrollo ágil ha demostrado ser efectivo para la implementación de la Landing Page, permitiendo al equipo adaptarse a los cambios y desafíos de manera eficiente y eficaz.

### Video About-the-Team.
![AboutTeam](assets/img/img_8.png) <br>

#### Microsoft Stream
https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213652_upc_edu_pe/EUzF2s_VeyxLoLS1JP1IQO0BXB_uZv271FQfEF-FVIx-sQ?e=EbCPBk&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
<br> 
#### YouTube
https://youtu.be/y6P2SFQNDK0

### Anexos
- Anexo 1: [Landing Page Repository](https://github.com/los-seniors-v2)
- Anexo 2: [Mockups - Wireframe](https://www.figma.com/file/91Ez19KOQpxgpmPEZ9NtIm/FlexPal?type=design&node-id=0%3A1&mode=design&t=vgM82K5YOfavEdYS-1)
- Anexo 3: [User-Flow - WireFlow Diagram](https://lucid.app/lucidspark/2c642c76-fe1b-41c2-a0e3-613a0b64f8f0/edit?viewport_loc=-1797%2C-1394%2C8704%2C4350%2C0_0&invitationId=inv_0f96f168-1b85-4920-a9fb-ce76f2b42015)
### Bibliografía
- Ipsos. (16 de octubre de 2019). Alimentación y vida saludable en Lima. Ipsos. https://www.ipsos.com/es-pe/alimentacion-y-vida-saludable-en-lima
- Aproximadamente 15 millones de peruanos sufren de obesidad. (4 de marzo de 2024). Noticias - Ministerio De Salud - Plataforma Del Estado Peruano. https://www.gob.pe/institucion/minsa/noticias/915217-aproximadamente-15-millones-de-peruanos-sufren-de-obesidad
- Mena, F. G. (10 de junio de 2019). La realidad de los gimnasios: “80% de peruanos abandona su membresía en los primeros 3 meses.” Gestión. https://gestion.pe/tendencias/realidad-gimnasios-80-peruanos-abandona-membresia-primeros-3-meses-269519-noticia/
