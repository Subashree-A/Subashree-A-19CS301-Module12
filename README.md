# Subashree-A-19CS301-Module12

### Register No - 212222020029
### Name - Subashree A

# ExNo: 12.1 Stack using linked list (Display, Peek and Pop)
### Aim: To Type and display the elements pushed in stack using python.

### Algorithm:

STEP 1: Start.

STEP 2: Create an empty list called stack.

STEP 3: Push elements onto the stack using the append() method.

STEP 4: Print a message indicating the stack after pushing elements.

STEP 5: Display the current contents of the stack.

STEP 6: Stop.

### Program:
```
stack = []

stack.append('a')
stack.append('b')
stack.append('c')

print("Stack after elements are pushed:")
print(stack)


```
### OUTPUT:

![image](https://github.com/user-attachments/assets/f3ceaa65-d809-4f0c-9b76-63c92ff6962f)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 12.2 Stack using linked list (Push and all operations)

### Aim: To Type a python code to insert 3 elements. Also check and print the index value of the elements stored in the stack.

### Algorithm:

STEP 1: Start.

STEP 2: Create an empty list called stack.

STEP 3: Push three elements onto the stack using the append() method.

STEP 4: Print the initial contents of the stack.

STEP 5: Use a loop to iterate through the stack with enumerate() and print the index and corresponding value.

STEP 6: Stop.

### Program:
```
stack = []

# Insert 3 elements
stack.append('a')
stack.append('b')
stack.append('c')

print('Initial stack: ' + str(stack))

# Print index and element
for index, value in enumerate(stack):
    print(index, value)


```
### OUTPUT:

![image](https://github.com/user-attachments/assets/8920da3e-a608-4162-a650-73a2feedfed7)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 12.3 Queue using linked list (Display, Peek and Pop)

### Aim: To Type a python code to insert 3 elements. Also check and print the index value of the elements stored in the queue.

### Algorithm:

STEP 1: Start.

STEP 2: Create an empty list called queue.

STEP 3: Enqueue three elements into the queue using the append() method.

STEP 4: Print the initial contents of the queue.

STEP 5: Use a loop with enumerate() to display the index and corresponding element of each item in the queue.

STEP 6: Stop.

### Program:
```
queue = []

queue.append('a')
queue.append('b')
queue.append('c')

print('Initial queue: ' + str(queue))

for index, value in enumerate(queue):
    print(index, value)

```
### OUTPUT:

![image](https://github.com/user-attachments/assets/99d705a5-df02-464e-bd3a-73b9ef3991d5)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 12.4 Queue using linked list (Enqueue and all operations)

### Aim: To Type a python code to insert 3 players in the list. Also check and print the index value of the players in the list.

### Algorithm:

STEP 1: Start.

STEP 2: Create an empty list called queue.

STEP 3: Enqueue three elements (Player_1, Player_2, Player_3) using the append() method.

STEP 4: Print the initial contents of the queue.

STEP 5: Use a for loop with range(len(queue)) to print the index and corresponding element from the queue.

STEP 6: Stop.

### Program:
```
queue = []

queue.append('Player_1')
queue.append('Player_2')
queue.append('Player_3')

print('Initial queue: ' + str(queue))

for i in range(len(queue)):
    print(i, end=" ")
    print(queue[i])
```
### OUTPUT:

![image](https://github.com/user-attachments/assets/3d2716d9-678d-483f-a35e-67ec4f55d685)

### Result: Thus, the given program is implemented and executed successfully .
