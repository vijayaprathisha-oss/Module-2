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
n=int(input())
n1=n
pal=n
rev=0
while n>0:
    r=n%10
    rev=rev*10+r
    n=n//10
if pal==rev:
    print("The given number",n1,"is a Palindrome")
else:
    print("The given number",n1,"is not a palindrome")
## Output
<img width="916" height="861" alt="image" src="https://github.com/user-attachments/assets/9f868a81-e7c1-40f4-9d89-be7a0a2ce1ac" />


## Result
Thus, the given python program has been executed successfully
