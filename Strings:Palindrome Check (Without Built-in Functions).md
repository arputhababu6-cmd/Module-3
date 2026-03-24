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
s = "google"

reversed_s = s[::-1]

if s == reversed_s:

    print(f"'{s}' is a palindrome.")
else:

    print(f"'{s}' is not a palindrome.")
## Output
<img width="348" height="32" alt="image" src="https://github.com/user-attachments/assets/fa78750b-3d48-4436-b7a5-54d3f4564ea6" />

## Result
The program reverses the string "google" using a slicing technique and compares it to the original, ultimately determining and printing that the word is not a palindrome.
