# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```
# Reg.No-212223060072
# Name-Gowri.M

stack = []

class Stack:
    def push(self, items):
        for i in items:
            stack.append(i)

    def pop(self):
        if stack:
            print("Element popped:", stack.pop())
        else:
            print("The stack is empty")

    def peek(self):
        print("Elements in the stack:\n", stack)

# Create stack object
s = Stack()

# Input size and generate even numbers less than size
size = int(input("Enter size: "))
l = [i for i in range(1, size) if i % 2 == 0]

# Push, peek, pop, and peek again
s.push(l)
s.peek()
s.pop()
s.peek()
```
# OUTPUT
<img width="759" height="305" alt="{B4182EF7-1E15-41E9-8A58-97C2F3E0EBDE}" src="https://github.com/user-attachments/assets/789ef41e-f875-4377-8a3b-4b9eb239dc46" />
# RESULT
Thus the program to implement a stack using a list and its built-in methods has been implemented and executed successfully.
