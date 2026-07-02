<div align="center">

# 📱 Qrify

### A modern, native Android QR code scanner & generator — built with Jetpack Compose

<p>
  <img src="https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>
  <img src="https://img.shields.io/badge/Min%20SDK-24-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Min SDK 24"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
</p>

<p>
  <img src="https://img.shields.io/badge/100%25-Ad--Free-success?style=for-the-badge&logo=adblock&logoColor=white" alt="Ad-Free"/>
  <img src="https://img.shields.io/badge/No%20Trackers-Privacy%20First-informational?style=for-the-badge&logo=shield&logoColor=white" alt="No Trackers"/>
</p>

<p>
  <img src="https://img.shields.io/github/stars/mustafizur-web/Qrify?style=social" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/mustafizur-web/Qrify?style=social" alt="Forks"/>
  <img src="https://img.shields.io/github/issues/mustafizur-web/Qrify" alt="Issues"/>
  <img src="https://img.shields.io/github/last-commit/mustafizur-web/Qrify" alt="Last Commit"/>
</p>

**Scan. Generate. Organize.** Qrify is a fast, privacy-first QR code toolkit for Android — scan any code with real-time detection, generate custom QR codes for links, Wi-Fi, contacts and more, and keep a searchable history of everything you've scanned.

> 🚫 **100% Ad-Free.** No banner ads, no interstitials, no promotional pop-ups, and no third-party promotion of any kind — ever.

