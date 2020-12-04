# Menu options with a for/while loop
The goal of this assignment is to lead you towards being able to create a menu in a program *using a for or while loop*.

Example result:
```
Please choose from one of the following options:
[1] Option one
[2] Option two
[3] Option three
[4] Option four

Enter choice: 3

You chose Option three!
```
Write a program that will:
1. loop through and print out each letter in the string "Hello, world!" one at a time. Store this value in a variable.
2. loop through and print out each letter in *any* string. Hint: use the `len()` function in your loop.
3. loop through and print out each index value of the string "Hello", the index values for this string are shown below.
    ```
    Hello
    01234
    ```
    Therefore your output should look like:
    ```
    0
    1
    2
    3
    4
    ```
4. loop through and print out each index value of *any* string.
5. loop through and print out each index value side-by-side with the character in that position. Example output for the string `Hello`:
    ```
    0 H
    1 e
    2 l
    3 l
    4 o
    ```
6. loop through a **list** (same concept as using a string) and display it's index positions side-by-side with each of the list's elements.
For example, given a list `my_list = ["Hello", "world", "how", "art", "thou?"]`, your program should output the following:
    ```
    0 Hello
    1 world
    2 how
    3 art
    4 thou?
    ```
7. create a new list containing menu options of your choice as strings (like #6). This time, loop through and create a program that displays
a menu like the following. Get the user's choice and display a message confirming the user's choice. Note how the menu starts at `1`, yet lists start at index `0`. Make it work.
    ```
    Please choose from one of the following options:
    [1] Option one
    [2] Option two
    [3] Option three
    [4] Option four

    Enter choice: 3

    You chose Option three!
