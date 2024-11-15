# Ex03 Time Table
## Date:15.11.24

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
<img src="logo.png" height="200" width="1000">
<table border="2">
    
    <h1>SLOT TIME TABLE - DEEPADHARSHINI(24005728)</h1>
    <tr bgcolor="red">
        <th>TIME/DAY</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr bgcolor="yellow">
      <th>8-10</th>
      <td>Maths</td>
      <td>Web</td>
      <td>C Prog</td>
      <td>Free Slot</td>
      <td>Physics</td>
      <td colspan="2">Free slot</td>
    </tr>
    <tr bgcolor="yellow">
       <th>10-12</th>
       <td>DS</td>
       <td>Physics</td>
       <td>Maths</td>
       <td>English</td>
       <td>ESS</td>
       <td>Free Slot</td>
    </tr>
    <tr bgcolor="yellow">
       <th>1-3</th>
       <td>C Prog</td>
       <td>English</td>
       <td>Mentor Meet</td>
       <td>DS</td>
       <td>Web</td>
       <td>Web</td>
    </tr>
    </table>
    <table border="2">
        <tr bgcolor="red">
            <th>S.no</th>
            <th>Couse code</th>
            <th>Course name</th>
        </tr>
        <tr bgcolor="yellow">
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr bgcolor="yellow">
            <td>2</td>
            <td>SH3214</td>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
        </tr>
        <tr bgcolor="yellow">
            <td>3</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr bgcolor="yellow">
            <td>4</td>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr bgcolor="yellow">
            <td>5</td>
            <td>19MA222</td>
            <td>PROBABILITY AND QUEING MODEL</td>
        </tr>
        <tr bgcolor="yellow">
            <td>6</td>
            <td>19AI403</td>
            <td>INTRODUCTION TO DATASCIENCE</td>
        </tr>
        <tr bgcolor="yellow">
            <td>7</td>
            <td>SH4801</td>
            <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
        </tr>
    </table>

## OUTPUT
![alt text](<Screenshot (4).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
