# BashPass

A secure, encrypted password manager written in pure Bash.

## Features

- AES-256-CBC encryption with PBKDF2 key derivation
- Master password protection
- Strong password generation
- Search, view, and delete passwords

## Requirements

- Bash 4.0+
- OpenSSL
- Linux/Unix

## Quick Install

**Direct (from main branch):**
```bash
curl -sL https://raw.githubusercontent.com/Adhvay0505/BashPass/main/BashPass -o /usr/local/bin/BashPass && chmod +x /usr/local/bin/BashPass && BashPass
```

**Latest release:** https://github.com/Adhvay0505/BashPass/releases/latest

## Manual Install

```bash
git clone https://github.com/Adhvay0505/BashPass.git
cd BashPass
chmod +x BashPass
./BashPass
```

## First Run

1. Run `./BashPass`
2. Create a master password
3. Start managing passwords securely

## Backup

Your vault is stored in `password_store.csv.enc` - safe to copy/back up.

## Security

Master password is never stored. Use at your own risk.
