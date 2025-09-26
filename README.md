# Airbnb Data Analysis

A Jupyter Notebook-based exploration and analysis of Airbnb Open Data.

## Contents
- `Airbnb_Data_Analysis_Project.ipynb` — Main analysis notebook
- `1730285881-Airbnb_Open_Data.xlsx` — Dataset used by the notebook

## Quick Start
1) Ensure Python 3.9+ is installed.
2) Install Jupyter and common data libraries:
   ```bash
   pip install jupyter pandas numpy matplotlib seaborn
   ```
3) Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook Airbnb_Data_Analysis_Project.ipynb
   ```

## Notes on the Dataset
- The Excel dataset included (~16.5 MB) is below GitHub’s 100 MB per-file limit and can be pushed directly to GitHub.
- If you later add larger files (>100 MB), consider using Git LFS.

## Reproducibility
- This project currently does not include a `requirements.txt`. The minimal dependencies to run the notebook are listed above.
- For consistent environments, consider creating a virtual environment and exporting a requirements file:
  ```bash
  python -m venv .venv
  .venv\\Scripts\\activate  # Windows
  pip install jupyter pandas numpy matplotlib seaborn
  pip freeze > requirements.txt
  ```

## License
This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

## Author
- Owner/Author: **N H Padma Priya**

## Hosting on GitHub
- Initialize a local repository, commit, create a GitHub repo, add it as a remote, and push:
  ```bash
  git init
  git add .
  git commit -m "Initial commit: notebook and dataset"
  git branch -M main
  git remote add origin https://github.com/<YOUR-USERNAME>/Airbnb-data-analysis.git
  git push -u origin main
  ```
