# Tarea #6
 
## Integrantes 
Leidy Dahiana Osorio Ocampo
Catalina palacios 

## Ejercicio 1

``` javascript
var nombre = prompt("Ingresar Nombre");
console.log("Ahora estas en la matriz "+ nombre);
```
![Alt text](./img/1.png "Title");

## Ejercicio 2

``` javascript
var numerod = parseFloat(prompt("Ingresar Numero Decimal"));
var numeroe = parseFloat(prompt("Ingresar Numero Entero"));
var suma= numerod+numeroe;
console.log("La suma es: "+ suma);
```
![Alt text](./img/2.png?raw=true "Title");

## Ejercicio 3

``` javascript
var numeroUno = parseFloat(prompt("Ingresar Numero Uno"));
console.log("Numero uno: "+ numeroUno);
var numeroDos = parseFloat(prompt("Ingresar Numero Dos"));
console.log("Numero dos: "+ numeroDos);
var suma= numeroUno+numeroDos;
console.log("Suma: "+ suma);
var numeroTres = parseFloat(prompt("Ingresar Numero Tres"));
console.log("Numero Tres: "+ numeroTres);
var mult= suma*numeroTres;
console.log("Multiplicacion: "+ mult);
```
![Alt text](./img/3.png "Title");

## Ejercicio 4

``` javascript
var numeroKi = parseFloat(prompt("Ingresar El numero de Kilometros recorridos por la motocicleta"));
var combustible = parseFloat(prompt("Ingresar Combustible gastado"));
var consumo= numeroKi/combustible;
console.log("El consumo por kilometros es de "+ consumo);
```
![Alt text](./img/4.png "Title");

## Ejercicio 5

``` javascript
var fahrenheit = parseFloat(prompt("Ingresar temperatura Fahrenheit"));
var conversion= (5/9)*(fahrenheit-32);
console.log("Fahrenheit "+ fahrenheit +"  en celcius son:  "+ conversion);
```
![Alt text](./img/5.png "Title");

## Ejercicio 6

``` javascript
var numeroUno = parseFloat(prompt("Ingresar Numero Uno"));
var numeroDos = parseFloat(prompt("Ingresar Numero Dos"));
var numeroTres = parseFloat(prompt("Ingresar Numero Tres"));
var promedio= (numeroUno+numeroDos+numeroTres)/3;
console.log("El promedio de Numero 1:"+ numeroUno + " Numero 2:"+ numeroDos+ " Numero 3:" +numeroTres+ " es:" +promedio );
```
![Alt text](./img/6.png "Title");

## Ejercicio 7

``` javascript
var numeroUno = parseFloat(prompt("Ingresar Numero Uno"));
var desc= numeroUno-(numeroUno*15)/100;
console.log("Descontando el 15% queda: "+desc );
```
![Alt text](./img/7.png "Title");

## Ejercicio 8

``` javascript
var palabraUno = prompt("Ingresar primera palabra");
var palabraDos = prompt("Ingresar Segunda palabra");
console.log( palabraUno+" "+palabraDos );
```
![Alt text](./img/8.png "Title");

## Ejercicio 9

``` javascript
var tex=prompt("ingrese un texto");
console.log("Del texto "+tex+" La primer letra es: " + tex.charAt(0));
var num =prompt("ingrese un numero entre 0 y "+tex.length);
console.log( "resultado del numero"+num+" es: "+ tex.charAt(num));
```
![Alt text](./img/9.png "Title");

## Ejercicio 9

``` javascript
var tex=prompt("ingrese un texto");
console.log("Del texto "+tex+" La primer letra es: " + tex.charAt(0));
var num =prompt("ingrese un numero entre 0 y "+tex.length);
console.log( "resultado del numero"+num+" es: "+ tex.charAt(num));
```
![Alt text](./img/9.png "Title");

## Ejercicio 10

``` javascript
var show = parseInt(prompt("Ingrese el numero de Shows"));
console.log("Numero de shows: "+show)
if(show > 3)
    {
        console.log(true);
    }
else
{
      console.log(false);
}
```
![Alt text](./img/10.png "Title");

## Ejercicio 11

