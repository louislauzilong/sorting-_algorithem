@@ -1,31 +1,31 @@
# Caesar_cipher
A classic Caesar cipher implementation in Python. Shifts each letter by a fixed number, preserving case and non‑alphabetic characters. Use a positive shift to encrypt, negative to decrypt.
## 🔐 How It Works
## How It Works
- For each character:
  - If it’s a letter, find the base (`A` or `a`) and shift by the given amount, modulo 26.
  - If it’s not a letter (space, punctuation, etc.), leave it unchanged.
- Encrypt with a positive shift, decrypt using the negative of the same shift.

## 🚀 Usage
## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/caesar-cipher.git
   cd caesar-cipher
   ```
 2. Run the script:
```bash
python caesar_cipher.py
```
## Example
```
python
encrypted = enc("Hello World!", 3)
print("Encrypted:", encrypted)   # Khoor Zruog!

decrypted = enc(encrypted, -3)
print("Decrypted:", decrypted)   # Hello World!
```
## licence 
this is published under the mit licence 
[licence](https://mit-license.org/)
## have fun
