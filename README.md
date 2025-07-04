# 🎯 Foocus Colab Launcher (Unofficial)

This notebook allows you to run [Fooocus](https://github.com/lllyasviel/Fooocus) — a powerful image generation UI based on Stable Diffusion — directly in **Google Colab**, with no local setup required.

---

## 🚀 Quick Start

Click below to launch the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KSOEnz7nYg7WA4IC2tu7TPhNHCntoC2q?usp=sharing)

---

## 🛠️ What This Notebook Does

- Clones the [Fooocus repository](https://github.com/lllyasviel/Fooocus)
- Installs dependencies (Torch, torchvision, xformers, etc.)
- Launches the app with `launch.py --share` so you can use it via a public link

---

## 📦 Requirements (Handled by Colab)

- Google account
- Runtime: GPU (recommended)

Go to **Runtime > Change runtime type > Select GPU** for best performance.

---

## 📋 How to Use

1. Open the notebook via the **Open in Colab** badge above.
2. Run each cell step by step (Shift + Enter).
3. Wait for the app to start — Colab will give you a **gradio.live** or **ngrok** link.
4. Click the link and start using Fooocus!

---

## 📁 Repository Cloned

This notebook automatically clones:
([Github link](https://github.com/lllyasviel/Fooocus.git))


If you want to contribute to Fooocus, please visit the [original repo](https://github.com/lllyasviel/Fooocus).

---

## ⚠️ Notes

- If you encounter a **"Too much RAM used"** or **"session crashed"**, try reducing batch size or resolution inside the Fooocus UI.
- This notebook does **not contain any model weights**. They will be auto-downloaded by Fooocus on first run.

---

## 🙏 Credits

- [lllyasviel/Fooocus](https://github.com/lllyasviel/Fooocus) for the awesome base repo
- [Google Colab](https://colab.research.google.com) for the free GPU compute
