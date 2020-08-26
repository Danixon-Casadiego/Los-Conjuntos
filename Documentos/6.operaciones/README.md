# Operaciones de conjuntos

Las operaciones de conjuntos también conocidas como álgebra de conjuntos, nos permiten realizar operaciones sobre los conjuntos para obtener otro conjunto. De las operaciones con conjuntos veremos las siguientes unión, intersección, producto cartesiano. 

___
## Unión de conjuntos
___

La unión de dos conjuntos es una operación que resulta en otro conjunto, cuyos elementos son los mismos de los conjuntos iniciales. y la operación se denota con el siguiente símbolo [ ["∪"] ](# "unión") se lee: "*unión*". Así que si tenemos dos conjuntos A y B, la unión de A y B formaría un nuevo conjunto C [[ A ∪ B = C ]](# "A unido con B es igual a C") en simbologia se vería así:

[A ∪ B = C = { x / x ∈ A ∨ x ∈ B }](# "A unido con B es igual al conjunto de los elementos x tal que x pertenezca a A o x pertenezca a B")

![imagen](/imagenes/imagen19.jpg)

La unión de conjuntos posee las siguientes propiedades:

- Conmutatividad : esto estable que si cambiamos el orden de los conjuntos nos va a dar exactamente igual que si no lo fuéramos cambiado es decir:

    [A ∪ B = B ∪ A](# "A unido con B es igual a B unido con A")


- Asociatividad : dado dos operaciones de unión, operar primero uno y luego operar el otro da el mismo resultado si se hace em sentido contrario, es decir: 

    [(A ∪ B) ∪ C = A ∪ (B ∪ C)](# "A unido con B y luego unido con C es igual a B unido con c y luego unido con A")

    >NOTA : Fíjate, lo que esta en paréntesis se opera primero y luego el resultado (que es un conjunto) se opera con el otro conjunto. OJO no se cambia la posición en la operación si ves todos los conjuntos siguen en su posición y los paréntesis dice que operación hago primero 
___
## Intersección de dos conjuntos 
___
La intercción de conjuntos es una operación que resulta en otro conjunto, cuyos elementos son los elementos que pertenecen a ambos conjuntos a la vez, y se denota con el siguiente símbolo [["∩"]](# "intersección") se lee: "*intersección*", dado dos conjuntos P y F, La intersección de P y F formaría un nuevo conjunto C [[ P ∩ F = D ]](# "P interceptado con F es igual a D").en simbología sería así:

 [P ∩ F = D = { x / x ∈ P ∧ x ∈ F }](# "P interceptado con F es igual al conjunto de los elementos x tal que x pertenezca a P y también a F ")

![imagen](/imagenes/imagen20.jpg)

La intersección de conjuntos posee las siguientes propiedades:

- Conmutatividad : esto estable que si cambiamos el orden de los conjuntos nos va a dar exactamente igual que si no lo fuéramos cambiado es decir:

     [ P ∩ F = F ∩ P](# "P interceptado con F es igual a F interceptado con P")

- Asociatividad :       estable que operar primero uno y luego operar la otra da el mismo resultado si se hace em sentido contrario, es decir:

    [(P ∩ F) ∩ C = P ∩ (F ∩ C)](# "P interceptado con F y luego interceptado con C es igual a F interceptado con c y luego interceptado con P")

    >NOTA : Fíjate, lo que esta en paréntesis se opera primero y luego el resultado (que es un conjunto) se opera con el otro conjunto. OJO no se cambia la posición en la operación si ves todos los conjuntos siguen en su posición y los paréntesis dice que operación hago primero

___
## Conjuntos disjuntos.
___
Se dice que dos conjuntos son disjuntos si no poseen ningún elemento en común, en caso contrario se dice que esos dos conjuntos son no disjuntos, se puede representar a través de la intersección de conjuntos que da como resultado el conjunto vació si es disjunto y si existe por lo menos un x de la intersección entonces son no disjuntos, como se muestra a continuación: 

![imagen](/imagenes/imagen21.jpg)
___
## Par ordenado

Antes de seguir con la siguiente operación hay que mencionar un elemento que va a resultar de dicha operación, los pares ordenados.

> Par ordenado: es un conjunto ordenado que posee dos elementos. 

Fíjate en esa definición "es con conjunto ordenado" antes había mencionado que no importaba el orden de los elementos cuando lo definíamos por extención es decir:

A = { a , b } es igual a decir { b , a }

 Pero los pares ordenados si tienen un orden y para eso se crearon, simbólicamente se representa así (a,b), y en conjunto seria así:

 (a,b) = { {a} , {a,b} }

 Ayyy!! que feo, pero en realidad no nos importa como se define en conjunto, sino esta "( a , b )" y la propiedad que cumple que es la siguiente:

 [( a , b ) = ( c , d )  <=> [ a = c  ∧ b = d ]](# "el par ordenado a,b es igual al par ordenado c,d si y solo si a = c y b=d")

 >Nota: acuérdate que los símbolos que están azul al pasar el curso te lo traduce en palabras

¿Pero que significa esto?

Significa que el orden de los elementos importa, es decir:

![imagen](/imagenes/imagen22.jpg)
  
  Si tenemos el par ordenado ( a , b) las partes se llaman así: a *a* se le llama primera coordenada y a *b* la segunda coordenada
___
## Producto cartesiano 
 ___
  El producto cartesiano de dos conjuntos es una operación, que resulta en otro conjunto, cuyos elementos son todos los pares ordenados que pueden formarse de forma que el primer elemento del par ordenado pertenezca al primer conjunto y el segundo elemento pertenezca al segundo conjunto. y se denota por este símbolo [[ X ]](# "por") se lee: "*por*", dado dos conjuntos A y B el producto cartesiano de A por B denotado así:  [[ A X B ]](# "A por B").

  ![imagen](/imagenes/imagen23.jpg)
  
La primera coordenada de los pares ordenados son elementos del conjunto A y la segunda coordenada son elementos del conjunto B.

El conjunto A X B es un conjunto desordenado a diferencia de sus elementos que son conjuntos ordenados esto quiere decir que la colocación de los pares ordenados en dicho conjunto no sigue un patron lo coloque así por mero gusto visual es decir que los siguiente también es correcto:

![imagen](/imagenes/imagen24.jpg)

Algo muy interesante de pensar dado ¿cuantos elementos poseen mis conjuntos cuantos pares ordenados se crean?

bueno la respuesta es una multiplicación, multiplica la cantidad de elementos que poseen  cada conjunto y te da la cantidad de pares ordenados, en este caso seria [ 3 . 3 = 9 ]

A diferencia de la union y la intersección, el producto cartesiano de dos conjuntos no es conmutativo en general, salvo en casos muy especiales. Lo mismo ocurre con la propiedad asociativa.

### Representación del producto cartesiano:

El producto cartesiano se representa de varias maneras pero aquí vamos a ver dos, el diagrama de flechas y el diagrama cartesiano o plano cartesiano:

![imagen](/imagenes/imagen25.jpg)

Fíjate que los puntos en el plano representan los pares ordenados mostrados anteriormente, y el plano cartesiano es la base de la geometría analítica, por eso es importante esta operación que efectuado con el conjunto de los Reales se crea el plano [R<sup>2</sup>](# "R dos") o R X R.
___
## Conclusiones

- Un par ordenado es un conjunto de dos elementos ordenados, el cual el primer elemento es la primera coordenada y segundo elemento es la segunda coordenada.

- El producto cartesiano es una operación que crea un conjunto formado por pares ordenados.

- [A X B = {(a,b)}, <==> a ∈ A y b ∈ B](# "A por B es igual al conjunto formado por pares ordenados si y solo si a pertenece a A y b pertenece a B ") se lee: A por B es igual al conjunto formado por pares ordenados, si y solo si, a es un elemento del conjunto A y b es un elemento del conjunto B.
___
En el siguiente apartado hablaremos de las correspondencia y luego de un tipo especial de correspondencia llamada función o aplicación que es la base de todo el calculo.

---
| [<------Volver al anterior apartado ](/Documentos/5.Conjuntos-especiales/README.md)| [volver al indice](/README.md)|[Seguir con el siguiente apartado------>](/Documentos/7.correspondencia/README.md)|
|:-|:-:|-:|



