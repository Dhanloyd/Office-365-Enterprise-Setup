<a href="https://buymeacoffee.com/abdullaherturk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
  
# Office 365 Enterprise Automated Offline/Online Installer 

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-Batch_&_PowerShell-blue?style=for-the-badge)

[![made-for-windows](https://img.shields.io/badge/Made%20for-Windows-00A4E3.svg?style=flat&logo=microsoft)](https://www.microsoft.com/)
[![Open Source?](https://img.shields.io/badge/Open%20source%3F-Of%20course%21%20%E2%9D%A4-009e0a.svg?style=flat)](https://github.com/abdullah-erturk/Office-365-Enterprise-Setup)

![sample](https://raw.githubusercontent.com/abdullah-erturk/Office-365-Enterprise-Setup/refs/heads/main/preview.jpg)

---

## Link:

[![Stable?](https://img.shields.io/badge/Release-v1.svg?style=flat)](https://codeload.github.com/abdullah-erturk/Office-365-Enterprise-Setup/zip/refs/heads/main)

<details>
<summary><strong>Türkçe Tanıtım</strong></summary>

---
## 📌 Office 365 Enterprise Otomatik Çevrimdışı / Çevrimiçi Kurulum Aracı (PowerShell Betiği)

Bu powershell uygulaması, Microsoft Office 365 kurulumunu hem çevrimdışı (offline) hem de çevrimiçi (online) olarak otomatikleştirmek için hazırlanmış gelişmiş bir PowerShell betiğidir.
Kullanıcıların kurmak istediği mimariyi (32-bit / 64-bit) ve dili seçmesine olanak tanır. Betik, kurulum dosyalarının bulunduğu dizini otomatik algılar ve temiz bir Office kurulumu yapar.

## ✅ Öne Çıkan Özellikler

✔️ Powershell GUI arayüzü için Türkçe ve İngilizce dil desteği

✔️ İsteğe bağlı uygulama seçimi

✔️ 43 farklı dilde kurulum desteği

✔️ Ek ürünler: Visio Pro - Project Pro

✔️ Herhangi bir klasör, DVD/ISO, USB veya ağ üzerinden offline kurulum

✔️ Office Deployment Tool ile online ve offline kurulum

✔️ 32-bit / 64-bit otomatik algılama

✔️ Dil klasörünü otomatik algılama (tr-TR, en-US vb.)

✔️ Sessiz kurulum (silent install) seçeneği

✔️ Kurulum süresince ilerleme çubuğu

✔️ Kurulum sonrası doğrulama

✔️ Yönetici yetkisi kontrolü

✔️ Hata yakalama ve loglama

📂 Klasör Yapısı
```
│   Office365_Install.bat
│   autorun.inf
└───Office
    │   Check.bat
    │   ico.ico
    │   o365.ps1
    │   setup.exe
    └───Office365
        ├───32
        │   └───tr-TR (veya EN-US vb.)
        │       └───Office
        │           └───Data
        │               │   v32.cab
        │               │   v32_16.xxxxx.xxxxx.cab
        │               │
        │               └────────────────────────16.xxxxx.xxxxx
        └───64
            └───tr-TR
                └───Office
                    └───Data
                        │   v64.cab
                        │   v64_16.xxxxx.xxxxx.cab
                        │
                        └────────────────────────16.xxxxx.xxxxx
```
## 🚀 Kullanım

Yönetici olarak çalıştırın. (Office365_Install.bat dosyası sayesinde otomatik yönetici olarak çalıştırılır)

Mimari ve dil seçin.

Kurulum otomatik başlatılır. (online veya offline)

## 🧩 Gereksinimler

Windows 10 / Windows 11 / Server (Minimum Server versiyonu: Windows Server 2012 R2)

Yönetici yetkisi

PowerShell 5.1 veya üstü

</details>

---

<details>
<summary><strong>English Description</strong></summary>

---

## 📌 Office 365 Enterprise Automated Offline/Online Installer (PowerShell Script)

This powershell application is a fully automated, user-friendly PowerShell script designed to install Microsoft Office 365 in both offline and online modes.
It allows users to choose the preferred architecture (32-bit or 64-bit) and the installation language dynamically. The script automatically detects the correct folder structure and initiates a clean Office deployment using your pre-downloaded installation files.

## ✅ Key Features

✔️ Turkish and English language support for the powershell GUI interface

✔️ Optional application selection

✔️ Installation support in 43 different languages

✔️ Additional products: Visio Pro - Project Pro

✔️ Supports offline installation from any folder, DVD/ISO, USB, or network path

✔️ Online and offline installation with Office Deployment Tool

✔️ Automatic detection of architecture (x86 / x64)

✔️ Automatic detection of language folder (e.g., tr-TR, en-US, etc.)

✔️ Clean and silent installation option

✔️ Progress bar during installation

✔️ Post-installation verification

✔️ Admin privilege auto-check

✔️ Error handling and detailed logs

## 📂 Folder Structure
```
│   Office365_Install.bat
│   autorun.inf
└───Office
    │   Check.bat
    │   ico.ico
    │   o365.ps1
    │   setup.exe
    └───Office365
        ├───32
        │   └───tr-TR (or en-US etc.)
        │       └───Office
        │           └───Data
        │               │   v32.cab
        │               │   v32_16.xxxxx.xxxxx.cab
        │               │
        │               └────────────────────────16.xxxxx.xxxxx
        └───64
            └───tr-TR
                └───Office
                    └───Data
                        │   v64.cab
                        │   v64_16.xxxxx.xxxxx.cab
                        │
                        └────────────────────────16.xxxxx.xxxxx
```
## 🚀 Usage

Run as Administrator. (Automatically runs as administrator thanks to the Office365_Install.bat file)

Choose architecture + language.

Installation starts automatically. (online or offline)

## 🧩 Requirements

Windows 10 / 11 / Server (Minimum Server version: Windows Server 2012 R2)

Administrator privileges

PowerShell 5.1 or higher

</details>


