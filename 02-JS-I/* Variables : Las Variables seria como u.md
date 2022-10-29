* Variables : Las Variables seria como una caja donde le asignamos un nombre, y adentro de esta se le puede agregar cosas, como un valor, un numero. Las cosas que agregamos dentro de la variable pueden ir cambiando mientras vamos programando.
Para crear una variable se escribe {var}, {espacio} y {el nombre de la variable} un ejemplo:
var hola = 1

 * Strings : Los Strings sirven para asignar cosas a forma de texto, por ejemplo la letra {a} es una..letra, pero no forma parte de un texto, pero si a esta letra le agregamos {''} se convierte en un string y la computadora lo lee como que forma parte de un texto y no como una ¨¨caja¨¨ {variable}
 Lo mismo con los numeros, 1 es 1 pero si le agregamos {''} se podria decir que forma parte del abecedario. 

 * Funciones (argumentos, `return`): Las Funciones, es como una maquina donde adrentro de esta, tiene una linea de codigo donde se le indica que debe de hacer, esta maquina le podemos poner nombre. Y cada vez que la llamamos por su nombre esta inicia su codigo que le creamos adentro. EJEMPLO:
 function hola(){
    console.log('hola');
 }
 A las funciones se les puede agregar un argumento, donde estan los parentesis podemos agragar una variable que despues en la linea de codigo que creamos esta se meta adentro y pueda ser manipulada-
 EJEMPLO: 
 function Adios(nombre) {
    console.log('Chau, ' + nombre);
}
El return: Cuando usamos este codigo no hace falta usar {console.log}, la funcion de este codigo es devolver el codigo que creamos en la funcion.

 * Declaraciones `if`: 
   function mayorque10(num){
      if // siginifa SI, osea si ocurre lo que nosotros le indicamos ejemplo//
      if(num > 10){   // SI {num} es mayor que 10 y cumple con esta condicion la computadora lo lee y utiliza el codigo que le asignamos con las llaves 
         return true;  // pero si num no es mayor que 10 este el codigo de recien no lo lee, y sigue hasta abajo de la linea de codigo que en este caso termina en return false(como el num no es mayor que 10 este en la consola nos tira es que falso; ejemplo; 1>10 no es verdaro y seria false)
      }
      return false
 }
 * Valores booleanos (`true`, `false`); los valores booleanos sirven para ver si el algo es verdero o falso (true, false) ejemplo:
 1>10 = false
 10>5 = true 