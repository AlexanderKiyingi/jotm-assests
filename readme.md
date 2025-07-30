# 🎵 JOTM Assets Repository

This repository hosts public assets for **JOTM Radio (Jazz On The Move)**. These files are used by the JOTM mobile application and other media integrations (e.g., lock screen artwork, notifications, and promotional materials).

---

## 🧾 Purpose

- Serve static assets (e.g. logos, icons) via **GitHub Pages**
- Enable smooth integration with Flutter's `MediaItem.artUri` and other media APIs
- Make assets accessible from anywhere using public URLs

---

## 📁 Asset Structure
jotm-assets/
├── images/
│ └── 1JOTM_LOGO_GOLD.png



> 🌐 Access it publicly:
> 
> `https://domainname.github.io/jotm-assets/images/1JOTM_LOGO_GOLD.png`

---

## 📦 Usage Example (Flutter `MediaItem`)

```dart
MediaItem(
  id: '1',
  album: "JOTM Radio",
  title: "Jazz On The Move",
  artUri: Uri.parse('https://<yourusername>.github.io/jotm-assets/images/1JOTM_LOGO_GOLD.png'),
);