# DocuLens

### Ask Your Documents Anything. See the Proof.

DocuLens is a multimodal document intelligence web application developed for the **HNX26PSI01 – Multimodal Document Intelligence** problem statement.

The system is designed to help users understand information distributed across documents containing text, tables, charts, graphs, images, and scanned pages.

Instead of providing only an answer, DocuLens follows an **evidence-first approach** by connecting answers to relevant document information.

---

## 1. Problem Statement

### HNX26PSI01 – Multimodal Document Intelligence

Documents often contain important information in different formats such as:

- Text
- Tables
- Charts
- Graphs
- Images
- Scanned pages

Traditional document search may not understand information contained in visual elements such as charts and tables.

The goal of DocuLens is to provide a user-friendly system for asking natural-language questions about documents and presenting the answer together with supporting evidence.

---

## 2. What the Project Does

DocuLens provides an interactive document analysis interface with the following capabilities:

- PDF document processing
- Text extraction from PDF files
- OCR support for scanned documents
- Table-oriented information analysis
- Chart and graph analysis
- Natural-language document questions
- Document comparison
- Evidence-oriented answers
- Document and page references
- Interactive document viewer
- Analysis dashboard
- Comparison dashboard
- Demonstration mode

The project follows this general workflow:

  text
Document
   ↓
Document Processing
   ↓
Text / OCR / Visual Information
   ↓
Evidence Identification
   ↓
Question Analysis
   ↓
Answer
   ↓
Supporting Evidence


## 3. Technologies, Libraries and Models Used

### Technologies

* HTML5
* CSS3
* JavaScript

### Libraries

* **PDF.js** – PDF document processing and text extraction
* **Tesseract.js** – OCR for scanned document content
* **Chart.js** – Data visualization
* **Bootstrap Icons** – User interface icons

### AI / Models

The current prototype uses **Tesseract.js** for OCR processing.

No external LLM API or separately hosted AI model is required to run the current browser-based prototype.

---

## 4. Installation and Dependencies

The current version is a browser-based prototype.

No Python environment, Node.js server, database, or backend server is required to run the current version.

The required JavaScript libraries are loaded through CDN links in `index.html`.

### Requirements

* Google Chrome, Microsoft Edge, or another modern web browser
* Internet connection for CDN-based libraries
* PDF documents for testing

---

## 5. How to Install

### Step 1 – Clone the Repository

Clone the GitHub repository:

```bash
git clone https://github.com/neriahmaliseb/DocuLens.git
```

### Step 2 – Open the Project Folder

```bash
cd DOCLENS
```

### Step 3 – Open the Application

Open:

```text
index.html
```

in a modern web browser.

No additional package installation is required for the current prototype.

---

## 6. How to Run the System

### Option 1 – Direct Browser Run

1. Open the project folder.
2. Double-click `index.html`.
3. The DocuLens application will open in the browser.

### Option 2 – Using VS Code

1. Open the `DOCLENS` folder in Visual Studio Code.
2. Open `index.html`.
3. Run the file using a local development server such as Live Server if required.

The DocuLens interface will then be available in the browser.

---

## 7. How to Use the System

### Step 1

Open the DocuLens application.

### Step 2

Go to the **Documents** section.

### Step 3

Add or process a PDF document.

### Step 4

Go to the **Chat** section.

### Step 5

Enter a natural-language question about the document.

### Step 6

View the generated analysis.

### Step 7

Open the **Evidence** section to inspect the supporting document information.

### Step 8

Use the **Analysis** and **Compare** sections to view numerical comparisons and visualizations.

---

## 8. Example Question

A representative question for the demonstration is:

```text
Compare production efficiency between Q2 and Q4.
```

The example data contains:

```text
Q2 efficiency = 72%

Q4 efficiency = 84%
```

The improvement is:

```text
84 - 72 = 12 percentage points
```

Percentage increase:

```text
((84 - 72) / 72) × 100 = 16.67%
```

Therefore:

```text
Q2 → 72%
Q4 → 84%
Improvement → 12 percentage points
Percentage increase → 16.67%
```

---

## 9. How to Reproduce the Demonstrated Results

Follow these steps to reproduce the demonstration:

