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



**EJERCICIO 3**

var numeroUno = 12;  
var numeroDos = -3;  
var numeroTres = 24;  

if (numeroUno < 0) {  
        console.log(numeroDos + numeroTres + " El número es negativo y se suman " + numeroDos + " y " + numeroTres);  
    } else {  
        console.log(numeroUno*numeroDos*numeroTres + "Es el resultado de multiplicar los tres números");  
    }  
    
    

**EJERCICIO 4**

var mes = prompt("¿En que mes estamos?");  
var dia = prompt("¿En que día estamos?");  
var precio = prompt("¿Cuanto vale el producto?");

var descuento = 25*precio/100;  
var precioDescuento = precio - descuento;  

if( mes === "Diciembre" || mes === "Enero" || mes === "Febrero") {  
	if (dia === "Viernes" || dia === "Sabado" || dia === "Domingo") {  
	console.log("No se aplica descuento, debes pagar " , precio);  
	} else {  
	console.log ("BINGO! Has acertado de mes y días. Debes pagar solamente " , precioDescuento);  
		}   
	}  
	else{  
		console.log("No se aplica descuento.. ven en invierno mejor!. Debes pagar " , precio );  
	};  

