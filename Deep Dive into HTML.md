# Deep Dive into HTML

## Ammet Avrivation

Emmet is a set of plug-ins for text editors that allow for high-speed coding and editing in HTML

!  gives the snippet for HTML 

Meta tag this tag is used for seo that is search engine optimization that helps the google or Bings to know our websites 

here in this meta tag is telling the browser that we will use utf-8 

```html
<meta charset="UTF-8">
```



<meta charset="UTF-8">

<meta charset="UTF-8">

<meta charset="UTF-8">      

<meta charset="UTF-8">

**The meta element represents various kinds of metadata that cannot be expressed using the title, base, link, style, and script elements.**

<meta name="viewport" content="width=device-width, initial-scale=1.0">

```html
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

here in this line metatag is adjusting the display screen in which it is being viewed 

## Adding the descripton in the meta tag

we can add decription of the website when it show on a browser 

```html
 <meta name = "description" content = "this is description ">
```

## Adding the keywords in the meta tag

these are the words which we tell a search engine when somebody search something like 

shopping , grocery , smartphone etc 

<meta name = "keyword" content = "html , html tutorials , web dev ">

```html
  <meta name = "keyword" content = "html , html tutorials , web dev "> 
```

## Robots in the meta tag

Robots are used to tell a search engine that they want to be indexed or followed by the search engine 



### how to include extenal CSS to your file

```html
<!-- how to include extenally css -->
<link rel="stylesheet" href="harry.css">
```



### how to include extenal JavaScript to your file

```html
 <!-- how to include javascript file  -->
 <script> src = "Harrry.js"</script>
```

# tags in HTML

Heading tag : it is used for writing heading in html 

opening tag closing tag 

```html
<h1></h1>
```



headings are 1 to 6 and should be used only once in the program 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name = "description" content = "this is description ">
    <meta name = "keyword" content = "html , html tutorials , web dev "> 
    <meta name = "robots" content = "INDEX , FOLLOW ">
    <title>My First Website </title>
  
</head>
<body>
  <h1>This is html </h1>
  <h2>This is html </h2>
  <h3>This is html </h3>
  <h4>This is html </h4>
  <h5>This is html </h5>
  <h6>this is html </h6>
</body>
</html>
```

Output

# This is html

## This is html

### This is html

#### This is html

##### This is html



### Paragraph in html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name = "description" content = "this is description ">
    <meta name = "keyword" content = "html , html tutorials , web dev "> 
    <meta name = "robots" content = "INDEX , FOLLOW ">
    <title>My First Website </title>
  
</head>
<body>
    <h1>this is  heading </h1>
 <p>this is my first paragraph </p>

</body>
</html>
```

Output

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-27-16-33-55-image.png" title="" alt="" data-align="left">

#### 💡 Tip of the Day

💡Tip 1 

if you type lorem<word>

Example : lorem12 

it will generate 12 words for you 

Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit alias commodi saepe!

this is worth when we want to display some random text 

💡Tip 2 

inserting multiple paragraph 

p * 4 

💡Tip 3 

next line without using mouse 

`ctrl + Enter`



<div>
<p></p>
<p></p>
<p></p>
<p></p>
</div>

```html
<p></p>
<p></p>
<p></p>
<p></p>
```

for hovering into one paragraph to another use tab 



#### Strong tag in html

```html
<!DOCTYPE html>
<html lang="en">
<head>this is head </head>
<body>
  <h1>I am heading </h1>
  <p>Lorem ipsum dolor, sit amet <strong> I am strong </strong> consectetur adipisicing elit. Provident, sit.</p>
</body>
</html>
```

Output

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-27-16-54-50-image.png)



* you can use `<b>` instead of `<strong>` but it is not recommended as they are defined in HTML3 and Current version is HTML5 

* you can also use `<i>` instead of `<em>` but it is not recommended as they are defined in HTML3 and Current version is HTML5

Emphasis tag in html 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My First Website </title>
</head>
<body>
  <h1>I am heading </h1>
  <p>Lorem ipsum dolor, sit amet <em>this is emphasised </em> consectetur adipisicing elit. Provident, sit.</p>
</body>
</html>
```

Output

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-27-16-58-36-image.png)

### Break Tag in Html

suppose you want a new line you won't be able to do it without this tag , B'coz Html igores extra spaces , it is empty tag as it does'nt require any closing tag 

`<br>`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My First Website </title>
  
</head>
<body>
  <h1>I am heading </h1>
  <p>Lorem ipsum dolor <br> sit amet consectetur,<br> adipisicing elit. <br> Illum explicabo unde rem.</p>
</body>
</html>
```

Output:

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-27-17-07-09-image.png)

### Horizontal rule in html

it is also a empty tag it doen'nt need any closing tag it's purpose is to draw a horizontal line on the page 

it is written like that 

`<hr>`

---




