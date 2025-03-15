# calidad de codigo

deuda tecnica: hacer las cosas rapido para sacarlo lo antes posible, la deuda realmente son las cosas que sacrificamos en cuanto a calidad a cambio de sacar un proyecto lo antes posible

a menos mantenible sea el codigo menor sera su rendimiento al largo plazo (el siu guarani)

## la unica manera valida de medir la calidad del codigo

la manera matematica de medir esa calidad es con el sistema WTFs/minuto

## objetivos de buen codigo

- Mantenibilidad
- Simplicidad
- Claridad
- Flexibilidad
- Legibilidad

## tips de clean cod

- Nombre significativos y pronunciables, que revelen la intencion
- los metodos tienen un unico concepto
- single responsability
- tener un solo nivel de abtraccion por funcion
- max 8 lineas por metodo
- evitar switch
- argumentos (a menos mejor)
- DRY (do not repeat yourself)
- boy scout (dejar las cosas mejor que como las encontramos)

## comentarios

tambien se mantienen

### malos

- el que explica todo
- redundancia
- comentario erroneo
- comentarios obligatorios
- comentarios tipo diario
- ruido
- marcadores de posicion
- codigo muerto

### buenos

- legales
- informativos
- explicar una intesion
- advertencias de consecuencias
- TODO
- ampliar informacion

## Formato de los archivos

es para mejorar el formato general del proyecto

usar excepciones

test unitarios: FIRST 

- Fast 
- Independent
- Repeteable
- Self Validating
- Timely

- No hay nada mas importante que escribir codigo de calidad para el exito del proyecto
- Leer codigo deberia ser como leer una novela
- Cualquier tonto escribe codigo que una pc pueda entender, un buen programador escribe codigo que los humanos puedan leer

## criterios de buen diseño

### sintomas de un mal diseño

- rigidez
- fragilidad
- inmovilidad

- carateristicas de un buen diseño: alta cohesion bajo acoplamiento
- hacer SOLID
