# 🚀 Qexur CA — Evaluation & User Quick-Start Guide

This guide provides step-by-step instructions for installing, activating, and evaluating the **Qexur CA Desktop AI Financial Document Extraction & Forensic Audit Platform**.

---

## 📋 Step 1: Installation

1. Download the Windows installer:
   * **[Download Qexur_CA_Setup_Installer.exe](https://github.com/ujjalrajkonwar/qexur-ca/releases/download/v2.0.0/Qexur_CA_Setup_Installer.exe)**
2. Run `Qexur_CA_Setup_Installer.exe` on any standard Windows 10/11 64-bit computer (minimum 8 GB RAM supported).
   > **Note on Windows SmartScreen:** Because this is a private, freshly compiled pre-acquisition evaluation build (prior to buyer commercial EV code-signing), Windows SmartScreen may show an unrecognized app prompt. Simply click **"More info" ➔ "Run anyway"** to proceed.
3. Follow the setup wizard and launch **Qexur CA**.

---

## 🔑 Step 2: License Activation

1. When launched for the first time, the **Hardware-Locked DRM Activation Modal** will appear.
2. Enter the **Evaluation License Key** provided in your private due-diligence email.
3. Click **Activate License**.
4. The application will cryptographically bind to your local hardware and activate immediately **100% offline (no internet connection required)**.

---

## 🤖 Step 3: One-Time AI Model Setup

1. On initial startup, the **Model Management Wizard** will prompt you to initialize your local AI engine.
2. Select your preferred tier:
   * ⚡ **Speed Tier (Recommended):** ~810 MB GGUF download (`Qwen 3.5 0.8B Instruct Q8_0`). Best for 8GB RAM laptops and ultra-fast high-volume batch processing.
   * 🧠 **Standard Tier:** ~2.8 GB GGUF download (`Gemma 4 E2B QAT`). Best for 16GB+ RAM workstations requiring deep forensic cross-examination.
3. Click **Install Model**. The software will stream the weights directly from Hugging Face into your local application cache.
4. *Once installed, the model runs 100% locally and never requires an internet connection again.*

---

## 📄 Step 4: Testing the Extraction Engine (Tab 1)

1. Navigate to the **Extraction Engine** tab in the sidebar.
2. Drag and drop any sample European/international invoices, receipts, or PDF bills into the dropzone.
3. Observe real-time data extraction:
   * **Supplier / Vendor Name** (automatically filtered for legal corporate suffixes).
   * **Invoice Number, Issue Date, Due Date**.
   * **EU VAT ID / Greek AFM Checksum Status** (Mod-11 verified).
   * **ISO 7064 IBAN & BIC/SWIFT** (Mod-97 verified).
   * **Multi-Rate Line Items:** Descriptions, quantities, unit prices, and tax percentages.
   * **Mathematical Reconciliation:** Green checkmark for verified arithmetic balance (`Net + VAT == Total`).
4. Click **Export to Excel (.xlsx)** to generate a 3-sheet audit workpaper (`Detailed_Invoices`, `ERP_Journal_Entries`, `VAT_Tax_Summary`).

---

## 🔍 Step 5: Testing the Local RAG Vault (Tab 2)

1. Navigate to the **Local RAG Vault** tab in the sidebar.
2. Drag & drop a batch of 10 to 150+ financial documents into the vault.
3. Type natural language audit queries into the chat input:
   * *"List all unique vendors found across the documents in a clean summary table."*
   * *"Are there any duplicate invoices or repeated invoice numbers across the uploaded files? Provide the total duplicate financial risk."*
   * *"Generate a multi-currency ledger reconciliation breaking down Net, VAT, and Gross spend across all currencies."*
   * *"Identify all suppliers offering early payment cash discounts (Skonto) and calculate our total liquid savings."*
4. Test the **1-Click Spreadsheet Toolbar**:
   * Click **`📊 Export Excel (.xlsx)`** on any table response to instantly download an auto-formatted `.xlsx` workbook.
   * Click **`📄 CSV`** to export a UTF-8 BOM CSV file for universal spreadsheet compatibility.
   * Click **`📋 Copy Table`** to copy Tab-Separated Values (TSV) directly to your clipboard for instant pasting into Excel or Google Sheets.

---

## 🛡️ Step 6: Testing Anti-Fraud & Credit Notes

* **Credit Notes:** Drop a credit note PDF and verify that the gross amount is automatically assigned a negative value and mathematically subtracted from your total expenditure.
* **Duplicate Invoices:** Drop duplicate copies of an invoice (e.g. `invoice_2001321.pdf` and `invoice_2001321 (1).pdf`) and query the RAG Vault to observe exact excess financial exposure calculations.

---

## 💬 Support & Handover Questions

If you encounter any questions during your evaluation or require custom ERP integration schemas, please reach out directly to the founder.
