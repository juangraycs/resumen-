Juan Manuel Gray Cervantes 146585
	
Resumen de temas Programacion.

Variables estáticas.
" static: los atributos miembros de una clase pueden ser atributos de clase o atributos de instancia; se dice que son atributos de clase si se usa la palabra clave static: en ese caso la variable es única para todas las instancias (objetos) de la clase (ocupa un único lugar en memoria). A veces a las variables de clase se les llama variables estáticas. Si no se usa static, el sistema crea un lugar nuevo para esa variable con cada instancia (la variable es diferente para cada objeto). En el caso de una constante no tiene sentido crear un nuevo lugar de memoria por cada objeto de una clase que se cree. Por ello es adecuado el uso de la palabra clave static. Cuando usamos “static final” se dice que creamos una constante de clase, un atributo común a todos los objetos de esa clase."
Una variable de clase es aquella que puede ser invocada sin existir una instancia.
Para invocar a una variable estática no se necesita crear un objeto de la clase en la que se define:
Si se invoca desde la clase en la que se encuentra definido, basta con escribir su nombre.
Si se le invoca desde una clase distinta, debe anteponerse a su nombre, el de la clase en la que se encuentra seguido del operador punto (.) <NombreClase>.variableEstatica



Memoria dinámica.
¿Qué es memoria?
Es un espacio lógico para guardar información.
La memoria (también llamada almacenamiento) se refiere a parte de los componentes que forman parte de una COMPUTADORA, Son dispositivos que retienen DATOS informáticos durante algún intervalo de tiempo. Las memorias de computadora proporcionan unas de las principales funciones de la computación moderna, la retención o almacenamiento de información. Es uno de los componentes fundamentales de todas las computadoras modernas que, acoplados al CPU.
¿QUÉ ES ESTÁTICA?
La forma más fácil de almacenar el contenido de una variable en memoria en tiempo de ejecución es en memoria estática o permanente a lo largo de toda la ejecución del programa. O sea,  que no se modifica al menos en tiempo de ejecución.
No todos los objetos (variables) pueden ser almacenados estáticamente.
Para que un objeto pueda ser almacenado en memoria estática su tamaño (número de bytes necesarios para su almacenamiento) ha de ser conocido en tiempo de compilación, como consecuencia de esta condición no podrán almacenarse en memoria estática:
¿Qué es dinámica?
Su tamaño puede variar durante la ejecución del programa y puede ser liberado mediante la función free. O sea que se modifica permanentemente.
Memoria estática
Las técnicas de asignación de memoria estática son sencillas.
La asignación de memoria puede hacerse en tiempo de compilación y los objetos están vigentes desde que comienza la ejecución del programa hasta que termina.
En los lenguajes que permiten la existencia de subprogramas, y siempre que todos los objetos de estos subprogramas puedan almacenarse estáticamente se aloja en la memoria estática un registro de activación correspondiente a cada uno de los subprogramas.
Estos registros de activación contendrán las variables locales, parámetros formales y valor devuelto por la función.


Objeto.
Entidad existente en la memoria del ordenador que tiene unas propiedades llamadas atributos que son valores o características de los objetos y permiten definir el estado del objeto u otras cualidades y unas operaciones disponibles específicas llamadas métodos que en pocas palabras son acciones que puede realizar el objeto.
Se trata de un ente abstracto usado en programación que permite separar los diferentes componentes de un programa, simplificando así su elaboración, depuración y posteriores mejoras.
Los objetos integran, a diferencia de los métodos, tanto los procedimientos como las variables y datos referentes al objeto.
A los objetos se les otorga ciertas características en la vida real. Cada parte del programa que se desea realizar es tratado como objeto, siendo así estas partes independientes las unas de las otras. Los objetos se componen de 3 partes fundamentales: metodos, eventos y atributos.
Decimos que un objeto es una instancia de una clase. Por ejemplo el taxi matrícula BFG-7452 es una instancia de la clase Taxi. Varios objetos (p.ej. taxis) de una misma clase decimos que constituyen instancias múltiples de la clase. Más adelante veremos que tanto una clase como un objeto en Java pueden representar otras cosas además de lo que ahora hemos explicado, pero todo a su tiempo.

