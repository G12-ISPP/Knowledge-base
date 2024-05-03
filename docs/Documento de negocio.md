![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 05/05/2024

# **DOCUMENTO DE NEGOCIO**

### **PPL**

### **- GRUPO 12 -** 

# **CONTROL DE VERSIONES**

<div class="markdown-table">

| **Versión** | **Descripción de los cambios** | **Autor** | **Fecha** |
| --- | --- | --- | --- |
| v0.1.0 | Creación del documento | García Linares, Diego | 01/02/2024 |
| v0.3.0 | Descripción de la idea de negocio y objetivos | Reyes Alés, David | 02/02/2024 |
| v0.4.0 | Mejoras en la idea de negocio y creación de un MVP preliminar | Campos Garrido, Juan Jesús | 02/02/2024 |
| v0.5.0 | Redacción inicial del dafo | García Linares, Diego | 02/02/2024 |
| v0.6.0 | Revisión y mejora del MVP y discusión técnica del mismo | Carretero Díaz, Antonio | 03/02/2024 |
| v0.7.0 | Mejora sobre el DAFO | Mera Gómez, Pablo | 08/02/2024 |
| v1.0.0 | Actualización de formatos y revisión del documento | García Linares, Diego | 17/02/2024 |
| v1.1.0 | Revisión, DAFO, resumen ejecutivo, introducción, conclusiones y pequeñas correcciones. | Baquero Villena, Carlos | 18/02/2024 |
| v1.2.0 | Corrección en la idea de negocio y formato de colores en las tablas | Campos Garrido, Juan Jesús | 18/02/2024 |
| v1.5.0 | Conversión a Markdown | García Linares, Diego | 08/03/2024 |
| v2.0.0 | Revisión en el sprint 2 para evitar failure conditions | Campos Garrido, Juan Jesús | 31/03/2024 |
| v2.0.1 | Revisión en el sprint 3 para evitar failure conditions | Campos Garrido, Juan Jesús | 21/04/2024 |
| v2.0.2 | Revisión documento para evitar failure conditions | Campos Garrido, Juan Jesús | 05/05/2024 |
</div>

### **ÍNDICE DE CONTENIDOS**
<div class="markdown-center">

[**RESUMEN EJECUTIVO**](#resumen-ejecutivo)

[**INTRODUCCIÓN**](#introducción)

[**CONTENIDOS**](#contenidos)

[**IDEA CLAVE DE NEGOCIO**](#idea-clave-de-negocio)

[**OBJETIVO PRINCIPAL**](#objetivo-principal)

[**TIPO DE NEGOCIO**](#tipo-de-negocio)

[**MVP**](#mvp)

[**GRADO DE INNOVACIÓN TÉCNICA DEL MVP**](#grado-de-innovación-técnica-del-mvp)

[**DAFO**](#dafo)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)

</div>

## **RESUMEN EJECUTIVO**

En este documento se explica detalladamente la idea de negocio, tipo de negocio, MVP y el grado de innovación técnica. Se explica que nuestro servicio será un sistema web para ejercer la compra/venta de productos y diseños en el ámbito de la impresión 3D. Se contará con varios tipos de usuario dentro de la aplicación como usuario, diseñador o impresor.

## **INTRODUCCIÓN**

Nuestro negocio está pensado para cubrir un nicho de mercado en auge que está todavía muy poco explotado, debido a su prematura existencia. El mundo de las impresoras 3D es un mercado muy precoz que consideramos que está todavía en una etapa muy temprana, y las personas que están muy interesadas en él necesitan una comunidad donde poder compartir sus ideas e inquietudes. De esto se encargará nuestro servicio.

En las siguientes páginas se explicará detalladamente como nuestro servicio será un sistema web para ejercer la compra/venta de productos y diseños en el ámbito de la impresión 3D. Se explicará cuál es la idea y tipo de negocio, el MVP y el grado de innovación técnica.

## **CONTENIDOS**

### **IDEA CLAVE DE NEGOCIO**

#### Compra y vende todo tipo de productos relacionados con la impresión 3D. Haz realidad tus diseños favoritos, y pon a disposición de otros las herramientas necesarias para llevarlos a cabo. Todo ello, sin intermediarios, donde proveedor y consumidor podrán negociar el precio más conveniente. Con la idea de crear una comunidad donde todos puedan compartir sus creaciones y ayudar a los demás a hacer sus propias creaciones

### **OBJETIVO PRINCIPAL**

El objetivo que persigue este sistema es desarrollar una plataforma colaborativa en la que personas que dispongan de una impresora 3D puedan ayudar a otras que la soliciten a cambio de una compensación económica. Además, este proyecto estimulará la creatividad de los usuarios a través de la publicación de sus ideas con el fin de materializarlas. También reunirá y conectará a una comunidad de personas interesadas en la fabricación digital y la tecnología de impresión en tres dimensiones. También fomentará la reutilización de elementos ya fabricados mediante su venta a usuarios que realmente lo necesiten. No solo esto, sino que los diseñadores podrán también usar esta plataforma para vender sus diseños o ayudar a usuarios que no saben diseñar a crear su idea desde 0, generando ganancia así tanto el diseñador, el usuario y nosotros, llevándonos un porcentaje de cada diseño vendido.

Todo esto basado siempre en la colaboración entre usuarios, para así crear una gran comunidad tanto de diseñadores, impresores y entusiastas del diseño y de la impresión 3D, llegando a hacer concursos o subastas para mantener nuestra página viva.

### **TIPO DE NEGOCIO**

Principalmente nos gustaría desarrollar un sistema web para ejercer la compra/venta de productos y diseños en el ámbito de la impresión 3D. Esta es la idea base, pero nuestro factor diferenciador es que el sistema dispondrá de un apartado donde se puede pedir la impresión de un diseño a otros usuarios “impresores”, que pondrán a disposición de los usuarios consumidores su hardware especializado para construir los diseños adjuntos, así como otro apartado de chat interactivo para poder pedir diseños personalizados a otro tipo de usuarios “diseñadores”.

En resumen tendremos una micro red social de amantes de la impresión 3D, sumado al apartado de compra venta de productos y diseños genéricos al que los usuarios también tendrán acceso (tanto consumidores como proveedores). Esto no solo funcionará para usuarios casuales que quieran una pieza de su animal o superhéroe favorito, también pequeños o medianos empresarios podrán pedir la impresión de X cantidad de una pieza con la cual varios impresores de su elección se harán cargo para así hacer nuestro negocio más escalable.

Para ello, el sistema dispondrá de un sistema de “matchmaking”, el cuál se explicará con mayor detalle en los siguientes puntos, que nos permita relacionar usuarios entre sí, teniendo en cuenta algunos parámetros: Tipo de envío, afinidades en estilo de impresión, diseño, cercanía, precios…

Con todo esto podemos implementar las siguientes ideas de negocio:

- Comisiones en la compra-venta sin intermediario (por el uso de nuestro sistema), que no sean desproporcionadas, para hacer atractiva la utilización del servicio. Esta compra-venta no tiene porqué ser de piezas únicas sino de impresoras o material que algún usuario necesite vender, ya sean impresoras, bobinas de material…
- Planes para vendedores, para destacar productos y diseños.
- Planes para compradores frecuentes, para deshacerse de gastos de envíos en cada compra.
- Planes para diseñadores, para que puedan publicitar sus servicios de diseño de piezas a medida para un comprador.

Por último, cabe decir que, a juicio del equipo, es un sistema muy explotable, prometedor y con mucha posibilidad de ampliación de cara a un futuro.

### **MVP**

| **Como** | **Quiero** | **Para** |
| --- | --- | --- |
| Usuario | Añadir producto publicado al carrito | tener guardada una impresora, diseño o impresión |
| Usuario | Comprar el carrito | poder comprar productos de la aplicación |
| Usuario | Poder solicitar a un impresor la impresión de una pieza negociando el precio | Conseguir que me impriman mi pieza a un buen precio |
| Impresor | Poder subir mis artículos a la aplicación | que otros usuarios puedan comprarlos |
| Impresor | un chat | negociar la impresión a medida de una pieza con un usuario |
| Usuario | solicitar la impresión a medida de muchas piezas | Conseguir muchas piezas a un buen precio |
| Usuario | Poder solicitar un diseño personalizado | Obtener piezas a mi gusto |
| Diseñador | Un chat | para comunicarme con los usuarios que quieran un diseño personalizado |

### **GRADO DE INNOVACIÓN TÉCNICA DEL MVP**

| **Caso de uso** | **Nivel de innovación** | **Razonamiento** |
| --- | --- | --- |
| Gestión del carrito | Bajo | El grupo lo ha implementado anteriormente |
| Comprar el contenido del carrito | Bajo | El grupo lo ha implementado anteriormente |
| Solicitar a un impresor la impresión de una pieza negociando el precio | Medio | Se necesitará crear un chat donde los dos implicados negocien, para esto se necesitará utilizar tecnología de websockets |
| Subir artículos a la aplicación | Bajo | El grupo lo ha implementado anteriormente |
| Solicitar impresión a medida | Alto | Esta funcionalidad requerirá utilizar librerías nunca antes utilizadas por el equipo para tener un visor 3d del diseño y calcular el precio de imprimir dicho diseño |
| Solicitar un diseño a medida | Medio | De nuevo necesitaremos crear un chat con tecnología de web sockets para que dos personas puedan negociar a través de él un diseño a medida |

Para poder llevar a cabo esta aplicación utilizaremos Django como Framework de desarrollo backend junto a React como Framework de desarollo React, tecnologías conocidas por el equipo y que nos permitirán desarrollar el proyecto.

### **DAFO**

En este apartado se van a definir las debilidades, fortalezas, oportunidades y amenazas a la hora de realizar el proyecto, para tener claro tantos nuestros puntos fuertes como débiles al empezar el desarrollo.

| **FORTALEZAS** | **DEBILIDADES** |
| --- | --- |
| \- Red social especializada: con esto fomentamos la retención de clientes haciendo que sea una experiencia agradable y así conseguir una comunidad activa y fiel.\- Innovador sistema de matchmaking: con esto mejoramos la experiencia de usuario facilitando el emparejamiento entre diseñadores, compradores y vendedores.\- Modelo de negocio escalable: a largo plazo el modelo de negocio sería fácilmente escalable ya que al no estar enfocado a la compra/venta de diseños y objetos hechos con impresoras 3D podríamos hacer eventos, añadir funcionalidades las cuales nos diferencian mucho de la competencia.\- Diversidad de productos y servicios: no nos enfocaremos únicamente en el diseño y envío de piezas sino también en la venta de hardware relacionado, diseños exclusivos, distintos tipos de material…\- Proximidad entre los implicados: debido a nuestro chat y a nuestra conexión directa entre comprador, vendedor y diseñador crearemos una sensación de mayor confianza ya que estos estarán en contacto durante todo el proceso, tanto para hacer cambios como para ver el progreso de la impresión y diseño. | \- Competencia en el mercado online: la competencia en el mercado electrónico es abundante por tanto debemos diferenciarnos tanto en funcionalidades como en la calidad del servicio.\- Posibles fallos técnicos: es posible que se produzcan retrasos por culpa del envío al no poder controlar posibles fallos técnicos del hardware del vendedor y demás problemas por conexión.\- Dependencia de terceros: este negocio depende totalmente de proveedores externos que sean lo suficientemente confiables para completar las transacciones en el plazo establecido además de con la calidad y características pactadas con el vendedor.\- Dependencia de la calidad de la impresión: el buen acabado de la pieza va a depender de la impresora con la que se haga y puede ser diferente al esperado debido a parámetros como calibración, densidad o calidad del hilo, dejando esto desalineaciones o impresiones defectuosas bajando así la reputación de la plataforma aunque eso no dependa en sí de nosotros sino de la decisión del vendedor. |
| **OPORTUNIDADES** | **AMENAZAS** |
| \- Mercado en crecimiento: en los últimos años la demanda de productos impresos en 3D ha aumentado debido a la libertad que nos brinda esta tecnología a la hora de diseñar y fabricar piezas.\- Alianzas y proveedores: posibilidad de colaborar con diseñadores reconocidos además de conseguir proveedores externos de los cuales poder sacar un beneficio mútuo.\- Captación de usuarios casuales: brindamos la oportunidad a un usuario casual de hacer cualquier impresión ya que los costes de hacerlo son extremadamente elevados. | \- Avances rápidos en la tecnología: debido a los avances rápidos de la tecnología puede ser que en un futuro todo el mundo pueda tener en su casa una impresora 3D sin que suponga un gasto extra.\- Recesión económica: en una posible recesión económica este servicio no sería rentable ya que no es un producto de primera necesidad por lo tanto bajarán las ventas drásticamente.\- Desvinculación de la plataforma: un posible riesgo sería que los usuarios usaran una plataforma de comunicación externa para proceder con el mismo servicio para no pagar la comisión y cobrar el dinero íntegramente. |

El proyecto presenta un alto potencial ya que se encuentra en un mercado con un crecimiento exponencial del cual aún se puede sacar mucho rendimiento y todavía queda mucha innovación por llevar a cabo. También será de gran utilidad ya que va a hacer que la comunidad crezca significativamente conectando a todos los usuarios. Por otra parte, debemos tener en cuenta que hay varios competidores los cuales acaparan bastante cuota de mercado y para ello tendremos que diferenciarnos de estos para garantizar la sostenibilidad y el éxito a largo plazo del proyecto.

Gracias a la amenaza de que la tecnología va cambiando continuamente, tenemos la oportunidad de captar más usuarios. Con un modelo de negocio escalable y un innovador sistema de matchmaking, podemos adaptarnos rápidamente a estos avances tecnológicos, ofreciendo constantemente nuevas funcionalidades y mejoras que mantengan a nuestros usuarios comprometidos y satisfechos. Además, nuestra red social nos permite crear una comunidad activa y fiel que esté al tanto de las últimas tendencias, desarrollos en el mundo de la impresión 3D.

La competencia en el mercado online puede ser una debilidad, pero también puede convertirse en una fortaleza si sabemos diferenciarnos y ofrecer un servicio de calidad superior. Nuestra diversidad de productos y servicios nos permite destacar entre la competencia al ofrecer no solo diseños exclusivos, sino también hardware relacionado y diferentes tipos de material, brindando a nuestros usuarios una experiencia completa y personalizada.

Los posibles fallos técnicos y la dependencia de terceros pueden ser desafíos, pero también nos ofrecen la oportunidad de establecer relaciones sólidas con proveedores confiables y desarrollar protocolos de contingencia efectivos para minimizar los impactos negativos en nuestros clientes. Además, la proximidad entre los implicados gracias a nuestro chat y conexión directa puede convertirse en una fortaleza al generar confianza y transparencia en todo el proceso de compra y diseño.

Contra la desvinculación de la plataforma podemos implementar programas de fidelización u ofrecer descuentos exclusivos. Esto no solo aumentará la retención de usuarios, sino que también fortalecerá nuestra posición en el mercado como la opción preferida para todos los aspectos relacionados con la impresión 3D.

En resumen, al enfrentar estas características, nuestro negocio de matchmaking en el ámbito de la impresión 3D puede convertir las amenazas en oportunidades y las debilidades en fortalezas, permitiéndonos mantenernos ágiles, innovadores y centrados en ofrecer un servicio excepcional a nuestra comunidad de usuarios.

## **CONCLUSIONES**

A la hora de comenzar el desarrollo de un producto o servicio, es muy importante tener muy claro a qué público va dirigido y cuáles van a ser sus principales funcionalidades. En este documento se puede tener una idea muy clara y concisa de por qué y para quién se desarrollará nuestro servicio.

## **BIBLIOGRAFÍA**

Intencionalmente vacío

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

Intencionalmente vacío