# Netflix Movies & TV Shows — Data Analysis Project

This is a **Python Data Analysis** project using
[`Pandas`](https://pandas.pydata.org/)
[`NumPy`](https://numpy.org/)
[`Matplotlib`](https://matplotlib.org/)
[`Seaborn`](https://seaborn.pydata.org/)
[`KaggleHub`](https://pypi.org/project/kagglehub/) for dataset management.

---

## Getting Started

First, clone the repository:

```bash
git clone https://github.com/<your-username>/netflix-analysis.git
cd netflix-analysis

Create and activate a conda environment:

conda create -n netflix python=3.10 -y
conda activate netflix


Install dependencies:

pip install pandas numpy matplotlib seaborn kagglehub jupyterlab


Start JupyterLab:

jupyter lab


Open notebooks/netflix_analysis.ipynb to start exploring the project.

Dataset

This project uses the Netflix Movies & TV Shows dataset from Kaggle:

import kagglehub

# Download the latest version
```bash
path = kagglehub.dataset_download("shivamb/netflix-shows")
print("Dataset downloaded to:", path)
```

Place the CSV inside the data/ folder for proper GitHub tracking.
```bash
Project Structure
netflix-analysis/
│
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── README.md
├── .gitignore
```

Tech Stack

Languages: Python 3.10+

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Tools: JupyterLab, KaggleHub, Git & GitHub

Optional: GitHub CLI for repo creation


Key Analysis

Count of Movies vs TV Shows

Most common genres

Country-wise production of Netflix content

Trend of content additions over the years

Handling missing values & mixed date formats

Distribution of content ratings

Top directors and actors

