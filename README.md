# 🏛️ Qexur CA — Desktop AI for Financial Document Extraction & Forensic Audit

[![Download Windows x64](https://img.shields.io/badge/Download-Windows_x64_Installer-3b82f6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ujjalrajkonwar/qexur-ca/releases/download/v2.0.0/Qexur_CA_Setup_Installer.exe)
[![Version](https://img.shields.io/badge/Release-v2.0.0-10b981?style=for-the-badge)](https://github.com/ujjalrajkonwar/qexur-ca/releases/tag/v2.0.0)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25_Air--Gapped_Local_AI-8b5cf6?style=for-the-badge)](https://github.com/ujjalrajkonwar/qexur-ca)
[![Tech Stack](https://img.shields.io/badge/Stack-React_19_|_Tauri_v2_|_Rust-f97316?style=for-the-badge)](https://github.com/ujjalrajkonwar/qexur-ca)

---

## 📌 Overview

**Qexur CA** is a native, offline-first desktop AI application engineered specifically for Chartered Accountants (CAs), statutory auditors, and accounting firms. It automates financial document data extraction, arithmetic reconciliation, anti-fraud auditing, and multi-currency ledger consolidation without ever transmitting sensitive client financial data to cloud APIs.

---

## 📥 Direct Downloads

| Package | Direct Download Link | Target Platform | File Size |
| :--- | :--- | :--- | :--- |
| 📦 **Windows Setup Installer** | **[Download Qexur_CA_Setup_Installer.exe](https://github.com/ujjalrajkonwar/qexur-ca/releases/download/v2.0.0/Qexur_CA_Setup_Installer.exe)** | Windows 10 / 11 (64-bit) | ~134 MB |
| 🏷️ **GitHub Releases Portal** | **[View All Releases & Assets](https://github.com/ujjalrajkonwar/qexur-ca/releases/tag/v2.0.0)** | Official Release Hub | — |

---

## 💎 Core Capabilities

### 1. 🤖 Dual-LLM Local AI Engine (100% Air-Gapped)
* Executes Large Language Models locally on consumer hardware via an embedded `llama.cpp` GGUF runtime.
* **Speed Tier (~810 MB):** Qwen 3.5 0.8B Instruct (Q8_0 Quantized) for ultra-fast extraction on standard 8GB RAM laptops.
* **Standard Tier (~2.8 GB):** Gemma 4 E2B QAT (Q4_K_M Quantized) for deep forensic cross-examination on 16GB+ workstations.
* **Zero API Fees:** $0.00/month recurring cloud or LLM inference costs.

### 2. 💶 European & International Statutory Compliance
* **EU VAT Numbers:** Comprehensive regex validation across 20+ EU member states (`DE`, `FR`, `IT`, `NL`, `AT`, `ES`, `PL`, `SE`, `BE`, `IE`, etc.).
* **Greek AFM Numbers:** Statutory **Modulo-11 Checksum Validator** for Hellenic Tax Administration (IAPR/ΑΑΔΕ).
* **IBAN / BIC:** ISO 7064 **Modulo-97 Checksum Verification** for European bank routing.
* **Multi-Currency Ledgers:** Strict segregation for `EUR (€)`, `CHF`, `GBP (£)`, `PLN (zł)`, `SEK (kr)`, and `USD ($)`.
* **Automatic Credit Note Deductions:** Real-time negative sign balance mapping and ledger subtraction.

### 3. 🔍 Local RAG Vault & Forensic Audit Suite
* **Unique Vendor Spend Concentration:** Consolidates all supplier-level net, tax, and gross expenditures across hundreds of documents.
* **Anti-Fraud Duplicate Detection:** Flags identical invoice numbers uploaded across separate files and computes exact excess disbursement risk.
* **1-Click Native Excel (.xlsx) & CSV Export:** Generates auto-column-width spreadsheets with dynamic sheet naming and UTF-8 BOM CSV exports.

### 4. 🛡️ Cryptographic Hardware-ID (HWID) DRM
* Built-in native Rust licensing engine (`licensing.rs` + `hardware_id.rs`) that cryptographically binds licenses to motherboard UUIDs.
* 100% offline license key validation with zero external telemetry or server pings.

---

## 💻 System Requirements

| Specification | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit) / Windows 11 (64-bit) | Windows 11 (64-bit) |
| **Memory (RAM)** | 8 GB RAM (CPU Mode enabled) | 16 GB RAM |
| **Processor** | Intel Core i5 / AMD Ryzen 5 (AVX2 supported) | Intel Core i7 / AMD Ryzen 7 |
| **Graphics (GPU)** | Not required (CPU mode default) | NVIDIA GTX/RTX GPU (2GB–6GB VRAM) |
| **Disk Space** | ~1.5 GB total (App + Local GGUF Model) | 3 GB Free Space |
| **Internet** | Only required once for initial GGUF download | 100% Offline / Air-Gapped thereafter |

---

## 📚 Technical Documentation

* 🏗️ **[Technical Architecture & Deep-Tech Blueprint (architecture.md)](./architecture.md)**
* 🚀 **[Step-by-Step Evaluation & User Guide (use-me.md)](./use-me.md)**

---

## 🔑 License Activation

License keys are issued privately for enterprise clients and due-diligence prospective buyers.  
*For evaluation access, please refer to the private evaluation key provided in your due-diligence correspondence.*
