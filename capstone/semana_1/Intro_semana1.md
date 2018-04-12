## Presentación del proyecto y de los datos

Habéis tenido nunca la ocasión de contemplar el cielo en una noche despejada, sin luna, y lejos de las luces de las ciudades? El ojo humano es capaz de captar solo una pequeña parte de los mile de millones de estrellas que nos rodean.

## Las galaxias
El sol es una de las muchas estrellas que forman parte de nuestra galaxia: la vía láctea.
Observando las estrellas más lejanas, podemos ver cómo se agrupan formando galaxias, como la vía láctea, de distintas formas y tamaño. Sus forma, tamaño y brillo nos revelan cómo se forman y evolucionan.

## Astronomía y Big Data
Potentes telescopios escanean el cielo y recogen fotos en formato digital de galaxias lejanas. Son capaces de recoger imágenes de galaxias que a simple vista sería imposible ver. Aun así, tenemos información de solo una fracción despreciable del enorme cantidad (centenares de miles de millones) de galaxias del que está poblado nuestro Universo.
La Cosmología es la ciencia que estudia cómo el Universo ha nacido, ha evolucionado, para poder entender cuál podría ser su destino. Conocer los distintos tipos de galaxias y clasificar su forma es uno de los pasos fundamentales para el avance en el conocimiento del Universo en que vivimos.
La clasificación de imágenes de galaxias basadas en su forma, es el objetivo del proyecto final de esta especialización, que hemos preparado para ti. Con este objetivo tendrás la oportunidad de aplicar algunas de la técnicas de análisis y clasificación de Big Data que has ido conociendo durante los cursos y las semanas pasadas.  

## Clasificación

La galaxias se pueden clasificar en muchas formas distintas, pero la más común es por su foma, que depende de su edad, composición, etc.

Clasificar una galaxia por su forma no es siempre tarea fácil. Lo tipos más reconocibles de galáxias son las espirales y elípticas, pero hay muchísimos estados intermedios, o algunas de forma irregular que, junto con el tamaño, la orientación del objeto y la resolución de la imagen, puede dificultar el trabajo del clasificador.
 
## GalaxyZoo

El proyecto GalaxyZoo https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/ consiste en recolectar datos sobre la forma de los objetos celestes fotografiados por unos telescopio opticos.

(enseñar ejemplos de imagenes...)

El objeto al centro de la imagen es el que hay que clasificar, y para llevar al cabo esa tarea el proyecto prevé la colaboración de voluntarios que, a través de una pagina web, visualicen imágenes en su ordenador personal y las clasifiquen. El resultado se envía a través de la misma página web.

Los objetos representados en las imágenes se clasifican  según los siguientes criterios:
a. La imagen de la galaxia va disminuyendo gradualmente desde el centro

b. La imagen tiene estructuras, que pueden ser:

* los brazos de una galaxia espiral
* un núcleo, o unas barras, u otras características peculiares
* una estrella, o una traza de satélite, o algún otro artefacto que obstaculice la posibilidad de clasificar el objeto

En el enlace https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/classify podéis encontrar (en inglés) un tutorial.
 
# Data Set

Los datos que se van a utilizar en este proyecto final son:
* un sub-set de imágenes de galaxias tomadas por el telescopio de un proyecto llamado Sloan Digital Sky Survey (SDSS).
* un fichero que contiene sets de parámetros asociados a cada imagen de galaxias (identificador único en el catálogo de SDSS, posición en el cielo, brillo, etc.)
* un subset de los resultados de la clasificación web hecha a través del proyecto Galaxy Zoo, que vendrá proporcionado en las siguientes semanas

Con estos datos y con la herramientas que ya han sido presentadas en el curso de esta especialización, te guiaremos en las próximas semanas para que puedas desarrollar y  finalmente presentar a un imaginario comité científico tu método de clasificación y análisis de galaxias basados en herramientas Big Data para poderlo aplicar a las miles de milliones de galaxias observadas. 

# Herramientas

La herramientas que vamos a utilizar son:
HDFS y sus comandos de consola para la ingestión de datos.
* Hive y su cliente beeline para la creación del modelo de datos, la importación de los datos externos, su exploración preliminar y su análisis posterior.
* Spark (web) para el análisis, visualización e interpretación de los resultados.
(Comprobar si falta algo más)

Estas herramientas se van a proporcionar mediante la máquina virtual de Cloudera (referencia a las instrucciones).