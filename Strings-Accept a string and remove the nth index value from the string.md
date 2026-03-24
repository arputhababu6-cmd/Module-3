# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(input_string):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(input_string)):
        if i != n:
            a += input_string[i]
    return a

test_string = input("Enter a string: ")
print(remove(test_string))
## Output
<img width="312" height="74" alt="image" src="https://github.com/user-attachments/assets/b3b9198e-d477-45d0-ba3d-43bc517da721" />

## Result
The program iterates through a user-provided string and constructs a new version of it that excludes the character located at a specifically chosen index.
