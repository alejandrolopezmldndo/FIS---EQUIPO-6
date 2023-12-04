# Estimación


# Modelos de Calidad
De acuerdo con Constanzo, M. (2014) los estándares o modelos de calidad en la ingeniería de software son conjuntos de criterios que orientan el desarrollo. Estos estándares aseguran la uniformidad en los procesos y sirven como guía para alcanzar tanto la productividad como la calidad.
## Modelo de calidad: Boehm
De acuerdo con Manco, C. (2020) el modelo de calidad de Barry Boehm, propuesto en 1978, establece estándares para medir la calidad del software a través de atributos cualitativos y el uso de métricas. Estas métricas son utilizadas para evaluar si el software cumple con los atributos o funcionalidades esperadas. Este modelo, vigente desde 1978, organiza las características del software y las evalúa en atributos organizado en tres niveles: primarios, secundarios y primitivos.

- **Primarios**: representan las cualidades más esenciales y fundamentales del software, como la Utilidad, Mantenimiento y Portabilidad.

- **Secundarios**: se derivan de los primarios y se refieren a cualidades como la Portabilidad, fiabilidad, eficiencia, usabilidad, capacidad de prueba, comprensibilidad y flexibilidad.

- **Primitivos**: son aquellos aspectos más específicos y detallados que se asocian con los atributos secundarios y primarios, permitiendo una evaluación más precisa y detallada de la calidad del software.

Las métricas que evalúan cada uno de los atributos son los siguientes:
1. Portabilidad:
     * Independencia del dispositivo
     * Autocontención
2. Fiabilidad:
    * Autocontencion
    * Exactitud
    * Complititud
    * Robustez
    * Consistencia
3. Eficiencia:
    * Capacidad para rendir cuentas
    * Eficiencia de dispositivos
    * Accesibilidad
4. Ergonomía:
    * Robustez
    * Accesibilidad,
    * Facilidad de comunicación.
5.	Facilidad de evaluación o prueba:
    * Capacidad para rendir cuentas
    * Accesibilidad
    * Estructuración
    * Autodescripción
6. Compresibilidad:
    * Autodescripción
    * Estructuración
    * Concisión
    * Legibilidad.
7. Facilidad para ser modificado:
    * Estructuración
    * Extensibilidad

