# 🔐 Password Generator

A modern, secure password generator with pronounceable passwords.

🌐 [LIVE](https://phpoyer.github.io/password-generator/)

## ✨ Features

- 🎯 **Pronounceable Passwords** - Easy to remember through consonant-vowel patterns
- 🌓 **Dark/Light Mode** - Automatic theme storage
- 🌍 **Multilingual** - German and English
- 📱 **Responsive Design** - Works on desktop and mobile
- 🔒 **100% Client-side** - No server communication, all passwords remain local
- 💾 **Offline-capable** - No external dependencies
- 📋 **One-click Copy** - Individual passwords or all at once

## 🎨 Design

- Minimalist interface
- Smooth animations and transitions
- Green color scheme for better visibility
- Favicons in various sizes

## 🔧 Technology

- **HTML5** - Semantic markup
- **CSS3** - Custom Properties, Flexbox, Grid
- **Vanilla JavaScript** - No frameworks, no build tools
- **LocalStorage** - Persistent theme and language settings

## 📝 Password Format

Generated 12 character passwords follow this pattern:
```
[2 Capital Letters][6 Consonant-Vowel Letters][3 Digits][1 Special Character]
```

**Pattern:** 2G + 6K + 3Z + 1S (12 characters)

**Examples:**
- `VibeWufu357+`
- `NopaKate924#`
- `TixuRevo618-`

**Security (12 characters - the more signs, the better):**
- ~16.3 trillion combinations
- ~2.7 minutes to crack (offline brute-force attack)
- Practically uncrackable with online rate limiting
- Fully secure when combined with 2FA

**Settings:**
- Length: 10-20 characters (default: 12)
- Count: 1-50 passwords (default: 3)
- Special characters: `-`, `+`, `#`

## 🚀 Installation

### Local Usage

- Open the HTML file in your browser

## 🎯 Usage

1. **Choose password length** (10-20 characters)
2. **Set count** (1-50 passwords)
3. **Click "Generate"**
4. **Copy individual password** or **"Copy All"**
5. **Switch language** with the DE/EN button
6. **Change theme** with the 🌙/☀️ button

## 🔐 Security

- ✅ All passwords are generated client-side
- ✅ No data is sent to external servers
- ✅ Uses `crypto.getRandomValues()` for secure random numbers
- ✅ No cookies or tracking
- ✅ Code can be reviewed

## 🌍 Languages

- 🇩🇪 German
- 🇬🇧 English

Language selection is saved in the browser.

## 🎨 Theme

- 🌙 **Dark Mode** (default)
- ☀️ **Light Mode**

Theme setting is saved in the browser.

## 📱 Browser Compatibility

- ✅ Chrome/Edge (latest versions)
- ✅ Firefox (latest versions)
- ✅ Safari (latest versions)
- ✅ Mobile browsers (iOS/Android)

## 🤝 Contributing

Contributions are welcome! Please create a pull request or open an issue.

## 📄 License

NON-COMMERCIAL License. See license file.

## 👤 Author

**P. Poyer**
- GitHub: [@phpoyer](https://github.com/phpoyer)

---

**Note:** For maximum security, use a professional password manager such as Keepass, Proton Pass, 1Password or Bitwarden for long-term storage of your passwords.
