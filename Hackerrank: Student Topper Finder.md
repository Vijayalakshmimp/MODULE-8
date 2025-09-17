# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
~~~
marks=eval(input())
total={name: sum(scores) for name, scores in marks.items()}
print(total)
topper=max(total,key=total.get)
print("Topper is: ",topper,"with marks = ",total[topper])
~~~

## OUTPUT
<img width="1261" height="244" alt="image" src="https://github.com/user-attachments/assets/8101571a-db58-4a67-8241-ce209c903d2e" />

## RESULT
Thus, the program has been executed and verified successfully.
