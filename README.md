
# Password Sentinel

Password Sentinel is a command-line password strength analyzer that evaluates your password using real-world techniques. It estimates how long it would take to brute-force your password, checks it against common wordlists, and provides actionable suggestions to improve your password security.


## Features

- Brute Force Attack Time Estimation

- Wordlist Test

- Character Variety Analysis

- Repeated Character Detection

- Actionable Suggestions


## Run Locally

Clone the project

```bash
  git clone https://github.com/jnikhil16/PasswordSentinel.git
```

Go to the project directory

```bash
  cd PasswordSentinel
```

Run the program

```bash
  python3 src/main.py
```


## Usage/Examples

```text
$ python3 main.py

Welcome to Password Sentinel! Enter a password to check its strength.

Enter the password to continue: abcd1234
Found: abcd1234                                                         

Summary:
Length is okay, but you might want to increase it for better security.
Lacks variety in characters. Try including more uppercase letters symbols.
Good character position. No repeated patterns found.
Present in a list of commonly used passwords. Consider using a more unique password.
Password is moderate and can be cracked in a few hours. Consider strengthening it.

Thank you for using Password Sentinel!

```


## Tech Stack

**Language:** Python 3

**Libraries:**

- `string` – for character set operations

- `os` – for file and path handling

- `time` – for timing and estimation

- `sys` – for system-specific functions

**Dev Tools:**

- VS Code

- Git & GitHub for version control