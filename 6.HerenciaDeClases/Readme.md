![HerenciaV2_jarroba](https://user-images.githubusercontent.com/92232878/179843219-af0b857e-70b5-4f35-8517-322193fb35eb.png)

# Herencia de clases

La herencia es una de las principales caracteristicas de la **POO**, la cual nos permite agrupar aquellas características que algunos objetos tengan en común.
La herencia divide a las clases en dos tipos:

* Clase base/padre: contiene los atrinutos y métodos que tienen en común otras clases.
* Clase heredada: tiene acceso a los atributos y métodos de la clase base/padre, además de contener los propios.

En la siguiente imágen tenemos un doctor, un maestro y un policía. Las 3 son profesiones distintas, tendrá cada una métodos y atributos propios pero además, tienen 
métodos y atributos en común ya que son personas. Por eso decimos que una clase doctor, maestro o policía (heredadas) hereda de la clase persona (padre)

![image](https://user-images.githubusercontent.com/92232878/179846914-2ec988b7-dab9-46f4-abb1-9f64aa6e4195.png)

Una clase en una representación de un objeto de la vide real.

Si organizamos cada una de las profesiones en una clase, podemos ver los métodos y atributos que comparten y los propios:

![image](https://user-images.githubusercontent.com/92232878/179847344-8166e77d-24c0-4e3b-a9d4-d2d14442014a.png)

![image](https://user-images.githubusercontent.com/92232878/179847871-4ee77590-8561-4d1e-b145-e3b060d1f017.png)

![image](https://user-images.githubusercontent.com/92232878/179847989-52fe189d-14ae-415d-810a-4a2b900b02ed.png)

## Clase base/padre
![image](https://user-images.githubusercontent.com/92232878/179848207-11330ed8-df12-456b-80b2-26f0aea456a6.png)

## Clase heredada
![image](https://user-images.githubusercontent.com/92232878/179848386-17cdd73e-5575-40cc-86cc-8c1f3a575391.png)

![image](https://user-images.githubusercontent.com/92232878/179850533-04cab6f8-7aac-4572-895e-2450d380302e.png)

## 6 aspectos acerca de cómo pasar parámetros al constructor de la clase base usando la palabra reservada **super**

* 1) La clase padre será **Person**, en ella deberá estar el constructor de la clase hija, en este caso **Police**

![image](https://user-images.githubusercontent.com/92232878/179852085-f5e9f897-8116-4de0-9f58-ab3912626c68.png)

![image](https://user-images.githubusercontent.com/92232878/179852131-873c9373-74f1-4e44-aa6a-8c12aab819c4.png)

* 2) Por aparte, en la clase hija **Police** que extiende de **Person**, utilizamos el constructor **Police** definido en la clase **Person** e incluso agregamos 
el atributo **Model** de tipo **String** que es propia de la clase **Police**

![image](https://user-images.githubusercontent.com/92232878/179853724-fe1bf7e3-7604-4fb2-92fc-8d3f54a088f3.png)

![image](https://user-images.githubusercontent.com/92232878/179853794-6003fd60-38c1-4c04-9bf5-cb36f838d6c4.png)

* 3) En la clase **Police**, al iniciar el constructor del mismo nombre (pero definido en la clase **Person**) usamos la palabra reservada **super** cuáles 
atributos serán tomados desde la clase original/base/padre o **superclase**.

![image](https://user-images.githubusercontent.com/92232878/179854461-04b4a8d1-97a2-460a-b8c9-466093b37552.png)

* 4) Más adelante y aún en la clase **Police**, creamos una instancia de sí misma e indicamos el valor de los atributos. Podemos ver esta sentencia como: "una 
instancia ***p*** del tipo **Police** es un nuevo objeto que se crea con el constructor **Police**".

![image](https://user-images.githubusercontent.com/92232878/179855309-8bd2c6c5-13d5-45e6-a793-8bd0ea9b60cf.png)

* 5) Y para observar el objeto o instancia creada, utilizamos la función "***System.out.println();***"

![image](https://user-images.githubusercontent.com/92232878/179855645-72ab5bad-89a4-4c78-b696-6e28eba9860d.png)

* 6) En consola se observa:

![image](https://user-images.githubusercontent.com/92232878/179855760-c38205fd-37ce-43d9-a021-fe2728fc633b.png)

El ejemplo anterior es un ejemplo de ***Herencia Simple***, una o varias clases se definen de manera que se extienden a una sola **superclase**. Se pueden 
agregar indefinidamente más profesiones ya que a fin de cuentas son personas.

### Herencia multiple

Consiste en tener más de una clase base y heredar los atributos y métodos de cada una de ellas.

![image](https://user-images.githubusercontent.com/92232878/179856922-78f2c0f3-7f3e-4789-aa5b-d131e3986f0c.png)

**JAVA NO ACEPTA HERENCIA MULTIPLE** para simular este tipo de herencia, en **Java** tenermos las **Interfaces**.

## Interfaz

![image](https://user-images.githubusercontent.com/92232878/179857532-64e20084-fcb8-434c-9de2-9c47eb3554dd.png)

Es una especie de plantilla en la cual se definen un conjunto de métodos sin ninguna lógica y variables que contienen valores estáticos, sin la posibilidad 
de ser modificados durante la ejecución del programa, es muy parecido a un método abstracto.
