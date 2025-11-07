# 🧪 Setup Instructions for `explainable_ai_2025`

This guide will help you set up a Python virtual environment and install the required dependencies for the `explainable_ai_2025` workshop.

---
## 📦 1. Download Git for Windows
> ⚠️ Skip this step if you already have `git` installed.

    Go to the official Git website:
    👉 https://git-scm.com/download/win

    The download will begin automatically for the 64-bit Windows installer (e.g., Git-x.y.z-64-bit.exe).
---

## 📦 2. Clone the Repository and Set Up the Environment

Open a terminal and run the following commands:

```sh
# Clone the repository
git clone https://github.com/mikesips/explainable_ai_2025.git

# Navigate into the project directory
cd explainable_ai_2025

# Create a virtual environment (named 'explainable_ai_2025')
python3 -m venv explainable_ai_2025

# Activate the virtual environment (Linux/macOS)
source explainable_ai_2025/bin/activate

# On Windows, use:
explainble_ai_2025\Scripts\activate.bat

# Upgrade pip
python -m pip install --upgrade pip

# Install required dependencies (Linux/macOS)
python -m pip install -r REQUIREMENTS/requirements_venv.txt

# On Windows, use:
python -m pip install -r REQUIREMENTS\requirements_venv.txt

```

## 📦 3. Check your install and environment

To confirm that your environment is correctly configured, run the check_env.py script:
```sh
# Linux/macOS
python check_environment.py REQUIREMENTS/requirements_venv.yml

# On Windows, use:
python check_environment.py REQUIREMENTS\requirements_venv.yml
```

If everything is correctly installed, the output should look like:
```
Using Python from: /home/mike/Workshops/test/explainable_ai_2025/explainable_ai_2025
3.11.2 (main, Apr 28 2025, 14:11:48) [GCC 12.2.0]
[ OK ] Python 3.11 is compatible.

[INFO] Loading requirements from requirements.yml

[INFO] Checking installed packages

[ OK ] streamlit version 1.51.0
[ OK ] pandas version 2.3.3
[ OK ] scikit-learn version 1.7.2 
[ OK ] plotly version 6.4.0

[INFO] Environment check complete. All installable requirements have been processed.
```

## 📦 4. Alternatively, use bash script
```sh
# Clone the repository
git clone https://github.com/mikesips/explainable_ai_2025.git

# Navigate into the project directory
cd explainable_ai_2025

# Run Bash Script
./run_env_setup.sh explainable_ai_2025

# Activate the virtual environment (Linux/macOS)
source explainable_ai_2025/bin/activate