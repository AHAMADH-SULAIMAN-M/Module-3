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
```python
s = "google"        # assign string

rev = s[::-1]        # reverse using slicing

if s == rev:         # compare
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")

```
## Output

<img width="817" height="230" alt="image" src="https://github.com/user-attachments/assets/a3d4b9c0-1bd6-4b90-bceb-261555b53600" />

## Result
The python program to check whether the string google is a palindrome or not, without using inbuild function is executed successfully and verified
