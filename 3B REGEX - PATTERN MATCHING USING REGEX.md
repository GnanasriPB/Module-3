# Exp.No:3b  
 REGEX - PATTERN MATCHING USING REGEX

---

 AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

 PROGRAM

import re

s=input()

pattern=r'[a-z]*_[a-z]+'

if re.search(pattern,s):

    print("Found a match!")
    
else:

    print("Not matched!")
    
    
OUTPUT

![image](https://github.com/user-attachments/assets/46686b32-84cf-4a6a-8511-14385847b895)


RESULT

Thus the  Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions was implemented and executed successfully.


