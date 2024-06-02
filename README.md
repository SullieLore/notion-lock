# Notion-Lock

A simple add-on for Notion that enables encryption and decryption of plain text using a password. It utilizes AES encryption directly in the browser, ensuring that no data is transmitted to any server during the process. Everything operates locally within your device's memory.

## Changelog
02/06/2024
- Removed BR translation readme.
- Adjusted README.md wording/instructions.

## Features
- **Local Encryption**: Encrypts your data locally in the browser with AES.
- **Data Recovery**: Data can only be decrypted with the correct password.
- **Multiple Passwords**: Allows for the use of different passwords for various texts.

## How to Use

### Adding to Notion
1. Embed the URL `https://sullielore.github.io/notion-lock/en` as a view in Notion.
2. Adjust the frame size as needed.

### Encrypting Text
1. Enter a password to encrypt your data.
2. Input the text you want to encrypt.
3. Select "Encrypt text" and click "Generate text".
4. Copy the encrypted data from the result or use "Copy to Clipboard".
5. Store the encrypted text in Notion.

### Decrypting Text
1. Enter the password used for encryption.
2. Paste the encrypted text into the field.
3. Select "Decrypt" and click "Generate Text".
4. Access your decrypted data.

## Forking the Project
To ensure continued access to this tool, you can fork this repository to your GitHub account and set up GitHub Pages on your forked project. This way, you're not dependent on the original repository's availability.

The entire script is contained within a single `index.html` file, so it can also be hosted independently of GitHub Pages if you have a hosting service.

**Disclaimer**: The add-on runs entirely in your browser's memory using AES encryption. There is no way to recover encrypted data if you lose your password.

Project forked from Marcello09/notion-lock.
