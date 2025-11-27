## 2E Loops in Python: Palindrome Number Checker
## Developed by : Srinithi Muthukumar
## Register No. : 212224240161
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

## 🧾 Program :

```
## Developed by : Srinithi Muhtukumar
## Register No. : 212224240161
num=int(input())
temp=num
rev=0
while temp!=0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```

## Output :

<img width="1097" height="203" alt="image" src="https://github.com/user-attachments/assets/597983cd-9e48-4624-95a0-a5b46083cdb4" />

## Result :
Programm was executed successfully.
