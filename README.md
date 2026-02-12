# Bash Password Manager

A simple terminal-based **Password Manager** written in Bash. Store, search, delete, and view passwords securely with AES-256 encryption.

## Features

- **Generate strong passwords** for any service with customizable length
- **Save passwords** with a service label and username/email
- **Search passwords** by service or username
- **Delete passwords** easily by label or username
- **View all passwords** in a clean, tabular format
- **AES-256-CBC encryption** with PBKDF2 key derivation protects your passwords
- Encrypted storage file (`password_store.csv.enc`) - safe to back up

## Security

- Master password required to decrypt and view passwords
- Uses OpenSSL with AES-256-CBC and PBKDF2 for strong encryption
- Plaintext passwords never written to disk - only in memory during session
- Automatic encryption on exit and after each modification  


## 📥 Installation

1. **Download the script manually or clone the repository:**
   ```bash
   git clone https://github.com/Adhvay0505/BashPass.git
   cd BashPass/
2. **Make the file executable**
   ```bash
   chmod +x BashPass
3. **Run the script**
   ```bash
   ./BashPass
4. **Or just run using**
   ```bash
   bash BashPass
   ```

   
<img width="887" height="485" alt="Screenshot From 2025-08-01 23-58-18" src="https://github.com/user-attachments/assets/a33aef48-f40a-4c5a-b8b2-3e9814eb9a24" />
