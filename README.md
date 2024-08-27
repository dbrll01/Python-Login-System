# Python-Login-System
Python Login System V1
This project is a simple command-line-based login system implemented in Python. It allows users to create an account and securely log in using a username and password.

Features:
Account Creation: Users can create an account by entering a unique username and a password. The password is hashed using the SHA-256 algorithm before being stored.
Secure Login: Users can log in by providing their username and password. The system checks if the hashed version of the entered password matches the stored hash.
Error Handling: The system provides feedback on incorrect passwords or non-existent accounts.
Getting Started
Prerequisites:
Python 3.x installed on your system.

How to Run
Clone the repository:

->bash
Copiar código:
git clone https://github.com/your-username/simple-python-login-system.git
cd simple-python-login-system

Run the script:
python3 login_system.py 

Notes:
Passwords are stored as SHA-256 hashes to enhance security. However, this is a basic implementation and should not be used in production without additional security measures.
Contributing:
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.
