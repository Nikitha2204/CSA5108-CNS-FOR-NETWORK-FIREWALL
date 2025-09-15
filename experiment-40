def encode_message(image, message):
    return image + "[HIDDEN]" + message

def decode_message(encoded):
    if "[HIDDEN]" in encoded:
        return encoded.split("[HIDDEN]")[1]
    return ""

img = "fake_image_data"
msg = input("Enter secret message: ")

encoded = encode_message(img, msg)
print("Encoded Image Data:", encoded)
print("Decoded Message:", decode_message(encoded))
