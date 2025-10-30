# IDS-KDD-CICIDS2017
Reproducibility Instructions for Journal Reviewers
1) Clone the repository
git clone https://github.com/miguelarcosa/IDS-KDD-CICIDS2017.git
cd IDS-KDD-CICIDS2017

2) Create the Conda environment
Open Anaconda Prompt (Windows) or a terminal with Conda available. Ensure the file environment.yml is located in the root of your cloned repository (the same folder you are in after cd above). Then run:
conda env create -f environment.yml
After creation finishes, activate the environment (use the exact name specified inside environment.yml, e.g. ids-repro):

3) Run the NSL-KDD notebook
Launch Jupyter from the repository root:
jupyter lab
Open notebooks/BACK-nsl-kdd-github.ipynb and run all cells (Jupyter menu: Run → Run All Cells).
This will execute the complete NSL-KDD preprocessing and evaluation pipeline.

4) Run the CICIDS2017 notebook
In the same Jupyter session, open notebooks/BACK-cicids2017-github.ipynb and run all cells.
This will execute the complete CICIDS2017 preprocessing and evaluation pipeline.
