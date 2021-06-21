# Using git version 2

1. Linking your local repository (the one on your computer) to remote repositories on GitHub

 - If you **clone** a repository, the command automatically adds that **remote repository** under the name `origin`.


2. The git commands `fetch`, `pull`, `merge`, `push` and `sync`

 - The command `git fetch origin` **fetches** any new work that has been **pushed** to that server since you **cloned** (or last **fetched** from) it.

 - The `git fetch` command only downloads the data to your local repository.

 - If I want get changes from the remote repository called `origin` into my local repository I type `git fetch origin`.

 - It doesn’t automatically merge it with any of your work or modify what you’re currently working on. You have to merge it manually into your work when you’re ready.


 - the `git pull` command is a `git fetch` command followed by a `git merge` command.


 - Git sync does everything in one command meaning pull and push read here

2. Branching

  - To view the branches in a Git repository, run the command `git branch`

  - To see both local and remote branches use `git branch -a` or `git branch --all`

  - To see details of each brach use `git branch -v` or `git brach --verbose`

  - 

  - `git checkout -b BRANCH_NAME` creates a new branch and checks out the new branch

  - `git branch BRANCH_NAME` creates a new branch but leaves you on the same branch.

  - In other words `git checkout -b BRANCH_NAME` does the following for you:

    `git branch BRANCH_NAME    # create a new branch`
    `git switch BRANCH_NAME    # then switch to the new branch`
