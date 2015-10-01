# Ivestigaci-n

Variables estáticas

Cualquier declaración de una variable puede tener el prefijo “static”. Las variables estáticas en C tienen las siguientes dos propiedades:
1.	No pueden ser accedidas desde otro fichero. Por tanto, los prefijos “extern” y “static” no pueden ser utilizados en la misma declaración.
2.	Mantienen su valor a lo largo de toda la ejecución del programa independientemente del ámbito en el que estén definidas.
Como consecuencia de estas dos propiedades se derivan los siguientes casos:
1.	Si una variable estática está declarada fuera de las funciones, será accessible únicamente por el código que le siga en el mismo fichero de su declaración.
Si una variable estática está declarada en una función, sólo será accesible desde esa función y mantendrá su valor entre ejecuciones de la función. Este comportamiento es contra intuitivo porque estas variables se declaran en el mismo lugar que el resto de variables en una función, pero mientras que estas adquieren valores nuevos con cada ejecución, las estáticas conservan estos valores entre ejecuciones.

Ciclo de vida de las variables

El tiempo de vida se refiere al intervalo de tiempo que trascurre desde que se crea la variable hasta que se destruye. En Java, una variable se crea en el momento que se ejecuta su declaración y se destruye cuando finaliza el bloque de instrucciones en donde fue declarada

Memoria dinámica (lenguaje c)

memoria que no puede ser definida ya que no se conoce o no se tiene idea del número de la variable a considerarse, la solución a este problema es la memoria dinámica que permite solicitar memoria en tiempo de ejecución, por lo que cuanta más memoria se necesite, más se solicita al sistema operativo. El sistema operativo maneja la memoria gracias al uso de punteros, por la misma naturaleza del proceso nos impide conocer el tamaño de la memoria necesaria en el momento de compilar.

Clase

es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables -el estado, y métodos apropiados para operar con dichos datos -el comportamiento. Cada objeto creado a partir de la clase se denomina instancia de la clase.
Permiten abstraer los datos y sus operaciones asociadas al modo de una caja negra.

Objeto

Un objeto es una unidad dentro de un programa de computadora que consta de un estado y de un comportamiento. Cada objeto es capaz de recibir mensajes, procesar datos y enviar mensajes a otros objetos de manera similar a un servicio. Un objeto es el resultado de la instanciación de una clase

Constructores de instancias
Los constructores de instancias se usan para crear e inicializar cualquier variable de miembro de instancia cuando se usa la expresión new para crear un objeto de una clase.
Herencia 
Es la capacidad de crear nuevas clases basándose en clases previamente definidas, de las que se aprovechan ciertos datos y métodos, se desechan otros y se añaden nuevos.
Sobrecarga
La sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizando acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados.
Shadowing 

Se llama shadowing al hecho de que en una clase una variable miembro y una variable local definida en un método miembro, se llamen igual.
