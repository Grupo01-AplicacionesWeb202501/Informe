# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
Branding:
- Nombre del proyecto: Eduflow

- Logotipo: El nombre del proyecto "Eduflow" esta estilizado como marca principal y encabezado izquierdo superior.

- Identidad visual: Uso predominante de azul, tipografía moderna sans-serif, y diseño limpio y amigable. En los archivos de la landing page se refleja esta identidad visual, con colores definidos y fuentes aplicadas de forma coherente.

Typography:
- Fuente principal: Noto Sans, sans-serif

- Fuente decorativa o alternativa: National Park, sans-serif (en títulos o énfasis)

- Tamaños y jerarquía:

  - Títulos grandes (h1, h2): 2rem o más

  - Subtítulos y descripciones (p, h3): 1rem – 1.25rem

- Estilo de fuente: Uso de negrita para títulos y énfasis

Colors:

- Primario: #477eb9 (azul principal)

- Secundario: #ebf4ff (azul muy claro)

- Terciario: #bed6fb (azul pastel)

- Fondo general: #f7f9fc

- Texto principal: #4a5568

- Texto en encabezados: #2d3748

- Blanco para contraste: #ffffff

State Colors:

- Hover de botones y enlaces:

  - Fondo en hover: #3d1ebb

  - Texto en hover: blanco (#ffffff)

- Enlaces activos / seleccionados: subrayado o cambio de color

- Animación de aparición: .fade-in (con @keyframes fadeInUp)

Black/grey Colors:

- Gris oscuro (texto): #4a5568

- Gris para bordes / fondos:

  - #e2e8f0 (borde claro)

  - #edf2f7 (fondo gris suave)

- Negro puro: No se utiliza, se emplean grises oscuros para suavidad visual

Spacing:

- Margen general: margin: 0 auto (centrado horizontal)

- Padding interno en secciones: padding: 2rem en promedio

- Espaciado entre elementos:

  - Títulos y párrafos: margin-bottom: 1.5rem

  - Botones y bloques: gap: 1rem – 2rem según layout

- Diseño responsivo: uso de *max-width, display: flex, justify-content: center y text-align: center*



### 4.1.2. Web Style Guidelines.
Para nuestra plataforma, hemos diseñado un sitio web orientado a la presentación clara y accesible de la información del producto, pensado para mejorar la experiencia de los usuarios desde su primer contacto con la landing page.

El diseño sigue el patrón de lectura en forma de Z, lo que facilita que el usuario siga intuitivamente la estructura de la página desde el logotipo (arriba a la izquierda), pasando por los llamados a la acción principales, hasta llegar a los contenidos y formularios. Esta estrategia asegura que los usuarios vean primero los elementos más importantes, como los botones de registro o información clave.

El sitio emplea colores contrastantes y tipografías limpias para optimizar la visibilidad y la interacción, manteniendo siempre la coherencia gráfica para reforzar la identidad visual del producto.

## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
La landing page de Eduflow se estructura siguiendo un sistema jerárquico que permite presentar la información de manera progresiva, clara y centrada en la experiencia del usuario. Las secciones están organizadas en bloques definidos para facilitar la navegación:

- Header con el nombre del producto y navegación principal.

- Hero Section que presenta una propuesta de valor clara.

- Sobre Nosotros: breve descripción del propósito de la plataforma.

- Servicios: muestra funcionalidades o beneficios destacados.

- Contacto: información de redes sociales e íconos interactivos.

Este orden responde a un flujo de atención de patron tipo z, que guía al usuario desde el encabezado hacia los llamados a la acción.

### 4.2.2. Labeling Systems.
El sistema de etiquetado empleado es claro, directo y consistente con el propósito del sitio. Como por ejemplo:

- Menú principal con enlaces como: Sobre Nosotros, Características, etc.

- Encabezados visualmente destacados con clases personalizadas.

- Botones con textos de acción como “Consultar precios” o “Registrate”, con clases que permiten cambiar su apariencia al pasar el cursor.

- Las imágenes tienen etiquetas alt, contribuyendo también a la accesibilidad.

### 4.2.3. SEO Tags and Meta Tags
El documento HTML incluye etiquetas mínimas de optimización para buscadores:

- Se emplea *meta charset="UTF-8"* y *meta name="viewport" content="width=device-width, initial-scale=1.0"* para asegurar accesibilidad y diseño responsivo.

- Uso de *<title>Eduflow - Sistema de matrícula inteligente</title>* como título del documento.

- El uso de etiquetas semánticas como header, section y footer facilita la interpretación del contenido por los motores de búsqueda.
### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems.
La navegación está basada en un sistema de anclas internas que permiten al usuario desplazarse por las secciones de la misma página. Algunas características clave:

- Menú fijo en la parte superior con enlaces que apuntan a #about, #services, #contact, etc.

- El comportamiento scroll-behavior: smooth facilita una transición amigable entre secciones.

- El diseño es responsivo: incluye una versión para dispositivos móviles basada en un menú tipo hamburguesa, activado mediante un checkbox (#menu-toggle) y manipulado con JavaScript.

## 4.3. Landing Page UI Design.
El diseño de interfaz de la landing page de Eduflow ha sido concebido como el primer punto de contacto visual y emocional entre los usuarios y la plataforma. Esta página no solo cumple una función informativa, sino que busca generar confianza, facilitar la navegación y motivar la acción inmediata, ya sea para conocer más del servicio o iniciar el proceso de registro.

El enfoque visual sigue los lineamientos establecidos en la guía de estilo (4.1) y la arquitectura de información (4.2), asegurando coherencia gráfica, claridad estructural y una experiencia de usuario fluida. La disposición de los elementos, la elección de colores, tipografías, espaciado y jerarquía visual responden directamente a las preferencias detectadas en entrevistas (2.2), así como a las necesidades funcionales expresadas en las historias de usuario (3.2), particularmente las relacionadas a la exploración de beneficios, visualización de precios y contacto directo.

Además, la interfaz está pensada para adaptarse a diferentes dispositivos (diseño responsive), reforzando la accesibilidad para estudiantes y psicólogos desde cualquier contexto de navegación.

### 4.3.1. Landing Page Wireframe.
<img src= "..\Chapter-IV/Images/LD Eduflow PG1.png">

<img src= "..\Chapter-IV/Images/LD Eduflow PG2.png">

<img src= "..\Chapter-IV/Images/LD Eduflow PG3.png">

<img src= "..\Chapter-IV/Images/LD Eduflow PG4.png">

<img src= "..\Chapter-IV/Images/LD Eduflow PG5.png">

### 4.3.2. Landing Page Mock-up.
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG1.png">

<img src= "..\Chapter-IV/Images/LD MU Eduflow PG2.png">

<img src= "..\Chapter-IV/Images/LD MU Eduflow PG3.png">

<img src= "..\Chapter-IV/Images/LD MU Eduflow PG4.png">

<img src= "..\Chapter-IV/Images/LD MU Eduflow PG5.png">

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
**Inicio:**
<img src= "..\Chapter-IV/Images/LD Eduflow PG1.png">

**Sobre Nosotros:**
<img src= "..\Chapter-IV/Images/LD Eduflow PG2.png">

**Caracteristicas:**
<img src= "..\Chapter-IV/Images/LD Eduflow PG3.png">

**Lista de precios:**
<img src= "..\Chapter-IV/Images/LD Eduflow PG4.png">

**Contacto:**
<img src= "..\Chapter-IV/Images/LD Eduflow PG5.png">

### 4.4.2. Web Applications Wireflow Diagrams.

<img src= "..\Chapter-IV/Images/LP Wireframes  EduFlow.jpg">

https://miro.com/welcomeonboard/Qmp1MlA4dXZHSnQ0SHBRcW9mS2VlaFVjQTRtVUtmbVhOOHAvM2hYVnc3K25ZM1U5R3RCb29jMkdHUFM1RkoyWDE5YjdGNkQrSmU5ODJIbkRBa25SVjlhbnlyYXlVTzJiUU1xZUdlbWl2WWxUcWt1RnV1TXpXcDhWNzgwQ3BzaDNhWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE=?share_link_id=337829451648

### 4.4.3. Web Applications Mock-ups.
**Inicio:**
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG1.png">

**Sobre Nosotros:**
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG2.png">

**Caracteristicas:**
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG3.png">

**Lista de precios:**
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG4.png">

**Contacto:**
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG5.png">

### 4.4.4. Web Applications User Flow Diagrams.

<img src= "..\Chapter-IV/Images/LP MockUp EduFlow.jpg">

https://miro.com/welcomeonboard/aDR6Yy9hUkU3aWVFNjdFR08yNm9RWW0vak1pQWVyZUlJckVOdW1KUUNWOFVDT0ZrbUsxdE04aXJRSmUwYkx4UDZCTXM2a2U4VDBFT1d1aDMyZGErY2RhbnlyYXlVTzJiUU1xZUdlbWl2WWx6Q3UxZmNuY01Yc0N0UE1EWW5henNyVmtkMG5hNDA3dVlncnBvRVB2ZXBnPT0hdjE=?share_link_id=967038294190

## 4.5. Web Applications Prototyping.
<img src= "..\Chapter-IV/Images/LD MU Eduflow PG1.png">

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202318814_upc_edu_pe/EXspQ-QqvTVIsFm0_i13sLsBeiCkZDpyXSTJNAnxcJmrEg?e=iFd0fF&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

Presentaremos como un diagrama de clases algunas de las funciones principales que debe de tener nuestra futura aplicación web.
<img src= "..\Chapter-IV/Images/diagrama-clases.png">

### 4.7.2. Class Dictionary.

En esta sección colocaremos la descripción de cada atributo de cada clase, teniendo en cuenta también su tipo de dato. Es importante crear un diccionario de las clases ya que sirve como documentación para que otros programadores sean capaz de entender el funcionamiento de cada atributo.

#### Clase: Usuario
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idUsuario          | Identificador único del usuario        | int                   |
| nombre             | Nombre completo del usuario            | String                |
| correo             | Correo electrónico del usuario         | String                |
| contraseña         | Contraseña del usuario                 | String                |
| tipoUsuario        | Tipo de usuario (Alumno, Profesor, Admin) | enum (Alumno, Profesor, Administrador) |


#### Clase: Alumno (hereda de Usuario)
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| codigoAlumno       | Código único del alumno                | String                |
| carrera            | Carrera que cursa el alumno            | String                |
| cicloActual        | Ciclo académico actual del alumno      | int                   |


#### Clase: Profesor (hereda de Usuario)
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| codigoProfesor     | Código único del profesor              | String                |
| especialidad       | Especialidad del profesor              | String                |


#### Clase: Curso
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idCurso            | Identificador único del curso          | int                   |
| nombre             | Nombre del curso                       | String                |
| codigo             | Código único del curso                 | String                |
| creditos           | Número de créditos del curso           | int                   |
| cupoMaximo         | Número máximo de estudiantes en el curso | int                   |


#### Clase: Seccion
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idSeccion          | Identificador único de la sección      | int                   |
| horario            | Horario de la sección                  | String                |
| aula               | Aula en la que se imparte la sección   | String                |
| vacantesDisponibles| Número de vacantes disponibles         | int                   |


#### Clase: Matricula
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idMatricula        | Identificador único de la matrícula    | int                   |
| fechaMatricula     | Fecha en la que se realizó la matrícula | Date                  |


#### Clase: Pago
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idPago             | Identificador único del pago          | int                   |
| monto              | Monto total del pago                  | double                |
| fechaPago          | Fecha en la que se realizó el pago    | Date                  |
| estado             | Estado del pago (Pendiente, Pagado, etc.) | enum (Pendiente, Pagado, Cancelado) |


#### Clase: Documento
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idDocumento        | Identificador único del documento      | int                   |
| tipo               | Tipo de documento (DNI, Certificado, etc.) | enum (DNI, Certificado, Otros) |
| numero             | Número del documento                   | String                |
| estadoValidacion   | Estado de validación del documento (Pendiente, Aprobado, Rechazado) | enum (Pendiente, Aprobado, Rechazado) |
| fechaSubida        | Fecha en la que se subió el documento  | Date                  |


#### Clase: Notificacion
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idNotificacion     | Identificador único de la notificación | int                   |
| tipo               | Tipo de notificación (Email, SMS)      | enum (Email, SMS)     |
| destinatario       | Destinatario de la notificación        | String                |
| asunto             | Asunto de la notificación              | String                |
| mensaje            | Contenido del mensaje de la notificación | String              |
| fechaEnvio         | Fecha en la que se envió la notificación | Date                |
| estado             | Estado de la notificación (Enviado, Pendiente, Error) | enum (Enviado, Pendiente, Error) |


#### Clase: Factura
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idFactura          | Identificador único de la factura      | int                   |
| numeroFactura      | Número único de la factura             | String                |
| montoTotal         | Monto total de la factura              | double                |
| fechaEmision       | Fecha de emisión de la factura         | Date                  |
| estadoPago         | Estado del pago (Pagada, Pendiente, Anulada) | enum (Pagada, Pendiente, Anulada) |


#### Clase: Reporte
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idReporte          | Identificador único del reporte        | int                   |
| tipoReporte        | Tipo de reporte (PorGrado, PorCurso, etc.) | enum (PorGrado, PorCurso, PorCiclo) |
| formato            | Formato del reporte (PDF, Excel)       | enum (PDF, Excel)     |
| fechaGeneracion    | Fecha en la que se generó el reporte   | Date                  |
| rutaArchivo        | Ruta del archivo generado del reporte  | String                |


#### Clase: Vacante
| Nombre de Atributo | Descripción                            | Tipo de Dato          |
|--------------------|----------------------------------------|-----------------------|
| idVacante          | Identificador único de la vacante      | int                   |
| estado             | Estado de la vacante (Disponible, Ocupada) | enum (Disponible, Ocupada) |



## 4.8. Database Design.
### 4.8.1. Database Diagram.
<img src= "..\Chapter-IV/Images/diagrama-bd.png">