Clase.
En resumen una clase no es más que una serie de código que define a todos los elementos relacionados con ella.
Cuando decimos “ave”, sabemos que nos referimos a “algo” con plumas, pico, dos patas, etc. No importa realmente si hemos visto un ave o no, o si tenemos un ave frente a nosotros; entendemos claramente que la palabra “ave” se refiere a alguna cosa que cumple con unas características específicas, se comporta de una forma concreta, etc, etc. No es más que una palabra, pero nos permite clasificar las cosas. Por ejemplo, sabemos que una gallina es un ave y que un perro no es un ave.
La clasificación es algo que hacemos todos los días, a cada momento (entre otras cosas, nos libra de utilizar medias como guantes o bañarnos en el comedor en vez de en la ducha). Cada vez que decimos que algo es alguna cosa, estamos clasificándolo, asociándolo a una clase.
Herencia
la herencia es, después de la agregación o composición, el mecanismo más utilizado para alcanzar algunos de los objetivos más preciados en el desarrollo de software como lo son la reutilización y la extensibilidad. A través de ella los diseñadores pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistente (ya comprobadas y verificadas) evitando con ello el rediseño, la modificación y verificación de la parte ya implementada. La herencia facilita la creación de objetos a partir de otros ya existentes e implica que una subclase obtiene todo el comportamiento (métodos) y eventualmente los atributos (variables) de su superclase.
Es la relación entre una clase general y otra clase más específica. Por ejemplo: Si declaramos una clase párrafo derivada de una clase texto, todos los métodos y variables asociadas con la clase texto, son automáticamente heredados por la subclase párrafo.
La herencia es uno de los mecanismos de los lenguajes de programación orientada a objetos basados en clases, por medio del cual una clase se deriva de otra de manera que extiende su funcionalidad. La clase de la que se hereda se suele denominar clase base, clase padre, superclase, clase ancestro (el vocabulario que se utiliza suele depender en gran medida del lenguaje de programación).
En los lenguajes que cuentan con un sistema de tipos fuerte y estrictamente restrictivo con el tipo de datos de las variables, la herencia suele ser un requisito fundamental para poder emplear el Polimorfismo, al igual que un mecanismo que permita decidir en tiempo de ejecución qué método debe invocarse en respuesta a la recepción de un mensaje, conocido como enlace tardío (late binding) o enlace dinámico (dynamic binding).


INSTANCIA

Se llama instancia a todo objeto que derive de algún otro. De esta forma, todos los objetos son instancias de algún otro, si bien, decíamos que una clase es como la definición de un objeto, pero no es el objeto en sí, del modo como una idea no es una cosa física. Así que para sentarnos necesitaremos convertir esa idea en algo, en un objeto real; a ese objeto lo llamamos instancia.
En un mismo proyecto puedo tener una o más instancias de una misma clase sin problemas.
Cada vez que creamos una nueva instancia, ésta adquiere las propiedades, métodos y eventos de la clase a la que pertenece, sin embargo, cada instancia es independiente de las otras; esto nos da dos ventajas:
Si hago algún cambio en la clase, todas las instancias de esta clase se actualizarán automáticamente; esto nos permite hacer cambios sin tener que ir a cada una de las instancias.
Al ser independientes de las otras instancias, puedo darles valores diferentes sin que afecten a las demás (como tener una silla negra, una roja, una más alta, etc.). Aunque comparten la misma estructura, pueden programarse individualmente, dando versatilidad y flexibilidad al código.

Sobre carga.
 es la capacidad de un lenguaje de programación, que permite nombrar con el mismo identificador diferentes variables u operaciones.
