# Ex03 Time Table
## Date:29/09/23
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## CODE
```
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE -Jeevanesh (23013802)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        th, td {
            border: 1px solid #000000;
            text-align: center;
            padding: 8px;
        }
    </style>
</head>
<body>
<style>
    .center-text {
      text-align: center;
    }
  </style>
</head>
<body>
  <img src="logo.png"width="90%" height="70%">
  <div class="center-text">
    <p>SLOT TIME TABLE -jeevanesh (23013802)</p>
  </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
        </tr>
	<tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">FREESLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
	    <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
        </tr>

	<tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH BREAK</th>
        </tr>
	<tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
	    <th colspan="1" bgcolor="Cyan">SS</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
	    <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
      </table>






      <table>
        <tr>
            <th colspan="1">S.NO</th>
            <th colspan="1">Subject code</th>
	    <th colspan="1">Subject Name</th>
        </tr>
	<tr>
            <th colspan="1">1</th>
            <th colspan="1">19AI414</th>
	    <th colspan="1">Fundamentals of Web application Development</th>
        </tr>
	<tr>
            <th colspan="1">2</th>
            <th colspan="1">19EN612</th>
	    <th colspan="1">German Basic(GER)</th>
        </tr>
	<tr>
            <th colspan="1">3</th>
            <th colspan="1">19PH206</th>
	    <th colspan="1">Physics for Information Technology</th>
        </tr>
	<tr>
            <th colspan="1">4</th>
            <th colspan="1">19CY205</th>
	    <th colspan="1">Principles of Chemistry in Engineering</th>
        </tr>
	<tr>
            <th colspan="1">5</th>
            <th colspan="1">19MA201</th>
	    <th colspan="1">Calculas and Matrix Algebra(MAT)</th>
        </tr>
	<tr>
            <th colspan="1">6</th>
            <th colspan="1">19EY701</th>
	    <th colspan="1">SOFT skills</th>
        </tr>
      </table>
    </body>
  </html>
```
## OUTPUT:
![Screenshot (12)](https://github.com/plotswag/slot/assets/145822344/0ef0b8fe-58dc-47ee-8760-85ecf6b6d438)


## HTML VALIDATOR
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

