# Box Model in CSS

The **CSS box model** is a container that contains multiple
 properties including borders, margin, padding, and the content itself. 
It is used to create the design and layout of web pages. It can be used 
as a toolkit for customizing the layout of different elements. The web 
browser renders every element as a rectangular box according to the CSS 
box model

<img src="file:///C:/Users/HP/Documents/CSS-Box-Model.webp" title="" alt="" width="475">

padding is near to element that is 794 * 160 It gives space from all four sides to the element . 

margin gives  space to border or aligns the the border in which padding and element placed in.

## setting padding from all four sides

As padding makes space around element we can do for all four sides 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Model </title>
    <style>
        .container{
            background-color:#c99efd;
            border: #7c09b0 solid 4px ; 
             padding: 100px;  
            /* padding-top: 34px ;
            padding-left: 50px;
            margin: 34px; */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>this is my  first heading </h1>
        <p id="first">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sint minus eum necessitatibus asperiores, sed tenetur! Error cum ad hic perspiciatis fugiat eum vero ab at quam commodi voluptatum quo, quaerat quos voluptate?
        </p>
        </div>

</body>
</html>
```

<img title="" src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-19-04-10-image.png" alt="" width="625">

## code for margin

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Model </title>
    <style>
        .container{
            background-color:#c99efd;
            border: #7c09b0 solid 4px ; 
             padding: 30px;  
             margin: 34px;
             /* 
             padding-top: 34px ;
             padding-left: 50px;
             padding-right:50px ; 
             padding-bottom : 30px ; 
              */
            }
    </style>
</head>
<body>
    <div class="container">
        <h1>this is my  first heading </h1>
        <p id="first">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sint minus eum necessitatibus asperiores, sed tenetur! Error cum ad hic perspiciatis fugiat eum vero ab at quam commodi voluptatum quo, quaerat quos voluptate?
        </p>
        </div>

        <div class="container">
        <h1>this is my second  heading </h1>
        <p id="second">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sint minus eum necessitatibus asperiores, sed tenetur! Error cum ad hic perspiciatis fugiat eum vero ab at quam commodi voluptatum quo, quaerat quos voluptate?
        </p>
    </div>

    <div class="container">
        <h1>this is my third heading </h1>
        <p id="Third">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sint minus eum necessitatibus asperiores, sed tenetur! Error cum ad hic perspiciatis fugiat eum vero ab at quam commodi voluptatum quo, quaerat quos voluptate?
        </p>
    </div>

</body>
</html>
```

### Output

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-19-16-11-image.png)

this  has made our element 30px far from the border 

### we may also give padding from right,left,top and bottom

`padding-right` 

`padding-left` 

`padding-top` 

`paddin-bottom` 

```css
 /* we can set padding / margin like this also */
             padding-top: 34px ;
             padding-left: 50px;
             padding-right:50px ; 
             padding-bottom : 30px ; 
```

Setting padding as TRBL{Top,Right,Bottom,Left} 

`padding:<Top Right Bottom left> ` 

```css
padding: 23px 56px 6px 78px ; 
```

note : we can also use this as `padding :23px 56px` 

basically we gave top and bottom 23px and right left 56px padding  

when we increase padding in x axis it changes the height and when we change in y-axis it x changes the width that should not be done as we have setted the hight and width 

this is also same for margin will also change the height and width setted 

## Box sizing

it is a property which prevent from variating the length and breadth 

| Property   | Description                                                                                                    |
|:---------- | -------------------------------------------------------------------------------------------------------------- |
| Box-Sizing | Defines how the width and height of an element are calculated: should they include padding and borders, or not |
