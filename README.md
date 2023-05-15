# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:

Clone the github repository and create Django admin interface.
### Step 2:

Change settings.py file to allow request from all hosts.
### Step 3:

Use CSS for creating attractive colors.
### Step 4:

Write Javascript program for implementing five different operations.
### Step 5:

Vlidate the HTML and CSS code.
### Step 6:

Validate the HTML and CSS code.
### Step 7:

Publish the website in the given URL



## PROGRAM :
```


<!DOCTYPE html>
<html>
    <head>
        <title>Calculator in JavaScript</title>
        <style type="text/css">
        table{
            border: 3px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 2px solid black;
            padding: 20px 40px;
            font-size: 24px;
            font-weight: bold;
            background-color: aqua;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:pink;
            border-radius: 2px;
        }
        </style>
    </head>
    <body bgcolor="violet">
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:red;">Simple Calculator</h1>
            <h2 style="text-align: center;color:red;"> SATHISH R 212222100048</h2>
         
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            
            <tr>
                <td colspan="4">
                    <input type="button" value="clearall" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```

## OUTPUT:

![OUT1](a.png)

![OUT2](b.png)

## Result:
The program for designing a simple calculator using Jvascript is created successfully.

