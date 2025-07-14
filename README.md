# Prodigy-task-1
**Caesar Cipher** is a simple encryption method where each letter in the text is shifted by a fixed number of places in the alphabet. It's used to hide messages by making them unreadable to unintended readers.

What is the Caesar Cipher?
The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted a fixed number of places down the alphabet. It’s named after Julius Caesar, who reportedly used it to protect military messages.

 How the Shift Works (with shift = 3)
In a Caesar Cipher with a shift of 3, every letter is replaced by the one 3 positions later in the alphabet. If the shift goes past 'Z', it wraps around to the beginning.
Example Shift (3 positions forward):
Plain Alphabet : A B C D E F G H I J K L M N O P Q R S T U V W X Y Z  
Cipher Alphabet: D E F G H I J K L M N O P Q R S T U V W X Y Z A B C  

~ Encrypting a Message
Let’s encrypt the message:
 "HELLO"
H → K, E → H, L → O, L → O, O → R

Encrypted Message: "KHOOR"

~Decrypting the Message
To decrypt, you reverse the shift by 3 positions.
K → H, H → E, O → L, O → L, R → O

Decrypted Message: "HELLO"

~Security of Caesar Cipher

Very easy to break: Only 25 possible shifts (excluding shift of 0).

]Vulnerable to brute-force attacks and frequency analysis.

Not suitable for real-world encryption.


