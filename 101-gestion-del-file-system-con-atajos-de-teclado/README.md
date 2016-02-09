# Gestión del File System con atajos de teclado

## Preliminares: diferentes tipos de teclas

Las teclas que componen un [teclado de ordenaror](https://en.wikipedia.org/wiki/Keyboard_layout) se dividen en varias categorias:

![Keyboard Layout](https://upload.wikimedia.org/wikipedia/commons/9/9c/ISO_keyboard_%28105%29_QWERTY_UK.svg)

Es importante saber que los **modificadores** no tienen efecto al ser presionados solos: esto es util a la hora de utilizar atajos compuestos por varios modificadores (e.g. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd>), porque podemos ir presionandolos antes de darle a la tecla alfanumerica.

## Preliminares: el mantra del teclado

Repetir costantemente dentro de uno mismo:

> El ratón es mi enemigo.

![Tom chasing Jerry](https://upload.wikimedia.org/wikipedia/en/7/74/Tom_and_Jerry_Chuck_Jones.jpg)

Mover las manos desde el teclado al ratón **hace perder mucho tiempo**, al cual hay que sumar el tiempo necesario para localizar los elementos interesados en la pantalla (cuanto más pequeños, más dificil obviamente).

En contextos en los cuales no tenemos control es necesario usar el mismo, véase visitar _links_ al interior de una pagina web, cuya extructura es desconocida y no es posible navegar con teclado unicamente.

## Preliminares: el File System

Por **File System** se entiende la manera que el sistema operativo utiliza para guardar datos en el disco. Sin entrar en detalles tecnicos, todos los sistemas utilizan una estructura gerargica de _carpetas_ y _archivos_.

![Windows File Explorer](http://media.askvg.com/articles/images5/Windows_8_1_This_PC_Explorer.png)

Cada carpeta tiene una referencia a su carpeta madre, y puede contener una lista arbitraria de carpetas y archivos (textos, imagenes, canciones, videos, aplicationes, enlaces...).

## Preliminares: atajos de teclado globales de Windows

El sistema operativo Windows tiene varios [atajos de teclado](https://es.wikipedia.org/wiki/Atajo_de_teclado) comunes, disponibles desde las primeras versiones (Windows 95 inclusive).

Los que vamos a necesitar más a menudo son los siguientes:

- <kbd>Win</kbd> + <kbd>D</kbd>: enseña [Escritorio](https://en.wikipedia.org/wiki/Desktop_metaphor);
- <kbd>Win</kbd> + <kbd>E</kbd>: abre un nuevo File Explorer;
- <kbd>Ctrl</kbd> + <kbd>W</kbd>: cierra ventana corriente;
- <kbd>Alt</kbd> + <kbd>F4</kbd>: cierra aplication corriente (todas sus ventanas);
- <kbd>Alt</kbd> + <kbd>Tab</kbd>: navegar a traves de las aplicaciones abiertas.

No incluyo los quizás ya conocidos _copiar_ (<kbd>Ctrl</kbd> + <kbd>C</kbd>), _pegar_ (<kbd>Ctrl</kbd> + <kbd>V</kbd>), _cortar_ (<kbd>Ctrl</kbd> + <kbd>X</kbd>), _anular_ (<kbd>Ctrl</kbd> + <kbd>U</kbd>), porqué serán revisados en el apartado oportuno.

---

## Gestión de carpetas

Vamos a ver ahora como crear, borrar y navegar a traves de las carpetas del sistema, posiblemente con el solo teclado.

### Creacion de carpetas

1. situemonos en el Escritorio (<kbd>Win</kbd> + <kbd>D</kbd>);
2. creemos una **nueva carpeta** con <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd>;
3. aparecerá ahora una nueva carpeta amarilla, y tendremos la posibilidad de darle un nombre. Llamemosla **Informática**;
4. para abrír sus contenidos, es suficiente apretár <kbd>Enter</kbd>. Veremos ahora un _File Explorer_ situado en la carpeta recién creada.

Muy bien! Ahora podemos repetir el proceso para crear una nueva carpeta dentro de `Informatica`, llamada **prueba**: es suficiente seguir los pasos 2 y 3.

Si ahora le damos al <kbd>Enter</kbd>, el Explorer bajará de un nivel y entrará en `prueba`. Si ahora le damos al <kbd>Backspace </kbd> (<kbd>⌫</kbd>), volveremos a la carpeta madre.

### Renombrar carpetas

Es suficiente darle al <kbd>F2</kbd>, y será posible cambiar de nombre a la carpeta selecionada. Llamemosla **prueba 2** por ejemplo.

### Borrar carpetas

El botón <kbd>Del</kbd> (Delete) es nuestro amigo. Una ventana de confirmación nos preguntará si somos ciertos de enviar la carpeta a la _papelera_, nosotros contestamos que sí.

---

## Bonus: atajos para web browers!

Toda información se puede buscar e incontrar en Internet, inclusida toda la presente en este documento! Conocér los atajos basilares de nuestro _web browser_ favorito nos convertirá en [power users](https://en.wikipedia.org/wiki/Power_user), o más simplemente nos hará ahorrar un montón de tiempo a la hora de cumplír tareas que repetimos decenas/cientos de veces al dia.

No vamos a revisar todos ahora, sino solo los de primera utilidad:

- <kbd>Ctrl</kbd> + <kbd>L</kbd>: lleva a la barra de dirección (Address <strong>L</strong>ine). Desde allí podemos digitar una nueva dirección, o copiár la actual para pegarla en otro contexto;
- <kbd>Espacio</kbd>: navega la pagina hacia abajo;
- <kbd>Shift</kbd> + <kbd>Espacio</kbd>: navega la pagina hacia arriba;
- <kbd>Ctrl</kbd> + <kbd>T</kbd>: abre una nueva pestaña;
- <kbd>Ctrl</kbd> + <kbd>W</kbd>: cierra la pestaña corriente.

Por curiosidad personal, comparar el tiempo medio necesario para cerrár una pestaña con <kbd>Ctrl</kbd> + <kbd>W</kbd>, con el necesario a través de hacer click en la minuscula cruz situada al lado del titulo de la misma. Repetir con 10 o 20 pestañas abiertas!
