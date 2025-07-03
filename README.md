# CryptoPhaseTwo: Cipher Analysis and Decryption Toolkit

A Java-based cryptanalysis tool for performing **frequency analysis** and **reverse Caesar cipher decryption** on given ciphertext files. This project is useful for learning classical cryptographic techniques and automating decryption of simple substitution ciphers.

---

## ✨ Features

- 🔍 Single-letter, digram, and trigram frequency analysis
- 🔄 Brute-force Caesar cipher decryption with shift detection
- 📖 Dictionary matching to identify likely decrypted words
- 🧪 Customizable dictionary and ciphertext input

---

## 🧰 Requirements

- Java 8 or higher
- A plain text file named `dictionary.txt` containing lowercase dictionary words (one per line)

---

## 🚀 Getting Started

### ✅ Step 1: Compile the program

```bash
javac CryptoPhaseTwo.java
###✅ Step 2: Prepare your files
Ensure dictionary.txt is in the same directory as the compiled .class file.

Create or obtain a ciphertext file (e.g., cipher.txt) that contains the encrypted message to analyze.

###✅ Step 3: Run the program
bash
Copy
Edit
java CryptoPhaseTwo
###✅ Step 4: Follow the prompt
When prompted, enter the name of the ciphertext file:

css
Copy
Edit
Input the filename to be opened: cipher.txt
The program will:

Perform frequency analysis (letter, digram, trigram)

Attempt reverse Caesar decryption

Match results against the dictionary

🗂️ Project Structure
bash
Copy
Edit
├── CryptoPhaseTwo.java   # Main Java program for cryptanalysis
├── dictionary.txt        # Wordlist file used for Caesar shift word matching
├── cipher.txt            # Example ciphertext file to analyze and decrypt


👨‍💻 Authors
Khalifa Alfalasi

Sufyan Alsayeh

Krunal Thumar
