# Unidad 2
### Reflexiona sobre 3 habilidades técnicas asociadas a la fase de Requerimientos. Indica su importancia dentro del ciclo de Ingeniería de Requerimientos. Incluye argumentos de tu selección. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.

De acuerdo con la fase de requerimientos, el equipo de desarrollo debe tener integrantes con las capacidad o habilidades.

* **Comunicación eficiente:**

Una persona debe tener la habilidad, tanto de transmitir la idea o información, así como de recibirla. Un ejemplo en la fase de requerimientos de gran importancia es en la obtención de información para el desarrollo del proyecto que se realice a algún cliente. No es lo mismo que una persona con conocimiento técnico le hable con tecnicismos complejos a una persona que tenga poco o nulo conocimiento del software, por ello es importante que los integrantes sepan comunicarse en el mismo plano para que la transmisión de ideas sea eficiente, esto puede en muchos casos ahorrar tiempo, trabajo innecesario, dinero y el posible descontento del cliente o pérdida del mismo proyecto.

* **Buen cuestionamiento y análisis de los requerimientos:**

Cuando se analizan los requerimientos y las exigencias del cliente, debemos cuestionar y pensar más allá de la información que recibimos, capaz de encontrar inconsistencias o ambigüedades en los requisitos, expectativas o pedidos a realizar en el proyecto o en los mismos requisitos planteados por el equipo de desarrollo. Ejemplo: si se pide realizar por parte de un posible cliente una aplicación de pedidos a domicilio de comida, debemos preguntarnos ¿Sería un requerimiento obligatorio o no que los usuarios tengan que registrarse para poder usar la aplicación?, ¿pediremos número celular o correo para registrarse?, ¿el cliente quiere que sea una aplicación para celulares o en sitios web?, etc.

* **Abstracción visual:**

Tenemos la certeza de que poder representar esas ideas en ocasiones abstractas de manera visual es una habilidad indispensable sobre todo en la hora de comunicarse con el cliente, va de la mano con la habilidad de la comunicación. En ocasiones las palabras no alcanzan a transmitir de toda una idea, por ello es importante saber plasmar esas ideas en algún objeto visual que el cliente pueda entender. A lo mejor el cliente trata de pedir que su tienda online tenga un buscador de productos, pero no es capaz de expresar bien lo que quiere. Por ello nosotros con un dibujo o mostrando un ejemplo de una barra de búsqueda puede resultar necesario para que el usuario confirme que ambos nos referimos a lo mismo.

Un ejemplo de estas habilidades, más bien de falta de estas en habilidades en nuestro proyecto (aplicación que funciona como traductor de lenguaje de señas mediante la cámara de una teléfono inteligente y que aparte tiene la función de enseñar este mismo lenguaje) es que nuestro equipo de desarrollo no se cuestionó más allá de los requisitos que podría tener el proyecto/diseño, un ejemplo es que a la hora del diseño nunca nos planteamos si la aplicación iba a tener una interfaz de registro de sesión, es más, nunca nos planteamos si iba a tener esa función de registro de usuario, lo cual nos llevó a documentarlo, aunque en nuestro caso la única consecuencia fue que tuvimos aumentar un poco de tiempo al proceso de realizar la documentación; sin embargo, en un caso real, eso pudo haber atrasado el proyecto así como aumentar los costos del mismo para entregar el trabajo en la fecha estimada.

### Explica de forma clara la diferencia entre Especificación de Casos de Uso vs Historias de Usuario. Adicionalmente indica en qué casos se recomiendan el uso de cada una de estas herramientas. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.

La especificación de casos de uso y las historias de usuario son dos técnicas utilizadas en el desarrollo de software para capturar los requisitos funcionales de un sistema.

**Especificación de casos de uso**

*Ventajas*

* Proporciona una descripción formal y completa de los requisitos funcionales del sistema.
 
* Es útil para comunicar los requisitos al cliente y a los desarrolladores.

* Puede ayudar a identificar riesgos y problemas potenciales en el diseño del sistema.

