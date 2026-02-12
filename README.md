# 🍷 Wine ARM64 macOS Build (Unofficial)

A custom Wine engine build for Apple Silicon (ARM64) Macs.  
This project aims to bridge the gap until official Wine ARM64 support is fully mature on macOS.

![Platform](https://img.shields.io/badge/platform-macOS--ARM64-blue?logo=apple)
![Language](https://img.shields.io/badge/made_with-Python%20%7C%20Java-orange)
![License](https://img.shields.io/github/license/AehoraDeSum/wine-arm64-macos-build)

---

## 🚀 Features

- ✅ Full ARM64 Wine engine for Apple Silicon Macs
- 🐍 Python-based build and packaging automation
- ☕ JavaFX-based GUI test tool
- 📄 Bilingual documentation (🇬🇧 English & 🇹🇷 Turkish)
- 📦 Wineskin integration ready

---

## 📦 Getting Started

### 1. Install Dependencies

```bash
brew install autoconf bison flex pkg-config
```

### 2. Build the Engine

```bash
cd python-scripts
python3 download_wine_src.py
python3 build.py
python3 patch_engine.py  # Optional
python3 package_engine.py
```

### 3. Test With JavaFX

```bash
cd java-tools
javac --module-path $PATH_TO_FX --add-modules javafx.controls EngineTesterFX.java
java --module-path $PATH_TO_FX --add-modules javafx.controls EngineTesterFX
```

---

## 📚 Documentation

📁 `docs/` klasörü içerisinde:

| Konu | English | Türkçe |
|------|---------|--------|
| Build Instructions | ✅ `build-instructions.en.md` | ✅ `build-instructions.tr.md` |
| Wineskin Integration | ✅ `integration-with-wineskin.en.md` | ✅ `integration-with-wineskin.tr.md` |
| Project Architecture | ✅ `architecture-overview.en.md` | ✅ `architecture-overview.tr.md` |

---

## 👨‍💻 About the Author

Developed by **Yiğit Yardımcı** as part of an open-source initiative to contribute to the macOS gaming and compatibility ecosystem.  
🛠️ Special focus on automation (Python) and system integration testing (JavaFX).

📫 Contact: [LinkedIn](https://www.linkedin.com/in/yigit-yardimci-a52b6823a/) | [GitHub](https://github.com/AehoraDeSum)

---

## 🧾 License

MIT License – see `LICENSE` file for details.
