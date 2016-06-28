**EJERCICIO 1**


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


**EJERCICIO 2**

var numeroUno = 22;  
var numeroDos = 48;  
var numeroTres = 34

if (numeroUno > numeroDos & numeroUno > numeroTres) {  
    console.log(numeroUno + " es mayor que " + numeroDos + " y " + numeroTres);  
} else if (numeroDos > numeroUno & numeroDos > numeroTres){  
    console.log(numeroDos + " es mayor que " + numeroUno + " y " + numeroTres);  
} else {  
    console.log("Número tres es mayor");  
}  



var numeroUno = 22;  
var numeroDos = 48;  
var numeroTres = 34;  

    console.info(numeroUno > numeroDos & numeroUno > numeroDos ? "Numero uno es mayor" : numeroDos > numeroUno & numeroDos > numeroTres ? "Numero Dos es mayor" : "Numero tres es mayor");
    


var numeroUno = 22;  
var numeroDos = 48;  
var numeroTres = 34;  
switch (true) {  
  case numeroUno > numeroDos & numeroUno > numeroTres:  
    console.log(numeroUno + " es mayor que " + numeroDos + " y" + numeroTres);  
    break;  
  case numeroDos > numeroUno & numeroDos > numeroTres:  
    console.log(numeroDos + " es mayor que " + numeroUno + " y" + numeroTres);  
    break;  
  default:  
    console.log(numeroTres + " es mayor que " + numeroUno + " y" + numeroDos);  
}  

