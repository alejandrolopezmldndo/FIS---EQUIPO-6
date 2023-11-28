# Evolución de los requerimientos 

En este apartado se muestran los requerimientos funcionales y no funcionales de la segunda y tercera entrega para facilitar su comparación y de esta manera hacer más notorios los cambios presentes y cómo estos requerimientos han ido evolucionando. Para esta última entrega, nuevos requerimientos de ambos tipos (funcionales y no funcionales) fueron añadidos y, de igual manera, hubo un cambio en la priorización (por el método MoSCoW) de algunos requerimientos no funcionales ya existentes desde la segunda entrega.  

Entre los cambios más significativos en los requerimientos de tipo funcional, se añadieron los requerimientos: __RF-02, RF-03, RF-09, RF-11__. De los cuales el RF-02 y RF-03 forman parte del proceso necesario por parte del usuario para acceder a la aplicación con un perfil ya existente, estos requerimientos anteriormente estaban considerados dentro del RF-01 por la relación que guardan entre ellos; sin embargo, como cada uno exige al sistema realizar distintas funciones, se optó por separalos. Por otra parte, en los requerimientos de tipo no funcionales, se añadieron los siguientes: __RNF-01, RNF-07__.

---

# Requerimientos de la Tercera Entrega:
## __Requerimientos funcionales__

| RF-01 | Creación de un usuario | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Para acceder a la aplicación móvil, el usuario antes deberá registrarse proporcionando un nombre, correo y una contraseña. | 

| RF-02 | Inicio de sesión | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | El sistema deberá guardar los datos previamente ingresados por el usuario al registrarse en la aplicación para que al abrirla se inicie la sesión automáticamente, o bien, de ejecutarse en otro dispositivo móvil, el usuario sólo necesite introducir su correo y contraseña. | 

| RF-03 | Recuperar contraseña | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | El sistema permite al usuario recuperar y/o modificar su contraseña por una nueva. | 

| RF-04 | De Lengua de Señas Mexicanas al español | 
|----------|:----------:|
| Prioridad MOSCOW | Must have |
| Descripción | Por medio de la cámara del dispositivo móvil, la aplicación deberá reconocer los movimientos y gestos propios de la Lengua de Señas Mexicana y traducirlos al idioma español como subtítulos. | 

| RF-05 | Subtítulos | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | Los subtítulos generados a partir de la traducción de Lenguaje de Señas Mexicanas al español deberán ser claros, legibles, coherentes y de preferencia emplear las palabras o sinónimos más correctos en la interpretación de cada oración. |

| RF-06 | Del español a Lengua de Señas Mexicanas | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | El usuario podrá dictar y escribir palabras u oraciones en español y el programa lo traducirá al Lenguaje de Señas Mexicanas por medio de videos o GIFS. | 

| RF-07 | Apartado de Lecciones | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación contendrá un apartado específico cuyo contenido serán varias lecciones en las que el usuario aprende distintas palabras y oraciones en Lengua de Señas Mexicanas mediante la imitación de una animación que aparece en pantalla que realiza los movimientos de manos y gestos correspondientes a dicha palabra. | 

| RF-08 | Retroalimentación de las Lecciones | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Durante las lecciones, la aplicación retroalimentará al usuario con respecto a que tan acertados fueron sus movimientos y gestos realizados, indicando así, sus aciertos y errores. | 

| RF-09 | Asignación de medallas en las lecciones | 
|----------|:----------:|
| Prioridad MOSCOW | Could have | 
| Descripción | Al terminar una lección, el sistema otorgará una medalla de oro, plata o bronce según la puntuación obtenida en dicha lección. | 

| RF-10 | Eficaz | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación debe redireccionar al usuario al sitio correcto cuando presiona un apartado. | 

| RF-11 | Avisos de la cámara | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | Cuando la cámara no esté bien situada (enfocando cabeza y torso de la persona), el sistema avisará al usuario de que la cámara se encuentra posicionada incorrectamente. | 


## __Requerimientos no funcionales__

| RNF-01 | Dispositivos | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación sólo podrá ejecutarse en dispositivos móviles Android y iOS. | 

| RNF-02 | Optimización de la Aplicación | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación deberá ejecutarse de manera óptima. | 

| RNF-03 | Seguridad del usuario | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Para garantizar la seguridad del usuario, la aplicación sólo pedirá permiso para el uso del micrófono y la cámara cuando se abra la aplicación. | 

| RNF-04 | Interfaz accesible | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | El diseño de la aplicación deberá ser llamativo, intuitivo para el usuario y con los distintos apartados ordenados para facilitar su uso. | 

