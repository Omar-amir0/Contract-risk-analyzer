# Contract Risk Analysis System

An AI-powered system that analyzes contracts, identifies potential risks, and retrieves relevant legal and organizational policies using Retrieval-Augmented Generation (RAG).

## 1. Project Setup

### Prerequisites

- Python 3.10 or later
- Git
- VS Code (recommended)

### 2. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd contractRisk
```

### 3. Create a Virtual Environment

Create a new virtual environment:

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows (Command Prompt / PowerShell):**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

Make sure your virtual environment is activated, then run:

```bash
pip install -r requirements.txt
```

### 6. Configure VS Code

1. Open the project folder in VS Code.
2. Press `Ctrl + Shift + P`.
3. Search for `Python: Select Interpreter`.
4. Select the Python interpreter inside the `venv` folder.
5. Select the same environment as your Jupyter notebook kernel when working with notebooks.

### 7. Project Structure

```text
contractRisk/
│
├── code/           # Python scripts and Jupyter notebooks
├── database/       # Persistent databases (including ChromaDB)
├── knowledge_base/ # Legal documents and policies
├── uploads/        # Uploaded contracts
├── requirements.txt
└── README.md
```

### 8. Important Notes

- Do not upload the `venv` folder to GitHub.
- Install dependencies using `requirements.txt`.
- Keep the original knowledge-base documents available when rebuilding the vector database.
- Do not commit confidential contracts or sensitive user data.

## 9. Deactivating the Virtual Environment

When finished working, run:

```bash
deactivate
```
