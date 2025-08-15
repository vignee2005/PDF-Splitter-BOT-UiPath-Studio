**PDF Splitter BOT – UiPath Studio**

This project is an automated **PDF document classification and splitting bot** built using **UiPath Studio**. It is designed to process a multi-page PDF containing different types of documents — **Invoices**, **Receipts**, and **Clinic Bills** — and automatically classify and split them into separate files.

### **Key Features**

* **Automated PDF Reading:** Extracts text and data from multi-page PDF files.
* **Document Type Identification:** Uses keyword-based or pattern-based logic to detect the type of each page (Invoice, Receipt, or Clinic Bill).
* **Smart Splitting:** Splits the original PDF into individual pages or sets of pages based on document type.
* **Organized Output:** Saves each classified PDF page into dedicated folders (`Invoices`, `Receipts`, `ClinicBills`).
* **Error Handling:** Handles empty pages, unrecognized documents, and missing data gracefully.

### **Workflow Overview**

1. **Read PDF File** → Extract text from each page using UiPath’s PDF activities.
2. **Identify Document Type** → Apply string matching or regex patterns to detect keywords (e.g., "Invoice No", "Receipt", "Clinic").
3. **Split PDF Pages** → Separate pages according to identified document type.
4. **Save to Folders** → Store split files in their respective directories for easy retrieval.

### **Applications**

* Accounting & Finance document processing.
* Medical and healthcare bill management.
* Bulk document archiving and classification.
