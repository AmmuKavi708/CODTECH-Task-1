Name:KAVITHA S
Company:CODETECH IT SOLUTIONS
ID:CT08DS10164
Domain:Python Programming
Duration: November 15th,2024 to December 15th,2024
Mentor:NEELA SANTHOSH KUMAR

**Overview of the Project:**

**Project Title:** SIMPLE CALCULATOR
          This project is a Basic Calculator Program written in Python. The program allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division. It guides the user through input steps and provides results based on their choices. Below is an overview of the program's key components and functionality:

**Key Components:**
1.Operations Dictionary:
      The program uses a dictionary (operations) where:
      The keys are strings ('1', '2', '3', '4'), representing the four basic arithmetic operations.
      The values are tuples: the first element is a string symbol of the operation (e.g., '+', '-', '*', '/'), and the second element is a lambda function that performs the corresponding     arithmetic operation.
2.User Input:
      First and Second Numbers: The program prompts the user to input two numbers. These inputs are validated to ensure that they are valid floating-point numbers using a try and except     block. If invalid input is detected, an error message is displayed, and the function exits.
      Operation Selection: The user is asked to select an operation by entering a corresponding number (1 for addition, 2 for subtraction, etc.). This is handled via user input, which is     stored as a string.
3.Error Handling:
      The program checks if the selected operation is valid by looking for the user input in the operations dictionary. If the input is not valid, an "Invalid operation selected!"           message is shown.
      In the case of division, the program includes a safeguard to avoid division by zero, which would otherwise cause a runtime error.
4.Result Display:
      Once a valid operation is selected, the program calls the corresponding lambda function to calculate the result. The result is then printed, showing the operation and the result in     a user-friendly format.
      For division, if the second number is zero, it displays an error message ("Error! Division by zero.") instead of performing the operation.

**Flow of the Program:**
1.Introduction: The program begins by printing a welcoming message.
2.Input Handling: It asks the user for two numbers and checks if they are valid numeric inputs.
3.Operation Choice: The user is prompted to choose an arithmetic operation from the available options.
4.Calculation: Based on the selected operation, the program performs the calculation using the appropriate lambda function.
5.Result Output: The program prints the result of the operation or an error message if the operation was invalid or division by zero was attempted.

**Features:**
1.Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
2.Error Handling: Handles invalid number inputs, division by zero, and invalid operation selections.
3.User-Friendly: Easy-to-understand prompts and clear outputs.

**Improvements or Extensions:**
1.Looping for Multiple Calculations: The program could be extended to allow the user to perform multiple calculations without restarting the program.
2.More Operations: You could add more complex operations like square roots, exponentiation, or even trigonometric functions.
3.Graphical User Interface (GUI): This could be developed using libraries like Tkinter to make the program more interactive and accessible.

Overall, this program is a simple yet effective example of how to create a basic calculator using Python, incorporating user input, error handling, and dictionary-based operations for a clean, modular approach.

**Sample Input and Output:**
(ADDITION)
Welcome to the Basic Calculator!
Enter the first number: 10
Enter the second number: 5
Select an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
Enter the number corresponding to the operation: 1
10.0 + 5.0 = 15.0
