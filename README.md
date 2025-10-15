# Explainable AI for Affective Computing Tutorial
##### Winter Semester 25 - Bielefeld University

In this seminar, we will learn about the latest research in eXplainable AI (XAI) and its application in affective computing.  This repository will contain a series of [Jupyter Notebooks](https://jupyter.org/) to give you practical experience implementing state-of-the-art explainability techniques using various approaches.

These notebooks have been designed to be run via Google Colab or locally.  Google Colab's free usage should be sufficient to run the notebooks (but in some cases, GPU acceleration can speed up processing).

## Colab Instructions

- Click the "Open in Colab" button at the top of the notebook
- Click "Copy To Drive" at the top of the notebook so that you can save your results.
- Review the notebook and update code as needed for running on Colab (see comments in the corresponding Notebooks).

## Local Installation Instructions

### Install Anaconda

We will use Anaconda for the management of virtual environments and Python package installations.

Download and install [miniconda](https://docs.conda.io/en/latest/miniconda.html), a lightweight installation of Anaconda (if you already have the full version of Anaconda installed, that will work as well).

### Create Virtual Environment and Install Necessary Python Packages

After installing miniconda, you can now easily create and manage Python virtual environments using the `conda` command. For the Jupyter Notebooks used in this seminar, we recommend you create a new virtual environment to manage the various Python packages we will use throughout the semester.

If you're not already familiar with `conda`, you may want to familiarize yourself with the [documentation](https://docs.conda.io/projects/conda/en/latest/commands.html) and the various commands in [this cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

To create a new virtual env for this seminar, run the following commands from your conda terminal.

1. Create a new virtual env named 'ml_bias_seminar' with the latest version of Python 3:
 	- `conda create -n xai_ac python=3.10`
2. Activate the new virtual env:
	- `conda activate xai_ac`
3. Install the required Python packages (The requirements.txt will be updated to include all necessary packages for the notebook assignments)
	- `pip install -r requirements.txt`


## Getting Started with the Notebooks

### Clone the Seminar GitHub Repo

All notebooks during the semester will be provided through this GitHub repository.  The easiest way to obtain the notebooks is to `clone` this repository, and then perfrom a `git pull` when we announce that new notebooks are available. Here I will provide terminal instructions to clone and pull the repo, but you are free to use your preferred GUI or Git interface.

1. To `clone` the repository:
	- First, make sure you have a directory where you would like to store the repository
	- `git clone \<LINK TO REPO\>`
	- This will download all the current notebooks and material into a folder named \<REPO NAME\>

2. If we announce a new notebook or repository changes, then `pull` from the repo to get the latest material
	- Make sure you are in the cloned directory named \<REPO NAME\>
	- Run: `git pull`
	- You should receive a message indicating new files were downloaded

### Running JupyterLab and Launching a Notebook

For this seminar, all exercises will use [Jupyter Notebooks](https://jupyter.org/try-jupyter/notebooks/?path=notebooks/Intro.ipynb). These combine code blocks with outputs, such as plots, and markdown text annotations. Among others, you can use [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) to run and manage our Notebooks:

1. Start JupyterLab
	- On the command line, make sure your virtual env is activated
	- Run: `jupyter lab`
	- This should automatically open JupyterLab in your browser window
	- If not, open the URL provided in your terminal output
2. To create a new Notebook
	- Go to the "Launcher" tab and click the Python icon in the "Notebook" section
3. To open an existing notebook
	- In the file explorer pane on the left, browse to an `.ipynb` file and double-click it
