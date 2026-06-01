# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
text = "google"

reverse = ""

for i in text:
    reverse = i + reverse

if text == reverse:
    print(text, "is a palindrome")
else:
    print(text, "is not a palindrome")
```
## Output
<img width="906" height="92" alt="image" src="https://github.com/user-attachments/assets/ddfab16b-be45-4d74-8b29-b2de59ea1084" />


## Result
the output is verified
