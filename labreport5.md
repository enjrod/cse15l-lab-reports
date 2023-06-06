# Lab Report 5 <br>
## ʕっ•ᴥ•ʔっ Part 1 – Debugging Scenario <br>
<br>
**1) Mock Student Post** <br>

![Image](MockStudentPost2.png) <br>

<br>
<br>
For reference, here is a clearer version of the screenshot within the edstem post: <br>

![Image](SymptomLab5.png) <br>

<br>

**1) TA Mimick Response** <br>
> Consider what directory you are in and where the junit tests are. How would you access the lib folder with the path you are passing in your bash script? 
<br>

**2) Bug & Student's Terminal Output** <br>
The bash script correctly runs in the screenshot below. The bug was that the student's `CPATH` within their bash script did not have a proper relative path to the lib folder where the .jar files needed to run JUnit are. 
![Image](ConsideringTA.png) <br>

**3) Setup** <br>
> Directory Structure <br>

![Image](DirectorySt.png) <br>

> File Structure (After fixing the bug) <br>

![Image](FileSt.png) <br>

> File Structure (Before fixing the bug) <br>

![Image](BeforeLab5.png) <br>

> Command Triggering the Bug <br>

`sh grade.sh https://github.com/ucsd-cse15l-f22/list-methods-lab3` <br>


> To fix the bug <br>
<br>
In order to fix the bug, you will have to change the path given in `CPATH` and add ".." before lib to properly access the jar files within the lib folder. <br><br>

## ʕっ•ᴥ•ʔっ Part 2 – Reflection <br>
<br>
The most interesting thing I learned this second half of the quarter would have to be the vim command and being able to access as well as edit files within the terminal. Personally, this is what piqued my interest because it was a whole new way to write code and at that point I thought the terminal could only compile files--not expecting you could edit withi it. Another thing I would like to aknowledge would be the ouotput redirection. I just think its cool that there is a convenient way to save an output after compiling!








