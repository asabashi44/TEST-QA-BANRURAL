Vulnerabilidades
1. Al inspeccionar el código fuente se puede determinar que la variable que contiene el valor aleatorio es randomNumber el cual se podrá imprimir por medio de consola para hacer trampa.
2. El usuario puede controlar las variables de intentos modificando las asignaciones de las variables de intentos para obtener más oportunidades.
3. Para los valores que se deban mantener en secreto realizar peticiones al servidor por medio de jQuery o Ajax y evitar manipulaciones de valores.
4. Tokenizar cada petición al servidor para evitar inyecciones.

Pruebas
1. Ingresar un valor aleatorio para obtener un resultado en consola.
2. Ingresar valores menores a 1.
3. Ingresar valores mayores a 100.
4. Ingresar valores con decimales.
5. Ingresar caracteres alfanuméricos.
6. Agotar los intentos para obtener el mensaje de !!!Pérdistes!!!
7. Imprimir en consola el valor aleatorio actual para evaluar un caso de victoria.

Usabilidad
1. En el input de tipo text debería ser remplazo por un number para evitar recibir valores fuera de los requeridos.
2. Indicar en la etiqueta input atributos de step, max y min para que los exploradores guíen al usuario con la información a ingresar.
3. Agregar el atributo required para que el explorador obligue al usuario a ingresar un valor.

Funcionalidad
1. Utilizar un IDE con autocompletado para evitar escribir palabras reservadas de forma errónea.
2. Math.random() es una función que devuelve valores aleatorios, pero con decimales.
3. Incluir la funcion Math.floor para redondear la funcion Math.random.
4. Definir el mínimo y máximo de Math.random para evitar que cree valores fuera del rango establecido.
5. Agregar una validación para evitar que el usuario pierda intentos al momento de ingresar valores fuera del rango de 1 a 100.
6. En caso el usuario ingrese valores errados deberá terminarse la función sin aumentar el contador de intentos y preparar el input para un nuevo ingreso.
7. Con las validaciones del punto 6 y 7 se tendrá contemplado la excepción para los usuarios que no ingresen un valor.
8. La constante ATTEMPS está configurada en valor 5 cuando debería ser un valor de 10 para dar el total de oportunidades indicadas. 
9. Las validaciones están asignadas con tres signos de igual lo que provoca que la evaluación no sea correcta. Para este caso en particular debe utilizarse doble signo de igual para que sea considerada una evaluación numérica.
10. La evaluación de perdiste y ganaste están de forma incorrecta. Están evaluadas de informa inversa.
11. Tomar en cuenta que la validación correcta cuando el valor aleatorio es igual al que ingreso el usuario mostrar el mensaje de felicidades.
12. Al reiniciar el juego no se está generando un nuevo valor aleatorio. Siempre se mantiene el valor en 1.
13. Deberá ejecutarse una nueva asignación de valor aleatorio como al inicio del script.

Mejoras
1. Implementar expresiones regulares para evitar manipulación de los input.
2. Mostrar al usuario los intentos restantes para que el usuario tenga una mejor experiencia.
3. Integrar diseño responsivo para mejorar la experiencia del usuario. Mobile First.
4. utilizar un diseño llamativo para mejorar la calidad visual de la aplicación
