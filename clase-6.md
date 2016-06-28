
var clave = prompt("¿Cual es la clave?");


if (clave === "Fictizia mola mucho") {
console.log("¡Esa es la clave!");
} else {
	for (var i = 0; i < 3; i++) {
    prompt("¿Cual es la clave?")
	} 
	console.log("No tienes más intentos")
}





var clave = "Fictizia mola mucho";

var acierto = false;
var control = 0;

while (control < 3 && acierto===false ) {
	var secreto = prompt("¿Cual es la clave?");
	if(secreto===clave) {
		console.log("¡Esa es la clave!");
		break;
	} else {
		console.log("No es correcto");
	}
	control++
};

if(control >= 3) {
	console.log("Has acabado lo 3 intentos");
}
