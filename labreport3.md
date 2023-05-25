# Lab Report 3 <br>
## ʕっ•ᴥ•ʔっ `grep` Options <br> <br> 
**grep -c**
```
[cs15lsp23qm@ieng6-203]:biomed:114$ grep -c "health" 1468-6708-3-1.txt
44
```
```
[cs15lsp23qm@ieng6-203]:biomed:115$ grep -c "adults" 1468-6708-3-1.txt
18
```
<br> The "-c" after grep means count and it is taking the third command line argument withing the parentheses and printing in the terminal how many times it appears in the text file you give it. This can be useful when trying to track a specific piece of data within a large file or rather when it would be too time consuming to count by hand. <br>
Source refrenced: https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/
<br><br>

**grep -w**
```
[cs15lsp23qm@ieng6-203]:biomed:116$ grep -w "risk" 1468-6708-3-1.txt
        excess risk for persons with very low BMI, but that persons
        with moderately high BMI had little or no extra risk except
        In older adults, risk factors may have a greater effect
        whom risk factors, subclinical disease, and morbidity are
          effects of obesity on risk factors for future health. A
        no excess risk for older adults who would be classified as
```
```
[cs15lsp23qm@ieng6-203]:biomed:117$ grep -w "unlikely" 1468-6708-3-1.txt
          persons, but we think this is unlikely given the absence
```
<br> The "-w" indicates to grep to find the lines in a given file where the third command line argument appears exactly. This command prints in the terminal all the lines it finds in the file following the previously mentioned guidelines. This can be useful when wanting to find lines of code in a file with a specific variable or method.  <br>
Source refrenced: https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/
<br><br>

**grep -i**
```
[cs15lsp23qm@ieng6-203]:biomed:125$ grep -i "covariates"  1468-6708-3-1.txt
        for relevant covariates [ 1 2 3 4 5 6 ] . All studies found
          Covariates
          baseline covariates that were prevalent in the elderly,
          and likely to be related to BMI. Self-reported covariates
          baseline. Clinical covariates include hypertension,
          second on all of the covariates listed above. We
        baseline covariates (analyses not shown).
        also adjusted for the entire set of covariates (columns 2
        adjusted for all covariates, is not very different (the
        covariates also made little difference for YHL (columns 3
          covariates made little difference in the findings. We
```

<br>

```
[cs15lsp23qm@ieng6-203]:biomed:126$ grep -i "clinical"  1468-6708-3-1.txt
        decreased mortality. Clinical trials powered to detect
        whom risk factors, subclinical disease, and morbidity are
          baseline. Clinical covariates include hypertension,
        significantly greater than zero. A clinical trial of a
          Implications for clinical trials
          YHL, but not YOL. Clinical trials of weight modification
          found for underweight older adults. Clinical trials whose
          outcome measure. Both YOL and YHL would be clinically
        YHL as the outcome measure in clinical trials involving 
```

<br>
The "-i" means to print all the lines where the third command line argument appears in a given file without being case sensitive. This could be useful when trying to identify how many lines a word or phrase appears in a given text document where that same word or phrase can have their capitalization flutctuate.  <br>
Source refrenced: https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/
<br><br>


**grep -n**
```
[cs15lsp23qm@ieng6-203]:biomed:118$ grep -n "conclusion" 1468-6708-3-1.txt
16:        adults drew similar conclusions [ 7 ] .
```
<br>

```
[cs15lsp23qm@ieng6-203]:biomed:121$ grep -n "expectancy" 1468-6708-3-1.txt
82:          or active life expectancy [ 14 ] . We based YHL on
325:          future improvements in life expectancy may be limited [
```
<br> The "-n" after grep basically means to find the number of the line that contains the third command line argument. In the terminal, it will print the number of the line where the word appears right before the colon. This can be useful if you want to find where a specific word or phrase is in a file and easily navigate to where that word or phrase appears. <br>
Source refrenced: https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples/
<br><br>