En programación orientada a objetos la sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizan acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.
También existe la sobrecarga de operadores que al igual que con la sobrecarga de funciones se le da más de una implementación a un operador.
El mismo método dentro de una clase permite hacer cosas distintas en función de los parámetros.
Java no permite al programador implementar sus propios operadores sobrecargados, pero sí utilizar los predefinidos como el +. C++, por el contrario si permite hacerlo.

Shadowing.
En la programación de computadoras, sombras variables se produce cuando una variable declarada dentro de un determinado ámbito (bloque de decisión, el método o clase interna) tiene el mismo nombre que una variable declarada en un ámbito exterior. A nivel de los identificadores (nombres, en lugar de variables), esto se conoce como nombre de enmascaramiento. Se dice Esta variable externa a la sombra de la variable interna, mientras que el identificador interno se dice para enmascarar el identificador exterior. Esto puede llevar a confusión, ya que puede no estar claro que los usos posteriores variables del nombre de la variable en sombras se refieren a, que depende de la resolución de nombres reglas del lenguaje.
Uno de los primeros lenguajes de introducir sombras variables fue ALGOL, que introdujo por primera vez bloques de establecer ámbitos. También se le permitió por muchos de los lenguajes de programación derivados, incluyendo C ++ y Java.
El C # lenguaje rompe esta tradición, lo que permite el remedo variable entre un interior y una clase externa, y entre un método y su clase que contiene, pero no entre un si-bloque y su método contiene, o entre las declaraciones de caso en un interruptor de bloque.


Ciclo de las variables.
Automática. Este es el caso de las variables que se declaran dentro de una función, conocidas también como variables locales. Las variables locales automáticas mantienen su valor mientras se esté ejecutando el código de la función en que hayan sido declaradas. Cuando concluye la función, el espacio reservado en la pila se vuelve a poner a disposición del programa, y se pierde el contenido de las variables locales automáticas. Las variables locales (automáticas o estáticas) sólo se pueden utilizar en el código contenido en la función en que están declaradas. 
Estática. Si se antepone la palabra reservada static a la declaración de una variable local, ésa variable pasa a crearse en la zona destinada a datos estáticos; por tanto, el espacio reservado para ella se mantendrá operativo durante toda la ejecución del programa. Por tanto, las variables estáticas se caracterizan porque su valor se mantiene entre ejecuciones de la función, esto es, su valor no se pierde cuando finaliza la ejecución de la función en que hayan sido declaradas. Las variables locales (automáticas o estáticas) sólo se pueden utilizar en el código contenido en la función en que están declaradas 
Global. Si se declara una variable fuera de toda función, la variable es automáticamente estática en el sentido del párrafo anterior, y el espacio reservado para ella se mantiene operativo durante todo el programa, si que se pierda su valor. Además, las variables globales se pueden utilizar en el código de cualquier función del programa, por tanto, su valor se puede leer y modificar desde cualquier función del programa. 
Dinámica. El lenguaje C, entre otros, aporta la posibilidad de reservar espacio para almacenar variables mientras se está ejecutando el programa. Las variables que se crean de esta manera, denominadas dinámicas, siguen existiendo mientras el programa no decida lo contrario, esto es, las variables reservadas dinámicamente se pueden crear y destruir al arbitrio del programador. La memoria utilizada para una variable dinámica, cuando ésta es destruida, puede reutilizarse para crear otras variables. El acceso a las variables dinámicas se realiza a través de otras variables de un tipo especial denominado puntero (pointer). 





Referencias 
http://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=639:static-final-en-java-palabras-clave-variables-de-clase-o-campos-estaticos-y-constantes-ejemplos-cu00673b&catid=68:curso-aprender-programacion-java-desde-cero&Itemid=188
http://codejavu.blogspot.mx/2013/05/conceptos-de-programacion-orientada.html
http://profesores.fi-b.unam.mx/cintia/Lenguaje_C.pdf
https://es.wikipedia.org/wiki/Sobrecarga_(inform%C3%A1tic
