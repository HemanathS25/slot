# Ex03 Time Table
## Date:15-11-2024

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

## PROGRAM
```
<html>
<img src="logo.png" alt="" height="200" width="1000">
<body>
<table border="1">
    <caption>TIME TABLE-HEMANATH S (24009648)</caption>
        <tr bgcolor="cyan">
            <th>Day/Time</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr bgcolor="cyan">
                <td>Monday</td>
            <td bgcolor="yellow"> FREE SLOT</td>
            <td>English</td>
            <td bgcolor="yellow"> FREE SLOT</td>
            <td bgcolor="yellow"> FREE SLOT</td>
        </tr>
        <tr bgcolor="cyan">
            <td>Tuesday</td>
            <td>Web</td>
            <td bgcolor="yellow"> FREE SLOT</td>
            <td> Python</td>
            <td bgcolor="yellow"> FREE SLOT</td>
        </tr>
        <tr bgcolor="cyan">
            <td>Wednesday</td>
            <td>Python</td>
            <td>Dig ele</td>
            <td bgcolor="yellow"> FREE SLOT</td>
            <td bgcolor="yellow"> FREE SLOT</td>
        </tr>
        <tr bgcolor="cyan">
            <td>Thursday</td>
            <td>English</td>
            <td>Python</td>
            <td>Physics</td>
            <<td bgcolor="yellow"> FREE SLOT</td>
        </tr>
        <tr bgcolor="cyan">
            <td>Friday</td>
            <td bgcolor="yellow"> FREE SLOT</td>
            <td>Physics</td>
            <td>Web</td>
                <td bgcolor="yellow"> FREE SLOT</td>
    
        </tr>
        <tr bgcolor="cyan">
            <td>Saturday</td>
            <td>Dig ele</td>
            <td>Python</td>
            <td>Web</td>
            <td bgcolor="yellow"> FREE SLOT</td>
        </tr>
    </table>
    <br>
    <table border="1">
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamental Web Application Development(WEB)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI301C</td>
            <td>Python and Linear Algrbra(PYTHON)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE404</td>
            <td>Digital electronics(DIG ELE)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EN101</td>
            <td>Communicative english(ENGLISH)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>SH3214</td>
             <td>Physics for quantum computing(PHYSICS)</td>
        </tr>
    </table>
    </body>
    </html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-15 143108.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
