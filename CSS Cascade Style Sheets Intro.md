# CSS Cascade Style Sheets Intro

What is CSS Used for ? 

1. CSS gives the Style to raw HTML 

2. CSS gives style to Our Websites 

3. CSS makes the Website Responsive for Phones and Desktop

<img src="file:///C:/Users/HP/Documents/responsive-web-design-caktus.gif" title="" alt="" width="584">

4. It makes our website beatiful and morden looking 
   
   ## CSS Syntax
   
   ![](C:\Users\HP\Documents\index12.png)
   
   **Selector** define where is the change to be madeon a particular element .  here the change to made is in paragraph
   
   **Property** defines a value to be given  for example change color to blue 
   
   dot(.) means class 
   
   pound(#) means Id 

```css
header , p.into {
    background-color : red ; 
    border-radius : 3px ; 
}
```

## <mark>**How to Add CSS to the Markup(HTML Code)**</mark>

* Inline CSS : CSS is added to the element directly using Style Attribute 

* Internal CSS : CSS is kept inside the head tags in `<Style>` Tag 

* Extrenal CSS : CSS is kept Separately inside a `.css` style sheet 

#### Smash up Code for inline code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Introduction</title>
</head>
<body>
    <h3>this is CSS </h3>
    <!-- inline css  -->
    <!-- it is not recomended  -->
    <!-- priority is first given to inline  -->
    <p style="background: greenyellow; color:darkcyan">this will let me know about css </p> 

</body>
</html>
```

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-29-23-20-43-image.png" title="" alt="" width="417">

#### Smash up the code for Internal CSS

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
       <style>
        p {
            color : purple; 
            background-color: darkcyan;
        }
    </style>
</head>
<body>
    <h3>this is CSS </h3>
    <!-- internal css  -->
    <!--not recommended but usable -->
    <!-- Seprates the Style from the markup  -->
    <p>this will let me know about css </p> 

</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-23-34-42-image.png)

#### Smash up the code for Extrenal CSS

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <h3>this is CSS </h3>
    <p>this will let me know about css </p> 

</body>
</html>
```

```css
/* style.css */
p{
    color:blue ;
    background-color: coral;
}
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-23-41-18-image.png)

the priority of internal and external CSS is Same . 

the style which come later takes precidence as it overwrites the privious property 

if we want it take priority then we can write !important 

```html
 <link rel="stylesheet" href="style.css">
    <style>
        p{
            color:crimson;
            background-color: blue !important; 
        }
    </style>
```

now the style of paragraph would  definately in which `!important` is present 
