# 2023-09-11-git_history

- `add< FILENAMES>`: adding the <FILENAMES> to the staging area

-   `commit -m "MESSAGE"`: commit with a message everything in the staging area

-   `push <WHERE> <WHAT>` pushes the history/commits to the remote (WHERE) using the commits from the specified branch (WHAT). WHAT = MAIN/MASTER

-   `pull <WHERE> <WHAT>` pulls/updates the local repo with contents in the remote (WHERE) using the information in the specified branch (WHERE)

-   `log`: shows the log
    -   `log --oneline`: shows the log in one line condenced format
    -   this may open a terminal program called `less` that lets you scroll, hit the letter `Q` to quit this program

-   `diff`: shows the modification details between local machine and the last commit. e.g., difference between local files and staging area; shows you the difference between your changes and hte last known commit
    -   `diff --staged`: shows the modification details in the last commit - for checking staged changes
    -   `diff <FILENAME>`: shows only the difference in a certain file instead of the whole git folder

-   `restore --staged <FILENAME>`: unstages a file from the staging area

-   `touch`: change the modify time to current timestamp
    -   `touch <FILENAME>`: create a new file, or change modification time to current

-   `touch .gitignore`: create a git ignore file that stores all files (by filename) or specific file types (by *FILE EXTENSION, e.g., *.pdf)
    `code .gitignore`: opens up the .gitignore file to make changes to the ignore list
