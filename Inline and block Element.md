# Inline and block Element

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Inline and block elements</title>
</head>
<body>

    <p>this is a paragraph </p>
    <p>this is also a  paragraph </p>

</body>
</html>
```

look at this code 

I am expecting 

this is a paragraph this is also a paragraph

but getting 

this is a paragraph

this is also a paragraph

here I want the two paragraph together

this is because `<p>` is a block element 

**<mark>Block Element :</mark>** are the elements which occupies whole line or width 

if we want to improve this code we can use the span tag which is inline element 

**<mark>Inline element :</mark>** it is the element which occupies only the size of the String 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Inline and block elements</title>
</head>
<body>
    <p>this is a paragraph </p>
    <p>this is also a paragraph </p>
    <span>this is also a Span </span> <span>this is also a span </span>


</body>
</html>
```

this is also a Span  this is also a span

Examples of block element :

`<p>, <div> , <h1>`

Examples of Inline element 

`<a> , <span>, <input>, <Strong>, <em> `

`
