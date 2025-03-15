# ATM System

Welcome to the ATM System project. This project simulates an ATM system where users can interact with their accounts, perform transactions, and manage account information. It is a Python-based application using a simple console interface.

## Features

1. **Withdrawal**: Allows users to withdraw money from their account (if sufficient balance is available).
2. **Deposit**: Users can deposit money into their accounts.
3. **Pin Generation**: Users can generate a new PIN for their account if not already set.
4. **Mini Statement**: Displays basic account information like name, account number, date of birth, and balance.
5. **Reset Pin**: Allows users to reset their PIN using their date of birth as a verification method.

## Requirements

- Python 3.x
- No external libraries or dependencies are required.

## How to Run

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/atm-system.git
    ```

2. Navigate into the project directory:
    ```bash
    cd atm-system
    ```

3. Run the Python script:
    ```bash
    python atm_system.py
    ```

4. Follow the on-screen prompts to interact with the system.

## Account Information

The following sample accounts are preloaded into the system:

| Account No | Name    | Date of Birth | Balance | Pin   |
|------------|---------|---------------|---------|-------|
| 2345       | Dhanush | 12-07-2001    | 10000   | 8591  |
| 8897       | Veeresh | 11-04-2002    | 20000   | 5431  |
| 7609       | Amar    | 16-03-2003    | 5000    | None  |
| 5213       | Kumar   | 13-08-2002    | 15000   | 6490  |

## How to Use

1. **Withdrawal**: Select the withdrawal option, enter your account number, PIN, and the amount to withdraw. The system will ensure that sufficient funds are available before completing the transaction.
   
2. **Deposit**: Select the deposit option, enter your account number, and the amount to deposit.

3. **Pin Generation**: If you don't have a PIN, select this option to create a new one. You'll need to provide your account number and confirm the new PIN.

4. **Mini Statement**: Select this option to view basic details about your account, including your balance.

5. **Reset Pin**: You can reset your PIN by entering your date of birth. After confirmation, a new PIN can be set.

6. **Exit**: To exit the ATM system, select the "Exit" option.

## License

This project is open-source and available under the MIT License.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request.

## Acknowledgements

This project was developed as a part of a learning exercise in creating an ATM system with basic features like account management and transactions.

