# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
En esta sección veremos diversos puntos acerca de la configuración de las herramientas necesarias para el desarrollo del proyecto, desde la Landing Page hasta el proyecto final con el backend incluído. Se verán las herramientas utilizadas para el diseño UX/UI, Style Guide Conventions, Deployment Configuration y más.
### 5.1.1. Software Development Environment Configuration.

En esta parte del proyecto se verán las herramientas que utilizaremos para cada fase de la creación del proyecto.

**Organización del proyecto**

Para organizarnos en la asignación de tareas fue necesario la creación de reuniones para poder coordinar lo necesario y tener una organización. Para esto usamos:
- **Discord:** Discord es una red social que es útil para crear grupos y comunidades, en este caso usamos la creación de un grupo de Discord para la realización de llamadas grupales.  

**Diseño UX/UI**

Es importante verificar las necesidades de los usuarios a la hora de crear una aplicación, por lo que es necesario la creación de maquetas, wireframes, mockups e interfaces para establecer un estándar que satisfaga a los usuarios. Para ello, utilizaremos diversos software, como:

- **Figma:** Es una aplicación muy útil para diseñar wireframes y mockups, que servirán como una guía para poder realizar el diseño final al pasarlo a código.
- **UXPressia:** Herramienta útil para la creación de User Personas, Emphaty Maps, Journey Mappings, etc. La mayoría de documentación relacionada a la experiencia de usuario se hizo con esta herramienta.
- **Miro:** Una pizarra colaborativa en donde varios usuarios pueden trabajar a la vez para la creación de wireframes, braimstormings, mapas mentales, etc.
- **LucidChart:** Herramienta útil para la realización de diagramas UML, diagramas de flujo, modelos C4, entre otros. Al igual que Miro, varios usuarios pueden colaborar en una misma pizarra.

**Desarrollo del programa**

En esta parte se verán los programas o IDE's utilizados pacra la creación del aplicativo.

- **Visual Studio Code:** Es un IDE con una interfaz muy intuitiva el cual tiene soporte para trabajar con la gran mayoría de lenguajes de programación, además de contar con muchas extensiones que ayudan a que el programador se sienta cómodo.

- **Rider:** IDE que forma parte de JetBrains el cual se especializa en la creación de aplicativos .NET, ASP.NET, .NET CORE entre otros. Se usa como lenguaje principal C#.

