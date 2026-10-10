# 🔒 Encryption, Hashing & Encoding

Encryption, hashing, and encoding transform data for different purposes. Encryption protects confidentiality, hashing helps verify integrity, and encoding changes data representation.

## Examples

```text
Encryption → Plaintext → Ciphertext → Decryption
Hashing    → Data → Fixed-length digest
Encoding   → Data → Different representation
```

Common examples:

- Encryption → AES, RSA
- Hashing → SHA-256
- Encoding → Base64

## Characteristics

- **Encryption** → Uses a key to protect data confidentiality; authorized decryption restores the plaintext
- **Hashing** → Produces a digest used for integrity checks and other security purposes
- **Encoding** → Changes data representation; it does not provide security by itself
- Passwords should be stored using dedicated password-hashing algorithms such as Argon2id, bcrypt, or scrypt—not plain SHA-256
- Digital signatures can help verify authenticity and integrity

## Key Takeaway

**Encryption → Confidentiality.**  
**Hashing → Integrity verification.**  
**Encoding → Data representation.**