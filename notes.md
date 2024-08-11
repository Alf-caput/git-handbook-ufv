# git notes
## Introduction
This document intends to show a simple but consistent workflow using Git, it will not focus on how Git works under the hood, but on how to use it efficiently.

Git is a free and open source distributed version control system (VCS), that tracks changes made to a file or set of files over time, allowing developers to manage different versions of their codebase efficiently.

## 1. Installation (Windows)
For the installation we can leave most of the configurations as they are by default.

However there are 2 options that are highly recommended: 

- **Choosing the default editor used by git**

    By default the editor that git uses for commit messages, merge commits and so on is VI (Visual Improved).
    This editor although is light weight and efficient can be daunting at first.
    For that reason we suggest using a more friendly editor such as VSCode

    ![image info](./images/set-default-editor.png?raw=true)

    Notes: 
    - In case you set Vi as the default editor and by accident you happen to enter the editor, to exit press `Esc` to enter normal mode then `:q!` to exit the file without saving changes 
    - It is possible to change the default editor used by git with the following command
    ```shell
    git config --global core.editor code
    ```
    It is also possible to set the default editor only for the local repo by using the `--local` flag

    Or by editing .gitconfig for the global config on Windows C:\Users\username\.gitconfig

    And for just the local repo under the `.git` folder by editing the `config` file within


