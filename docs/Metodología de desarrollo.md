![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 21/05/2024

# **METODOLOGÍA DE DESARROLLO**

### **WPL**

### **- GRUPO 12 -** 

### **CONTROL DE VERSIONES**
<div class="markdown-table">

| **Versión** | **Descripción de los cambios** | **Autor** | **Fecha** |
| --- | --- | --- | --- |
| v0.1.0 | Creación del documento | Mera Gómez, Pablo | 16/02/2024 |
| v1.0.0 | Primera versión | Mera Gómez, Pablo | 16/02/2024 |
| v1.1.0 | Añadidas nuevas secciones | Mera Gómez, Pablo | 17/02/2024 |
| v1.5.0 | Conversión a Markdown | García Linares, Diego | 08/03/2024 |
| v2.0.0 | Revisión en el sprint 2 para evitar failure conditions | Campos Garrido, Juan Jesús | 31/03/2024 |
| v2.0.1 | Revisión en el sprint 3 para evitar failure conditions | Campos Garrido, Juan Jesús | 21/04/2024 |
| V2.0.2 | Revisión documento para evitar failure conditions | Campos Garrido, Juan Jesús | 05/05/2024 |
| V3.0.0 | Revisión para entrega final | Campos Garrido, Juan Jesús | 21/05/2024 |
</div>

### **ÍNDICE DE CONTENIDOS**
<div class="markdown-center">

[**RESUMEN EJECUTIVO**](#resumen-ejecutivo)

[**INTRODUCCIÓN**](#introducción)

[**CONTENIDOS**](#contenidos)

[**EQUIPO DE DESARROLLO**](#equipo-de-desarrollo)

[**ROLES Y RESPONSABILIDADES**](#roles-y-responsabilidades)

[**METODOLOGÍA DE DESARROLLO**](#metodología-de-desarrollo)

[**GESTIÓN DE RAMAS**](#gestión-de-ramas)

[**POLÍTICA DE COMMITS**](#política-de-commits)

[**SEGUIMIENTO Y CONTROL**](#seguimiento-y-control)

[**ENTREGABLES Y RESULTADOS ESPERADOS**](#entregables-y-resultados-esperados)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)

</div>

## **RESUMEN EJECUTIVO**

El proyecto Shar3D se basa en una metodología de desarrollo ágil, principalmente centrada en la implementación de la metodología Scrum, respaldada por GitHub como plataforma central. Con un equipo de 12 personas organizado en grupos multifuncionales y roles clave como el Scrum Master y el encargado, se prioriza la colaboración, la adaptabilidad y la entrega continua de valor al cliente. El seguimiento y control se llevan a cabo mediante reuniones de seguimiento, GitHub Projects y una gestión proactiva de problemas y riesgos. Este enfoque busca garantizar la entrega de resultados que satisfagan al cliente a lo largo del proyecto.

## **INTRODUCCIÓN**

El presente documento establece la metodología de desarrollo a ser empleada en el proyecto Shar3d. En él se detallan las estrategias, procesos y roles que guiarán el desarrollo del proyecto con el fin de alcanzar sus objetivos de manera eficiente y efectiva.

## **CONTENIDOS**

Ahora vamos a abarcar los distintos apartados que creemos necesario para que la metodología que se va a seguir durante todo el proyecto esté bastante clara, tanto para personas externas a la organización como para el propio equipo de trabajo.

### **EQUIPO DE DESARROLLO**

Antes de pasar a la descripción de la estructura, debemos asumir que el proyecto va a usar una metodología de gestión ágil llamada Scrum, por lo tanto, se debe asumir que se necesita una estructura orientada a este tipo de gestión.

En esta metodología aparecen nuevos roles que no son comunes en el resto, como es el Scrum Master, que es el miembro encargado de corroborar que Scrum se está llevando a cabo de manera adecuada; generalmente es el miembro del equipo más experimentado en esta metodología el que se encarga de este rol.

En nuestro caso, somos un grupo de trabajo de 12 personas, en el cuál algunos miembros han participado juntos en otro proyecto pero otros nunca han coincidido, por lo tanto, se opta por realizar una subdivisión en pequeños grupos de 4 personas multifuncionales, es decir, que cada grupo sea capaz individualmente de realizar una tarea de cualquier tipo, como puede ser documentación, código fuente u otra necesidad.

Estos grupos se formarán atendiendo a las habilidades que cada miembro ha mencionado en el documento _Team Skills,_ buscando cubrir las necesidades de todos los participantes y que, entre todos, haya un interesado en cada una de las necesidades de un proyecto informático, que lo dividimos en: Backend, Frontend, Documentación, Gestión. Realmente, esta división no es exhaustiva, pues hay muchas tareas que no van a necesitar desarrollo Backend o Frontend y puede que necesiten investigación, por lo tanto, esto no significa que el miembro más interesado en una característica vaya a estar durante todo el proyecto trabajando en ese campo, la intención de esta estructura es que todos los miembros se dediquen a tareas que le interesen pero que también conozcan todas las mejoras que se están realizando, para tener un conocimiento profundo sobre el producto en general, no sobre una sección.

En cada uno de estos grupos de 4 personas, debe haber un encargado, que será la persona que se ocupe de la gestión y de la comunicación con el resto de grupos. Este miembro debe conocer en profundidad las tareas asignadas a su grupo, aunque también debe ser consciente del trabajo de los demás, pues es el encargado de coordinar que todo lo que se está realizando no afecte a otros equipos, que no haya conflictos y que se cumplan todas las tareas en los periodos adecuados. Además, se debe elegir uno entre los 3 encargados que ocupará el puesto de Scrum Master durante todo el desarrollo.

Tanto la división de grupos como los encargados y las tareas asignadas, se seleccionarán al inicio del Sprint. Durante el transcurso del mismo, los grupos tendrán que trabajar en sus tareas y cumplir con los plazos establecidos. Tras la finalización del Sprint, en la Sprint Retrospective, cada grupo comentará su experiencia trabajando juntos, los puntos positivos y negativos y habrá posibilidad de cambiar tanto roles como miembros de grupos si todos los miembros lo consideran estimado. En el caso de los encargados, la decisión puede ser unilateral, es decir, el cambio de encargado se puede ejecutar tanto si el encargado está descontento con el puesto asignado y quiere tener otro rol, como si el equipo considera que el encargado no ha trabajado de manera correcta durante el Sprint y necesita un cambio para poder mejorar el rendimiento. En ambos casos, se debe comunicar al equipo y establecer una votación para elegir al nuevo encargado entre los interesados en ocupar ese rol.

### **ROLES Y RESPONSABILIDADES**

Para comprender un poco mejor la estructura del equipo, se van a explicar a continuación los distintos roles que pueden haber y las responsabilidades que ocupan cada uno de ellos:

**Scrum Master**. Sus responsabilidades son las siguientes:

- - Garantizar la correcta implementación de la metodología Scrum en el proyecto.
    - Facilitar las reuniones Scrum, como las reuniones de seguimiento, la planificación de sprint y la retrospectiva del sprint.
    - Ayudar al equipo a comprender y adoptar los principios y prácticas ágiles.

**Encargados de Grupo**. Sus responsabilidades son las siguientes:

- - Coordinar las actividades de su grupo de trabajo.
    - Comunicar y coordinar con otros grupos para garantizar la coherencia y el progreso del proyecto.
    - Conocer en profundidad las tareas asignadas a su grupo y asegurarse de que se completen dentro de los plazos establecidos.
    - Actuar como punto de contacto principal entre su grupo y el resto.
    - Facilitar la resolución de conflictos dentro del grupo y entre grupos.
    - Supervisar el rendimiento del grupo y tomar medidas correctivas si es necesario.

**Miembros del Equipo**. Sus responsabilidades son las siguientes:

- - Contribuir activamente en la realización de las tareas asignadas durante el sprint.
    - Participar en las reuniones y eventos de Scrum.
    - Mantener una comunicación constante con el encargado del equipo.

Tanto a los miembros del equipo como a los encargados y al scrum master, se le van a asignar distintos roles dentro del proyecto para el que tendrán otras responsabilidades. Las cargas de trabajo se van a equilibrar, pues tanto el scrum master como los encargados tienen más trabajo para realizar que los miembros del equipo, por lo tanto, aunque tengan otros roles deben tener menos carga que los miembros. Los roles disponibles son:

**Desarrolladores backend**. Sus responsabilidades son:

- - Diseñar, desarrollar y mantener la lógica y la funcionalidad del servidor y la base de datos.
    - Implementar soluciones para las necesidades del backend.
    - Colaborar con los desarrolladores frontend para integrar el frontend con el backend.

**Desarrolladores frontend**. Sus responsabilidades son:

- - Crear interfaces de usuario interactivas que satisfagan las necesidades de los usuarios finales y que garanticen una experiencia de usuario coherente y de alta calidad
    - Integrar el frontend con el backend para asegurar un flujo de datos sin problemas.

**Desarrolladores fullstack**. Sus responsabilidades son:

- Cumplir las responsabilidades de los desarrolladores backend y frontend al mismo tiempo.

**Encargados de la documentación**. Sus responsabilidades son:

- - Crear y mantener la documentación técnica del proyecto, que incluye todos aquellos documentos que el equipo considere necesarios para el correcto desarrollo y los que el cliente especifique que necesita.
    - Asegurar que la documentación esté actualizada y sea accesible para todos los miembros del equipo.

**Encargados de las pruebas**. Sus responsabilidades son:

- - Diseñar y ejecutar casos de prueba para garantizar la calidad y la fiabilidad del software.
    - Identificar y reportar errores.
    - Automatizar pruebas para mejorar la eficiencia del proceso de prueba.

**Encargados de la calidad**. Sus responsabilidades son:

- - Realizar revisiones de código y auditorías para garantizar el cumplimiento de los estándares de calidad.
    - Identificar áreas de mejora en los procesos de desarrollo y proponer soluciones.
    - Realizar seguimiento de métricas de calidad y proporcionar informes sobre el estado de la calidad del producto.

Cabe recalcar que no es necesario que todos los roles sean asignados durante todos los sprints, es decir, no en todos los sprints será necesario un encargado de las pruebas, pero en algún momento habrá algún miembro que ocupe un rol. También se ha de repetir que los roles no son constantes, la idea es que cada persona pueda ocupar distintos roles en distintos sprints, lo que el equipo considera idóneo para que cada miembro conozca en profundidad el proyecto.

### **METODOLOGÍA DE DESARROLLO**

En el marco del proyecto Shar3D, hemos seleccionado GitHub como nuestra plataforma principal para la gestión del código fuente y la colaboración en el desarrollo del software. GitHub ofrece una variedad de herramientas y funcionalidades que facilitan el trabajo en equipo, el seguimiento de tareas (issues), la revisión de código y la integración continua, lo que lo convierte en una elección ideal para nuestro enfoque ágil de desarrollo.

Además, adoptaremos la metodología de gestión ágil Scrum para organizar y gestionar nuestras actividades de desarrollo. Scrum es un marco de trabajo iterativo e incremental que nos permitirá trabajar de manera colaborativa, adaptativa y eficiente. Con Scrum, dividiremos el proyecto en iteraciones llamadas sprints, cada una con una duración fija y objetivos específicos a alcanzar al final del sprint.

Utilizaremos Scrum para estructurar nuestros sprints y actividades de desarrollo. Al inicio de cada sprint, realizaremos una reunión de planificación para revisar y priorizar las tareas del product backlog, seleccionar las que se incluirán en el sprint backlog y establecer los objetivos a alcanzar. Durante el sprint, llevaremos a cabo reuniones cada 2 o máximo 3 días entre los encargados de cada uno de los grupos para mantenernos actualizados sobre el progreso y discutir posibles obstáculos, mejoras…

Más allá, para controlar las tareas de cada sprint backlog, tanto en qué parte del proceso (toDo, inProgress, inReview, Done) está cada una, como quién debe realizarla, de qué trata e incluso su importancia, se usará GitHub Projects, una herramienta que ofrece GitHub para manejar las issues y a la cuál todo los miembros del equipo de desarrollo están adecuados, por lo que consideramos que será una parte indispensable para el control de tareas.

Al final de cada sprint, realizaremos una revisión para demostrar el trabajo realizado y recibir retroalimentación, así como una retrospectiva para reflexionar sobre el proceso e identificar puntos de mejora. Estas prácticas nos permitirán iterar rápidamente y adaptarnos a los cambios.

Por último, integraremos prácticas de DevOps para mejorar la eficiencia y calidad del desarrollo. Esto incluirá la implementación de la integración continua, para lo que haremos uso de GitHub Actions, que es un servicio de automatización proporcionado por GitHub que permite automatizar tareas típicas de la integración continua como la construcción, las pruebas y el despliegue, realizándose todo directamente desde nuestro repositorio en GitHub. Todo esto nos ahorrará mucho tiempo y garantizará una mayor calidad del código al detectar errores de manera temprana, permitiendo una entrega más rápida y confiable del software.

En resumen, nuestra metodología de desarrollo se basará en el uso de GitHub como plataforma central, combinada con las metodologías ágiles Scrum y DevOps. Esto nos permitirá colaborar de manera efectiva, entregar software de manera rápida y adaptarnos de manera flexible a los cambios y desafíos del proyecto.

### **GESTIÓN DE RAMAS**

Vamos a adoptar la metodología de Git Flow para nuestra estrategia de desarrollo. Esta metodología implica tener dos tipos de ramas principales en las que no trabajaremos directamente:

master: Aquí estarán las versiones de lanzamiento de nuestra aplicación.

- develop: Utilizaremos esta rama para integrar todos los cambios que desarrollemos una vez finalizados.

Para incorporar cambios, los fusionamos a través de un merge en estas ramas principales. Sin embargo, para realizar este merge, necesitamos la aprobación de al menos dos personas mediante una pull request, ya que estas ramas están protegidas (una única persona en caso de la rama develop). En estas pull requests, detallaremos el trabajo realizado para que los demás puedan entender y verificar que todo funciona correctamente, incluso si no tienen conocimiento previo de la tarea.

Estas pull request mencionadas deben ser unitarias respecto a lo que contienen, es decir, cada pull debe tener una funcionalidad, puede ser de cualquier tipo como añadir realmente más valor al sistema, preparar un lanzamiento o corregir un bug, pero no se puede proponer un merge que incluya varios propósitos.

Además de estas ramas principales, tendremos ramas de trabajo donde desarrollaremos el proyecto y luego incorporaremos los cambios a partir de las pull request mencionadas anteriormente. Estas ramas son:

**hotfix**: Utilizadas para corregir errores en las versiones de lanzamiento.

**fix**: Utilizadas para corregir errores en la rama develop.

**release**: Aquí preparamos las diferentes versiones de lanzamiento.

**feat**: Usadas para incorporar nuevas funcionalidades o características

**doc**: Utilizadas para subir documentos.

Siempre que deseemos trabajar en una de estas ramas, creamos una nueva a partir de la rama principal correspondiente, en la mayoría de casos desde develop. El nombre de la rama debe seguir el formato:

**&lt;Tipo&gt;/Título**

donde los tipos pueden ser feature, release, fix, hotfix o doc, y el título describe la tarea de manera concisa utilizando snake_case o, si es una release, la versión a lanzar. Dentro de estas ramas, desarrollaremos individualmente la tarea descrita en el título y, al finalizar, realizaremos el merge mencionado anteriormente.

Finalmente, es importante destacar que cuando preparamos el lanzamiento de una versión a través de una rama release, también debemos actualizar la rama develop al mismo tiempo que lanzamos la versión a la rama master. Además, debemos etiquetar la rama master con un tag indicando la versión del lanzamiento.

### **POLÍTICA DE COMMITS**

Los commits se realizarán de manera individual por cada miembro, al menos debe haber uno por persona en cada sprint, si no es así, se deberá justificar. Estos incrementos deben ser unitarios y descritos a través del mensaje para que todos sepan en qué mejora al producto o cuál es la intención del cambio.

El patrón que se utilizará para los mensajes de commits será el siguiente:

**&lt;Tipo&gt; \[Título\]**

**\[Descripción\]**

En estos casos, el tipo debe describir con una palabra qué contiene o qué soluciona el commit. Los distintos tipos son:

- **fix**: el cambio soluciona un bug que tenía la aplicación.
- **feat**: el cambio añade nueva funcionalidad al sistema.
- **refactor**: el cambio está destinado a mejorar la calidad del código.
- **test**: el cambio se destina a probar el correcto funcionamiento de alguna parte del código
- **docs**: el cambio añade documentos necesarios para el proyecto o modifica los ya existentes.
- **build**: el cambio modifica el código para permitir que la construcción del proyecto funcione como se estima.
- **release**: el cambio se encarga de permitir el lanzamiento adecuado de la versión del código para cada uno de los sprints.

El **título** podrá tener un máximo de 50 caracteres, debe incluir en muy pocas palabras qué contiene el commit. La **descripción**, en cambio, podrá tener un máximo de 100 caracteres y debe tratar de explicar el qué y por qué se ha hecho.

### **SEGUIMIENTO Y CONTROL**

El seguimiento y control durante los distintos sprints es fundamental para garantizar la efectividad y el éxito del equipo de desarrollo. Estos procesos se centran en monitorear el progreso del trabajo, identificar y abordar obstáculos. Para ello, creemos que es indispensable la comunicación entre todos los miembros, por eso apareció la figura del encargado de cada grupo. Las técnicas que vamos a usar durante el desarrollo para controlar que el proyecto avanza como estimamos en el sprint planning son las siguientes:

**Reuniones de seguimiento**: Se llevarán a cabo reuniones periódicas entre los encargados de cada grupo de trabajo, así como reuniones generales del equipo, para revisar el progreso del sprint, discutir posibles obstáculos y tomar decisiones para mantener el trabajo en curso. Estas reuniones proporcionarán una plataforma para compartir actualizaciones, identificar problemas y colaborar en la búsqueda de soluciones. Creemos que, dentro del marco de Scrum, estas reuniones son primordiales para cumplir con los objetivos especificados en el Sprint Backlog.

Durante estas reuniones, si se detecta un problema el cuál los 4 miembros del grupo consideran que ponga en riesgo la salud y el correcto avance del proyecto, se tiene que proponer una reunión entre todos los miembros para buscar soluciones al problema y acordar la respuesta mediante consenso.

**GitHub Projects**: Se utilizará GitHub Projects como herramienta principal para el seguimiento y control de las tareas de cada sprint backlog. Todos los miembros del equipo serán responsables de mantener actualizado el estado de las tareas, asignar responsabilidades y utilizar la herramienta de manera efectiva para mantener una visión clara del progreso general del sprint. La consideramos, junto a las reuniones, la herramienta más importante para realizar el seguimiento, pues Projects será una herramienta compartida entre todos los miembros del equipo de desarrollo y podremos conocer el avance general del proyecto fuera de nuestro grupo.

Tras el Sprint Planning, el encargado de realizar el acta de la reunión, debe añadir todas las tareas a la herramienta junto con una descripción y la asignación al miembro que le corresponda.

**Gestión de problemas**: Si un miembro del equipo cree que tiene dificultades para desarrollar una actividad, que es incapaz de realizar una tarea o considera que no está haciendo las cosas como debería, tiene que contactar con el encargado de su grupo lo antes posible para no desperdiciar horas de trabajo. Los miembros deben comunicar cuanto antes este tipo de problemas para gestionarlo y hacer del reloj del proyecto lo más eficiente posible, tomando una decisión consensuada entre el encargado del equipo y el desarrollador, como puede ser un intercambio de tareas con otro compañero o recibir ayuda de un compañero para poder continuar con la tarea.

**Gestión de Riesgos**: Se llevará a cabo una evaluación continua de los posibles riesgos que puedan surgir durante el desarrollo del sprint. Al inicio de cada iteración, se identificarán los puntos críticos de riesgo a partir del registro de riesgos, se mostrará su impacto potencial y se comunicarán las estrategias para mitigarlos. Esto garantizará que el equipo esté preparado para hacer frente a cualquier desafío que pueda surgir durante el sprint y que estén especialmente centrados en aquellos riesgos que el equipo considere más probables en la iteración.

**Evaluación tras sprint**: Al finalizar cada sprint, se realizará una evaluación del rendimiento del equipo a través de una Sprint Retrospective, que es una sesión interna donde el equipo reflexiona sobre el sprint y busca mejoras para el próximo. Se revisará el cumplimiento de los objetivos del sprint, se identificarán áreas de mejora y se reconocerán los logros individuales y colectivos. Esta retroalimentación será fundamental para el aprendizaje continuo y el desarrollo del equipo a lo largo del proyecto.

### **ENTREGABLES Y RESULTADOS ESPERADOS**

Los entregables y resultados esperados del proyecto se van a diseñar para garantizar el cumplimiento de los objetivos del sprint y el progreso hacia la meta final del desarrollo del software. Para ello, se van a realizar ciertas comprobaciones al final de cada sprint que son las siguientes:

**Entregables del Sprint**: Son los resultados clave, al finalizar cada sprint, se espera que el equipo entregue un conjunto de tareas que cumplan con los requisitos establecidos y que funcionen como se estimó. Esto incluye tanto el cumplimiento de los objetivos establecidos en la planificación del sprint, como la resolución de cualquier problema u obstáculo identificado durante el desarrollo.

Para comprobar estos entregables, el equipo debe reunirse, al menos, 2 días antes de la finalización del Sprint para comprobar los requisitos. Cada encargado del grupo será el responsable de comprobar que todas las tareas que han sido realizadas por el equipo cumplen con lo estimado. En el caso de que le surjan dudas a los encargados o tengan problemas con la comprobación del entregable, se lo deben comunicar al resto del equipo para hacer un análisis más exhaustivo y poder asegurar que todas las tareas propuestas para dicho Sprint se cumplen.

**Calidad del Trabajo**: Se espera que todos los entregables cumplan con los estándares de calidad definidos por el equipo en el documento “Plan de Gestión de Calidad”.


## **CONCLUSIONES**

En conclusión, la metodología de desarrollo implementada en el proyecto se basa en la adopción de prácticas ágiles como Scrum. Con un equipo de 12 personas subdividido en grupos multifuncionales dirigidos por encargados, y roles adicionales como el Product Owner y el Scrum Master, se promueve la colaboración, la comunicación y la responsabilidad individual y colectiva en el cumplimiento de los objetivos del proyecto.

Además, el seguimiento y control durante los sprints se realiza mediante reuniones de seguimiento, el uso de GitHub Projects y la gestión proactiva de problemas y riesgos. Esto busca la identificación temprana de obstáculos y la mejora continua del equipo. En conjunto, estas prácticas pretenden garantizar la entrega de resultados que cumplen con las expectativas del proyecto y contribuyen al éxito general tanto del propio proyecto como del equipo.


## **BIBLIOGRAFÍA**

Intencionalmente vacío.

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

[Prompt para tener una estructura en el documento:](https://chat.openai.com/share/70e539be-225e-4820-a24d-e47ec5932f9f)