# Bank-App
This Python code uses Tkinter to create a simple bank application GUI. Users can deposit, withdraw, and check balance. It's a basic example with input validation.

This Python code creates a basic bank application with a graphical user interface (GUI) using the Tkinter library. Here's how it operates:

1. **Imports**: The code imports the `tkinter` library and the `messagebox` module for creating GUI elements and displaying messages.

2. **Class Definition**: It defines a class `BankApp`, which encapsulates all the functionalities of the bank application.

3. **Initialization**: The `__init__` method initializes the GUI window (`master`), sets its title, and initializes the balance to zero.

4. **GUI Elements**: Inside the initialization method, various GUI elements are created, such as labels, entry fields, and buttons. These include:
   - Labels for displaying balance and prompting for an amount.
   - Entry fields for users to input amounts.
   - Buttons for depositing, withdrawing, checking balance, and exiting.

5. **Deposit Method**: The `deposit` method is called when the user clicks the "Deposit" button. It retrieves the amount entered by the user, validates it, and adds it to the balance if valid. If the amount is not a positive number, or if it's not a valid number at all, an error message is displayed.

6. **Withdraw Method**: Similar to the deposit method, the `withdraw` method is called when the user clicks the "Withdraw" button. It validates the withdrawal amount and deducts it from the balance if it's within the available balance and a positive number.

7. **Check Balance Method**: The `check_balance` method displays a message box showing the current balance when the user clicks the "Check Balance" button.

8. **Update Balance Label Method**: This method updates the balance label to display the current balance after each deposit or withdrawal.

9. **Main Function**: The `main` function creates an instance of the `BankApp` class and starts the GUI main loop.

10. **Execution**: Finally, the code checks if it's being run directly and calls the `main` function to start the application.

This bank application provides basic functionalities like depositing, withdrawing, and checking balance, with input validation to ensure data integrity and user-friendly error handling through message boxes.
