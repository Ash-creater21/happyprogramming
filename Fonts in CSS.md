# Fonts in CSS

there are many fonts we can change using css this is kinda fun to using them all this is some extara design to our website 

## websafe fonts

websafe are fonts are the fonts which are built in almost all system like mac , linux and Windows 

these are : 

- Palatino

- Garamond

- Bookman

- Avant Garde

- Georgia

- Comic Sans MS

- Trebuchet MS

- Arial Black

- Impact

## how to change the fonts in css ?

```css
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Fonts in CSS </title>
    <style>
        p{
            color:blueviolet ; 
           font-family:'Courier New', Courier, monospace;
        }
    </style>
</head>
<body>
<p>this is fonts in css </p>
</body>
</html>
```

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-30-16-30-23-image.png)

## How to import extra fonts from External Source

1. go to google and type google fonts 

2. then select a font 

3. Then copy the file link  from the web 

4. then copy the font-family link 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fonts in CSS </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Comforter&display=swap" rel="stylesheet"> 
    <style>
        p{
            text-align: center;
            font-family: 'Comforter', cursive;
            background-color: deeppink;
            border-radius: 1000px;
            font-size: 23px;
            line-height: 23em;
            font-weight: bolder;
        }
        span{
            font-weight: 800;
            font-style: italic;
        }
    </style>
</head>
<body>
    <h4>CSS Fonts 
    </h4>
    <p> Lets play with fonts , it is very exiting </p>
    <span>fonts make life easier </span>
</body>
</html>
```

# Output

<img src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-30-16-51-07-image.png" title="" alt="" data-align="left">

# some properties of CSS

#### Text-allign

Describes how inline contents of a block are horizontally aligned if the contents do not completely fill the line box.

Syntax: start | end | left | right | center | justify | match-parent

#### font-family

Specifies a prioritized list of font family names or generic family names. A user agent iterates through the list of family names until it matches an available font that contains a glyph for the character to be rendered.

font-family<family-name> ; 

#### background-color

Sets the background color of an element.

background-color: <color> ; 

#### border-radius

Defines the radii of the outer border edge.

#### font-size

Indicates the desired height of glyphs from the font. For scalable fonts, the font-size is a scale factor applied to the EM unit of the font. (Note that certain glyphs may bleed outside their EM box.) For non-scalable fonts, the font-size is converted into absolute units and matched against the declared font-size of the font, using the same absolute coordinate space for both of the matched values.

Syntax: <absolute-size> | <relative-size> | <length-percentage>

#### line-height

Determines the block-progression dimension of the text content area of an inline box.

Syntax: normal | <number> | <length> | <percentage>

` line-height: 23em;`

#### font-weight

Specifies weight of glyphs in the font, their degree of blackness or stroke thickness.

Syntax: <font-weight-absolute>{1,2}

#### font-style

Allows italic or oblique faces to be selected. Italic forms are generally cursive in nature while oblique faces are typically sloped versions of the regular face.

Syntax: normal | italic | oblique <angle>{0,2}
