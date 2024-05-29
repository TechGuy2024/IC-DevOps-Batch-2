

# Git Commands Scribe Sheet Prepared by
Shabbir Hoshen
IC_Student_ID_44
IC-DevOps-Batch-2
Mobile: 01913310310
Email: shabbir6646@gmail.com

## Below are explanations of common Git commands:

#### Adding Name to the git.
```git config --global user.name "name" ```


#### Adding Name to the git.
```git config --global user.email "email"```


#### This command will show user and email associeted
```git config -l ```

#### Initialize an empty Git repository in the current directory.

```git init```

#### Clone a repository into a new directory.

```git clone <repository-url>```

#### Add specific file.

```git add <file>```

#### Add all file which are created and make change

```git add .```

#### Remove file from the git.

```git rm <file>```

#### Restore file which was removed before.

```git restore <file>```

#### Record changes to the repository with a message.

```git commit -m "message"```

#### To see any remote link of remote repository.

```git remote```

#### To see URL of remote repository.

```git remote -v```

#### To add original URL address to the repository

```git remote add origin <URL>```

#### Update remote refs along with associated objects.

```git push```

#### Update remote refs along with associated objects in main branch or in any other branch.

```git push -u origin main```

#### Fetch from and integrate with another repository or a local branch.

```git pull```

#### List, create, or delete branches.

```git branch```

#### Switch branches or restore working tree files.

```git checkout <branch>```

#### Create new branch and Switch branches or restore working tree files.

```git checkout -b <branch>```

#### Join two or more development histories together.

```git merge <branch>```

#### Show the working tree status.

```git status```
#### Show commit logs.

```git log```