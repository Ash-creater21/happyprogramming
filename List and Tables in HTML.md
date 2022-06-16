# List and Tables in HTML

## list in HTML

1. unordered list 
   
   when list is not numbered like 
   
   * Apple 
   
   * Banana
   
   * Mango 

2. Ordered list 
   
   when list is numbered like
   
   1. Apple 
   
   2. Mango 
   
   3. Banana 

## Example of ordered and unordered list

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List and table in the html </title>
</head>
<body>
    <!-- list in html  -->
    <h1>list in HTML </h1>
    <ul>
        <li> Apple  </li>
        <li> mango  </li>
        <li> banana  </li>
    </ul>
    <ol>
        <li> Apple  </li>
        <li> mango  </li>
        <li> banana  </li>
    </ol>
</body>
</html>
```

Output:

# list in HTML

- Apple

- mango

- banana
1. Apple

2. mango

3. banana

## Type Attribute in ordered list

| Attribute | type of list you get            |
| --------- | ------------------------------- |
| 1         | default                         |
| A         | listing  capital alphabetically |
| a         | listing small alphabetically    |
| I         | Roman counting capital          |
| i         | Roman counting small            |

## type attribute in unordered lists

| Attribute | type of list you get |
| --------- | -------------------- |
| square    | fileed square        |
| dics      | filles circle        |
| circle    | hollow circle        |

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List and table in the html </title>
</head>
<body>
    <!-- list in html  -->
    <h1>list in HTML </h1>
    <ul type = "dics">
        <li> Apple  </li>
        <li> mango  </li>
        <li> banana  </li>
    </ul>
    <ol type="I">
        <li> Apple  </li>
        <li> mango  </li>
        <li> banana  </li>
    </ol>
</body>
</html>
```

nested list 

we may create nested list by placing list inside a list 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List and table in the html </title>
</head>
<body>
    <!-- list in html  -->
    <h1>list in HTML </h1>
    <ul type = "dics">
        <li> Apple  </li>
        <li> mango  </li>
        <li> banana  </li>
    </ul>
    <ol type="I">
        <li> Apple  </li>
        <ol>
            <li> red apple </li>
        <li>
            green apple 
        </li>
        </ol>
        <li> mango  </li>
        <li> banana  </li>
    </ol>
</body>
</html>
```

Output 

# List in HTML

- Apple

- mango

- banana
1. Apple
   
   1. red apple
   
   2. green apple

2. mango

3. banana

# Tables in HTML

let us understand this by example 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table in html </title>
</head>
<body>
    <h3>the content of table </h3>
    <table>
        <thead>
            <th>Employee</th>
            <th>Employee Id </th>
            <th>Employee Role </th>
       </thead>
       <tbody>
         <tr>
            <td> Ashutosh </td>
            <td>387487</td>
            <td>Support engineer</td>
        </tr>
        <tr>
            <td> Deepanshu </td>
            <td>387487</td>
            <td>Web developer </td>
        </tr>
        <tr>
            <td>Kunal </td>
            <td>387487</td>
            <td>Marketing analist </td>
        </tr>
      </tbody>
    </table>
</body>
</html>

    </table>
</body>
</html>
```

### output

### the content of table

| Employee  | Employee Id | Employee Role     |
| --------- | ----------- | ----------------- |
| Ashutosh  | 387487      | Support engineer  |
| Deepanshu | 387487      | Web developer     |
| Kunal     | 387487      | Marketing analist |


