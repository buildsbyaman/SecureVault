# 🔐 SecureVault

**Live Demo**: [https://buildsbyaman-securevault.vercel.app/](https://buildsbyaman-securevault.vercel.app/)

A browser-based file encryption and decryption tool using AES-GCM encryption. All operations happen locally in your browser—your files never leave your device.

---

## ✨ Features

- **Encrypt any file** — Upload and secure files with a passphrase
- **Decrypt files** — Restore encrypted files with the correct key
- **Client-side only** — No server uploads, complete privacy
- **AES-GCM encryption** — Industry-standard 256-bit encryption
- **Dark/Light theme** — Toggle between visual modes

---

## 🔐 How It Works

### Encryption

1. Upload a file
2. Enter a passphrase
3. Download the encrypted file (with `_Encrypted` suffix)

### Decryption

1. Upload an encrypted file
2. Enter the same passphrase
3. Download the original file (with `_Decrypted` suffix)

> **Note**: Decryption only works with the correct passphrase.
