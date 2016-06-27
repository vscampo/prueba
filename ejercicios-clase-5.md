<!-- Ejercicio 1 -->


var numeroUno = 22;
var numeroDos = 48;


    if (numeroUno > numeroDos) {
        console.log(numeroUno + " es mayor que " + numeroDos);
    } else if (numeroDos > numeroUno){
        console.log(numeroDos + " es mayor que " + numeroUno);
    } else {
        console.log("Ambos son iguales");
    }


var numeroUno = 22;
var numeroDos = 48;

    console.info(numeroUno > numeroDos ? "Numero uno es mayor" : numeroDos > numeroUno ? "Numero Dos es mayor" : "Son iguales");
    
    

var numeroUno = 22;
var numeroDos = 48;
switch (true) {
  case numeroUno > numeroDos:
    console.log(numeroUno + " es mayor que " + numeroDos);
    break;
  case numeroDos > numeroUno:
    console.log(numeroDos + " es mayor que " + numeroUno);
    break;
  default:
    console.log("Ambos son iguales");
}

