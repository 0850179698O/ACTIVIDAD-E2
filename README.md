# Programas en C++ de TORRES JENNIFFER
### Informacion de autor 
`Autor:TORRES JENNIFFER`
### Correo electronico
`Correo:jenniffer.torres.ayovi@utelvt.edu.`
### Link de la actividad B1
`https://youtu.be/Qynm8VSVHX0`

## Programas
### Compara dos numeros
#### Descripcion del problema 
```
comparamos los valores de dos números, para determinar cuál número es mayor o igual.
```
#### Funcionalidad
```
Para comprobar si un valor numérico es mayor que otro, usamos el símbolo “>”, como se ve en este ejemplo. Para ver si dos valores son iguales, usaremos dos símbolos de “igual”.
```
#### Salidad
```
if(jt_x==jt_y) //si son iguales
if(jt_x>jt_y)  //si es mayor
```
### Suma de varios numeros
#### Descripcion del problema 
```
La suma es la operación matemática que resulta al reunir en una sola varias cantidades. También se conoce la suma como adición. Las cantidades que se suman se llaman sumandos y el resultado suma o total. el cual se lee "más".
```
#### Funcionalidad
```
Comprobar si el programa muestre la suma total.
#### Salidad
```
#### Salida
```
jt_suma=jt_a+jt_b;  //sumamos
```
### Punto de venta
#### Descripcion del problema 
```
Punto y venta de un producto que permita ver el iva y el descuento.
```
#### Funcionalidad
```
Programa que muestre el 12% de iva y el 10% de descuiento y que desmuestre el valor a pagar, el valor del iva y el valor del descuento.
```
#### Salidad
```
jt_vb = jt_a0;
jt_iva = jt_vb*0.12; //sacamos el iva
jt_vdes = jt_vb*0.10;  //sacamos el descuento
jt_vfi = jt_vb+jt_iva;
jt_vft = jt_vfi-jt_vdes;
```
### La edad de una persona
#### Descripcion del problema 
```
Hacer que el programa muestre el año, el mes y el dia de que a transcurrido desde su fecha de nacimiento hasta la fecha actual.
```
#### Funcionalidad
```
programa que muestre la edad de una persona (año, mes, dia) de la persona, tenemos que restar el año, mes y dias actual menos  el año, mes y dias de nacimiento de la persona. 
```
#### Salidadá
```
if(jt_mesNaci < jt_mesAct){
jt_edad=jt_anioNaci-jt_anioAct;
}else if(jt_mesNaci<= jt_mesAct&jt_fechaNaci<=jt_fechaAct){
jt_edad=jt_fechaNaci-jt_fechaAct;
}else if(jt_mesNaci>jt_mesAct&jt_fechaNaci>jt_mesAct){(jt_edad=jt_anioAct-jt_anioNaci)-1; // restamos para que nos de la edad
```
### Cuenta moneda
#### Descripcion del problema
```
Una maquina de monedas de 10 y 25 centavos
```
#### Funcionalidad
```
Debes escribir un programa que decida cuantas monedas dará de cambio, dando prioridad las de mayor denominación. 
```
#### Salidada
```
if(jt_x==0.25)
{
jt_c1 = jt_c1+1;
jt_a1 = jt_x+jt_a1;
}
else
{
jt_c2 = jt_c2+1;
jt_a2 = jt_a2+jt_x;
}
```
## Instalador
### Descargar el repositorio
```
https://github.com/0850179698O/fundamento
```
### Compilar y ejececutar
```
cd pamelatorres
```
```
sumaN.cpp
```
```
g++ sumaN -o sumaN-ejecutable
```
