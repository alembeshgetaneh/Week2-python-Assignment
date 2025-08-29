
# Week Two Assignment – Python List Operations

## Description
This assignment demonstrates basic list operations in Python such as appending, inserting, extending, removing, sorting, and finding the index of an element.

## Steps Performed
1. Create an empty list called `my_list`.
2. Append the following elements to `my_list`: `10, 20, 30, 40`.
3. Insert the value `15` at the second position in the list.
4. Extend `my_list` with another list: `[50, 60, 70]`.
5. Remove the last element from `my_list`.
6. Sort `my_list` in ascending order.
7. Find and print the index of the value `30` in `my_list`.

## Code

```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend the list with [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element
my_list.pop()

# Step 6: Sort the list in ascending order
my_list.sort()

# Step 7: Find and print the index of value 30
index_of_30 = my_list.index(30)
print("Final List:", my_list)
print("Index of 30:", index_of_30)

#Expected Output
Final List: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3