``` javascript
var num = parseInt(prompt("Ingresar fecha"));
var texto = num.toString()
var date = texto.substr(0,2) + "/" + texto.substr(2,2) + "/" + texto.substr(4,4)
console.log(date)
```
![Alt text](./img/11.png "Title");

## Ejercicio 12

``` javascript
var par = parseInt(prompt("Ingrese un Numero"));
console.log("Numero ingresado es "+par)
if(par %2 == 0)
{
    console.log(true);        
}
else
{
    console.log(false);
}
```
![Alt text](./img/12.png "Title");

## Ejercicio 13

``` javascript
var edad=prompt("ingrese la edad");
var articulo=+prompt("ingrese cantidad de articulos");
if (edad>18 && articulo>1){
	console.log("true"+ " Edad "+edad +("numero de articulos "+articulo))

}
else {
	console.log("false"+ " Edad "+ edad +(" numero de articulos "+articulo))
}
```
![Alt text](./img/13.png "Title");

## Ejercicio 14

``` javascript
var texto = prompt("Ingrese un texto");
console.log("texto ingresado: "+texto  );
if(texto.length %2 == 1) 
{
    console.log(true)
}
else
{
    console.log(false)
}
```
![Alt text](./img/14.png "Title");

## Ejercicio 15

``` javascript
var pal1 = prompt("Ingrese la Palabra 1");
console.log(pal1);
var pal2= prompt("Ingrese la Palabra 2");
console.log(pal2);
if(pal1.length < pal2.length)
{
    console.log(true)
}
else
{
    console.log(false)
}
```
![Alt text](./img/15.png "Title");

## Ejercicio 16

``` javascript
var nombre1 = prompt("Ingrese Primer Nombre");
console.log(nombre1);
var nombre2 = prompt("Ingrese segundo Nombre");
console.log(nombre2);
if(nombre1.charAt(0).toLowerCase() == nombre2.charAt(0).toLowerCase())
{
    console.log(true);
}
else if(nombre1.charAt((nombre1.length -1)).toLowerCase() == nombre2.charAt((nombre2.length -1)).toLowerCase())
{
    console.log(true);
}
else
{
    console.log(false);
} 
```
![Alt text](./img/16.png "Title");

## Ejercicio 17

``` javascript
var num1 = parseInt(prompt("Ingrese un Numero"));
console.log(num1);
if(num1<0)
{
    num1 = num1 * (-1);
    console.log("valor Absoluto "+num1)
}
else
{
    console.log("valor Absoluto "+num1)
}
```
![Alt text](./img/17.png "Title");

## Ejercicio 18

``` javascript
var numero1 = +parseFloat(prompt("ingrese el primer numero"));
console.log(numero1);
var numero2 = +parseFloat(prompt("ingrese el primer numero"));
console.log(numero2);

if(numero1 > numero2){
	console.log("el valor mas grande es "+ numero1)
}
else{
	console.log("el valor mas grande es "+ numero2)
}
```
![Alt text](./img/18.png "Title");

## Ejercicio 19

``` javascript
var letra = prompt("ingrese una letra")
console.log(letra)

if(letra.legenth>1){
    console.log("se ingreso mas de un caracter")
}
else if (letra == 'A' || letra == 'E' || letra == 'I' || letra == 'O' || letra=='U'){
	console.log("es vocal")
}
else{
	console.log("no es vocal")
}
```
![Alt text](./img/19.png "Title");

## Ejercicio 20

``` javascript
var numero1 = parseInt(prompt("Ingrese Primer Numero"));
var numero2 = parseInt(prompt("Ingrese Segundo Numero"));
var numero3 = parseInt(prompt("Ingrese Tercer Numero"));
console.log("numerosingresados son: "+numero1+","+numero2+" y "+numero3);

if(numero1 < numero2 && numero1 < numero3) {
    console.log("El numero menor es: " + numero1);
}
if (numero2 < numero1 && numero2 < numero3) {
    console.log("El numero menor es: " + numero2);
}
if(numero3 < numero1 && numero3 < numero2) {
    console.log("El numero menor es: " + numero3);
}
```
![Alt text](img/20.png "Title");