# 📚 ArduinoCore-API for STM32duino

> **fork** of [`arduino/ArduinoCore-API`](https://github.com/arduino/ArduinoCore-API) — Designed to be used as a **Git submodule** in [`stm32duino/Arduino_Core_STM32`](https://github.com/stm32duino/Arduino_Core_STM32)

---

## 🎯 Purpose

This repository is a **fork** that contains **only** the official Arduino API and hardware-independent code.

**Main Goal:** Simplify Arduino API integration into STM32duino via a **git submodule**.

---

## 📦 What's Included?

✅ Arduino API official files (`api/` folder)

---

## 🚀 Using as a Submodule

### 1️⃣ Add the Submodule

In your `Arduino_Core_STM32` repository, run:

```bash
# Add this repository as a submodule
git submodule add https://github.com/stm32duino/ArduinoCore-API.git cores/arduino/api

# Initialize and update
git submodule update --init --recursive
```

---

## 🔗 Official Resources

| Resource | Link |
|----------|------|
| **Official ArduinoCore-API** | https://github.com/arduino/ArduinoCore-API |
| **STM32duino** | https://github.com/stm32duino/Arduino_Core_STM32 |

---

## 📝 License

This repository is a fork of `arduino/ArduinoCore-API` and maintains the **same license** (LGPL 2.1+).

See the `LICENSE` file in the repository root for details.

---

## 💡 Important Notes

### ✅ Advantages of Using a Submodule

- **Traceability**: Know exactly which version of the API you're using
- **Easy Updates**: Simple `git submodule update` to sync
- **Isolation**: API stays in its own code branch
- **Compatibility**: STM32-specific modifications remain separate

### ⚠️ Points to Consider

- **After Clone**: Run `git submodule update --init --recursive`

---

## 📊 Project Information

| Property | Value |
|----------|-------|
| **Type** | fork |
| **Use Case** | Submodule for STM32duino |
| **Language** | C/C++ |
| **License** | LGPL 2.1+ |
| **Original Repository** | https://github.com/arduino/ArduinoCore-API |
---

## ✨ Quick Start

### Clone with Submodule

```bash
git clone --recurse-submodules https://github.com/stm32duino/Arduino_Core_STM32.git
```

### Update Submodule

```bash
git submodule update --remote
```

---

**Last Updated:** December 15, 2025