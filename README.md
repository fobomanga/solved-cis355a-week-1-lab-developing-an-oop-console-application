Download Link: https://assignmentchef.com/product/solved-cis355a-week-1-lab-developing-an-oop-console-application
<br>
<strong>OBJECTIVES</strong>

<ul>

 <li>Create a class in java with appropriate methods.</li>

 <li>Process user input with the class using the scanner for keyboard input and console output.</li>

</ul>




<strong>PROBLEM:  Health Profile Console Program</strong>

GymsRUs has a need to provide fitness/health information to their clients, including BMI and maximum heart rate. Your task is to write a console program to do this.




Body mass index (BMI) is a measure of body fat based on a person’s height and weight. BMI can be used to indicate if you are overweight, obese, underweight, or normal. The formula to calculate BMI is




The following BMI categories are based on this calculation.

<u>Category</u>                               <u>BMI Range</u>

Underweight                         less than 18.5

Normal                                  between 18.5 and 24.9

Overweight                           between 25 and 29.9

Obese                                    30 or more




Max heart rate is calculated as 200 minus a person’s age.




<strong>FUNCTIONAL REQUIREMENTS</strong>

Design and code a class called HealthProfile to store information about clients and their fitness data. The attributes (name, age, weight, and height) are private instance variables. The class must include the following methods.




<table>

 <tbody>

  <tr>

   <td width="145"><strong>method</strong></td>

   <td width="420"><strong>description</strong></td>

  </tr>

  <tr>

   <td width="145">setName</td>

   <td width="420">Receives a value to assign to private instance variable</td>

  </tr>

  <tr>

   <td width="145">setAge</td>

   <td width="420">Receives a value to assign to private instance variable</td>

  </tr>

  <tr>

   <td width="145">setWeight</td>

   <td width="420">Receives a value to assign to private instance variable</td>

  </tr>

  <tr>

   <td width="145">setHeight</td>

   <td width="420">Receives TWO inputs (height in feet, inches).  Converts and stores the total INCHES in private instance variable</td>

  </tr>

  <tr>

   <td width="145">getName</td>

   <td width="420">Returns private instance variable</td>

  </tr>

  <tr>

   <td width="145">getAge</td>

   <td width="420">Returns private instance variable</td>

  </tr>

  <tr>

   <td width="145">getWeight</td>

   <td width="420">Returns private instance variable</td>

  </tr>

  <tr>

   <td width="145">getHeight</td>

   <td width="420">Returns private instance variable (inches)</td>

  </tr>

  <tr>

   <td width="145">getBMI</td>

   <td width="420">Calculates and returns BMI</td>

  </tr>

  <tr>

   <td width="145">getCategory</td>

   <td width="420">Returns category based on BMI</td>

  </tr>

  <tr>

   <td width="145">getMaxHR</td>

   <td width="420">Calculates and returns maximum heart rate</td>

  </tr>

 </tbody>

</table>




Create a SEPARATE TEST CLASS, Lab1Main, to prompt for user input and display output using the HealthProfile class. Process multiple inputs using a loop. You can assume all user input is valid.




<strong>SAMPLE OUTPUT</strong>




Enter name or X to quit: John Smith

Your age: 35

Your weight: 200

Your height – feet: 6

Your height – inches: 0




Health Profile for John Smith

BMI:  27.1

BMI Category: overweight

Max heart rate: 185




Enter name or X to quit: Ann Jones

Your age: 50

Your weight: 120

Your height – feet: 5

Your height – inches: 2




Health Profile for Ann Jones

BMI:  21.9

BMI Category: normal

Max heart rate: 170




Enter name or X to quit: X







<strong> </strong>

<strong></strong>

<strong> </strong>

<strong>GRADING RUBRIC</strong>

<table width="631">

 <tbody>

  <tr>

   <td width="541">HealthProfile class·         All methods created with proper functionality</td>

   <td width="90">30</td>

  </tr>

  <tr>

   <td width="541">Lab1Main class·         Receives user input using Scanner·         Process input using a HealthProfile object·         Correct output displayed in console·         BMI displayed with 1 decimal place·         Loop to process multiple clients</td>

   <td width="90">10</td>

  </tr>

  <tr>

   <td width="541">Code style</td>

   <td width="90">5</td>

  </tr>

  <tr>

   <td width="541">Lab Report</td>

   <td width="90">10</td>

  </tr>

  <tr>

   <td width="541">TOTAL</td>

   <td width="90">55</td>

  </tr>

 </tbody>

</table>




<strong>CODE STYLE REQUIREMENTS</strong>

<ul>

 <li>Include meaningful comments throughout your code.</li>

 <li>Use meaningful names for variables.</li>

 <li>Code must be properly indented.</li>

 <li>Include a comment header at beginning of each file, example below.</li>

</ul>

<strong>/****************************************************Program Name: ProgramName.javaProgrammer’s Name: Student NameProgram Description: Describe here what this program will do***********************************************************/</strong>




<strong>DELIVERABLES</strong>

Submit as a SINGLE zip folder

<ul>

 <li>All java files</li>

 <li>Lab report</li>

</ul>




Follow assignment specification regarding class/method names.

Note that your java filename must match class name (DO NOT rename).