| RNF-05 | Facilidad de mantenimiento | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | Durante el desarrollo de la aplicación se debe considerar los aspectos de cambio y el tipo de documentación que permita la facilidad de los futuros mantenimientos. | 

| RNF-06 | Usabilidad de la cámara | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La cámara deberá enfocar desde la cabeza hasta el torso de la persona que utiliza el Lenguaje de Señas Mexicanas para el correcto reconocimiento de los movimientos y gestos realizados. | 

| RNF-07 | Redacción inmediata | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | Al hacer uso del micrófono, el programa escribe al momento lo que está siendo dictado por el usuario. | 

| RNF-08 | Instantaneidad | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | En la medida de los posible, el programa deberá generar los subtítulos en español y los videos en lenguaje de señas rápido y en tiempo real. | 

| RNF-09 | Conexión Wi-Fi | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | El dipositivo móvil en el que se quiera abrir la aplicación deberá estar conectado a una red Wi-Fi, de modo que se pueda hacer uso de la aplicación. | 

| RNF-10 | Límite de palabras | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Al usar el traductor de español a Lengua de Señas Mexicanas, la aplicación permitirá introducir un límite de 140 palabras. | 

---

# Requerimientos de la Segunda Entrega:
## __Requerimientos funcionales__
| RF-01 | Creación de un usuario | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Para acceder a la aplicación móvil, el usuario antes deberá registrarse proporcionando un nombre, correo y una contraseña. | 

| RF-02 | De Lengua de Señas Mexicanas al español | 
|----------|:----------:|
| Prioridad MOSCOW | Must have |
| Descripción | Por medio de la cámara del dispositivo móvil, la aplicación deberá reconocer los movimientos y gestos propios de la Lengua de Señas Mexicana y traducirlos al idioma español como subtítulos. | 

| RF-03 | Subtítulos | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | Los subtítulos generados a partir de la traducción de Lenguaje de Señas Mexicanas al español deberán ser claros, legibles, coherentes y de preferencia emplear las palabras o sinónimos más correctos en la interpretación de cada oración. |

| RF-04 | Del español a Lengua de Señas Mexicanas | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | El usuario podrá dictar y escribir palabras u oraciones en español y el programa lo traducirá al Lenguaje de Señas Mexicanas por medio de videos o GIFS. | 

| RF-05 | Apartado de Lecciones | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación contendrá un apartado específico cuyo contenido serán varias lecciones en las que el usuario aprende distintas palabras y oraciones en Lengua de Señas Mexicanas mediante la imitación de una animación que aparece en pantalla que realiza los movimientos de manos y gestos correspondientes a dicha palabra. | 

| RF-06 | Retroalimentación de las Lecciones | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Durante las lecciones, la aplicación retroalimentará al usuario con respecto a que tan acertados fueron sus movimientos y gestos realizados, indicando así, sus aciertos y errores. | 

| RF-07 | Eficaz | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación debe redireccionar al usuario al sitio correcto cuando presiona un apartado. | 


## __Requerimientos no funcionales__

| RNF-01 | Optimización de la Aplicación | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La aplicación deberá ejecutarse de manera óptima en dispositivos móviles Android y iOS. | 

| RNF-02 | Seguridad del usuario | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Para garantizar la seguridad del usuario, la aplicación sólo pedirá permiso para el uso del micrófono y la cámara cuando se abra la aplicación. | 

| RNF-03 | Interfaz accesible | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | El diseño de la aplicación deberá ser llamativo, intuitivo para el usuario y con los distintos apartados ordenados para facilitar su uso. | 

| RNF-04 | Facilidad de mantenimiento | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Durante el desarrollo de la aplicación se debe considerar los aspectos de cambio y el tipo de documentación que permita la facilidad de los futuros mantenimientos. | 

| RNF-05 | Usabilidad de la cámara | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | La cámara deberá enfocar desde la cabeza hasta el torso de la persona que utiliza el Lenguaje de Señas Mexicanas para el correcto reconocimiento de los movimientos y gestos realizados. | 

| RNF-06 | Instantaneidad | 
|----------|:----------:|
| Prioridad MOSCOW | Should have | 
| Descripción | En la medida de los posible, el programa deberá generar los subtítulos en español y los videos en lenguaje de señas rápido y en tiempo real. | 

| RNF-07 | Conexión Wi-Fi | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | El dipositivo móvil en el que se quiera abrir la aplicación deberá estar conectado a una red Wi-Fi, de modo que se pueda hacer uso de la aplicación. | 

| RNF-08 | Límite de palabras | 
|----------|:----------:|
| Prioridad MOSCOW | Must have | 
| Descripción | Al usar el traductor de español a Lengua de Señas Mexicanas, la aplicación permitirá introducir un límite de 140 palabras. | 
