Explicar con sus propias palabras:

1. Diseño de software.-

Viene hacer el "como" se va hacer la aplicacOn , se centra en los requerimientos no funcionales y los temas mas abstractos en ver la aqruitectura y como se va a orquestar el negocio.

2. Favorecer la composición de objetos frente a la herencia de clases.

se puede favorecer la composicion de objetos con la herencias de clases, ya que teniendo una clase maestra se puede heredar sus metodos. Por ejemplo si tenemos una clase Persona y hemos definido sus propiedades y metodos luego definimos una clase alumno esta puede heredar los metodos de la clase padre y crear los metodos que se van a necesitar de la clase hija.

3. Drivers arquitecturales y conceptos de diseño.-

En los drivers arquitecturaes se ven cuales son los atributos de calidad, cual es la funcionalidad principal, los propositos del diseño, tambien se ve las restricciones (todo esos inputs tiene el arquitecto) en base a eso se debe modelar los artefactos. Al final despues de ver la arquitectura se termina en el codigo.
Los CONCEPTOS DE DISEÑO se refiere a que todo diagrama de arqitectura de software debe de tener su leyenda (flechas). Los productos pueden ser un paquete de software. Hay conceptos de diseño para analytics. Frameworks: hibernate, netcore

4. Domain Driven Design (DDD).-

DISEÑO DIRIGIDO POR DOMINIO, usa los bounded context (bc) que es un microservicio el cual maneja un lenguaje ubicuo. La union de bounded context agrega valor al negocio.En una organizacion existen n bounded context con n servicios.Los expertos del dominio ayuda a identificar los bounded context.En el dominio puro se tiene estado y comportamiento. El lenguaje obicuo lo deben entender los expertos del negocio y los miembros del equipo para ello se hace el even storming y se llega a un acuerdo. No se pueden hacer join en bounded context porque tienen bases de datos diferentes, lo que se hace se crea un evento y el se suscribe y entra a ese evento.

5. Comand Query Responsibility Segregation (CQRS).-

CQRS es un patrón arquitectural de alto nivel. CQRS es para diferentes bases de datos. Puedo tener una base de datos nos relacional (acpeta transacciones) y de escritura (create, update, delete) base de datos relacional.

6. Event Driven Architecture.-











