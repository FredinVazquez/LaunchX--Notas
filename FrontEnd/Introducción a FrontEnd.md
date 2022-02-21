# **Introducción al mundo de FrontEnd**
FrontEnd hace referencia a la parte más expuesta de una página o aplicación web, es lo que primero que nos encontramos y es el frente de las aplicaciones web. Es lo primero a ver debido a que es la capa donde los usuarios interactuar. 

Lo encargado de ver en FrontEnd es:

* La estructura.
* El acomodo.
* Distribución del contenido.
* Estilos que son mostrados. 
* Los flujos de interacción con los usuarios.

Para el usuario se tendrá que dividir en dos conceptos para que sea posible una interfaz.

### **UX/UI**
Partes importantes del diseño web para poder sentar las bases sobre la interfaz que estará viendo el usuarios así como experiencia de esta al momento de usar la interfaz.

UI: hace referencia a la interfaz del usuario. 

UX: trata sobre la experiencia del usuario.

Estas son partes escenciales para tener una base y programar sobre ella, no iniciar directamente con el código.


### **Patrones de Arquitectura de Desarrollo Web**
#### **MVC**
Este es el patrón más usado y con ello podremos entender mejor el FrontEnd.
!["MVC"](https://github.com/LaunchX-InnovaccionVirtual/FrontEnd-Mision/blob/main/01%20-%20INTRO/images/mvc.png)

De modo que se podrá observar que es en el View donde estará funcionando como el FrontEnd debido a que estará teniendo un contacto directo con el usuario, para después enviarle la información de entrada del usuario al controlador el cual se encargará de enviarle esa información de la mejor forma ordenada al modelo, el cual estará funcionando como BackEnd, para que pueda cumplir con lo demandado por el usuario. Se estaría encargando de producir una salida mientras que View solo se encarga de recibir entradas, el controlador sería el intermediario.

Será importante conocer otros patrones de arquitectura para poder emplear el que mejor al momento de hacer nuestras aplicaciones web.


### **Software Development Life Cycle**
El ciclo de vida del desarrollo es una parte esencial para transmitir esta idea de sustentabilidad de la aplicación, es claro que al momento de emmpezar con algo grande es necesario primero iniciar con bases para después de ahí hacer pasos seguros con el fin de que nuestra aplicacion sea escalable, mantenible.

!["MVC"](https://lh3.googleusercontent.com/UvGkTRWfKbQqoVyaEyhPk-qSBsAfUZqgPgoxfpdmwbEpglkPfG2RAFIWwmlBArJfEdytf27jOYP-OpW7A0zAWhoyJCM6t6AkQZB0BMTKGsmcZunYFRlEz3yPazLGAycLKVtCSK7gIw=w2400)

Es claro que no será lo mismo construir un edificio sin varillas, o sea simplemente hacer una construccion con puro cemento, a llevar un controlar y un plan de desarrolla la aplicación. 

1. Fase 1 Requerimientos: esto es la fase en donde se contempla todas las necesidades que tiene la aplicación para poder desarrollarse.
2. Fase 2 Diseño: se empieza a formular un # plan.
3. Fase Desarrollo: en esta parte del proyecto se estará insertando ya el código en sí, se debe de confiramos dle número real entero decimale ydise lfrFase 4: verificano problemas en nuestra solución.
4.  Matenimiento y evolución: las páginas web se mantienen constantemente actualizadas debido a los cambios constantes.

## **Uso de las principales tecnologías**
### **HTML**
Este sería como el esqueleto de nuestra página o aplicación web, es lo que define la estructura del sitio.

### **CSS**
Este será el lenguaje que va permitir añadir la creatividad a nuestro sitio, añadir propiedades y características a los elementos de nuestro sitio será la principal función a cumplir.

### **JavaScript**
Este será el lenguaje que nos va ayudar a darle uan funcionalidad a los elementos de nuestro sitio, el cerebro de nuestras aplicaciones.

### **Frameworks**
> Esto aplica tanto para FrontEnd como BackEnd

Estas serán variantes del propio lenguaje de JavaScript que ayudarán a crear funciones más fáciles o anidar funcionalidades adicionales a JavaScript nativo. Lo cual se resume en herramientas para facilitar la programación de ciertas funciones que se desean crear.

JavaScript llega a ser la base principal de muchos de los Frameworks de la red. Algunos de FrontEnd son:
* React JS 
* Vue JS 
* Angular 
* Ember JS 
* Svelte
* Entre otros.

## **Herramientas a usar para FrontEnd**
## **Herramienas de diseño**
Recordando el ciclo de vida del desarrollo de software, lo primero a realizar es el diseño del problema para poder programarlo, y en caso de que ocurra un cambio sea más fácil realizarlo.

El objetivo de esta fase es aterriza las ideas del software que se solicite. Aquí es importante ver que el diseño abarca dos cosas: 
* Wireframes 
* Interfaces gráficas

De modo que los wireframe puede ser atterizados por medio de diagramas de flujo mientras que las interfaces gráficas pertenece ya directamente a la interfaz que el usuario va a observar.

### **Wireframes**
Esta fase es para entender bien las necesidades y lo que debe de cumplir la aplicación, de modo que se tendrá que empezar a dibujar entorno a esta idea de abarcar y entender las necesidades antes de dibujar pensando en el lado estético. 

En esta sección se podrá analizar sobre los bordes, zonas de click, botones, todo aquel elemento necesario que deberá de presentar la aplicación. 
Para esto, las herramientas recomendadas son:

* Miro board

    Este es un pizarrón blanco en línea que literalmente es usado para plasmar ideas acerca de proyectos o cualquier cosa de forma colaborativa o individual.

*  Balsamiq Wireframes
    
    Es una herramienta que ayuda a plasmar las interfaces de usuarios que tenemos en mente, ya nos da elementos para que esta tarea sea rápida.

* Dibujar en papel físico

    Las ideas pueden ser simplemente plasmadas en una hoja común.


### **Interfaces gráficas**

Cuando ya se haya terminado con la parte del wireframes y entendido todas las necesidades a cubrir por parte de nuestra aplicación ya será posible entrar en el terreno de las interfaces gráficas. Aquí será importante el uso de colores, las interacciones y formas de estos elementos para que sean atractivos.

Las aplicaciones recomendadas para esta tarea es, aunque también pueden servir para la parte de wireframe:

* Sketch
    
    También es otra aplicación que nos permite colaborar en tiempo real, además. Está enfocada para el diseño de una aplicación, no obstante solo está disponible para MacOs.

* Figma

    De igual forma permite la colaboración para el diseño en equipos.

* Adobe XD

    Programa enfocado para el diseño de UI/UX, además de otras cosas.

> Estos programas son de paga, pero los últimos dos tienen versiones gratuitas que pueden ser de gran ayuda.


## **IDE**
Las palabras IDE hacen referencia a un entorno de desarrollo, el cual es un herramienta que va a combinar varias herramientas para que al final sea una más fácil realizar tareas de desarrollo. Un ejemplo sería realizar la compilación en un lenguaje de programación, donde tan solo al dar un click nuestro código se va ejecuta. También son caracterízados para la detección de errores, un ejemplo sería que al tener un error de syntaxis (escribir mal una instrucción en el lenguaje) el IDE será capaz de detectarlo e informar sobre el error y en ocasiones hasta el cómo corregirlo o dónde surge, otras funciones sería el autocompletado de palabras y automatizar tareas como la compilación.

Una tarea importante que también hacen es la depuración, o el debug que sería ejecutar punto por punto o en una cierta sección para observar el comportamiento del código en esa sección.

Hay IDE orientados directamente a un solo lenguaje como DEV-C++ que está para C++, pero también hay otros como Atom o Visual Studio code con una alta variedad de extensiones para personalizar.

Un editor de texto es diferente a un IDE, debido a que un editor de texto solo se dedica a detectar el lenguaje programado y ya, es como un block de notas más elegante y cómodo. No obstante, un IDE ya trae también incorporada esta función.

## **Importancia de los navegadores web**
Algo que se debe de tener en mente es que las aplicaciones web o páginas web deben tener la habilidad de ser ejecutadas en distintos navegadores web de forma que puedan ejecutarse y siga funcionando de forma normal sea cual sea el navegador que se trate.

No obstante, la realidad es que no todos los navegadores tienen la capacidad o tratan igual a la tecnología usada para la creación de las páginas. 

Por lo cual, teniendo en cuenta el problema anterior será necesario entonces saber qué navegadores será posible usar las tecnologías que empleamos para la generación de sitios, y para esto existe Can I use: https://caniuse.com/.

El funcionamiento de la página consiste en colocar ahí el lenguaje que se quiere emplear y se va a desplegar un listado de los navegadores web que soportan dicha herramienta y son compatibles.

## **Developer tools**
Estas son herramientas que nos informan sobre nuestra aplicación y cosas sobre cómo es posible mejorarlas. 

La herramienta más conocida es Lighthouse de Google (https://developers.google.com/web/tools/lighthouse?hl=es) 

Esta herramienta nos dará una auditoría del status de nuestra aplicación en distintas áreas de la cual la más importante, además del rendimiento buenas prácticas, es la accesibilidad de nuestra aplicación. La acccesibilidad es una parte fundamental, una cosa es que se pueda ingresar a la página facilmente y otra cosa es que cualquier persona sea capaz de usarla y para esto se puede usar el ejemplo de personas con alguna capacidad que le impida interactuar con toda nuestra aplicación.

Es necesario pensar en ese tipo de situaciones, para esto es necesario hacer uso de guías para conocer sobre los usos adecuados de accesibilidad. Un ejemplo de ello es: 

DevTools (https://www.deque.com/axe/devtools/) 

Herramienta para informarnos sobre los errores existentes de nuestro desarrollo y también dará información sobre cómo solucionarlos.

## **Documentación**
Esto es una parte fundamental para el desarrollo de nuestras aplicaciones, debido a que un proyecto sin ninguna información sobre cómo se realizó provocará un caos a la hora de querer corregir, añadir funcionalidad o que un nuevo desarrollador entre al juego.

Una buena práctica será siempre documentar nuestras aplicaciones y para esto nos podemos apoyar de:
* API Doc (https://apidocjs.com/) 
* Rails Admin (https://github.com/railsadminteam/rails_admin) 
* Atlassian es Confluence (https://www.atlassian.com/es/software/confluence)
* Notion (https://www.notion.so/)

Los cuales son programas que van a generar un sitio con nuestra documentación, de modo que se estará realizando separaciones de cada apartado.

Las partes importantes que debe de considerarse en la documentación es:

1. A quién va dirigida la documentación 

    Para esto se deberá de pensar sobre quién leera la documentación para saber hasta donde podemos utilizar lenguaje formal de programación o hasta donde explicar detalladamente el funcionamiento de ciertas funciones, etc. No será lo mismo que lo lea un administrador a que lo lea un desarrollador.

2. Problematica a solucionar

    Este sería en sí el objetivo de nuestro código, del proyecto, o de una actualización realizada para llevar un control sobre la nueva información incorporada. Además de informar sobre las formas de entrada y salida de los datos.

3. Estructura de la aplicación

    Una aplicación o página web tendrá que tener varias secciones, desde una vista general (inicio) hasta información más específica dentro de nuestros sitios. Es por esto mismo que será necesario documentar desde lo más general hasta lo más específico, desde el menú hasta la sección más profunda del sitio.

## **Estructura web**
La estructura web se refiere a cómo la aplicación o sitio web está ligada a otras páginas, visto desde la interacción interna de links y llamados internos.

Es simplementae la forma de cómo estará organizado la información dentro de nuestra aplicación. Esto es importante ya que define el cómo será leido y consultado la información dentro de nuestras aplicaciones.

## **Contenido jerárquico**
Este hace referencia directamente de ir a lo más general a lo más particular, por lo cual será lógico pensar sobre una página principal con la imformación más importante del sitio para después en cada click ir más y más profundo del sitio, o sea ir a lo más particular.

### **Homepage**
Página inicial en donde la información más relevante será visible y debe estar ligada a esta con el fin de tener una navegación más cómoda y rápida.

Aquí será importante la incorporación de todos aquellos elementos como botones, sliders, menús y diferentes interacciones para que el usuario pueda encontrar todo de una manera más rápida.

### **Menú/Navegación**
Es donde el usuario podrá identificar la información que contiene la página, ya sea ver las categorías u otros datos para encontrar lo buscado.

Las categorías principales e información más importante deberán estar en el menú, en la página principal.

Consideraciones para esto:

1. Usar descripciones cortas para cada elemento, facilitar lectura.
2. Lenguaje simple y claro.
3. Buscar un orden de prioridad de la información.
4. Las URLs deben ser intuitivas (iE. tusitio.com/contacto)
5. Usar subcategorías como parte de la jerárquia las cuales se despliegan de una categoría padre.
6. Poner en el pié de página los términos y condiciones para que no sea tedioso leer toda esa info desde el principio.

Para realizar esta búsqueda y navegación es posible emplear diferentes formas, pero la más común es NavBar:

!["NavBar"](https://i.stack.imgur.com/cSNfw.png)

### **Categorías y subcategorías**
Se debe de pensar en las categorías como la agrupación de información en común la cual debe de brindarle una vista generar sobre un conjunto de información, mientras que las subcategorías son para dar información más detallada.

De forma que las categorías serán vistas desde la página principal de modo que deben de funcionar como una especie de mapa para que el usuario sepa en dónde ir para obtener una información en específico. De modo que las subcategorías darán información más detallada.
 
Como una tienda donde se puede dividir en frutas/verduras, carnes, cereales, etc. De modo que si una persona quiere comprar pescado debería ir a la categoría de carnes.

### **Páginas individuales / finales**
Es donde ya no hay más categorías puesto que será el final y por ende será en donde descance la mayor cantida de información de nuestra aplicación. Un ejemplo sería la misma persona en la tienda donde se encuentra con una gran variedad de diferentes peces, de ahí escoge uno y después se ve obligado a escoger un tipo de corte, etc, hasta llegar con algo muy particular de modo que ya no hay más, es el final.

Se debe de tener información de contacto en esas páginas o la información que llegue a necesitar el usuario. Así como brindar información para que sea posible llegar hasta esas páginas.

## **Modelo secuencial**
Este tipo de modelo hace referencia a que el usuario deberá seguir una serie de pasos en secuencia para usar la aplicación. El uso de la aplicación se detecta como un flujo de pasos, y no podremos salir de ella.

## 