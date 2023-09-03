# Dados Médicos - Student Dropout Prediction Model

This project aims to create a prediction model for student dropout using Jupyter Notebook. To get started, follow these steps to set up your development environment.

## Prerequisites

Before you begin, make sure you have the following software installed on your system:

- Python 3.x
- Virtualenv (for creating a Python virtual environment)
- Visual Studio Code (VS Code)

## Setup Instructions

Follow these step-by-step instructions to set up your environment:

### 1. Clone the Repository

If you haven't already, clone this repository to your local machine using Git:


```bash
git clone https://github.com/Guilhermeasper/dados-medicos.git

cd dados-medicos

python -m venv .venv
```

or

```bash
python3 -m venv .venv
```


### 3. Activate the Virtual Environment

- On Windows:

```powershell
.venv\Scripts\activate
```

- On macOS and Linux:

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

With the virtual environment activated, install the project's dependencies using pip:

```bash
pip install -r requirements.txt
```

### 5. Open the Project in VS Code

Launch Visual Studio Code and open the project folder:

```bash
code .
```

### 6. Select the Virtual Environment as Jupyter Kernel

In VS Code, follow these steps to select the virtual environment you created as the Jupyter Notebook kernel:

1. Press `F1` to open the command palette.
2. Search and select "Notebook: Select Notebook Kernel".
3. Select "Select Another Kernel".
4. Choose "Python Environments".
5. Select the virtual environment you created previously (e.g., `venv`).

Remember to activate the virtual environment (`venv`) every time you need to use the project to ensure you are working within the isolated environment.