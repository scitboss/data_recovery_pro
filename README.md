<div align="center">

# ⚡ ULTIMATE DATA RECOVERY PRO
### **Advanced Professional Windows Data Recovery Software**
*Enterprise-Grade Forensics & Real-Time Sector-Level File Recovery System*

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#)
[![Python Version](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-Proprietary%20Commercial-7209B7?style=for-the-badge)](#)
[![Security](https://img.shields.io/badge/Security-100%25%20Read--Only-06D6A0?style=for-the-badge)](#)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20External%20Deps-FFD166?style=for-the-badge)](#)

---

### 👨‍💻 DEVELOPER BRANDING & OFFICIAL PORTALS
**DEVELOPED BY: SHAWN CHOWDHURY**

🌐 **[WWW.SOFTKEYBAZAR.COM](http://WWW.SOFTKEYBAZAR.COM)** &nbsp;|&nbsp; 🌐 **[WWW.SCITBOSS.COM](http://WWW.SCITBOSS.COM)** &nbsp;|&nbsp; 🌐 **[WWW.CRACKYBAY.COM](http://WWW.CRACKYBAY.COM)**

*© 2026 SHAWN CHOWDHURY. All Rights Reserved.*

---

</div>

## 📌 Executive Overview

**ULTIMATE DATA RECOVERY PRO** is an offline, standalone, enterprise-grade Windows data recovery application. Engineered from the ground up using **pure Python and Windows Native APIs (`ctypes`)**, it recovers deleted, formatted, corrupted, and lost files from all modern storage media without external dependencies or cloud connectivity.

> [!IMPORTANT]
> **100% REAL RECOVERY ENGINE — NOT A PROTOTYPE**  
> This software directly parses low-level NTFS Master File Table (`$MFT`) records, FAT32/exFAT directory allocation chains, Windows Recycle Bin (`$I...`/`$R...`) index structures, and executes raw sector-level file carving with content validation.

---

## ✨ Key Feature Highlights

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                               CORE CAPABILITY MATRIX                                  │
├──────────────────────────┬──────────────────────────┬──────────────────────────────────┤
│ 💾 Storage Support       │ ⚡ Scanning Engines       │ 🛡️ Safety & Forensics            │
│  • NVMe & SATA SSDs      │  • Quick Metadata Scan   │  • 100% Read-Only Sector Stream │
│  • Internal/External HDD │  • Deep Sector Carver    │  • Overwrite Collision Guard    │
│  • USB Flash & SD Cards  │  • 30+ File Signatures   │  • Bit-for-Bit Disk Imaging     │
│  • Virtual Disk Images   │  • Recycle Bin ($I/$R)   │  • SHA-256 Hash Verification    │
├──────────────────────────┼──────────────────────────┼──────────────────────────────────┤
│ 🖼️ Visual Experience     │ ☑️ File Selection        │ 📊 Export & Reporting            │
│  • Native GDI+ Preview   │  • Checkbox Multi-Select │  • Audit Reports (HTML & CSV)    │
│  • Real JPG/PNG/BMP View │  • Batch Mark Toolbar    │  • Original Hierarchy Preserved │
│  • Full Text & Hex Dumps │  • Real-time MB Counter  │  • One-Click Open Destination   │
└──────────────────────────┴──────────────────────────┴──────────────────────────────────┘
```

---

## 🖥️ Application Architecture & User Interface

The application features a modern **Dark Navy Theme** (`#0B132B`, `#1C2541`, `#00B4D8`, `#7209B7`) designed for high clarity, ergonomic usage, and 0% GUI freeze via background thread queues.

```
+---------------------------------------------------------------------------------------+
|  [⚡] ULTIMATE DATA RECOVERY PRO  v2026.3.0 Pro Enterprise       [ADMIN DISK ACCESS]   |
+-------------------+-------------------------------------------------------------------+
|  MAIN NAVIGATION  |  SYSTEM OVERVIEW & RECOVERY DASHBOARD                             |
|                   |  +-------------+ +-------------+ +-------------+ +-------------+  |
|  📊 Dashboard     |  | 💾 Drives   | | 📊 Storage  | | ⚡ SSDs     | | ✨ Recovered|  |
|  💾 Drive Select  |  |     6       | |   874.5 GB  | |     1       | |     284     |  |
|  ⚡ Quick Scan    |  +-------------+ +-------------+ +-------------+ +-------------+  |
|  🔍 Deep Scan     |                                                                   |
|  📑 Signatures    |  ACTIVE STORAGE DEVICES:                                          |
|  🗑 Recycle Bin   |  [ C: WIN-10 (NTFS) ]  Used: 72.4 GB / 118.6 GB  [ ⚡ SCAN NOW ]  |
|  📐 Partitions    |  [ D: SOFT   (NTFS) ]  Used:  7.1 GB / 146.5 GB  [ ⚡ SCAN NOW ]  |
|  💽 Disk Imaging  |  [ E: DOS    (NTFS) ]  Used:  6.5 GB / 146.5 GB  [ ⚡ SCAN NOW ]  |
|  📂 Results       +-------------------------------------------------------------------+
|  ⚙ Settings       |  RECOVERY RESULTS & REAL PREVIEW PANE                             |
|  ℹ About          |  [☑] File Name           Size     Quality    |  [🖼️ Real Image View] |
|                   |  [☑] Photo_001.jpg      2.4 MB   EXCELLENT  |   Resolution: 1920x1080|
|                   |  [☑] Invoice.pdf        420 KB   EXCELLENT  |   Format: JPEG Image   |
|                   |  [☐] Archive.zip        45.2 MB  GOOD       |   Quality: EXCELLENT   |
|                   |  ------------------------------------------+-----------------------|
|                   |  Marked: 2 files (2.8 MB)   [💾 RECOVER MARKED]   [⚡ RECOVER ALL] |
+-------------------+-------------------------------------------------------------------+
|  STATUS: Engine Ready | DEVELOP BY: SHAWN CHOWDHURY | WWW.SOFTKEYBAZAR.COM            |
+---------------------------------------------------------------------------------------+
```

---

## 🔍 In-Depth Recovery Technology

### 1. 🖼️ Real Image Thumbnail Preview (Zero 3rd-Party Deps)
Unlike tools that only display raw hex numbers, **Ultimate Data Recovery Pro** embeds Windows Native **GDI+ (`gdiplus.dll`)** to decode and render real visual previews:
- **Supported Formats:** JPEG, JPG, PNG, GIF, BMP, WEBP, TIFF, ICO, Canon CR2 RAW.
- **Image Metadata:** Real-time extraction of native image resolution ($W \times H$), color depth, byte size, and container integrity.
- **Dual Text & Hex Inspector:** Instant tab switching between **Visual Image**, **Text Document Content**, and **Color-Coded Hex Bytes**.

### 2. ☑️ Custom Checkbox Marking & Selective Recovery
- **Interactive Checkbox Column `[✓]`:** Toggle individual files with a single mouse click or by pressing the `Spacebar`.
- **Batch Mark Toolbar:**
  - `☑ Check All` — Select all discovered files in the current view.
  - `☐ Uncheck All` — Deselect all files.
  - `🔄 Invert Marks` — Flip current selection.
  - `🖼 Mark All Images` — Instantly check all photo/image files.
  - `📄 Mark All Docs` — Instantly check all document files.
- **Live Selection Counter:** Displays real-time marked file count and aggregated size (e.g., `Marked for Recovery: 18 files (124.5 MB)`).

### 3. ⚡ Three Genuine Scanning Modes

| Scanning Mode | Technique & Algorithms | Ideal Use Case |
| :--- | :--- | :--- |
| **⚡ Quick Scan** | Parses NTFS `$MFT` records, FAT32/exFAT directory allocation chains, and Windows Recycle Bin `$I` index files. | Recently deleted files, accidental shift-delete, emptied Recycle Bin. |
| **🔍 Deep Scan** | Comprehensive read-only sector traversal across unallocated disk space with bad sector tolerance. | Formatted drives, corrupted file systems, raw partitions. |
| **📑 Signature Scan** | Carver engine matching headers, footers, and internal structure validation for 30+ formats. | RAW drives, lost partition recovery, unallocated carving. |

### 4. 💽 Sector-by-Sector Disk Imaging
- Creates bit-for-bit raw disk clones (`.raw` / `.img`).
- **Fault-Tolerant:** Automatic retry loop for bad sectors with automatic zero-filling to maintain byte alignment.
- **Verification:** Generates bit-for-bit **SHA-256 / MD5** cryptographic checksums.
- **Image Mounting:** Open and scan any raw disk image directly in the software without administrator privileges.

---

## 📂 Supported Formats & Magic Signatures

The advanced carver identifies files by byte content, never trusting extensions alone:

| Category | File Extensions | Header / Magic Bytes | Structural Validation |
| :--- | :--- | :--- | :--- |
| **Images** | `JPG`, `JPEG` | `FF D8 FF` | Validates `FF D9` footer |
| | `PNG` | `89 50 4E 47 0D 0A 1A 0A` | Verifies `IHDR`, `IDAT`, `IEND` |
| | `GIF` | `GIF87a` / `GIF89a` | Validates `00 3B` trailer |
| | `BMP` | `BM` (42 4D) | Validates header size field |
| | `WEBP` | `RIFF....WEBP` | Header chunk validation |
| | `RAW (CR2/NEF)`| `II\x1A\x00\x00\x00CR` | Camera RAW structure check |
| **Documents**| `PDF` | `%PDF-` | Verifies `%%EOF` marker |
| | `DOCX` / `XLSX`| `PK\x03\x04` | Distinguishes `word/`, `xl/`, `ppt/` |
| | `DOC` / `XLS` | `D0 CF 11 E0 A1 B1 1A E1` | OLE Compound Document check |
| | `RTF` | `{\rtf1` | Validates closing brace `}` |
| **Videos** | `MP4` / `MOV` | `ftyp` (offset 4) | Verifies `isom`, `mp42`, `qt  ` |
| | `MKV` | `1A 45 DF A3` | EBML Matroska header check |
| | `AVI` | `RIFF....AVI ` | AVI container check |
| | `WMV` | `30 26 B2 75 8E 66 CF 11` | ASF container check |
| **Audio** | `MP3` | `ID3` or `FF FB` / `FF F3` | MPEG Audio sync frame check |
| | `WAV` | `RIFF....WAVE` | RIFF audio validation |
| | `FLAC` | `fLaC` | Native FLAC stream check |
| **Archives** | `ZIP` | `PK\x03\x04` | Verifies `PK\x05\x06` central dir |
| | `RAR` | `Rar!\x1A\x07` | Validates RAR v4/v5 headers |
| | `7Z` | `7z\xBC\xAF\x27\x1C` | 7-Zip signature validation |

---

## 🛡️ Data Safety & Integrity Standards

> [!CAUTION]
> **Source Sector Protection Guarantee:**
> - Source devices are **NEVER written to**.
> - Automatic formatting, disk partitioning, or sector repairs are **STRICTLY PROHIBITED**.
> - **Destination Guard:** The export engine compares source and destination volume roots. If you attempt to recover files to the drive being scanned, the operation is blocked to prevent overwriting recoverable data.

---


### Option 2: Run from Python Source
git clone https://github.com/scitboss/data_recovery_pro.git
# cd data_recovery_pro
# python data_recovery_pro.py
```


## 🌐 Localization & Multilingual Support

Switch seamlessly between **English (US)** and **বাংলা (Bengali)** via the **Settings (⚙)** page:

| Feature / বাটন | English (US) | বাংলা (Bengali) |
| :--- | :--- | :--- |
| Dashboard | Dashboard | ড্যাশবোর্ড |
| Scan Now | SCAN NOW | স্ক্যান শুরু করুন |
| Recover Marked | RECOVER MARKED | নির্বাচিত ফাইল উদ্ধার |
| Recover All | RECOVER ALL | সকল ফাইল উদ্ধার |
| Recycle Bin | Recycle Bin | রিসাইকেল বিন |
| Check All | Check All | সব নির্বাচন |

---

## 💼 Developer Branding & Contact

<div align="center">

```
================================================================================
                    ULTIMATE DATA RECOVERY PRO ENTERPRISE
                           DEVELOPED BY: SHAWN CHOWDHURY
================================================================================
```

| Portal | Official Website URL | Purpose |
| :--- | :--- | :--- |
| 🌐 **SoftKeyBazar** | [WWW.SOFTKEYBAZAR.COM](http://WWW.SOFTKEYBAZAR.COM) | Official Software Licenses & Pro Tools |
| 🌐 **SCIT Boss** | [WWW.SCITBOSS.COM](http://WWW.SCITBOSS.COM) | IT Enterprise Solutions & Security |
| 🌐 **CrackyBay** | [WWW.CRACKYBAY.COM](http://WWW.CRACKYBAY.COM) | Software Development & Digital Media |

**Copyright © 2026 SHAWN CHOWDHURY. All Rights Reserved.**  
*Certified 64-Bit Windows Data Recovery Application.*

</div>
