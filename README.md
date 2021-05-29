# DIU21
Prácticas Diseño Interfaces de Usuario 2020-21 (Tema: Turismo) 

Grupo: DIU1_TeamAlpacas.  Curso: 2020/21 
Updated: 14/5/2021

Proyecto:

![Appestruznegro](https://user-images.githubusercontent.com/62596996/118160645-de81d000-b41e-11eb-846e-47be72b920fe.png)![Appestruzbnnegro](https://user-images.githubusercontent.com/62596996/118161327-bb0b5500-b41f-11eb-8d84-51e316147fe0.png)


Descripción: 

Appestruz es una aplicación disponible en varios idiomas que te permite tanto planificar viajes como gestionar aquellos que ya tengas de forma muy visual. Además, no requiere registro previo para buscar información, y te mantiene al día con las últimas noticias relevantes, y con posts de la comunidad. 


Miembros
 * :bust_in_silhouette:  Jesús López Rodríguez  [@susolr](https://github.com/susolr)                :octocat:     
 * :bust_in_silhouette:  María Esmeralda Jiménez Martínez [@esmeraldajm](https://github.com/esmeraldajm)  :octocat:

----- 




# Proceso de Diseño 

## 1. Investigación y análisis de experiencias de usuario

![Método UX](img/Competitive.png) Análisis competitivo:
-----

Para empezar, hemos analizado algunas aplicaciones parecidas a la que vamos a desarrollar, de forma que podamos tomar inspiración de ellas, y prestar más atención en aquellos aspectos de los que carecen. En concreto, hemos analizado las siguientes: Inspirock, Roadtrippers, Tripit y Lambus.

A pesar de que todas ellas cuentan con una amplia variedad de recursos y puntos de interés, creemos que necesitan prestar más atención a las diferencias que se generan al cambiar entre países (idioma, moneda, etc.), y así ampliar su público objetivo.

![competitive_analysis](https://user-images.githubusercontent.com/62568912/118197248-d9d51000-b44e-11eb-8cbb-c3d503470747.png)


Por la versatilidad que posee, vamos a analizar Inspirock.


![Método UX](img/Persona.png) Personas ficticias:
-----

Queríamos cubrir los segmentos de mercado más interesantes: un joven estudiante con recursos limitados y una mujer de mediana edad en busca de experiencias emocionantes. 

Mateo Kroos: 

[![mateo](https://user-images.githubusercontent.com/62596996/118166867-4daef280-b426-11eb-8b3b-b065ef7a1068.png)](https://github.com/susolr/DIU21/blob/master/P1/ficha_mateo.PNG)

Nuria Vargas: 

[![nuria](https://user-images.githubusercontent.com/62596996/118166888-556e9700-b426-11eb-9524-79cb1bd56192.png)](https://github.com/susolr/DIU21/blob/master/P1/ficha_nuria.PNG)



![Método UX](img/JourneyMap.png) Mapas de experiencias de usuario:
----

Procedemos entonces a simular como reaccionarían, tanto Mateo como Nuria, al enfrentarse a escenarios predefinidos:

Mateo Kroos: 

[![mateo](https://user-images.githubusercontent.com/62596996/118166867-4daef280-b426-11eb-8b3b-b065ef7a1068.png)](https://github.com/susolr/DIU21/blob/master/P1/journey_mateo.PNG)

Nuria Vargas: 

[![nuria](https://user-images.githubusercontent.com/62596996/118166888-556e9700-b426-11eb-9524-79cb1bd56192.png)](https://github.com/susolr/DIU21/blob/master/P1/journey_nuria.PNG)


![Método UX](img/usabilityReview.png) Revisión de usabilidad:
----
Tras hacer la revisión de usabilidad (usability review) de la página [Inspirock](https://www.inspirock.com/), hemos extraído las siguientes conclusiones.

-Enlace al documento: [usability_review](https://github.com/susolr/DIU21/blob/master/P1/Usability-review-Inspirock.xls) 

-Por los detalles descritos en ese documento, le hemos dado una puntuación a la página de 86/100.

-En general, esta página es bastante completa e intuitiva, pero, aun así, hay varios campos en los que podría mejorar (ej: idiomas y distribución de componentes en la interfaz).

Vamos a continuar con el análisis de esta página usando las siguientes herramientas.

## 2. Diseño de experiencias de usuario


![Método UX](img/feedback-capture-grid.png) Malla receptora de información, mapa de empatía y punto de vista:
----

Primeramente, hemos realizado un Feedback Capture Grid, recogiendo ideas que tendrían nuestras personas ficticias al entrar en Inspirock. En concreto, recogen estos cuatro aspectos:

 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  

![Malla](https://user-images.githubusercontent.com/62596996/118161578-0aea1c00-b420-11eb-8edc-6c7cb21ceab5.png)

Para seguir sintetizando las experiencias de Mateo y Nuria tras usar Inspirock, hemos realizado un mapa de empatía, escribiendo las ideas de Mateo en azul, y las de Nuria en magenta:
  
![MapaEmpatia](https://user-images.githubusercontent.com/62596996/118162169-bdba7a00-b420-11eb-970f-05cd87bda1fe.png)

Por último, hemos descrito los puntos de vista de ambas personas ficticias, y de una tercera persona más, para completar aún más la recopilación de experiencias:

![POV](https://user-images.githubusercontent.com/62596996/118162186-c1e69780-b420-11eb-80c3-d4c3b7bbb935.png)

  

Nuestra propuesta parte de toda la información que hemos recogido de los apartados anteriores, desarrollando aquellos aspectos esenciales que una aplicación de viajes debe realizar (planificar y gestionar viajes), pero ofreciendo más funcionalidades que pueden hacerla destacar del resto (una amplia sección de noticias y comunidad, además de un apartado de configuración que te permite adaptar la aplicación en función de tu idioma y el país en el que residas).


![Método UX](img/ScopeCanvas.png) ScopeCanvas:
----

Para comenzar con nuestra idea, realizamos un ScopeCanvas, concretando en un mismo lugar las necesidades, propósitos, objetivos, acciones y métricas que se desean alcanzar. Así conseguimos centrarnos para empezar con el proceso de desarrollo.

![ScopeCanvas](https://user-images.githubusercontent.com/62596996/118161652-21907300-b420-11eb-9407-d86226b39145.png)


![Método UX](img/Sitemap.png) Análisis de tareas:
-----

Mediante el uso de un Task Flow, delimitamos las funcionalidades de nuestra aplicación, y la importancia que dichas tienen en función del público que estemos analizando. Además, determinamos cuáles de ellas son las más importantes.

![TaskAnalysis](https://user-images.githubusercontent.com/62596996/118162329-e478b080-b420-11eb-933b-aee88329c70d.png)



![Método UX](img/labelling.png) Arquitectura de información: Mapa de la web y etiquetado:
----

En cuanto al mapa de nuestra aplicación, comenzamos desde la pantalla de Home, y, a través de ella, podemos acceder a las páginas principales, que a su vez nos darán acceso al resto de páginas, tal y como se puede observar en el siguiente esquema:

![Sitemap](https://user-images.githubusercontent.com/62596996/118161758-41279b80-b420-11eb-8176-e7484cff7f06.png)

Una vez tenemos diseñado el Sitemap, describimos la funcionalidad de cada una de las opciones que se encontrarán en nuestra aplicación:

![Labelling](https://user-images.githubusercontent.com/62596996/118161778-4684e600-b420-11eb-96e3-5b43b1a473ea.png)



![Método UX](img/Wireframes.png) Bocetaje:
-----

Para terminar con el bocetaje, diseñamos a grandes rasgos algunas de las páginas principales que tendrá nuestra aplicación:

![lo_fi](https://user-images.githubusercontent.com/62596996/118166005-41766580-b425-11eb-810e-3cdf5503e050.png)



## 3. Diseño de nuestro caso de estudio de experiencias de usuario

Pasamos ahora a la concreción de nuestro proyecto:

![Método UX](img/moodboard.png) Moodboard:
-----

Empezamos plasmando todas las ideas y recursos principales necesarios para el desarrollo en un solo tablón, como el logotipo que tendrá nuestra apliacación en varias versiones, la paleta de colores que se usará las fuentes y los iconos que se utilizarán, y, por último, imagenes de otras aplicaciones que nos vayan a servir de inspiración más tarde.

En cuanto al logotipo, hemos diseñado con Photoshop un avestruz sin patas, pero con un ala de avión. Esta imagen se podría usar, por ejemplo, como cabecera de Twitter, siempre que se inserte encima de un fondo de color sólido que contraste con el avestruz y con el color de las letras empleado.


![Moodboard](https://user-images.githubusercontent.com/62596996/118172180-5c98a380-b42c-11eb-9882-ddd8333002ce.png)


![Método UX](img/landing-page.png)  Landing Page:
----

Nada más entrar, aterrizamos en la Landing Page, que con colores vivos y una imagen llamativa, te invita a comenzar a planificar tu viaje, explicándote por qué deberías de usar nuestra aplicación.

![LandingPage](https://user-images.githubusercontent.com/62596996/118161899-6b795900-b420-11eb-8448-f0faefe481ee.png)


![Método UX](img/guidelines.png) Guidelines:
----

Para decidir qué Patrones IU y Guidelines queríamos usar en nuestra aplicación, hemos tomado inspiración de las siguientes páginas:

Diseños para utilizar con Adobe XD: https://www.adobe.com/es/products/xd/features/ui-kits.html#panel-3

Diseño para Apple: https://developer.apple.com/design/human-interface-guidelines/

Tras analizar ambas páginas, hemos decidido seguir los Patrones IU y Guidelines que ofrece Adobe XD en su kit de Google.


![Método UX](img/mockup.png) Maquetaje:
----

Llegamos por fin al último paso del diseño de nuestra aplicación, el layout Mockup, realizando bocetos Hi-Fi de las distintas páginas de nuestra aplicación.

![mockup](https://user-images.githubusercontent.com/62596996/118165418-8f3e9e00-b424-11eb-8b0b-51796eab8184.png)



![Método UX](img/caseStudy.png) Nuestro caso de estudio de experiencias de usuario:
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----

[TourGraná](https://github.com/raulrguez09/DIU21):

Esta aplicación nos ofrece información sobre las ofertas turísticas que se encuentran en la ciudad de Granada, ofreciendo la posibilidad de buscar aquello que más se ajuste a los deseos del usuario, para posteriormente darle la opción de reservarlo desde la propia página.

>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

Hemos usado un número de personas (tanto reales como ficticias) para realizar todo lo referido a la práctica.

![Usuarios](https://user-images.githubusercontent.com/62568912/120051424-e34ea280-c020-11eb-85e5-72e2e052bdf7.png)


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 

SUSAppestruz:

![SUSAppestruz](https://user-images.githubusercontent.com/62568912/120051441-f3ff1880-c020-11eb-9e84-da456b9fa8a5.png)

SUSTourGraná:

![SUSTourGrana](https://user-images.githubusercontent.com/62568912/120051449-fb262680-c020-11eb-9a49-ff7a722caf24.png)

En general ambas propuestas cuentan con un nivel más que aceptable, además de haber recibido puntuaciones bastante similares. Si que difieren en los sectores más críticos, aunque obviando estas puntuaciones más bajas la calificación que obtienen es bastante similar. 

![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)
[Usability-report](https://github.com/susolr/DIU21/blob/master/P4/DIU_report-template-usability-testOK-B-TourGrana.pdf)


>>> Valoración personal 

Durante el análisis de la propuesta de nuestros compañeros hemos visto que han conseguido elaborar una app muy intuitiva y fácil de usar, a la par que agradable. Sin embargo, si tuvieramos que poner una objeción, serían los serios problemas de contraste entre las letras y el fondo de la app, lo que la hace un poco difícil de ver en algunas situaciones. Obviando este último punto, el trabajo realizado por los compañeros es bastante bueno, ya que han conseguido desarrollar un producto muy bueno. 


## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













