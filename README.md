# FaceTrace-New

AI-driven suspect face generation and matching system for forensic use.

## Repository Link

https://github.com/Anandak9074/FaceTrace-New

---

# Overview

FaceTrace-New helps convert witness descriptions into facial sketches and realistic face images using AI, NLP, and generative models. The project supports both text and voice input and compares generated faces against a database of stored records.

---

# Features

- Text and voice-based suspect description input
- NLP-based facial feature extraction
- AI sketch generation
- Realistic face generation
- Database matching and ranked results
- API integration using `.env`
- Frontend and backend integration
- Batch file execution support

---

# Tech Stack

- Python
- React / JavaScript
- AI / ML Models
- NLP
- Database Integration

---

# Clone Repository

```bash
git clone https://github.com/Anandak9074/FaceTrace-New.git
cd FaceTrace-New
```

---

# Setup Instructions

## 1. Create Virtual Environment

```bash
python -m venv venv
```

---

## 2. Activate Virtual Environment

### CMD

```bash
venv\Scripts\activate
```

### PowerShell

```bash
.\venv\Scripts\Activate.ps1
```

Alternative activation command:

```bash
& "c:\Users\swath\Desktop\major project\Forensic-sketch\venv\Scripts\Activate.ps1"
```

If PowerShell blocks execution:

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then activate again.

---

## 3. Upgrade pip

```bash
python -m pip install --upgrade pip
```

---

## 4. Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

## 5. Install protobuf

```bash
pip install protobuf==3.20.3
```

---

## 6. Install Frontend Dependencies

```bash
npm install
```

---

# Environment Variables

Create a `.env` file in the root directory.

Example:

```env
API_KEY=your_api_key
TOKEN=your_token
SECRET_KEY=your_secret_key
```

Paste all required API tokens and keys inside the `.env` file for the APIs and project features to work correctly.

Important:
- Do NOT upload `.env` to GitHub
- Keep API tokens private
- `.env` should remain local

---

# Run Project

After completing all setup steps:

```bash
.\run_project.bat
```

This is the final command used to run the complete project.

---

# Full Setup Order

1. Clone repository

```bash
git clone https://github.com/Anandak9074/FaceTrace-New.git
```

2. Enter project folder

```bash
cd FaceTrace-New
```

3. Create virtual environment

```bash
python -m venv venv
```

4. Activate virtual environment

```bash
venv\Scripts\activate
```

OR for PowerShell:

```bash
.\venv\Scripts\Activate.ps1
```

OR

```bash
& "c:\Users\swath\Desktop\major project\Forensic-sketch\venv\Scripts\Activate.ps1"
```

5. Upgrade pip

```bash
python -m pip install --upgrade pip
```

6. Install Python requirements

```bash
pip install -r requirements.txt
```

7. Install protobuf

```bash
pip install protobuf==3.20.3
```

8. Install npm packages

```bash
npm install
```

9. Create `.env` file

10. Paste API keys and tokens into `.env`

11. Run the project

```bash
.\run_project.bat
```

---

# Project Structure

```text
FaceTrace-New/
│
├── backend/
├── frontend/
├── models/
├── data/
├── venv/
├── .env
├── requirements.txt
├── package.json
├── run_project.bat
└── README.md
```

---

# Troubleshooting

## Python Dependency Error

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

## npm Error

```bash
npm install
```

---

## PowerShell Activation Error

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

---

# Important Notes

- Make sure Python and Node.js are installed before setup.
- Activate the virtual environment before installing Python packages.
- Ensure `.env` contains valid API tokens before running the project.
- Keep all sensitive keys private.
- Run all commands inside the project root directory.

---

# Author

Anandak9074
