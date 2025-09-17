# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. Start the program.
2. Input a string s from the user.
3. Initialize five counters:
  - c → count of alphanumeric characters.
  - c1 → count of alphabetic characters.
  - c2 → count of digits.
  - c3 → count of lowercase letters.
  - c4 → count of uppercase letters.
4. For each character in the string:
  - If the character is alphanumeric, increment c.
  - If the character is alphabetic, increment c1.
  - If the character is a digit, increment c2.
  - If the character is lowercase, increment c3.
  - If the character is uppercase, increment c4.
5. After the loop:
  - If c >= 1, print True, else print False.
  - If c1 >= 1, print True, else print False.
  - If c2 >= 1, print True, else print False.
  - If c3 >= 1, print True, else print False.
  - If c4 >= 1, print True, else print False.
6. End the program.

---

## 💻  Program
~~~
s = input()
c,c1,c2,c3,c4=0,0,0,0,0
for i in range(len(s)):
    if s[i].isalnum():
        c+=1
    if s[i].isalpha():
        c1+=1
    if s[i].isdigit():
        c2+=1
    if s[i].islower():
        c3+=1
    if s[i].isupper():
        c4+=1
if c>=1:
    print('True')
else:
    print('False')
if c1>=1:
    print('True')
else:
    print('False')
if c2>=1:
    print('True')
else:
    print('False')
if c3>=1:
    print('True')
else:
    print('False')
if c4>=1:
    print('True')
else:
    print('False')

~~~

## Output
![IMG-20250917-WA0002 1](https://github.com/user-attachments/assets/cfe277dc-1e08-4b57-8e08-41a7a2f447ba)

## Result
Thus, the program has been executed and verified successfully.
