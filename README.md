# Ex.08 Design of a Standard Calculator
## Date:12/11/23

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title> calculator using javascript</title>
<link rel="index" href=calc.css"
</head>
<body>

<div class ="container">
  <div class="calculator">
    <form>
      <div class ="display">
        <input type="text" name="display">
      </div>
	<div>
	<input type="button" value="AC" onclick="display.value = '' ">
	<input type="button" value="DE" onclick="display.value = display.value.tostring().slice(0,-1)">
	<input type="button" value="." onclick="display.value += '.' ">
	<input type="button" value="/" onclick="display.value += '/' ">
	</div>
        <div>
	<input type="button" value="7" onclick="display.value += '7' ">
	<input type ="button" value="8" onclick="display.value +='8' ">
	<input type="button" value="9" onclick="display.value += '9' ">
	<input type="button" value="*" onclick="display.value += '*' ">
	</div>
	<div>
	<input type ="button" value="4" onclick="display.value += '4' ">
	<input type="button" value="5" onclick="display.value += '5' ">
	<input type="button" value="6" onclick="display.value += '6' ">
	<input type="button" value="-" onclick="display.value += '-' ">
	</div>
	<div>
	<input type="button" value="1" onclick="display.value += '1' ">
	<input type="button" value="2" onclick="display.value += '2' ">
	<input type="button" value="3" onclick="display.value += '3' ">
	<input type ="button" value="+" onclick="display.value += '+' ">
	</div>
	<div>
	<input type="button" value="00" onclick="display.value += '00' ">
	<input type="button" value="0" onclick="display.value += '0' ">
	<input type="button" value="=" onclick="display.value = eval(display.value)" class="equal">
	</div>
    </form>
  </div>
 </div>
```


## OUTPUT:
![Screenshot 2023-11-14 161523](https://github.com/divakar618/Calc/assets/121932143/7f113731-a4cf-44f6-96bf-5d8d764f4f85)



## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
