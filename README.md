# Banking Program in Python

This is a simple command-line banking program written in Python that allows users to check their balance, deposit money, withdraw money, and exit the program. It demonstrates basic programming concepts such as functions, conditionals, and loops.

## Features

- **Show Balance**: Displays the current balance of the user.
- **Deposit**: Allows the user to deposit a specified amount. Validates that the amount is non-negative.
- **Withdraw**: Allows the user to withdraw a specified amount. Validates that there are sufficient funds and that the amount is greater than zero.
- **Exit**: Exits the program gracefully.

## How to Run

1. Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).
   
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/banking-program.git
   ```

3. Navigate to the project directory:
   ```bash
   cd banking-program
   ```

4. Run the program:
   ```bash
   python banking_program.py
   ```

## Usage

1. Upon running the program, you will see a menu with options:
   - **1**: Show Balance
   - **2**: Deposit
   - **3**: Withdraw
   - **4**: Exit

2. Enter the corresponding number to perform the desired action.

3. Follow the prompts to enter amounts for deposits and withdrawals.

4. The program will continue to run until you choose to exit.

## Code Structure

- `show_balance(balance)`: Function to display the current balance.
- `deposit()`: Function to handle deposits and validate input.
- `withdraw(balance)`: Function to handle withdrawals and validate input.
- `main()`: The main function that runs the program loop.

## Contributing

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue in the GitHub repository.


## Acknowledgments

- This program is a basic exercise in Python and is intended for educational purposes.
