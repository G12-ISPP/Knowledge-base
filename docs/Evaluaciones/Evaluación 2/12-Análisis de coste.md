![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 01/03/2024

# **ANÁLISIS DE COSTE**


## **REALIZADO POR:**
<div class="markdown-table">
| Baquero Villena, Carlos | Campano Galán, Alejandro | Campos Garrido, Juan Jesús |
| --- | --- | --- |
| Carretero Díaz, Antonio | Cortabarra Romero, David | Escalante Ramos, María |
| García Linares, Diego | García Sánchez-Hermosilla, Alejandro | Garrucho Sánchez, Úrsula |
| Mera Gómez, Pablo | Reyes Alés, David | Santiago Félix, Alejandro |
</div>

### **2ª ENTREGA**

### **- GRUPO 12 -** 

### **ÍNDICE DE CONTENIDOS**
<div class="markdown-center">

[**CONTROL DE VERSIONES**](#control-de-versiones)

[**RESUMEN EJECUTIVO**](#resumen-ejecutivo)

[**INTRODUCCIÓN**](#introducción)

[**CONTENIDOS**](#contenidos)

[**COSTE DE PUESTA EN FUNCIONAMIENTO**](#coste-de-puesta-en-funcionamiento)

[**COSTE OPERACIONAL**](#coste-operacional)

[**TCO**](#tco)

[**RENTABILIDAD DEL NEGOCIO**](#rentabilidad-del-negocio)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)

</div>

# **CONTROL DE VERSIONES**
<div class="markdown-table">
| **Versión** | **Descripción de los cambios** | **Autor** | **Fecha** |
| --- | --- | --- | --- |
| v1.0.0 | Inicio del documento | García Sánchez-Hermosilla, Alejandro | 15/02/2024 |
| v1.1.0 | Versión para la primera evaluación | García Sánchez-Hermosilla, Alejandro  Escalante Ramos, María | 15/02/2024 |
| v1.2.0 | Ajuste de costes tras calcular la necesidad de GitHub Actions | Campos Garrido, Juan Jesús | 22/02/2024 |
| v1.3.0 | Revisión del coste para añadir los conceptos CapEx OpEx | Campos Garrido, Juan Jesús | 01/03/2024 |
| v1.4.0 | Añadidos distintos escenarios para medir la rentabilidad | Campos Garrido, Juan Jesús | 01/03/2024 |
</div>

## **RESUMEN EJECUTIVO**

En este documento se hace un **análisis sobre los costes** que abarcan el alcance del proyecto tanto en el ciclo de vida del desarrollo como en el despliegue.

Para ello se ha seccionado en diferentes partes, como por ejemplo, **coste capital, coste operacional, coste restante y coste total de TCO**. Durante el desglose de los costes, se ha llevado a cabo la idea de realizar un **análisis de la rentabilidad** del negocio suponiendo unas transacciones mensuales y suscripciones.

Y finalmente como conclusión del documento se exponen los **costes totales** en un plazo de **2 años de uso** de la aplicación, conjunto a los **beneficios** que obtendremos en contraparte de lo que ha costado el proyecto en tres escenarios diferentes.

## **INTRODUCCIÓN**

En este documento se llevará a cabo una explicación del análisis de costes estimado, para comprobar cuánto costaría el inicio del proyecto desde 0, y el mantenimiento de la aplicación desplegada y disponible para todos los usuarios.

Las secciones a tratar en este documento serán, coste capital, coste operacional, costes extras (ya sean destinados a fondos de contingencias o apartados que no encajen en los 2 anteriores), rentabilidad del negocio, TCO global y una breve conclusión del documento.

Para realizar esta estimación y el cálculo sobre la rentabilidad del negocio, se ha investigado en internet mediante un estudio exhaustivo, cuánto dinero se invierte en el mercado de las impresiones en 3D. Por ello en las secciones de bibliografía o Prompts podemos consultar de donde salen los datos escogidos para llevar a cabo estas estimaciones.

## **CONTENIDO**

En este apartado se explicarán cuáles serán los costes en los que se incurrirá para llevar a cabo el proyecto en base al modelo de negocio contemplado en nuestro equipo. Para ello trataremos todos los aspectos posibles en los que se pueda incurrir, tanto en el desarrollo del producto como en el mantenimiento necesario posterior. También se analizará la rentabilidad que obtendremos del sistema de negocio.

### **COSTE DE PUESTA EN FUNCIONAMIENTO**

Este coste trata de estimar el coste total que los trabajadores supondrán para la empresa. Las horas totales trabajadas deben ser:

En primer lugar habría que tener en cuenta el coste de los equipos de los desarrolladores, para esto asumimos que cada desarrollador trabajará con un ordenador de 1000€, y asumimos que la vida útil de un equipo de estas características es de 4 años, lo que son 48 meses, teniendo esto en cuenta, los equipos consumirán en el proyecto 4 meses, lo que supone un 0,083% de su vida útil. Por lo que el valor correspondiente a cada equipo en el proyecto será de **83€**, teniendo en cuenta que necesitamos 12 equipos, en total serán **996€.**

**12 trabajadores × 15 semanas × 10 horas/semana = 1800 horas**

En la siguiente tabla se muestra un desglose detallado de los perfiles laborales que participarán en el proyecto; especificando el sueldo por hora bruto, las horas trabajadas por perfil y el coste total asociado resultante de la multiplicación de ambos datos anteriores. Finalmente mediante la suma de los costes totales de cada perfil obtenemos el coste total que supondrá la contratación del equipo de trabajo para la empresa.

| **Perfil** | **Sueldo por hora bruto (sin IVA)** | **Horas trabajadas por perfil** | **Coste total** |
| --- | --- | --- | --- |
| Project Manager | 35,35 €/h | 400 h | 14.140 € |
| Desarrolladores Backend | 25,67 €/h | 350 h | 8.984,50 € |
| Desarrolladores Frontend | 25,67 €/h | 350 h | 8.984,50 € |
| Documentalistas | 13,71 €/h | 100 h | 1.371 € |
| Analistas de negocios | 23,65 €/h | 150 h | 3.547,50 € |
| Especialista en QA | 30,46 €/h | 100 h | 3.046 € |
| Especialistas en base de datos | 22,17 €/h | 100 h | 2.217 € |
| Diseñadores gráfico | 20,15 €/h | 100 h | 2.015 € |
| DevOps | 12,05 €/h | 150 h | 1.807,5 € |
| Total | \-  | 1.800 h | **46.113 € \*\*** |

**\*\*** Los costes de cada perfil han sido calculados en base a los salarios mínimos brutos estipulados para empleados junior.

A este coste habría que sumarle el coste de la licencia de hospedar el proyecto en GitHub. Para ello se ha escogido la opción de suscripción Team con un precio de 3,28 €/mes por usuario de la empresa, lo que hace un total de **39,36 €/mes** ya que somos 12 desarrolladores en el proyecto. Durante 4 meses lo que haría un total de **157,44€**.

Se ha escogido la suscripción Team ya que esta nos asegura 3.000 minutos de CI al mes. Estimando que cada ciclo de integración continua tarde como máximo diez minutos, podríamos realizar 300 ciclos al mes, cantidad que el equipo estima que será más que suficiente para el desarrollo del proyecto.

Adicionalmente habría que tener en cuenta el coste de utilizar plataformas para gestionar la calidad del proyecto durante su desarrollo en concreto utilizaremos SonarCloud con un plan que costaría 11 €/mes durante cuatro meses.

Finalmente tendríamos un coste de puesta en marcha de **47.310,44€**

### **COSTE OPERACIONAL**

Este es el coste que a la empresa le supondrá tener la plataforma desplegada y operativa para su uso por parte de los usuarios. En nuestro caso utilizaremos un PaaS lo que nos obliga a alquilar un servidor de despliegue web para el hosting.

Tras realizar un estudio sobre las plataformas de despliegue más utilizadas por las diferentes entidades (Amazon Web Services, Google Cloud, Heroku, Vultr), hemos estimado que el coste mensual de desplegar el servicio es de **179,32€/mes**.

Con esto en la mayoría de casos obtendremos una instancia con 6 núcleos de cpu 10 gb de ram y 20 de almacenamiento lo que puede soportar un total de 10.000 personas concurrentemente.

Además del propio despliegue se ha decidido contratar a un técnico para que realice revisiones y mejoras correctivas mensuales del servicio de despliegue por un sueldo de 10 €/hora y 75 h/mes que da un total de **750 €/mes.**

Además, debemos tener en cuenta el coste de GitHub para el técnico que realice las revisiones y mejoras correctivas lo que implicaría un gasto de **3,28€/mes.**

También debemos de tener en cuenta que para mantener la calidad del código en el proyecto vamos a usar SonarCloud que tiene un precio de **11 €/mes** durante el tiempo que la aplicación esté desplegada.

Lo que en resumen conlleva un coste operacional de **943,6€/mes**.

### **TCO**

Por lo tanto el coste de propiedad de la aplicación al cabo de dos años se podría descomponer de la siguiente forma:

CAPEX:

- Coste de los equipos necesarios para el proyecto: 996€

OPEX:

- Coste de los contratos de los desarrolladores 46.133€
- Coste de licencias de GitHub durante el desarrollo 157,44€
- Coste de licencias de sonarCloud durante el desarrollo 44€
- Coste de licencias de GitHub durante el ciclo de vida del servicio 78,72€
- Coste del despliegue 4.303,68€
- Coste de licencias de SonarCloud al cabo de dos años del servicio 528€
- Coste de las revisiones y mejoras continuas 18.000€

A estos costes se añadirá una reserva de contingencia de 2.000€

Por lo que en total el coste de propiedad del servicio al cabo de dos años será de 72.240,84 €

### **RENTABILIDAD DEL NEGOCIO**

En el contexto de esta aplicación tenemos que tener en cuenta que vamos a sacar un beneficio económico de diferentes aspectos, no solamente de la impresión de productos en tres dimensiones.

En nuestra idea de negocio un usuario puede realizar las siguientes actividades, suscribirse a un plan para obtener ciertas ventajas sobre la aplicación, en este caso dependiendo del rol del usuario el plan tiene un precio determinado:  

- Plan de vendedor: **15 €/mes**
- Plan de comprador: **10 €/mes**
- Plan de diseñador: **15 €/mes**

Además de esto también proporcionamos un servicio de compraventa de productos de tres dimensiones, tantos productos como se imaginen, desde accesorios para las impresiones en 3D como filamentos, hasta las propias impresoras o productos impresos en 3 dimensiones.

Haciendo unas estimaciones generales viendo como se encuentra el mercado de las impresiones en 3D, calculamos que de cada transacción obtendremos un beneficio medio de 3€, esto es debido a la gran diferencia entre productos, a causa de la diversidad de magnitudes entre objetos imprimibles.

A continuación, realizaremos un estudio con el objetivo de determinar si el negocio es rentable en un plazo de 2 años diferenciando varios escenarios:

En un escenario intermedio las suposiciones serían las siguientes:

En cuanto a las ganancias en las ventas de productos anualmente, se estima que en Europa existe un gasto de 4.000 millones de euros en productos 3D y se prevé que haya un aumento del 17% para 2025 y se mantenga constante. Por lo que un número de 200 transacciones mensuales es una estimación razonable para los cálculos futuros. Teniendo en cuenta todas estas estimaciones y cálculos basados en datos estadísticos, esto supone que en total obtendremos:

- Suscripción comprador: **14400€**

- Suscripción vendedor: **21600€**

- Suscripción diseñador: **21600€**

- Beneficio ventas: **14400€**

Todo esto hace un total de **72.000€** en 2 años. Que comparándolo con los **72.240,84 €** que costaría la propiedad del servicio en ese mismo tiempo, nos da la seguridad de que recuperamos la inversión inicial y a partir del tercer año empezaríamos a ganar dinero.

En un escenario pesimista las suposiciones serían las siguientes:

Se estiman 100 transacciones mensuales, donde el precio por transacción sería igualmente de 3€ y se estima que venderíamos 40 cuentas de cada tipo mensualmente. Teniendo en cuenta todas estas suposiciones podríamos obtener:

- Suscripción comprador: **9600€**

- Suscripción vendedor: **14400€**

- Suscripción diseñador: **14400€**

- Beneficio ventas: **7200€**

Todo esto haría un total de **45.600€**, una cifra bastante inferior a los **72.240,84 €** que costaría la propiedad del servicio durante este periodo, en este escenario la aplicación podría llegar a ser rentable al cabo de varios años más, pero no a corto plazo, por lo que la aplicación no sería realmente sostenible.

En un escenario optimista las suposiciones serían las siguientes:

Se estiman 300 transacciones mensuales, donde el precio por transacción sería igualmente de 3€ y se estima que venderíamos 100 cuentas de cada tipo mensualmente. Teniendo en cuenta todas estas suposiciones podríamos obtener:

- Suscripción comprador: **24000€**

- Suscripción vendedor: **36000€**

- Suscripción diseñador: **36000€**

- Beneficio ventas: **21600€**

Todo esto haría un total de **117.600€**, una cifra superior a los **72.240,84 €** que costaría la propiedad del servicio durante este periodo, en este escenario la aplicación sería altamente rentable.


## **CONCLUSIONES**

Anteriormente, en el análisis de la rentabilidad obtuvimos que con las ventas realizadas en los escenarios positivo e intermedio, al cabo de dos años, la aplicación empieza a ser sostenible.

Y en el caso negativo la aplicación podría llegar a ser sostenible al cabo de varios años, pero no a corto plazo.

**Por todo esto, nuestro negocio es sostenible económicamente.**

## **BIBLIOGRAFÍA**

- [https://www.mordorintelligence.com/es/industry-reports/automated-3d-printing-market]
- [https://www.interempresas.net/Fabricacion-aditiva/Articulos/472878-La-impresion-aditiva-Informe-2023.html]
- [Tabla de salario de perfiles] (https://www.juntadeandalucia.es/export/drupaljda/DGTD_instruccion_perfiles_TIC.pdf)
- [Enlace calculo de coste de productos 3D](https://www.interempresas.net/Fabricacion-aditiva/Articulos/372358-El-mercado-de-la-impresion-3D-facturara-10120-millones-en-2025.html)

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

En esta sección se recogen los diferentes prompts que se han usado a través de diferentes inteligencias artificiales:

**CHATGPT**

- [Ayuda para costes preliminares](https://chat.openai.com/share/8e941490-dd91-40c5-a53c-5ff59102beba)
- [Analisis de personas concurrentes y precio de GitHub](https://chat.openai.com/share/75b42eab-42f0-424a-85c0-6314ec0e711c)
- [Consulta sobre el tipo de costes del personal de desarrollo](https://chat.openai.com/share/c918717a-13ba-4af7-8001-013f075fc8b1)