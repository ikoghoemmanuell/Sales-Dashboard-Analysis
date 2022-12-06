# git-and-github-basic-repo
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
## Description
This is a basic repository to start practicing Git &amp; Github.

## Assignment
The following steps constitute your assignment :
1. Clone this repository on your local machine; 
1. Configure it as described in the `Setup` section;
1. Create a file named exactly `firstfile.py` in the `src` folder;
1. Commit your change with the message `Here Is My First Commit.`;
1. Finally, push your first commit.

## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:


- Windows *(Python should be added to the Path variable of environment)*:
        
        python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

## Evaluation
This evaluation will be automatically grade, so please follow the instructions carefully. 

You can run this command bellow being at the root of the repository to be sure your solutions are the good ones before to push your solutions.
```command
python -m pytest -v
```
