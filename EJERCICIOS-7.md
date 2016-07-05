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

var fecha = dia.toDateString() + "/" + mes.toDateString() + "/" + year.toDateString();

if( dia <= 31 && dia > 0 && mes <= 12 & mes > 0 && year > 0) {
	console.log("La fecha es correcta");
	switch (mes) {
		case 1:
			fechaEscrito = dia.toDateString() + " de Enero de " + year.toDateString();
		case 2:
			fechaEscrito = dia.toDateString() + " de Febrero de " + year.toDateString();
		case 3:
			fechaEscrito = dia.toDateString() + " de Marzo de " + year.toDateString();
		case 4:
			fechaEscrito = dia.toDateString() + " de Abril de " + year.toDateString();
		case 5:
			fechaEscrito = dia.toDateString() + " de Mayo de " + year.toDateString();
		case 6:
			fechaEscrito = dia.toDateString() + " de Junio de " + year.toDateString();
		case 7:
			fechaEscrito = dia.toDateString() + " de Julio de " + year.toDateString();
		case 8:
			fechaEscrito = dia.toDateString() + " de Agosto de " + year.toDateString();
		case 9:
			fechaEscrito = dia.toDateString() + " de Septiembre de " + year.toDateString();
		case 10:
			fechaEscrito = dia.toDateString() + " de Octubre de " + year.toDateString();
		case 11:
			fechaEscrito = dia.toDateString() + " de Noviembre de " + year.toDateString();
		case 12:
			fechaEscrito = dia.toDateString() + " de Diciembre de " + year.toDateString();
	
	}

	console.log("La fecha en otro formato es " , fechaEscrito)

} else {
	console.log(" ERROR!!!")
}

