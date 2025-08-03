# Brute-force-password-cracker-python
Python script that demonstrates brute force password cracking for educational and cybersecurity awareness purposes.

# 🔐 Python Brute Force Password Cracker Lab

## 📌 Project Overview  
This project demonstrates how to build a Password Cracker using brute force techniques in Python. It is designed for **educational purposes only**, to better understand the logic behind brute force attacks and why securing passwords is critical in cybersecurity.

## 🛠️ Tools & Libraries Used  
- **Python Standard Library**  
- `string` – to generate a list of printable characters  
- `random` – to generate combinations of characters  
- `input()` – to take user input  

## 📚 What I Learned
- Basics of brute force logic and password cracking  
- Working with `string.printable` for character sets  
- Using loops and conditional logic (`while`, `if`)  
- Joining lists into strings using `"".join()`  
- Ethical considerations of offensive security tools  

## ⚠️ Security & Ethical Context
This lab was created only for educational use. Brute force tools must never be used without explicit permission from system owners. This is to understand how attackers might attempt to break passwords, so we can build stronger defenses.

## 🧪 Step-by-Step Lab Breakdown
### 1️⃣ Take Input from the User  
We start by letting the user enter the target password.

```python
password = input("Enter The Password: ")
