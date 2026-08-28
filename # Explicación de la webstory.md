# Explicación de la webstory

#### Leer es una actividad cultural que forma parte de la vida diaria de los chilenos. Sin embargo, mantener un hábito lector implica distintos costos dependiendo de la frecuencia con que se lee, el formato utilizado y la manera en que se accede a los libros. Comprar libros nuevos es solo una de las alternativas disponibles, ya que también existen bibliotecas, libros de segunda mano, formatos digitales y audiolibros.
#### La Encuesta Nacional de Participación Cultural y Comportamiento Lector 2024 (ENPCCL) permite conocer cómo se relacionan los chilenos con la lectura, considerando aspectos como la cantidad de libros leídos, la frecuencia de lectura y los formatos utilizados. Estos datos permiten establecer distintos perfiles de lectores y estimar cuánto podría costar mantener sus hábitos de lectura.
#### Sin embargo, conocer la cantidad de libros que leen las personas no permite determinar por sí solo cuánto cuesta mantener ese hábito. El precio de los libros varía según características como género, editorial, formato, número de páginas y lugar de compra. Por esta razón, el proyecto propone construir una base de datos propia con los precios y características de libros disponibles en librerías chilenas y cruzarla con la información sobre hábitos lectores.
#### A partir de este cruce será posible estimar cuánto dinero podría gastar anualmente una persona dependiendo de su frecuencia de lectura y comparar distintas formas de acceder a los libros. De esta manera, el proyecto busca mostrar la lectura no solo como una actividad cultural, sino también desde su dimensión económica, relacionando cuánto leen los chilenos con cuánto les cuesta hacerlo.

### Pregunta e Hipótesis
__***¿Cuánto cuesta tener un hábito lector en Chile considerando los precios de los libros, la frecuencia de lectura y las distintas alternativas para acceder a ellos?***__

_Mientras mayor sea la frecuencia de lectura, mayor será el gasto anual asociado a mantener el hábito cuando el acceso a los libros depende principalmente de su compra._

#### La Encuesta Nacional de Participación Cultural y Comportamiento Lector 2024 constituye uno de los principales antecedentes para comprender los hábitos de lectura en Chile. Esta encuesta permite conocer aspectos como la cantidad de libros que leen las personas, la frecuencia con que leen y los formatos utilizados.
#### Los resultados muestran que la lectura no se limita a un único formato, sino que pueden coexistir los libros impresos y digitales. Esta información es relevante para la investigación porque el costo de mantener un hábito lector puede variar dependiendo de la forma en que las personas acceden a los contenidos.
#### Por otra parte, los precios de los libros presentan diferencias según sus características y el lugar donde se comercializan. Una novela, un ensayo o un libro infantil pueden tener precios diferentes incluso cuando pertenecen a una misma editorial o presentan características similares. Sin embargo, la información disponible sobre el mercado editorial suele mostrar estos precios de manera separada, sin relacionarlos directamente con la frecuencia con que las personas leen.
#### Por ello, el proyecto busca abordar el problema desde una perspectiva económica y de datos, relacionando dos dimensiones que normalmente se presentan por separado: los hábitos lectores de los chilenos y el costo económico de acceder a los libros.

### Datos
Para probar la hipótesis se necesitan datos de dos dimensiones principales:
1. Hábitos de lectura
    * Libros leídos al año en promedio.
    * Frecuencia de lectura.
    * Formato utilizado: físico, digital o audiolibro.
    * Edad.
    * Región.
    * Motivos para leer.
    * Forma de acceso a los libros.
2. Características y precios de los libros
    * Número de páginas.
    * Género.
    * Editorial.
    * Autor.
    * Formato.
    * Librería.
    * Título.
    * Fecha en que se registró el precio.
    * Precio.
    * Precio por cada 100 páginas.
#### La principal fuente disponible es la Encuesta Nacional de Participación Cultural y Comportamiento Lector 2024, que entrega información sobre los hábitos lectores de la población chilena.
#### Además, ya se identificaron diferentes librerías y plataformas que pueden utilizarse para construir la base de precios:
* Feria Chilena del Libro.
* Librería Antártica.
* Contrapunto.
* Buscalibre.
* Green Libros.
* Storytel.
* ChileBooks.
#### Los datos sobre hábitos lectores provenientes de la ENPCCL 2024 son públicos y se encuentran disponibles a través del Ministerio de las Culturas, las Artes y el Patrimonio.
#### Los precios de los libros también son datos públicamente observables, ya que se obtendrán directamente desde los catálogos online de las librerías. Sin embargo, estos precios corresponden al momento específico en que se realiza la consulta y pueden cambiar posteriormente debido a ofertas, promociones o modificaciones de precio. Por esto, se registrará la fecha de consulta.
#### Los datos de hábitos lectores provenientes de organismos oficiales serán considerados de alta confiabilidad, debido a que corresponden a una encuesta nacional realizada mediante una metodología definida.
#### Los precios obtenidos desde las librerías son verificables porque provienen directamente de sus catálogos. Sin embargo, tienen una limitación: pueden cambiar con el tiempo. Por ello, se debe registrar la fecha en que se obtuvo cada precio y evitar presentarlos como valores permanentes.

