# Git
- github.com
- bitbucket.com
- gitlabs.com

## VS Code Extension
- GitLens — Git supercharged

## Repository (Repo)
Folder present online to share and maintain code

### Clone: 
```git clone https://github.com/tejashwasharma/example.git```

### Check git config
```git config --list```

### Set Git configs locally
```
git config user.name "tejashwasharma"
git config user.email "tejsharma407@gmail.com"
```

### Set Git configs globally
```
git config user.name "tejashwasharma" --global
git config user.email "tejsharma407@gmail.com" --global
```

### Checkout to branch
```git checkout branch_name```

### Create new branch
```git branch new_branch_name```

### Steps to push code
- ```git add path-to-file.extension```(particular file only)
    or
    ```git add .``` (All files)
- ```git commit -m "commit msg"```
- ```git push origin branch_name```

### To check commit log/history
```git log```

### TO reset commit
```git reset HEAD^1```
