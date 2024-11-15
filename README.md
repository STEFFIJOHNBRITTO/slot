# Ex03 Time Table
## Date:15.11.2024

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
    <body>
       <img src="logo.png" width="700" height="90">
<table border="1" cellspacing="5" cellpadding="15">
   <caption> SLOT TIME TABLE - STEFFI J (24900405)</caption>
   <tr bgcolor="grey">
      <th>DAY/TIME</th>
      <th>MONDAY</th>
      <th>TUESDAY</th>
      <th>WEDNESDAY</th>
      <th>THURSDAY</th>
      <th>FRIDAY</th>
      <th>SATURDAY</th>
   </tr>
   <tr>
       <th bgcolor="orange">8-10</th>
       <td bgcolor="green">FREE SLOT</td>
       <th>WEB</th>
       <td bgcolor="green">FREE SLOT</td>
       <th>HUMAN VALUES</th>
       <td bgcolor="green" colspan="2"> FREE SLOT</td>
   </tr>
   <tr>
      <th bgcolor="orange">10-12</th>
      <th>MATHS</th>
      <td bgcolor="green" colspan="2"> FREE SLOT</td>
      <th>CAREER</th>
      <th>BEEM</th>
      <th>C PROGRAM</th>
   </tr>
   <tr>
      <th bgcolor="orange">12-1</th>
      <th colspan="6">LUNCH</th>
   </tr>
   <tr>
      <th bgcolor="orange">1-3</th>
      <th>C PROGRAM</th>
      <th>MATHS</th>
      <th>MENTOR MEET</th>
      <th>DIGITAL</th>
      <th colspan="2">WEB</th>
   </tr>
   <tr>
      <th bgcolor="orange">3-5</th>
      <td bgcolor="green">FREE SLOT</td>
      <th>DIGITAL</th>
      <td bgcolor="green" colspan="2">FREE SLOT</td>
      <th>YOGA</th>
      <th>BEEM</th>

   </tr>
   </table>
   <br>

   <table border="1" cellspacing="5" cellpadding="15">
   <tr bgcolor="grey">
      <th>S.NO</th>
      <th>COURSE.CODE</th>
      <th>COURSE.NAME</th>
   </tr>
   <tr>
      <td bgcolor="orange">1</td>
      <td>19AI414</td>
      <td>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT</td>
   </tr>
   <tr>
      <td bgcolor="orange">2</td>
      <td>19AI304</td>
      <td>FUNDAMENTALS OF C PROGRAMMING</td>
   </tr>
   <tr>
      <td bgcolor="orange">3</td>
      <td>19EE305</td>
      <td>BEEM</td>
   </tr>
   <tr>
      <td bgcolor="orange">4</td>
      <td>19EE404</td>
      <td>DIGITAL ELECTRONICS</td>
   </tr>
   <tr>
      <td bgcolor="orange">5</td>
      <td>19EY708</td>
      <td>CAREER</td>
   </tr>
   <tr>
      <td bgcolor="orange">6</td>
      <td>19MA201</td>
      <td>MATHS</td>
   </tr>
   <tr>
      <td bgcolor="orange">7</td>
      <td>ECA-M-SCOFT</td>
      <td>MENTOR MEET</td>
   </tr>
   <tr>
      <td bgcolor="orange">8</td>
      <td>SH5616</td>
      <td>YOGA</td>
   </tr>
   <tr>
      <td bgcolor="orange">9</td>
      <td>SH7801</td>
      <td>HUMAN VALUS AND PROFESSIONAL ETHICS</td>
   </tr>
</table>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (12).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
