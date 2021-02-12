# ![alt text](https://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=breathecode,32)  HTML5 Form Validations

Después de crear el HTML y el CSS para este formulario, debemos asegurarnos de que evite que el usuario envíe un formulario con la información o el formato incorrectos. En el desarrollo web, lo llamamos: Validación de formularios. Echa un ojo a la [documentación oficial](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation).

Para evitar que se envíe un formulario, tenemos que escuchar el evento "enviar" que se activa con el formulario cuando el usuario presiona: la tecla Intro / Retorno o el botón Enviar.

Si quieres saber más sobre como prevenir los eventos: [https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s](https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s)

![Form Validations Preview](https://projects.breatheco.de/json?slug=html5-form-validations&preview)

## Instrucciones

Tras que la usuaria presione el botón de submit:
1. Asegúrate de detener el flujo del envío utilizando `preventDefault ()`, [aquí hay un poco más sobre preventDefault ()](https://www.youtube.com/watch?v=3SNyh57XSIA).
2. Después de evitar el envío, asegúrese de que todos los valores de entrada sean correctos y tengan el formato correcto.
3. Si hay una o más entradas con un valor no válido, muestre un error claro en la parte superior del formulario con un mensaje muy explícito sobre lo que sucedió.
4. Cambie el color de fondo de las entradas relevantes (las que tienen datos incorrectos).

## ¿Qué hacer si estás atascado?

¡No te sientas frustrado y pide ayuda! Después de probarte por tu cuenta durante 20 minutos, es hora de dejar de trabajar y pedir ayuda.

## 🤠 ¿Te sientes confiado?

Este requerimiento adicional no es necesario para completar el proyecto:

`+5` Haz que los errores del formulario se visualizen arriba de cada input en lugar de mostrarlos en la parte de arriba del formulario. Si el error esta en el correo electronico entonces el mensaje de error deberia aparecer justo arriba del input para correo electronico, de esa forma el usuario entenderá más rápidamente donde esta el problema.
