# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Create a new django project and app

### Step 2:
create a static folder and sub folder html

### Step 3:
write the code in the html file

### Step 4:
Write internal css code making it attractive

### Step 5:
Start the Django Server

## PROGRAM :
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SEC Demo on Calculator</title>
        <style>
        table{
            border: 10px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 5px solid grey;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color: lightskyblue;
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value='0'">
            <h1 style="text-align: center;color:black;">Standard Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"></td>
                <td><input type="button" value="2" onclick="result.value+='2'"></td>
                <td><input type="button" value="3" onclick="result.value+='3'"></td>
                <td><input type="button" value="+" onclick="result.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"></td>
                <td><input type="button" value="5" onclick="result.value+='5'"></td>
                <td><input type="button" value="6" onclick="result.value+='6'"></td>
                <td><input type="button" value="-" onclick="result.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"></td>
                <td><input type="button" value="8" onclick="result.value+='8'"></td>
                <td><input type="button" value="9" onclick="result.value+='9'"></td>
                <td><input type="button" value="*" onclick="result.value+='*'"></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"></td>
                <td><input type="button" value="0" onclick="result.value+='0'"></td>
                <td><input type="button" value="." onclick="result.value+='.'"></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="Clear" id="clear" onclick="result.value='0'">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```
## OUTPUT:
### Client Side
![client_side-2](https://github.com/Sanjay-2610/standard-calculator/assets/91368803/fc7f0d9c-e7e4-4012-afd3-01c904caa169)

### Server Side
![server_side-2](https://github.com/Sanjay-2610/standard-calculator/assets/91368803/73051acb-d1de-4919-89ee-bad6f4123d33)

## Result:
Thus the program for the simple calculator executed successfully.
