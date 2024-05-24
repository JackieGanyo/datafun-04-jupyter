# Creating a Jupyter Notebook

## **CC4.1: Start a New Project**

Core Competency: Start a New Project

From now on, all Python projects will require a virtual environment. This is the process we'll use for future Python projects.

**Step 1. Create a GitHub Repo with README.md**
Go to GitHub and create a new GitHub repo in your browser for Project 4 (use the name the specification requires). Be sure to add a default README.md when you first create the repository - it makes the easiest workflow.

**Step 2. Clone Repo**
Copy the URL of your new GitHub repo into your clipboard (CTRL+A, then CTRL+C, or CMD if on Mac).

Open a Git Bash, Terminal, or PowerShell terminal in your Documents folder (the parent folder of where you want your repo) and type:  git clone paste_your_repo_URL_here

My command might look like this - yours should use your GitHub username instead of denisecase:

\\\git clone <https://github.com/denisecase/datafun-04-jupyter\\\>

**Step 3.  Create a Project Virtual Environment**
Open your project 4 repository in VS Code. Open a terminal (Windows = PowerShell, Mac/Linux = zsh usually).  See CC3.4: Create a Local Virtual Environment Create a virtual environment named .venv:

python -m venv .venv

**Step 4. Activate Project Virtual Environment**
Activate your project virtual environment and notice how your prompt changes. See CC3.5: Activate Your Project Virtual Environment

Windows:

.\.venv\Scripts\activate
macOS and Linux:

source .venv/bin/activate

**Step 5. Manage Your Project Requirements**
Manage your project requirements.  See CC3.6: Manage Project Requirements Add an empty requirements.txt. We'll look at project dependencies  in the next assignment.

**Step 6. Git Add and Commit Your Change**s
Verify these files and folders exist in your root project folder:

.venv/
.gitignore - see the spec .gitignore for suggested contents Links to an external site.
README.md
requirements.txt
Git add and commit your initial changes with a message. See CC3.7: Git Add and Commit Your Local Changes

git add .
git commit -m "initial commit"

Step 7. Git Push To GitHub
Git push your initial changes to GitHub. See CC3.8: Git Push Local Changes to Remote Repo

git push origin main

## **Start Jupyter on machine**

**Install Dependencies**
Option 2. Install packages on one line

py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy

**Freeze Your Dependencies**
When finished, freeze your dependencies to the requirements.txt file:

\\\ py -m pip freeze > requirements.txt \\\

## **Start Jupyter**

1. Start Jupyter in VS Code
Open your project folder in VS Code.

2. Add a new file, e.g. FirstNotebook.ipynb - the file extension must be exactly ".ipynb" - that is how VS Code will know what needs to be done.

3. Make sure the file is open for editing (if it is not already).

## **CC4.3 Create Jupyter Notebook in VS Code**

1. Open your Project 4 repository in VS Code. You can do this by going to "File" > "Open Folder" and selecting your Project 4 repository folder.
2. Launch Jupyter Notebook: To run Jupyter within VS Code, you'll need to use the Jupyter extension. If you haven't installed it already, you can do so by going to the Extensions pane on the left sidebar (the icon looks like four squares), searching for "Jupyter," and installing the "Jupyter" extension provided by Microsoft.
3. Create a New Notebook: Click on the "New" button in the Jupyter extension sidebar (usually on the left side of the VS Code window). Select "Python 3" to create a new notebook named "Untitled.ipynb".
4. Rename the Notebook: Right-click on the notebook's name tab (usually at the top of the notebook interface). Choose the "Rename Notebook" option and rename the notebook to "TestDrive.ipynb."
5. In the new notebook, create a new code cell by clicking the "+" button or using the "Insert Cell Below" option from the menu. Write a simple Python code snippet in the code cell, e.g., print("Hello, Jupyter!").
6. Execute the code cell and ensure it runs without errors.

## **CC4.4: Verify/Select a Jupyter Kernel for Your Notebook**

**Before you Begin**
Follow the earlier instructions - you should have a Project 4 repository with Jupyter running in VS Code or natively on your machine and have created and renamed a new Jupyter Notebook.

### *Select a Kernel*

1. In the Jupyter Notebook interface, create a new notebook if you haven't already.
2. Click on "Kernel" in the menu and choose "Change Kernel."
3. Select a different kernel, such as Python 2 or another available option.

## **CC4.5: Edit and Execute a Jupyter Notebook**

1. Edit and Execute Notebook
2. In your Jupyter Notebook, add a new code cell.
3. Write a Python code snippet in the cell (e.g., a mathematical calculation or a data manipulation task).
4. Execute the cell and ensure it runs without errors.
5. Edit the code cell's content and re-execute it.
6. Insert several code cells - each can have multiple lines of code.
7. Experiment until you have at least 6 code cells.
8. Show the results after running the ENTIRE notebook (not just one cell at a time).
