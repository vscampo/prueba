**EJERCICIO 1 **


var resultado = Math.floor(Math.random() * (3 - 1)) + 1;  

        if (resultado === 1){  
            console.info("Cara");  
        } else {  
            console.info("Cruz");  
        }  








var dia = prompt("Introduce un día");  
var mes = prompt("Introduce un mes");  
var year = prompt("Introduce un año");  

var fecha = dia + "/" + mes + "/" + year;  
var fechaEscrito = dia + "/" + mes + "/" + year;  

if( dia <= 31 && dia > 0 && mes <= 12 & mes > 0 && year > 0) {  
	console.log("La fecha es correcta ",fecha);  
	switch (mes) {  
		case 1:   
			fechaEscrito = dia + " de Enero de " + year;  
			break;  
		case 2:   
			fechaEscrito = dia + " de Febrero de " + year;  
			break;  
		case 3:  
			fechaEscrito = dia + " de Marzo de " + year;  
			break;  
		case 4:  
			fechaEscrito = dia + " de Abril de " + year;  
			break;  
		case 5:  
			fechaEscrito = dia + " de Mayo de " + year;  
			break;  
		case 6:  
			fechaEscrito = dia + " de Junio de " + year;  
			break;  
		case 7:  
			fechaEscrito = dia + " de Julio de " + year;  
			break;  
		case 8:  
			fechaEscrito = dia + " de Agosto de " + year;  
			break;  
		case 9:  
			fechaEscrito = dia + " de Septiembre de " + year;  
			break;  
		case 10:  
			fechaEscrito = dia + " de Octubre de " + year;  
			break;  
		case 11:  
			fechaEscrito = dia + " de Noviembre de " + year;  
			break;  
		case 12:  
			fechaEscrito = dia + " de Diciembre de " + year;  
			break;  

	}  

	console.log("La fecha en otro formato es " , fechaEscrito);  
	} else {   
		console.log(" ERROR!!!")   
		}  
