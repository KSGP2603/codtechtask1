NAME: Guru Prasad K S
Company: codtech it solutions
ID: CT08DS1981
Domain: Cyber Security & Ethical hacking
Duration: June to July 2024
Mentor: G.Sravani

Overview
This C++ program is a simple password strength checker. It evaluates the strength of a given password based on its length and the presence of various character types (lowercase, uppercase, digits, and special characters). The strength is classified as "Weak", "Moderate", "Strong", or "Very Strong".

Key Activities
Contains Check Functions:

containsLowercase(const string&): Checks if the password contains at least one lowercase letter.
containsUppercase(const string&): Checks if the password contains at least one uppercase letter.
containsDigit(const string&): Checks if the password contains at least one digit.
containsSpecialChar(const string&): Checks if the password contains at least one special character.
Password Strength Evaluation:

evaluatePasswordStrength(const string&): Evaluates the password based on length and the presence of different character types. It assigns a score and classifies the strength as "Weak", "Moderate", "Strong", or "Very Strong".
User Input and Output:

The main() function prompts the user to enter a password, calls evaluatePasswordStrength(), and prints the strength of the entered password.
