# 🔐 AES Implementation – Applied Cryptography

## 📘 Project Overview
This project demonstrates the implementation of the **Advanced Encryption Standard (AES)** algorithm as part of the *Applied Cryptography* course assignment.  
The goal of the project is to understand and implement AES encryption and decryption **without relying on external cryptographic libraries**, ensuring complete understanding of the internal mechanics.

---

## 📂 Folder Structure

```
AES Implementation Assignment - Applied Cryptography/
├── aes_withoutchanges.c                   # Original AES implementation (base version)
├── aesO.c                                 # Modified AES implementation (with improvements)
├── program/                               # Compiled program outputs or related files
├── Run time Screenshot Before Changes.png # Runtime output of original code
├── Run time Screenshot After Changes.png  # Runtime output after improvements
├── AES Applied Cryptography.pptx          # Project presentation slides
├── AES Applied Cryptography.pdf           # Project report in PDF format
├── .git/                                  # Git version control files
└── .DS_Store                              # macOS system file (can be ignored)
```

---

## ⚙️ Implementation Details

- **Language Used:** C  
- **Algorithm:** AES (Advanced Encryption Standard)
- **Encryption Type:** Symmetric Key Encryption
- **Block Size:** 128 bits  
- **Key Sizes Supported:** 128 / 192 / 256 bits  
- **Modes Supported:** Electronic Codebook (ECB) mode (basic version)

### ✳️ Modifications
- The file `aesO.c` contains optimized or modified code for performance or readability.
- The file `aes_withoutchanges.c` preserves the original logic for comparison.

---

## 🧠 Learning Objectives
- Understand the inner workings of AES rounds (SubBytes, ShiftRows, MixColumns, AddRoundKey).
- Implement key expansion logic manually.
- Compare performance and correctness of the original vs. modified implementations.
- Observe runtime behavior before and after optimization.

---

## 🧪 How to Run the Program

### 1. **Compile the Code**
Use any standard C compiler (e.g., GCC):

```bash
gcc aesO.c -o aes
```

or for the original version:
```bash
gcc aes_withoutchanges.c -o aes_original
```

### 2. **Run the Executable**
```bash
./aes
```

or
```bash
./aes_original
```

### 3. **Expected Output**
- The program encrypts and decrypts sample text.
- The console output matches the results shown in the screenshots.

---

## 🖼️ Screenshots

| Description | Screenshot |
|--------------|-------------|
| Before Optimization | ![Before Changes](Run%20time%20Screenshot%20Before%20Changes%20.png) |
| After Optimization  | ![After Changes](Run%20time%20Screenshot%20After%20Changes.png) |

---

## 🎯 Results and Observations
- The optimized version (`aesO.c`) shows improved performance and code readability.
- Encryption and decryption outputs remain consistent with the AES standard.
- The project fulfills the applied cryptography assignment requirements without external libraries.

---

## 📑 References
- NIST FIPS Publication 197: *Advanced Encryption Standard (AES)*
- Applied Cryptography Course Materials

---

## 👨‍💻 Author
**Name:** Ramnarayanan Sankar  
**Course:** Applied Cryptography  
**Project:** AES Implementation (Without External Libraries)  
**Instructor:** [Yongge Wang]

---

## 🏁 Conclusion
This project successfully demonstrates AES implementation fundamentals and key optimization principles.  
It provides a clear understanding of encryption internals — essential for deeper cryptographic system development.
