
<div align="center">

# ⚙️ Cysra Anome Plugin Factory (CAPF)

**AI-powered plugin generator for the Cysra Anome ecosystem.**

  <p align="center">
    <a href="https://github.com/muhabbetkusudayi/capf/stargazers">
      <img src="https://img.shields.io/github/stars/muhabbetkusudayi/capf?style=for-the-badge&color=gold" alt="Stars">
    </a>
    <a href="https://github.com/muhabbetkusudayi/capf/network/members">
      <img src="https://img.shields.io/github/forks/muhabbetkusudayi/capf?style=for-the-badge&color=orange" alt="Forks">
    </a>
    <a href="https://github.com/muhabbetkusudayi/capf/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/muhabbetkusudayi/capf?style=for-the-badge&color=blue" alt="License">
    </a>
    <a href="https://python.org">
      <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    </a>
    <a href="https://riverbankcomputing.com/software/pyqt/">
      <img src="https://img.shields.io/badge/PyQt-5-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt5">
    </a>
  </p>

  <p align="center">
    <a href="#-about-the-project">About</a> •
    <a href="#-key-features">Features</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-example-output">Example</a> •
    <a href="#-contributing">Contributing</a>
  </p>

</div>

---

## 🚀 About The Project

**Cysra Anome Plugin Factory (CAPF)** is an AI-driven tool designed to simplify and accelerate plugin creation for **Cysra Anome**. 

Developing plugins for new framework architectures can be challenging for beginners. CAPF lowers this barrier to zero by converting simple, 1-2 sentence prompts into fully functional, production-ready PyQt5 plugins.


---

## ✨ Key Features

* **⚡ Instant Generation:** Turn natural language prompts into working PyQt5 widgets in seconds.
* **📦 Standardized Architecture:** Ensures every plugin inherits correctly from `QWidget` and follows strict coding conventions.
* **🔓 Open Source First:** Built to make open-source plugin development accessible to everyone.
* **🧩 Modular & Clean Code:** Outputs self-contained, well-structured, and easily integrable Python scripts.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **UI Framework:** PyQt5
* **Target Environment:** Cysra Anome

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have Python installed, along with PyQt5:

```bash
pip install PyQt5

```

### Usage

1. Load the CAPF System Prompt into your AI Assistant.
2. Provide a brief description of the plugin you want to build (e.g., *"Create a terminal emulator plugin"*).
3. Copy the generated PyQt5 code into your Cysra Anome project!

---

## 💻 Example Output

Here is a minimal example of a widget generated following the CAPF standard:

```python
from PyQt5.QtWidgets import QWidget, QVBoxLayout, QLabel, QPushButton

class AppWidget(QWidget):
    def __init__(self):
        super().__init__()
        self.count = 0
        layout = QVBoxLayout()
        
        self.label = QLabel(f"Count: {self.count}")
        layout.addWidget(self.label)
        
        self.btn = QPushButton("Increase")
        self.btn.clicked.connect(self.increment)
        layout.addWidget(self.btn)
        
        self.setLayout(layout)

    def increment(self):
        self.count += 1
        self.label.setText(f"Count: {self.count}")

```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingPlugin`)
3. Commit your Changes (`git commit -m 'Add some AmazingPlugin'`)
4. Push to the Branch (`git push origin feature/AmazingPlugin`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

**Made with ❤️ by [muhabbetkusudayi](https://www.google.com/search?q=https://github.com/muhabbetkusudayi) for the Cysra Anome Community**
