# Version Control and Branch Management ( Git )
## Versioning
--------------------------------------------------------
Versioning mengatur versi dari source code progrram
Tools :
Version Control System ( VCS )
Source Code Manager ( SCM )
Revision Control System ( RCS )
## Version Control System
--------------------------------------------------------
1.	Single User
    - SCCS – 1972 Unix only
    - RCS – 1982 Cross platform, text only
2.	Centralized
    - CVS – 1986 File Focus
    - Perforce – 1995
    - Subversion – 2000 – track directory structure
    - Microsoft Team Foundation Server – 2005
3.	Distributed
    - Git – 2005
    - Mercutial – 2005
    - Bazaar – 2005
## GIT
--------------------------------------------------------
Salah satu version control system yang digunakan developer untuk mengembangkan software secara bersama – sama. Dengan adanya git dapat dilakukan collaboration. Pemanfaatan git secara terdistribudi bukan tersentralisasi yang dibuat oleh linys torvalds ( 2005 ).
### Git repository
    - Berisi folder dan file serta history
### Tools
    - Github - Bagi developer github layaknya seperti sosoal media dan github dapat melakukan kontribusi pada programing
### Instalasi git for Windows
    - Download versi terakhir git for windows installer
    - Kemudian lakukan instalasi pada git setup
    - Kemudian check version dengan git –version.
### Setting up
Git init, clone, config
- Melakukan git config pada git bash

```$ git config --global user.name "nama"```

```$ git config --global user.email "email"```
- Untuk melihat username dan email

```$ git config –list```
- Start with init

```$ git init```

```$ git remote add <remote_name> <remote_repo_url>```

```$ git push -u <remote.name> <local_branch_name>```
- Start with existing project, Start working on the project

```$ git clone <remote_repo_url>```

```$ cd <repo_name>```
### Saving Changes

- Staging Area

Work directory -> git add -> staging area -> git commit -> repository

- Git status, add, commit

```$ git status```

```$ git add <directory>```

```$ git add .```

```$ git commit -m “message”```

- Git diff and stash

git diff

```$ git diff –-staged```

stashing

```$ git stash```

re-applying stashed changes

```$ git stash apply```

### Inspecting Repository
- Git log, checkout

viewing an old revision

```$ git log –-oneline```

checkout

```$ git checkout <branch>```

Git reset

```$ git reset --soft```
```$ git reset --hard```

### Syncing

- Git push, fetch, and pull

git remote

```$ git remote -v```

```$ git remote add origin <repo_url>```

fetch and pull

```$ git fetch```

```$ git pull origin master```

push

```$ git push origin master```
```$ git push origin feature/login-user```
### Braches
- Git branching

show all branch

```$ git branch --list```

create a new branch called < branch >

```$ git branch <branch>```

force delete the specified branch

```$ git branch -D <branch>```

list remote branch

```$ git branch -a```

- Git Merge

start a new feature

```$ git checkout -b new-featur master```

Edit some file

```$ git add <file>```

```$ git commit -m “message”```

Merge in the new-feature branch

```$ git checkout master```

```$ git merge new-feature```

```$ git branch -d new-feature```

# Task Github
## 1. Membuat Repository dan Membuat Project di Github
Repository yang dibuat dengan nama 2_version-control-and-branch-management-git dan dengan nama project ATM Project.

Link Github dibawah ini :

[2_version-control-and-branch-management-git](https://github.com/fhallatu/2_version-control-and-branch-management-git.git)


Output :

<img src= Screenshots/2.PNG>

## 2. Membuat Branch Development
Link Github dibawah ini :

[2_version-control-and-branch-management-git](https://github.com/fhallatu/2_version-control-and-branch-management-git.git)

Output :

<img src= Screenshots/4.PNG>

## 3. Membuat Branch Ketiga Untuk Penambahan Fitur dan Lakukan Merge ke dalam branch Development
Link Github dibawah ini :

[2_version-control-and-branch-management-git](https://github.com/fhallatu/2_version-control-and-branch-management-git.git)

Output :

<img src= Screenshots/9.PNG>

## 4. Membuat Branch Keempat Untuk Penambahan Fitur dan Lakukan Merge ke dalam branch Development
Link Github dibawah ini :

[2_version-control-and-branch-management-git](https://github.com/fhallatu/2_version-control-and-branch-management-git.git)
Output :

<img src= Screenshots/15.PNG>

## 5. Didapatkan Hasil Insights => Network

<img src= Screenshots/16.PNG>
