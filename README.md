# Description:
> The project involves the development of a Python application focusing on email and password validation, alongside storing user data in a JSON file format, including a one-time password (OTP) in a dictionary structure.

# Key Components:

- > Importing necessary libraries for functionality.
- > Initialization of an empty dictionary to manage user details such as email, password, and OTP.
- > Implementation of various functions and methods catering to distinct operations.
- > Adaptation of these functions to acquire user input and persist the data in JSON format through file handling, facilitating retrieval as needed.

# Procedure:
- > Prompting the user for login credentials.
- > Continuation to password and OTP verification upon successful user data matching.
- > Providing an option for users to create a new account if no matching data is found.
- > During the signup process, ensuring the correct format of email and password according to predefined criteria.
- **Email Conditions:**
- Validating domain existence.
- Enforcing a single '@' symbol usage.
- Restricting special characters.
- Prohibiting emails starting with a digit.
- **Password Conditions:**
 -  Enforcing a length requirement between 8 to 16 characters.
 -  Requiring at least one uppercase letter.
 -  Mandating at least one lowercase letter.
 -  Ensuring the presence of at least one digit.
-  Requiring at least one special character.
- > Post-signup, offering the user the option to proceed with login.
- > Validating OTP and password authenticity during the login process.





