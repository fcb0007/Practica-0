# Manual de Markdown
## Títulos
>Para crear títulos pondremos una almohadilla `#`, si queremos un título más pequeño pondremos más almohadillas seguidas, hasta 6

### Método alternativo
Otro método para crear títulos del mayor tamaño sería poniendo debajo a lo largo del texto el símbolo `=` como en este ejemplo
>`Ejemplo`
>`=======`

Para el segundo mayor tamaño sería igual pero con el símbolo `-`

### Buenas prácticas
La sintaxis correcta se realizará dejando un espacio entre la almohadilla y el título:
`# Título`
  
## Párrafos
Para crear párrafos lo haremos como en un editor de texto normal, solo tendremos que dejar una línea en blanco:  
>Este es el manual de markdown.
>
>En este ejemplo vemos lo fácil que es  
>hacer un párrafo.

### Buenas prácticas
No dejaremos espacios ni tabulaciones al principio de los párrafos.
  
## Saltos de línea
Para realizar un salto de línea solo tendremos que dejar dos espacios o más al final y pulsar intro para seguir escribiendo en la siguiente:  
>Esta es la forma de realizar  
>un salto de línea.  
   
## Texto en negrita  
Para poner texto en negrita lo pondremos entre dobles asteriscos `**`.  
>Este texto se vería así **Ejemplo**  
  
## Texto en cursiva
Para poner texto en cursiva meteremos el texto que queramos entre asteriscos `*`.  
>Aquí tenemos un *ejemplo*.  
  
## Negrita y cursiva
Si queremos nuestro texto en negrita y cursiva usaremos triple asterisco `***` al principio y al final del texto.
>Así sería el resultado ***ejemplo***.
  
## Citas en bloques
Para crear bloques usaremos `>` antes del texto, aqui veremos un ejemplo
>Este es un ejemplo de bloque

## Bloques con varios párrafos
Si queremos crear párrafos dejaremos una línea en blanco Con un `>` al principio y después seguimos en las siguientes líneas con el símbolo también al principio
>Este sería un ejemplo de como
>
>creamos varios párrafos.
  
## Listas  
Podemos organizar el texto en listas

### Listas ordenadas
Para crear listas ordenadas solamente debemos poner un número seguido de un punto,  
no tenemos por qué seguir un orden pero siempre deben empezar por un uno.
>1. Primero
>2. Segundo
>3. Tercero

### Listas desordenadas
Para crear listas desordenadas podemos usar `-`, `+` o `*` seguido de un espacio al inicio de cada elemento de la lista,  
para crear listas anidadas solo tenemos que tabular los elementos que queramos.
>+ Elemento
>+ Elemento
>    + Elemento
>+ Elemento
  
## Imágenes
Si queremos insertar una imagen debemos hacerlo con esta estructura, primero una exclamación !, seguida del texto alternativo entre corchetes y la ruta relatva de la imagen entre paréntesis si se encuentra en nuestro repositorio o una url:    
`![Texto alternativo](/direcciondelaimagen)` o `![Texto alternativo](http://urldelaimagen.com)`
>![Logo Github](./git.png)
  
## Enlaces
Para crear un enlace, cerramos el texto en el que incrustaremos el en enlace entre corchetes `ej. [Texto]` a continuación el enlace entre paréntesis `ej, (http://enlace.com)`, nos quedará así `[Texto](http://enlace.com)`, aquí tenemos un ejemplo real:  
>[Manual de markdown](https://www.markdownguide.org/basic-syntax/)
  
## Código
Para dar formato de código a un texto lo acotaremos de dos comillas invertidas  (`). A continuación veremos un ejemplo:        
 
>En esta frase insertaremos `código`.

### Bloques de código
Podemos crear bloques de código delimitados colocando comillas simples triples ``` antes y después del bloque de código. Se recomienda dejar una línea en blanco antes y después de los bloques de código para facilitar la lectura del formato sin procesar.

 ```
   <html>
      <head>
      </head>
   </html>
````
  
## Tablas
Puede crear tablas con canalizaciones `|` y guiones `-`. Los guiones se usan para crear cada encabezado de columna, mientras que las barras verticales separan cada columna. Debes incluir una línea en blanco antes de tu tabla para que se representen correctamente.

>```
>|   Primera columna   |   Segunda columna  |  
>| ------------------- | ------------------ |  
>|   Contenido cleda   |   Contenido celda  |  
>|   Contenido celda   |   Contenido celda  |
>```   

Así se verá nuestro ejemplo:  

>|   Primera columna   |   Segunda columna  |
>| ------------------- | ------------------ |
>|   Contenido cleda   |   Contenido celda  |
>|   Contenido celda   |   Contenido celda  |

Las celdas pueden variar en el ancho y no es necesario que estén perfectamente alineadas dentro de las columnas. Debe haber al menos tres guiones en cada columna de la línea de encabezamiento.
>```
>| Columna | Columna |       
>| --- | --- |     
>| Contenido | Contenido  |     
>| Contenido | Podemos insertar un contenido más extenso y la tabla se adaptará a el |
>``` 

En este caso se vería así:      

>| Columna | Columna |   
>| --- | --- |   
>| Contenido | Contenido  |   
>| Contenido | Podemos insertar un contenido más extenso y la tabla se adaptará a el |

### Alinear contenido

Puede alinear el texto a la izquierda, a la derecha o centrarlo usaremos dos puntos `:` a la izquierda, a la derecha o a ambos lados de los guiones en la línea de encabezamiento.
>```
>| Alineado a la izquierda | Centrado | Alineado a la derecha |    
>| :---         |     :---:      |          ---: |    
>| Contenido   | Contenido     | Contenido    |   
>| Contenido     | Contenido       | Contenido     |
>```

Y este será el resultado:

>| Alineado a la izquierda | Centrado | Alineado a la derecha |
>| :---         |     :---:      |          ---: |
>| Contenido   | Contenido     | Contenido    |
>| Contenido     | Contenido       | Contenido     |








                        







