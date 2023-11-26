
# Versioning Git and Github


Repository to store some resumes from classes from [DIO](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/f3cbaa66-efbd-4c25-842e-2069c188c066?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined) about Versioning with git and github.

## 📚 Documentation

- [Documentation Git](https://git-scm.com/docs/git/en)
- [Documentation Github](https://docs.github.com/en)

## 🖥 Overview from Classes

|Class|Overview|
|---|---|
|Creating and cloning repositories|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|
|Saving changes in a local repository|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|
|Unmaking changes in the local repository|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|
|Sending and downloading changes with the remote repository|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/dd17c56e-2327-493c-942a-358a49a26549?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|
|Working with branches pt.1|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/2c7fd2b1-e7c4-4947-9b07-ffcbfb4bd689?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|
|Working with branches pt.2|[Video Class](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/80018fab-daac-4917-8527-a6be2e0c3cf0?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)|



## 👨‍💻 Useful Terminal Commands

```
mkdir [name]
```
Makes a new directory

---

```
cd [local]
```

Changes the directory to the specified one

---


```
touch [name]
```

Creates a empty file with the name specified

---

```
clear
```

Cleans the command prompt

---

```
rm -rf .git
```

Deletes a wrong initialized repository

## ⌨ Git Commands

###### Here are some useful commands to use to version the code:

---

### git init

```
git init
```

Inicializes a repository in the local file

---

### git clone

```
git clone [local]
```
Clones a remote repository to a local repository

---

```
git clone [local] [name]
```

Changes the name of the cloned repository

---
```
git clone [local] --branch [branchName] --single-branch
```

Clones a specific branch from the remote repository

---

### git status

```
git status
```
Prints the status of your files, if they are commiteds or not, altered or not in the selected branch

---

### git log

```
git log
```

Shows the lasts commits

---

### git add

```
git add [file name]
```
Adds the files selected by the name into the commit

To add all the files to the commit,is necessary to use the command:

``` 
git add .
```
---

### git commit

``` 
git commit -m "[message]"
```

Commits the added code to the branch

---

``` 
git commit --amend -m "[new message]"
```

Changes a message from the last commit

---

### git reset

``` 
git reset [name]
```

Undo the commit selected by the name of the file

### git reset --soft

``` 
git reset --soft [hash]
```

(Use git log to obtain the hash from the last commit)

git reset --soft [hash] gets the files from the later commit and puts them into the preparation area 

---

### git reset --mixed

``` 
git reset --mixed [hash]
```
This is the pattern state of git reset, it can be also written only by [git reset].

Adds the later files in the work tree indicating the files as "untracked files"

---

### git reset --hard

``` 
git reset --hard [hash]
```

Ignores the files from the previous commit, deleting them 

---

### git restore

``` 
git restore [name]
```

Recovers the last saved files/data from the commits

---
### git checkout

```
git checkout -b [name]
```

Leaves from the current branch, creating another one with the name specified

```
git checkout [name]
```

Trade from the current branch to the specified one

---
### git branch

```
git branch 
```
Lists the branches in the repository

---

```
git branch -M [name]
```
Changes the name of the main Branch of the project

---

```
git branch -v
```
Show the last commit from each branch

---
```
git branch -d [name]
```
Deletes a branch from the repository

---

### git fetch

```
git fetch origin [branch]
```

Downloads the changes in the remote repository without merge them automatically int the local repository

---

### git diff

```
git diff [branch1] [branch2]
```

Shows the differences between the two selected branches

---

### git stash

```
git stash
```

Arquive a change made on a branch

---

```
git stash list
```

Lists the arquived changes

---

```
git stash pop
```

Brings back the marquived change and exclude the most recent change

---

```
git stash apply
```

Mantains the change on the list to a later use of it

### git merge

```
git merge [name]
```
Specifies wich branch will be merged with the current branch

---

### git remote

```
git remote add origin [local]
```
Adds a remote repository origin to the project

---
```
git remote -v
```
Show the linked repository

---

### git push

```
git push -u origin main
```

Sends the code commited to the remote origin

---

### git pull

```
git pull
```

Gets the code from the remote repository to the local repository

---

## ❌ Gitignore

To have a file ignored by git, its necessary to add the path to the file in Gitignore

```
echo [local file name] > .gitignore
```
---

## ✔ Gitkeep

Git ignores automatically empty files, to keep them into commits, and github, its necessary to add a file into it, normally named .gitkeep 

```
touch [local]/.gitkeep
```

## 🔎 References

[DIO - Digital Innovation One](https://www.dio.me/)

[Git documents](https://git-scm.com/docs)

[Github documents](https://docs.github.com/en)

[Windows CMD documents](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)

