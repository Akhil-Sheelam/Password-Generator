# 🔐 Password Generator

A simple and customizable **Python Password Generator** that creates strong random passwords using a combination of uppercase letters, lowercase letters, numbers, and special characters.

This project provides a simple command-line interface where users can specify the required password length and generate multiple passwords without restarting the program.

---

## 🚀 Features

- 🔢 Custom password length
- 🔠 Uppercase letters (`A-Z`)
- 🔡 Lowercase letters (`a-z`)
- 🔢 Numbers (`0-9`)
- 🔣 Special characters
- 🎲 Random password generation
- 🔀 Character shuffling for better randomness
- 🔁 Generate multiple passwords in one session
- ✅ Password length validation
- 💻 Simple command-line interface
- 🐍 Built using Python

---

## 🛠️ Technologies Used

- Python 3
- `random` module
- `string` module

---

## 📂 Project Structure

    Password-Generator/
    │
    ├── pass_generator.py
    ├── README.md
    └── LICENSE

---

## 📋 Requirements

Before running the project, make sure Python 3.x is installed on your system.

Check your Python version:

    python --version

or:

    python3 --version

No external Python packages are required.

The project uses Python's built-in libraries.

---

## 📥 Installation

### 1. Clone the Repository

    git clone https://github.com/Akhil-Sheelam/Password-Generator.git

### 2. Navigate to the Project

    cd Password-Generator

### 3. Verify Python Installation

    python --version

---

## ▶️ How to Run

Run the Python script:

    python pass_generator.py

If your system uses `python3`, run:

    python3 pass_generator.py

The program will ask you to enter the desired password length.

---

## 🔄 How It Works

The password generator follows these steps:

    User enters password length
              ↓
    Validate the input
              ↓
    Create character pool
              ↓
    Add uppercase letters
              ↓
    Add lowercase letters
              ↓
    Add numbers
              ↓
    Add special characters
              ↓
    Randomly select characters
              ↓
    Shuffle generated characters
              ↓
    Display password
              ↓
    Ask whether to generate another password

---

## 🔍 Character Set

The generated password can contain:

### Uppercase Letters

    A B C D E ... Z

### Lowercase Letters

    a b c d e ... z

### Numbers

    0 1 2 3 4 5 6 7 8 9

### Special Characters

    ! @ # $ % ^ & * ( ) _ + ...

The combination of these character types creates passwords with a variety of characters.

---

## 💻 Example Usage

After starting the application:

    Enter the desired length of the password: 12

Example output:

    Generated Password: s*7P@q!2zE_5

The program then asks:

    Do you want to generate another password? (yes/no):

Enter:

    yes

to generate another password.

Enter:

    no

to exit the application.

---

## 🧠 Code Explanation

The main password generation process is handled by the `generate_password()` function.

### 1. Character Collection

The program creates a collection containing:

- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

### 2. User Input

The user specifies the desired password length.

The input is validated to make sure the password length is a positive number.

### 3. Random Character Selection

Characters are randomly selected from the available character pool.

### 4. Password Creation

The selected characters are added to a password list.

### 5. Shuffling

The generated characters are shuffled to increase randomness.

### 6. Final Password

The characters are combined into a single string and displayed to the user.

### 7. Repeat Generation

The user can generate another password without restarting the application.

---

## 🔐 Security Notes

This project is intended primarily as a **Python learning project and basic password generator**.

For passwords protecting important accounts, consider using a dedicated password manager or a security-focused password generator.

Do not store generated passwords in public repositories, source code, screenshots, or shared files.

---

## 🎯 Learning Objectives

This project demonstrates:

- Python functions
- User input handling
- Input validation
- Loops
- Lists
- Strings
- Random character generation
- Character shuffling
- Command-line applications
- Basic security concepts

---

## 🔮 Future Improvements

Possible improvements include:

- [ ] Add password strength indicator
- [ ] Add minimum password length
- [ ] Allow users to enable/disable character types
- [ ] Add separate options for letters, numbers, and symbols
- [ ] Add password strength scoring
- [ ] Add GUI using Tkinter
- [ ] Add password history
- [ ] Add secure password generation using Python `secrets`
- [ ] Add copy-to-clipboard functionality
- [ ] Add command-line arguments
- [ ] Add unit tests
- [ ] Add configuration options

---

## 🐛 Troubleshooting

### Python Command Not Found

If you see:

    python is not recognized as an internal or external command

Install Python 3.x and make sure Python is added to your system PATH.

---

### Invalid Password Length

If the program asks for a valid password length, enter a positive number.

Example:

    Enter the desired length of the password: 12

Avoid entering:

    -5

or:

    abc

---

### File Not Found

Make sure you are inside the project directory:

    cd Password-Generator

Then run:

    python pass_generator.py

---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `pass_generator.py` | Main Python password generator |
| `README.md` | Project documentation |
| `LICENSE` | Project license |

---

## 👨‍💻 Author

**Akhil Sheelam**

GitHub:

https://github.com/Akhil-Sheelam

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.

See the `LICENSE` file for more information.
