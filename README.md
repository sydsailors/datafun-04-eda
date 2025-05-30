# datafun-04-eda

This project uses Jupyter to perform exploratory data analysis (EDA) on the Iris dataset. 

Steps already completed:
1. [Set up the Machine](https://github.com/denisecase/pro-analytics-01/blob/main/01-machine-setup/MACHINE-SETUP.md)
2. [Initialized a new Project](https://github.com/denisecase/pro-analytics-01/blob/main/02-project-initialization/PROJECT-INITIALIZATION.md)

## Before/During Working on the Project
1. Pull the Latest Changes from GitHub 
   
```shell
git pull origin main
```

2. Activate the Project Virtual Environment

```powershell
source .venv/bin/activate
```

3. Install Dependencies As Needed 

```powershell
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

4. Run Script 

```powershell
source .venv/bin/activate
python3 demo-script.py
```

## Git add-commit-push command 
```shell
git add .
git commit -m "custom message"
git push -u origin main
```

## Create Jupyter Notebook and Select Kernel
- Create new Jupyter notebook: Command + Shift + P then type "Create: New Jupyter Notebook"
- Rename notebook: File -> Save As...
- Set kernel: click "Select Kernel" in top right corner and select local .venv

### Markdown Cells
- text-based content (formatting, lists, headings)

### Code Cells
- write and run programming (e.g. Python) code 

## Iris Dataset
- Tools used for project: pandas, seaborn, matplotlib
- Once data is loaded, we will perform data inspection, descriptive statistics, data distribution, data transformation and feature engineering, and initial visualizations (e.g. scatterplots)