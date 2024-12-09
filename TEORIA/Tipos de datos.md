# Tipos de datos en java

## Datos primitivos

Hay 8 tipos de datos _primitivos_ en java, estos se dividen en los siguientes 4 grupos:

###  Enteros
Basicamente numeros __enteros__ positivos y negativos.

+ long
+ __int__
+ short
+ byte
Principalmente usaremos el int
La principal diferencia entre cada uno es el __rango__ que abarcan. por ejemplo el int va desde el numero –2,147,483,648 al 2,147,483,647.
 Con eso en principio tendredemos suficiente para nuestros programitas.

### Decimales
Nos permiten trabajar con numeros decimales tanto positivos como negativos.

+ double
+ float
  
Su diferencia tambien radica en el rango numerico que abarcan. Podemos usar cualquiera de los dos.
Al declarar una variable tipo float es __importante__ hacerlo de la siquiete manera:
~~~
float numeroTipoFloat = 45.6f;
~~~
Recuerda colocar la __f__ al final.


### Caracteres
Tipo de dato __char__. Por ejemplo 'A'  o 'v'
Al declarar un __char__ recuerda usar las comillas simples ''
~~~
char letraFavorita = 'e';
~~~
Tambien podemos escribir el codigo __ASCCI__ y nos devolvera la letra.

Por ejemplo:
~~~
char letraAscci = 97;
System.out.println(letraAscci);
~~~
Este programa nos devolvera la letra __a__.
Debido a que 'a' en ASCCI corresponde al numero 97.



## Datos no primitivos

### Strings
Representan una secuencia de caracteres(char) 

Por ejemplo:
~~~
String frase = "Esto es una frase!";
~~~


### Arrays
Estructura que almacena multiples valores del mismo tipo.
Se podria decir que es como una caja divivida en secciones ahi pudes guardar lo que quieres siempre y cuando sea del mismo tipo de dato(los datos que hemos visto arriba )

Por ejemplo para declarar un array para guardar numeros __enteros__:
~~~
int[] numeritos = {1, 3, 8, 2};
~~~

#### Declarando Arrays
Hay dos formas de crearlas:

+ Asignando los valores al principio.

~~~
int[] numeritos = {1, 2, 3, 4};
~~~
De esta forma ya hemos definido la __cantidad__ de "cosas" que hay dentro y tambien que "cosas" concretas hay dentro, en este caso habrian los numeros 1,2,3 y 4.

+ Asignando los valores despues.

~~~
int[] numeritos = new int[3];
~~~
Ahora solo hemos definido la cantidad de cosas que habran en nuestro array `[3]` en este caso __4__ cosas.
Porque podremos poner cosas en las posiciones 0,1,2 y 3. A cada una de esas posiciones podremos asignarle un numero.
De la siguiente forma:
~~~
numeritos[0] = 1;
numeritos[1] = 2;
numeritos[2] = 3;
numeritos[3] = 4;
~~~
Dos dos metodos de lograr lo mismo. Dependiendo del programa que queramos hacer tendremos que usar uno u otro.
