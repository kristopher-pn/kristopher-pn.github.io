---
layout: "default"
title: "🚀 zalo-transfer-data - Simplify Your Zalo Data Transfer"
description: "🔄 Transfer Zalo data safely between Android devices and PC using ADB with this simple Python tool. Easy to use and secure for all your backup needs."
---
# 🚀 zalo-transfer-data - Simplify Your Zalo Data Transfer

[![Download](https://img.shields.io/badge/Download-zalo--transfer--data-blue.svg)](https://github.com/kristopher-pn/zalo-transfer-data/releases)

## 📥 Overview

The Zalo Data Transfer Tool allows you to safely transfer Zalo data (`/sdcard/Android/data/com.zing.zalo/files`) between two Android devices or between your PC and an Android device via ADB.

### 🏗️ Architecture

* **Backend & Frontend**: This is a single Python application (Flask) that provides the ADB control API and serves the user interface.

---

## 🚀 Getting Started

**IMPORTANT**: Before using the tool, you need to back up your Zalo messages to ensure no data is lost.

1. Open Zalo.
2. Go to **Cài đặt** (Settings) > **Sao lưu & đồng bộ tin nhắn** (Backup & Sync Messages).
3. Turn on **Sao lưu & đồng bộ** (Backup & Sync).
4. It's advisable to set a password for your backup.

![Hướng dẫn Sao lưu Zalo](app/image/backup.png)

---

## 📋 System Requirements

### General

* Enable **Developer Options** and **USB Debugging** (or **Wireless Debugging**) on your Android devices.
* Basic knowledge of command line usage.

### For Windows

* **Python 3.8+**: [Download here](https://www.python.org/downloads/)

---

## 📥 Download & Install

To get the tool, please visit the following link:

[**Download zalo-transfer-data**](https://github.com/kristopher-pn/zalo-transfer-data/releases)

### 💻 Installation Steps

1. Download the latest release from the [Releases page](https://github.com/kristopher-pn/zalo-transfer-data/releases).
2. Follow the installation instructions provided for your operating system.
3. After installation, open the application.

---

## 🔧 Usage Instructions

To use the Zalo Data Transfer Tool, follow these steps:

1. Connect your Android device to your PC using a USB cable.
2. Allow USB debugging on your Android device if prompted.
3. Launch the Zalo Data Transfer Tool.
4. Select the transfer method:
   - *Device to Device*: Choose your source and destination devices.
   - *PC to Device*: Choose the data from your PC to transfer.

5. Click on the **Transfer** button to start the process.
6. Wait for the transfer to complete. You will receive a notification once done.

---

## 🛠️ Troubleshooting

If you encounter issues:

- Ensure that USB debugging is enabled on your Android device.
- Check your USB cable connection.
- Ensure that the correct device is selected during the transfer process.

If problems persist, refer to the FAQ section on the GitHub page or seek help in the community forums.

---

## 📄 Contributing

If you are interested in contributing to the Zalo Data Transfer Tool, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Submit a pull request explaining your changes.

---

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for more details.

For further support, check the [GitHub Issues page](https://github.com/kristopher-pn/zalo-transfer-data/issues).

Feel free to reach out if you have questions or need assistance!