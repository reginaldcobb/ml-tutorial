# ml-tutorial
Welcome! This is the repository for the BIT ML Tutorial 16 Nov 2019

The tutorial uses Anaconda Python, SciKitLearn, and Pandas

## Getting Started
1. Download and install Anaconda 3.7: https://www.anaconda.com/distribution/#download-section
2. Install Git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Clone this repository
````
git clone git@github.com:jesuisme/ml-tutorial.git
````
Once the repository is cloned, open either Git Bash or a terminal or a CMD window and change directory (cd) to the newly cloned directory

4. Create a Conda virtual environment
````
conda create --name <name of the environment> python==3.6.8
````
Select Y when asked to proceed and a virtual environment will be created.

5. Activate the conda environment you just created:
````
activate <name of the environment>
````
Note: in Git Bash and in several Linux variants, you have to use
````
source activate <name of the environment>
````

6. Install the Python modules we will use for the tutorial
````
conda install --file requirements.txt
````
The modules and versions installed (note, they aren't necessarily the latest versions):
* SciKitLearn 0.20.3
* Matplotlib 3.0.3
* Pandas 0.24.2
* Jupyter 1.0.0

7. Create and start a Jupyter notebook
````
jupyter notebook
````

*And... we're off!*
