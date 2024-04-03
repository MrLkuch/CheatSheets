# GIT
### getting started
- Initiate your local repository.

        git init

- Link your local with your remote repository.

        git remote add origin <linkToYourRemoteRepo>

- Add files to your staging before commit.

        git add <file>

- Make your commit.

        git commit -m "your Message"

- Send your work to the remote repo.

    - for the first time

            git push -u origin main

    - after

            git push



### Additional commands

- copy a remote repository, replacing all files with the remote version.

        git clone <linkToYourRemoteRepo>

- receive changes made on the remote repository without replace your files.

        git pull

### Work with a forked repository

After forking the choosen repository start by clone the repository

        git clone <linkToYourRemoteRepo>


### Work with branches

Create branch

        git branch <branchName>

Change branch

        git switch <branchName>

Apply the changes of a branch to the current branch

        git merge <branchName>

> Fast-fortward: the historic is linear <br>
git pull: fetch + merge <br>
git fetch: take the changes of the remote repository and save then in a "hidden branch" <br>
git diff: compare the differences between two branches


### When you made a mistake

- when you want to rollback <br>
        
        git reflog

you will see a list of every thing you've
done in git, across all branches <br>
each one has an index HEAD@{index}
find the one before you broke everything then use :
        
        git reset HEAD@{index}

<br>

- when you need to add a small change while already made the commit

make your change
        git add . # or add individual files

        git commit --amend --no-edit
now your last commit contains that change!
> WARNING: never amend public commits

- rename a commit

        git commit --amend