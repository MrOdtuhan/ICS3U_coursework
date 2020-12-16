# Functions and Lists Quiz

You will build a markbook program for a teacher entering grades for students. You will be responsible for creating functions and then using them in a `main()` function, which will be the menu system for the user. You should start with the functions themselves; the `main` function is a lesser part. The functions are in order of appearence in the `main` function. Look them all over to choose which ones you should work on first. They don't need to be completed in order.

### The `main` function
The structure of the `main()` function will be:

- Ask the teacher for their name (function #1)
- Print out a welcome message to the teacher (function #2)
- Ask the teacher how many student marks they would like to enter. (function #3)
- Use that number to create a loop to do the following:
  - Get a student name (function #1) and add it to a list of student names.
  - Get a mark (function #3) and add it to another list, this one of student marks
- Display a report of student names and their marks. (function #4)
- Display the number of failing students (function #5)


### The Functions:
1. Create a function that will ask the user for a name (keyboard input). The name must be 2 to 15 characters. Return the name if it is valid, otherwise, display a message indicating the input is invalid and why, then ask for their name again.
2. Create a function that will take a name (as an argument) and return the message `Hello, {name}. Welcome to the Markbook Program.`.
3. Create a function that will ask the user for an integer (keyboard input). Return the number they choose. Ensure the number is `>= 0` with input validation.
4. Create a function that will take a list of student names (as an argument), and a list of student marks. Use a loop to print out each name with their mark. If student names is `["Jeff", "Sally"]` and student marks is `[65, 87]`, the output would look like:
    ```
    Jeff 65
    Sally 87
    ```
5. Create a function that will take a list of marks (as an argument) and return the number of failing grades (`< 50`). For `[78, 50, 76, 23, 54, 33]`, the function should return `2`.

### Starter code:
```python
def main():
    pass



main()
```
