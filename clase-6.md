
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



**EJERCICIO 2**

console.log("Empieza la cuenta!");  

for (var control = 1; control <= 100; control++) {  
	console.log (control);  
}  
console.log("Aquí termina la cuenta");  



console.log("Empieza la cuenta!");  

var control = 1;  
while (control <= 100) {  
    console.log(control);  
    control++;  
};  
console.log("Aquí termina la cuenta");  



console.log("Empieza la cuenta!");  

var control = 1;  
do {  
   control++;  
   console.log(control);  
} while (control < 100);  
console.log("Aquí termina la cuenta");  


**EJERCICIO 3**

console.log("Empieza la cuenta atras!");  

for (var control = 100; control >= 0 ; control--) {  
	console.log (control);  
}
console.log("Aquí termina la cuenta atras");  




console.log("Empieza la cuenta!");  

var control = 100;  
while (control >= 0) {  
    console.log(control);  
    control--;  
};
console.log("Aquí termina la cuenta");  




console.log("Empieza la cuenta!");  

var control = 101;  
do {  
   control--;  
   console.log(control);  
} while (control >= 1);  
console.log("Aquí termina la cuenta");  

