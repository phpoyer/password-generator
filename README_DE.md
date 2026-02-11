# 🔐 Password Generator

Ein moderner, sicherer Passwort-Generator mit aussprechbaren Passwörtern.

🌐 [Live](https://phpoyer.github.io/password-generator/)

## ✨ Features

- 🎯 **Aussprechbare Passwörter** - Leicht zu merken durch Konsonant-Vokal-Muster
- 🌓 **Dark/Light Mode** - Automatische Theme-Speicherung
- 🌍 **Mehrsprachig** - Deutsch und Englisch
- 📱 **Responsive Design** - Funktioniert auf Desktop und Mobile
- 🔒 **100% Client-seitig** - Keine Server-Kommunikation, alle Passwörter bleiben lokal
- 💾 **Offline-fähig** - Keine externen Dependencies
- 📋 **Ein-Klick-Kopieren** - Einzelne Passwörter oder alle auf einmal

## 🎨 Design

- Minimalistisches Interface
- Smooth Animationen und Transitions
- Grünes Farbschema für bessere Sichtbarkeit
- Favicons in verschiedenen Größen

## 🔧 Technologie

- **HTML5** - Semantisches Markup
- **CSS3** - Custom Properties, Flexbox, Grid
- **Vanilla JavaScript** - Keine Frameworks, keine Build-Tools
- **LocalStorage** - Persistente Theme- und Spracheinstellungen

## 📝 Passwort-Format

Generierte Passwörter folgen diesem Muster:
```
[Großbuchstabe][Konsonant-Vokal-Muster][3 Ziffern][Sonderzeichen]
```

**Beispiele:**
- LexaKiwu865-
- MikaKuxu228!
- VoriHaka223$

**Einstellungen:**
- Länge: 12-20 Zeichen (Standard: 12)
- Anzahl: 1-50 Passwörter (Standard: 3)
- Sonderzeichen: `-`, `!`, `$`

## 🚀 Installation

### Lokale Nutzung

- HTML-Datei im Browser öffnen

## 🎯 Verwendung

1. **Passwortlänge wählen** (12-20 Zeichen)
2. **Anzahl festlegen** (1-50 Passwörter)
3. **"Generieren" klicken**
4. **Einzelnes Passwort kopieren** oder **"Alle kopieren"**
5. **Sprache wechseln** mit dem DE/EN Button
6. **Theme ändern** mit dem 🌙/☀️ Button

## 🔐 Sicherheit

- ✅ Alle Passwörter werden client-seitig generiert
- ✅ Keine Daten werden an externe Server gesendet
- ✅ Verwendung von `crypto.getRandomValues()` für sichere Zufallszahlen
- ✅ Keine Cookies oder Tracking
- ✅ Code kann überprüft werden

## 🌍 Sprachen

- 🇩🇪 Deutsch
- 🇬🇧 Englisch

Sprachauswahl wird im Browser gespeichert.

## 🎨 Theme

- 🌙 **Dark Mode** (Standard)
- ☀️ **Light Mode**

Theme-Einstellung wird im Browser gespeichert.

## 📱 Browser-Kompatibilität

- ✅ Chrome/Edge (neueste Versionen)
- ✅ Firefox (neueste Versionen)
- ✅ Safari (neueste Versionen)
- ✅ Mobile Browser (iOS/Android)

## 🤝 Beitragen

Contributions sind willkommen! Bitte erstelle einen Pull Request oder öffne ein Issue.

## 📄 Lizenz

NON-COMMERCIAL Lizenz. Siehe Lizenz-Datei.

## 👤 Autor

**P. Poyer**
- GitHub: [@phpoyer](https://github.com/phpoyer)

---

**Hinweis:** Für maximale Sicherheit verwenden Sie einen professionellen Passwort-Manager wie KeePass, Proton Pass, 1Password oder Bitwarden für die langfristige Speicherung Ihrer Passwörter.
