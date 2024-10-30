# Caesar-Cipher-code
This  code is called a Caesar Cipher, named after Julius Caesar, who reportedly used it to keep his messages secret.
Alright, imagine you have a message written in plain English, like “HELLO.” Now, suppose you don’t want just anyone to understand it, so you decide to create a secret code. You could do this by shifting each letter forward in the alphabet by a certain number of places. Let’s say you pick 3 as your shift number, meaning each letter in your message will be shifted forward by three positions.

So, starting with “HELLO”:

H becomes K
E becomes H
L becomes O
O becomes R
After shifting each letter, “HELLO” turns into “KHOOR.” Now, only people who know the shift number (3 in this case) can understand your coded message. They just need to shift each letter back by three positions to reveal the original word, HELLO.

This project is about creating a small computer program that can do this shifting automatically for any message. It lets users type in a message, choose a shift number, and the program will transform the message using this shift, either to create a secret code (encryption) or to change it back to the original message (decryption).

This project involves creating a program that encrypts and decrypts text using the Caesar Cipher, a classical encryption method. The Caesar Cipher is a simple substitution cipher where each letter in a text is shifted a specific number of positions in the alphabet. The main purpose of the project is to create functions that allow users to:

1. Encrypt and Decrypt Text:  
   - By shifting each letter of a given message by a specified number of positions.
   - The program should support both **uppercase and lowercase** letters, and output should always be in uppercase.

2. User Interaction:  
   - Prompt users to choose between encryption and decryption modes.
   - Validate inputs, ensuring that users select valid options (e.g., correct mode, shift number).
   - Allow users to input their message via the console or read it from a file.

3. File Input/Output:  
   - Process multiple messages from a file, encrypting or decrypting each one based on user input.
   - Save results to a new file.

4. Loop for Repeated Actions:  
   - Users should be able to encrypt/decrypt multiple messages without restarting the program.

5. Structure and Documentation:  
   - The project requires adherence to Python’s PEP8 style guide for clean, readable code and uses Pylint for code analysis.

The program includes helper functions to handle file verification, mode selection, file writing, and ensuring that users provide the necessary information correctly. Overall, the project simulates a text-based encryption application, demonstrating foundational programming concepts such as loops, functions, file handling, input validation, and basic encryption.
