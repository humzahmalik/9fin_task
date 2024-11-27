# Instructions to Set Up the Environment and Install Packages

These steps will guide you to recreate the conda environment required to run the Jupyter Notebook. 

## Step 1: Install Conda (if not already installed)

If Conda is not installed, follow these steps:

1. Download the Miniconda installer for your operating system from the [official Miniconda website](https://docs.conda.io/en/latest/miniconda.html).
2. Install Miniconda by running the installer and following the instructions on the screen.

## Step 2: Create the Conda Environment

1. Open a terminal or command prompt.

2. Create a new conda environment by running:

   conda create --name 9_fin_env python=3.10.5

3. Activate conda environment by running

   conda activate 9_fin_env

4. Install required files by running
   
   pip install -r requirements.txt

5. Activate Conda environment

   conda activate 9_fin_env

6. Open jupyter notebook and run main.ipynb

   jupyter notebook

