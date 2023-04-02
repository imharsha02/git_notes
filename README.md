# git_notes

### Clone a repository from github to local computer:
```git
git clone urlOfGitHubRepository
```

### Track file changes
```git
git add .
```
the '.' tells git to make a note of changes made to all the files in the repository(repo)

### Saving files to git
```git
git commit -m "Some message"
```

### Upload file to online git repo
```git
git push
```

### Download changes from remote repo to local machine
```git
git pull URLOfGitHubReop
```

### Create a markdown file after creating a repo
1) Click the new file option
2) Name the new file with the '.md' extension

### show the files that are not commited yet
```git
git status
```

### See different branches
```git
git branch
```
* beside the branch name means that we are currently on that branch
the 'q' key is used to quit that page and get back to the home page in the terminal

### To switch between branches
```git
git checkout branchName
```

### To create a new branch
```git
git checkout -b newBranchName
```
If the changes to the file are staged and commited in a branch that is not the default one, then the files are staged and commited to the new branch and there will be no connection b/w these two branches

### To know the new lines added or modified in the new branch(since the changes to the branch)
```git
git diff newBranchName
```
