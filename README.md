CREAR - ALMACENA - ELIMINA
Crea una lista de tareas (todo list) usando React:

Importamos React y el hook useState de React.

Importamos un archivo de estilos llamado "Home.css" desde el directorio "../src".

Definimos un componente funcional llamado Home.

Usamos el hook useState para definir dos estados: input para almacenar el valor del input y guardarlist para almacenar la lista de tareas.

Creamos una función enter que se ejecuta cuando se presiona la tecla "Enter" en el input. Esta función agrega el valor del input actual a la lista de tareas y luego limpia el input.

Dentro del retorno del componente, creamos un input donde los usuarios pueden ingresar nuevas tareas. Este input tiene un event listener para detectar cuando se presiona la tecla "Enter" (onKeyUp={enter}).

Renderizamos las tareas guardadas en la lista usando el método map() en el array guardarlist. Por cada tarea, creamos un <div> con la clase "list" y mostramos el texto de la tarea en un <p>. También creamos un botón de eliminar ("X") que, al hacer clic, filtra las tareas para eliminar la tarea correspondiente al índice actual.

Exportamos el componente Home al final del archivo.


![image](https://github.com/JhojanBinary/Todo-Lis-with-React/assets/102551448/c4246649-dc74-423e-bc2f-a7133f4023d0)


![image](https://github.com/JhojanBinary/Todo-Lis-with-React/assets/102551448/2f79d124-777a-45e3-8342-7976e07e8e72)