#### Principalmente necesitamos construir la base de datos propia de precios de libros, registrando una muestra de aproximadamente 100 a 200 libros disponibles en distintas librerías chilenas.
#### Con esta información podremos calcular:
* Precio promedio.
* Precio mínimo y máximo.
* Precio promedio por género.
* Precio promedio por editorial.
* Precio según formato.
* Precio según número de páginas.
* Precio por cada 100 páginas.

### Preguntas a responder:
1. ¿Cuánto cuesta en promedio un libro en Chile?
2. ¿Cuánto gastaría al año una persona que lee 1, 2 o más libros al mes?
3. ¿Qué géneros literarios tienen los precios promedio más altos?
4. ¿Existe una relación entre el precio de un libro y su cantidad de páginas?
5. ¿Cuál es el precio promedio por cada 100 páginas?
6. ¿Qué formatos pueden resultar más económicos?
7. ¿Cuánto cambia el gasto anual dependiendo de la frecuencia de lectura?
8. ¿Existen diferencias en los hábitos lectores según edad o región?
9. ¿Cuánto podría ahorrar una persona utilizando libros usados, bibliotecas o formatos digitales?
10. ¿La percepción de que los libros son caros coincide con los precios observados?

### Webstory
#### La historia busca mostrar que leer también tiene un costo económico, pero que este costo no es igual para todas las personas. Depende de cuánto leen, qué tipo de libros consumen, en qué formato los leen y cómo acceden a ellos.
#### Lo novedoso del proyecto es cruzar información que normalmente aparece separada: por un lado, los datos sobre cuánto y cómo leen los chilenos y, por otro, los precios reales de los libros disponibles en el mercado chileno. Este cruce permitirá transformar los datos sobre hábitos lectores en una estimación concreta del gasto anual.
#### La webstory podría mostrar, por ejemplo, cuánto tendría que gastar una persona que lee un libro al mes frente a otra que lee uno por semana, y cómo ese costo puede cambiar si utiliza libros digitales, usados, bibliotecas u otras alternativas.
#### Además, se podría incorporar una calculadora de costo anual de lectura, en la que el usuario ingrese cuántos libros lee y pueda estimar cuánto gastaría según distintos precios y formatos. El resultado máximo planteado por el proyecto contempla precisamente que cada usuario pueda calcular su propio costo anual y comparar distintas formas de acceder a los libros.
### Posibles elementos:
1. Calculadora interactiva de hábito lector: El usuario podría seleccionar la cantidad de libros que lee al mes, el formato, y un precio aproximado del libro.
**La herramienta mostraría el gasto mensual y anual estimado.**
2. Gráfico comparativo: Un gráfico podría comparar cuánto gastaría una persona leyendo: 1 o 2 libro al mes, 1 libro por semana.
**Esto permitiría visualizar inmediatamente cómo aumenta el gasto según la frecuencia de lectura.**
3. Gráfico de precio por género: Permitiría comparar el precio promedio de novelas, ensayos, libros infantiles, etc.
4. Gráfico precio/páginas: Podría mostrar si los libros más extensos necesariamente tienen un precio proporcionalmente mayor, utilizando el indicador de precio por cada 100 páginas.
5. Comparador de formatos: Un elemento interactivo podría comparar el costo de acceder a un mismo libro mediante diferentes formatos o alternativas.

### Posibles resultados de la investigación:
#### Con los datos disponibles, lo mínimo que podremos contar como historia es: Cuánto cuesta en promedio un libro y cuánto gastaría anualmente una persona según distintos niveles de frecuencia de lectura. Por ejemplo, podremos construir escenarios para personas que leen un libro al mes, dos libros al mes o un libro por semana.
#### En cambio, en el escenario más completo, podríamos construir un panorama del costo económico del hábito lector en Chile, relacionando: hábitos de lectura, precio, género, editorial, formato, páginas y alternativas de acceso. Además, la investigación podría incorporar una calculadora que permita a cada usuario estimar su propio costo anual de lectura y comparar diferentes formas de acceder a los libros.