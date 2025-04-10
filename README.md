### **Basic Git Concepts**

1.  **Repository(repo)**
    A poject folder that Git is tracking can be **local** (on your computer) or **remote** (like github).
2.  **Version Control**
    A system that tracks changes to code over time letting you revery to previous versions or collaborate with others.
3.  **Comit**
    A snapshot of your changes. Includes a message desribing what changed.
4.  **Working Directory**
    The current state of your files on disk.
5.  **Staging Area**
    Where you prepare changes before commiting. You "stage" files that are ready to be commited.

---

### **Common Commands**

6.  `git init`
    Initializes a new Git repository in a folder.

7.  `git status`
    Shows the current state of the working directory and staging area.

8.  `git add <file>`
    Stages changs in a file for the next commit.

9.  `git commit -m "message"`
    Saves the staged changes with a commit message.

10. `git push`
    Send local commits to the remote repository.
    **Note**: You may need to first creat a repo in github, and use `add origin` to link repo to the remote one.

11. `git pull`
    Fetches and merges changes from the remote repository to your local one.

12. `get merge`
    Merges changes from one branch to another

13. `git fetch`
    Downloads changes from the remte but doesn't merge them automatically.

14. `git clone <repo>`
    Copies a remote repository to your local machine.

### **`.gitignore`**

    Use this file to specify files that should not be tracked/commited by git.
    Once a file is tracked by git, adding it to .gitignore won't remove it. You need to untrack it with git rm --cached
