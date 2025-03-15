# clean code

clean code es un libro de buenas practicas de programagacion escrito **Robert C. Martin**, el mismo inicia indicando que "si lees esto es por dos razones, eres programador y quiere ser mejor programador, que bueno, necesitamos mejores programadores"

## primer capitulo, introduccion

en este libro se va a vewer mucho codigo, tanto codigo que al terminar con el libro vamos a saber diferencia buen codigo de mal codigo y el como transformar mal codigo en buen codigo

si bien hoy en dia se cuestione la continuidad de la figura del "programador" o "el codigo" debido a la constante busqueda de lenguajes que automaticen la programacion o que se enfoquen en ambitos especificos, o inclusive la aparicion de las IA, jamas desaparecera el codigo, ya que nadie puede mediante vagos sentimiento o expresiones redactar bien los requerimientos del programa (algo tan formal e importante como el codigo en si mismo), hasta que no se pueda crear un lenguaje que haga que la maquina entienda a la persona y no que la persona se de a entender a la maquina, vamos a seguir teniendo programadores

### codigo malo

el autor se enoja con otro autor(Kent Beck) al mencionar en un libro propio que "el codigo bueno importar" era una fragil premisa, para Roberto era una premisa principal, el a visto empresas fundirse por mal codigo, muchas veces uno esta apurado, por tiempos de entrega por que tiene que correr a hacer otras partes del proyecto, porque se atraso, por lo que sea, sin embargo codigo que se hace mal atrasa mas que el retraso en si mismo ya que existe un fenomeno descrito como "wading" que consiste en ir vadeando en el codigo, esto se refiere a que el mal codigo en el intento de entenderlo atrasa mas que el tiempo de desarrollo, respecto de "dejarlo asi, despues lo corrijo" el autor hace alusion a la ley de Le' Blanc: mas tarde equivale a nunca

### el costo total de un desastre

si llevas programando el suficiente tiempo seguramente el codigo enquilombado de otro programador te a retrasado, el mal codigo retrasa, en una empresa se puede dar que el atraso lleve a que la misma contrate mas oprgramadores que terminen atrasando mas ya que estos saben menos del proyecto que los programadores ya existentes por tanto retrasan mas el proyecto

### el gran rediseño

el autor parece relatar sus propias vivencias, habla de un famoso "gran rediseño" que aparece luego de que los desarrolladores infieran que el proyecto no puede continuar asi y demandan a la empresa que de luz verde a un rediseño que permita mejorar las condiciones del codigo viejo, el asunto con esto es que ahora la mtad de los developers estan trabajando en el sistema viejo y mal hecho y la otra mitad esta apurada en el rediseño haciendo que para cuando termina sea mas rentable hacerle  a este rediseño un rediseño

### attitude y the primal conundrum

aca menciona el como los messed code son en realidad nuestra culpa, las deadlines las pone el pm ahora el que estirarlas en post del buen codigo depende enteramente de nosotros,es prioridad en nosotros hacernos cargo de lo que nos toca, hacer buen codigo antes que cualquier otra cosa, la unica manera de ir rapido es haciendo buen codigo

### el arte del codigo limpio

al igual que en el arte reconocer buen arte no significa saber hacer buen arte, lo mismo con el codigo, hacer buen codigo e identificar buen codigo no van de la mano

### que es codigo limpio

aca el autor cita a varias eminencias de la programacion

#### Bjarne Stroustrup (inventor de c++)

*"me gusta mi codigo elegante y eficiente, tiene como mojetivo que los bugs sean dificiles de ocultar, las dependencias faciles de mantener, el manejo de eerrores completado mediante a una articulada estrategia, y la performance cercana a la optima para no tentar a la gente a hacer codigo enquilombado para optimizaciones innecesarias, el codigo limpio hace una cosa"*

#### Grady Booch (autor de Object Oriented Analysis and Design with Applications)

*"el codigo limpio es simpe y directo, se lee como una prosa bien escrita, este nunca oscurese el intento de diseño sino que esta lleno de crispadas abstracciones y lineas de control directas"*

#### Ward Cunningham (inventor de wiki, el motivador de patrones de diseño, lider en el desarrollo de smalltalk y el padrino de todos los que les importa el buen codigo)

*"sabes que que estas trabajando en codigo limpio cuando cada rutina que lees es mas linda de lo que esperabas, podes decir que es codigo hermoso cuando el codigo te hace ver como si el lenguaje utilizado estaba hecho para el problema"*

### escuelas de pensamiento

y que piensa el tio bob (el mismo) sobre esto?, el autor hace un paralelismo con las artes marciales, existen varias escuelas con distintas tecnicas en cada una y hasta distinta filosofia, ahora el alumno puede centrarse en una y meujorar en la misma pero a la larga el mismo puede estudiar en distintqas escuelas aprnder distintas tecnicas, crear las suyas propias en inclusive crear su propia escuela, uno debe aprender de tantos autores como pueda ya que asi podra encontrar su propia escuela de como programar

### nosotros somos los autores

somos programadores, aprendemos de otros programadores pero somo autores de nuestro propio codigo por tanto nuestras enseñanzas deben ser transmitidas tanto como la de los autores en quienes nos inspiramos

### ley del boy scout

siemopre hay que dejar las cosas mejor que como las encontramos, sin vemos codigo malo tenemos que esfrozarnos en dejalro mejor que como lo encontramos