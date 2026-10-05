# Práctica XML y DTD

# Nombre: Azkahira Ziret Yescas Diaz
# Expediente: 222213158

## Objetivo

## Ejercicio 1: Pedido
### Modelo propuesto
### Decisiones de diseño

## Ejercicio 2: Nota
### DTD externo
### DTD interno
### Pruebas realizadas

## Ejercicio 3: Matrícula
### Modelo
### Cardinalidad
### Restricción del atributo tipo
### DTD externo
### DTD interno
### Pruebas realizadas

## Conclusiones
### ¿Cuál es la diferencia entre XML bien formado y XML válido?
### R: El primero cumple las reglas sintáticas del lenguaje (etiquetas cerradas, 
### estructura de árbol); el segundo, además de estar bien formadom cumple las
### reglas de un esquema o DTD.

### ¿Qué función cumple un DTD?
### R: DEfine la estructura, elementos, atributos y reglas permitidas en un documento 
### XML para validar sus datos

### ¿Qué diferencia existe entre DTD interno y externo?
### R: El interno se escribe dentro del mismo archivo XML (en <!DOCTYPE [...[>); el 
### externo reside en un archivo separado ( .dtd) que se referencia

### ¿Cómo se expresa cardinalidad en DTD?
### R: Se expresa con operadores sobre elementos: ? (0 o 1), * (0 o más), + (1 o más), 
### o sin operado (exactamente 1)

### ¿Cómo puede restringirse un atributo a determinados valores?
### R: Definiendo una enumeración en <!ATTLIST>, listando los valores permitidos entre 
### paréntesis separados por tuberías, como (opcion1 | opcion2)

### ¿Qué ventaja proporcionó Git durante las pruebas?
### R: Permite registrar cambios paulatinamente, experimentar sin perder código funcional
### y volver a estados anteriores si surge un error

### ¿Qué utilidad tuvieron git diff y git restore?
### R: git diff muestra las diferecias exactas entre archivos modificados; git restore 
### rescata el archibo original descartando cambios no guardados 

### ¿Qué ventaja proporcionó una rama para desarrollar una solución alternativa? 
### R: Permite probar enfoques o soluciones distintas de forma aislada sin alterar la
### rama principal ni romper el código estable

