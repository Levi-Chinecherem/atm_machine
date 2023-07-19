
# ATM MACHINE CODE

![Sample Output](https://github.com/Levi-Chinecherem/atm_machine/blob/master/sample.PNG)

**Description:**
This code is for a simple ATM (Automated Teller Machine) system. It allows users to log in with their usernames and PINs and perform various operations such as checking their account balance, withdrawing money, depositing money, and changing their PIN.

## How to Use

1. **Login**
   - The code will display a welcome message and prompt you to enter your username.
   - Enter your username (your name) and press Enter.

2. **Enter PIN**
   - Next, you will be asked to enter your 4-digit PIN (Personal Identification Number).
   - Type the PIN and press Enter.

3. **Main Menu**
   - If your PIN is correct, you will be logged in and presented with the main menu options.
   - The options are: 
       - **S**: Check your account statement (balance)
       - **W**: Withdraw money
       - **D**: Deposit money
       - **P**: Change your PIN
       - **Q**: Quit and exit the ATM

4. **Perform Operations**
   - To select an option, type the corresponding letter and press Enter.
   - Depending on the option you choose, follow the on-screen instructions.

5. **Exiting**
   - To quit the ATM, choose the option **Q** from the main menu.

## Sample Users and PINs

- User 1:
  - Username: precious
  - PIN: 1234
  - Account Balance: ₦10,000

- User 2:
  - Username: levi
  - PIN: 2222
  - Account Balance: ₦20,000

- User 3:
  - Username: user3
  - PIN: 3333
  - Account Balance: ₦30,000

## Important Notes

- If you enter an incorrect username, the ATM will prompt you to try again.
- You have a maximum of three attempts to enter the correct PIN.
- If you fail to enter the correct PIN within three attempts, the ATM will lock your card, and you won't be able to proceed.
- The ATM only dispenses money in ₦10 denominations (i.e., ₦10, ₦20, ₦30, ...).
- Deposits and withdrawals must be made using multiples of ₦10 (e.g., ₦10, ₦20, ₦30, ...).
- The ATM system is case insensitive, so you can type responses in uppercase or lowercase.

## Sample Run

```
****************************************************************************
*                                                                          *
*                         Welcome to my ATM MACHINE                           *
*                                                                          *
****************************************************************************

ENTER USER NAME: precious

PLEASE ENTER PIN: 1234

LOGIN SUCCESFUL, CONTINUE

Precious, welcome to:
----------ATM SYSTEM-----------
-------------------------------
*******************************
SELECT FROM FOLLOWING OPTIONS:
Statement__(S)
Withdraw___(W)
Deposit__(D)
Change PIN_(P)
Quit_______(Q)
Type The Letter Of Your Choices: s
*******************************
-------------------------------

Precious, YOU HAVE ₦10,000 ON YOUR ACCOUNT.
```

Note: This is a simple demonstration code and should not be used for real-world applications. It lacks proper security measures and validation checks for a genuine ATM system.

# FEEDBACK
Any suggestion and feedback is welcome. You can message me on Instagram
- https://www.instagram.com/itz_me_sooriii?r=nametag
