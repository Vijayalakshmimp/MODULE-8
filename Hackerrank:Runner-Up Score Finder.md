# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
~~~
n = int(input())
arr = list(map(int, input().split()))
arr = list(set(arr))
arr.sort()
print(arr[-2])
~~~

## OUTPUT
![IMG-20250917-WA0001 1](https://github.com/user-attachments/assets/7069a502-415b-41c6-bc2e-cf625601e92b)

## RESULT
Thus, the program has been executed and verified successfully.
