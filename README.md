# Ex03 Time Table
## Date:23/04/2025

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
    <img src="logo.jpg">
        <table border="1" cellspacing="10" cellpadding="2">
            <caption>SLOT TIME TABLE -Vamsi Reddy(24003778)</caption>
            <tbody><tr bgcolor="lavender">
               <th bgcolor="violet">DAY/TIME</th>
               <th>Monday</th>
               <th>Tuesday</th>
               <th>Wednesday</th>
               <th>Thursday</th>
               <th>Friday</th>
               <th>Saturday</th>
            </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">8-10</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>PHY</td>
                    <td>ML</td>
                    <td>FREE SLOT</td>
                </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">10-12</td>
                <td>FREE SLOT</td>
                <td>SOFT ENG</td>
                <td>LAC</td>
                <td>SOFT ENG</td>
                <td>FWAD</td>
                <td>LAC</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">12-1</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">1-3</td>
                <td>ADV C</td>
                <td>PHY</td>
                <td>SCOFT MM</td>
                <td>ML</td>
                <td>HV</td>
                <td>ADV C</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">3-5</td>
                <td>RA</td>
                <td>FREE SLOT</td>
                <td>OS</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>OS</td>
            </tr>
        </tbody></table>
        <table border="1" cellspacing="10" cellpadding="2">
            <tbody><tr bgcolor="sky blue">
                <th bgcolor="sky blue">S.NO</th>
                <th>Course code</th>
                <th>Course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI410</td>
                <td>INTRODUCTION TO MACHINE LEARNING</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI305</td>
                <td>ADVANCED C PROGRAMMING</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19MA206</td>
                <td>LOGIC AND COMBINATORICS</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19PH814</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19CS408</td>
                <td>SOFTWARE ENGINEERING</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19CS405</td>
                <td>OPERATING SYSTEM</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19HS801</td>
                <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>19EY709</td>
                <td>REASONING ABILITY</td>
            </tr>
            <tr>
                <tr>
                <td>9.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>10.</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
        </body></table>
    
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot (2).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
