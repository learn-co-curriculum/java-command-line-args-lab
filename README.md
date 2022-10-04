# Command-Line Arguments Lab

## Learning Goals

- Practice passing arguments in via the command-line.

## Instructions

Given the `GroceryListDriver` class again, modify the program to take in the
file as a command-line argument instead of prompting the user for the file path.

Reuse the last lab to implement the read and write methods and then make sure
that everything passes the unit tests again.

To implement the reading of command-line arguments, consider the following
instructions and tips:

- Modify the `GroceryListDriver` class.
  - Replace the `Scanner` object that is prompting the user for the file path
    with getting the file path via the command-line.
  - Refer to the Command-Line Arguments lesson as needed.
- When running the `GroceryListDriver` class, pass in a file named
  `grocery-list.txt`.
- Make sure the unit tests all still pass successfully.

## Example Output

Consider the example output if no file is passed in via the command-line:

```text
Please specify one file path as a command-line argument.
```

Consider the example output if we do pass in the file as a command-line
argument:

```text
Apples
Bananas
Cookies

```

## Stretch

Along with passing the file path into the program via the command-line, also
pass it the contents of the grocery list. If we were to implement this and then
execute the Java program via the command-line, the command would look like this:

```text
java GroceryListDriver grocery-list.txt Apples Bananas Cookies
```
