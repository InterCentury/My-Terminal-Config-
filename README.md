
# Windows Terminal Custom Config Pack

A curated collection of **Windows Terminal configurations**, **themes**, and **fonts** for easy, clean, and fast terminal customization on Windows.

This repository is designed so **anyone**—from beginners to power users—can quickly personalize their terminal without digging through documentation or trial-and-error.

---
![Alt text]([121233.png](https://github.com/InterCentury/My-Terminal-Config-/blob/main/Previews/terminal_preview_1.png?raw=true))
## ✨ Features

- 🎨 Pre-made **terminal themes**
- 🧩 Ready-to-use **Windows Terminal `settings.json` configs**
- 🔤 Nerd Fonts & programming-friendly fonts
- ⚡ Minimal, clean, and readable setups
- 🆓 Free & open-source (MIT License)

---

## 📂 Repository Structure

```

.
├── Config/
│   ├── settings.json
│   ├── minimal.json
│   └── power-user.json
│
├── Themes/
│   ├── Dracula.json
│   ├── Gruvbox.json
│   ├── Nord.json
│   └── Custom/
│
├── Fonts/
│   ├── JetBrainsMono/
│   ├── FiraCode/
│   ├── CascadiaCode/
│   └── README.md
│
└── README.md

````

---

## 🚀 Getting Started

### 1️⃣ Install Windows Terminal
Download from:
- Microsoft Store (recommended)
- Or GitHub Releases

---

### 2️⃣ Install Fonts

1. Open the `Fonts/` folder
2. Choose a font family
3. Select all `.ttf` files
4. Right-click → **Install for all users**

⚠ Restart Windows Terminal after installing fonts.

---

### 3️⃣ Apply Config

1. Open Windows Terminal
2. Press `Ctrl + ,` (opens `settings.json`)
3. Backup your existing config:
   ```json
   // Save a copy somewhere safe
````

4. Copy a config from `Config/`
5. Paste it into your Windows Terminal settings
6. Save & restart

---

### 4️⃣ Apply a Theme

1. Open a theme file from `Themes/`
2. Copy the theme JSON block
3. Paste it inside:

   ```json
   "schemes": []
   ```
4. Set it as default:

   ```json
   "colorScheme": "ThemeName"
   ```

---

## 🎨 Preview

> Screenshots coming soon
> (Feel free to open a PR and add previews!)

---

## 🛠 Compatibility

* ✅ Windows 10 (19041+)
* ✅ Windows 11
* ✅ PowerShell
* ✅ Command Prompt
* ✅ WSL


---

## 📖 Customization Tips

* Use **Nerd Fonts** for icons
* Pair with:

  * `oh-my-posh`
  * `starship`
  * `zoxide`
* Enable acrylic:

  ```json
  "useAcrylic": true,
  "acrylicOpacity": 0.8
  ```

---

## 🤝 Contributing

Contributions are welcome!

You can:

* Add new themes
* Improve configs
* Add fonts
* Fix documentation
* Add screenshots

### Steps:

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to:

* Use
* Modify
* Share
* Redistribute

Even for commercial use.

---

## ⭐ Support

If you find this useful:

* Give the repo a ⭐
* Share it with friends
* Use it as a base for your own setup

Happy customizing 🚀

```
