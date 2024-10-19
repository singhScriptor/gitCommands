# Git Command Cheat Sheet

## Basic Git Commands

- **Initialize a New Git Repository**:
    ```bash
    git init
    ```

- **Clone a Repository**:
    ```bash
    git clone <repository-url>
    ```

- **List Directories and Files**:
    ```bash
    ls
    ```
    

## Staging and Committing Changes

- **Add Specific Files to Staging Area**:
    ```bash
    git add <file-path>
    ```

- **Add All Changes to Staging Area**:
    ```bash
    git add .
    ```

- **Commit Changes with a Message**:
    ```bash
    git commit -m "Commit message"
    ```

- **Amend the Last Commit**:
    ```bash
    git commit --amend -m "New commit message"
    ```

## Pushing Changes

- **Push to the Remote Repository**:
    ```bash
    git push origin <branch-name>
    ```

- **Force Push to the Remote Repository**:
    ```bash
    git push --force origin <branch-name>
    ```

## Removing Files

- **Remove a File**:
    ```bash
    git rm <file-path>
    ```

## Handling Branches

- **Create a New Branch**:
    ```bash
    git branch <new-branch-name>
    ```

- **Switch to a Branch**:
    ```bash
    git checkout <branch-name>
    ```

- **Create and Switch to a New Branch**:
    ```bash
    git checkout -b <new-branch-name>
    ```

- **Delete a Branch**:
    ```bash
    git branch -d <branch-name>
    ```


## Deleting Remote Branch

- **Delete a Remote Branch**:
    ```bash
    git push origin --delete master
    ```
    

## Merging and Syncing

- **Merge a Branch into Current Branch**:
    ```bash
    git merge <branch-name>
    ```

- **Pull Changes from Remote**:
    ```bash
    git pull origin <branch-name> --allow-unrelated-histories
    ```

## Viewing and Logging

- **Check the Status of the Repository**:
    ```bash
    git status
    ```

- **View Commit History**:
    ```bash
    git log
    ```

## Stashing Changes

- **Stash Changes** (temporarily save changes without committing):
    ```bash
    git stash
    ```

- **Apply Stashed Changes**:
    ```bash
    git stash apply
    ```

## Remotes

- **Check Which Repositories are Connected Remotely**:
    ```bash
    git remote -v
    ```



## Moving and Updating Files

- **Move Files to a Different Directory**:
    ```bash
    mv <source-path> <destination-path>
    ```

- **Update Git After Moving Files**:
    ```bash
    git add <destination-path>
    git rm <source-path>
    git commit -m "Move files"
    git push origin <branch-name>
    ```
    

 🚀
