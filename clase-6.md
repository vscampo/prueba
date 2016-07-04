
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


**EJERCICIO 4**

console.log("Empieza la cuenta pares!");  

for (var control = 0; control <= 100; control+=2) {  
	console.log (control);  
}  
console.log("Aquí termina la cuenta");  



console.log("Empieza la cuenta pares!");  

var control = 0;  
while (control <= 100) {  
    console.log(control);  
    control+=2;  
};  
console.log("Aquí termina la cuenta");  



console.log("Empieza la cuenta pares!");  

var control = 0;  
do {  
   control+=2;  
   console.log(control);  
} while (control < 100);  
console.log("Aquí termina la cuenta");  




**EJERCICIO 5**

var numero = prompt("Dame un número:");  

console.log("Empieza la cuenta!");  

for (var control = 0; control <= 50;control++ ) {  
	if(numero % 2 !== 0) {  
	console.log(numero);  
	}  
	numero++;  
}  
console.log("Aquí termina la cuenta");  




var numero = prompt("Dame un número:");  
var control = 0;  

console.log("Empieza la cuenta atras!")  

while(control <= 50) {  
	if(numero % 2 !== 0) {  
	console.log(numero);  
	control++;  
	}   
	numero++;  
}  
console.log("Aquí termina la cuenta");  




var numero = prompt("Dame un número:");  
var control = 0;  

console.log("Empieza la cuenta atras!")  

do {  
   if(numero % 2 !== 0) {  
	console.log(numero);  
	control++;  
	}   
	numero++;  
} while (control <= 50);  
console.log("Aquí termina la cuenta");  




**EJERCICIO 6**

var numero = 48;  
var numeroOriginal = numero;  

        if (numero <= 50 && numero > 0){  

        var numeroRomano = "";  

            for(; numero > 0 ;){  

                if(numero === 50){  
                    numeroRomano = "L";  
                    numero = 0;  
                } else if (numero >= 40 && numero < 50){  
                    numeroRomano += "XL";  
                    numero -= 40;  
                } else if (numero >= 10 && numero < 40){  
                    numeroRomano += "X";  
                    numero -= 10;  
                } else if(numero === 9){  
                    numeroRomano += "IX";  
                    numero -= 9;  
                } else if(numero === 8){  
                    numeroRomano += "VIII";  
                    numero -= 8;  
                } else if (numero === 7){  
                    numeroRomano += "VII";  
                    numero -= 7;  
                } else if (numero === 6){  
                    numeroRomano += "VI";  
                    numero -= 6;  
                } else if (numero === 5) {  
                    numeroRomano += "V";  
                    numero -= 5;  
                } else if (numero === 4){  
                    numeroRomano += "IV";  
                    numero -= 4;                  
                } else if(numero <= 3 && numero > 0){  
                    numeroRomano += "I";  
                    numero -= 1;  
                }  

            }  

            console.info(numeroOriginal + " en números romanos es " + numeroRomano);  

        } else {  

            console.warn(numeroOriginal + "NO es un número valido (0-50)");  

        }  
        
        
        

var numero = 48;  
var numeroOriginal = numero;  

        if (numero <= 50 && numero > 0){  

        var numeroRomano = "";  

            do{  

                if(numero === 50){  
                    numeroRomano = "L";  
                    numero = 0;  
                } else if (numero >= 40 && numero < 50){  
                    numeroRomano += "XL";  
                    numero -= 40;  
                } else if (numero >= 10 && numero < 40){  
                    numeroRomano += "X";  
                    numero -= 10;  
                } else if(numero === 9){  
                    numeroRomano += "IX";  
                    numero -= 9;  
                } else if(numero === 8){  
                    numeroRomano += "VIII";  
                    numero -= 8;  
                } else if (numero === 7){  
                    numeroRomano += "VII";  
                    numero -= 7;  
                } else if (numero === 6){  
                    numeroRomano += "VI";  
                    numero -= 6;  
                } else if (numero === 5) {  
                    numeroRomano += "V";  
                    numero -= 5;  
                } else if (numero === 4){  
                    numeroRomano += "IV";  
                    numero -= 4;                  
                } else if(numero <= 3 && numero > 0){  
                    numeroRomano += "I";  
                    numero -= 1;  
                }  

            } while (numero > 0)  

            console.info(numeroOriginal + " en números romanos es " + numeroRomano);  

        } else {  

            console.warn(numeroOriginal + "NO es un número valido (0-50)");  

        }  
        
        
        
        
        
var numero = 48;  
var numeroOriginal = numero;  

        if (numero <= 50 && numero > 0){  

        var numeroRomano = "";  

            while (numero > 0){  

                if(numero === 50){  
                    numeroRomano = "L";  
                    numero = 0;  
                } else if (numero >= 40 && numero < 50){  
                    numeroRomano += "XL";  
                    numero -= 40;  
                } else if (numero >= 10 && numero < 40){  
                    numeroRomano += "X";  
                    numero -= 10;  
                } else if(numero === 9){  
                    numeroRomano += "IX";  
                    numero -= 9;  
                } else if(numero === 8){  
                    numeroRomano += "VIII";  
                    numero -= 8;  
                } else if (numero === 7){  
                    numeroRomano += "VII";  
                    numero -= 7;  
                } else if (numero === 6){  
                    numeroRomano += "VI";  
                    numero -= 6;  
                } else if (numero === 5) {  
                    numeroRomano += "V";  
                    numero -= 5;  
                } else if (numero === 4){  
                    numeroRomano += "IV";  
                    numero -= 4;                  
                } else if(numero <= 3 && numero > 0){  
                    numeroRomano += "I";  
                    numero -= 1;  
                }  

            }  

            console.info(numeroOriginal + " en números romanos es " + numeroRomano);  

        } else {  

            console.warn(numeroOriginal + "NO es un número valido (0-50)");  

        }  



