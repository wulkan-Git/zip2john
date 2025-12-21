# zip2john Guide 🇷🇺

Complete guide for extracting hashes from ZIP archives using zip2john for John the Ripper

---

## 📋 Contents
- [Purpose](#purpose)
- [Quick Start](#quick-start)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [FAQ](#faq)
- [Warning](#warning)

---

## 🎯 Purpose

`zip2john` is a utility for extracting cryptographic hashes from password-protected ZIP archives...

*(далее весь ваш контент на русском, но с английскими заголовками для якорей)*

## ⚡ Quick Start

```bash
zip2john protected.zip > hash.txt
john --wordlist=rockyou.txt hash.txt
john --show hash.txt
