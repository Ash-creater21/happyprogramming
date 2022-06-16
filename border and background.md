# Border and Background in CSS

## Height and Width  property in CSS

when we take any paragraph or heading they take whole line as space by default we can change it's height as well as width by property height and width 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background and border in CSS </title>
    <style>
        #head1{
            height: 100px ;
            width: 300px ; 
            background-color: blueviolet;
        }
    </style>
</head>
<body>
    <h3 id = "head1">this is head in box 1 </h3>
<br>
    <h3>this is head in box 2 </h3>
</body>
</html>
```

#### output:

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-14-33-30-image.png)

## Text Allign

It allign the text with in set height and width 

## Borders in CSS

borders have some property they are

1. border-color 

2. border-style 

3. border-thickness 
   
   

we can merrge them all in a single boder property 

synatx:

`border: {thickness}[int]px {style}(dashed,solid,dotted...) {color}(blue,green,black,yellow)  `

example:

```css
border : 4px solid green ;
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background and border in CSS </title>
    <style>
        #head1{
            height: 100px ;
            width: 300px ; 
            background-color: blueviolet;
            text-align: center ;
            border:5px solid blue ;  
        }
    </style>
</head>
<body>
    <h3 id = "head1">this is head in box 1 </h3>
<br>
    <h3>this is head in box 2 </h3>
</body>
</html>
```



#### Output

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-14-37-34-image.png)



#### you can also do this by

```css
background-color: purple-blue ; 
border-color: darkblue;
border-style: solid;
border-bottom-left-radius: 3px;
```

### how to make rounded corners of the box ?

we can do this with property **border-radius** this makes corners rounded how much we want 

### code smash for rounded corner

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background and border in CSS </title>
    <style>
        #head1{
            height: 100px ;
            width: 300px ; 
            background-color: blueviolet;
            text-align: center ;
            border:5px solid blue ;  
            border-radius: 23px;
        }
    </style>
</head>
<body>
    <h3 id = "head1">this is head in box 1 </h3>
<br>
    <h3>this is head in box 2 </h3>
</body>
</html>
```



![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-14-46-23-image.png)

## More border properties

border-top {to color the top of the box} 

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-14-54-08-image.png" title="" alt="" width="414">

border-bottom {to color the bottom of the box}

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-14-54-46-image.png" title="" alt="" width="420">

border-left {to color the left of the box}

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-14-58-42-image.png" title="" alt="" width="428">

border-right {to color the right of the box}

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-14-56-29-image.png" title="" alt="" width="432">

### playing with borders<mark> <u>leaf style border</u></mark>



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background and border in CSS </title>
    <style>
        #leaf{
            height: 200px ;
            width: 200px ; 
            background-color: blueviolet;
            text-align: center ;
            border-left: 20px yellowgreen solid ; 
            border-top-right-radius: 40px ;
            border-bottom-left-radius: 40px;
        }
    </style>
</head>
<body>
    <h3 id = "leaf">this is head in box 1 </h3>
<br>
    <h3>this is head in box 2 </h3>
</body>
</html>
```



<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-15-04-39-image.png" title="" alt="" width="259">



### right-leaf design

<img title="" src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-31-15-25-42-image.png" alt="" width="282" data-align="inline">

### code for right leaf design

```css
#leafy{
            height : 200px ; 
            width : 200px ; 
            text-align:center; 
            background-color:rgb(255, 0, 149); 
            border-top-left-radius: 50px ; 
            border-bottom-right-radius: 50px;
            border:4px solid blueviolet ; 
            
        }
```

## Backgound Image in CSS

background image looks awesome when it puts on your website gives more natural look to the website 

we can set the Backgound Image using **background-image** property but it has several problem that can be resolved by using some more properties 

1. Reapeation of image 

2. allignment of image 

```css
 #third{
          height:200px ; 
          width : 200px ; 
          background-image: url("chrome://branding/content/about-logo.png");
          background-repeat: no-repeat; /* repeat x and repeat y will make repeat in x and y axis */
          border:12px solid  green ; 
          border-radius:150px ; 
          /* background-position: 12px 12px ; x axis and y axis  */
          background-position: center center ;
} 
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-15-38-11-image.png)


