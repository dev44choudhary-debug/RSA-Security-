#  RSA Digital Signature System using SHA-256

## 📖 Overview

The **RSA Digital Signature System using SHA-256** is a menu-driven cryptography project developed using **Windows Batch Scripting** and **OpenSSL**. It demonstrates the complete process of generating RSA key pairs, hashing a message using SHA-256, creating a digital signature with the private key, and verifying the signature with the public key.

The project is designed for educational purposes to help students understand the concepts of public-key cryptography, message integrity, authentication, and non-repudiation.

---

## 🎯 Objectives

* Generate RSA public and private keys.
* Create and manage text messages.
* Generate SHA-256 hashes.
* Create digital signatures using RSA.
* Verify digital signatures.
* Demonstrate message tampering detection.
* Understand the practical implementation of digital signatures.

---

## ✨ Features

* Interactive menu-driven interface
* RSA 2048-bit key generation
* SHA-256 message hashing
* Digital signature creation
* Signature verification
* Message tampering demonstration
* Public key display
* Automatic cleanup of generated files
* Windows Command Prompt compatible

---

## 🛠️ Technologies Used

* Windows Batch Script (.bat)
* OpenSSL
* RSA Algorithm
* SHA-256 Hash Algorithm
* Windows Command Prompt

---

## 📂 Project Structure

```text
RSA_Digital_Signature_Project/
│
├── project.bat           # Main menu-driven application
├── message.txt           # User message
├── private_key.pem       # RSA Private Key
├── public_key.pem        # RSA Public Key
├── message.hash          # SHA-256 Hash
├── signature.bin         # Digital Signature
└── README.md             # Project documentation
```

---

## 🚀 How to Run

### Step 1: Install OpenSSL

Download and install OpenSSL, then ensure it has been added to your system's PATH.

Verify the installation:

```cmd
openssl version
```

### Step 2: Run the Project

Open Command Prompt in the project folder and execute:

```cmd
project.bat
```

---

## 📋 Menu Options

| Option | Description                  |
| ------ | ---------------------------- |
| 1      | Generate RSA Private Key     |
| 2      | Generate RSA Public Key      |
| 3      | Create/Edit Message          |
| 4      | View Message                 |
| 5      | Generate SHA-256 Hash        |
| 6      | View SHA-256 Hash            |
| 7      | Create Digital Signature     |
| 8      | Verify Digital Signature     |
| 9      | Modify Message (Tamper Test) |
| 10     | Verify After Modification    |
| 11     | Display Public Key           |
| 12     | Delete Generated Files       |
| 13     | Exit                         |

---

## 🔄 Project Workflow

1. Create a message.
2. Generate the RSA private key.
3. Generate the RSA public key.
4. Generate the SHA-256 hash of the message.
5. Create a digital signature using the private key.
6. Verify the signature using the public key.
7. Modify the message to simulate tampering.
8. Verify again to observe signature verification failure.

---

## 🔐 Cryptographic Concepts

### RSA Key Pair

* **Private Key:** Used to create digital signatures.
* **Public Key:** Used to verify digital signatures.

### SHA-256 Hashing

SHA-256 generates a fixed-length cryptographic hash that uniquely represents the contents of a message.

### Digital Signature

The SHA-256 hash of the message is signed using the RSA private key to produce a digital signature.

### Signature Verification

The receiver verifies the signature using the RSA public key. If the message has been modified, verification fails because the newly generated hash no longer matches the signed hash.

---

## 🧪 Tamper Detection

The project includes a tamper test that demonstrates how changing even a single character in the original message causes signature verification to fail, proving the integrity protection provided by digital signatures.

---

## 📈 Learning Outcomes

After completing this project, users will understand:

* Public Key Cryptography
* RSA Key Generation
* SHA-256 Hashing
* Digital Signature Creation
* Signature Verification
* Data Integrity
* Authentication
* Non-Repudiation

---

## 📌 Future Enhancements

* Graphical User Interface (GUI)
* Support for multiple hashing algorithms
* File signing and verification
* Certificate-based digital signatures
* Cross-platform compatibility
* Automatic key management

---

## 👨‍💻 Author

**Dev Choudhary**

Bachelor of Technology (Computer Science & Engineering)

Cryptography Mini Project

---

## 📄 License

This project is intended for educational and learning purposes. You are free to use, modify, and improve it for academic or personal use.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
