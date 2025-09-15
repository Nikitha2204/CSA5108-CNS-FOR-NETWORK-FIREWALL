def caesar_encrypt(text, k):
    result = ""
    for ch in text:
        if ch.isalpha():
            shift = 65 if ch.isupper() else 97
            result += chr((ord(ch)-shift+k) % 26 + shift)
        else:
            result += ch
    return result

def caesar_decrypt(cipher, k):
    return caesar_encrypt(cipher, -k)

msg = input("Enter email message: ")
key = 3
enc = caesar_encrypt(msg, key)
print("Encrypted Email:", enc)
print("Decrypted Email:", caesar_decrypt(enc, key))
