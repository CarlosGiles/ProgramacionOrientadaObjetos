![metodo-sumar-java](https://user-images.githubusercontent.com/92232878/179815357-76b6edf8-86f5-4b18-87cf-e525e606f688.png)

# Métodos

Un métodos en **Java** es un bloque de código que contiene sentencias que realizan una tarea en específico. Por ejemplo:

En el siguiente **método** se observa el método ***add*** cuya finalidad es realizar la suma entre dos números e imprime los valores en la consola mediante en **Método println** (método ya pre-definido en Java).

![image](https://user-images.githubusercontent.com/92232878/179817340-4ac44494-3624-4d3f-913c-cc75f0d0c063.png)

El **método** ***println*** solo acepta un argumento, por ello se **concatena** la variable ***result*** utilizando el símbolo **+**. Esta concatenación de puede utilizar las veces que sean necesarias:

* ![image](https://user-images.githubusercontent.com/92232878/179817954-23051240-28a7-45ee-8ae5-a945e7d3eeb1.png)

El mensaje en la consola de la sentencia anterior sería: ***" La suma de los valores 10 + 5 es igual a 15"***

## Declaración de un método

En **Java** la declaración de un método implica 5 elementos:

* Modificador de acceso: indica desde qué parte del código, el método será accesible. Puede ser **public, protected o private**.

* Tipo de dato a devolver: el método puede o no devolver valores. Si se define **String** deberá devolver una cadena, si se define **int** será un número entero, si se define **void** no devolverá un valor.

* Nombre del método: el método se define con un nombre con el cual será identificado y se le podrá mandar llamar.

* Parámetros: este elemento es opcional. Los parámetros sirven para enviar argumentos y son utilizados en las sentencias dentro del método.

* Valor a devolver: este elemento es opcional. Se usa la palabra reservada **return** que devuelve un valor cuando se manda a llamar la función.

![image](https://user-images.githubusercontent.com/92232878/179820676-0c6c0db0-0ed8-425e-a50b-65e5ca22bd43.png)

## Parámetros en un método

Los **parámetros** son aquellos que se definen dentro del método, en el ejemplo anterior, **valA** y **valB**. Los **argumentos** son aquellos que se usan o que son ***"pasados"*** cuando se manda llamar al método.

![image](https://user-images.githubusercontent.com/92232878/179823409-60fcf722-91c4-4f46-8097-1703c7feb946.png)

## Retorno de valores en un método

Un **método** devuelve un valor siempre y cuando cumpla:

* Que tenga un tipo de dato diferente a **void** y que dentro del mismo haga uso de la palabra reservada **return**, seguido del valor que deseamos devolver.
* Que el tipo de dato sea igual que el método que se espera que devuelva.

Ejemplos:

Correcto --> ![image](https://user-images.githubusercontent.com/92232878/179824391-e548a1e8-1cc0-4e5a-aa2c-b5dd5fcbdfda.png)

Falta **return** y valor deseado --> ![image](https://user-images.githubusercontent.com/92232878/179824512-c659de24-cc08-42eb-8a8c-c6df6044a270.png)

Tipos de datos no corresponden --> ![image](https://user-images.githubusercontent.com/92232878/179824626-c3e4788a-1a02-4a41-abdb-7afe0dc0fae0.png)

## Sobrecarga de métodos (Overload)

Se da cuando se tienen dos o más métodos con el mismo nombre pero con diferentes parámetros (diferente cantidad de parámetros o diferente tipo de valores).
El siguiente ejemplo es correcto ya que tienen diferente cantidad de parámetros y aunque el segundo y el tercero solo tienen un parámetro, el tipo de dato es diferente.

![image](https://user-images.githubusercontent.com/92232878/179825833-036abcfe-7967-481d-964f-1ba98b3516dd.png)

El siguiente ejemplo es incorrecto ya que los métodos tienen el mismo número de parámetros y el mismo tipo de dato, el nombre del parámetro no los hace diferentes.

![image](https://user-images.githubusercontent.com/92232878/179826458-d9a4a2f0-b961-4479-861c-5e3cf66fa758.png)

## Método constructor y destructor

### Constructor
El **método constuctor** es primordial en la construcción de clases, es el primero en ser creado cuando se establece una instancia de la clase y usualmente es el encargado de inicializar los atributos que contenga la clase. Este método crea un objeto de la clase.
El método constructor se construye de una forma diferente:

* No puede contener un valor de retorno y ni el tipo **void** es considerado válido
* El nombre del constructor debe ser exactamente el de la clase considerando mayúsculas y minúsculas

Cabe aclarar que el **método constuctor** también trabaja con el paso de parámetros, sobrecarga de constructores e incluso con los modificadores de acceso.

### Destructor
El **método destructor** es utilizado para destruir las instancias de las clases. *Java* cuenta con **Garbage Collector** que libera la memoria RAM una vez que una instancia ha perdido su referencia, por lo tanto no es necesario usar destructores. 

#### Propiedad de Carlos Giles

<a href="https://twitter.com/charlygvc" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="charlygvc" height="30" width="40" /></a> [@CharlyGVC](https://twitter.com/CharlyGVC)
<a href="https://linkedin.com/in/https://www.linkedin.com/in/carlosgilesing/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/carlosgilesing/" height="30" width="40" /></a> [Carlos Giles](https://www.linkedin.com/in/carlosgilesing/)
<a href="https://instagram.com/gilescharly" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="gilescharly" height="30" width="40" /></a> [gilescharly](https://www.instagram.com/gilescharly/)
</p>
