# DragStash — Drag & Drop Shelf for Windows 🗂️

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?logo=windows)](https://github.com/Nitesh87409/dragstash-windows)
[![Published](https://img.shields.io/badge/Microsoft%20Store-Live-brightgreen?logo=microsoft)](https://github.com/Nitesh87409/dragstash-windows)
[![Framework](https://img.shields.io/badge/Framework-Flutter%20Desktop-02569B?logo=flutter)](https://flutter.dev)

> **DragStash** is a seamless, frameless Windows desktop utility designed to temporarily hold, organize, and manage dragged files, images, links, and documents.

---

## 💡 The Problem & Solution
When moving files between deeply nested folders, multiple screens, or applications, users often struggle with juggling windows.  
**DragStash** acts as a lightweight floating shelf: simply drag any file into the floating zone to stash it, switch your folder or app comfortably, and drag it right back out.

---

## ✨ Key Features
- **Floating Drop Shelf:** Frameless, stay-on-top window overlay that activates instantly when files are dragged.
- **Drag In / Drag Out:** Native Windows Shell integration allowing smooth two-way drag-and-drop operations.
- **System Tray Integration:** Runs quietly in the background without cluttering the taskbar.
- **Ultra-lightweight:** Minimal CPU and RAM footprint built with optimized Flutter Desktop and Win32 C++ interop.
- **Modern Fluent UI:** Clean, dark/light theme aesthetics conforming to Windows 11 design guidelines.

---

## 🛠️ Architecture & Tech Stack
- **Engine:** Flutter Desktop (Windows target)
- **Native Interop:** Windows Win32 API (`user32.dll`, `shell32.dll` for window hooks and drag events)
- **Packaging:** Windows MSIX Package for Microsoft Store distribution
- **State Management:** Reactive clean architecture

---

## 🔒 Source Code & License Notice
> **Proprietary Software Notice:**  
> This repository is an official public portfolio showcase. The proprietary production source code is owned and maintained under **[NiteshCodes-Official](https://github.com/NiteshCodes-Official)**. Source code is closed-source to protect commercial intellectual property.