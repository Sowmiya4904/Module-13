
# Exp.No:31 IMPLEMENTATION OF STACK
# AIM To write a Python program to implement a stack using a list and its built-in methods (append(), pop()).

# ALGORITHM
Start the program. Define a class st with the following methods: push(self, num): Adds the number num to the stack. pop(self): Removes and returns the top element from the stack. Create a stack object s using the class st. Input the stack size: Take an integer input size to define the size of the stack. Loop through numbers from 1 to size: Add only the odd numbers to the stack using the push() method. Display the elements in the stack after the loop completes. Call pop() to remove the top element from the stack and display the popped element. Display the stack again to show the remaining elements. End the program.

# PROGRAM
~~~
Reg - 212222020028 Name - G.Sowmiya

stack = []
class st:
    def push(self,L):
        for i in L:
            stack.append(i)
        return
    
    # Write your code here

    def pop(self):
        if stack:
            print("Element popped : ",stack.pop())
        else:
            print("empty")
    
    # Write your code here
   
    def peek(self):
        print("Elements in the stack\n",stack)
    
    # Write your code here
s=st()
a=int(input())
l=[i for i in range(1,a) if i%2!=0]
s.push(l)
s.peek()
s.pop()
s.peek()
~~~
# OUTPUT
<img width="1213" height="286" alt="image" src="https://github.com/user-attachments/assets/0fe7aae3-2723-45bf-84f7-aba250bc9db7" />

# RESULT 
Thus the program to implement a stack using a list and its built-in methods has been implemented and executed successfully.
