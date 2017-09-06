meta-json: {"viewport":"width=device-width, initial-scale=1.0, maximum-scale=1.0,\nuser-scalable=0","robots":"noindex,follow","title":"Notas en registros de ejemplar | Ayuda contextual de Janium","generator":["Divi v.2.2","WordPress 4.0.18"]}
robots: noindex,follow
title: Notas en registros de ejemplar | Ayuda contextual de Janium
viewport: width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0
Date:Nov 26, 2014


# Notas en registros de ejemplar

[%Date]

Para añadir información relacionada con el ejemplar que no pueda ser
registrada en ningún campo del formulario de edición, se pueden utilizar
las **notas de ítem**.

En principio, el contenido de estas notas no se despliega en el catálogo
al público; la única forma de mostrar esta información es yendo
nuevamente a la función *Notas del ítem*.

Para crear una nota de ítem es necesario lo siguiente:

-   Tener un registro bibliográfico desplegado con ejemplares asociados.
-   Dar clic en el cuadro selector situado junto al número de código de
    barras.
-   En la siguiente pantalla, *Administración de ítems*, y dentro de la
    sección *Notas del ítem*, dar clic en el botón ***Notas***.

![Acceso a la opción Notas del ítem](Creacion_notas_items.png)


-   A continuación, estando en *Creación de notas para ítems*, escribir
    en el campo de texto ***No. nota*** el número de nota que se desea
    crear (<span style="text-decoration: underline;">este número debe
    ser entero y no necesariamente debe iniciar con el número 1</span>)
    y hacer clic en el botón *Crear*.

![Introducción de número de nota](Creacion_notas_items2.png)

-   Después, escribir en el campo de texto ***Notas*** la información
    que desea registrarse para el ejemplar y hacer clic en el botón
    *Crear*. Además, en este punto, al poner la indicación **(OPAC)**
    antes del texto de la nota, convierte a esta en una nota que se
    puede desplegar en el catálogo al público. De esta forma, se
    obtienen <span style="text-decoration: underline;">notas
    públicas</span> (visibles desde el catálogo al público) y <span
    style="text-decoration: underline;">notas privadas</span> (sólo para
    el personal de la biblioteca).

![Introducción del texto de la nota](Creacion_notas_items3.png)

-   El sistema regresa a la pantalla de *Creación de notas para ítems*,
    mostrando en la parte inferior el texto escrito.

![Nota de ítem creada](Creacion_notas_items4.png)

### Gestión de material acompañante a ejemplares

El sistema Janium permite gestionar los materiales acompañantes de
acuerdo a las necesidades de la institución; para ello es necesario,
primeramente, responder si:

1.  ¿Es necesario que el material acompañante tenga su propio **código
    de barras**?

2.  ¿Es posible que el material acompañante **se preste de forma
    independiente** al material principal?

3.  ¿El material acompañante se tiene en una **ubicación diferente** al
    material principal?

4.  ¿Los materiales acompañantes **se inventarian de forma
    independiente** a los materiales principales?

Si se ha respondido afirmativamente a alguna de las preguntas, entonces
es necesario crear como ejemplar el material acompañante, asignándole un
código de barras. Esto permitirá gestionarlos de forma independiente
(inventario, préstamo, devolución, renovación, etc.).

Pero si a la biblioteca no le interesa gestionar de forma independiente
estos materiales, entonces no es necesario crearlos como ejemplares. En
este caso, lo que sí se debe hacer es **registrar los datos informativos
correspondientes** en el registro del ejemplar y en el registro
bibliográfico, de esta forma:

-   En el campo *Número de piezas* en el registro del ejemplar es
    necesario escribir de cuántas partes se compone el ejemplar (por
    ejemplo, si se trata de un libro con un disco compacto se tendría
    que escribir el número 2). Esto hará que al registrar la devolución
    del material el sistema informe al operador que se deben recibir dos
    piezas.

[<img src="Material_acompa1.png" alt="Material_acompa1" width="966" height="843">](Material_acompa1.png)

-   Crear una **nota pública** en el registro del ejemplar mencionando
    las piezas que conforman el mismo. Esto permitirá al usuario saber
    que el ejemplar de su interés tiene un material complementario.

[<img src="Material_acompa2.png" alt="Material_acompa2"  width="736" height="242">](Material_acompa2.png)

[<img src="Material_acompa3.png" alt="Material_acompa3" width="992" height="275">](Material_acompa3.png)

-   Escribir la información del material complementario en el **campo
    300**, **subcampo e** del formato MARC21 Bibliográfico.

[<img src="Material_acompa4.png" alt="Material_acompa4"  width="695" height="74">](Material_acompa4.png)


