## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="474" height="283" alt="image" src="https://github.com/user-attachments/assets/e1af9fd5-94d8-48b4-90c3-c4c7af27ea45" />
## Output
<img width="237" height="66" alt="image" src="https://github.com/user-attachments/assets/b2b86a9e-bcfa-4878-9feb-cecfddbc9367" />

## Result
<img width="361" height="55" alt="image" src="https://github.com/user-attachments/assets/0939b871-c530-4b8d-a01f-968d6c38b841" />
