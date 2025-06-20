# Guided Project: Predictive ML
**Author**: Kiruthikaa NS  
**Repo Name**: `datafun-07-ml`  
**Date**: June 2025  
**GitHub Repo**: [View this project on GitHub](https://github.com/Kiruthikaa2512/datafun-07-ml)  

## Project Overview

In this module, we will initiate a hands-on guided project that explores foundational and applied topics in data science, including introductory machine learning concepts. The project will be developed using Jupyter notebooks for interactive exploration and documentation.

We’ll begin by creating a GitHub repository—choose either `datafun-07-ml` or `datafun-07-applied`—to host and share our work. Simultaneously, we will set up the project locally to fully leverage our development tools.

To support our workflow, we’ll create and manage a local virtual environment. We'll start by installing essential external packages such as `jupyterlab`, `numpy`, `pandas`, `pyarrow`, `matplotlib`, `seaborn`, and `scipy`. Additional dependencies may be added as the project evolves.

## **Local Machine Setup**
### **Step 1: Install Python (if not installed)**
- Download from: [Python.org](https://www.python.org/downloads/)
- Verify installation using the terminal.

## **Project Initialization & GitHub Setup**
### **Step 2: Create and Clone GitHub Repo**
1. Navigate to [GitHub](https://github.com/)
2. Create a new repository named `datafun-07-ml`
3. Select **Add a README.md**
4. Clone the repo locally and navigate to the project directory.

### **Step 3: Set Up Version Control**
- Add a `.gitignore` file to exclude unnecessary files like virtual environments and cache directories.
- Use Git commands to **track changes**, commit updates, and push to the repository.

## **Virtual Environment & Dependency Setup**
### **Step 4: Set Up Python Environment**
- Create a virtual environment for dependency management.
- Activate the virtual environment according to the system you're using.

### **Step 5: Manage Dependencies**
Install essential Python packages including `jupyterlab`, `numpy`, `pandas`, `pyarrow`, `matplotlib`, `seaborn`, and `scipy` for data exploration, analysis, and visualization. To ensure reproducibility and ease of setup, list all dependencies in a `requirements.txt` file.

### Step 6: Setting Up spaCy with a Virtual Environment (Optional but Recommended)

For natural language processing tasks in this project, we recommend using [spaCy](https://spacy.io/usage) as a lightweight and efficient alternative to TensorFlow.

To ensure compatibility, we suggest using **Python 3.12.x** (e.g., 3.12.6), as spaCy may not install correctly with Python 3.13+.

#### Create and Activate a Virtual Environment

**On Windows:**
```bash
py -3.12 -m venv .venv
.venv\Scripts\activate
py -m pip install -U pip setuptools wheel
py -m pip install -U spacy==3.5.3
py -m spacy download en_core_web_sm
```

**On macOS/Linux:**
```bash
python3.12 -m venv .venv
source .venv/bin/activate
python3 -m pip install -U pip setuptools wheel
python3 -m pip install -U spacy==3.5.3
python3 -m spacy download en_core_web_sm
```

>  If you're using a different OS or configuration, refer to the official [spaCy installation guide](https://spacy.io/usage) for adjustments.

