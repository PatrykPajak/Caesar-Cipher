# 🔐 Caesar Cipher

A simple yet powerful command-line tool for encrypting and decrypting text using the classic Caesar Cipher technique — written in Python.

---

## How It Works

The Caesar Cipher is one of the oldest and simplest encryption techniques in history. It works by shifting each letter in a message by a fixed number of positions along the alphabet.

For example, with a shift of **3**:

```
Plain:    A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Encoded:  D E F G H I J K L M N O P Q R S T U V W X Y Z A B C
```

So the message `HELLO` becomes `KHOOR`.

To decrypt, the process is simply reversed — each letter is shifted back by the same amount. Non-alphabetic characters (spaces, numbers, punctuation) are left unchanged.

---

## Usage

Run the script from the command line and follow the prompts:

```bash
python caesar_cipher.py
```

### Encrypting a message

```
Choose an option (encrypt/decrypt): encrypt
Enter your message: Hello, World!
Enter the shift number: 3

Encrypted message: Khoor, Zruog!
```

### Decrypting a message

```
Choose an option (encrypt/decrypt): decrypt
Enter your message: Khoor, Zruog!
Enter the shift number: 3

Decrypted message: Hello, World!
```

---

## Requirements

- Python 3.x
- No external libraries required

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/PatrykPajak/Caesar-Cipher.git
   cd caesar-cipher
   ```

2. Run the script:
   ```bash
   python caesar_cipher.py
   ```
## Author 
Patryk Pajak
