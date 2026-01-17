<p align="center">
  <img src="https://raw.githubusercontent.com/TurtlPass/turtlpass-firmware-arduino/master/assets/icon.png" alt="Logo" width="133"/>
</p>

<h2 align="center">🔗 TurtlPass Ecosystem</h2>

<p align="center">
  🐢 <a href="https://github.com/TurtlPass/turtlpass-firmware-arduino"><b>Firmware</b></a> •
  💾 <a href="https://github.com/TurtlPass/turtlpass-protobuf"><b>Protobuf</b></a> •
  💻 <a href="https://github.com/TurtlPass/turtlpass-python"><b>Host</b></a> •
  🌐 <a href="https://github.com/TurtlPass/turtlpass-chrome-extension"><b>Chrome</b></a> •
  📱 <a href="https://github.com/TurtlPass/turtlpass-android"><b>Android</b></a>
</p>

---

# 🌍 TurtlPass Website

[![](https://img.shields.io/badge/Kotlin-Wasm-purple?logo=kotlin)](https://kotlinlang.org/docs/wasm-overview.html "Kotlin/Wasm")
[![](https://img.shields.io/badge/Compose-Multiplatform-blue?logo=jetbrains)](https://www.jetbrains.com/compose-multiplatform/ "Compose Multiplatform")
[![](https://img.shields.io/badge/Status-Under%20Development-orange)](#)

> 🚧 **This project is currently under active development.**
> Features, structure, and deployment details are subject to change.

The official **TurtlPass website**, built entirely in **Kotlin/Wasm** using **Compose Multiplatform for Web**.

This site serves as the public-facing entry point for the TurtlPass ecosystem, providing product information, documentation, downloads, and a consistent UI stack shared with other TurtlPass applications.

---

## ✨ Highlights

* ⚡ Compiled to **WebAssembly (Wasm)** via Kotlin
* 🎨 Declarative UI with Material-style components
* 🔐 No JavaScript frameworks required

---

## 🧠 Architecture Overview

The website is written in Kotlin and rendered in the browser using WebAssembly.
Compose handles UI composition, state, and layout – no HTML templating or JS frameworks involved.

```
+-----------------------------+
|     Compose Multiplatform   |
|-----------------------------|
|   @Composable UI Functions  |
|   State & Navigation        |
+-------------+---------------+
              |
              v
      Kotlin/Wasm Compiler
              |
              v
+-----------------------------+
|        WebAssembly          |
|-----------------------------|
|   Runs in Browser Sandbox   |
|   No JS Framework Runtime   |
+-----------------------------+
```

---

## 🧩 Tech Stack

* **Kotlin/Wasm** – WebAssembly target for Kotlin
* **Compose Multiplatform** – Declarative UI framework
* **Gradle** – Build system
* **Material Design** – UI components & theming

---

## 📚 Related Resources

* 📖 [Kotlin/Wasm Overview](https://kotlinlang.org/docs/wasm-overview.html)
* 🎨 [Compose Multiplatform](https://www.jetbrains.com/compose-multiplatform/)
