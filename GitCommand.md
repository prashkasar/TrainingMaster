ls                      # Lists files in the current directory.
pwd                     # Prints the working directory path.
mk git-for-devops        # (Typo, should be `mkdir`) Creates a new directory called "git-for-devops".
mkdir git-for-devops     # Creates the directory "git-for-devops".
cd git-for-devops        # Changes the current directory to "git-for-devops".
pwd                     # Prints the working directory path, now inside the "git-for-devops" directory.
git init                # Initializes a new Git repository in the current directory.
ls -a                   # Lists all files, including hidden ones (like `.git`).
git status              # Displays the status of the working directory and staging area.
ls -a                   # Lists all files again, including hidden ones.
git add nibba.txt       # Adds `nibba.txt` to the staging area.
ls -a                   # Lists files again to check the state.
git status              # Displays the status again, showing that `nibba.txt` is staged for commit.
git add nibbi.txt       # Adds `nibbi.txt` to the staging area.
ls -a                   # Lists files again.
git status              # Shows that both `nibba.txt` and `nibbi.txt` are staged.
git rm --cached nibba.txt  # Unstages `nibba.txt` without deleting it from the working directory.
git commit -m "adding nibbi"  # Commits the staged changes (only `nibbi.txt`) with the message "adding nibbi".
git status              # Shows the current status after the commit.
git restore nibba.txt   # Restores `nibba.txt` to its last committed state.
git restore nibbi.txt   # Restores `nibbi.txt` to its last committed state.
git status              # Displays the current status.
git add                 # (Incomplete command, should specify file name).
git status              # Shows the current status.
git restore nibba.txt   # Restores `nibba.txt` again.
git add nibba.txt       # Adds `nibba.txt` to the staging area again.
git status              # Displays the status showing `nibba.txt` is staged.
restore nibbi.txt       # (Typo, should be `git restore`) Restores `nibbi.txt` to its last committed state.
git restore nibbi.txt   # Correctly restores `nibbi.txt` to its previous state.
git add nibbi.txt       # Adds `nibbi.txt` back to the staging area.
git status              # Displays the current status with both files staged.
git commit -m "adding"  # Commits the staged changes with the message "adding".
git status              # Shows the status after the commit.
git add nibba.txt       # Adds `nibba.txt` again to the staging area.
git status              # Displays the current status.
git commit -m "adding"  # Commits the changes with the message "adding".
git status              # Shows the status.
git restore nibba.txt   # Restores `nibba.txt` to its last committed state.
git status              # Displays the status.
git add nibba.txt       # Adds `nibba.txt` back to the staging area.
git status              # Shows the current status.
git commit -m "adding"  # Commits the changes again with the message "adding".
git status              # Displays the status.
git commit -m "adding"  # (Redundant commit command, no staged changes).
git status              # Displays the current status.
git log                 # Shows the commit history of the repository.
vi nibba.txt            # Opens `nibba.txt` for editing in the `vi` editor.
git status              # Displays the current status, showing changes in `nibba.txt`.
git commit -m "adding"  # Commits the new changes with the message "adding".
git commit -m "adding"  # (Redundant commit, no new changes).
git status              # Shows the current status.
git add nibba.txt       # Adds `nibba.txt` to the staging area again.
git commit -m "adding"  # Commits the staged changes with the message "adding".
git status              # Displays the current status.
git checkout -b dev     # Creates and switches to a new branch called `dev`.
git status              # Displays the status on the new branch.
history                 # Shows the history of terminal commands used.
