# Forms in HTML

**An HTML form is used to collect user input. The user input is most often sent to a server for processing.**

the server program that takes the input is written in backend language like php , java , django Nodejs etc . 

## form tag in HTML

form tag is used to make forms in html form tag takes a argument that is the file of backend here we are not going to write the backend file . we can able to make forms without backend but when you submit you will get error like `Cannot GET /backend.php`

```html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Document</title>
</head>
<body>
    <form action="backend.php"></form>
</body>
</html>
```

here you can see that form tag takes the argument  `action = ""` that take in the backend file 



## Input tag  In HTML

Input tag is used to take input from user that goes into the backend server 

### Type of input tag

1. Text

2. Email

3. Number 

4. Date 

5. Radio 

6. Button

| Type                    | Description                                                      |
| ----------------------- | ---------------------------------------------------------------- |
| <input type="text">     | Displays a single-line text input field                          |
| <input type="radio">    | Displays a radio button (for selecting one of many choices)      |
| <input type="checkbox"> | Displays a checkbox (for selecting zero or more of many choices) |
| <input type="submit">   | Displays a submit button (for submitting the form)               |
| <input type="button">   | Displays a clickable button                                      |

### Example of input of text

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="backend.php">
        <div>
            first Name : <input type="text" >
        </div>
        <br>
        <div>
            last name : <input type="text">
        </div>
        <br>
        
    </form>
</body>
</html>
```

Output:

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-15-08-19-image.png)

### Name Attribute in input tag

name attribute is used to give input to the variable in the backend 

Value attribute is used to show the string which will be shown output window or browser 

### Adding up the code

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form action="backend.php">
        <div>first Name : <input type="text"></div>
        <br>
        <div> last name : <input type="text">  </div>
        <br>
        <div> Email : <input type="email" name="myemail"> </div>
        <br>
        <div> date : <input type="date" name="mydate">  </div>
        <br>
        <div> phone no : <input type="number" name="mynumber">  </div>
        <br>
        <div> Do you Agree with this agreement ? <input type="checkbox" name="Agree">  </div>
        <br>
        <div> Gender : Male <input type="radio" name="mygender">
            female <input type="radio" name="mygender">
            Other <input type="radio" name="mygender">
        </div>
        <br>
        <div>
<!-- value attribute is used show 123 in button --> 
            <input type="submit" value="123">
        </div>
    </form>
</body>

</html>
```



Output: 

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-15-39-20-image.png)



#### Adding reset button using input tag

you just need to append this code after submit 

```html
 <input type="reset" value="Reset">
```

it would look like 

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-15-44-57-image.png)

passwords in html 

you can take input of password using just by typing type = "password" 

```html
<input type = "password" name = "Password"> 
```

## Creating option in HTML forms

for creating option we use `<select>` tag and `<option>` tag inprder to create option 

```html
 Select the Car <select name="Car" > 
            <option value="Indica">Indica </option>
            <option value="Suzuki">Swift </option>
            <option value="Alto">Alto</option selected>
        </select>
```

you would get a drop down menu like this 

<img src="file:///C:/Users/HP/Desktop/dropdown.png" title="" alt="" width="222">

### Creating the text area in HTML

![](C:\Users\HP\AppData\Roaming\marktext\images\2022-01-29-16-20-13-image.png)

```html
 <div>
  tell us your suggestion : 
   <br>
   <textarea  name = "textarea" cols="30" rows="10">

  </textarea>
  </div>
```





Labels in HTML 

labels are bit important for careting form this allow input and the written promt connected and gives more natural user exprience 

when we click the word written it would autamticaly light up the input promt 

**we gain this by connecting to th ID** 



## summing This code Up !!!!!

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>forms in html </title>
</head>

<body>
    <h1>this is forms in HTML </h1>
    <form action="backend.php">
        <label for="name">name : </label>
        <div>
            <input type="text" name="myName" id="name">
        </div>
        <br>
        <div>
            <label for="Role">Your Role : </label>
            <input type="text" name="myRole" id="Role">
        </div>
        <br>
        <div>
            <label for="email">Your Email : </label>
            <input type="email" name="myemail" id="email">
        </div>
        <br>
        <div>
            <label for="date">Enter date : </label>
            <input type="date" name="Mydate" id="date">
        </div>
        <br>
        <div>
            <label for="phnumber">phone number : </label>
            <input type="number" name="Mynumber" id="phnumber">
        </div>
        <br>
        <br>
        <div>
            <label for="iseligible">Are you 18 </label>
            <input type="checkbox" name="mycheckBox" checked id="iseligible">
            <!-- for making cheack box cheacked by default  -->
        </div>
        <br>
        <label for="AnnualSalary">Annual Salary </label>
        <input type="number" name="Mysalary" id="AnnualSalary">
        <div>
            <br>
            <div>
                tell us your suggestions:
                <br>
                <textarea name="suggestion" cols="30" rows="10"></textarea>
            </div>
            <br>
            <div>
                Gender:
                <label for="male">Male</label>
                <input type="radio" name="ismorf" id="male">
                <label for="female">Female</label>
                <input type="radio" name="ismorf" id="female">
                <label for="other">other</label>
                <input type="radio" name="ismorf" id="other">
            </div>
            <br>
            <div>
                <label for="Car">Select the car you want </label>
                <select name="MyCar" id="Car">
                    <option value="Indica">Indica </option>
                    <option value="Suzuki">Swift </option>
                    <option value="Alto">Alto</option selected>

                </select>
            </div>
            <br>
            <input type="submit" value="submit Now">
            <button type="reset">Reset</button>
        </div>

    </form>
</body>

</html>



<!-- Tip of the day 

move block ! 
selct the block 
alt + arrow key  -->

```

<img title="" src="file:///C:/Users/HP/AppData/Roaming/marktext/images/2022-01-29-16-27-31-image.png" alt="" width="204">














