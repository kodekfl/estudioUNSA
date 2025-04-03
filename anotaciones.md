CONCEPTOS BASICOS

Diferencia entre informacion y entre datos

Que es un dato

Un dato es una unidad singular de conocimiento, es la minima cantidad de informacion. Podemos extraerle informacion cuando lo contextualicemos.

Informacion es un conjunto de datos que nos va a dar conocimientos, que nos va a permitir resolver necesidades y conflictos.

Una bases de datos es una coleccion de datos organizada en un sistema, como por ejemplo una bases de datos podria ser una libreta donde guardamos los contactos de las personas, ya que almacenamos sus numeros de manera organizada por la inicial del nombre de esa persona.

La tecnologia que nos va a permitir gestionar estos datos sera un SGBD/DBMS es un sistema gestor de base de datos o un Data base managment system.
Los gestores de bases de datos estan optimizados para almacenar y gestionar grandes cantidades de datos.

TIPOS DE BASES DE DATOS

Los sistemas gestores relacionales y los no relacionales se diferencian porque usan bases de datos SQL o NoSQL

Las bases de datos relaciones se caracterizan por ser una coleccion de datos organizados en diferentes tablas. La tabla es el elemento principal en una bases de datos relacional y es muy parecida a una hoja de calculo, osea que se van a organizar en filas y en columnas. Estas mismas van a estar relacionadas entre si. Para poder acceder y alterar de manera organizada estos datos vamos a usar el lenguaje SQL. Para ello vamos a usar distintos comandos que nos ofrece SQL para poder manipularlos.

El objetivo de este curso es disenar las bases de datos

Cada tabla va a elegir a un campo como identificador unico, asi las tablas pueden establecer relaciones con otras tablas

Las bases de datos no relacionales tienen datos que estan estructurados de una manera mas especifica, y que no necesariamente necesitan ser relacionadas.
Cada entidad va a funcionar de manera independiente y son mas sencillas que las bases de datos relacionales. Se pueden tener datos duplicados.

Las bases de datos relacionales demoran mas tiempo en sus consultas debido a las estructuras que poseen sus datos, en cambio las bases de datos no relacionales son mas rapidas debido a que ofrecen poder obtener sus datos de manera rapida y accesible

Podemos ver a los distintos tipos de bases de datos de la siguiente forma:

    Bases de datos relacionales: Es como una tabla de excel, donde tenemos columnas y filas
    Cada campo esta estructurado como columnas pero los datos estan estructurados de manera horizontal.

    Bases de datos no relacionales: Son como distintos documentos JSON o un documento con un solo objeto html siendo modificado por CSS como por ejemplo

        html{
            background-color: black;
            color: white;
            text-align: center;
        }

CUANDO USAR SQL Y CUANDO NOSQL

Si tenemos la certeza de que todos los datos se van a estructurar de la misma manera y que necesitaremos en algun momento relacionarlos, como podria ser una base de datos de un supermercado, deberiamos usar SQL para la bases de datos relacionales

En cambio si nuestros datos no estamos seguros de que todos van a tener la misma estructura, que no vamos a necesitar relacionarlos. Por ejemplo una bases de datos para coleccionar estadisticas de distintos deportistas o una base de datos de publicaciones de tiktok ya que no siempre van a ponerle hashtags no siempre van a poner una descripcion y no necesitamos relacionarlo con otro video

La eleccion de una bases de datos correcta es importante

La diferencia mas grande entre ambas bases de datos es basicamente la forma en la que se estructura su informacion, mientras uno lo hace de manera organizada otro tiene una estructura mas propia

Ventajas SQL

Cuando necesitemos relaciones estructuradas
Cuando requereamos datos estructurados

Ventajas NoSQL

Cuando la bases de datos necesite ser escalable, osea que va a crecer rapidamente y en gran cantidad en cuanto datos
Cuando no requieran estructura rigida
Cuando tengamos aplicaciones en tiempo real y requeramos de la velocidad

ENTIDADES Y ATRIBUTOS

Que es una entidad

Va a ser un objeto de la vida real que pretendemos controlar dentro de la bases de datos, que vamos a almacenar su informacion. Y sus caracteristicas van a ser informacion, las caracteristicas pueden llegar a ser sus propiedades como objeto, y estas mismas propiedades se les llama atributos

Cuando hagamos una bases de datos vamos a hacer una lista de cuales entidades van a entrar en nuestra bases de datos

TIPOS DE ENTIDADES

Entidades de Datos Una tabla de personas

Entidades Catalogos Una tabla que almacene informacion precargada de Estudiantes, administrativo, profesores. Un mejor ejemplo es cuando tenemos que llenar un formulario y ponemos de que pais somos, ya hay una lista cargada con los datos de los paises, entonces el catalogo es PAISES pero tiene tambien datos cargados como Argentina, Mexico, Uruguay, etc

Entidades Pivotes Son las que nos van a permitir tener relacion, tambien se les llama entidad de relacion. Un profesor esta asignado a una materia o a mas. Entonces podemos hacer relaciones entre el profesor y las materias. Por ejemplo que la materia diga que profesor la dicta y podemos ir al dato profesor, pero cuando vayamos al dato profesor tambien podemos ver que materias dicta el.


TIPOS DE DATOS

