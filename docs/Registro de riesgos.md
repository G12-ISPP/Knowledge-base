![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 21/04/2024

# **REGISTRO DE RIESGOS**

## **REALIZADO POR:**

### **SPRINT 3**

### **- GRUPO 12 -** 

### **CONTROL DE VERSIONES**
<div class="markdown-table">
| **Versión**| **Descripción de los cambios**| **Autor**| **Fecha**|
| --- | --- | --- | --- |
| v0.1 | Creación del documento | Campos Garrido, Juan Jesús | 10/02/2024 |
| v0.3 | Añadido listado de 45 riesgos | Campos Garrido, Juan Jesús | 10/02/2024 |
| v0.5 | Evaluados y priorizados los 45 riesgos iniciales | Campos Garrido, Juan Jesús | 11/02/2024 |
| v0.8 | Propuestos 45 planes de acción para los riesgos iniciales | Campos Garrido, Juan Jesús | 11/02/2024 |
| v0.9 | Añadido riesgo de dependencia entre tareas | Campos Garrido, Juan Jesús | 25/02/2024 |
| V1.5 | Conversión a Markdown | García Linares, Diego | 08/03/2024 |
| V2.0 | Añadido riesgo de relajación en el sprint 2 | 31/03/2024 |
| v3.0 | Revisión en el sprint 3 para evitar failure conditions | Campos Garrido, Juan Jesús | 21/04/2024 |
</div>


### **ÍNDICE DE CONTENIDOS**
<div class="markdown-center">

[**RESUMEN EJECUTIVO**](#resumen-ejecutivo)

[**INTRODUCCIÓN**](#introducción)

[**CONTENIDOS**](#contenidos)

[**REGISTRO DE RIESGOS**](#registro-de-riesgos)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)

</div>



## **RESUMEN EJECUTIVO**

En este documento se recogen una gran cantidad de riesgos que pueden surgir a lo largo del proyecto, así como una evaluación de la probabilidad de aparición y de su impacto y finalmente para cada riesgo se proporciona un plan de acción para saber cómo reaccionar en el caso de que alguno de los riesgos se active.

## **INTRODUCCIÓN**

En los proyectos software la gestión de riesgos es un proceso muy importante en los proyectos de desarrollo software, en este proceso hay que identificar los riesgos, evaluarlos y definir un plan de acción por si ocurren. Pero el trabajo de la gestión de riesgos no termina aquí ya que una vez se identifican los riesgos y se definen planes de acción, hay que monitorearlos para ver si ocurren o si surgen nuevos riesgos que no se contemplaron en su momento. En el caso de que se detecte que un riesgo ocurre, habrá que poner en marcha el plan de acción y tras ponerlo en marcha habrá que evaluar su efectividad para ver si hay que realizar cambios sobre dicho plan de acción.

A lo largo de este documento se identifican y cuantifican los riesgos, además se propone un plan de acción para cada uno de los identificados.

## **CONTENIDOS**

En la siguiente tabla se identificarán los riesgos, los campos probabilidad e impacto tendrán un valor entre 1 y 10, mientras que el campo factor podrá tener valores entre 1 y 100, finalmente, el campo prioridad tendrá valores entre 1 y 10 siendo los riesgos más prioritarios aquellos que tengan un valor de prioridad más bajo

### **REGISTRO DE RIESGOS**
<div class="markdown-table">
| **Id**| **Problema**| **Probabilidad de ocurrencia**| **Impacto**| **Factor**| **Prioridad**| **Plan de acción**|
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Cambios en los proveedores de software. Por ejemplo cambios en el SLA de GitHub que pueda afectar al uso del repositorio del proyecto | 2 | 8 | 8 | 10 | Aceptar las consecuencias del riesgo y adaptar el proyecto a la nueva situación, esto podría implicar buscar alternativas como usar otro software de otros proveedores |
| 2 | Cambios en los costes de las adquisiciones de servicios de proveedores | 3 | 7 | 21 | 8 | Aceptar las consecuencias y adaptar el proyecto a la nueva situación siempre y cuando el presupuesto no aumente considerablemente. En el caso de que el coste aumente demasiado, se buscarán nuevos proveedores |
| 3 | Problemas en la calidad del software de terceros | 2 | 8 | 8 | 10 | Contactar con los proveedores para que solucionen los problemas de calidad o incluso buscar proveedores alternativos para el software que esté dando problemas |
| 4 | Cambios en los requisitos del proyecto | 4 | 6 | 24 | 7 | Modificar el registro de requisitos con los cambios realizados y ajustar el cronograma en el caso de que sea necesario por el cambio en alguna tarea o el surgimiento de una nueva |
| 5 | Requisitos incompletos o mal definidos | 5 | 8 | 40 | 4 | Estudiar las incompletitud y adaptar los requisitos a las necesidades reales del proyecto y tras esto modificar el registro de requisitos con los cambios pertinentes |
| 6 | Defectos en la elaboración de documentación | 5 | 6 | 30 | 6 | Recopilar las deficiencias de la documentación para corregirlas de forma efectiva y posteriormente verificar si los cambios son correctos |
| 7 | Incumplimiento de estándares | 6 | 8 | 42 | 4 | Reunir al equipo para revisar los estándares y garantizar su cumplimiento |
| 8 | Deficiencias en las pruebas de las funcionalidades | 4 | 9 | 36 | 5 | Redefinir las pruebas realizadas para garantizar que la funcionalidad de la aplicación se comporta como se espera |
| 9 | Falta de pruebas en las funcionalidades del software | 3 | 9 | 27 | 6 | Identificar aquellas funcionalidades o aspectos de la aplicación que no han sido probados y elaborar nuevos test |
| 10 | Problemas de comunicación o malentendidos entre los miembros del equipo | 5 | 8 | 40 | 4 | Revisar las vías de comunicación de los integrantes del equipo y modificar el plan de gestión de las comunicaciones |
| 11 | Problemas relacionados con la realización de reuniones | 3 | 6 | 18 | 8 | Modificar la fecha de la realización de reuniones, facilitar nuevas vías para la realización de las mismas o cambiar a las personas encargadas de ir a las reuniones |
| 12 | Fallos en las herramientas de comunicación utilizadas | 2 | 5 | 5 | 10 | Explorar nuevas herramientas para la comunicación, como en el proyecto principalmente se usará Slack, en caso de fallos podremos usar Discord |
| 13 | Aumento inesperado en los costes del proyecto superando el coste estimado inicial | 4 | 9 | 36 | 5 | Ejecutar planes de contingencia para controlar los costes, adaptar el plan de gestión de los costes y buscar formas de recortar costes en el proyecto |
| 14 | Falta de compromiso y participación de algún participante del proyecto | 5 | 9 | 45 | 3 | Establecer vías de comunicación continuas con los interesados para motivarlos a involucrarse más en el desarrollo del proyecto |
| 15 | Desacuerdo entre los participantes del proyecto | 9 | 6 | 54 | 2 | Realizar reuniones extraordinarias para tratar los desacuerdos y buscar soluciones para aumentar el compromiso y la participación |
| 16 | Diferencia en las expectativas de los distintos participantes | 3 | 6 | 18 | 8 | Corregir ambigüedades en el alcance del proyecto y definir con exactitud las expectativas a lograr |
| 17 | Aparición de nuevos competidores con soluciones parecidas a las propuestas en el proyecto | 2 | 8 | 16 | 9 | Estudiar las fortalezas y debilidades de la nueva competencia para potenciar nuestra solución y diferenciarnos de alguna forma |
| 18 | Variaciones en la demanda del mercado hacia el producto con el que trabajamos | 4 | 7 | 28 | 6 | Realizar un estudio del mercada para adaptar las expectativas del proyecto con el objetivo de buscar la aceptación y acogida del producto en los usuarios finales |
| 19 | Problemas de los usuarios finales para utilizar el software y habituarse a su uso | 4 | 9 | 36 | 5 | Realizar una revisión de la usabilidad del producto final utilizando el feedback de los usuarios piloto para facilitar el uso del software final
 |
| 20 | Cambios en el equipo del proyecto | 5 | 8 | 40 | 4 | Establecer una vía de comunicación continua con los nuevos integrantes del equipo de forma adecuada con la finalidad de formarlos en el menor tiempo posible |
| 21 | Falta de liderazgo en el proyecto y problemas en la toma de decisiones | 4 | 8 | 36 | 5 | Reorganizar la dirección del equipo con el objetivo de mejorar la toma de decisiones en vista al cumplimiento de las expectativas del proyecto |
| 22 | Pérdidas de personal en el equipo | 7 | 8 | 56 | 2 | Se deberá reorganizar el trabajo y los tiempos de la planificación y otras personas tendrán que asumir las responsabilidades de las personas que dejen el equipo |
| 23 | Conflictos y disputas entre los miembros del equipo | 8 | 5 | 40 | 4 | Se realizarán reuniones extraordinarias para tratar de solucionar los conflictos y si no se consigue, se harán cambios en los equipos de trabajo para tratar de separar a las personas que tengan conflictos |
| 24 | Falta de habilidades técnicas por parte de alguno de los integrantes | 3 | 8 | 24 | 7 | Se definirá un plan de formación y se readaptar los tiempos del proyecto teniendo en cuenta los retrasos debidos al aprendizaje de tecnologías |
| 25 | Cansancio de los miembros del equipo debido a la sobrecarga de trabajo | 8 | 8 | 64 | 1 | Reorganizar la distribución de tareas para encontrar soluciones que liberen el estrés de las personas que mayor sobrecarga tengan |
| 26 | Falta de motivación en el proyecto por parte de uno o todos los miembros del equipo | 8 | 8 | 64 | 1 | Realizar dinámicas de grupo que mantengan la motivación por el trabajo que se está realizando |
| 27 | Problemas de desigualdad en la distribución del trabajo entre los diferentes miembros del equipo | 6 | 8 | 48 | 3 | Reorganizar la distribución de tareas entre los miembros del equipo |
| 28 | Robo de información del desarrollo del proyecto | 3 | 8 | 24 | 7 | Identificar la brecha de seguridad y destinar recursos a eliminarla |
| 29 | Suplantación de identidad que produzca que algún intruso pueda acceder al proyecto en nombre de otro | 3 | 8 | 24 | 7 | Identificar la brecha de seguridad y destinar recursos a eliminarla además de realizar cambios en los permisos del proyecto |
| 30 | Incompatibilidad de los sistemas y plataformas utilizadas | 2 | 9 | 18 | 9 | Buscar sistemas y plataformas alternativas para desarrollar el software |
| 31 | Problemas de hardware de en alguno de los miembros del equipo | 5 | 8 | 40 | 4 | Facilitar herramientas necesarias al miembro del equipo afectado para que pueda continuar trabajando, por ejemplo se pedirán dispositivos prestados a la universidad o en casos más graves algunos desarrolladores compartirán equipo |
| 32 | Problemas de rendimiento de la solución software desarrollada | 6 | 9 | 54 | 2 | Se prepará un plan para corregir estos problemas y se realizarán más pruebas de rendimiento |
| 33 | Problemas de rendimiento por parte de la plataforma donde se ha desplegado el software | 6 | 9 | 54 | 2 | O se contratarán sistemas con más capacidad o se buscará una nueva plataforma para desplegar el proyecto |
| 34 | Cambios en los sistemas y tecnologías utilizadas para el desarrollo del proyecto | 4 | 7 | 28 | 6 | Se adaptará el proyecto a las nuevas herramientas y se facilitarán tutoriales a los miembros del equipo para que puedan habituarse a las nuevas herramientas de la forma más rápida posible |
| 35 | Interferencia de otras actividades en el desarrollo del proyecto lo que produzca retrasos en las entregas | 5 | 7 | 35 | 5 | Adaptar el cronograma a las interferencias de las nuevas situaciones o priorizar las actividades a realizar |
| 36 | Aparición de eventos inesperados durante el desarrollo del proyecto | 3 | 7 | 21 | 8 | Adaptar el cronograma las nuevas actividades y comunicar a todo el equipo los cambios |
| 37 | Cambios en las fechas de entrega | 2 | 9 | 9 | 10 | Adaptar el cronograma realizando una intensificación para poder cumplir con las fechas de entrega en el caso de que las fechas se adelanten |
| 38 | Expectativas poco realistas | 2 | 7 | 7 | 10 | Se establecerán canales de comunicación claros para evaluar las expectativas y establecer criterios de éxito claros |
| 39 | Falta de escalabilidad | 6 | 8 | 42 | 4 | Se evaluará la modularidad de la aplicación para mejorarla y se realizarán pruebas de carga y rendimiento para asegurarnos de que se cumplen los requisitos de escalabilidad, además de que posteriormente se monitorizará la aplicación y se realizarán ajustes continuos |
| 40 | Falta de coordinación entre los equipos | 5 | 9 | 45 | 3 | Se harán reuniones extraordinarias para evaluar la causa de la falta de coordinación y se harán cambios en los encargados de los equipos |
| 41 | Falta de programas de capacitación | 7 | 9 | 63 | 1 | Los propios desarrolladores más formados en las tecnologías para las que no se encuentren programas de capacitación, se encargarán de hacer de profesores para capacitar al resto de desarrolladores
 |
| 42 | Errores en la estimación de costes | 6 | 9 | 54 | 2 | Utilizar métodos de estimación robustos, desglosar el alcance del proyecto, incluir reservas de contingencia y revisar constantemente los costes |
| 43 | Falta de documentación generada | 5 | 8 | 32 | 6 | Se realizarán cambios en el cronograma para añadir nuevas tareas que tengan como finalidad realizar la documentación que se ha pasado por alto en otros momentos |
| 44 | Uso de tecnologías obsoletas | 3 | 8 | 24 | 7 | Realizar un proceso adecuado para escoger tecnologías punteras que faciliten el desarrollo del proyecto utilizando las versiones más actuales posibles en cada caso |
| 45 | Proceso para la gestión del cambio mal definido | 3 | 8 | 24 | 7 | Se evaluará el proceso de gestión del cambio para ver en qué puntos falla o no se aplica y se realizarán cambios para asegurarnos de tener un buen proceso de gestión del cambios y asegurarnos de su estricto cumplimiento |
| 46 | Retrasos por las dependencias de tareas | 6 | 7 | 42 | 4 | Reorganizar las tareas en función de la disponibilidad del equipo para que los desarrolladores que tengan disponibilidad antes, hagan las tareas de las que dependen otras tareas |
| 47 | Bajada del rendimiento de un integrante o del equipo tras un periodo de descanso del mismo | 6 | 7 | 42 | 4 | Se detectará si baja el rendimiento a partir de la medida de los puntos de esfuerzo por hora y si se detecta que desciendo el rendimiento de alguien se harán reuniones privadas para ver el motivo del bajón de rendimiento y para motivar al integrante a seguir trabajando como antes del parón |
</div>

## **CONCLUSIONES**

Intencionalmente vacío.

## **BIBLIOGRAFÍA**

Intencionalmente vacío.

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

Consulta sobre riesgos de propósito general en proyectos de desarrollo software:

[https://chat.openai.com/share/50f98cee-a6a3-4772-89af-77679cc1aed1](https://chat.openai.com/share/50f98cee-a6a3-4772-89af-77679cc1aed1)

Consulta sobre planes de acción en riesgos como errores en la estimación de costes, falta de escalabilidad o expectativas poco realistas:

[https://chat.openai.com/share/d2d7037e-2d4e-46bd-93af-4b653e3fbd77](https://chat.openai.com/share/d2d7037e-2d4e-46bd-93af-4b653e3fbd77)