# SecureMe 🔐

SecureMe is a privacy-first encrypted vault for storing sensitive credentials securely on Android.

The idea came from a personal frustration.

I had almost 10 Gmail accounts for different purposes like testing, registrations, projects, and backups. Over time I realized that I had forgotten passwords for several of them.

Every time I needed access, I had to go through the entire **Forgot Password process** again.

Verification emails. Recovery codes. Security questions.

It became frustrating.

Storing passwords in a notes app didn't feel safe either.

Notes apps are not designed to store sensitive information like passwords, bank details or crypto keys.

That is when the idea of **SecureMe** was born.

SecureMe is a secure vault application where sensitive information can be stored safely and accessed quickly when needed.

All data is stored **locally on the device and encrypted**.

---

## Features

• AES encrypted vault storage  
• Biometric authentication (fingerprint / device security)  
• Secure recovery key system  
• Screenshot protection  
• Storage for passwords, bank details, crypto wallets and cards  
• Custom secure fields  
• Offline-first design (no cloud storage)

Your data **never leaves your device**.

---

## Tech Stack

Kotlin  
Jetpack Compose  
Room Database  
SQLCipher encrypted database  
AES encryption  
Android Biometric API  
MVVM architecture

---

## Screenshots

| Lock Screen | Dashboard |
|-------------|-----------|
| ![](screenshots/lock_screen.png) | ![](screenshots/dashboard.png) |

| Add Entry | Vault Details |
|-----------|---------------|
| ![](screenshots/add_entry.png) | ![](screenshots/vault_details.png) |

---

## Security Architecture

SecureMe follows a layered security model.

1. AES encryption protects vault data.
2. SQLCipher encrypted database stores encrypted payloads.
3. Biometric authentication prevents unauthorized access.
4. Recovery key system enables account recovery.
5. Screenshot protection prevents screen capture of sensitive data.

All encryption operations happen **locally on the device**.

---

## Architecture

SecureMe follows MVVM architecture.

UI (Jetpack Compose)  
↓  
ViewModel  
↓  
Repository  
↓  
Encrypted Database (SQLCipher)

---

## Why This Project

SecureMe started as a personal problem but evolved into a project focused on security and privacy.

Through building this project I explored:

• Secure data storage on Android  
• Encryption and cryptography concepts  
• Biometric authentication  
• Designing security-focused user experiences

---

## Author

Aman Joshi

LinkedIn  
https://www.linkedin.com/in/YOUR_LINKEDIN_PROFILE

---

## License

This project is licensed under the MIT License.
