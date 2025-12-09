La función main del código escribe para el usuario el menú de opciones que tiene para elegir, siendo estas: 
conversión de longitud, masa, temperatura o salir del programa. Leyendo posteriormente la elección del usuario, mediante los números 1, 2, 3, y 4; respectivamente. 
Y haciendo uso de la función switch case para ejecutar cada uno de los casos posibles; mandando a llamar a la función correspondiente, declaradas anteriormente, 
cada una contiene otro menú de funcionamiento similar que ejecuta la conversión solicitada mediante la relación matemática entre sus unidades.

La función “menuLongitud” se abre al seleccionar la primera opción, el código se va a conversiones de longitud donde nos despliega otro menú que nos da opciones 
de pasar de kilómetros a metros, de metros a centímetros, de centímetros a pulgadas, etc. y dependiendo de lo que eliges se hace alguna de esas conversiones. 

La función “menuMasa” se despliega como el segundo caso al ingresar el número dos como opción en el menú principal. 
Nos despliega nuevamente opciones para que el usuario pueda decidir el tipo de unidad de masa que quiere convertir, teniendo las opciones de: 
kilogramos a gramos; gramos a onzas; onzas a libras; o volver al menú principal. 
Volvemos a hacer uso de switch case para llevar a cabo la lectura de la cantidad de unidades a convertir y su operación correspondiente, para después imprimir la conversión para el usuario.

La función “menuTemperatura” se activa cuando el usuario selecciona la opción tres dentro del menú principal. 
Al ejecutarse, muestra un submenú con distintas alternativas para convertir entre escalas de temperatura. Las opciones disponibles incluyen: 
convertir de grados Celsius a Fahrenheit, de Fahrenheit a Celsius, de Celsius a Kelvin, o bien regresar al menú principal.

Dentro de esta función se utiliza nuevamente una estructura switch–case, la cual permite determinar qué tipo de conversión realizará el programa según la elección del usuario. 
Cada caso solicita al usuario ingresar un valor numérico en la unidad correspondiente (°C o °F), realiza la operación matemática necesaria para obtener la conversión y
finalmente muestra el resultado con el formato adecuado utilizando setprecision. En caso de que el usuario ingrese una opción inválida, se despliega un mensaje de error. 
El ciclo se repite hasta que el usuario decide regresar al menú principal seleccionando la opción cuatro.



Compilar con:

g++ conversor.cpp -o conversor
./conversor
