**EJERCICIO 1 **

var imgs = document.getElementsByTagName("img");
var n = imgs.length;
for(i=0;i<n;i++){
	imgs[i].src = "http://placekitten.com/200/300";
}
