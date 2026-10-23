<h1 align="center">OrchardVM</h1>

<p align="center">
  <strong>Virtual machines and experimental OS emulation, right on Android.</strong><br>
  Explore iOS environments and more from your phone.
</p>

<p align="center">
  <img alt="Android" src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white">
  <img alt="Experimental" src="https://img.shields.io/badge/Project-Experimental-6C63FF?style=flat-square">
</p>

<p align="center">
  <em>An Android emulator project for exploring iOS and other operating systems.</em>
</p>

---

## 📖 About

**OrchardVM** is an experimental Android app designed to help you set up and run virtualized or emulated operating-system environments directly on an Android phone.

> [!IMPORTANT]
> OrchardVM is currently a **public beta**. Expect bugs, warnings, and unfinished features. Not every setup will work on every device.

## ✨ Features

| Environment | Current status | Details |
|:--|:--|:--|
| **iOS** | 🧪 Public beta | Includes configurations listed for **iPod touch 2.0** and **iPhone 11 (iOS 14)** |
| **Windows Phone** | 🚧 In development | Not yet ready for general use |
| **Windows** | 🚧 In development | Planned for **KVM-capable** devices |
| **FirefoxOS** |  🧪 Public beta | Bugs and problems but works |
> Additional environments and improvements may arrive as development continues.

## 📋 Requirements

- An **Android phone**
- **Termux installed from F-Droid** (not the Play Store version) (NOTE: Termux isn't needed if 0.4.9 and newer
- Enough available storage and memory for the environment you want to run; needs will vary by configuration

**Termux:** https://f-droid.org/packages/com.termux/

## 🚀 Getting Started

1. **Install Termux** from the F-Droid link above.
2. **Open OrchardVM** and navigate to the **Setup** tab.
3. **Choose an available environment** and follow its setup process.
4. If a setup (such as **FirefoxOS**) does not begin automatically, try pressing **Start** to let it configure itself.
5. For the iOS configurations, check the **Setup** tab for the **iOS 14 / iOS 3** options.
6. Once setup finishes, launch your configured environment.

> [!NOTE]
> Some environments are still being developed. An entry appearing in the project roadmap does **not** mean it is ready to run.

## 🐛 Known Issues

- As a public beta, OrchardVM may display **errors or warnings**.
- Some setup processes might need to be **started manually**.
- Compatibility and performance can vary by **device and environment**.
- **Windows Phone** and **Windows (KVM)** support are still in development.

If something goes wrong, please report the environment, device model, Android version, steps to reproduce, and any relevant error messages.

## 🧪 Tested Devices

| Device | Configuration |
|:--|:--|
| **Samsung Galaxy S25 Ultra** | **12 GB RAM** |
| **Poco X7 Pro** | **12GB RAM** |
| **Xiaomi 15T Pro** | **12GB RAM** |

Testing on one device doesn't guarantee compatibility with other Android phones.

## 🤝 Contributing & Feedback

Want to help improve OrchardVM? You can:

- ⭐ **Star the repository** to support the project.
- 🐛 **Report bugs** with clear reproduction steps.
- 💡 **Suggest features** or improvements.
- 🧪 **Share your test results** from other Android devices.

---

<p align="center">
  <strong>Made for experimentation. Improved by feedback.</strong><br>
  Thanks for checking out OrchardVM! 🍏
</p>
