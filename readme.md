
# 🚀 YpsilonX Builder - Professional Stealer Loader Generator

> **Advanced Python-based stealer loader generator with automatic obfuscation and executable compilation**

![Version](https://img.shields.io/badge/version-1.1-blue.svg)
![Python](https://img.shields.io/badge/python-3.7+-green.svg)
![License](https://img.shields.io/badge/license-Premium-red.svg)

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Detailed Usage](#-detailed-usage)
- [Configuration](#-configuration)
- [Troubleshooting](#-troubleshooting)
- [Support](#-support)
- [Disclaimer](#-disclaimer)

---

## ✨ Features

- 🔐 **KeyAuth Integration** - Secure license verification system
- 🌐 **Discord Webhook Support** - Real-time data transmission
- 🔒 **Automatic Obfuscation** - Advanced code protection with external obfuscator
- 📦 **Multiple Build Options** - PyInstaller, IExpress, and Shortcut support
- 🎨 **Custom Icon Support** - Personalize your executables
- ⚡ **Admin Privileges** - Optional UAC elevation
- 🛡️ **Anti-Detection** - Built-in evasion techniques
- 📁 **Clean Build Process** - Automatic temporary file cleanup

---

## 📋 Requirements

### System Requirements
- **OS**: Windows 10/11 (64-bit)
- **Python**: 3.7 or higher
- **RAM**: Minimum 4GB
- **Storage**: 2GB free space

### Python Dependencies
The script will automatically install these libraries:
- `requests`
- `wmi`
- `psutil`
- `pyarmor==7.6.1`
- `pyinstaller`
- `Pillow`
- `discord-webhook`
- `pycryptodomex`
- `pycryptodome`
- `pywin32`
- `customtkinter`
- `colorama`
- `fade`

---

## 🚀 Installation

### Step 1: Download Files
1. Download the complete package
2. Extract all files to a dedicated folder
3. Ensure you have the following files:
   ```
   📁 YpsilonX-Builder/
   ├── Y7Tva9MnEMT.py          # Main builder script
   ├── obfuscator.py           # Code obfuscator
   ├── README.md               # This file
   └── 📁 build/               # Output directory (auto-created)
   ```

### Step 2: Install Python
1. Download Python 3.7+ from [python.org](https://python.org)
2. During installation, **check "Add Python to PATH"**
3. Verify installation: `python --version`

### Step 3: Run as Administrator
- **Right-click** on `Y7Tva9MnEMT.py`
- Select **"Run as administrator"**
- The script will automatically install required dependencies

---

## ⚡ Quick Start

1. **Launch the Builder**
   ```bash
   python Y7Tva9MnEMT.py
   ```

2. **Enter License Key**
   - Input your valid KeyAuth license key
   - Press Enter to continue

3. **Configure Your Stealer**
   - **Discord Webhook**: Your Discord webhook URL
   - **File Name**: Name for the output executable
   - **Icon Path**: Optional custom icon (.ico file)
   - **Admin Rights**: Choose if exe needs admin privileges

4. **Build Process**
   - Code uploads to dpaste automatically
   - Obfuscation applied (if obfuscator.py present)
   - Executable compilation with PyInstaller

5. **Get Your File**
   - Find your executable in the `build/` folder
   - Ready for deployment

---

## 📖 Detailed Usage

### 1. Discord Webhook Setup

**Create a Discord Webhook:**
1. Go to your Discord server
2. Right-click on a channel → "Edit Channel"
3. Go to "Integrations" → "Webhooks"
4. Click "New Webhook"
5. Copy the webhook URL

**Webhook URL Format:**
```
https://discord.com/api/webhooks/YOUR_WEBHOOK_ID/YOUR_WEBHOOK_TOKEN
```

### 2. File Naming Convention

**Recommended naming:**
- ✅ `system_update`
- ✅ `security_patch`
- ✅ `windows_fix`
- ❌ `stealer` (avoid obvious names)

### 3. Icon Customization

**Icon Requirements:**
- Format: `.ico` file
- Size: 256x256 pixels recommended
- Path: Full path to icon file
- Example: `C:\Icons\update.ico`

### 4. Obfuscation Options

**Automatic Obfuscation:**
- Place `obfuscator.py` in the same folder
- Obfuscation applied automatically
- Multiple layers of protection

**Manual Obfuscation:**
```bash
python obfuscator.py output_name.py
```

### 5. Build Methods

**PyInstaller (Recommended):**
- Single executable file
- No dependencies required
- Best compatibility

**IExpress (Coming Soon):**
- Windows native installer
- Silent installation
- Professional appearance

**Shortcut (Coming Soon):**
- Lightweight option
- Quick deployment
- Minimal footprint

---

## ⚙️ Configuration

### Advanced Settings



**Build Directory:**
- Default: `./build/`
- Change in script if needed

**Obfuscation Settings:**
- Recursive obfuscation: 1 iteration (default)
- Anti-debugging: Enabled
- Code morphing: Enabled

---

## 🔧 Troubleshooting

### Common Issues

**1. "License failed" Error**
```
Solution: Verify your KeyAuth license is valid and active
```

**2. "obfuscator.py not found"**
```
Solution: Ensure obfuscator.py is in the same directory as the main script
```

**3. PyInstaller Installation Failed**
```
Solution: Run as administrator and ensure internet connection
```

**4. "Upload failed" Error**
```
Solution: Check internet connection and dpaste.com availability
```

**5. Permission Denied**
```
Solution: Run the script as administrator
```

### Error Codes

| Error | Description | Solution |
|-------|-------------|----------|
| `[x] Invalid webhook` | Discord webhook format incorrect | Check webhook URL format |
| `[x] Upload failed` | Dpaste upload failed | Check internet connection |
| `[!] Obfuscation failed` | Obfuscator error | Verify obfuscator.py file |
| `[x] Error while running PyInstaller` | Compilation failed | Run as administrator |

---

## 📞 Support

### Getting Help

**Before contacting support:**
1. ✅ Read this README completely
2. ✅ Check the troubleshooting section
3. ✅ Verify all requirements are met
4. ✅ Try running as administrator

**Contact Information:**
- **Discord**: [Your Discord Server]
- **Telegram**: [Your Telegram Channel]
- **Email**: [Your Support Email]

### Bug Reports

When reporting issues, include:
- Error message (screenshot or text)
- Python version: `python --version`
- Windows version
- Steps to reproduce
- Screenshots if applicable

---

## ⚠️ Disclaimer

**IMPORTANT LEGAL NOTICE:**

This software is provided for **EDUCATIONAL PURPOSES ONLY**. The developers are not responsible for any misuse of this tool. Users must:

- ✅ Use only on systems they own or have explicit permission to test
- ✅ Comply with all applicable laws and regulations
- ✅ Not use for malicious purposes
- ✅ Accept full responsibility for their actions

**By using this software, you agree to:**
- Use it responsibly and legally
- Not hold the developers liable for any damages
- Comply with your local laws and regulations

---

## 🔄 Updates

**Current Version:** 1.1

**Latest Updates:**
- ✅ Enhanced obfuscation system
- ✅ Improved error handling
- ✅ Better file cleanup
- ✅ Menu return functionality
- ✅ English language support

**Upcoming Features:**
- 🔄 IExpress integration
- 🔄 Shortcut creation
- 🔄 Advanced anti-detection
- 🔄 Custom encryption methods

---

## 📄 License

This software is **PREMIUM** and requires a valid license key from KeyAuth.

**License Terms:**
- Single user license
- No redistribution allowed
- Updates included for 1 year
- Technical support included

---

**Made with ❤️ by the YpsilonX Team**

*For educational and authorized testing purposes only.* 
