# Banking Management System

This is a console-based banking program that allows users to simulate two roles: **Banker** and **Customer**. The program operates with different functionalities based on the selected role and requires valid credentials for access.

## Getting Started

To get started with the program, follow these steps:

1. Clone this repository to your local machine.

2. Compile the Java source code using a Java compiler.

3. Run the compiled program.

4. The program will start and prompt you to choose a role: **Banker** or **Customer**.

## Banker Role

If you choose the **Banker** role, you will be prompted to enter admin credentials:

- Admin ID
- Admin Password

Upon successful authentication, you will have access to the following functionalities:

### Banker Functionalities

- **Create Bank Account:** Create a new bank account for a customer with the following details:
  - Account Type
  - Name
  - Gender
  - Nationality
  - Account Number
  - PIN
  - KYC Document (e.g., Passport, Driving License)
  - Date of Account Creation
  - Date of Birth (DOB)
  - Mobile Number
  - Initial Account Balance

- **Display Account Summary:** View the summary of a customer's bank account, including details such as account type, name, gender, nationality, account number, PIN, KYC documents, date of account creation, DOB, mobile number, and current account balance.

- **Close Bank Account:** Close an existing bank account.

- **Create Admin Account:** Create a new admin account.

- **Delete Admin Account:** Delete an existing admin account.

- **Return to Main Menu:** Go back to the main menu to switch roles or exit the program.

## Customer Role

If you choose the **Customer** role, you will be prompted to enter your customer account number and PIN:

- Account Number
- PIN

Upon successful authentication, you will have access to the following functionalities:

### Customer Functionalities

- **Deposit Money:** Add funds to your bank account.

- **Withdraw Money:** Withdraw funds from your bank account (if available).

- **Change PIN:** Change your account's PIN.

- **Show Account Balance:** View your account balance.

- **Return to Main Menu:** Go back to the main menu to switch roles or exit the program.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the Java programming language for making this console-based banking program possible.