### Step 1

Open `index.html` in a modern web browser.

### Step 2

Navigate to the **Chat** or **Demo** section.

### Step 3

Enter the following question:

```text
Compare production efficiency between Q2 and Q4.
```

### Step 4

View the generated result.

### Step 5

Open the **Evidence** section to inspect the supporting information.

### Step 6

Open the **Compare** or **Analysis** section to view the numerical comparison and visualization.

The demonstrated calculation is:

```text
Q2 = 72%

Q4 = 84%

Difference = 84 - 72
           = 12 percentage points

Percentage increase
= ((84 - 72) / 72) × 100
= 16.67%
```

---

## 10. Evidence-First Approach

DocuLens is designed around the principle:

> **Don't just give the answer. Show the proof.**

The system follows this workflow:

```text
Question
   ↓
Evidence
   ↓
Analysis
   ↓
Verification
   ↓
Answer
```

The goal is to make important document-based answers easier for users to understand and verify.

The system is designed to associate important information with relevant document and page information where available.

---

## 11. Multimodal Document Processing

DocuLens is designed to work with multiple types of document information:

```text
Documents
   │
   ├── Text
   │
   ├── Tables
   │
   ├── Charts
   │
   ├── Graphs
   │
   ├── Images
   │
   └── Scanned Pages
```

The current prototype provides browser-based PDF processing, text extraction, OCR support, analysis, and visualization.

---

## 12. Project Structure

```text
DOCLENS/
│
├── index.html
│
└── README.md
```

The current prototype is intentionally lightweight and runs primarily in the browser.

---

## 13. Current MVP Scope

The current MVP includes:

* Interactive DocuLens interface
* PDF document processing
* Text extraction
* OCR support
* Evidence-oriented workflow
* Natural-language question interface
* Document comparison
* Analysis dashboard
* Data visualization
* Interactive document viewer
* Demonstration workflow

---

## 14. Future / Stretch Features

The following features can be added in future versions:

* Advanced multimodal vision-language models
* Advanced chart understanding
* Advanced table extraction
* Retrieval-Augmented Generation (RAG)
* Semantic document retrieval
* Cross-document reasoning
* Improved evidence bounding boxes
* Advanced confidence scoring
* Backend API
* Database integration
* User authentication
* Multilingual OCR
* Improved scanned-document processing
* More document formats

---

## 15. Limitations

The current submission is a browser-based prototype.

Document and OCR processing accuracy can depend on:

* Document quality
* Scan quality
* Image resolution
* Text clarity
* Page layout
* Rotation
* Image compression
* Lighting conditions

Difficult or damaged scanned documents may produce lower-quality OCR results and may require manual verification.

Advanced multimodal reasoning and backend-based retrieval are planned for future development.

---

## 16. Dependencies Summary

| Component          | Technology              |
| ------------------ | ----------------------- |
| User Interface     | HTML5, CSS3, JavaScript |
| PDF Processing     | PDF.js                  |
| OCR                | Tesseract.js            |
| Data Visualization | Chart.js                |
| Icons              | Bootstrap Icons         |
| Runtime            | Modern Web Browser      |

---

## 17. System Requirements

### Minimum

* Modern Windows, Linux, or macOS system
* Modern web browser
* Internet connection
* PDF documents for testing

### Recommended

* Google Chrome or Microsoft Edge
* 4 GB or more RAM

---

## 18. Hackathon Information

### Problem Statement

**HNX26PSI01 – Multimodal Document Intelligence**

### Domains

* Generative AI
* Vision-Language Models
* RAG
* Document AI

### Project Name

**DocuLens**

### Tagline

**Ask Your Documents Anything. See the Proof.**

---

## 19. Conclusion

DocuLens provides an evidence-oriented approach to multimodal document intelligence.

The project focuses on helping users ask questions about complex documents and understand not only the answer, but also the supporting evidence behind the answer.

The long-term goal is to combine document processing, OCR, visual understanding, multimodal reasoning, numerical verification, and evidence tracing into a reliable document intelligence system.

---

## 20. Team

**Project:** DocuLens

**Problem Statement:** HNX26PSI01 – Multimodal Document Intelligence


