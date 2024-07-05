# KYA323 Workshops
Jupyter notebooks used in the workshops for KYA323.

## Miniconda installation
Conda is an open source package/environment management system that we will use to set up and run our Python-based computations. Miniconda is a free minimal installer for conda from which we will build upon to set up our computing environment. If you do not have conda installed, please visit 

    https://docs.conda.io/en/latest/miniconda.html
  
and download the latest version suitable for your operating system. Opening the downloaded file will bring up a prompt which you can follow to install Miniconda. *Note: Mac/Linux users will likely need to select "Add Anaconda to my PATH environment variable"*

Open up a window in either **Anaconda Prompt** (Windows) or **Terminal** (Mac/Linux).  The input line should look something like this:

    (base) C:\>
    
If it does not have the `(base)` then you may need to restart your computer. If after restarting there is still no `(base)` then conda is not installed properly in that terminal window. Please come see me to troubleshoot. 

## Creating a conda environment
To create the environment needed for this unit, download the `electro_environment.yml` file from this repository. Navigate from your command line to the directory of the file and run

    conda env create -f electro_environment.yml
    
This will take a few minutes.  Please ensure you are connected to the internet. To activate the environment simply run

    conda activate electro
    
## Initialising Jupyter
To initialise a Jupyter notebook use the command

    jupyter notebook

