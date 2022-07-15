

# Clases

La **clase** es una forma definida para la creación de objetos. A partir de una **clase** se pueden definir una infinidad de objeto, a continuación se muestra una *plantilla* de una **clase**:

![image](https://user-images.githubusercontent.com/92232878/179121478-56b324b5-cd8c-44c0-9211-1f08a9fdff96.png)

Enseguida podemos organizar por *"bloques"* el contenido dentro de una clase:

![image](https://user-images.githubusercontent.com/92232878/179122230-f7050f08-8ae0-410d-9f8b-32c7347db7d0.png)

![image](https://user-images.githubusercontent.com/92232878/179121787-7d61a82d-c437-48eb-bfc2-53e2bc1cafd5.png)

![image](https://user-images.githubusercontent.com/92232878/179121917-fc3fffd0-d808-4c9f-8524-59d5f8c74106.png)

![image](https://user-images.githubusercontent.com/92232878/179121945-84bad5f5-8e94-454a-bc1e-d960af283f43.png)

## Atributos de una clase

Los **atributos** de una clase son siempre *variables* pero no todas las variables de nuestro programa son atributos. Un atributo es una propiedad que ayuda a describir un objeto.

![image](https://user-images.githubusercontent.com/92232878/179123857-c91b8adb-d54d-4c26-9be3-c12414c50e6c.png)

![image](https://user-images.githubusercontent.com/92232878/179123955-999bf396-511a-438b-ac1c-ab81f5ac65da.png)

![image](https://user-images.githubusercontent.com/92232878/179123991-5ac3c2a6-4923-4a63-a8de-4aa0dd059e2f.png)

Para los atributos, existen dos tipos de datos:

* **Primitivos:** son los definidos por el lenguaje (String, int, etc)
* **Por referencia:** haven referecia a una clase, por ejemplo, ***"Person person;"*** donde ***"Person"*** es el tipo de dato y ***person"*** corresponde a la variable.

## Métodos de una clase

Ayudan a agrupar instrucciones y sirven para que la clase pueda realizar tareas en específico. Dentro sel **método** se escriben las instrucciones necesarias para llevar acabo dichas tareas.
Cabe destacar que un método puede o no devolver un valor y, además, puede recibir **N** cantidad de parámetros.

Los elementos de un método son:

![image](https://user-images.githubusercontent.com/92232878/179125402-de4dffa4-0ef3-41b6-9000-2d8d0a90ee48.png)

![image](https://user-images.githubusercontent.com/92232878/179125441-789e73b0-b17f-470e-9270-653ff9fbf177.png)

![image](https://user-images.githubusercontent.com/92232878/179125675-473b3611-c04a-4e03-958d-74125a2fdcce.png)

## Encapsulamiento en una clase

En el siguiente fragmento de código vemos la palabra reservada **this**, la cual tiene acceso a todos los elementos de la clase actual. Es por eso que **this** tiene acceso a los atributos ***name*** y ***lastName*** y a los **métodos** ***talk*** y ***walk***.

![image](https://user-images.githubusercontent.com/92232878/179126039-d1a33a6c-a91f-45b5-942c-11fba255d003.png)

![image](https://user-images.githubusercontent.com/92232878/179126425-ad0e0cfb-a9e8-4118-91e9-3bd698c61dd2.png)

![image](https://user-images.githubusercontent.com/92232878/179126452-48b7566c-0d51-4d45-9652-17576e946e83.png)

Poner todo público causaría que se modifiquen los atributos desde cualquier parte y poner todo en privado complicaría modificar los atributos cuando sea realmente necesario. Para estos inconvenientes existen dos **métodos**: **set* y **get**.

* El **método set** asigna un valor a un atributo:

![image](https://user-images.githubusercontent.com/92232878/179127241-f118d17c-765c-4fd9-940c-f6fc7a26df5c.png)

* El **método get** obtiene/devuelve ese mismo valor:

![image](https://user-images.githubusercontent.com/92232878/179127383-5d77184a-0c69-40ab-ba4e-dd590c13ac77.png)

## Instancia de una clase

Una instancia se crea a partir de una clase, mediante la cual tenemos a los atributos y métodos de la misma. Para crearla, usamos la palabra reservada **new**.
Al crear una instancia se reserva un espacio en la memoria RAM.

![image](https://user-images.githubusercontent.com/92232878/179128719-404645be-6876-472a-bd6d-7b72c490a245.png)

Para poder acceder a los atributos y métodos de una clase mediante su instancia, necesitamos crear una variable del mismo tipo que la clase a la cual se está creado la instancia, por ejemplo: 

**Person person;**

Hemos creado una variable llamada **person** pero en lugar de asignar un tipo de dato primitivo como **int, double, etc**, indicamos que es del tipo **Person**, el cual corresponde a una clase.

![image](https://user-images.githubusercontent.com/92232878/179129950-623a127a-74e3-43c1-9c49-a65f51a449ce.png)

#### Propiedad de Carlos Giles

<a href="https://twitter.com/charlygvc" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="charlygvc" height="30" width="40" /></a> [@CharlyGVC](https://twitter.com/CharlyGVC)
<a href="https://linkedin.com/in/https://www.linkedin.com/in/carlosgilesing/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/carlosgilesing/" height="30" width="40" /></a> [Carlos Giles](https://www.linkedin.com/in/carlosgilesing/)
<a href="https://instagram.com/gilescharly" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="gilescharly" height="30" width="40" /></a> [gilescharly](https://www.instagram.com/gilescharly/)
</p>
