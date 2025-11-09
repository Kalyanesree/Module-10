## EX 10 (D) Stack-Stack Reversal Program 

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## Aim
To write a Python program that reverses the values in a stack using standard stack operations.

## Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```
stack = []
n = int(input())
for i in range(n):
    val = int(input())
    stack.append(val)
reverse = []
while stack:
    reverse.append(stack.pop())
print(reverse)
```
## Output
<img width="1210" height="464" alt="image" src="https://github.com/user-attachments/assets/7ac3b743-4738-47e9-a6ae-b97104e99a24" />

## Result
  Thus, the python program that reverse the values in a stack has been executed successfully.
