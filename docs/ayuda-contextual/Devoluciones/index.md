# Devoluciones

Estas acciones consisten en registrar la entrega en la biblioteca de un material prestado. Cuando se registra la devolución de dicho material antes de su fecha y hora de vencimiento _no se genera ninguna sanción_ (monetaria o administrativa) al usuario.

### Pantalla

La pantalla de Devolución se compone de tres secciones:

- **Información sobre el usuario**, que muestra lo siguiente:

    - Número de cuenta y nombre completo del usuario.
    - Notas informativas asociadas al usuario.

- **Campo de código de barras y préstamo en sala**, que muestra lo siguiente:

    - Campo de texto para escribir el código de barras.
    - Cuadro de selección para préstamo en sala.

- **Lista de material devuelto en la sesión activa**, que muestra lo siguiente:

    - Código de barras y biblioteca del ejemplar.
    - Clasificación, título y autor.
    - Número de cuenta del usuario, biblioteca del usuario y perfil.
    - Fecha y hora de préstamo.
    - Fecha y hora de vencimiento.
    - Fecha y hora de devolución.
    - Número de cuenta y biblioteca del operador de Circulación responsable del préstamo.
    - Número de cuenta y biblioteca del operador de Circulación responsable de la devolución.
    - Renovaciones efectuadas.

- **Historial de devoluciones de un material:** que puede ser consultado introduciendo el código de barras del ítem.

![](Pantalla_devolucion.png)

![](Pantalla_devolucion2.png)

### Procedimiento de devolución

- Hacer clic sobre la opción **Devolución** de la barra de herramientas del módulo.

![](Opcion_devolucion.png)

- Escribir el _número de código de barras del material_ en el campo de texto de la sección destinada para ello y hacer clic en el botón **Aceptar**.

![](Entrada_codigo_barras2.png)

- Al llevar a cabo la acción anterior, se despliegan los datos del usuario que tenía vinculado el material en préstamo y la información del registro de devolución.

![](Registro_devolucion.png)

### Devolución de un préstamo vencido

Cuando se devuelve un material cuyo período de préstamo ha expirado, el sistema avisa de tal situación y, además, ejecuta la _multa monetaria_ o _suspensión administrativa_ correspondiente dependiendo de las **políticas de circulación** aplicadas por la institución.

El posible mensaje de alerta es el siguiente:

> Por favor, tenga en cuenta que el usuario ha sido multado por retraso
> en la devolución del material.

### Devolución de un material apartado / reservado

Un usuario puede solicitar el apartado / reserva de un material que se encuentre **Prestado**. Esto significa que al registrar la devolución del material, este queda reservado para el usuario solicitante siguiente _evitando que otros usuarios lo puedan pedir en préstamo_, durante el tiempo que la institución haya definido para estos casos. Además, el sistema avisa de la mencionada circunstancia.

El posible mensaje de alerta es el siguiente:

> Por favor, tenga en cuenta que el material fue apartado por el
> usuario: 1234