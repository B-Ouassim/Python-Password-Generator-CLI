# 🔑 Command Line Password Generator (Python)

A straightforward utility to generate strong, random passwords directly from the command line. This project showcases **Python functions**, basic control flow, and the effective use of the built-in `random.choice` function for secure string generation.

## ✨ Features
* **Custom Length:** Easily specify the desired length of the password.
* **Character Set:** Generates passwords using a comprehensive set of characters: uppercase letters, lowercase letters, numbers, and common symbols (`?!,.$%_-&`).
* **Command Line Interface (CLI):** Easy to run and use in any terminal environment.

## 💻 Technology Used
* **Python 3:** Core language used for the generation logic.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Python-Password-Generator-CLI.git](https://github.com/YourUsername/Python-Password-Generator-CLI.git)
    ```
2.  **Run the script:** Open your terminal or command prompt, navigate to the project directory, and execute the file.
    ```bash
    python test.py
    ```
    *Note: The current script calls the function with a default length of 8.*

## ⚙️ How to Customize
The main function is `createpass(data)`. To generate a password of a different length, simply change the argument when calling the function in your file:

```python
# To generate a 12-character password:
print(createpass(12))

# To generate a 20-character password:
print(createpass(20))
