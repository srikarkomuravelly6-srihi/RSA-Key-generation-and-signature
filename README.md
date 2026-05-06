1. Key Generation
Generate a 2048-bit RSA key pair
Private key is used for signing
Public key is used for verification

2. Message Preparation
Input message is converted into UTF-8 bytes
Supports text, symbols, and Unicode characters

Signing Process
SHA-512 hash is applied to the message
RSA-PSS padding is used for secure signing
Private key generates the digital signature

4. Signature Encoding
Signature is encoded using Base64
Makes it readable and transferable over text-based systems

5. Verification Process
Message is hashed again using SHA-512
Public key verifies the signature against the message
Any change in message results in verification failure