![image](https://github.com/alejandrolopezmldndo/FIS---EQUIPO-6/assets/133535448/28a6e335-1f28-4ee0-89c5-9c0fcbe3ae65)


Este enfoque jerárquico proporciona una estructura para evaluar y mejorar la calidad del software en múltiples niveles, permitiendo una comprensión detallada de sus características y su grado de cumplimiento con los estándares de calidad establecidos


## Modelo de calidad: McCall

Constanzo. M. (2014) resume el método McCall en lo siguiente 

> El estándar McCall utiliza tres perspectivas para evaluar la calidad del software. Este modelo identifica 11 factores y establece 23 criterios asociados a estos factores. Para medir estos criterios, propone métricas que se expresan como preguntas y asignan valores numéricos a los atributos del producto de software. Después de recopilar los valores de todas las métricas relacionadas con un criterio específico, se calcula su promedio para determinar el valor de dicho criterio.

![image](https://github.com/alejandrolopezmldndo/FIS---EQUIPO-6/assets/133535448/93a21a64-5a72-48b9-89a0-7761b95c34e8)

El modelo McCall utiliza 11 factores a evaluar divididas en tres perspectivas:
* Operación se refiere a la capacidad del software para cumplir con sus especificaciones y funcionar de acuerdo con lo que se ha definido en los requisitos y expectativas previamente establecidos. Los factores que entran en esta perspectiva y sus respectivas métricas de evaluación son: 
    - Corrección:
        - Trazabilidad
        - Completitud
        - Consistencia     
    - Fiabilidad
        - Consistencia
        - Exactitud
        - Tolerancia a fallos 
    - Eficiencia
        - Eficiencia en ejecución
        - Eficiencia en almacenamiento   
    - Integridad
        - Control de acceso
        - Auditoria de acceso
    - Usabilidad
        - Operabilidad
        - Formación
        - Facilidad de comunicación 

* Revisión se centra en evaluar la facilidad con la que el software puede ser adaptado, modificado o mejorado sin comprometer su funcionamiento o integridad. Sus factores son:
    -	Facilidad de mantenimiento
        - Simplicidad
        - Concisión
        - Autodescripción
        - Modularidad	
    -	Facilidad de prueba o evaluación
        - Instrumentación
        - Simplicidad 
    -	Flexibilidad
        - Extensibilidad
        - Generalidad	


* Transición capacidad de adaptar el software a diferentes entornos, sistemas operativos, plataformas o contextos sin perder su funcionalidad ni comprometer su rendimiento. En esta perspectiva están incluidos los factores de:
    * Interoperabilidad
        * Comunicaciones comunes
        * Datos comunes
    *	Portabilidad
        *	Independencia de la maquina
        *	Independencia del sistema operativo
    *	Reusabilidad
        *	Modularidad
        *	Generalidad
        *	Simplicidad
        *	Independencia del sistema
        *	Independencia de la maquina
          
![image](https://github.com/alejandrolopezmldndo/FIS---EQUIPO-6/assets/133535448/d4acd3da-3851-480c-9acf-e99e855a941a)

## Reflexión y decisión del estándar de calidad para nuestro proyecto

El modelo que utilizaríamos seria el de McCall porque es un modelo aun vigente en la actualidad, tomando en cuenta que modelos actuales hasta el mismo modelo boehm se basan en el de McCall, aparte tenemos la certeza que se adapta perfectamente a nuestro proyecto de desarrollo de software, que implica un traductor de lenguaje de señas usando cámaras de dispositivos móviles con funciones educativas similares a Duolingo. Este modelo ofrece una evaluación completa de tres perspectivas clave: operatividad, transición y revisión, el cual, nos ayuda a garantizar la precisión en la interpretación de gestos, la fiabilidad en las traducciones, la eficiencia en la interacción con la cámara y la usabilidad para usuarios nuevos y aquellos que usan el traductor para comunicarse.

McCall destaca criterios específicos para cada factor los cuales podríamos utilizar, ejemplos son utilizar el criterio de evaluación de la la consistencia en la interpretación de gestos, la precisión en las traducciones, y tolerancia a fallos en la captación de las señas mediante el traductor de señas. Además, se enfoca en la usabilidad y facilidad de aprendizaje del uso de nuestro software, siendo esencial para un software dirigido a principiantes en lenguaje de señas o para una comunicación efectiva.

El modelo promueve una mayor comprensión y alineación entre el equipo de desarrollo y los usuarios, ya que sus criterios establecidos facilitan la comunicación y la mejora continua del software según las necesidades y expectativas del usuario/cliente.

En resumen, la elección del modelo de calidad de McCall para nuestro proyecto se justifica por su enfoque completo en la calidad, criterios detallados y capacidad para mejorar la comunicación entre el equipo de desarrollo y los usuarios.

# Auditoría de la gestión de la configuración del software
Elegimos dos artefactos utilizados como parte de la tercera entrega, nuestros casos de uso y el diagrama de dichos casos. 

## Informe
La configuración del proyecto empieza con la producción de un cambio en la linea base que queda pendiente de aprobación. El primer chequeo busca que la linea base se mantenga funcional tras el cambio. Si no funciona, el código tiene que reimplementarse a la linea base con los cambios requeridos, en caso opuesto puede continuar al siguiente. Para nuestro diagrama, tuvimos que realizar un cambio debido a que hasbía un conflicto entre esta primera version y lo que se mostraba en nuestro prototipo en Figma, así que tuvimos que cambiarlo.

Para el segundo chequeo, se revisa la integridad con respecto a los requisitos del proyecto y si ocurre un problema con los requisitos, éstos se tienen que cambiar. Con los casos de uso encontramos que no estaban adaptados a los nueuvos requerimientos que habíamos agregado en la entrega posterior. Como no hubo ningún problema con los que ya estaban anteriormente sólo tuvimos que regresarlo a nuestra producción para añadir los cambios necesarios.

Adicionalmente, se realizan chequeos para asegurarnos de la calidad del la linea base como reflejar los cambios en la documentación y ser verificado por el líder del repositorio (Alejandro Maldonado).

Durante el transcurso de nuestro proyecto, adoptamos una estrategia de versionamiento y entregas a través de la plataforma GitHub, donde los artefactos desempeñaron un papel fundamental, puesto que fueron incluidos como parte de una entrega, evolucionando gradualmente para cumplir con los requisitos específicos del proyecto. Este enfoque no solo facilitó un seguimiento preciso del progreso del desarrollo, sino que también fomentó una mayor colaboración entre los miembros del equipo. La sincronización de la evolución de los artefactos nos proporcionó una visión clara de la evolución del proyecto.

# Checklist de Revisión del Proyecto

## Chequeo 1: Mantenimiento de la Linea Base

| No. | Descripción                                               | Estado    |
| --- | --------------------------------------------------------- | --------- |
| 1   | Realizar un cambio en la línea base pendiente de aprobación |           |
| 2   | Verificar que la línea base se mantenga funcional         |           |
| 3   | En caso de fallo, reimplementar el código a la línea base con cambios requeridos |           |
| 4   | Continuar al siguiente chequeo si la línea base es funcional |           |

### Notas Chequeo 1:
- Hubo un conflicto entre la primera versión y el prototipo en Figma, se realizó un cambio para resolverlo.

## Chequeo 2: Integridad con Requisitos del Proyecto

| No. | Descripción                                               | Estado    |
| --- | --------------------------------------------------------- | --------- |
| 1   | Revisar la integridad con respecto a los requisitos del proyecto |           |
| 2   | Modificar requisitos en caso de problemas identificados    |           |
| 3   | Asegurarse de que los casos de uso se adapten a los nuevos requisitos |           |
| 4   | Regresar a producción para añadir cambios necesarios en caso de problemas |           |

### Notas Chequeo 2:
- Casos de uso no estaban adaptados a los nuevos requisitos; se realizaron cambios necesarios.

## Chequeos Adicionales de Calidad

| No. | Descripción                                               | Estado    |
| --- | --------------------------------------------------------- | --------- |
| 1   | Reflejar cambios en la documentación                       |           |
| 2   | Verificación por el líder del repositorio (Alejandro Maldonado) |           |



## Referencias
* Fernández, C. (3 de julio de 2020). Modelo Boehm [video] URL: https://www.youtube.com/watch?v=YbNq3tr030M&ab_channel=CarmenzaFernandezOspitia
* Ramírez, A. (7 de octubre de 2019). Modelos de calidad Boehm [Video] URL: https://www.youtube.com/watch?v=RtlflSqSo4c&ab_channel=AndresMauricioRamirezPuentes
* Modelosred.com. (s.f.). Modelos de Calidad: Boehm. [Publicación en línea]. Recuperado de URL: https://modelosred.fandom.com/es/wiki/Modelo_de_Calidad_de_Boehm
* Manco, C. (24 de septiembre de 2020). Modelo de calidad Boehm [Video] URL: https://www.youtube.com/watch?v=OoiiuJW14k&ab_channel=Andr%C3%A9sCamiloManco%C3%81lvarez
* Constanzo M., Casas I., Marcos C. (2014). Comparación de modelos de calidad, factores y métricas en el ámbito de la ingeniería de software. Informe Científico-técnico UNPA, volumen 6, pagina 1. URL: https://publicaciones.unpa.edu.ar/index.php/ICTUNPA/article/view/395
* Fandom. (s. f.). Modelo de Evaluación McCall. Recuperado de https://modelos-de-evaluacion-red-grupo9.fandom.com/wiki/MODELO_DE_EVALUACI%C3%93N_MCCALL 
https://cdn.goconqr.com/uploads/node/image/33498787/desktop_615fc79c-314e-43ef-b6d7-b93693d68194.png






