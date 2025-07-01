# Cve
Cve
# CVE-2025-27363 FreeType Exploit (Educational Proof-of-Concept)

This repository contains an educational proof-of-concept (PoC) for **CVE‑2025‑27363**, a vulnerability in the FreeType font rendering engine that may lead to remote code execution via crafted font files.

## Files
- `final.woff2`: The malicious font file containing injected shellcode
- `exploit.html`: HTML that loads the font to trigger FreeType rendering
- `inject_shellcode.py`: Script to inject shellcode into font XML
- `README.md`: You’re reading it :)

## ⚠️ Disclaimer

> This code is for **educational and authorized testing purposes only.**  
> Do **not** use this against any device you do not own or have permission to test.  
> The author assumes **no responsibility** for any misuse.

## Usage

Host the files locally or on a test server, then open `exploit.html` in a FreeType-based renderer to trigger the payload.
