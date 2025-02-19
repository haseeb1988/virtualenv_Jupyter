# Creating and Activating Python Virtual Environments in Jupyter NoteBook

## Lab Overview:

This lab guides you through the process of setting up and activating Python virtual environments within Jupyter Notebook. Virtual environments are essential for managing project dependencies and avoiding conflicts between different projects' requirements. By creating a virtual environment, you isolate project-specific packages and ensure that your projects remain organized and reproducible.

## Learning Objectives:
- Describe the purpose and benefits of Python virtual environments.
- Create a virtual environment within Jupyter Notebook.
- Activate a virtual environment.
- Install packages (specifically the IPython kernel) within a virtual environment.
- dd a virtual environment as a Jupyter kernel.
- Select a virtual environment in Jupyter Notebook.
 ## Tools and Technologies:
- Jupyter Lab
- Python's `venv` module
- `pip` package manager
- `ipykernel` 

## Begin Istruction:

Follow these steps to activate a virtual environment in Jupyter Notebook.

## Step 2: Create a New Directory:
Create a new folder or directory. In this directory, we will create a virtual environment.
For this example, let's name the folder `test_jupy_folder`.

## Step 1: Open Jupyter Lab  :

Open your terminal, such as **CMD**, and start Jupyter Lab using the command below:

```
jupyter lab
```

## Step 3: Navigate to the Directory
Open a new terminal on Jupyter and navigate to the newly created folder using the `cd` command:

```
cd C:/FolderName/test_jupy_folder
```

## Step 4: Create a Virtual Environment
Run the following command to create a virtual environment:
```
python -m venv your_env_name
```
Note: your_env_name is a environment name, you can change it



## Step 5: Activate the Virtual Environment
Open Terminal on Jupyter Notebook, and activate the virtual environment using the command below
```
your_env_name\Scripts\activate

```

## Step 6: Install IPython Kernel
On Jupyter terminal, Install the IPython kernel package in the virtual environment by using below command
```
pip install ipykernel

```

## Step 7: Add the Virtual Environment to Jupyter
Run the following command to add the virtual environment as a Jupyter kernel:

```
python -m ipykernel install --user --name your_env_name

```

## Step 8: Select the Virtual Environment in Jupyter Notebook
Now, when you open Jupyter Notebook, you can select your newly created virtual environment as a kernel.
![Alt text]([images/example.png](https://github.com/haseeb1988/virtualenv_Jupyter/blob/main/JupyterLab-02-19-2025_06_24_PM.png)
![alt text](https://github.com/haseeb1988/virtualenv_Jupyter/blob/main/JupyterLab-02-19-2025_06_24_PM.png?raw=true)
