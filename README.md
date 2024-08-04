# mini-ciphertext-project
# Title: Message Encode-Decode - Secure Your Information by Encryption.

This project allows users to securely encode and decode messages using a common key. Built with Python, and Tkinter for the GUI, it provides a straightforward method to transform messages into an unrecognizable form and back to their original state.

This project is a simple yet effective way to encode and decode messages using a common key. Built using Python, Tkinter for the GUI, and the base64 library, it allows users to transform their text into an unrecognizable form and then back to its original state using the same key.

# Features:
Encode messages into ciphertext.
Decode ciphertext back to the original message.
Simple GUI interface using Tkinter.
Secure encoding using a key.

# Project Structure:
The project consists of the following components:
Import module: 
Import necessary libraries.
Create display window: 
Initialize and configure the Tkinter window.
Define functions: 
Encode, decode, mode selection, exit, and reset functions.
Define labels and buttons:
GUI elements for user interaction.

# Prerequisites:
To run this project, you need to have Python installed along with the Tkinter and base64 libraries. You can install Tkinter and base64 using pip:

pip install tk
pip install base64

# Installation:

Clone the repository:
git clone https://github.com/your-username/message-encode-decode.git
cd message-encode-decode

Install the required libraries:
pip install tk
pip install base64

# Usage:
Run the script using Python:

python message_encode_decode.py
The GUI window will open, allowing you to enter the message, key, and mode (encode or decode).

# Encode a Message:
Enter the message you want to encode.
Enter the key.
Select the mode as e.
Click the RESULT button to see the encoded message.

# Decode a Message:
Enter the encoded message.
Enter the key.
Select the mode as d.
Click the RESULT button to see the original message.

# Example:
Here’s an example of how to encode and decode a message:

Encoding:
Message: Hello World
Key: key123
Mode: e
Result: Encoded message here

Decoding:
Encoded Message: Encoded message here
Key: key123
Mode: d
Result: Hello World

# Creating an Executable:
To create an executable file from the Python script, use PyInstaller:

Install PyInstaller:
pip install pyinstaller

Create the executable:
pyinstaller --onefile message_encode_decode.py

The executable will be created in the dist directory.

# Contributing:
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
