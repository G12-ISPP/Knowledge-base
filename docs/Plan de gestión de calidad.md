![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 31/03/2024

## **REALIZADO POR:**

### **SPRINT 2**

### **- GRUPO 12 -** 

### **CONTROL DE VERSIONES**
<div class="markdown-table">
| **Versión** | **Descripción de los cambios** | **Autor** | **Fecha** |
| --- | --- | --- | --- |
| v1.0.0 | Comienzo del documento | Santiago Félix, Alejandro | 11/02/2024 |
| v1.1.0 | Seguimiento del documento | Garrucho Sánchez, Úrsula  García Linares, Diego | 15/02/2024 |
| v1.2.0 | Proceso de medida del rendimiento | Campos Garrido, Juan Jesús | 16/02/2024 |
| v1.3.0 | Revisión del documento | Santiago Félix, Alejandro | 16/02/2024 |
| v1.4.0 | Añadida sección de proceso de mejora | Santiago Félix, Alejandro | 16/02/2024 |
| v1.5.0 | Nueva medición sobre el rendimiento individual | Campos Garrido, Juan Jesús | 23/02/2024 |
| v1.6.0 | Conversión a Markdown | García Linares, Diego | 08/03/2024|
| v2.0.0 | Revisión en el sprint 2 para evitar failure conditions | Campos Garrido, Juan Jesús | 31/03/2024 |
</div>

### **ÍNDICE DE CONTENIDOS**

<div class="markdown-center">

[**RESUMEN EJECUTIVO**](#resumen-ejecutivo)

[**INTRODUCCIÓN**](#introducción)

[**CONTENIDOS**](#contenidos)

[**OBJETIVO DE LA CALIDAD**](#objetivo-de-la-calidad)

[**ENFOQUE DE LA CALIDAD**](#enfoque-de-la-calidad)

[**RESPONSABILIDADES**](#responsabilidades)

[**PROCESOS DE ASEGURAMIENTO DE LA CALIDAD**](#procesos-de-aseguramiento-de-la-calidad)

[**PROCESOS DE CONTROL DE CALIDAD**](#procesos-de-control-de-calidad)

[**HERRAMIENTAS Y TÉCNICAS**](#herramientas-y-técnicas)

[**CRITERIOS DE ACEPTACIÓN**](#criterios-de-aceptación)

[**ACCIONES CORRECTIVAS Y PREVENTIVAS**](#acciones-correctivas-y-preventivas)

[**REGISTRO DE CALIDAD**](#registro-de-calidad)

[**EVALUACIÓN Y MEJORA CONTINUA**](#evaluación-y-mejora-continua)

[**EVALUACIÓN DEL RENDIMIENTO DEL EQUIPO**](#evaluación-del-rendimiento-del-equipo)

[**PROCESO DE MEJORA**](#proceso-de-mejora)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)

</div>

## RESUMEN EJECUTIVO

En este documento nos centraremos en describir cómo será todo nuestro proceso de gestión, revisión y aseguramiento de la calidad en nuestro proyecto. Además de establecer la forma en la que mediremos el rendimiento de los integrantes del equipo.


## INTRODUCCIÓN

Se va a proceder a detallar el Plan de Gestión de Calidad que ha sido diseñado con el objetivo de garantizar la calidad a lo largo de todo el desarrollo además de implementar medidas para poder obtener una mejora continua y no dejar de rectificar errores para evitar futuros.

### **CONTENIDOS**

### INTRODUCCIÓN

Se va a proceder a establecer los procesos, responsabilidades, herramientas y técnicas que van a ser usadas para garantizar la calidad en todo el desarrollo software llevando a cabo medidas tanto preventivas como correctivas obteniendo así una mejora continua durante todo el desarrollo.

### OBJETIVO DE LA CALIDAD

Nuestro objetivo con respecto a la calidad se centra en garantizar que nuestra plataforma web cumpla con altos estándares de usabilidad, seguridad y rendimiento, proporcionando una experiencia fluida y satisfactoria a los usuarios. De esta manera conseguiremos desmarcarnos de la competencia haciendo así una página atractiva y útil la cual atraiga a nuevos usuarios.

### ENFOQUE DE LA CALIDAD

Para conseguir nuestros objetivos adoptaremos un enfoque de calidad integral, combinando SCRUM que es una metodología ágil de desarrollo, la cual encaja perfectamente con nuestro tipo de proyecto ya que es un proyecto de un calibre medio/bajo, con técnicas de desarrollo que explicaremos en siguientes puntos, centradas en las necesidades y expectativas del usuario.

### RESPONSABILIDADES

- Director de Calidad: su responsabilidad se basa en liderar y supervisar la implementación y cumplimiento del Plan de Calidad.
- Equipo de Desarrollo:
  - Desarrolladores: van a ser los responsables de escribir código de alta calidad siguiendo buenas prácticas de programación.
  - Diseñadores: se van a encargar de crear una experiencia de usuario atractiva intuitiva y cómoda.
  - Probadores (QA): responsables de ejecutar pruebas exhaustivas para identificar defectos y garantizar la funcionalidad adecuada del sistema.
- Gerente de Proyecto: supervisa la implementación del Plan de Gestión de Calidad y coordina las actividades de los diferentes equipos de desarrollo.
- Usuarios piloto: van a proporcionar retroalimentación sobre la usabilidad y la funcionalidad del desarrollo software además de participar en pruebas de usuario para validar que el sistema cumpla con las necesidades y expectativas establecidas en el inicio.

### PROCESOS DE ASEGURAMIENTO DE LA CALIDAD

- Implementaremos un proceso automatizado de revisión de código utilizando herramientas como SonarCloud. Cada vez que se realice un commit en el repositorio, se ejecutará un análisis estático de código para identificar posibles problemas de calidad, vulnerabilidades de seguridad y oportunidades de mejora. Esto asegurará que el código cumpla con los estándares definidos y se mantenga libre de errores. Estos bugs, o bad smells deberán ser arreglados antes de mergear estos commits a develop o master. Además tendremos que conseguir al menos estas puntuaciones en los siguientes apartados relacionados con la calidad del código:
- Implementaremos la estrategia de branching GitFlow para gestionar el flujo de trabajo en nuestro repositorio Git. Esta estrategia define un modelo de ramificación que organiza el desarrollo en diferentes tipos de ramas, como "feature/№ issue - Descripción de la tarea a realizar", "develop", y "master". Al seguir GitFlow, mantendremos un control estructurado sobre las nuevas características, las versiones de lanzamiento y las correcciones de errores, lo que facilitará la colaboración entre los miembros del equipo y garantizará una integración fluida y ordenada del código.
- Adoptaremos el estándar de [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) para estandarizar nuestros mensajes de commit. Este estándar define un formato claro y consistente para los mensajes de commit, lo que facilita la comprensión de los cambios realizados en el código. Al seguir este estándar, mejoraremos la trazabilidad del desarrollo, facilitaremos la colaboración entre los miembros del equipo y mantendremos un historial de cambios más organizado y comprensible. La estructura de Conventional Commits se controlará mediante un github action y no se podrá mergear a develop si un commit está mal hecho ya que buscamos que nuestro código sea trazable para así minimizar al máximo el tiempo de corrección de los problemas.
- Configuraremos un sistema de pruebas automáticas que se ejecute cada vez que se realice un commit en el repositorio. Esto garantizará que se detecten rápidamente posibles problemas de código y se mantenga la integridad del mismo.

### PROCESOS DE CONTROL DE CALIDAD

- Control de versiones: se van a gestionar y controlar las diferentes versiones del proyecto gracias a un sistema de control de versiones donde cada cambio realizado en el código va a ser registrado y documentado además de establecer políticas para el manejo de ramas de desarrollo, fusiones y etiquetado de versiones estables.
- Auditorías de código: se llevarán a cabo auditorías antes del lanzamiento de una nueva versión funcional del código para garantizar la calidad y el cumplimiento de los estándares establecidos. En estas auditorías se va a revisar el código con la intención de detectar posibles problemas o malas prácticas.
- Inspecciones de diseño: se realizan inspecciones periódicas de diseño para asegurar que se estén cumpliendo los requisitos de usabilidad, accesibilidad y experiencia de usuario establecidos. Se revisarán los diseños de interfaz de usuario, la arquitectura y flujos de navegación para identificar problemas o posibles mejoras y optimización.
- Validación de Requisitos: se verificará el cumplimiento de requisitos funcionales y no funcionales que se hayan especificado en la documentación del proyecto. Esto va a incluir las pruebas de aceptación de usuario mencionadas anteriormente para poder validar que se cumplen las expectativas y necesidades de éste.

### HERRAMIENTAS Y TÉCNICAS

- SonarCloud para la calidad del código
- Conventional Commits para la integridad de los comentarios de commit mediante Github Actions
- Github Actions para las pruebas automáticas.
- Git para el control de versiones.

### CRITERIOS DE ACEPTACIÓN

SonarCloud:

- Reliability: B o más
- Security: B o más
- Security review: B o más
- Maintaniability: A
- Coverage: 80% o más
- Duplicated lines: Menos de un 7%
- Technical Debt: Menos de un 8%
- Complejidad ciclómatica: Menos de un 12%

Tests: El 100% de los tests deben ser positivos.

Conventional Commits: El 100% de los commits deben seguir la estructura.

###ACCIONES CORRECTIVAS Y PREVENTIVAS

- Se llevarán a cabo sesiones al final de cada Sprint de retroalimentación y mejora continua para analizar las lecciones aprendidas, identificar áreas de mejora y definir acciones correctivas y preventivas. Esto se hace automáticamente al seguir scrum gracias a su retrospective en las cuales se tendrán en cuenta las auditorías de código.

### REGISTRO DE CALIDAD

- Se mantendrá un registro detallado de todas las actividades relacionadas con la calidad, incluyendo pruebas realizadas, resultados obtenidos, problemas identificados y acciones tomadas para abordarlos. Esto básicamente se podrá ver todo en github gracias a los actions y en sonarcloud.

### EVALUACIÓN Y MEJORA CONTINUA

- Seguimiento y Análisis de Métricas: Realizaremos un seguimiento regular de las métricas de calidad definidas en nuestro plan, como la cobertura de código, la duplicación de código, la deuda técnica y la complejidad ciclomática. Analizaremos estos datos para identificar tendencias, áreas de mejora y posibles problemas que requieran atención.
- Revisiones y Auditorías Periódicas: Programaremos revisiones y auditorías periódicas del proceso de desarrollo y del código fuente. Estas revisiones nos permitirán identificar posibles desviaciones del plan de calidad, así como oportunidades de mejora en nuestros procesos y prácticas de desarrollo.

### EVALUACIÓN DEL RENDIMIENTO DEL EQUIPO

Otro aspecto importante referente a la calidad del proyecto es el rendimiento del equipo que lo realiza, por eso definiremos el siguiente proceso para medir el rendimiento del equipo:

- En primer lugar todas las tareas tendrán una puntuación de peso que representarán el esfuerzo necesario para completar la tarea, el peso de las tareas será establecido por votación de los integrantes del equipo.
- Para estimar el peso de cada tarea, los integrantes deben tener en cuenta tres factores como son, el tiempo que puede conllevar la tarea, la dificultad de la tarea y un último factor que sería lo repetitiva o pesada que se puede hacer la tarea.
- A partir de este peso, semanalmente se calculará para cada integrante del equipo el número de puntos de esfuerzo realizados cada semana, a partir de esto se pueden estudiar métricas como la proporción de puntos de esfuerzo por hora, la media de puntos de esfuerzo semanales del equipo etc.
- Inicialmente no se establecerá un mínimo de puntos de esfuerzo semanal por persona, ya que la idea de esta forma de medir el rendimiento es motivar al equipo a mejorar semanalmente el número de puntos de esfuerzo que se completan, mejorando así también métricas como el ratio de puntos de esfuerzo por hora.
- En los casos en los que se detecte que durante dos semanas seguidas algún integrante del equipo tenga métricas por debajo del resto o si se detecta que un integrante empieza a reducir sus números se hablará con él para detectar la raíz del problema y buscar posibles soluciones.

### PROCESO DE MEJORA

- Identificar las necesidades y expectativas: realizaremos encuestas, entrevistas y pruebas de usuario para recoger la opinión y retroalimentación de los usuarios pilotos sobre la usabilidad, la funcionalidad y el valor de nuestro producto. Analizaremos estos datos para identificar las áreas de satisfacción y las áreas de mejora.
- Implementar acciones de mejora: aplicaremos las acciones de mejora que hayamos definido en las sesiones de retroalimentación y mejora continua, así como en las revisiones y en las auditorías. Estas acciones pueden incluir corrección de errores, la optimización del código, la mejora del diseño, la incorporación de nuevas funcionalidades o la adaptación de los cambios de los requisitos.
- Verificar y validar los resultados: realizaremos pruebas automáticas y manuales para verificar y validar que los resultados obtenidos cumplen con los objetivos y los criterios de calidad establecidos. Compararemos los resultados con los objetivos y los criterios establecidos.
- Comunicar y documentar los hallazgos de las lecciones aprendidas: compartiremos los resultados y el impacto de las acciones de mejora con el resto del equipo y con los stakeholders. Documentamos los hallazgos y las lecciones aprendidas para facilitar el aprendizaje del equipo y la tranferencia de conocimientos.


## **CONCLUSIONES**

En el presente documento se establecen los fundamentos para asegurar que nuestro producto cumpla con los más altos estándares de calidad, proporcionando una base sólida para el éxito del proyecto y la satisfacción de los usuarios.

## **BIBLIOGRAFÍA**

- [SonarCloud Pricing](https://www.sonarsource.com/plans-and-pricing/#sonarcloud)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

Consulta de ideas para proponer un proceso de medición del rendimiento del equipo:

[Conversación 1](https://chat.openai.com/share/48ab304d-25f3-4186-893b-fd13d329541f)

Consulta sobre plan de gestión de calidad y estructura:

[Conversación 2](https://chat.openai.com/share/52feac81-0c04-44f8-a2ce-a5320e6cbb32)[Conversación 3](https://chat.openai.com/share/026c7a26-bd77-4f17-a76d-5d5eb58af750)