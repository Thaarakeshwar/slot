# Ex02 Time Table
## Date:09/12/2025

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
<head>
    <title>Timetable For Semester</title>
</head>            
    <body> 
        <center>
         <img src='c:\Users\acer\OneDrive\timetable\slot\myproject\slotapp\static\Screenshot (40).png' width="750" height="100">
        </center>
      <h3 align="center">  SLOT TIME TABLE </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8.00-9.45</th>
          <th bgcolor="yellow">10.00-11.45</th>
          <th bgcolor="yellow">1.00-2.45</th>
          <th bgcolor="yellow">3.00-4.45</th>
        </tr>
        <tr>
           <th bgcolor="yellow">MONDAY </th>
           <td>Python</td>
           <td>Python</td>
           <td>Web</td>
           <td>English</td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>Web</td>
            <td>-</td>
            <td>Python</td>
            <td>Web</td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>Web</td>
            <td>-</td>
            <td>Mentor Meet</td>
            <td>English</td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>-</td>
            <td>English</td>
            <td>Web</td>
            <td>-</td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>-</td>
            <td>Python</td>
            <td>Python</td>
            <td>-</td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>English</td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1</th> 
            <td>5Q-63</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2</th>
             <td>5P2-1</td>
             <td>COMMUNICATION ENGLISH  </td>
          </tr> 
         
          <tr>
             <th>3</th>
             <td>5P-1</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>
         </table>   
    </body>
</html>
```


## OUTPUT
<img width="1920" height="1080" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/c3d39f4f-2e62-46ae-baae-4e6bcd1ce1a0" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
