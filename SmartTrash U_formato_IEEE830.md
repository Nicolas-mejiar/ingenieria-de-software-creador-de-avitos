# 1. Introduccion
En este documento se presentan las especificaciones de requisitos de software del proyecto SmartTrash U. El propósito es definir los requisitos funcionales y no funcionales para tener un correcto desarrollo. Tambien se encuentra el alcance del proyecto, características, descripción de usuarios, restricciones y demás aspectos relevantes. Ademas, se incluyen partes importantes como las definiciones y referencias, todo con el fin de facilitar la comprensión durante las etapas de desarrollo del proyecto.
## 1.1 Proposito
El propósito de este documento es describir de manera clara y estructurada los requisitos del sistema SmartTrash U, el cual consiste en una aplicación web orientada a la gestión y clasificación inteligente de residuos sólidos en un entorno universitario. Este documento tiene como objetivo servir como guía para el desarrollo del sistema, facilitando la comprensión de sus funcionalidades, restricciones y características principales.
Está dirigido a los integrantes del equipo, docente evaluador y cualquier persona interesada en comprender el funcionamiento y alcance del proyecto. Asimismo, permite establecer una base común de entendimiento entre las partes involucradas, asegurando que el sistema cumpla con los objetivos planteados.
## 1.2 Alcance
El sistema a desarrollar llamado SmartTrash U, es una aplicación web orientada a la gestión y clasificación de residuos sólidos dentro de una institución universitaria. Su propósito es fomentar la correcta disposición de los desechos mediante la participación activa de estudiantes, docentes y personal administrativo, apoyándose en un sistema de puntos y recompensas.
El proyecto se fundamenta en el concepto de una caneca inteligente equipada con sensores capaces de identificar el tipo de residuo depositado. No obstante, debido al alcance académico del proyecto, esta funcionalidad será implementada mediante un simulador. El sistema permitirá a los usuarios registrarse, iniciar sesión, clasificar residuos de forma interactiva, visualizar su progreso (puntos acumulados, residuos clasificados e impacto ambiental) y acceder a recompensas.
Este alcance cumple con el objetivo general del sistema como una solución tecnológica orientada a la educación ambiental y la gestión eficiente de residuos, adaptada a un entorno universitario
## 1.3 Personal Involucrado
| Campo                     | Información                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Nombre                   | Andres Felipe Gonzalez Ferrucho                                             |
| Rol                      | Coordinador / Cohesionador                                                  |
| Categoría profesional    | Estudiante de Ingeniería de sistemas                                        |
| Responsabilidades        | Coordinación del equipo y seguimiento, apoyo en el diseño del sistema y asegurar la calidad del trabajo. |
| Información de contacto  | andres-gonzalezf@unilibre.edu.co                                            |
| Aprobación               | Si                                                                          |

| Campo                     | Información                              |
|--------------------------|------------------------------------------|
| Nombre                   | Santiago Peña Reyes                      |
| Rol                      | Impulsor                                 |
| Categoría profesional    | Estudiante de Ingeniería de sistemas     |
| Responsabilidades        | Apoyo en el desarrollo de página web y mentenimiento de la calidad del trabajo|
| Información de contacto  | santiago-penar@unilibre.edu.co           |
| Aprobación               | Pendiente                                |

| Campo                    | Detalle                                   |
|--------------------------|-------------------------------------------|
| Nombre                   | Eileen Espitia Castellanos                |
| Rol                      | Planeador / Analista                      |
| Categoría profesional    | Estudiante de Ingeniería de sistemas      |
| Responsabilidades        | Planificar el proyecto, analizar requerimientos, proponer soluciones claras y estructuradas |
| Información de contacto  | eileeng-espitia@unilibre.edu.co           |
| Aprobación               | Pendiente                                 |

| Campo                     | Información                             |
|--------------------------|------------------------------------------|
| Nombre                   | Nicolas Alexander Mejia Rojas            |
| Rol                      | Desarrollador                            |
| Categoría profesional    | Estudiante de Ingeniería de sistemas     |
| Responsabilidades        | Desarrollo de Simulador de caneca            |
| Información de contacto  | nicolasa-mejiar@unilibre.edu.co          |
| Aprobación               | Pendiente                                       |

| Campo                     | Información                             |
|--------------------------|------------------------------------------|
| Nombre                   | Carlos David Valbuena Ortiz              |
| Rol                      | Impulsor/Finalizador                     |
| Categoría profesional    | Estudiante de Ingeniería de sistemas     |
| Responsabilidades        | Docu y Desarrollo de Simulador de ca     |
| Información de contacto  | carlosd-valbuenao@unilibre.edu.co        |
| Aprobación               | Pendiente                                |

## 1.4 Definiciones, acronimos y abreviaturas
- SRS (Software Requirements Specification): Documentos en el que se describen los requisitos funcionales y no funcionales. 
- SmartTrash U: Sistema inteligente de reciclaje que emplea una plataforma web para la gestión y clasificación de datos y puntos de los usuarios.
- QR: Código de respuesta rápida que permite acceder a información mediante un escaneo, en este caso permite redirigir a la página web del proyecto.
- Sensor: Dispositivo que permite detectar características físicas de los objetos, usado para hacer la clasificación.  
- Sistema de puntuación: Mecanismo que asigna puntos a los usuarios por el correcto manejo de residuos. 
## 1.5 Referencias 
| Referencia | Título                                      | Ruta                                      | Fecha | Autor                         |
|------------|----------------------------------------------|--------------------------------------------|-------|-------------------------------|
| Ref. 01    | IEEE Std 830-1998                            | https://ieeexplore.ieee.org                | 1998  | IEEE                          |
| Ref. 02    | Documentación del proyecto SmartTrash U      | Documento interno                          | 2026  | Equipo de SmartTrash U        |
| Ref. 03    | Normativa sobre gestión de residuos          | Fuente institucional / documento oficial   | 2025  | Ministerio de ambiente        |
| Ref. 04    | Manuales de sensores y componentes           | Documentación técnica de fabricantes       | 2025  | Fabricantes de hardware       |
| Ref. 05    | Documentación del entorno de desarrollo      | Sitio oficial del lenguaje/plataforma      | 2025  | Proveedores de software       |
