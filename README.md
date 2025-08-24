# DM2025 Lab1 Exercise

This repository contains the exercises for DM2025 Lab1, including Python scripts and Jupyter Notebooks.

---

## System Requirements

- Python 3.9.9
- [uv](https://pypi.org/project/uv/) virtual environment manager
- Git
- Jupyter Notebook

---

## Setup Instructions

Follow these steps to set up your local environment and run the code:

### 1. Install Python 3.9.9

Download and install Python 3.9.9 from the official website:  
[https://www.python.org/downloads/release/python-399/](https://www.python.org/downloads/release/python-399/)

Make sure to add Python to your system PATH during installation.

---

### 2. Install `uv` tool

Open your terminal/PowerShell and run:
```bash
pip install uv
uv --version 
```
`uv --version` for checking the version of uv. Expected output: uv 0.8.13 (ede75fe62 2025-08-21)
### 3. Create a project folder
```bash
mkdir DM2025Labs
cd DM2025Labs
```

### 4. Fork this repository
Go to https://github.com/leoson-wu/DM2025-Lab1-Exercise and fork it to your own GitHub account.

### 5. Clone your forked repository
```bash
cd <the path to your project folder DM2025Labs>  
git clone https://github.com/<your-github-username>/DM2025-Lab1-Exercise.git
cd DM2025-Lab1-Exercise
```

### 6. Create the virtual environment with uv  
```bash
uv venv
```  
This will create a .venv folder in your project. 

### 7. Sync the dependencies  
```bash
uv sync
``` 
This will install all required Python packages in your virtual environment.  
### 8. Register the Jupyter Kernel  
```bash
uv run python -m ipykernel install --user --name=dm2025lab --display-name "Python (dm2025lab)"
``` 
### 9. Run the code
You can now open Jupyter Notebook and select the Python (dm2025lab) kernel to run the exercises.
