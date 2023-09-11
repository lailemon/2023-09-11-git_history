# 2023-09-11-git_history

- `add<FILENAMES>`: adding the <FILENAMES> to the staging area

-   `commit -m "MESSAGE"`: commit with a message everything in the staging area

-   `push <WHERE> <WHAT>` pushes the history/commits to the remote (WHERE) using the commits from the specified branch (WHAT). WHAT = MAIN/MASTER

-   `pull <WHERE> <WHAT>` pulls/updates the local repo with contents in the remote (WHERE) using the information in the specified branch (WHERE)

-   `log`: shows the log
    -   `log --oneline`: shows the log in one line condenced format
    -   this may open a terminal program called `less` that lets you scroll, hit the letter `Q` to quit this program

-   `diff`: shows the modification details between local machine and the last commit. e.g., difference between local files and staging area
