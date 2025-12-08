HOW TO RUN THIS PROJECT

1) Install Python on your computer.

2) Install Jupyter Notebook or JupyterLab. (Anaconda can be used.)

3) Open a terminal or command prompt and go to the project folder.

4) Install all required Python packages using:
   pip install -r requirements.txt

5) Make sure there is a folder named "data" inside the project folder.

6) Copy the CIC-IDS-2017 CSV files into the "data" folder.
   Due to storage limits, only one CSV file is included.
   The full dataset can be downloaded from public CIC-IDS-2017 sources or personal storage link.
   Any missing CSV files must be placed inside the "data" folder manually.
   
   Personal storage link: https://gounbc-my.sharepoint.com/:f:/r/personal/islam5_unbc_ca/Documents/data?csf=1&web=1&e=QQQYWG

7) Start Jupyter by running one of these commands in the terminal:
   jupyter notebook
   or
   jupyter lab

8) In the Jupyter interface, go to the "notebooks" folder.

9) Open the file named:
   NIDS_DM.ipynb

10) Run the notebook cells one by one to see each result,
    or use "Run All" from the menu to execute the whole notebook automatically.

This will load the dataset, train the machine learning models, and show the results.

Note 1: This project can be accessed from the public GitHub repository:https://github.com/sharif2008/ML-NIDS-CPSC-673
Note 2: If jupyter notebook file does not work, then relevant python script is provied under optional[not preferred].