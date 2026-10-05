<p align="center">
  <img src="docs/stirling.png" width="100" alt="Stirling PDF Logo - Open Source PDF Processing Platform">
</p>

<h1 align="center">Stirling PDF: Powerful Self-Hosted & Open-Source PDF Platform</h1>

<p align="center">
  <b>Complete Local PDF Processing • Privacy-First Architecture • 50+ Built-in PDF Tools</b>
</p>

---

## 🚀 Overview

**Stirling PDF** is a comprehensive, self-hosted PDF management and editing suite designed for maximum privacy and automation. Process, convert, edit, and secure your confidential documents locally without transmitting data to external third-party cloud services.

Whether deployed as a **standalone desktop application**, a **web service in Docker**, or integrated via **REST API**, Stirling PDF provides enterprise-grade document operations directly within your infrastructure.

---

## ✨ Key Features & Capabilities

### 📄 Advanced PDF Editing & Conversion
* **Full Editing Suite**: Merge, split, rotate, reorder, and remove PDF pages instantly.
* **Document Conversion**: Convert PDFs to and from Word, Images (PNG/JPG), HTML, TXT, and PDF/A format.
* **OCR Text Recognition**: Extract searchable text from scanned documents in multi-language setups.
* **Compression & Optimization**: Reduce PDF file size without sacrificing visual quality.

### 🛡️ Privacy, Security & Compliance
* **100% Local Processing**: Keep sensitive documents secure behind your firewall.
* **Digital Signatures & Watermarks**: Add custom watermarks, stamps, and cryptographic signatures.
* **Redaction & Protection**: Permanently sanitize sensitive data, password-protect, or unlock PDFs.

### ⚙️ Automation & Integration
* **REST API Access**: Seamlessly integrate PDF processing into custom software and scripts.
* **No-Code Automation Workflows**: Set up automated document pipelines directly from the UI.
* **Multi-Language Support**: Fully localized interface supporting 40+ global languages.

---

## ⚡ Quick Start with Docker

Launch Stirling PDF locally in seconds using Docker:

```bash
docker run -d -p 8080:8080 --name stirling-pdf stirlingtools/stirling-pdf:latest
