# colors in CSS

There are so many colors in CSS which is beyond our imagination it is fun to play with colors 

color pickers in VS code 

Color piker in Vscode helps us to find the color that we want for our wesite it makes our wesite to look asethic and natural as we can able to select color which are beyond the color palate 

## Methords to pickup the colors

1. from color palate 

2. from color picker or rgb 

3. hex colors 
   
   

from color palate 

in color palate we choose the color which are defined in the CSS .

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colors in CSS </title>
    <style>
        #firstpara{
            color:red;  /*color by name  */

        }
        
    </style>
</head>
<body>
    <h2>this is my first box </h2>
    <p id = "firstpara">this is paragraph from first box </p>
    
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-11-43-03-image.png)

from rgb

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colors in CSS </title>
    <style>
        #firstpara{
            color:red;  /*color by name  */

        }
        #secondpara{
            /* second methord */
            color:rgb(209, 5, 216) ; 
        }
      
    </style>
</head>
<body>
    <h2>this is my first box </h2>
    <p id = "firstpara">this is paragraph from first box </p>

    <h2>this is my second box </h2>
    <p id = "secondpara">this is paragraph from second box </p>
 
    
</body>
</html>
```



![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-11-44-43-image.png)

Hex color 

hex colors are defined in hexadecimal 

they start with `#` symbol like 

`#000` ===> Black 

`#f88f` ==> pink 

when you hover this you will get color picker 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colors in CSS </title>
    <style>
        #firstpara{
            color:red;  /*color by name  */

        }
        #secondpara{
            /* second methord */
            color:rgb(209, 5, 216) ; 
        }
        #thirdpara{
            color: rgb(173, 231, 14);
        }
    </style>
</head>
<body>
    <h2>this is my first box </h2>
    <p id = "firstpara">this is paragraph from first box </p>

    <h2>this is my second box </h2>
    <p id = "secondpara">this is paragraph from second box </p>
    
    <h2>this is my third box </h2>
     <p id = "thirdpara">this is paragraph from third box </p>
    
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-31-11-53-10-image.png)


