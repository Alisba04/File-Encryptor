# File-Encryptor
Advanced file encryption tool with batch processing and compression

#Advanced File Encryptor
A powerful, browser-based file encryption tool with military-grade security, batch processing, and built-in compression. Encrypt and decrypt files directly in your browser with zero server uploads.

#Features
- Military-Grade Encryption - AES-256-GCM with PBKDF2 key derivation (100,000+ iterations)
- Batch Processing - Encrypt/decrypt multiple files simultaneously
- Smart Compression - Built-in GZIP compression reduces file sizes by 20-80%
- Performance Statistics - Real-time processing time and compression ratio tracking
- Secure Password Generator - Cryptographically secure random password generation
- Metadata Preservation - Original filename, size, and timestamp stored in encrypted files
- Zero Knowledge - 100% client-side processing, no data leaves your device
- Cross-Platform - Works on desktop, mobile, and tablets
- Modern UI - Beautiful, intuitive interface with dark mode
- No Installation - Runs directly in your browser

HOW TO RUN:-

#Run Locally
-Download the index.html file
-Double-click to open in any modern browser
-Done! Works completely offline.
#Clone Repository
git clone https://github.com/Alisba04/File-Encryptor.git
cd File-Encryptor
# Open index.html in your browser

📖 How to Use
Encrypting Files

Select Mode: Click the "Encrypt" button (default mode)
Choose Files: Click "Select Files" or drag & drop files into the upload area
Set Password:

Enter a strong password manually, OR
Click "Generate Secure Password" for a random 20-character password
⚠️ SAVE THIS PASSWORD! Without it, files are permanently unrecoverable


Configure Settings (Optional):

Choose encryption method: AES-256-GCM (recommended) or AES-128-GCM
Enable/disable compression (enabled by default)


Encrypt: Click the "Encrypt X File(s)" button
Download: Click download button for each encrypted file (.encrypted extension)

Decrypting Files

Select Mode: Click the "Decrypt" button
Choose Files: Select your .encrypted files
Enter Password: Type the EXACT same password used for encryption
Decrypt: Click the "Decrypt X File(s)" button
Download: Get your original files back with their original names

🔐 Security Features
Encryption Specifications

- Algorithm: AES-GCM (Galois/Counter Mode)
- Key Sizes: 256-bit (default) or 128-bit
- Key Derivation: PBKDF2 with SHA-256
- Iterations: 100,000 (AES-256) or 210,000 (AES-128)
- Salt: 16 bytes (randomly generated per file)
- IV (Initialization Vector): 12 bytes (randomly generated per file)
- Authentication: Built-in authenticated encryption with GCM mode

What Makes This Secure?
✅ Industry Standard Encryption - Same algorithms used by governments and militaries
✅ Random Salt & IV - Each encryption is unique, even with the same password
✅ High Iteration Count - Makes brute-force attacks computationally infeasible
✅ Authenticated Encryption - Detects any tampering with encrypted files
✅ Client-Side Only - Files never uploaded to any server
✅ No Telemetry - Zero tracking, analytics, or data collection

⚠️ **Password Security**
🔴 Lose your password = **data gone forever**  
- No recovery, no backdoors, no brute-force  
- Use a password manager  

✅ **DO:**  
- Strong, unique (12+ chars)  
- Save in manager  
- Test decryption right away  
- Use AES-256-GCM  
- Compress large files  

❌ **DON’T:**  
- Use weak/common passwords  
- Share insecurely  
- Delete originals before testing  
- Forget to store password safely  


🐛 Troubleshooting
"Decryption failed: Wrong password or corrupted file"
Causes:
Incorrect password (most common)
File was modified/corrupted after encryption
File was not fully encrypted

Solutions:
Double-check password (try copying from where you saved it)
Ensure file extension is .encrypted
Try re-encrypting original file

Browser Shows "Out of Memory"
Causes:
File too large for browser memory
Multiple large files processed simultaneously

Solutions:
Process files one at a time
Use smaller files (<100MB)
Close other browser tabs
Restart browser

Files Won't Upload
Causes:
Browser security restrictions
File locked by another program

Solutions:
Refresh the page
Try different browser
Ensure file isn't open in another program

📄 License
-MIT License - Free to use, modify, and distribute.
🤝 Contributing
Contributions welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

 
 ⭐ Star this repo if you find it useful!
