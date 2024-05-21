# datafun-04-jupyter
Creating a Jupyter Notebook
**CC4.1: Start a New Project**

Core Competency: Start a New Project

From now on, all Python projects will require a virtual environment. This is the process we'll use for future Python projects. 

**Step 1. Create a GitHub Repo with README.md**
Go to GitHub and create a new GitHub repo in your browser for Project 4 (use the name the specification requires). Be sure to add a default README.md when you first create the repository - it makes the easiest workflow.

**Step 2. Clone Repo**
Copy the URL of your new GitHub repo into your clipboard (CTRL+A, then CTRL+C, or CMD if on Mac).

Open a Git Bash, Terminal, or PowerShell terminal in your Documents folder (the parent folder of where you want your repo) and type:  git clone paste_your_repo_URL_here

My command might look like this - yours should use your GitHub username instead of denisecase:

git clone https://github.com/denisecase/datafun-04-jupyter

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
.gitignore - see the spec .gitignore for suggested contentsLinks to an external site.
README.md
requirements.txt
Git add and commit your initial changes with a message. See CC3.7: Git Add and Commit Your Local Changes

git add .
git commit -m "initial commit"
Step 7. Git Push To GitHub
Git push your initial changes to GitHub. See CC3.8: Git Push Local Changes to Remote Repo

git push origin main
