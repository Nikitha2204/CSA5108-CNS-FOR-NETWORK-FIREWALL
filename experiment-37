import random
import string

def generate_captcha(length=5):
    letters = string.ascii_uppercase + string.digits
    return ''.join(random.choice(letters) for _ in range(length))

captcha = generate_captcha()
print("CAPTCHA:", captcha)

user = input("Enter CAPTCHA: ")
if user == captcha:
    print("Verified")
else:
    print("Failed")
