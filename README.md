# ML Learning Environment Setup

## ✅ Environment Successfully Configured!

Your Python environment for machine learning has been set up with all necessary dependencies.

## 📦 What's Installed

- **Python**: 3.13.6
- **Jupyter**: Full Jupyter suite (notebook, lab, console)
- **ML Libraries**: 
  - NumPy 2.4.0
  - Pandas 2.3.3
  - Matplotlib 3.10.8
  - Scikit-learn 1.8.0
  - SciPy 1.16.3

## 🚀 How to Use

### In VS Code (Recommended)

1. Open your notebook file (e.g., `L13.ipynb`)
2. Click on the kernel selector in the top-right corner
3. Select **"Python (ML Environment)"** from the dropdown
4. Start coding! 🎉

### From Terminal

To activate the virtual environment:
```bash
source ml_env/bin/activate
```

To start Jupyter Notebook:
```bash
jupyter notebook
```

To start JupyterLab:
```bash
jupyter lab
```

To deactivate the environment:
```bash
deactivate
```

## 🔧 Troubleshooting

### If the kernel doesn't appear in VS Code:
1. Reload VS Code window (Cmd+Shift+P → "Developer: Reload Window")
2. Make sure the Jupyter extension is installed
3. Try selecting the kernel again

### To install additional packages:
```bash
source ml_env/bin/activate
pip install package-name
```

### To recreate this environment on another machine:
```bash
python3 -m venv ml_env
source ml_env/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=ml_env --display-name="Python (ML Environment)"
```

## 📝 Files in This Directory

- `ml_env/` - Virtual environment (not tracked in git)
- `requirements.txt` - List of installed packages
- `.gitignore` - Git ignore rules
- `L13.ipynb` - Your notebook file

## 💡 Tips

- Always activate the virtual environment before installing new packages
- Use `pip freeze > requirements.txt` to update the requirements file after installing new packages
- The virtual environment is isolated from your system Python, preventing conflicts

Happy Learning! 🎓
