![alt text](assets/uva-datapalooza-2018.png)

## 1 SUMMARY

## 1.1 Installation

### PYTHON
### 1.1.1 ANACONDA
The Anaconda platform is the industry standard for performing data science tasks in Python.  Please follow the installation instructions for your operating system from the Anaconda website.
* https://www.anaconda.com/

### 1.1.2 VIRTUAL ENVIRONMENT
Once Anaconda is installed, create a virtual environment for the application.  A virtual environment allows us to isolate the Python packages installed for Anaconda.
* Open Anaconda Navigator
* Select the “Environments” tab
* Select the “Create” button
* Do not alter the default settings
* Title the environment “uva-datapalooza”
* Select the “Create” button

### 1.1.3 APPLICATION REQUIREMENTS
The application folder contains a requirements.txt file.  This file lists the required Python libraries to run the application:
* Open the Anaconda Prompt and change directories to the application folder
* Type “conda activate uva-datapalooza”
* Type “pip install -r requirements.txt”

## 1.2 APPLICATION

### JUPYTER NOTEBOOK
### 1.2.1 DATA VISUALIZATION
Jupyter Notebook is an interactive computational environment. The application can be run using the following steps.
* Open the Anaconda Prompt and change directories to the application folder
* Type “conda activate uva-datapalooza”
* Type ‘python -m ipykernel install --user --name uva-datapalooza --display-name "Python (uva-datapalooza)"’ NOTE: Only required once.
* Type  “jupyter notebook”
* Navigate to desired notebook and open
* From the top menu, select kernel, Restart & Run All
