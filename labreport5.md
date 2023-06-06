# Lab Report 5 <br>
## ʕっ•ᴥ•ʔっ Part 1 – Debugging Scenario <br> <br> 
---
**1) Mock Student Post** <br>
![Image](MockStudentPost2.png) <br>
<br>
For reference, here is a clearer version of the screenshot within the edstem post: <br>
![Image](SymptomLab5.png) <br>

**1) TA Mimick Response** <br>
> Consider what directory you are in and where the junit tests are. How would you access the lib folder with the path you are passing in your bash script? 
<br>

**2) Bug & Student's Terminal Output** <br>
The bash script correctly runs in the screenshot below. The bug was that the student's `CPATH` within their bash script did not have a proper relative path to the lib folder where the .jar files needed to run JUnit are. 
![Image](ConsideringTA.png) <br>

**3) Setup** <br>







