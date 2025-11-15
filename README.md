

# **AI Invoice Automation (n8n + OCR + Gemini)**

This project automates invoice processing using **n8n**, **Google Drive**, **OCR**, and **Google Gemini**.
Invoices uploaded to the *Unprocessed* folder are automatically read, converted to text, structured into JSON, saved to Google Sheets, and moved to the *Processed* folder.

### **Features**

* Auto-detect new invoices in Google Drive
* OCR text extraction (JPG/PNG/PDF)
* AI-based data extraction using Gemini
* Save structured data to Google Sheets
* Auto-archive processed files

### **Workflow Steps**

1. Detect file in Google Drive
2. Convert to Base64
3. OCR text extraction
4. Gemini extracts invoice fields
5. Append data to Google Sheet
6. Move invoice to Processed folder

### **Extracted Fields**

* Vendor
* Invoice Number
* Date
* Amount
* Tax
* Currency

---

If you want, I can turn this into a **ready-to-upload README.md**.
