¿Cuál es la diferencia fundamental entre let y const en JavaScript?

    ## La variable let es una variable local, que puede cambiar su valor
    durante la ejecucion del programa, y const pues un valor constante que 
    no podemos mutar su informacion.

¿Qué significa que una variable declarada con let sea mutable(que se pueda cambiar su valor)?

    ## Su valor se puede estar modificando a nuestra necesidad durante la 
    ejecucion de nuestro programa.

¿Por qué es importante entender la diferencia entre let y const al programar en JavaScript?

    ## La variable let funcionara de manera loca y puede ser mutable mientras que
    const nos a dar la seguridad de que si alguien o algo cambia su valor
    nos arrojara un error.

¿Cuál es el problema principal con el uso de "var" en JavaScript?

    ## Al usar un var no limitamos su uso en el codigo por lo que podemos generar errores de manera global, ya que su valor puede ser cambiado en alguna
    fraccion de nuestro codigo y asi dar problemas en la salida de datos.

¿Qué diferencias existen entre var y let/const en términos de ámbito (scope)?

    ## Var tiene alcance alcance global, let  se puede actualizar y declarar dentro de su alcance y const mantendra un valor global dentro del scope 
    donde se declaro.

¿Cuáles son los cinco tipos de datos primitivos vistos en el curso de JavaScript?

    ## string, boolean, undefined, null, symbol, number.

¿Cuál es el tipo de dato primitivo que se utiliza para representar un valor verdadero o falso?

    ## boolean

¿Qué tipo de dato primitivo se utiliza para representar valores que no están definidos o que están ausentes?

    ## undefined

¿Cómo se define una cadena de texto (String) en JavaScript?

    ## declarar como una variable e igualarlo a un mensaje. Como:
    const ejemplo = 'Esto es una cadena de texto';

¿Qué es una función en programación y para qué se utiliza?

    ## Un encapsulamiento de codigo que podremos reutilizar durante nuestro 
    programa al mandar a llamar nuestra funcion

¿Cómo se define una función en JavaScript? Proporciona un ejemplo básico(no utilizar function).

    ## const funcion = ("algo que se puede llamar") =>{
        elementos de la funcion
    }
    
    const a = ( n ) => {
        return n;
    }

    const usuario = (//acá van los parametros que declararemos) => {
    }

¿Qué es un parámetro en el contexto de las funciones?

    ## es un valor que tomara cuando llamemos a nuestra funcion y le enviemos 
    su argumento, el parametro es una variable que solo existira dentro de nuestra
    funcion.

¿Qué es un argumento en el contexto de las funciones?

    ## Es el valor que se enviara a nuestra funcion en los parentesis;

¿Cuál es la relación entre los parámetros y los argumentos en una función?

    ## Que para que funcionen los parametros necesitamos de los argumentos, pero en ciertas ocaciones no es asi, ya que los parametros pueden tener 
    valores por defecto.

¿Cuál es la diferencia entre pasar una variable por valor y pasarla por referencia?

    ## Los datos que pasan por valor (primitivos) podemos cambiarlos o copiarlos 
    a diferentes variables sin alterar el original, sin embargo las referencias se modifican si no se rompe esa referencia es decir si copiamos una funcion, objeto, clase no estamos copiando su valor si no la referencia al objeto o dato completo y si se modifica la copia, modificaremos el original.

¿Qué es un objeto en el contexto de la programación?

    ## Es un objeto que tiene propiedades y atributos.

¿Cómo se define un objeto en JavaScript?

    ## objeto = {
        carlos: 'amigo'
    };

    objeto = {
        elemento1:"",
        elemento2:0
    }

    const nameObject {
        //características del objeto
    }

    const carro = {
        marca: mazda,
        modelo: 2016,
        color: azul
    }

¿Cómo se accede a las propiedades y los métodos de un objeto en JavaScript?

    ## usando el nombre del objeto y . usando el nombre de la propiedad
    objeto.elemento1

¿Qué es un array en programación y para qué se utiliza?

    ## Es una coleccion de datos, pueden ser de la misma familia o mixtos.

¿Cómo se define y se crea un array en JavaScript?
    
    ## const array=["hola",2,3,5];
       
       array = [];

       const alumnos = [
            {
            nombre: "Juan",
            edad: 21,
            carrera: "Ing. Sistemas",
            numMaterias: 6,
            calificaciones: [7, 8, 9, 6, 10, 7]
            }
        ];
        const frutas= ["manzana", "platano", "pepino", "mango"];

¿Cómo se accede a los elementos de un array en JavaScript?

    	## hay varias formas de hacerlo , si sabemos la posicion de los objeto podemos hacer como array[0]; mostrando la primera propiedad,o si se requiere podemos hacer con un ciclo for.

¿Cómo se realiza la iteración sobre los elementos de un array en JavaScript?

    ## for(let i=0;i<array.lenth;i++){
        array[i]
    }

    forEach()


¿Cómo se define una clase en JavaScript?

    ## Con la variable class, y poniendo los elementos que tiene dicha clase

¿Cómo se crea un objeto a partir de una clase en JavaScript?

    ## con una instancia de clase new Class();

¿Qué es la estructura condicional "if" en programación y para qué se utiliza?

    ## Evalua datos booleanos, si son true o false, evaluar sentencias;

¿Cuál es la importancia de los bloques "else" y "else if" en una estructura condicional "if"?

    ## Para evaluar diferentes condiciones tanto if y else if y si no se cumplen 
    nos vamos al else;

¿Cuál es la diferencia entre los operadores "==" y "===" en una condición "if"?

    ## 5 == "5" true Evalua el valor absoluto
        5 === "5" false Evalua estrictamente el valor y tipo de dato
