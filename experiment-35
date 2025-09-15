import re

def check_password(password):
    if len(password) < 8:
        return "Weak (too short)"
    if not re.search("[A-Z]", password):
        return "Weak (no uppercase)"
    if not re.search("[a-z]", password):
        return "Weak (no lowercase)"
    if not re.search("[0-9]", password):
        return "Weak (no digits)"
    if not re.search("[@#$%^&+=]", password):
        return "Weak (no special chars)"
    return "Strong"

pwd = input("Enter password: ")
print("Password Strength:", check_password(pwd))