*Desventajas*

* Puede ser laborioso y complejo de desarrollar.

* Puede ser difícil mantener la especificación actualizada a medida que cambian los requisitos.

**Historias de usuario**

*Ventajas*

* Son fáciles de entender y comunicar.
  
* Fomentan la colaboración entre el cliente y los desarrolladores.
  
* Son flexibles y pueden adaptarse a los cambios en los requisitos.

*Desventajas*

* Pueden no proporcionar una descripción completa de los requisitos funcionales del sistema.
  
* Pueden ser difíciles de priorizar y estimar.
  
* Elección de la técnica

**¿Cuál usar?**

Para concluir, determinamos que la elección de utilizar la especificación de casos de uso o las historias de usuario depende de las necesidades específicas del proyecto. La especificación de casos de uso se aprovecharía de una mejor manera para proyectos que requieren una descripción formal y completa de los requisitos funcionales. Las historias de usuario, por otro lado, son una buena opción para proyectos que requieren una colaboración estrecha entre el cliente y los desarrolladores, o proyectos en los que los requisitos pueden cambiar con frecuencia.

**Ejemplo (caso de uso) con base en nuestra experiencia con el login del proyecto:**

Caso de uso: Iniciar sesión

Actor: Usuario

Precondiciones: El usuario debe tener una cuenta registrada en el sistema.

Flujo principal:

* El usuario ingresa su nombre de usuario y contraseña.
* El sistema valida los datos de inicio de sesión.
* Si los datos son correctos, el sistema inicia sesión al usuario.

Flujo alternativo:

Si los datos de inicio de sesión son incorrectos, el sistema muestra un mensaje de error.

Postcondiciones: El usuario está autenticado en el sistema.

### Selecciona un producto resultante de la etapa de diseño (Arquitectura, Base de Datos, Interfaz de Usuario, Procedimientos). Explica de forma clara y sintética algún método asociado al producto resultante. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.

Para nuestro proyecto, el diseño de software es una parte fundamental para su éxito, ya que nuestra aplicación está diseñada para un público menos familiarizada con tecnología. Por poner un ejemplo, la interfaz de usuario, definida como el medio que permite al usuario interactuar con una máquina o dispositivo (Thimbleby, 1990). Al requerir de un teléfono inteligente para ingresar a la aplicación, estaríamos utilizando una interfaz táctil para ofrecer una respuesta de entrada (mediante la pantalla o cámara) y una de salida (feedback) (Li et al., 2009).

En el caso de nuestro proyecto, utilizamos wireframes en Figma para crear un boceto del diseño de nuestra aplicación con una fidelidad media para lograr observar algún problema o deficiencia en nuestra interfaz de usuario. Durante el mismo, logramos observar que era poco intuitivo el cómo llegar la pantalla de actividades entre tantas pantallas de opciones y otras funciones. Decidimos implementar una barra inferior con pestañas para el inicio y ajustes, lo cual favorece una fácil interacción con la aplicación.

### Investiga sobre un método o técnica que permita incluir pruebas de forma efectiva en el proceso de desarrollo. ¿A partir de qué etapa pueden ser consideradas las pruebas?. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.

Las pruebas de regresión se enfocan en asegurar que los cambios no afecten negativamente el funcionamiento existente. Se llevan a cabo después de cambios significativos o al actualizar el software para garantizar su correcto desempeño. Estas pruebas también se realizan al implementar una aplicación en un nuevo entorno y de manera periódica para detectar problemas originados por cambios previos.

Se inician identificando y documentando los requisitos, definiendo casos de prueba y seleccionándolos según su importancia. Luego, se crea una suite de pruebas considerando las áreas modificadas y las invariables. Posteriormente, se ejecutan los casos de prueba y se analizan los resultados para detectar discrepancias. Finalmente, se genera un informe con los resultados para evaluar la calidad del producto y mejorar en áreas específicas.

Es clave considerar las pruebas desde las etapas tempranas del desarrollo para detectar y solucionar problemas rápidamente, incluso con cambios importantes en el proceso de desarrollo.

