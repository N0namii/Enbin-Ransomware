# Enbin-Ransomware
This project is an educational tool simulating ransomware behavior. It demonstrates encryption (AES, RSA) and system log deletion techniques. The code is intended for cybersecurity education and should not be used for attacks. It helps understand how threats work and how data protection can be implemented.
Here’s the English translation of your provided description:

---

**Main Functions:**

**File Encryption:**
- The AES algorithm is used for encrypting data.
- The RSA algorithm is used to encrypt the AES key.
- All files in the specified directory are encrypted using a randomly generated key, with the encrypted key being appended to the encrypted data.

**System Log Deletion:**
- A function is provided for deleting system logs on both Windows and Linux operating systems.
- For Windows, the `wevtutil` command is used to remove event logs.
- For Linux, commands are used to delete various system logs (e.g., `syslog`, `auth.log`, and others).

**GUI with Timer:**
- A simple graphical user interface (GUI) with a countdown timer.
- Once the timer expires, files can be deleted (though in real-world applications, this should be prevented).

**Important Notes:**
- This code is intended **for educational purposes only**!
- Do not use this code on real systems without proper permission.
- Use this project only in controlled environments, such as educational labs or for demonstrations on security and data protection.

**Instructions for Running:**
Ensure that the following libraries are installed on your system:
- cryptography
- tkinter
- subprocess
- os

You can install the required libraries using the following command:

```bash
pip install cryptography
```

To use the project, run the script:

```bash
python your_script_name.py
```

**Notes:**
- The code encrypts all files in the specified directory.
- After the encryption process is completed, a graphical interface with a timer will appear.
- The time until the operation completes can be adjusted in the functions.

---
