# Git Commands for DevOps

## Initial Setup
1. **Create Directory and Initialize Git Repository**
    ```bash
    mkdir git-for-devops
    cd git-for-devops/
    pwd  # Print the current working directory
    git init  # Initialize an empty Git repository
    ```

2. **Create Files and Add to Staging Area**
    ```bash
    touch file.txt file2.txt  # Create two new files
    ls  # List the files in the directory
    git add file.txt  # Add file.txt to the staging area
    git status  # Check the status of the repository
    git add .  # Add all changes in the current directory
    ```

3. **Commit Changes**
    ```bash
    git commit -m "this is commit"  # Commit with a message
    ```

4. **Configure Global Git Settings**
    ```bash
    git config --global user.name "rutujachandurkar03"
    git config --global user.email "rutujachandurkar96@gmail.com"
    ```

5. **View Commit Logs**
    ```bash
    git log  # View the commit history
    ```

## Making Changes
1. **Create and Edit New Files**
    ```bash
    vim file1.txt  # Edit file1.txt
    git add .  # Stage all changes
    git commit -m "new file"  # Commit the changes with a message
    git log  # View the updated commit history
    ```

2. **Branching**
    ```bash
    git checkout -b dev  # Create and switch to a new branch 'dev'
    touch file3.txt  # Create another file
    git branch  # List all branches
    git add .  # Stage all changes
    git commit -m "this is file"  # Commit with a message
    ```

3. **Switching Between Branches**
    ```bash
    git checkout master  # Switch back to the 'master' branch
    git checkout dev  # Switch to the 'dev' branch
    ```

## Viewing Logs and History
1. **Log and History**
    ```bash
    git log  # View commit history
    history  # View command history
    ```
