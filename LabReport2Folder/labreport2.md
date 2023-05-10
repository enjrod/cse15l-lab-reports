# Lab Report 2 <br>

### Part 1  <br>
**String Server Code** <br> <br>
![Image](https://github.com/enjrod/cse15l-lab-reports/blob/main/LabReport2Folder/Lab2-Code.png)<br>
---
**Examples of using add-message** <br> <br>

![Image](https://github.com/enjrod/cse15l-lab-reports/blob/main/LabReport2Folder/Lab2SC1.png)<br>

When using `add-message` in the url, it gets passed to the handleRequest method which checks for the appropritae syntax of the query and then takes the string after `s=` and sets it to the variable "toReturn". That same string is added in to the arraylist "toAdd" and then the updated contents of "toAdd" are returned--being what you see in the image above. <br>

![Image](https://github.com/enjrod/cse15l-lab-reports/blob/main/LabReport2Folder/Lab2SC2.png)<br>

In this use of `add-message`, it too employs the handleRequest method and takes the string query after `s=` and sets it to the variable "toReturn". That string is then added into the arraylist "toAdd" and then the contents of "toAdd" are returned which now include the present and previous query. <br>

---

### Part 2 <br>

**Non-Failure Inducing Input**
```
@Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
```
<br>

**Failure Inducing Input**
```
@Test
  public void testReversed2() {
    int[] input1 = {1, 2, 3};
    assertArrayEquals(new int[]{3, 2, 1}, ArrayExamples.reversed(input1));
  }
```
**Symptom** <br>

**Bug**
