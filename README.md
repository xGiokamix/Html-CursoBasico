# HTML
Hyper Text Markup Language

### Estructura básica de html

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
~~~
HTML se divide en dos etiquetas importantes  
`<head>` LLeva datos importantes de la página web pero no son mostrados en el navegador  
`<body>` LLeva todo lo que se muestra en la página web



### Estructura etiquetas html

En html las etiquetas tienen una de apertura y otra de cierre:  
`<etiqueta>` `</etiqueta>`

Las etiquetas tienen atributos que son datos adicionales que ponemos a una etiqueta:  
`<etiqueta atributo=" ">` `</etiqueta>`

~~~
<familia>
    <padre nombre="Juan" edad="40" >  
        
        <hijo nombre="Oscar"edad="18" >
        </hijo>
        
        <hijo2 nombre="Romeo" edad="15">
        </hijo2>       

    </padre>
</familia>
~~~

### Comentarios en HTML

Para hacer comentarios se hace uso de los de:  
+ Para abrir `<!--`
+ Para cerrar `-->`
~~~
<!--
Todo lo que se encuentra aquí, será ignorado por el navegador
-->
~~~