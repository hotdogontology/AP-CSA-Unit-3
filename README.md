
# Unit 3 - If Statements and Booleans

This project is designed for AP CS-A, focusing on Unit 3 concepts such as conditional statements, Boolean expressions, and logical operators. The project includes a set of methods that students need to implement, along with unit tests to verify their functionality.

## Project Structure

- **`Unit3.java`**: Contains method headers and task descriptions. Students are required to implement the method bodies.
- **`Unit3Test.java`**: JUnit test cases for each method in `Unit3.java`. These tests validate the correctness of the implemented methods.
- **`pom.xml`**: Maven configuration file that manages dependencies and plugins required to build and run the project.

## Prerequisites for Local Work

- Java 17 (or compatible version)
- Maven 3.x

You can also use Codespaces and the environment will load the required packages automatically upon prompt.

## Instructions

### Accept the Project

Use link found in Canvas to accept in GitHub Classroom. You may have to check your GitHub account associated email or the GitHub inbox tray to have access to the assignment.

### Clone the Repository

Open the repository in GitHub Codespaces. (Or clone to your local machine and use your preferred IDE.)

### Complete the Methods

Write the required code for the methods as described by each problem.

### Run Tests

Run the JUnit tests to verify your implementations

### Push Work to the Repository

When your code passes all tests, Commit and Sync to push your answers to the Repo for submission.

## Method Descriptions

Students need to implement the following methods in `Unit3.java`:

1. **`isPositive(int number)`**: Returns `true` if the number is positive, otherwise `false`.
2. **`isWithinRange(int number, int lower, int upper)`**: Returns `true` if the number is within the specified range (inclusive).
3. **`isLeapYear(int year)`**: Determines if a year is a leap year based on given rules.
4. **`areBothSameSign(int number1, int number2)`**: Checks if both numbers have the same sign (either positive or negative).
5. **`containsSubstring(String main, String sub)`**: Returns `true` if the main string contains the substring and both are not empty.
6. **`reversePhoneNumber(int phoneNumber)`**: Reverses the given phone number using modulo operations.

## Common Mistakes to Avoid

- Using `=` instead of `==` in conditionals.
- Ending `if` statements with a semicolon (`;`).
- Using multiple `if` statements when `if-else` would be more appropriate.
- Misunderstanding the use of logical operators (`&&`, `||`).
- Failing to apply short-circuit evaluation correctly.

## Grading
Your grade will be based on the correctness of your implementations as verified by the unit tests. Make sure all methods are completed and that all tests pass.

## Honor Code
Remember to adhere to the GSSM Academic Integrity Policy. Do not copy code from others or AI, and ensure all work is your own.

## Contact
If you have any questions or need assistance, send me an email or come to office hours. 

## Acknowledgements
This project has been adapted from the repo generously shared by [Kevin Hare](https://csplusplus.com/).
