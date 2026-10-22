# Crypto — Cryptographic Hashing and Security

> **Category**: `library` | **Subcategory**: Standard Library (Security)

## Overview
Cryptographic digest routines including SHA-256, SHA-512, MD5, HMAC generation, and cryptographically secure random bytes.

## Syntax
```verscript
load Crypto
Crypto.sha256(text)
Crypto.sha512(text)
Crypto.hmac(key, data)
Crypto.randomBytes(count)
```

## Example
```verscript
load Crypto
set token : Crypto.sha256("user_token_seed")
display "Generated Token: " + token ?color=#00FFCC
```

