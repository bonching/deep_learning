### 2. Odd or Even Checker

* **Rationale:** Understand boolean logic, comparison operators, and conditional branching (`if`, `else`), which are essential for switching player turns.
* **Requirement Details:** Ask the user to input an integer. Use an `if-else` statement and the modulo operator (`%`) to check whether the number is odd or even, then print the result.
* **Sample Input:** `4`
* **Expected Output:** `The number 4 is Even.`
* **Hint:** Wrap your `input()` call inside `int()` to convert the text input into a number (e.g., `number = int(input(...))`). Use `number % 2 == 0` to check for even numbers.
* **Edge Cases:** Entering letters or decimals instead of a whole number (triggers a `ValueError`), or entering negative numbers.
