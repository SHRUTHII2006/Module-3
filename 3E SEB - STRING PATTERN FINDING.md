# Exp.No:3e
## SEB - Find sequences of Lower case letters joined with a '#'.

---

### AIM  
To Write a Python program to find sequences of Lower case letters joined with a '#'.

---

### ALGORITHM

1.Input: Take a string as input that may contain various characters and words.

2.Define Pattern: Use a regular expression pattern to match sequences like abc#def (i.e., lowercase letters on both sides of #).

3.Search: Scan the string using the regex to find all matches of the defined pattern.

4.Collect Matches: Store all matching sequences in a list or suitable data structure.

5.Output: Return or print the list of matched sequences.


### PROGRAM

import re

a=input()

pattern=r'[a-z]#'

if re.search(pattern,a):

    print("Found a match!")
    
else:

    print("Not matched!")
    


### OUTPUT

![image](https://github.com/user-attachments/assets/52d5b9a5-284a-472b-a730-d628082bf69c)


### RESULT

Thus the Python program to find sequences of Lower case letters joined with a '#' was successfully executed.