Un ejemplo basado en nuestra experiencia fue la comprobación del repositorio cuando se hacían grandes cambios desde nuestras bifurcaciones, así como durante la realización de nuestro prototipo de la interfaz cuando se agregaba una nueva sección en la herramienta figma.

### Utilizando fuentes confiables, establece las habilidades/conocimientos/competencias míninas indispensables que un Ingeniero de Software debe incluir en su formación académica para el desarrollo de Aplicaciones de Software Seguras.

Un ingeniero de software es un profesionista que requiere de muchas habilidades técnicas, conocimiento, valores, competencias etc. Su formación académica es crucial para poder ser un buen profesionista que sea capaz de desarrollas aplicaciones de software seguras, por lo que se debe tener los siguientes puntos a consideración en la formación:

**Habilidades** 

•	Uso de softskills.  

•	Trabajo en equipo.

•	Comunicación constante con el cliente y otros miembros del equipo.

**Competencias** 

•	Capacidad de análisis, síntesis, organización y planificación.

•	Comunicación oral y escrito, tanto en español como en inglés. 

•	Uso adecuado de las TICs y comunicaciones.

•	Análisis y resolución de problemas. 

•	Autodidacta, adaptación a situaciones nuevas.

•	Creatividad, liderazgo, iniciativa y respeto. 

•	Interés por el desarrollo de software de calidad.

•	Responsabilidad social, ética y moral.

•	Desarrollo de soluciones por medio del análisis de los usuarios y datos.

**Conocimientos** 

•	Codificación, lenguajes de programación. 

•	Comprensión de las pruebas de software y depuración. 

•	Gestión del ciclo de vida del software.

•	Control de versiones, computación en la nube, gestión de proyectos.

•	Sistemas operativos.

---
# Unidad 3
### Asumiendo que los valores descritos en el acuerdo del "Manifiesto para el desarrollo ágil de software", causan conflicto en el proceso de desarrollo reflexione y describa de manera clara posibles soluciones utilizando como base el proyecto que están desarrollando en equipo.
Existen 4 valores del manifiesto ágil, el primero de ellos: **Individuos e interacción sobre procesos o herramientas**, este valor entra en conflicto cuando no hay una buena comunicación del equipo; sin embargo, algunas soluciones son dar más peso a las interacciones con el equipo de manera presencial (de ser posible) para que la comunicación sea cara a cara y de este modo pueda haber un mayor entendimiento entre todos, lo que ayuda igual a entender nuestras ideas y motivaciones para poder salir adelante como equipo; no obstante, también se pude recurrir a herramientas que faciliten la comunicación rápida o a distancia entre el equipo en caso de que resulte imposible una reunión física con el equipo. El segundo valor es: **Software funcionando sobre documentación exhaustiva**, cuando este valor entra en conflicto es porque no se le está dando la prioridad o importancia al funcionamiento del software, es por eso que las soluciones son enfocarse más en que funcione el software y no tanto en la documentación, sino que solo se documente las cosas verdaderamente relevantes y fuera de eso el equipo verifique constantemente mediante retroalimentaciones que el software esté funcionado correctamente. El tercer valor es:  **Colaboración con el cliente sobre negocios de contratos**, si hay conflictos respecto a este valor del manifiesto ágil, las soluciones que se pueden tomar en cuenta son mejorar o mantener constantemente la comunicación desarrolladores-clientes, esto de manera que ambas partes puedan colaborar y generar una relación de confianza, y después de ello, llegar a una negociación o acuerdo. El cuarto y último valor es **Responder al cambio sobre seguimiento a un plan**, precisamente este es un aspecto muy importante y que una metodología ágil proporciona al desarrollo de software, ya que puede haber un plan inicial; sin embargo, es muy común que sobre la marcha vayan cambiando las necesidades del cliente u otros aspectos que involucren un desvío del plan inicial, por ello es muy importante poder adaptarse a los cambios y ajustar nuestro proyecto de software a estos.
### De las metodologías ágiles (Scrum, XP, Kanban, Design sprint, etc.), selecciona dos de ellas e identifica al menos tres de los principios de agilidad de software presentes en dichas metodologías. Explique también de qué manera pueden integrarse esos principios de agilidad en su proyecto de equipo, suponiendo que sigue una metodología ágil.
**Metodologías ágiles: Scrum y Kanban**