[Features](#-features) •
[Demo](#-demo) •
[Screenshots](#-screenshots) •
[Tech Stack](#-tech-stack) •
[Getting Started](#-getting-started) •
[Architecture](#-project-architecture) •
[Roadmap](#-roadmap) •
[Contributing](#-contributing)

</div>

---

## 🎬 Demo

<div align="center">

### 📥 Try Qrify Now

<a href="https://drive.google.com/file/d/1j6Jnp9CjR54zPrdZJwpG1J7EYmN-Se-S/view?usp=drive_link">
  <img src="https://img.shields.io/badge/Download-Qrify%20APK-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Download Qrify"/>
</a>

**[👉 Click here to view / download Qrify](https://drive.google.com/file/d/1j6Jnp9CjR54zPrdZJwpG1J7EYmN-Se-S/view?usp=drive_link)**

<sub>Hosted on Google Drive — tap the link above to preview or download the app.</sub>

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🔍 Smart Scanner
- Real-time QR/barcode detection powered by **ML Kit**
- Live camera preview with **CameraX**
- Flashlight toggle for low-light scanning
- Import & scan QR codes directly from your gallery
- Haptic feedback on successful scan

</td>
<td width="50%" valign="top">

### 🎨 QR Generator
- Create QR codes for **Links, Text, Wi-Fi, Contacts, Email, SMS & Phone numbers**
- Instant live preview as you type
- Save generated codes straight to your gallery
- One-tap sharing to any app

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Built-in URL Safety
- On-device heuristic risk analysis for scanned links
- Flags shortened URLs and suspicious top-level domains
- Warns before opening potentially unsafe links
- Optional auto-open for verified safe HTTPS links

</td>
<td width="50%" valign="top">

### 🗂️ Scan History
- Automatically saves every scan, searchable and organized
- Smart content-type detection: URLs, Wi-Fi, contacts, calendar events, geo-locations, deep links & more
- One tap to re-open, copy, or delete past scans
- Contextual quick actions (Call, Email, Connect to Wi-Fi, Save Contact, Open in Maps, Add to Calendar...)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚫 Ad-Free by Design
- **Zero ads** — no banners, no interstitials, no video ads
- **Zero promotions** — no sponsored content, no third-party product placement
- No paywalls or "premium unlock" nags
- A clean, distraction-free experience from first launch to last

</td>
<td width="50%" valign="top">

### 🔒 Privacy First
- No analytics SDKs, no ad networks, no data harvesting
- All scans and settings stay **on your device**
- Nothing is uploaded, shared, or sold — ever

</td>
</tr>
</table>

### 🎛️ Plus:
- 🌙 **Dark theme** support with full Material 3 theming
- ⚙️ **Customizable settings** — haptics, auto-open links, appearance
- 🧩 **Deep link routing** — the app intelligently routes parsed content to the right system action

---

## 📸 Screenshots

<div align="center">
<i>Add your app screenshots here to showcase the Scanner, Generator, History, and Settings screens.</i>

<table>
  <tr>
    <td align="center"><img src="docs/screenshots/scanner.png" width="200" alt="Scanner Screen"/><br/><sub>Scanner</sub></td>
    <td align="center"><img src="docs/screenshots/generator.png" width="200" alt="Generator Screen"/><br/><sub>Generator</sub></td>
    <td align="center"><img src="docs/screenshots/history.png" width="200" alt="History Screen"/><br/><sub>History</sub></td>
    <td align="center"><img src="docs/screenshots/settings.png" width="200" alt="Settings Screen"/><br/><sub>Settings</sub></td>
  </tr>
</table>
</div>

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| **Language** | [Kotlin](https://kotlinlang.org/) |
| **UI Toolkit** | [Jetpack Compose](https://developer.android.com/jetpack/compose) + Material 3 |
| **Architecture** | MVVM (ViewModel + StateFlow), Repository pattern |
| **Camera** | [CameraX](https://developer.android.com/training/camerax) |
| **QR/Barcode Detection** | [ML Kit Barcode Scanning](https://developers.google.com/ml-kit/vision/barcode-scanning) |
| **QR Generation** | [ZXing](https://github.com/zxing/zxing) |
| **Navigation** | Jetpack Navigation Compose |
| **Local Storage** | Jetpack DataStore (Preferences) |
| **Serialization** | Gson |
| **Async** | Kotlin Coroutines & Flow |
| **Testing** | JUnit, Espresso, Compose UI Test |

---

## 🏗 Project Architecture

Qrify follows a clean, layered **MVVM** architecture that separates UI, domain logic, and data:

```
app/src/main/java/com/example/qrify/
├── ui/
│   ├── scanner/        → Camera preview, live QR detection screen
│   ├── generator/       → QR code creation screen
│   ├── history/         → Scan history list & search
│   ├── settings/        → App preferences
│   ├── result/          → Bottom sheet showing parsed scan results
│   ├── components/      → Reusable Compose UI components
│   ├── navigation/       → App-wide navigation graph
│   └── theme/            → Material 3 theming (color, typography)
│
├── domain/
│   ├── parser/          → Parses raw QR payloads into structured content
│   ├── generator/       → Builds QR bitmaps from user input
│   ├── safety/          → On-device URL risk analysis
│   ├── action/           → Routes parsed content to system actions (call, email, maps, etc.)
│   └── model/            → Domain models (ContentType, ParsedQrContent, UrlSafetyResult...)
│
├── data/
│   ├── local/            → Local persistence (scan history store & entities)
│   └── repository/       → Settings & scan history repositories
│
├── scanner/              → ML Kit barcode analyzer
├── AppContainer.kt       → Lightweight manual dependency container
└── MainActivity.kt       → Single-activity entry point
```

This structure keeps scanning, generation, safety-checking, and persistence fully decoupled — making the codebase easy to test, extend, and maintain.

---

## 🚀 Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (latest stable release recommended)
- JDK 11+
- An Android device or emulator running **API 24 (Android 7.0)** or higher

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mustafizur-web/Qrify.git
   cd Qrify
   ```

2. **Open in Android Studio**
   Open the project folder and let Gradle sync automatically.

3. **Run the app**
   Select a device/emulator and hit ▶️ Run — or from the command line:
   ```bash
   ./gradlew installDebug
   ```

4. **Grant camera permission**
   On first launch, allow camera access so Qrify can start scanning.

### Building a release APK

```bash
./gradlew assembleRelease
```

---

## 🔐 Permissions

| Permission | Purpose |
|---|---|
| `CAMERA` | Required to scan QR codes in real time |
| `VIBRATE` | Provides haptic feedback on successful scans |
| `INTERNET` | Reserved for future safety/verification features |

Qrify does **not** collect or transmit personal data. All scan history and settings are stored locally on-device.

> 💯 **No ads. No promotions. No trackers.** Qrify contains zero ad SDKs and zero analytics/tracking libraries — the `INTERNET` permission is reserved solely for potential future safety-verification features (e.g. Google Safe Browsing lookups), not for ads or telemetry.

---

## 🗺 Roadmap

- [ ] Google Safe Browsing API integration for enhanced URL safety checks
- [ ] Cloud backup & sync for scan history
- [ ] Batch QR generation & export
- [ ] Custom QR styling (colors, logos, frames)
- [ ] Widget support for quick scanning
- [ ] Wear OS companion app

---

## 🤝 Contributing

Contributions are welcome and appreciated! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please make sure your code follows the existing style and includes tests where applicable.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Mustafizur Rahman**

<p>
  <a href="https://github.com/mustafizur-web">
    <img src="https://img.shields.io/badge/GitHub-mustafizur--web-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

<div align="center">

### ⭐ If you find Qrify useful, consider giving it a star on GitHub!

<sub>Built with ❤️ using Kotlin & Jetpack Compose — 100% Ad-Free, Always.</sub>

</div>
