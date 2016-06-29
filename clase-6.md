
**Ejercicio 1**

var clave = "Fictizia mola mucho";  
        var acierto = false;  
        
        for (var control = 0; control < 3 & acierto === false; control++) {  

            var secreto = prompt("¿Cual es la clave?");  

            if (secreto === clave) {  
                acierto = true;  
                console.info(secreto, "¡Esa es la clave!");   
            } else {  
                console.warn(secreto, " No es correcto.");  
            }  
        };  


        if(control >= 3){  
            console.warn("Has acabado lo 3 intentos");  
        }  

	





var clave = "Fictizia mola mucho";  
var control = 0;  

while (control < 3 ) {  
	var secreto = prompt("¿Cual es la clave?");  
	if(secreto===clave) {  
		console.log("¡Esa es la clave!");  
		break;  
	} else {  
		console.log("No es correcto");  
	}  
	control++  
};  

if(control > 3) {  
	console.log("Has acabado lo 3 intentos");  
}  




var clave = "Fictizia mola mucho";   

var acierto = false;   
var control = 0;   

var i = 0;  
do {  
   var secreto = prompt("¿Cual es la clave?");  
   if(secreto===clave) {  
   		acierto = true;  
		console.log("¡Esa es la clave!");  
		break;  
	} else {  
		console.log("No es correcto");  
	}  
	control++  
	} while (control < 3 || acierto===false);  

if(control > 3) {  
	console.log("Has acabado lo 3 intentos");  
}  

