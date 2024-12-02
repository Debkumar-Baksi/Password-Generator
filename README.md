# 🔐 Password Generator

## 📜 Description

This **Password Generator** is a simple Tkinter-based graphical user interface (GUI) application written in Python. It allows the user to generate passwords of different strengths (Weak, Medium, Strong) and of customizable lengths. The generated password can be easily copied to the clipboard for use.

---

## ✨ Features

- **Customizable Password Strength**:
  - **Weak**: Generates a password with lowercase letters only.
  - **Medium**: Generates a password with lowercase letters, uppercase letters, and numbers.
  - **Strong**: Generates a password with lowercase letters, uppercase letters, numbers, and special characters.

- **Customizable Password Length**:
  - Users can choose the password length between 5 and 18 characters.

- **Clipboard Copy**:
  - Users can copy the generated password to their clipboard for easy use.

---

## 🛠️ Requirements

- Python 3.x
- Tkinter library (usually comes with Python by default)
- `pyperclip` library (for clipboard functionality)

Install `pyperclip` using pip if not already installed:

```bash
pip install pyperclip
```
## 🖥️ How to Run
- Prerequisites: Ensure Python and the required libraries are installed.
- Run the Script:
  - Save the code to a file, for example, password_generator.py.
  - Open a terminal/command prompt and navigate to the directory containing the script.
  - Run the script using the following command:
```bash
python password_generator.py
```
## 🛠️ Code Overview
Imports
- tkinter: For creating the graphical user interface.
- string: For predefined sets of characters (lowercase, uppercase, digits, and special characters).
- random: For generating random selections from the character sets.
- pyperclip: For copying the generated password to the clipboard.
Functions
- generator():

  - Generates a random password based on the selected strength and length.
  - The password is displayed in an entry field.
- copy():

  - Copies the generated password to the clipboard.
GUI Components
- Radio Buttons: To select the strength of the password (Weak, Medium, or Strong).
- Spinbox: To input the desired length of the password.
- Buttons: To trigger password generation and copying to clipboard.
- Entry: To display the generated password.

## 📂 License
This project is licensed under the MIT License.

## 👤 Author
[Debkumar Baksi](https://www.linkedin.com/in/debkumar-baksi-269738279/)
