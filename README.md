Great! Below is a **complete step-by-step installation guide** you can include in your GitHub repository's `README.md`. It will help anyone (even beginners) set up your **Internet Speed Monitor Widget** on a Windows desktop.

---

## 🖥️ Internet Speed Widget

A lightweight Python desktop widget that shows real-time **upload and download speed** in a floating window. Built with **Tkinter**, it stays on top and uses minimal system resources.

![Preview](screenshot.png)

---

## 📦 Features

* Real-time download/upload speed (KB/s)
* Clean and semi-transparent UI
* Always-on-top widget
* Draggable interface
* System tray integration
* Super lightweight (uses only Python and a few libraries)

---

## ⚙️ Installation Guide (For Windows)

> ⚠️ Only needed once. After setup, you can run the widget by double-clicking the `.py` file.

### ✅ 1. Install Python

1. Go to the [official Python website](https://www.python.org/downloads/)
2. Download **Python 3.10+ for Windows**
3. During installation, **check this box**:

   ```
   ✅ Add Python to PATH
   ```
4. Click **Install Now**

To confirm installation:

```sh
python --version
```

You should see something like:

```
Python 3.11.5
```

---

### 📥 2. Download This Project

* Either:

  * Clone this repo:

    ```sh
    git clone https://github.com/yourusername/internet-speed-widget.git
    cd internet-speed-widget
    ```
  * Or [Download ZIP](https://github.com/yourusername/internet-speed-widget/archive/refs/heads/main.zip) → Extract

---

### 📦 3. Install Required Python Packages

Open **Command Prompt** in the project folder and run:

```sh
python -m pip install -r requirements.txt
```

If `requirements.txt` doesn't exist, install manually:

```sh
python -m pip install psutil pystray pillow
```

---

### 🚀 4. Run the Widget

In the project folder:

```sh
python speed_widget.py
```

The widget will appear on screen and start updating network speed every second.

---

## 🔁 Auto Start (Optional)

To make the widget auto-run at startup:

1. Create a shortcut of `speed_widget.py`
2. Press `Win + R` and type:

   ```
   shell:startup
   ```
3. Paste the shortcut inside the folder that opens

---

## 🧼 Uninstall

* Just delete the folder.
* Remove the startup shortcut if you added it.

---

## 📃 Requirements

* Windows 10 or 11
* Python 3.10+
* Packages:

  * `psutil`
  * `pystray`
  * `pillow`
  * `tkinter` (comes built-in with Python)

---

## 🧠 Credits

Developed by [Ozair] (https://github.com/Ozair-eng)

---

Would you like me to:

* Generate a `README.md` file with this content?
* Also include a `requirements.txt` file?

Let me know and I’ll send you a complete zipped GitHub-ready folder.