- **GitHub:** Usaremos GitHub para controlar el repositorio del proyecto y gestionar las versiones del código y de la documentación en estilo Markdown. Github es una herramienta muy importante para la creación de proyectos ya que ayuda a la colaboración de varios programadores y de el seguimiento de cambios del código.
### 5.1.2. Source Code Management.
| Producto             | Repositorio           | URL                                                                 |
|----------------------|-----------------------|----------------------------------------------------------------------|
| Landing Page         | Landing-Page   | [https://github.com/Grupo01-AplicacionesWeb202501/Landing-Page](https://github.com/Grupo01-AplicacionesWeb202501/Landing-Page)                                                                      |
| Reporte         | Informe   | [https://github.com/Grupo01-AplicacionesWeb202501/Informe](https://github.com/Grupo01-AplicacionesWeb202501/Informe) |

Flujo de trabajo de GitFlow

Nos centraremos en un modelo el cual es muy usado desde el 2010, en donde tendremos en cuenta ramas para producción, pruebas, features, arreglos de bug, entre otros.
<img src= "..\Chapter-V\images\git-model.png" alt="Git Model">

Teniendo en cuenta la imagen, tendremos lo siguiente:
  - Main branch: Será la rama principal, la cual se entregará a producción, es decir, la rama final.
  - Develop branch: Esta rama se encargará de implementar los diversos commits para posteriormente colocarlos en el Main branch.
  - Features branch: Cada feature tendra su propia rama, en donde posteriormente se combinará con el Develop branch. 

### 5.1.3. Source Code Style Guide & Conventions.

Utilizaremos diversos lenguajes de programación, además de usar lenguajes de marcado (HTML) y de estilo (CSS). Utilizaremos también JavaScript, Vue.js, Postman, Node.js, el IDE de Rider y VsCode, PrimeVue, MySQL y servicios .NET.

- **HTML:** HTML o Hyper Text Markup Lenguage, es el lenguaje que utilizaremos para definir el contenido de la página con el uso de etiquetas para colocar texto, imágenes, videos, tablas, etc.

    Es importante tener en cuenta algunas convenciones, como por ejemplo:
  1. Nombres de etiqueta en minúscula.
  2. Cerrar todos los elementos HTML.
  3. Colocar en minúscula el nombre de los atributos de las etiquetas.
  4. Especificar siempre un alto, ancho y alt para imagenes.
  5. Dejar lineas en blanco y sangría para el entendimiento del código.
- **CSS:** CSS o Cascade Style Sheets es el lenguaje que utilizaremos para definir una apariencia al documento HTML, colocando colores, margenes, padding, entre otros.

  Es importante seguir algunas convencionas, como por ejemplo:
  1. Los colores se definirán en una variable *root* para ayudar a la reutilización del código.
  2. El nombre de las clases se separarán con un '-', es decir:
   ```
      .navbar-landing-page {
     
        color: red;
     
        margin: 0;
     
     }
   ```
   3. En gran parte se trabajará con las unidades de medida de rem y de pixeles (px).

- **JavaScript y Vue:** JavaScript es el lenguaje de programación que se usará para poder realizar animaciones y hacer que la aplicación sea dinámica. Vue.js es un framework de JavaScript para crear interfaces de usuario. Se basa en HTML, CSS y JavaScript estándar y proporciona un modelo de programación declarativo basado en componentes que ayuda a desarrollar eficientemente interfaces de usuario de cualquier complejidad.
    1. El nombre de los archivos js deben de estar en minúscula, agregando unicamente - o _.
    2. Los componentes deben de seguir el kebab-case.
        ```
         // bad
        <MyComponent />
        // good
        <my-component />  
### 5.1.4. Software Deployment Configuration.
Para el despliegue inicial del proyecto (Landing Page) utilizaremos Netlify. Netlify es una plataforma de alojamiento web y de desarrollo que permite crear, implementar y gestionar sitios web y aplicaciones web completamente gratuito. 

<img src= "..\Chapter-V\images\netlify.png" alt="Git Model">


## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

| Sprint #            | Sprint 1           |
|----------------------|-----------------------|
| Date          | 13 - 04 - 2025  |                                                                      
| Time         | 7:00 pm   |
| Location | Virtual - Discord |
| Prepared By | Kevin Castañeda Llanos |
| Attendees | Kevin Alexander Castañeda Llanos, Adrian Alonso Calle Huayanca, Renzo José Araujo Ingunza, Rodrigo Nicolas Mechan Chumpitaz, Rodrigo Jesús Miraval Pomalaya |
| Sprint n - 1 Review Summary | Este es el primer sprint, por lo que este campo no aplica | 
| Sprint n - 1 Retrosprective Summary | Este es el primer sprint, no hay retroespectiva |
| Sprint 1 Goal | Organizarnos para la realización del reporte y para la elaboración y despliegue de la Landing Page |
| Sprint 1 Velocity | 3 Semanas|
| Sum of Story Points | 11 Story Points |


#### 5.2.1.2. Aspect Leaders and Collaborators.
| Team Member | Programación de Menu de Navegación | Programación de Sección "About-Us" | Programación de la sección "Features"| Programación de la sección "Planes"| Programación de la sección "Contacto"|
| ---------------------| ---------------- | ------------------ | -------------------| --------------------| ----------------|
| Kevin Alexander Castañeda Llanos | X | X | X | X | X |
| Adrian Alonso Calle Huayanca | - | - | - | - | - |
| Renzo José Araujo Ingunza | - | - | - | - | - | 
| Rodrigo Nicolás Mechan Chumpitaz| - | - | - | - | - |
| Rodrigo Jesús Miraval Pomalaya | - | - | - | - | - |
#### 5.2.1.3. Sprint Backlog 1.
| Sprint \# | Sprint 1 |  |  |  |  |  |  |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| User Story |  | Work-Item / Task |  |  |  |  |  |
| ID  | Title | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| US041 | Menú de navegación	 | TS01 | Implementación del menú de navegación | Implementacaión del menú de navegación para la Landing Page en la parte superior. | 2 hours | Kevin | Done |
| US042 | Call to Action | TS02 | Implementación de botones y enlaces internos | Implementación de botones y enlaces internos en la página web para llevar al usuario a secciones. | 2 hours | Kevin | Done |
| US043 | Características | TS03 | Implementación de la sección "Características | Implementación de la sección "Características", con los aspectos positivos de la app. | 2 hours | Kevin | Done |

#### 5.2.1.5. Execution Evidence for Sprint Review.
En esta sección mostraremos la evidencia de la creación de la Landing Page. Se presentarán capturas sobre algunas de las funciones principales.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

#### 5.2.1.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.

### 5.3.2. Registro de Entrevistas.

### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.

# Conclusiones

## Conclusiones y recomendaciones.

## Video About-the-Team.

# Bibliografía 

# Anexos

