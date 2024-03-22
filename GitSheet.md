# GIT

- Initiate your local repository.

        git init

- Link your local with your remote repository.

        git remote add origin <linkToYourRemoteRepo>

- Add files to your staging before commit.

        git add <file>

- Make your commit.

        git commit -m "you Message"

- Send your work to the remote repo.

    - for the first time

            git push -u origin main

    - after

            git push


- copy a remote repository, replacing all files with the remote version.

        git clone <linkToYourRemoteRepo>

- receive changes made on the remote repository without replace your files.

        git pull