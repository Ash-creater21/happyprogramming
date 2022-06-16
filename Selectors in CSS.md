# Selectors in CSS

* CSS selectors are used to find the element whose property will be set 

* Selectors are used to target the HTML elements 

* selector makes it easy for us to easily target multiple HTML elements in the markup 

## Types of Basic CSS selectors

* CSS element Selector 

* CSS Id Selector 

* CSS class Selector 

* CSS grouping Selector 

* universal Selector {select for all element in HTML}
  
       *{
           
       }

### CSS element Selector

when we define a Style for all the element of HTML , this will change the style of the element which we have defined under style tag , **even if it is under another tag**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS selector </title>
    <style>
        p{ color:red; }
    </style>
</head>
<body>
    <h3>Selectors in CSS </h3>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-30-11-32-45-image.png)

## CSS id selector

this selector is used to set the property for for differnt element of HTML here we define the id of the style preceded by `#`  pound or Hash symbol like 

```css
#voilet{
    color:red ; 
}
```

here we have to tell the tag the id in which paricualar element we change the style  

### code for CSS id Selector

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS selector </title>
    <style>
        p{

            color:red; 
        }
        #voilet{
            color:blueviolet ; 
        }
    </style>
</head>
<body>
    <h3>Selectors in CSS </h3>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
    <div>
        <p id ="voilet">
            Lorem ipsum dolor sit amet. 
        </p>
    </div>
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-30-11-44-45-image.png)

## CSS class selector

CSS class selectors are preceded by `.` symbol class selectors are also used to taget differnt element but with more power as id selector 

### code for CSS class selector

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS selector </title>
    <style>
        p{color:rgb(125, 43, 192); }
        #voilet{ color:blueviolet ; }
        .bgcolor{background-color:aquamarine;}
        .textcolor{color: darkblue;}
    </style>
</head>
<body class = "bgcolor">
    <h3>Selectors in CSS </h3>
    <p class = "textcolor">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis, itaque labore?</p>
    <div>
        <p id ="voilet">
            Lorem ipsum dolor sit amet. 
        </p>
    </div>
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-30-12-01-07-image.png)

GroupSelector 

group selector allow us to target multiple element of HTML at the same time 

code for group selcector 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>class id selector </title>
    <style>
        footer , span {
        background-color: black;
        color:aliceblue ; 
        }
    </style>
</head>
<body>
    <h3>this is class id selector </h3>
    <span> this is span </span>
    <footer>
        this is footer 
    </footer>
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-30-12-08-43-image.png)
