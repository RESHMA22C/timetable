# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
create a static folder and inert HTML code.
### STEP 3
create a simple table using```<table>```tag in html
### STEP 4
Add header row using```<th>```tag.
### STEP 5
Add your timetable using```<td>```tag.
### STEP 6
Execute the program using runserver command.

# PROGRAM
 ```
 <html>
    <head>
        <tittle></tittle>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption><br>SLOT TIME TABLE - RESHMA C(23012886)</caption></caption>
        <tr align="center">
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td >FUNDAMENTALS OF C PROGRAMMING</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>PHYSICS FOR QUANTUM COMPUTATION</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td> PRINCIPALS OF CHEMISTRY IN ENGINEERING</td>
        <td>FREE SLOT</td>
        <td>STATISTICS AND NUMERICAL METHODS</td>
        </tr>
        <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">1-3</th>   
        <td >FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FUNDAMENTALS OF WEN APPLICATION</td>
        <td>SOFT SKILLS</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td> STATISTICS AND NUMERICAL METHODS</td>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>PHYSICS FOR QUANTUM COMPUTATION</td>
        <td>PRINCIPALS OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        </tr>
        <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
        <td align="center">2.</td>
        <td align="center">19AI304</td>
        <td>Fundamentals of C PROGRAMMING (C PROGRAM)</td>
        </tr>
        <tr>
        <td align="center">3.</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
        <td align="center">4.</td>
        <td align="center">19CY205</td>
        <td>PRINCIPALS OF CHEMISTRY IN ENGINEERING (CHE)</td>
        </tr>
        <tr>
        <td align="center">5.</td>
        <td align="center">19MA211</td>
        <td>STATISTICS AND NUMERICAL METHODS (MAT)</td>
        </tr>
        <tr>
        <td align="center">6.</td>
        <td align="center">19EY701</td>
        <td>SOFT SKILLS (SS)</td>
        </br>
        </tr>
        </table>
        </body>
        </html>
 ```
 ## OUTPUT
 file:///home/sec/fwad/ex03/timetable/Screenshots/Screenshot%20from%202023-11-24%2021-44-42.png![image](https://github.com/RESHMA22C/timetable/assets/147474426/51136662-6abf-4527-b28e-719c69766371)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
