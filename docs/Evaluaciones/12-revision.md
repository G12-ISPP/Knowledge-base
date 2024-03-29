![alt text](/img/logo.png)

## **PROYECTO**

## **SHAR3D**

#### 28/02/2024

# **GUÍA DE REVISIÓN**


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

[**CASO 1: REGISTRO DE USUARIOS**](#caso-1:-registro-de-usuarios)

[**CASO 2: INICIO Y CIERRE DE SESIÓN**](#caso-2:-inicio-y-cierre-de-sesion)

[**CASO 3: SOLICITAR IMPRESIÓN**](#caso-3:-solicitar-impresion)

[**CASO 4: PAGAR CON PAYPAL**](#caso-4:-pagar-con-paypal)

[**CASO 5: VENDER PRODUCTO**](#caso-5:-vender-producto)

[**CASO 6: DETALLES DE PRODUCTO**](#caso-6:-detalles-de-producto)

[**CASO 7: DETALLES DE USUARIO**](#caso-7:-detalles-de-usuario)

[**CASO 8: CARRITO DE LA COMPRA**](#caso-8:-carrito-de-la-compra)

[**CONSIDERACIONES**](#consideraciones)

[**CONCLUSIONES**](#conclusiones)

[**BIBLIOGRAFÍA**](#bibliografía)

[**PROMPTS DE INTELIGENCIA ARTIFICIAL**](#prompts-de-inteligencia-artificial)
</div>

### **CONTROL DE VERSIONES**
<div class="markdown-table">

| **Versión** | **Descripción de los cambios** | **Autor** | **Fecha** |
| --- | --- | --- | --- |
| v0.1 | Creación del documento | Mera Gómez, Pablo | 28/02/2024 |
| v1.0 | Primera versión | Mera Gómez, Pablo| 01/03/2024 |
| v1.1 | Retoques finales | Mera Gómez, Pablo | 01/03/2024 |
| v2.0 | Nuevas funcionalidades | Mera Gómez, Pablo | 19/03/2024 |

</div>

## **RESUMEN EJECUTIVO**

En este documento se explican los 8 casos de uso implementados en el
servicio Shar3D durante el primer sprint: Registro de usuarios, inicio y
cierre de sesión, solicitar impresión, pagar con PayPal, vender
producto, detalles del producto, detalles de usuario y carrito de la
compra**.**

Para ello, hemos realizado una explicación muy detallada de qué deben
hacer para probar toda la funcionalidad implementada ayudándose de
imágenes, que en todo momento permitan a los usuarios interactuar con el
servicio.

## **INTRODUCCIÓN**

En este documento se va a realizar una explicación sobre cómo
interaccionar con el servicio Shar3D para comprobar el correcto
funcionamiento de todos los casos de uso implementados hasta la fecha
establecida.

## **CONTENIDO 1º SPRINT**

Primero de todo, la landing page de SHAR3D se encuentra en la URL:

[[https://landing-page-shar3d.vercel.app/]](https://landing-page-shar3d.vercel.app/)
desde aquí puedes acceder a la web del sistema en funcionamiento
navegando hacia "Nuestros lanzamientos", al final de la página
principal.

Si quiere directamente acceder a la web del sistema, sobre la cual se
realizarán las pruebas debe acceder a la URL:

[[https://ispp-s1.vercel.app/]](https://ispp-s1.vercel.app/)

El GitHub del equipo de trabajo se encuentra en la siguiente URL:

[[https://github.com/G12-ISPP/ISPP]](https://github.com/G12-ISPP/ISPP)

La herramienta para registrar las horas de cada uno de los miembros es
Clockify, para distinguir el trabajo de cada uno puede acceder a la URL:

[[https://app.clockify.me/shared/65d87eea756abe0bdf308a40]](https://app.clockify.me/shared/65d87eea756abe0bdf308a40)

Una vez tienen las distintas páginas, le proporcionaremos los datos
indispensables para que pueda acceder a la web y probar todo lo que
explicaremos posteriormente:

-   URL de la web: [[https://ispp-s1.vercel.app/]](https://ispp-s1.vercel.app/)

-   Credenciales administrador:

    -   Usuario: admin

    -   Contraseña: 4dm1n

-   Credenciales usuario:

    -   Usuario: user1

    -   Contraseña: us3r

    -   Usuario: user2

    -   Contraseña: us3r

-   Credenciales PayPal:

    -   Correo: sb-k43ebi28280380@personal.example.com

    -   Contraseña: nNU\<\<9Y%

En el caso de las credenciales de administrador, su uso va a ser
irrelevante para esta revisión debido a que no ofrece funcionalidad
distinta a la que de por sí tienen los usuarios, por lo tanto, no es
necesario acceder como administrador. Además, las credenciales de
usuario sí pueden ser útiles, pero para que pueda entender cómo
registrarse y tener su propio usuario y contraseña, le vamos a mostrar
el primer caso de uso.

### **CASO 1: REGISTRO DE USUARIOS**

> En esta sección, explicaremos cómo registraros en el sistema, primero
> de todo, tenemos la vista del menú principal \[Figura> 1\]:![](/img/revision/image46.png)

Figura 1 - Menú principal

Antes de todo, debemos saber que para volver a la pantalla del menú
principal, en cualquier lugar de la web, tendremos el botón SHAR3D
ubicado en la esquina superior izquierda, que tras pulsarlo siempre nos
redireccionará a este sitio.

Una vez en esta pantalla, debemos pulsar sobre el botón "Registrarse" en
la esquina superior derecha de la ventana \[Figura 2\]

> ![](/img/revision/image28.png)
Figura 2 - Botón de registro

Tras ello, el sistema te redireccionará a la pantalla de registro
\[Figura 3\], donde vas a poder ver cada uno de los campos a rellenar y
deberás introducir datos acordes a lo que pide el formulario, en caso de
que no se cumplan las restricciones de cada uno de estos atributos, el
sistema le mostrará un mensaje de error sobre el campo que no se adecua
a la estructura que deseamos \[Figura 4\]. Sin embargo, si cumplimenta
los campos de manera adecuada, el sistema almacenará los datos y le
mostrará una alerta \[Figura 5\] que, tras pulsar sobre aceptar, le
mandará de nuevo a la página principal del sistema. A partir de ahí, ya
podrá iniciar sesión a través del usuario y la contraseña que ha creado
anteriormente.

Figura 3 -- Formulario
registro![](/img/revision/image44.png)

![](/img/revision/image32.png)

Figura 4 - Ejemplo de error

![](/img/revision/image35.png)

Figura 5 - Alerta de registro exitoso

### **CASO 2: INICIO Y CIERRE DE SESIÓN**

Una vez registrados como usuarios del sistema, podremos iniciar sesión
para probar todas las funcionalidades. Para ello, debemos pulsar sobre
"Iniciar sesión" \[Figura 6\] en la esquina superior derecha de la
pantalla del menú principal \[Figura 1\], justo a la izquierda del botón
"Registrarse" visto anteriormente.

> ![](/img/revision/image29.png)

Figura 6 - Botón inicio de sesión

Una vez pulsado, el sistema nos redirigirá al formulario de iniciar
sesión \[Figura 7\], en el cuál únicamente nos solicitarán el usuario y
la contraseña. En el caso de proporcionar un usuario o contraseña
incorrectos, el sistema nos mostrará un error \[Figura 8\]. Además, si
intenta iniciar sesión cuando aún su sesión está abierta, se le debe
mostrar otro error \[Figura 9\]. Finalmente, si las credenciales son
correctas y no tenía su sesión abierta anteriormente, el sistema le
enviará instantáneamente al menú principal y podrá denotar que en el
lugar que se encontraba anteriormente el botón "Iniciar sesión" \[Figura
6\], ahora se encuentra el botón "Cerrar sesión" \[Figura 10\] que, tras
pulsarlo, cerrará la sesión del usuario con el que la inició.

![](/img/revision/image2.png)

Figura 7 -- Formulario inicio sesión

![](/img/revision/image7.png)

Figura 8 -- Error contraseña

![](/img/revision/image8.png)

Figura 9 -- Error ya iniciado

![](/img/revision/image17.png)

Figura 10 -- Botón cerrar sesión

### **CASO 3: SOLICITAR IMPRESIÓN**

En el menú principal \[Figura 1\], podrás solicitar la impresión de un
diseño específico, es decir, tú quieres que algún usuario imprima una
pieza que deseas y, para ello, le proporcionas un modelo .stl, que es un
archivo que muestra la pieza esperada en 3 dimensiones. Para ello, debes
pulsar en la parte central de la ventana sobre el botón "Solicitar
impresión" \[Figura 12\].

![](/img/revision/image20.png)

Figura 12: Botón solicitar impresión

Una vez pulsado el botón, se nos redirigirá a una nueva pantalla
\[Figura 13\] en la que podremos añadir los datos de nuestra solicitud
de impresión. En la parte izquierda de la ventana, podemos ver una
previsualización de la pieza proporcionada, pudiendo hacer zoom y girar
sobre la misma para comprobar que realmente se muestra el diseño que
esperamos que nos impriman. Por otro lado, en la parte derecha, debemos
cumplimentar todos los campos con datos adecuados, si no es así, el
sistema nos mostrará un error en aquellos atributos que sean incorrectos
\[Figura 14\]. Una vez que tenemos todos los datos, en la parte inferior
de la pantalla, veremos un resumen \[Figura 15\] que especificará el
precio, dimensiones...todos los datos para que el usuario sepa cómo va a
ser su producto. Estos datos cambiarán según el modelo proporcionado y
la calidad que quiera el cliente en su pieza, siendo el mínimo 12.10€.

![](/img/revision/image30.png)

Figura 13 - Formulario de solicitud de impresión

![](/img/revision/image33.png)

Figura 14 - Error en solicitud de impresión

![](/img/revision/image31.png)

Figura 15 - Resumen características de objeto a imprimir

Una vez que el cliente considere que el modelo va a ser fructífero y que
se ajusta en cuanto a tamaño, peso, calidad y precio, procede a pulsar
sobre el botón pagar y, automáticamente se le redirigirá a la pasarela
de pago *PayPal*, donde podrás realizar el pago y completar el encargo
del diseño. Para realizar este proceso, siga los pasos del apartado
[[Caso 4: Pagar con PayPal]].

Una vez finalizada la compra, volverá al servicio Shar3D y se mostrará
un resumen \[Figura 16\] con los detalles del pedido que ha realizado,

![](/img/revision/image43.png)

Figura 16 - Pantalla tras compra

La principal premisa de esta funcionalidad es que el modelo que hemos
solicitado que se nos imprima, sea impreso por un usuario de la
aplicación y este obtenga un beneficio a cambio de la impresión.

### **CASO 4: PAGAR CON PAYPAL**

Al estar probando el sistema, como no queremos que haya transacciones no
deseadas, usaremos las credenciales proporcionadas al inicio del
documento, que podéis usar para que el intercambio sea con dinero
ficticio. Les recuerdo las credenciales:

-   Correo: sb-k43ebi28280380@personal.example.com

-   Contraseña: nNU\<\<9Y%

Para llevar a cabo estos pagos en el servicio Shar3D, hacemos uso de una
pasarela de pago con PayPal. Lo primero que verás será una pantalla en
la cuál tendrás que poner el correo anterior \[Figura 17\] y una vez
pulsado sobre "Siguiente", le aparecerá el campo Contraseña \[Figura
18\] donde debe rellenar con la contraseña proporcionada para PayPal.
Una vez pulsado sobre "Iniciar sesión" le aparecerá una última vista
\[Figura 19\] para confirmar el pago, en ella tendrá que pulsar
directamente sobre "Continuar y revisar pedido" para finalizar el pago
ficticio y terminar la compra.

Figura 17: Correo
PayPal
![](/img/revision/image24.png)

![](/img/revision/image49.png)

Figura 18: Contraseña PayPal

> Figura 19: Confirmar
> PayPal![](/img/revision/image26.png)

### **CASO 5: VENDER PRODUCTO**

Una vez has iniciado sesión, en el menú principal \[Figura 1\], podrás
añadir un producto a la venta, tanto material, como diseño, pieza o
impresora. Para ello, tendrás que pulsar sobre el botón "Vender"
\[Figura 20\] ubicado en la esquina superior derecha de vuestra
pantalla. En el caso de intentar acceder a esta página sin haber
iniciado sesión, se le mostrará una alerta \[Figura 21\] y será
redirigido al menú
principal.![](/img/revision/image23.png)

Figura 20: Botón vender

Figura 21: Error
vender![](/img/revision/image6.png)

Una vez pulsado "Vender", se nos redireccionará hasta la vista de añadir
un producto \[Figura 22\], en la cuál vamos a poder añadir cualquier
tipo de herramienta relacionada con la impresión 3D. A la izquierda,
aparecerá la imagen que los usuarios del servicio van a ver de nuestro
producto, por defecto, aparece un cerdito, pero tendremos que subir una
foto en formato .jpg, .png o .jpeg, que sustituirá al cerdito y será
aquella que se mostrará luego en la web de Shar3D. Todos los campos del
formulario a rellenar son obligatorios, si alguno de ellos no es
rellenado o incumple con las restricciones establecidas, se mostrará un
mensaje de error para que los corrijan \[Figura 23\]. Si cumpliments
todos los campos de manera adecuada y pulsa sobre el botón "Añadir
producto" \[Figura 24\], el sistema guardará su producto para mostrarlo
en la web y le enviará una alerta \[Figura 25\] especificando que todo
ha ido bien y será redireccionado al menú principal.

![](/img/revision/image9.png)

Figura 22: Formulario añadir producto

Figura 23: Errores
formulario

![](/img/revision/image11.png)

![](/img/revision/image12.png)
Figura 24: Botón añadir
producto

![](/img/revision/image13.png)

Figura 25: Mensaje éxito

**CASO 6: DETALLES DE PRODUCTO**

Si usted quiere acceder a los detalles de cualquier producto de Shar3D,
como puede ser una pieza, un diseño, una impresora o material,
simplemente puede ver como en la página principal \[Figura 1\], hay
distintas secciones que muestran aquellos productos más destacados. Si
queremos acceder a los detalles de uno de ellos, básicamente pulsamos
sobre el producto y se abrirá una nueva ventana \[Figura 26\] en la cuál
podemos ver las características de este producto, desde la cantidad que
hay ahora mismo en stock, hasta el precio, el usuario que vende dicho
producto y el precio al que está disponible para comprar.

Si desea comprar uno de los productos del servicio, sea cual sea, pulse
sobre el botón "Añadir al carrito" \[Figura 27\] y se añadirá
directamente a su carrito para una futura compra.

![](/img/revision/image41.png)

Figura 26 - Detalle de producto

![](/img/revision/image22.png)

Figura 27 - Botón para añadir al carrito

### **CASO 7: DETALLES DE USUARIO**

Por el otro lado, en la pantalla principal \[Figura 1\], podemos ver una
sección sobre mejores artistas, en la cuál se muestran aquellos usuarios
con mejor valoración en Shar3D. Para poder acceder a los detalles de
dicho cliente, debemos pulsar sobre su foto y nos redireccionará a su
perfil \[Figura 28\], donde podremos ver su foto de perfil, su rol
dentro del sistema y todos sus datos relevantes. También podemos ver el
botón "Chat" \[Figura 29\], a través del cuál podremos comunicarnos con
el usuario en un futuro, pues esa funcionalidad aún no está
implementada.

![](/img/revision/image27.png)

Figura 28 - Detalle de Usuario

![](/img/revision/image21.png)

Figura 29 - Botón para el chat

### **CASO 8: CARRITO DE LA COMPRA**

Pasamos a la parte más importante para el negocio, el momento de pagar.
Para ello, en la esquina superior derecha del menú principal \[Figura
1\] hemos añadido un carrito \[Figura 30\] en el cuál se irán
almacenando los distintos productos que el cliente agregue para comprar.

![](/img/revision/image25.png)

Figura 30 - Botón de cesta

Considerando que ha añadido algunos productos, si pasamos con el ratón
por encima del icono, podremos ver un pequeño resumen \[Figura 31\] en
el cuál podemos ver los distintos productos, con sus respectivos precios
y el coste total. Si queremos quitar del carrito alguno de estos
productos, podremos pulsar sobre la cruz que se encuentra a la derecha
del nombre de cada uno de ellos.

![](/img/revision/image3.png)

Figura 31 - Overlay cesta

Pero si queremos ver realmente toda la funcionalidad que tiene el
carrito, debemos pulsar sobre el botón "Ver detalles", que nos
redireccionará a una nueva vista \[Figura 32\].

![](/img/revision/image1.png)

Figura 32 - Vista cesta

En esta vista, podemos modificar los productos de nuestro carrito. Por
cada producto, podemos ir añadiendo (con el botón "+" siempre que haya
en stock) y disminuyendo (con el botón "\--") unidades, además, podemos
eliminar un producto si ya no queremos comprarlo a través del símbolo de
la papelera \[Figura 33\]. Esta vista incluye un resumen del coste del
pedido, añadiendo los gastos de envío y, por último, se muestra un
formulario \[Figura 34\] en el cuál tenemos que adjuntar nuestros datos
personales para que la entrega sea satisfactoria. Una vez que estén
todos los datos rellenos, debemos pulsar el botón "Finalizar compra" que
nos permitirá pasar a la pasarela de pago vista anteriormente en el
apartado [[Caso 4: Pagar con
PayPal]](#_heading=h.xe1osuhs5eqe) y rellenando con los
mismos datos, el pago ficticio se llevará a cabo.

![](/img/revision/image5.png)

Figura 33 - Botón borrado de producto

![](/img/revision/image10.png)

Figura 34 - Formulario de datos de comprador

Una vez completado el pago, se le mostrará un resumen \[Figura 35\] con
los detalles del pedido y de la entrega, lo que confirmará que todo el
proceso se ha desarrollado correctamente.

![](/img/revision/image14.png)

Figura 35 - Vista detalles tras pago

### **CONSIDERACIONES**

Se ha de comentar que es posible que haya errores con el inicio de
sesión, puesto que hay veces que, al pasar un tiempo con la sesión
iniciada, pierdes los permisos a pesar de no haber hecho el logout. Esto
puede aparecer si, a la hora de intentar realizar alguna acción, le
aparece un error que no se ha especificado en esta guía, en ese caso,
cierra sesión y vuelve a iniciar para que todo funcione correctamente.
Si no es así, contacte con el equipo de desarrollo lo antes posible,
muchas gracias.

## **CONTENIDO 2º SPRINT**

Primero de todo, la landing page de SHAR3D se encuentra en la URL:

[[https://landing-page-shar3d.vercel.app/]](https://landing-page-shar3d.vercel.app/)
desde aquí puedes acceder a la web del sistema en funcionamiento
navegando hacia "Nuestros lanzamientos", pulsando sobre el frontend del Sprint 2, al final de la página
principal.

Si quiere directamente acceder a la web del sistema, sobre la cual se
realizarán las pruebas debe acceder a la URL:

[[https://ispp-s2.vercel.app/]](https://ispp-s2.vercel.app/)

El GitHub del equipo de trabajo se encuentra en la siguiente URL:

[[https://github.com/G12-ISPP/ISPP]](https://github.com/G12-ISPP/ISPP)

La herramienta para registrar las horas de cada uno de los miembros es
Clockify, para distinguir el trabajo de cada uno puede acceder a la URL:

[[https://app.clockify.me/shared/65d87eea756abe0bdf308a40]](https://app.clockify.me/shared/65d87eea756abe0bdf308a40)

Una vez tienen las distintas páginas, le proporcionaremos los datos
indispensables para que pueda acceder a la web y probar todo lo que
explicaremos posteriormente:

-   URL de la web: [[https://ispp-s1.vercel.app/]](https://ispp-s1.vercel.app/)

-   Credenciales administrador:

    -   Usuario: admin

    -   Contraseña: 4dm1n

-   Credenciales usuario:

    -   Usuario: user1

    -   Contraseña: us3r

-   Credenciales impresor:

    -   Usuario: user2

    -   Contraseña: us3r

-   Credenciales PayPal:

    -   Correo: sb-k43ebi28280380@personal.example.com

    -   Contraseña: nNU\<\<9Y%

En el caso de las credenciales de administrador, su uso va a ser
irrelevante para esta revisión debido a que no ofrece funcionalidad
distinta a la que de por sí tienen los usuarios, por lo tanto, no es
necesario acceder como administrador.

## **CASO 1: CHAT**

Una de las principales funcionalidades añadidas durante este sprint es el chat entre usuarios.
A partir de ahora, todos los clientes de Shar3D podrán comunicarse entre ellos una vez que inicien sesión.
Si queremos chatear con un usuario, podemos acceder a su perfil de usuario y pulsar 
sobre el botón chat \[Figura 36\], entonces, aparecerá una vista en la cuál podrá intercambiar
mensajes con dicho usuario \[Figura 37\].

![](/img/revision/image51.png)

Figura 36 - Botón chat en detalles de usuario

![](/img/revision/image52.png)

Figura 37 - Vista chat

Una vez que hemos hablado con algún que otro usuario, podemos acceder los distintos chats, 
a través del icono de mensajes \[Figura 38\], ubicado en la esquina superior derecha. Una vez
pulsado, podrá ver un menú desde el que puedes acceder a cada uno de los chats disponibles \[Figura 39\]

![](/img/revision/image50.png)
Figura 38 - Botón chat en menú

![](/img/revision/image53.png)
Figura 39 - Menú chats

## **CASO 2: LISTADO DE PRODUCTOS Y ARTISTAS**

Se han añadido listado para todos los productos disponibles en Shar3D, divididos en Diseños, 
Piezas, Impresoras, Materiales y también para artistas. Todos estos listados pueden ser accedidos
desde la barra de navegación del menú principal \[Figura 40\] y podrás ver un listado
como el siguiente \[Figura 41\]. En cada uno de los listados, podrás acceder a los detalles tanto
de productos como de artistas pulsando sobre la imagen. 

![](/img/revision/image54.png)
Figura 40 - Barra navegación

![](/img/revision/image55.png)
Figura 41 - Listado de materiales

## **CASO 3: APARTADO PARA ASIGNACIÓN DE IMPRESIONES**

Esta funcionalidad se ha realizado con la intención de que los impresores puedan escoger aquellas
impresiones que quieren realizar, por lo tanto, para acceder debe registrarse como impresor e inicar
sesión. Una vez hecho lo anterior, puede acceder a este apartado a partir de la barra de navegación,
en la sección "Modelos a imprimir" \[Figura 42\]. Una vez pulsado podrá ver aquellos modelos que están
esperando que alguien lo imprima. Si pincha sobre uno de ellos podrás asignartelo y recibirás un correo
con toda la información necesaria para que se pueda llevar a cabo la entrega del producto. Además, se
le adjuntará el modelo STL que debe imprimir.

![](/img/revision/image56.png)
Figura 42 - Modelos a imprimir

## **CASO 4: CONVERSIÓN STL**

Se ha añadido una funcionalidad para poder obtener archivos .stl a partir de otros como
.ply, .step, .obj, .vtk, .bmp y .dae. Esto permite unificar todos los archivos de la web
en el mismo formato. Para poder acceder a esta sección puede pulsar sobre el botón "Convertir
a STL" \[Figura 43\] del menú principal.
Al utilizar esta funcionalidad hay que tener en cuenta que por problemas tecnológicos, la conversión puede llegar a tardar hasta 3 minutos, esto se debe a que utilizamos plataformas gratuitas para desplegar nuestra aplicación y estas plataformas tienen ciertas limitaciones que hacen que esta funcionalidad sea bastante más lenta.

![](/img/revision/image57.png)
Figura 43 - Botón conversión STL

## **CASO 5: COMPRAR UN PLAN**

Si quiere unirse a algún plan de los disponibles en Shar3D puede acceder a través del botón
"Comprar plan" del menú principal \[Figura 44\] y verá los distintos planes y podrá seleccionar
el que desee.

![](/img/revision/image58.png)
Figura 44 - Botón comprar plan

## **CASO 6: PERFIL**

En este apartado se explicará los distintas acciones que se pueden realizar dentro del perfil de un usuario, tanto el nuestro propio como en el resto. En primer lugar, podemos acceder a nuestro perfil desde el botón "Ver perfil" \[Figura 45\]. Si queremos acceder al perfil de otro usuario,
con pulsar sobre él desde cualquier lugar en el que se referencie, como puede ser un producto o el lista de artistas, es suficiente.

![](/img/revision/image59.png)
Figura 45 - Botón ver perfil

Tanto en nuestro perfil como en los demás, podremos ver los productos que tiene publicados el usuario y las opiniones. En el de los demás, podremos
añadir opiniones, abrir un chat con ellos y empezar a seguirlo para poder ver su actividad en Shar3D, a partir de las publicaciones en la comunidad que veremos más adelante.

Respecto al nuestro, tenemos la posibilidad de editar tanto el propio perfil como nuestros productos, que lo explicaremos más adelante.


### 6.1 EDICIÓN PERFIL

Si hay algún cambio respecto a los datos con los que se registró, como puede ser correo, dirección e incluso foto de perfil, puede editar esa
información pulsando sobre el botón "Editar perfil" \[Figura 46\].

![](/img/revision/image60.png)
Figura 46 - Editar perfil

### 6.2 MIS PRODUCTOS

Para ver los productos que ha puesto a la venta el usuario, pulsando sobre el botón "Productos" \[Figura 47\] podrá ver una lista con todos
los disponibles.

![](/img/revision/image61.png)
Figura 47 - Botón productos

#### 6.2.1 EDICIÓN PRODUCTO

Respecto a lo anterior, si queremos editar alguno de nuestros productos, podemos acceder pinchando sobre él y pulsando sobre el botón "Editar
producto" \[Figura 48\], que nos enviará a un formulario desde el cuál se podrá modificar algunos de los datos del producto.

![](/img/revision/image62.png)
Figura 48 - Botón editar producto

### 6.3 OPINIONES

Volviendo a la vista del perfil, podremos ver que en la parte inferior se muestran las opiniones de cada usuario, en el caso de acceder
al perfil de un usuario distinto al nuestro, tendremos la posibilidad de añadir una opinión sobre él. Para ello, pulsando sobre el botón
"Añadir opinión" \[Figura 49\] se nos mostrará un formulario que, tras rellenarlo (Puntuación entre 1 y 5) \[Figura 50\] y pulsar sobre publicar opinión, se añadirá al perfil del usuario.

![](/img/revision/image63.png)
Figura 49 - Botón añadir opinión

![](/img/revision/image64.png)
Figura 50 - Añadir opinión

## **CASO 7: MIS PEDIDOS**

Podrá ver el histórico de los pedidos que ha realizado en la web a partir del botón "Mis pedidos" \[Figura 51\] siempre que hayas iniciado sesión. En el caso de que quiera comprobar el estado de alguno de los pedidos que ha realizado sin iniciar sesión, puede acceder a través del id del pedido que se le adjuntó en el correo de confirmación del mismo, pulsando en la parte inferior de la pantalla sobre "Seguimiento de pedidos" \[Figura 52\]

![](/img/revision/image65.png)
Figura 51 - Botón mis pedidos

![](/img/revision/image66.png)
Figura 52 - Seguimiento de pedidos


## **CASO 8: COMUNIDAD**

En esta sección podrá compartir y ver la actividad del resto de usuarios de Shar3D. Actualmente solo podrá consultar publicaciones de los usuarios a los que sigue en la web. Para ello, podras acceder desde la barra de navegación \[Figura 40\]. Una vez en el apartado comunidad, podrás añadir posts y ver los de tus amigos \[Figura 53\].

![](/img/revision/image67.png)
Figura 53 - Comunidad

## **CONSIDERACIONES**

Respecto al 1º Sprint, ha habido una mejora notable en cuanto al registro,
ya que se solicitó, como podemos ver en el feedback del 19 de marzo al grupo
Cocenfe NGO, https://knowledge-base-orpin.vercel.app/docs/Feedback/feedback-19-03-2024,
que el correo electrónico debía ser validado para poder completar el registro.
De esta manera, el registro se ha modificado respecto a la anterior entrega para que
se cumpla dicha propuesta. Además se ha añadido la posibilidad de añadir una foto
de perfil que podrá ver el resto de los usuarios de Shar3D y se ha cambiado el estilo \[Figura 54\].

![](/img/revision/image68.png)
Figura 54 - Registro



## **CONCLUSIONES**

Se ha realizado un documento bastante completo sobre cada uno de los
casos de uso, quizás un poco extenso debido a que hemos intentado que
quede bastante claro y no haya conflictos a la hora de usar la web, sin
embargo, consideramos que es una guía que puede permitir usar Shar3D a
cualquier tipo de usuario, aunque no tenga relación con la tecnología.

## **BIBLIOGRAFÍA**

> Intencionalmente vacío.

## **PROMPTS DE INTELIGENCIA ARTIFICIAL**

Intencionalmente vacío.
