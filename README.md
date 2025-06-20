# Key-logging-system-virtual-keyboard-
Secure GUI keypad that encrypts typed input and prevents clipboard exploits



Project Title: Secure Keyboard with Encryption
Description:
This project is a Python-based graphical user interface application that provides a secure virtual keyboard for entering sensitive information such as passwords. It uses the tkinter library for GUI components and the cryptography library's Fernet module for symmetric encryption of the user input.

The key motivation behind this project is to enhance input security by avoiding the traditional physical keyboard, which can be vulnerable to keyloggers or physical observation. Instead, it uses an on-screen keyboard with shuffled keys, preventing predictable patterns and making it more difficult for malicious software or observers to capture sensitive input.

When a user types a password or any sensitive data using the virtual keyboard, the characters are hidden visually (using asterisks), encrypted in real-time using Fernet encryption, and securely stored in memory. The application also provides a functionality to decrypt and view the last entered input securely for verification or testing purposes.

Additionally, standard clipboard operations such as copy and paste are disabled for the input field to avoid accidental exposure of typed data. The encryption key is generated at runtime, ensuring that all encryption operations are session-specific.

This project can serve as a foundational component for applications requiring secure data input, such as password managers, authentication terminals, or prototype systems for secure entry in kiosks and ATMs.

Core Techniques and Features:
On-screen virtual keyboard with randomized layout on each launch

Encrypted data storage using symmetric Fernet encryption

Real-time masking of user input

Prevention of clipboard-based attacks

GUI built with tkinter

Event-driven input and command handling

Message dialogs for feedback on encryption and decryption

Advantages:
Avoids traditional keyboard to reduce exposure to keyloggers

Ensures secure storage of sensitive input using industry-standard encryption

Makes screen-based attacks harder by using randomized keyboard layouts

Easy to understand and extend as an educational or prototype system

Written entirely in Python using standard and widely-used libraries

Use Cases:
Secure password entry applications

Educational tools to demonstrate encryption and secure input methods

Prototype for secure data entry in kiosks, ATMs, or terminals

Testing environments for UI encryption workflows

Let me know if you’d like this as a .txt or .md file, or want a one-paragraph summary version too.
