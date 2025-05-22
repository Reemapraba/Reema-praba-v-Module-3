# Reema-praba-v-Module-3
# 19CS301-Module3
### Register No - 212222020020
### Name - Reema praba V

# ExNo: 3.1 String
### Aim: To write a python program to find the length of the given string.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a variable `str`.

**STEP 3:** Get a string input from the user and store it in `str`.

**STEP 4:** Find the length of the string using the `len()` function and store it in variable `a`.

**STEP 5:** Print the length of the string using formatted output.

**STEP 6:** Stop.

### Program:
```
str = input()
a = len(str)
print(f"The length of the string '{str}' is",a)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/393e432a-aec8-4fa2-a0e5-6944f16108ee)
![image](https://github.com/user-attachments/assets/96104f48-849e-4133-98be-9fc0c93351f7)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 3.2 Regex
### Aim: To write a python program For the given list, filter all elements that do not contain - items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a list called `items` containing some strings.

**STEP 3:** Use a list comprehension to create a new list `filtered_items`:
- Include only those items from `items` that do **not** contain the letter `'e'`.

**STEP 4:** Print the `filtered_items` list.

**STEP 5:** Stop.

### Program:
```
items = ['goal','new','user','sit','eat','dinner']
filtered_items = [item for item in items if 'e' not in item]
print(filtered_items)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/5cc5d231-d1fd-40ab-bf3d-739d3f7a654c)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 3.3 List
### Aim: To write a non parameterized function to print the list in descending order that is entered by the user.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Define a function `sortlist()`.

**STEP 3:** Inside the function:
- Get a list input from the user using `eval(input())` and store it in variable `a`.

**STEP 4:** Sort the list `a` in descending order using `a.sort(reverse=True)`.

**STEP 5:** Print the sorted list.

**STEP 6:** Call the function `sortlist()`.

**STEP 7:** Stop.

### Program:
```
def sortlist():
     a = eval(input())
     a.sort(reverse=True)
     print(a)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/f5457e85-36de-4142-890d-717d2dc1ec7c)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 3.4 Tuples
### Aim: To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a variable `a`.

**STEP 3:** Get the value of `a` from the user.

**STEP 4:** Create an empty list `l`.

**STEP 5:** Use a `for` loop to iterate from 5 to `a` (exclusive) in steps of 5:
- Append each number to the list `l`.

**STEP 6:** Convert the list `l` to a tuple `x`.

**STEP 7:** Print the tuple `x`.

**STEP 8:** Stop.

### Program:
```
def sortlist():
     a = eval(input())
     a.sort(reverse=True)
     print(a)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/60fa3c68-0f59-4bc5-bfc1-3629fefff45b)

### Result: Thus, the given program is implemented and executed successfully .
