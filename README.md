# Week Two Assignment: List Operations 📝

**Author:** Alembesh Getaneh  
**Assignment:** Intro to Python  

---

## Description
This Python program demonstrates basic list operations.  
It performs the following steps on a list called `my_list`:

1. Creates an empty list.
2. Appends elements: 10, 20, 30, 40.
3. Inserts the value 15 at the second position.
4. Extends the list with `[50, 60, 70]`.
5. Removes the last element.
6. Sorts the list in ascending order.
7. Finds and prints the index of the value 30.

---

## Python Code
The program is implemented in `week2_list_operations.py`.  
Here’s the example code:

```python
# Week Two Assignment: List Operations
# Name: Alembesh Getaneh

my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()
index_of_30 = my_list.index(30)

print("Final list:", my_list)
print("Index of 30:", index_of_30)
How to Run
Make sure Python 3.x is installed on your system.

Save the code in a file named week2_list_operations.py.

Open a terminal in the folder containing the file.

Run the program:

python week2_list_operations.py


Observe the output:

Final list: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3

Notes
Demonstrates key list methods: append(), insert(), extend(), pop(), sort(), index().
Helps in understanding Python list manipulation and indexing.
