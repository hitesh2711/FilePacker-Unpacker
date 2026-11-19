# 📦 FilePacker-Unpacker

A Java-based file utility tool that allows packing multiple files into a single archive and unpacking them back with all metadata preserved. To enhance security, the packed file is encrypted so only authorized users can decrypt and extract the data, complete with a Swing-based GUI for easy interaction.

---

## 🚀 Features
- **File Packing** – Combines multiple regular files into a single archive.
- **File Unpacking** – Restores original files and metadata from the packed archive.
- **Encryption** – Built-in XOR-based encryption & decryption for data security.
- **Graphical User Interface (GUI)** – Simple Swing-based UI for packing and unpacking.
- **Cross-Platform** – Works on any system with Java Runtime Environment (JRE).

## 🛠 Tech Stack
- **Language:** Java 17+
- **GUI Framework:** Swing
- **Core API:** Java I/O Streams

---

## 📂 Project Structure
```text
FilePacker-Unpacker/
├── src/
│   └── FilePackerUnpacker/
│       ├── FilePacker.java
│       ├── FileUnpacker.java
│       └── GUI.java
└── screenshots/
    ├── main_window.png
    ├── packing_example.png
    └── unpacking_example.png
```

---

## ⚙️ Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/hitesh2711/FilePacker-Unpacker
cd FilePacker-Unpacker/src
```

### 2. Compile & Run (Source Code)
```bash
javac FilePackerUnpacker/*.java
java FilePackerUnpacker.GUI
```

---

## 🎓 Learning Outcomes
- Practical experience with Java I/O Streams and file handling.
- Implementation of metadata management in file operations.
- Understanding of encryption/decryption techniques in Java.
- Hands-on experience with Swing GUI development.

---

## 🔮 Future Improvements
- Add support for drag-and-drop in GUI.
- Stronger encryption methods (AES instead of XOR).
- Multi-threading for faster packing/unpacking.
- Cloud integration for remote file storage.

---

## 👨‍💻 Author
**Hitesh Choudhary**

