
# Caesar Cipher Application

A simple GUI-based Caesar Cipher application built using Python and Tkinter. This tool allows users to encrypt and decrypt messages with a specified shift value, implementing the classic Caesar Cipher algorithm.

## Features

- **Encryption:** Enter a message and a shift value to generate an encrypted message.
- **Decryption:** Enter an encrypted message and the same shift value to retrieve the original message.
- **Intuitive GUI:** Easy-to-use interface powered by Tkinter.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ShanuNajeeb/caesar-cipher-app.git
   cd caesar-cipher-app
   ```

2. Install Python if not already installed ([Download Python](https://www.python.org/downloads/)).

3. Run the application:
   ```bash
   python app.py
   ```

4. Use the GUI:
   - Enter your message in the **"Enter Message"** field.
   - Input a numeric shift value in the **"Enter Shift Value"** field.
   - Click **Encrypt** to see the encrypted message.
   - Click **Decrypt** to retrieve the original message.

---

## Caesar Cipher Algorithm

The Caesar Cipher is a simple encryption technique where each letter in the message is shifted by a fixed number of places in the alphabet.

### Example:
- Message: `HELLO`
- Shift: `3`
- Encrypted Message: `KHOOR`

For decryption, the shift is applied in the reverse direction.

---

## Technologies Used

- **Python**: Programming language for implementing the cipher logic.
- **Tkinter**: Library for building the graphical user interface.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

