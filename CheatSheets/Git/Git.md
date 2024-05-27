# How to initiate and link your repo with GitHub

## Prepare your remote repository

- Log In your [GitHub Account](https://github.com/)

- On your Profile go in **Repositories** then press **New**

- Fill the **Name** and choose to make your repository
    - Public
    - Private

Congrats ! We're done here for now.


## Initiate your local repository

After creating your directory, open your terminal.

- let's start by telling **_Git_** that we want this folder to become a repository

    in your terminal use the command:

    ```git init```

- the next step is to prepare the content of this fresh depo to be sent to **_GitHub_**

    > [!NOTE]
    > If no files exist don't forget to create one, we can't sent something to GitHub that doesn't exist.

    Type the command ```git add "your_file"``` to add it for your next commit.

- Prepare your commit with ```git commit -m "your commit"```


The only things left are to link your local repository to **_GitHub_**

- After copying the address of your remote repository on **_GitHub_** use the command ``` git remote add origin <your remote repository address>```

    > [!WARNING]
    > **_GitHub_** Doesn't support HTTPS connection anymore with the supression of password authentication when pushing your files.
        If you only plan to pull or clone from a public repository HTTPS is still usable.

- The last step is to push your local files to your remote repository by using ```git push -u origin main```

## You made it !

Your repository is now fully ready and only wait your next 

- add
- commit
- push