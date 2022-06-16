# Image and Anchor Tag

## Anchor tag in html

if we want to add links in the website we use anchor tag 

```html
 <a href="https://google.com">go to google </a>
```

in href we place link and between tags we write the word which would be seen in the website 

## example on tags html (External link)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>links and images</title>
</head>
<body>
    <!-- links in html  -->
    <a href="https://google.com">go to google </a>
    <a href="https://facbook.com">facebook</a>
    <a href="https:youtube.com">youtube</a>
    <a href="https://twitter.com">twitter</a>

</body>
</html>
```

output

[go to google](https://google.com)  
[facebook](https://facbook.com)  
[youtube](https:youtube.com)  
[twitter](https://twitter.com)

## Tags and attributes in html

<img title="" src="file:///C:/Users/HP/Desktop/index.png" alt="" width="545">

💡 Tip of the Day 

1. in VsCode we can use multicurser 

way select the tag using mouse and press ctrl + d to make multiple curser 

2. press alt then choose wherever you want the muliple cursor 

## opening  link in different  tab using target Attribute

for doing this we need another attribute of anchor tab that is  **target**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>links and images</title>
</head>
<body>
    <!-- links in html  -->
    <a href="https://google.com" target = "_blank">go to google </a>
    <br>
    <a href="https://facbook.com " target = "_blank">facebook</a>
    <br>
    <a href="https:youtube.com"target = "_blank"> youtube</a>
    <br>
    <a href="https://twitter.com " target = "_blank">twitter</a>
    <br>

</body>
</html>
```

## opening internal link

****internal link  it means internal storage files ****

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=a, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<!--you can also use target to open in another tab -->
    <a href="/first.html" target = "_blank" >code for first.html </a>
</body>
</html>
```

## Adding Images to the Website : img tage



img tag is used to insert the image in the web site

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=a, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Links and Images in html </h1>  
    <img src="https://unsplash.com/assets/api/api-photo-grid-6a8a9f9bd814cc5fd67b18bd91eace0f5e1b542a848d47ed074364bbd7597418.jpg" alt="this image is not avaiable">
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-28-14-34-53-image.png)

* you may set the height and width with the height and width attribute but it is not a good practice , we should use the css for this . 
