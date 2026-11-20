# -password-strength-checker.
Password Strength Checker

A beginner Python program that checks how strong a password is and tells the user how to improve it.

Features
Prompts the user to enter a password (input is hidden)
Checks for at least 8 characters
Checks for uppercase and lowercase letters
Checks for numbers
Checks for special characters
Rates the password Weak, Medium, or Strong
Explains how to improve a weak or medium password
How to Run
Install Python 3
Download password_strength_checker.py
Run it in a terminal:
python password_strength_checker.py
Example Output
=== Password Strength Checker ===
Enter a password to check:

Requirements met: 4/5
Strength rating: Medium

How to improve your password:
  - Add at least one special character (e.g. ! @ # $ % ?).
  - Avoid names, birthdays, and common words like 'password'.
How the Rating Works
Requirements met	Rating
0 to 2	Weak
3 to 4, or all 5 but under 12 characters	Medium
All 5 and 12+ characters	Strong
What I Learned
Using conditionals and loops to validate input
Working with Python's string module and getpass
Why password length and variety matter, connecting to password policies I studied in Active Directory and Security+
Future Improvements
Check against a list of common passwords
Estimate how long a password would take to crack
Add a simple GUI
Author

Peace Bola, Cybersecurity Analyst Operations student at Penn State
