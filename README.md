1- git init
git add .
git commit -m "learn git cmd"
git remote add origin url
git push -u origin main




Here’s a comprehensive list of essential Git commands, grouped by their functionality:

### **Basic Git Commands**

* `git init`
  Initialize a new Git repository.

* `git clone <repository_url>`
  Clone a repository from a remote source.

* `git status`
  Show the status of your working directory and staging area.

* `git add <file>`
  Stage a file for commit (use `.` to add all files: `git add .`).

* `git commit -m "<message>"`
  Commit staged changes with a message.

* `git push <remote> <branch>`
  Push changes to a remote repository (usually `origin`).

* `git pull <remote> <branch>`
  Fetch and merge changes from a remote repository.

* `git fetch`
  Download changes from a remote repository without merging.

* `git merge <branch>`
  Merge a branch into your current branch.

* `git diff`
  Show the differences between the working directory and the index (staging area).

* `git log`
  View the commit history.

---

### **Branching & Merging**

* `git branch`
  List all branches in the repository.

* `git branch <branch_name>`
  Create a new branch.

* `git checkout <branch_name>`
  Switch to another branch.

* `git checkout -b <branch_name>`
  Create a new branch and switch to it.

* `git merge <branch_name>`
  Merge the changes from another branch into your current branch.

* `git rebase <branch_name>`
  Rebase your current branch on top of another branch.

* `git branch -d <branch_name>`
  Delete a branch.

---

### **Remote Repositories**

* `git remote -v`
  Show the remotes associated with the repository.

* `git remote add <name> <url>`
  Add a remote repository.

* `git remote remove <name>`
  Remove a remote repository.

* `git push <remote> <branch>`
  Push your changes to a remote repository.

* `git pull <remote> <branch>`
  Pull changes from a remote repository.

---

### **Undoing Changes**

* `git reset <file>`
  Unstage a file.

* `git reset --hard`
  Reset the repository to the last commit (discard changes).

* `git reset --soft <commit>`
  Reset the current branch to a specific commit but keep changes in the working directory.

* `git checkout -- <file>`
  Discard changes in a file and restore it to the latest commit state.

* `git revert <commit>`
  Create a new commit that undoes the changes of a specific commit.

---

### **Stashing Changes**

* `git stash`
  Stash changes (save work in progress).

* `git stash list`
  List all stashes.

* `git stash apply`
  Apply the latest stash.

* `git stash pop`
  Apply and remove the latest stash.

* `git stash drop`
  Drop a specific stash.

---

### **Tagging**

* `git tag <tag_name>`
  Create a new tag.

* `git tag -d <tag_name>`
  Delete a tag.

* `git push <remote> <tag_name>`
  Push a specific tag to a remote repository.

* `git push --tags`
  Push all tags to a remote repository.

---

### **Viewing Changes**

* `git log`
  Show commit history.

* `git log --oneline`
  Show commit history in a concise format.

* `git log <file>`
  Show the commit history for a specific file.

* `git diff`
  Show differences between working directory and staging area.

* `git show <commit>`
  Show detailed information about a specific commit.

---

### **Advanced Commands**

* `git cherry-pick <commit>`
  Apply the changes from a specific commit to the current branch.

* `git bisect`
  Help you find which commit introduced a bug by performing a binary search.

* `git submodule`
  Manage submodules (repositories inside your repository).

* `git reflog`
  Show the history of `HEAD` (useful for finding lost commits).

* `git gc`
  Perform garbage collection to clean up unnecessary files.

---

### **Configuration**

* `git config --global user.name "<name>"`
  Set your Git username.

* `git config --global user.email "<email>"`
  Set your Git email.

* `git config --global core.editor <editor>`
  Set your default editor for Git.

---

### **Other Useful Commands**

* `git clean -f`
  Remove untracked files in the working directory.

* `git rm <file>`
  Remove a file from the working directory and staging area.

* `git mv <old_path> <new_path>`
  Rename or move a file.

* `git archive`
  Create a tar or zip archive of files from a commit or branch.

---

Let me know if you need more details about any of these commands!
