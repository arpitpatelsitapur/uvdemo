# uvdemo

> A sample project demonstrating the use of **[uv](https://github.com/astral-sh/uv)** – a new Python package manager that is **10–100x faster than pip**.

## 🚀 Getting Started with `uv`

### 🔧 1. Install `uv`
```bash
pip install uv
```


### 📖 2. Learn More About uv
```bash
uv
```
This command shows all available options and commands supported by uv.



## 🛠️ Project Initialization

### 📁 3. Create a New Project
```bash
uv init uvdemo
```
This creates a project directory `uvdemo` with the following files:
	•	.gitignore
	•	.python-version
	•	main.py
	•	pyproject.toml
	•	README.md


## 🐍 Python Version Management

### 📌 4. Install Multiple Python Versions
```bash
uv python install 3.11 3.12
```


## 🧪 Virtual Environment Setup

### 🌱 5. Create Virtual Environment
```bash
uv venv
```
This creates a virtual environment named `venv`.

### 🧬 6. Activate Virtual Environment
```bash
source .venv/bin/activate
```



## 📦 Dependency Management

### ➕ 7. Install Packages
- Install individual packages:
```bash
uv add numpy
uv add pandas
```
- Install from a requirements.txt file:
```bash
uv add -r requirements.txt
```
After installation, the pyproject.toml file is automatically updated to include the added dependencies under the [dependencies] section.



## ▶️ Running Scripts

### 🐍 8. Run Python Scripts
```bash
uv run script_name.py
```




## 📄 Lock File

### 🔒 9. Package Info Storage

Installed packages and dependency information are stored in the uv.lock file.



## 📚 Resources
- [uv GitHub Repository](https://github.com/astral-sh/uv)
- [uv Documentation](https://docs.astral.sh/uv/)



Happy Coding! ⚡️
