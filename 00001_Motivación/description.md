### Complemento a la base

Supongamos que tenemos un sistema decimal restringido a un solo dígito y se tiene que poder representar negativos (sin usar el signo “-”). 
Entonces se diseña un sistema denotado *D(1)* que se inspira en un mapeo circular como el de la imagen de manera que cada cadena (en este caso, dígito) quede aparejado con un valor. 

![Sistema complemento a la base de 1 bit](https://raw.githubusercontent.com/Orga-UNQ/mumuki-guia-text-complemento-a-2/master/images/d1.png "Sistema complemento a la base de 1 bit")

En la figura, el aparejamiento de cadenas con valores se hizo  usando el criterio de **complemento a la base**. Veamos de que se trata esto: La base es en este caso 10, y así, el ```9``` queda asociado al ```-1``` pues: ```10 +(-1) =9```

Esta distribución de las cadenas sobre los valores representados tiene la particularidad que **preserva las propiedades de las operaciones aritméticas**, pues para sumar dos cadenas del sistema D(1) es posible utilizar el mismo mecanismo que ya se conocía para el sistema decimal, aunque las cadenas estén representando otros números... y esa es una gran ventaja!. 
Responder:
