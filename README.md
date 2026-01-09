

🔐 Password Manager (Python)
A secure and user-friendly Password Manager built using Python that allows users to safely store, manage, and retrieve their passwords. The application uses encryption techniques to protect sensitive data and ensures that passwords are never stored in plain text.

🚀 Features
🔑 Secure password storage

🔐 Password encryption using hashing techniques

👤 Master password authentication

➕ Add new credentials

📋 View saved passwords

✏️ Update existing passwords

❌ Delete credentials

🖥️ Simple command-line / GUI interface

🛠️ Technologies Used
Programming Language: Python

Database: SQLite

Libraries Used:

sqlite3 – database management

hashlib – password hashing

cryptography – encryption & decryption

os – system operations

📂 Project Structure
password-manager/
│
├── main.py
├── auth.py
├── database.py
├── encryption.py
├── passwords.db
├── requirements.txt
└── README.md
⚙️ Installation & Setup
Clone the repository

git clone https://github.com/your-username/password-manager-python.git
Move into the project directory

cd password-manager-python
Install required dependencies

pip install -r requirements.txt
Run the application

python main.py
🔐 Security Implementation
Master password is stored using SHA-256 hashing

All saved passwords are encrypted before storing

Decryption is only possible after successful authentication


📈 Future Improvements
Graphical User Interface (Tkinter / PyQt)

Two-Factor Authentication (2FA)

Password strength analyzer

Cloud backup & sync

Auto password generator

🤝 Contributing
Contributions are welcome.
Please fork the repository and submit a pull request for improvements.

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Ankit Jha
MCA | Data Science & Artificial Intelligence



