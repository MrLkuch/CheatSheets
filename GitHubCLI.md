# GitHub CLI
<p align="center"><img src ="ghcli.png"/></p>



## auth

- ```gh auth login``` : Connect to a github account <br>
- ```gh auth logout``` : Remove authentication for a github account

## repo

- ```gh repo create [<name>] [flags]``` : Create a repository

    Options | effect 
    --- | --- 
    ```-p, --template <repository>``` | Make the new repository based on a template repository
    ```-t, --team <name>``` | The name of the organization team to be granted access
    ```-c, --clone``` | Clone the new repository to the current directory
<br>