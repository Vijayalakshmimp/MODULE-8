# 🔍 Hackerrank:Python program to replace the substring "not...poor" with "good" if "poor" follows "not".

Python program to replace the substring "not...poor" with "good" if "poor" follows "not".

---

## 🎯 Aim
To write a Python program that finds the first appearance of the substrings 'not' and 'poor' in a given string, and if 'poor' follows 'not', replace the whole 'not'... 'poor' substring with 'good'.

---

## 🧠 Algorithm
1. Start the program.
2. Read the input string.
3. Find the index of the substring 'not'.
4. Find the index of the substring 'poor'.
5. If 'poor' comes after 'not', replace the entire substring from 'not' to 'poor' with 'good'.
6. Display the resulting string.
7. Stop the program.

---

## 💻  Program
def not_poor(str1):

  snot = str1.find('not')

  spoor = str1.find('poor')
  
  if spoor > snot and snot>0 and spoor>0:
   
    str1 = str1.replace(str1[snot:(spoor+4)], 'good')
    
    return str1
  
  else:
  
    return str1

print(not_poor('The lyrics is not that poor!'))

## Output
<img width="790" height="156" alt="image" src="https://github.com/user-attachments/assets/3745b911-eaed-4514-8ac3-3479a0c8cd66" />

## Result
Thus, the Python program was successfully executed and verified.
