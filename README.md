# Caltech ACM/IDS 154 — Winter 2026

This repository contains course materials for **ACM/IDS 154: Inverse Problems and Data Assimilation** at Caltech (Winter 2026).

## Contents
- Jupyter notebooks for lectures and discussion sessions
- Python implementations of core algorithms and models
- Assignment starter code and project guidelines

## Usage

### Option 1: Google Colab (Recommended)
You can run the notebooks directly in your browser using Google Colab. No local installation is required. Simply upload the `.ipynb` file to your Google Drive and open it with Colab.

### Option 2: Local Installation
If you prefer running the code locally, follow the steps below to set up your environment.

#### 1. Clone the Repository
```bash
git clone https://github.com/wispcarey/caltech-acm-ids-154-winter-2026.git
cd caltech-acm-ids-154-winter-2026
```

#### 2. Environment Setup

Choose one of the following methods to create a virtual environment.

**Method A: Using Conda (Preferred)**

```bash
# Create a new environment
conda create -n acm154 python=3.10 -y

# Activate the environment
conda activate acm154
```

**Method B: Using standard Python venv**

```bash
# Create a virtual environment
python -m venv venv

# Activate (macOS/Linux)
source venv/bin/activate

# Activate (Windows)
.\venv\Scripts\activate
```

#### 3. Install Dependencies

Install all required packages using the provided requirements file:

```bash
pip install --upgrade -r requirements.txt
```

> **Note:** If you require specific CUDA versions for PyTorch (to use a local GPU), please visit [pytorch.org](https://pytorch.org/) for the command specific to your system before running the command above.

#### 4. Register Jupyter Kernel

To make this environment available in Jupyter Notebook:

```bash
python -m ipykernel install --user --name=acm154 --display-name "Python (ACM154)"
```

#### 5. Run Jupyter

```bash
jupyter notebook
```

