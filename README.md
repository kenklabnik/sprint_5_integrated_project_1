# sprint_5
Sprint 5 project from TripleTen bootcamp. Cumulative project analyzing video game sales data.

## Usage
The .ipynb file was downloaded as-is from TripleTen's JupyterNotebook instance. The Python code output and Markdown cells should be maintained from when this project was originally reviewed.

You can run this and other projects on your local, but you may run into an issue where `pd.read_csv` can't find the files in `datasets`. If this happens, add `import os` to the imports at the beginning of the project, then replace any instance of `pd.read_csv(string)` with `pd.read_csv(os.path.abspath("") + string)`, which will get the correct path from your local machine. 
