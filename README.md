# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE:
```
<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>

   <body>
	<img src="logo.png" width="350" lenght="350"></img>
      <table border = "1" cellspacing="1" bordercolor="blue" bgcolor="grey">
         <tr>
	     	
            <th colspan="8">TIME TABLE</th>

         </tr>
	<tr>
		<th colspan="2">Reference No:</th>
        	<th colspan="2">22003992</th>
		<th colspan="2">Name:</th>
		<th colspan="2">Meetha Prabhu</th>
	</tr>
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
            <th>8</th>
            <th>9</th>
         </tr>
       
 
  <tr>
             <td>Monday</td>
             <td colspan="2"><center>Fundamentals of Web application development/19AI414/Karthi Govindharaju</center></td>
             <td colspan="2"><center>Free</center></td>
             <td><center>LUNCH BREAK</centre></td>
             <td colspan="2"><center>C programming/19AI304/Magitha Nirmala</center></td>
             <td colspan="2"><center>Statistics and Numerical Methods/19MA211/Gayathri Lakshmi</center></td>
</tr>
<tr>
             <td>Tuesday</td>
             <td colspan="2"><center>Fundamentals of Web Technology/19AI414/Karthi Govindharaju</center></td>
             <td colspan="2"><center>Transforms and Its Application/19MA219/H. Pratap</center></td></center>
             <td><center>LUNCH BREAK</center></td>
             <td colspan="2"><center>Free</center></td>
              <td colspan="2"><center>Free</center></td>
</tr>
<tr>
             <td>Wednesday</td>
             <td colspan="2"><center>Physics for Quantum Computing/19PH204/V.Ramalakshmi</center></td>
             <td colspan="2"><center>Principles of Chemistry in Engineering/19CY205/Dollhi</center></td>
             <td><center>LUNCH BREAK</center></td>
             <td colspan="2"><center>Transform and Its Application/19MA219/H. Pratap</center></td>
              <td colspan="2"><center>Free</center></td>
</tr>
  <tr>
             <td>Thursday</td>
             <td colspan="2"<center>Statistics and Numerical Methods/19MA211/Gayathri Lakshmi</center></td>
             <td colspan="2"><center>Free</center></td>
             <td><center>LUNCH BREAK</center></td>
             <td colspan="2"><center>Principles of Chemistry in Engineering/19MA205/Dollhi</center></td></center>
             <td colspan="2"><center>Physics for Quantum Computing/19PH204/V.Ramalakshmi</center></td></center>
</tr>
<tr>
             <td>Friday</td>
             <td colspan="2"><center>C programming/19AI304/Magitha Nirmala</center></td>
             <td colspan="2"><center>Statistics and Numerical Method/19MA211/Gayathri Lakshmi</center></td>
             <td><center>LUNCH BREAK</center></td>
             <td colspan="2"><center>Fundamentals of Web application development/19AI414/Karthi Govindharaju</center></td>
              <td colspan="2"><center>Free</center></td>
</tr>

 
        
      </table>
    <br><center>1. 19AI401 - Fundamentals of Web Technology</center></br>
    <br><center>2. 19AI304 - Python Programming</center></br>
    <br><center>3. 19MA211 -Statistics and Numerical Methods</center></br>
    <br><center>4. 19MA205 - Principles of chemistry in Engineering</center></br>
    <br><center>5. 19PH219 - Transform and Its Application</center></br>
    <br><center>6. 19PH214 - Physics for Quantum Computing</center></br>
          </body>
</html>
```
# OUPUT:
![time](Timetable%20output.jpg)