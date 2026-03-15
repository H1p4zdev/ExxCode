# ExxCode (Xed-Editor Extension)

ExxCode is an AI agent extension for **Xed-Editor (Karbon)**. It adds command palette actions like opening an agent chat, explaining a selection, summarizing the current file, and refactoring the current file.

---

## 🚀 Getting Started

### 1. Clone

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

---

### 2. Configure

Before building, update the following in `manifest.json`:

* `name` – your extension’s name
* `version` – version of your extension
* `authors` – Developers of the extension

>[!WARNING]
If you rename the main class or move it to another package/folder, **you must update the `mainClass` field in `manifest.json`**, or the extension will not load.

---

### 3. Build the Extension

To build the extension in **debug mode**, run:

```bash
./compileDebug
```

(You can create your own release script later if needed.)

---

### 4. Find the Output

After a successful build, your extension package will be created here:

```
output/YourExtensionName.zip
```

This ZIP file is what you load into **Xed-Editor** as a extension.

---

## 📖 Documentation

For more detailed information about creating and managing extensions for Xed-Editor, see the official documentation:

[Xed-Editor Extension Docs](https://xed-editor.github.io/Xed-Docs/docs/extensions/)

This includes guides, API references, examples, and best practices for developing your extensions.
