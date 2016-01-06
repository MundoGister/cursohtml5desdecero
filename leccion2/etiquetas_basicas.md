# 2.4. Etiquetas básicas

Para terminar esta lección vamos a aprender el significado de ocho de las etiquetas que probablemente tendremos que usar con más frecuencia cuando creemos webs:

* ```<h1></h1>```: esta etiqueta se utiliza para representar el encabezado de una página ([+info](http://www.w3.org/TR/2014/REC-html5-20141028/sections.html#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements)).

* ```<p></p>```: representa un párrafo ([+info](http://www.w3.org/TR/2014/REC-html5-20141028/grouping-content.html#the-p-element)).

* ```<br>```: The br element represents a line break. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/grouping-content.html#the-p-element)).

* ```<ul></ul>```: The ul element represents a list of items, where the order of the items is not important — that is, where changing the order would not materially change the meaning of the document. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/grouping-content.html#the-ul-element)).

* ```<li></li>```: The li element represents a list item. If its parent element is an ol, or ul, then the element is an item of the parent element's list, as defined for those elements. Otherwise, the list item has no defined list-related relationship to any other li element. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/grouping-content.html#the-li-element)).

* ```<ol></ol>```: The ol element represents a list of items, where the items have been intentionally ordered, such that changing the order would change the meaning of the document. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/grouping-content.html#the-ol-element)).

* ```<strong></strong>```: The strong element represents strong importance, seriousness, or urgency for its contents. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/text-level-semantics.html#the-strong-element)).

* ```<em></em>```: The em element represents stress emphasis of its contents. ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/text-level-semantics.html#the-em-element)).

* ```<!-- -->```: comentarios ([+ìnfo](http://www.w3.org/TR/2014/REC-html5-20141028/syntax.html#comments)).

El siguiente ejemplo muestra una página web que combina todas ellas:

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Ejemplo con etiquetas básicas</title>
</head>
<body>
    <!-- Este comentario no lo podrá ver el visitante -->
    <h1>Mi primer ejemplo</h1>
    <p>
        Este ejemplo muestra cómo combinar algunas de las etiquetas más básicas de HTML5. <br>
        Recuerda que <strong>es importante entender la diferenciae entre ellas</strong>, por ejemplo tenemos dos etiquetas para crear listas:
    </p>
    <ul>
        <li><em>ul</em> para listas desordenadas</li>
        <li><em>ol</em> para listas ordenadas</li>
    </ul>
</body>
</html>
```

En este código 