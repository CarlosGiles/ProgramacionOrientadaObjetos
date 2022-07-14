![javaex](https://user-images.githubusercontent.com/92232878/178557171-bf46a4c0-1cab-4af9-bc3b-9c008c865eec.png)

# Modelo de objetos

El modelo de objetos se compone de elementos que ayudan a construir este paradigma y un poderoso lenguaje para hacerlo es **Java**. La programación orientada a objetos pretende agrupar el código por secciones y hacer que trabajen de manera independiente para que los métodos que se vayan construyendo no dependan de otros para funcionar correctamente, además, a medida que crece la aplicación se vuelve sostenible el código. Los elementos utilizados en **Java** son:

![image](https://user-images.githubusercontent.com/92232878/178564931-7b82e1f8-4761-40fe-871c-adc389a4ec0d.png)

## Clase

Podemos definir una **"clase"** como el molde o la caja que contiene los atributos y métodos dispuestos para dar forma a un objeto. Ejemplo:

* Gráfico --> ![image](https://user-images.githubusercontent.com/92232878/178567181-6d0d57e3-7053-4ef3-a380-d013efb98de9.png)
* Código --> ![image](https://user-images.githubusercontent.com/92232878/178567439-325c5fc6-098f-4c6d-a63e-ea4811e2b530.png)

## Objeto

Es la entidad creada a paritr de la clase (molde) compuesta de métodos y atributos, en seguida vemos el código donde se crea el objeto **vehiculo**:

![image](https://user-images.githubusercontent.com/92232878/178582558-e08c85e4-ebfe-42bf-9865-ce8549c4ab46.png)

![image](https://user-images.githubusercontent.com/92232878/178583069-573bb0c7-22aa-45ba-ae8b-d79a0dbf40d8.png)

## Herencia

Es la propiedad de las **clases** que permiten heredar los atributos y métodos de otra clase. En el siguiente código de **Java**, vemos cómo se implementa la herencia.

* Teniendo el siguiente código de la clase **Vehiculo**:

![image](https://user-images.githubusercontent.com/92232878/178586497-3c3c30d3-cd66-4f16-a4c8-7f21e93923d8.png)

* Implementamos la propiedad de herencia en la clase Motocicleta:

![image](https://user-images.githubusercontent.com/92232878/178584118-55090381-8e4d-4e9e-952e-bf7761a2059d.png)

Después del nombre de la clase **"Motocicleta"** se encuentra la palabra reservada **extends** que indica que, dicha clase (Motocicleta), hereda los atributos y métodos de la clase que se declara enseguida (en este caso **Vehiculo**). Como se observa, en este código de la clase **Motocicleta** se encuentra declarado el método "**public void conducirA(){ }**" y dentro de él, se utiliza en método "**public void encenderVehiculo(){ }**" que se declaró en la clase **Vehiculo**.

## Abstracción

En programación, la abstracción se aplica tanto a clases como a métodos. Hacer abstracción sigifica identificar características esenciales del objeto, es decir, todo aquello que el objeto necesita para ser o existir y que sin ello, deja de ser como lo consebimos.

Un método abstracto es un método que no contiene las acciones que realiza, por ende, cada objeto puede utilizar este método y "terminarlo" con las acciones que sean necesarias.

![image](https://user-images.githubusercontent.com/92232878/178591084-41108ec0-ddb6-4e14-b15a-18aacaca7d77.png)

Una clase abstracta es aquella que contiene al menos un método abstracto. Esta clase no se encuentra completamente definida y por lo tanto no es posible instanciar objetos de dicha clase.

![image](https://user-images.githubusercontent.com/92232878/178591172-622c23ca-9319-4e91-8593-58e541fb4aa2.png)

Enseguida vemos código en **Java** donde se define la clase abstracta con la palabra reservada **abstract** y los métodos abstractos:

![image](https://user-images.githubusercontent.com/92232878/179049235-7c577106-eede-49e0-ae7e-d76bceda61f9.png)

Podemos observar que los métodos están definidos pero no contienen código que describa acciones.

### Uso de una clase abstracta

El anterior código define la clase abstracta, ahora vemos que una clase pública **Motocicleta** hereda de la clase **Vehiculo** para poder acceder a sus métodos:

![image](https://user-images.githubusercontent.com/92232878/179049940-8715ff19-7709-4022-8096-552017398e8d.png)

Es importante aclarar que cuando se utiliza una clase abstracta (**Vehiculo**) dentro de otra clase (**Motocicleta**), es obligatorio **IMPLEMENTAR** los métodos abstractos definidos en dicha clase abstracta. Al hacerlo, es común que determinados editores de código muestren la leyenda "**@Override**", significa que estamos haciendo uso de una técnica llamada "**sobrescribir**" un método. 

## Modularidad

Cuando un programa cumple con esta propiedad, quiere decir que se encuentra separado en modulos independientes que no dependen de otros para funcionar correctamente. En **Java**, los métodos se comportan cómo módulos que mantienen el código separado.

![image](https://user-images.githubusercontent.com/92232878/179053974-8065e06f-da93-4aae-8326-9337581ea928.png)

Si observamos el anterior código, notaremos que hay dos métodos definidos, para separar las acciones que hará el vehículo y que cada una funcione independientemente.

## Encapsulamiento

Permite ocultar las características no relevantes de una clase, destacar las relevantes y modelar su comportamiento. Dando como resultado la abstracción de datos. Además, es un proceso que defne la privacidad de los atributos de los objetos para garantizar la seguridad de los datos.

En el siguiente código vemos la palabra ***private*** en lugar de ***public*** antes del nombre del atributo:

![image](https://user-images.githubusercontent.com/92232878/179068716-4b95b852-5455-414a-be1c-44104fb352fc.png)  continúa --> ![image](https://user-images.githubusercontent.com/92232878/179068946-a4e250df-9ab0-49e8-ab71-07f6e98c91b4.png)

## Polimorfismo

Es el conjunto de operaciones aplicables a un ***objeto*** por medio de los mensajes que invocan a alguno de los métodos definidos en la clase a la 
que pertenece el objeto de acuerdo al dominio de la aplicación. Por ejemplo, es cuando un método toma un comportamiento diferente al pasarle parámetros que son usados dentro del mismo método. Hay tres tipos de polimorfismo:

* Primitivos --> debido al ***overload*** (sobrecarga, se usa en métodos)
* Real --> por redifinición de métodos (***override***)
* Genérico --> gracias a las clases genéricas

![image](https://user-images.githubusercontent.com/92232878/179074878-aacf3e6b-0451-40c9-9753-1abe6f1a93c9.png)

En el anterior ejemplo tenemos 3 ***métodos*** con el mismo nombre pero diferente comportamiento debido a la diferencia en los parámetros recibidos.

#### Propiedad de Carlos Giles

<a href="https://twitter.com/charlygvc" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="charlygvc" height="30" width="40" /></a> [@CharlyGVC](https://twitter.com/CharlyGVC)
<a href="https://linkedin.com/in/https://www.linkedin.com/in/carlosgilesing/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/carlosgilesing/" height="30" width="40" /></a> [Carlos Giles](https://www.linkedin.com/in/carlosgilesing/)
<a href="https://instagram.com/gilescharly" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="gilescharly" height="30" width="40" /></a> [gilescharly](https://www.instagram.com/gilescharly/)
</p>
