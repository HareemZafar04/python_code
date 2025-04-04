# python_code

📘 Python Basics – Loops, Ranges, and Data Structures
This README explains some fundamental Python concepts through examples. It covers:

The range() function

Loops (for and while)

Basic data types: list, tuple, string, int, bool

Mutable vs immutable types

🔁 range() Function
The range() function generates a sequence of numbers.

x = range(1, 10)  # 1 to 9
print(list(x))    # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9]

Parameters of range(start, stop, step):

start: Starting number (default is 0)

stop: End (not inclusive)

step: Increment (default is 1)

📋 Multiplication Table Examples
Aam Zindagi (Manual Method)

num = 2
print("2 x 1 =", num * 1)
print("2 x 2 =", num * 2)
...
print("2 x 10 =", num * 10)




Mintos Zindagi (Using Loop)

for num in range(1, 11):
    print(f"2 x {num} = {2 * num}")
🔄 Loops
1. For Loop
Used to iterate over a sequence (like a list or range).


for num in range(5):
    print(num)
2. While Loop
Repeats as long as a condition is True.


num = 1
while num < 10:
    print("Before increment:", num)
    num += 1
🔐 Password Check Example

password = "python123"
user_input = ""

while user_input != password:
    print("Incorrect password!")
    user_input = input("Type your answer please: ")
📦 Data Types
1. List (Mutable)

names = ["Ali", "Bilal", "Hamza", "Okasha"]
names[1] = "Abdullah"  # allowed
2. Tuple (Immutable)

names = ("Ali", "Bilal", "Hamza", "Okasha")
names[1] = "Abdullah"  # ❌ Error: Tuples are immutable
