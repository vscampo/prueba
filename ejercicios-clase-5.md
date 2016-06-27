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
var casoUno = numeroUno > numeroDos;
var casoDos = numeroDos > numeroUno;

    console.info(casoUno ? "Numero uno es mayor" : casoDos ? "Numero Dos es mayor" : "Son iguales");