* **Satisfacer a los clientes a través de la entrega temprana y continua (principio 1):**

Ambas metodologías ágiles se caracterizan por su flexibilidad en el desarrollo de software, esto es porque permiten hacer modificaciones repentinas en cualquier etapa del ciclo de vida del software en el que este se encuentre, de manera que se pueda hacer cambios y mejoras al software sin la necesidad de seguir estrictamente un proceso lineal que retrase el desarrollo y la entrega del producto, mejorando la eficiencia y eficacia del proyecto. Por esta razón las entregas al cliente son más constantes y de buena calidad para la satisfacción y aprobación del cliente.
En nuestro proyecto de software integramos este principio al trabajar en equipo de manera eficiente mediante Sprints, cada uno con sus respectivos avances esperados y un periodo de tiempo definido, pero suficiente para completar dichos avances. Asimismo, nos apoyamos de la metodología Kanban por medio de la creación de un tablero visual que nos ayuda a tener total control y conocimiento de las tareas realizadas y por realizar para que podamos cumplir todas en el tiempo establecido y no exista atrasos en las entregas.

* **Cambios en los requerimientos (principio 2):**

En el transcurso del desarrollo de software, se van generando nuevas necesidades del cliente, las cuales el software final tiene que satisfacer y para ello, debe haber una actualización o implementación de requerimientos que ofrezcan una idea más clara de lo que tiene que incluir el software atendiendo siempre los intereses del cliente. Estas metodologías ágiles permiten los cambios en los requerimientos debido a su adaptabilidad.
Este principio lo implementamos en el proceso de desarrollo de software, concretamente durante la fase de diseño. El uso de una metodología ágil permitió al equipo regresar a la fase de requerimientos para modificar y agregar algunos tras notar que hacían falta para el diseño del programa, posteriormente, seguimos con el diseño y lo adaptamos conforme a los nuevos requerimientos establecidos. De esta manera no se perdió tiempo y pudimos ajustar nuestro software a las necesidades que fueron surgiendo en el momento. 

* **La simplicidad (principio 10):**

Las metodologías ágiles buscan entregar un software funcional y de calidad en el menor tiempo posible, es por ello que la simplicidad es un aspecto importante a considerar durante el desarrollo de software, ya que ahorra trabajo innecesario, tiempo y recursos; además de que aumenta la calidad del software y el cliente obtiene lo que desea sin retrasos e incluso de manera más pronta.
Este principio podemos integrarlo en nuestro proyecto en la etapa de diseño, ya que hasta esa fase llega el proyecto, pues no hay codificación. En nuestro caso el diseño tiene que cumplir con los requerimientos previamente establecidos y con ciertas características que dan lugar a interfaces intuitivas y llamativas; sin embargo, para cumplir con lo anterior no es necesario un diseño complejo, ya que incluso puede verse saturada la interfaz de tantos elementos o colores, sino que la simplicidad en el diseño supone un ahorro de tiempo, interfaces más ordenadas, cómodas y fáciles de usar para los usuarios, y lo más importante, sigue cumpliendo con los requerimientos y es funcional.

--- 
# Referencias

Beck, K., & Cunningham, W. (1989). A technique for specifying user interface requirements. In Proceedings of the ACM SIGCHI Conference on Human Factors in Computing Systems (pp. 313-320). New York, NY: ACM.
Jacobson, I. (1992). 

Object-oriented software engineering: A use case driven approach. New York, NY: Addison-Wesley.

QAlified. (2023, 10 de octubre). ¿Qué son las Pruebas de Regresión? Cómo hacerlas, herramientas y más. QAlified. https://qalified.com/es/blog/pruebas-regresion/
