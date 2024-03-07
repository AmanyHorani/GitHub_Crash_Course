# Example Repository
This is a sample repo, hello world!

This is a second change.

# What you learned
Terminology
- clone
- repo = repository
- push
- staging committing

# Commands to keep in mind
- mkdir (foldername) --- Creates directory (folder) in your current path.
- cd (filename)/ --- Changes the current directory to the specified directory
- git clone (GitHub repository link) --- Clones the entire repository into the specified directory
- dir --- To list current directory contents/details
- git status --- Shows the status of your local repository, including which files are staged, unstaged, or untracked, and whether there are changes that need to be committed.
- git commit -m "commit message" --- Commits the staged changes with the provided commit message
- git push origin main --- Pushes the committed changes from your local repository to the remote repository (typically on GitHub) on the main branch.
- git add (filename) --- Adding changes in the file to the stage.
- git diff (filename) --- Shows the differences between the working directory and the staging area for the specified file.
- git checkout (filename) --- Discard changes in the specified file in the working directory and revert it to the state it was in at the last commit.
- git checkout (copied hashcode) --- move the HEAD pointer to a specific commit identified by its hash code. This doesn't exactly "undo" a previous commit; it moves your repository to the state it was in at that commit, potentially discarding commits after it.