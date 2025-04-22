ERROR: El juego no funciona
DESCRIPCIÓN: Se identifico que el script no estaba cargado al cuerpo de la pagina web. 
SOLUCIÓN: Se debe cargar el script dentro del cuerpo de la pagina web.

ERROR: RandomNumber
DESCRIPCIÓN: El codigo para generar el numero aleatorio está mal, ademas de que el rango está definido hasta 10, no hasta 100 como indica la logica del negocio. 
SOLUCIÓN: Reconstruir el codigo para generar el numero y definir el rango hasta 100.

ERROR: Limite de intentos
DESCRIPCIÓN: El limite de intentos está establecido para 5 intentos, pero en la logica del negocio debe de ser hasta un maximo de 10 intentos.
SOLUCIÓN: Corregir el limite de ATTEMPS hasta 10.

ERROR: Rango permitido al usuario y tipo de dato ingresado.
DESCRIPCIÓN: Al momento de ingresar el valor por parte del usuario, el sistema permite ingresar letras, ademas de un rango mayor al establecido en la logica del negocio (0-100).
SOLUCIÓN: Crear una condicional la cual evalue si el valor ingresado por el usuario es un numero entero y si pertenece dentro del rango establecido (0-100), de no ser ningun caso deberá de mostrar un mensaje de alerta y no deberá de incrementar el contador de intentos (ATTEMPS).

ERROR: Resultados del juego
DESCRIPCIÓN: Los colores correspondientes segun la lofica del negocio al dar el resultado del juego son erroneos, deberá de mostrar en color verde cuando se gane y color rojo cuando se pierda por limite de intentos.
SOLUCIÓN: cambiar el color de cada caso.

ERROR: Mensaje de victoria o perdida
DESCRIPCION: El mensaje no es mostrado en pantalla cuando se gana o pierde en el juego. Esto se debe al fragmento de codigo que esta ubicado en la condicional de victoria y perdida.
SOLUCION: Eliminar el fragmento de codigo lowOrHi.textContent = '';

ERROR: Referencia de si el valor ingresado es mayor o menor.
DESCRIPCIÓN: No se muestra el mensaje de referencia.
SOLUCIÓN: Agregar el punto (.) al querySelector('.lowOrHi');