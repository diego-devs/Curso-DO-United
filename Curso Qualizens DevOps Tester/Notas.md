## Curso Qualizens - DevOps Testing
### DOu Certified Tester in DevOps - Foundation Level (CTD-FL)

Hands-on lab -> Curso practico

Todo es código en los equipos de DevOps. 
Requerimientos: 
-   Orientado a profesionales de TI
-   Conocimientos básicos de estadística - not really
-   Conocimientos básicos de código y programación

Es preparación para el examen
el examen son 40 preguntas. Examen de opción multiple -> 4 respuestas posibles

Presentación: 
-> Diego Díaz, mi trabajo es como programador junior para la empresa Global Hitss, 
actualmente trabajando con un cliente en estados unidos llamado Meridianlink, compania dedicada a 
la creación de software de prestamos y creditos. Hace 2 semanas que me encuentro en el equipo de QA
para distintos proyectos dentro de la organizacion. Tengo poca experiencia en la industria de tecnologia, llevo 9 meses ya trabajando como programador con el equipo de desarrollo. Este es mi primer trabajo en una compa;ia grande de tecnologia, y muy emocionado de poder compartir y aprender de todos ustedes.

Es requerido instalar todas las herramientas mencionadas en configuraciones: 
[Configuraciones](https://docs.google.com/spreadsheets/d/1XB52wcDkJcHssSG-kDfstjIFwqezNMstPbOgwzay0rE/edit#gid=0)

-   Ecplise
-   Docker Hub 
-   Git / Github
-   JIRA
-   AWS
-   VS Code
-   Java development kit

### Qué es DevOps? 

-> Todo lo que haces para superar la fricción generada por los silos hasta el objetivo final. -> definición de creador
-> DevOps es una serie de buenas practicas, filosofia y CULTURA sobre como lograr la construccion de software confiable, de calidad, robusto y escalable eficientando las labores de operaciones y developers.

### Por dónde empezar? 
### Modelo de madurez de DevOps

1.  No se ha iniciado DevOps: Interrupciones, cuartos de guerra, culpas, trabajos no planificados, retrasos y defectos.
2.  Iniciando con DevOps: Considerando el cambio cultural, comenzando a escribir guiones, considerando automatizar pruebas. 
3.  DevOps fundamental: Construcción automatizada, equipos multifuncionales, centrados en el producto, cambio cultural. 
4.  DevOps Gestionado: Personas felices con una cadena de herramientas integradas para prevenir fallos, pruebas automatizadas y despliegue - entrega continua. 
5.  Optimización de DevOps: Ajustado y estrechamente vinculado a los objetivos empresariales. 

*Los usuarios no prueban el producto, ellos APRUEBAN o desaprueban.*

DevOps -> Cultura y práctica de ingeniería de software que combina el desarrollo y las operaciones. 
El símbolo es un infinito. Demuestra el ciclo continuo entre devs y ops.

### Principios básicos de DevOps

1.  Acción centrada en el cliente. 
2.  Crear con el objetivo final en mente.
3.  Responsabilidad de extremo a extremo. 
4.  Equipos autónomos y multifuncionales. 
5.  Retroalimentación continua. 
6.  Integración y despliegue continuos. 
7.  Mejora continua. 
8.  Experimientación y aprendizaje continuos. 
9.  Automatizar todo lo que se pueda. 
*Y el ciclo vuelve a comenzar*

En un equipo DevOps todos los miembros del equipo saben por qué están haciendo lo que están haciendo. 
Conocen al cliente y conocen el objetivo final. 

### Problemas que enfrentan los equipos de TI

-   Diferencias de mentalidad.
-   Diferencias de objetivos: 
    -   Desarrollo - últimas innovaciones (negocio/tecnología)
    -   Operaciones - mantener las cosas en funcionamiento
-   Actitud de "arrojar por encima del muro".
-   Desajuste de impedancia - diferentes herramientas y lenguajes. 
-   Diferentes entornos: desarrollo, pruebas, staging y producción. 
-   Ciclos largos o rotos de retroalimentación y falta de comunicación.

### Retos que DevOps pretende resolver

-   Pruebas manuales
-   Datos de prueba
-   Ninguna virtualización del servicio
-   Falta de un sistema de gestión de la configuración

### Integración y entrega continua

-   La gestión liberación tradicional 
    -   planificación 
    -   programación
    -   Monitoreo y control
    -   aprobaciones

-   El gestor de liberación monitorea y controla las actividades. 
-   Integración continua

Integrar el trabajo diariamente, al menos 1 vez al día para poder obtener feedback. 
    -   Incluye procesos/mecanismos adicionales para realizar liberaciones más rápidas y fiables. 

### Liberación de software tradicional
Tradicionalmente pasaba mucho tiempo entre el proceso de construcción y release, como el estilo de cascada. 
Esto no era bueno ya que a medida que se avanza, se escriben mayor líneas de código. Aquí habrá una relación entre el número de líneas de código y el número de defectos en el producto final. Cuanto mayor cantidad, recién se integra, mayor número de errores y bugs saltarán. 
-   Problemas de fusión de código
-   Dificultad para aislar los defectos

Esto no es recomendado en un esquema de desarrollo moderno. *Esto es prehistoria*

### Qué sí se debe buscar? 

-   Integración continua
-   Releases cortos
-   Verificación temprana

### DevOps y pipeline de entrega

-   Recordar el principio -> Automatizar todo lo que se pueda
-   Se utilizan pipelines de datos
    -   Conjunto de elementos de procesamiento conectados en serie
    -   La salida de un elemento es la entrada del siguiente
    -   Los elementos pueden ejecutarse en paralelo o de forma secuencial

Build application -> Aceptance test -> Capacity test -> Pre-production -> Production
                    -> Automate     -> Automate      -> Automate    -> Automate
            <- feedback en todo momento ->

            De esta forma el equipo conoce todo lo que pasa en todo momento en el *pipeline*

En la mayoría de las organizaciones el pase a producción es MANUAL. 
Los pasos del pipeline de entrega pueden ser manuales o automatizados. 
Que sean automatizados ayudará al equipo a tener feedback continuo. Si alguno de los pasos del pipeline falla, los datos pueden ser revisados por los equipos en todo momento.

-   Ayuda al impulso continuo
-   Ayudan a detectar los defectos de forma temprana

### Enfoque de movimiento continuo

### Integración continua, Entrega continua CI / CD 

### Cuál es la diferencia? 

Ambos procesos son automatizados. 
La integracion continua CI es interesante en específico para los desarrolladores. Esta se hace al menos una vez al día. 
La entrega continua CD también necesita desplegar pruebas automatizadas.
Despliegue continuo.

CI -> Calidad del código -> no libera nada
CD -> Calidad funcional -> no libera, despliega y ejecuta pruebas
Despliegue continuo -> Calidad del proceso (sería el máximo nivel al que una organización podría llegar) -> Sí libera a producción

... próxima sesión en viernes 18 de nov
... Contenedores de jenkins, AWS ... 

## Sesión 2 - 18/11/2022

Recordamos que la liberación de software tradicional conlleva tiempos más largos a comparación de la Integración continua, Entrega Continua y Despliegue continuo. No son temas aislados, son continuación del anterior. 

-   CI (integration) -> CD (delivery) -> CD (deployment) 

## Integración Continua CI 

-   La práctica de fusionar código en una rama varias veces al día. 
-   Ventajas
    -   Facilidad de integración
    -   Detección y resolución temprana de problemas
    -   Depuración más fácil
    -   Reducción de problemas de integración
    -   Entrega más rápida

## Continuamos con GIT y ejercicios
### Branching, Merging and Conflict solving

Git clone -> cambios locales -> commits locales -> git push

Cuando dos o mas desarrolladores están trabajando en el mismo código los conflictos pueden y suelen darse. 
Para evitar estos conflictos es necesario un buen patrón de diseño y seguir buenas prácticas a la hora de construir y escribir código. 

God Class -> Objeto todopoderoso. es un objeto que conoce demasiado o hace demasiado. El objeto todopoderoso es un ejemplo de un anti-patrón.

El Código del Objeto todopoderoso no sigue esta regla. En su lugar, la funcionalidad entera del programa está codificada en un solo objeto que hace todo, el cual mantiene toda la información del programa entero y contiene todos los métodos y subrutinas para manipular los datos. Como el objeto contiene muchos datos y requiere muchos métodos, su rol en el programa se convierte en Objeto Todopoderoso (Abarca todo). En lugar de objetos comunicándose entre ellos directamente, los objetos en el programa se cuelgan del Objeto Todopoderoso para manejar su información e interacción. Como el Objeto Todopoderoso es referenciado por casi todo el código, el mantenimiento se vuelve mucho más difícil, que el diseño del código de un programa mejor dividido. 

## Pipelines y herramientas de CI

-   El pipeline de CI (Integración continua) es la columna vertebral en el entorno DevOps
-   Primer paso en el CI/CD en DevOps

## CD Continue Deployment -> Entrega continua

### Ventajas del CD
-   Cada cambio es construido, probado y liberado, lo que resulta en:
    -   Descubrimiento temprano de errores
    -   Facilidad para aislar problemas
    -   Construcción del **producto correcto** utilizando una retroalimentación rápida
    -   Un tiempo relativamente más corto para las correcciones
    -   Liberaciones más rápidas y un menor tiempo de salida al mercado
    -   Liberaciones fiables
    -   Mejora la calidad de los productos
    -   Mejora de la satisfacción del cliente
-   El mismo proceso automatizado para los entornos de prueba, de staging y de producción = menos sorpresas después de la liberación.

## Entrega continua vs Despliegue continuo

CD -> CD 

Entrega continua: 
Build -> Unit test -> Deliver to staging -> Application Acceptance tests -> Deploy to production -> Post deploy tests

Despliegue continuo: 
Build -> Unit test -> Deliver to staging -> Application 

### Entrega continua, despliegue continuo y el proceso Ágil

-   Tanto la entrega continua como el despliegue continuo existen en el proceso ágil que proporciona un marco de trabajo en el que se realizan cambios pequeños y frecuentes y donde la retroalimentación se obtiene rápidamente.

-   En el desarrollo en cascada se liberan cambios poco frecuentes. Picos de esfuerzo, Alto riesgo. 
-   proceso ágil se liberan cambios frecuentemente, esfuerzo uniforme en el tiempo, con menor riesgo. 

### Cultura DevOps

Desarrollo -> Prueba -> Operaciones

Cada quien tiene motivaciones individuales lo que puede ocasionar falta de comunicación, retrasos y tensiones.

En un equipo DevOps se tiene UN SOLO objetivo. Esto ya lo dijo el CTO de Amazon Werner Vogels : 

El modelo tradicional es cuando tomas el software de la pared que separa operaciones y desarrollo, lo tiras y lo olvidas. En DevOps no pasa eso. El equipo DevOps tiene un solo objetivo y un solo enfoque. La entrega de valor en un producto y de forma continua. Esto hace que tengan una motivación común y una mejora en la colaboración. 

### Principales aspectos culturales y mentalidad DevOps

-   Valores de ágil
-   Mentalidad / Cultura de equipo
-   Herramientas y procesos -> Automatización, ligeros (lean)

Esto crea: 
-   Mayor colaboración entre los departamentos: Dev, test, ops
-   Una menor tendencia a trabajar en silos. 
-   Trabajo ligero (lean) compartiendo la responsabilidad
-   Énfasis en la autonomía de los equipos
-   Mejorar la calidad
-   Aceptar el fracaso valorando la retroalimentación y aumentar la automatización

**Entre más autónomo sea el equipo, mejor** Es dificil cambiar la cultura de una organización, pero entre mayor sea la autonomía serán mejores los resultados que se obtendrán.

Es posible, por ejemplo en el caso de muchos proveedores, que sea difícil mantener un equipo unido con un solo objetivo. 

### DevOps y Shift Left
-   El término "Shift Left" se refiere a una práctica en el desarrollo de software en la que los equipos se centran en la calidad de sus productos, así como en la prevención de problemas en lugar de la detección y comienzan a realizar pruebas lo antes posible. 
-   Los principios clave para Shift Left son: 
    -   Probar pronto
    -   Retoralimentar antes los casos de uso orientados al cliente
    -   Probar a menudo
    -   Probar de forma incremental
    -   Reducir los costes

El punto del **Shift Left** es mover las revisiones, pruebas estáticas, pruebas unitarias, pruebas de integración, pruebas de sistema y pruebas de aceptación lo más antes posible en el tiempo. No esperar a que algo exista para comenzar a probar, sino que comenzar a probar desde antes. 
Así se comienza a cuestionar tempranamente las decisiones y cambios, y no solamente probar cuando ya se ha trabajado. 
El modelo típico de calidad es mover a la **derecha** estas pruebas en el tiempo. 
Debemos definir las pruebas **ANTES** de desarrollar, para que estas puedan ser usadas por el developer para después hacer las pruebas unitarias o de integración. Entre más a la **IZQ** mejor.

Diseñar pruebas ------> Producto -------> ejecutar pruebas

No se necesita que el producto exista para hacer pruebas. 
Pruebas son: 
-   Requisitos del negocio ------> Pruebas de aceptación
-   Especificaciones del sistema -----> Pruebas de sistema
-   Especificacion del diseño -----> Pruebas de integración 
-   Codificación ----> Pruebas de componentes (unit)

Esta cultura de **SHIFT LEFT** es que las pruebas se realizan al comienzao del ciclo de vida, es decir se desplazan a la izqiuerda en el calendario del proyecto. 
**Probar pronto y a menudo**

### Prácticas clave de DEVOPS: 
-   Pruebas continuas
-   Despliegue continuo
-   Métodos y enfoques utlizados
    -   Desarrollo guiado por pruebas TDD
    -   Desarrollo guiado por pruebas de aceptación ATDD
    -   Desarrollo guiado por comportamiento BDD
    -   Especificación por ejemplo SBE
-   Cuanto antes se realicen las pruebas, antes se detectarán los problemas. Esto ayuda también a reducir costes por bug que surgen en las fases tardías de pruebas. 

En el enfoque antiguo, es al revés, las pruebas se enfocan a la derecha del calendario y esto hace que la detección de problemas sea más tardío y cree más issues y sean más difíciles de abordar. 

Próxima clase: Pruebas continuas y pipeline...

## Sesión 4 - Continuamos con DevOps y Shift Left

TDD , ATDD, BDD, SBE -> 

1.  Desarrollo guiado por pruebas TDD 
2.  Desarrollo guiado por pruebas de aceptación ATDD 
3.  Desarrollo guiado por comportamiento BDD
4.  Especificación por ejemplo SBE

### Otros nombres populares para DevOps: 
-   DevSecOps (para la seguridad)
-   DevTestOps (para las pruebas)
-   DevDataOps (para los datos)
-   DevArchOps (para la arquitectura)
-   DevWinOps (para MS-centric)
-   **DEV*OPS** (nótese el asterisco *)
Lo más importante es que los SILOS se rompan. La tecnología viene después y pueden usar el término que gusten. Esto lo dijo el creador del término DEVOPS. 

### DevOps y Ágil

-   Ágil: entrega más rápida, mejoras y correcciones más rápidas, reduciendo así el tiempo de entrega mientras se sigue mejorando la calidad de cada liberación. 
-   Los valores y la cultura de DevOps se basan en la agilidad
-   DevOps aporta agilidad al proceso y a las herramientas
-   Tanto ágil como DevOps comparten un objetivo común, que es mejorar la velocidad y la calidad de la entrega de valor
-   Diferencia: la agilidad se centra en el desarrollo, pero no en las partes posteriores al desarrollo del flujo de valor, mientras que DevOps sí lo hace.

### Pruebas Continuas (CT)
-   El proceso de ejecución de pruebas automatizadas como parte del pipeline de entrega de software para obtener información inmediata sobre los riesgos de negocio asociados con un candiadto a release de un software
-   El objetivo principal es realizar las pruebas lo antes y con la mayor frecuencia posible

1.  Automatización estable
    1.  Qué obtendrán? 
    - Crear scripts
    - Mantener los scripts
    - entender lo que no funciona
    2. Qué neceistarán? 
    - Herramientas acordes a habilidades del equipo
    - Detección de falsos negativos en los informes  
2.  Ciclo diario
    1.  Qué obtendrán?
    - Ejecutar el script diariamente
    - Obtener resultados
3.  Aumentar la cobertura
4.  Alcanza el 95%
5.  Pruebas continuas

### Principales características de las pruebas continuas (CT)

-   Casos de prueba micro (atómicos) independientes
-   El menor número posible de dependencias entre las pruebas
-   Entorno de pruebas totalmente automatizado
-   Sistema sólido de gestión de la configuración para apoyar
    -   Evolución de las pruebas
    -   Automatización con el desarrollo
- Capacidad de desencadenar coualquier tipo de pruebas en cualquier nivel de la pirámide de pruebas
  - Contra diferentes entornos y liberaciones
- Comprender que las pruebas son una actividad necesaria, no sólo una fase de ciclo de vida del desarrollo
  
1. Unit Test
2. Pruebas de integración
3. Pruebas de API

### Pruebas

1. Q1 cuadrante 1 - orientadas a la tecnologia y al desarrollo del producto, APIS, tecnología usada, etc. Aquí sí se puede coificar. Pruebas unitarias, automzatizadas a la integración continua. 
2. q2 cuadrante 2 - orientadas al negocio para apoyar al equipo. Incluso antes de escribir código. 
3. q3 Pruebas orientadas al negocio para criticar el producto
4. q4 Pruebas tecnologicas para evaluar 

### Pruebas

-   Unit Test: La unit test o prueba unitaria se prueba en la unidad mínima del código, que son los métodos. q1
-   Prueba API: Las pruebas de API se hacen através de HTTP y prueban los endpoints y es a nivel de protocolo. Aquí se prueban códigos de error, contratos, tipos de datos, que los datos estén completos, etc. q1
-   Prueba UI: Con la prueba de UI ya se tiene que interactuar con la interfaz de usuario. q2 Ejemplo: 
    ** Escenario: Busqueda de producto
    Se buscará en el menú el producto "sleeve" y tiene que regresar x en pantalla dado que el producto se encuentra. (ejemplo) Estas pruebas están en el cuadrante 2

### Desarrollo guiado por pruebas Test Driven Development/Design

### Marco de trabajo xUnit

### Ejercicio
Crear pruebas utilizando el marco de trabajo xUnit contra un código dado. Vamos a utilizar Jenkins de nuevo. 

AWS -> Instances -> Start instance
usamos putty para conectarnos, cambiando la IP dinámica y conectándonos por vía consola. 

-   sudo docker ps -a
-   sudo docker start 476 <- este numero es el identificador del contenedor>
Iniciamos jenkins -> IP dinamica + :8080 <-este es el puerto por el cual nos conectaremos vía TCP>

Ya estamos en Jenkins

## Análisis Estático 

Es una forma de prueba automatizada
-   Comprueba las violaciones de las normas
-   Comprueba las pruebas dinámicas
Informes de rendimiento de código. 

Vamos a hacer un análisis estático de código con la herramienta SonarQube -> SonarQube (formerly Sonar) is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs and code smells on 29 programming languages. SonarQube offers reports on duplicated code, coding standards, unit tests, code coverage, code complexity, comments, bugs, and security recommendations.

El Sonar Runner corre desde Jenkins
después de procesado este hace un PUSH hacia SonarQube por medio de un TOKEN. Después SonarQube lo PRESENTA únicamente. 

## Sesion 5 - continuamos con pruebas
### Ejercicio 

-   Integrar una herramienta de medición de análisis estático del código (SonarQube) en un pipeline. 

Pruebas: 
- Estáticas: Análisis estático (por ejemplo SonarQube), Revisiones
- Dinámicas: Análisis dinámico

Análisis dinámico: este necesita ejecutar el código. 
Herramientas de cobertura de código. 
-   Ayuda a comprender qué parte del código ha sido ejecutada por sus pruebas

-   JaCoCo es la herramienta a usar

Entonces ejercicio: 
1.  Correr las dos instancias en AWS
2.  Levantar el container de Jenkins primero
    1.  sudo docker ps -a
    2.  sudo docker start ###
   
3.  Levantar SonarQube
    1.  sudo docker ps -a
    2.  sudo docker start ###

4.  Cambiar la url del SonarQube en Jenkins Confugure
5.  Añadir JaCoCo como plugin en Plugins -> Available -> install


El plugin de JaCocO es para que se muestre el reporte de jaCOCO dentro de Jenkins. Si no hacemos eso, el reporte estaría solamente en el contenedor. 

## Pruebas de API en el pipelina CI

-   los principales pasos para realizar las pruebas de la API en eun pipeline de Jenkins

Primero desplegar las pruebas
Y después ejecutar las pruebas

La integracion continua llega hasta el code coverage
todo lo demás es entrega continua, es decir ejecutar pruebas sobre una version especifica del ambiente para ver si el producto pasa las pruebas. 

Aquí podemos obtener immediatamente feedback prácticamente en minutos. Mientras que en el modelo tradicional podría tardar hasta días o semanas en obtener el feedback, ya que se ejecuta todo esto de forma manual. 

Checkout SCM -> Clean -> PMD -> Compile -> Code Analysis -> Unit Test -> Code Coverage -> Install -> Launch tomcat server -> Deploy War on tomcat Server

Último stage a añadir a nuestor pipeline: 

## Pruebas de aceptación

Dev -> Test
desarrollar para luego probar. Este es un pensamiento de la época industrial. 
Pero en los equipos ágiles pasa distinto, en específico, invertido. 
Test -> Dev
cómo vamos a hacer testing sin algo que testear? 
Siempr pensamos que se hace después de desarrollar algo, pero aquí se trata de definir. Las pruebas en ágil se definen antes del desarrollo y las pruebas dirigen el desarrollor. TDD. Test driven design TEST DRIVEN DEVELOPMENT

Test -> Dev -> Ejecutar tests

Behavior: (escenarios)
given -> 
when -> 
Then -> 

Se trata de definir el comportamiento del software antes de ser desarrollador. Se desarrolla y después se ejecutan los tests. 
-> -> <->
BDD 
Behaviour Driven Development

Hay una adopción más creciente de BDD. Esto para ver el comportamiento del producto ANTES de desarrollarlo.
Esto se define comunmente en una reunión de EQUIPO, qué espera el negocio? Reglas, lógica y entonces trabajar con ejemplos REALES sobre el negocio. Qué es lo que esperas que suceda cuando el usuario añada un elemento al carrito de compras? 
Así se definen estos escenarios. 

El formato Given When Then es especificacion ejecutable
ya que este escenario se debería llevar a una automatización. 

Los escenarios guian al desarollador y actuan como guias automatizadas. El tester también usa estos escenarios como guia para sus pruebas en ATDD (desarrollo guiado por pruebas de aceptacion) y en BDD las pruebas son automatizadas siempre. 

Cuando las pruebas automatizadas se van a actualizar se escrien en un archivo .feature Archivo de características
El feature describe el escenario y cada uno es un PASO y hay que ver su equivalente en código. 
"dado que me encuentro en la pagina inicio" -> debería haber un código que haga que se encuentre efectivamente en la página inicio. 

Tradicionalmente se habla de:
ANALISTA -> DESARROLLADOR -> TESTER

EN ágil no es así. Aquí todo el equipo participa en el diseño previo al desarrollo. 

### Archivo FEATURE y STEPS 

Mytest.Feature: 

**Feature**: Functionality on login page of Application

  **Scenario**: Verification of Login functionality
    **Given** Headless browser is opened and Expense Manager app is launched
    **When** I Enter correct Username and Password
    **And** click on login button
    **Then** it shows home page

Esto debe ser leíble para la gente del negocio. No es código, pero es un pseudo código. 

BDD Ferguson -> Libro recomendado por Guino

cada uno de los pasos necesitan código para ser ejecutados

Ahora vamos a añadir el ultimo stage a nuestor Pipeline
BDD TEST

Usamos cucumber en la clase para usar los controles 
y usamos selenium para activarlos a las pruebas

### Pruebas específicas de DevOps

Normalmente pruebas que se hacen ya en producción
Cuando hablamos de pruebas en prod, no hablamos de completar pruebas que se tenían que haber hecho antes. 

### Pruebas de características/features específicas del usuario

Se pueden realizar liberaciones de características (features) específicas del usuario utilizando los métodos: 
1.  feature toggles
2.  liberación canaria
3.  Pruebas A/B

Hablemos de la diferencia entre desplegar y liberar
Deploy y Release <- 

Liberar es cuando la versión del producto ya está disponible para los usuarios finales

Desplegar en ambiente de pruebas, o pre producción, o producción
Puedes desplegar a producción y puede estar disponible para los usuarios o no. 
En las técnicas tradicionales sí era así, pero en técnicas actuales no quiere decir que estén disponible para usuarios finales. 

Por eso existen los Feature Toggles: Se despliega en producción, pero no se ha habilitado para los usuarios finales.

La Liberacion Canaria es cuando despliega uno en producción y libera solo para un porcentaje pequeño de los usuarios. Digamos el 5%, pero el 95% no ha visto ese despliegue. 

A/B Testing es cuando en la versión de producción se tienen dos versiones de una misma feature. version A del carrito y version B del carrito. Se pueden diferenciar en X formas. Por qué desplegar dos versiones? Para ver cómo responden los usuarios con esas versiones. Si A es mas aceptada, se queda y B se deshecha, etc.
Esto se hace en producción. 

Ya no son priebas de sistema, ni unitarias, ni API. Esas son ANTES de producción. 
Estas otras se hacen en Producción ya. 

-   Feature Toggling de uso interno
    -   La característica se activa solo para usuarios internos
    -   La decisión puede basarse en cookies, cabeceras especiales, etc.
    -   Una vez realizadas las pruebas y los comentarios, se realizan los cambios. 

-   Liberación canaria: 
    -   La característica está disponible para un subconjunto de usuarios
    -   Los usuarios pueden ser elegidos al azar o en base a un algoritmo
    -   Se hace para probar las características
    -   Seguimiento de las métricas de los usuarios activados y desactivados

... Siguiente sesión: revisar sobre A/B Testing
y ver cosas como feature flag

## A/B Testing - Sesion 6 PENDIENTE

Pruebas A/B 
Dos versiones liberadas como Version A o Version B
Son elegidos bajo un determinado algoritmo o criterio
Seguimiento de las metricas de ambos grupos de usuarios
Decision de mantener A o B en base al analisis de los datos

Ejercicio:

## Sesion 7 PENDIENTE

## Sesion 8 03/12/2022

Diferencias entre maquinas virtuales y contenedores
-   Podemos utilizar los microservicios como un enfoque arquitectónico, donde cada aplicación se construye como un conjunto de servicios
-   Cada servicio ejecuta sus propios procesos y se comunica a través de APIs
-   Docker funciona proporcionando una forma estándar de ejecutar su código y es un sistema operativo para contenedores
-   Una máquina virtual virtualiza (elimina la necesidad de gestionar directamente) el hardware del servidor, los contenedores virtualizan el sistema operativo de un servidor
-   Docker se instala en cada servidor y proporciona comandos sencillos que se pueden utilizar para construir, iniciar o detener contenedores. 

Primero se instala Docker y después se puede usar en la máquina virtual. 

-   Los contenedores son una abstraccion en la capa de la aplicacion que agrupa el código y las dependencias
-   Varios contenedores pueden ejecutarse en la misma máquina y compartir en núcleo del sistema operativo con otros contenedores, cada uno de los cuales se ejecuta como procesos aislados en el espacio de usuario
-   Las plataformas en la nube más populares actualmente son: 
    -   Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform y Alibaba Cloud

Si no se usara tecnología en la nube podría ser más difícil trabajar en la automatización de los despliegues y la tecnología Cloud nos permite hacer esto más sencillo. 

### Infraestructura como código (IaC)

-   Es una forma ligera y guiada por datos de gestionar y aprovisionar la infraestructura del sustema (redes, máquinas virtuales, equilibradores de carga y topología de red)
-   Es un modelo descriptivo, en lugar de gestionarlo con la configuracion del hardware físico o con herramientas de configuración interactivas
-   Tiene principios similares a los de la gestión del código
    -   El modelo IaC genera el mismo entorno cada vez que se aplica
- Cada vez que el equipo realiza cambios, puede editar el código fuente y no el entorno de destino
- IaC es una práctica clave DevOps y se utiliza junto con la entrega continua
  
### Las principales ventajas de contar con una IaC modelizada son: 
-   Rapidez sencillez
-   Evitar incoherencias en el despliegue de la configuración del sistema
-   Reduce riesgos
-   Aumenta la eficiencia y la productividad de la I+D sobre todo en la nube
-   Reducir y ahorro de costes

### Repositorios Binarios

-   Un repositorio binario es un lguar de almacenamiento de paquetes de software. Ya no es texto. 
-   Por lo general, se almacena una tabla de contenidos como metadatos. Los repositorios también gestionan paquetes de grupo. 
-   Gestores de repos : 
    -   Crean construcciones continuas y generan una gran cantidad de artefactos
-  Como aprte del ciclo de vida del desarrollo, el código fuente se oconstruye continuamente en artefactos binarios utilizando la integración continua

Las herramientas de IaC:    
1.  Herramienta de orguqestacuion de configuracion
    1.  auto despliegue de infraestructura
2.  Herramientas de gestion de configuracion
    1.  despliegue de la condifuracion

Terraform
AWS CloudFormation
Chef
Puppet
Ansible
JuJu
uDeploy
JFrog Artifactory** realmente no es herramienta de IaC

-> Ver la tabla periódica de los elementos de DEVOPS


## Sobre el examen 

DOu certified Tester in devops 
foundation level 
ctd-fl






