# Insurance Policy Form Processing System 🚀

[![Streamlit App](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://insuranceformextraction123.streamlit.app/)
![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end solution for digitizing insurance policy forms using AI-powered data extraction and validation.



## Table of Contents
- [Features](#features-)
- [Installation](#installation-)
- [Configuration](#configuration-)
- [Usage](#usage-)
- [Supported Fields](#supported-form-fields-)
- [Tech Stack](#technology-stack-)
- [Security](#security-considerations-)
- [Troubleshooting](#troubleshooting-)
- [Contributing](#contributing-)
- [License](#license-)

## Features ✨

### Core Functionality
- **PDF Form Processing**
  - Handles both digital and scanned policy forms
  - Supports multi-page insurance documents
  - In-app PDF preview with zoom capabilities

- **AI Data Extraction**
  - Automated field recognition using Gemini AI
  - Handles typed and handwritten form entries
  - Context-aware date/value parsing

- **Data Validation Suite**
  - Four-step interactive review process:
    1. Policyholder Details
    2. Vehicle Specifications
    3. Coverage Selection
    4. Policy Dates & Signatures
  - Real-time formatting assistance
  - Cross-field validation rules

- **Compliance Features**
  - Audit trail of data modifications
  - Signature presence verification
  - Data integrity checks

### Output Generation
- Excel reports with multiple sheets:
  - Policy Summary
  - Vehicle Details
  - Coverage Breakdown
  - Compliance Documentation
- Standardized formats for enterprise systems
- Auto-generated timestamps for audit purposes

## Installation 🛠️

### Prerequisites
- Python 3.9+
- Google Gemini API key
- Poetry (recommended)

### Setup
```bash
# Clone repository
git clone https://github.com/yourusername/insurance-form-processor.git
cd insurance-form-processor

# Install dependencies (using poetry)
poetry install

# Alternative using pip
pip install -r requirements.txt

Configuration

1. Get a Gemini API key
2. Create .env:

GEMINI_API_KEY=your_key_here

Usage

1. Start the app:

2. Workflow:

Upload PDF form

Click Process Document

Validate data in 4 steps

Export to Excel

3. Technology Stack

Framework: Streamlit

AI Engine: Google Gemini

Data Processing: Pandas, Openpyxl

PDF Handling: Base64, Tempfile

4. Troubleshooting
"Invalid PDF" Error: Ensure files are unencrypted and <10MB

Empty Excel Output: Check for valid signatures/dates in the form

5. License

MIT License - See LICENSE
