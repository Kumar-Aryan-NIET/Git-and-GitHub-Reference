# Git-and-GitHub-Reference

```python
1.    What is Version Control System and its Types
2.    What is Git?
3.    What is GitHub?
4.    And the difference between the two.
```

# What is Version Control System?

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/96ea5c7d-0a05-4f58-b90a-397b904c17a4)

- VCS or version control 
  - is a management system 
  - that tracks changes in a computer file.

- It is a software tool that records and manages changes 
  - to the source code over a period of time.

###### Q. imagine that you are working with your friend on a shared document and two of you are making changes in the file at the same time, what will happen? How will you track the change and mark the owner of the same? Or maybe you are working in a large team, how will you manage then?

- It helps developers to work efficiently.

### A version control system can do these for you
    - rollback and revert files back to a previous state or 
    - revert the entire project back to a previous state, 
    - compare changes over time, 
    - see who last modified something that might be causing a problem, 
    - who introduced an issue and when, and more, .

### Types of Version control

Basically there are three major types of VCS.

1. Local Version Control Systems
2. Centralized Version Control Systems
3. Distributed Version Control Systems

# What is Git?

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/f6c41e2d-fd8c-493a-a8f0-c4c8ec684948)

official Link to Dowload
- https://git-scm.com/download/win

- Git is one of the most popular Version Control System.
- Git was originally developed in 2005 by the creator of Linux.
- Git is free and open-source software so, anyone can use it.

# What is GitHub?

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/28ba087b-5424-4409-9b6a-e3649dde9b30)

GitHub 
- is one of the most advanced and developed hosting platforms 
  - for version control and collaboration. 
- It is a web-based service for version control using Git 
  - has all the benefits of git and even more.

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/c84399ed-34e5-47b2-b835-b3605c1d81e2)
![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/eb90fd1b-bb6b-4b40-9bc2-68932f5d0a7f)

Set user name and email – Git
- git config --global user.name "Your Name"
- git config --global user.email youremail@example.com

To confirm it

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/4da995c4-5c29-4644-a1e5-0c98ea2b4d44)
![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/97f467ba-a0de-4ab4-8437-7786c3961c2e)

- change like adding / deleting etc. 
   - it's history will save in "git repository" named ".git"
  
- how do we get this folder ?
   - git init - initialize an empty git repository (means folder)

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/e9690eb6-69eb-44a2-b266-43a202961e59)

```python
cd "FolderLocation" ~ Change Directory

ls                  ~ Show all file in directory (Not the hidden once)

ls -a               ~ Show all hidden file (files start with ".")

ls ".FolderName "   ~ Show what folder contians.
```


```python
touch "FileName.Extension"   ~ create file

git status                   ~ what are the changes made in the project which is not currently saved in terms of record
                             ~ tells about the changes which are not in the history of your project
                             ~ show untracked file
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/732ee6b1-6784-481b-8bac-cae9634f8b19)

- Untracked File (Red File) ~ like "Main.java" above means they are in "Staging Area"


```python
git add "."(all untracked file) or "FileName"(particular file) ~ Save untracked file history in git repositry
```
![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/e915763b-1cfa-45b3-b3fc-20f9e9d581d3)

```python
green file like "main.java" above means they are at stage Area and now we can commit.
```


```python
git commit -m "message"  ~ allow to write description about last last tracked files. 
                         ~ and show which type of change occur
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/8dc60713-198b-4bc0-bc88-d87db0307dae)


 ############################################################################

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/bdb68d48-a15f-435d-bcd1-794d1cdd6039)


- above status means there is no untracked file and all you changes are recorded


```python
vi "FileName.Ex.."  ~ view, write and modify the file content
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/b09eb726-1ad5-45cd-8c89-4706f3a83da4)

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/f80bfb3f-03a7-4852-88d5-29cb94217493)


```python
press "esc" and then press ":x" to exit
```


```python
cat "FileName.Ex.." ~ only show the file content in terminalgit 
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/40b97e7e-a479-4982-bf0d-06612d8ad81a)

#############################################################################

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/d3c33b93-1f51-496e-87f2-ae83a9b1353f)

- above status shows modification in file 

### by using git add .

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/a802123d-99e4-4956-98b9-0056bb3b6668)

git restore --staged <FileName>          ~ used to unstage

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/7c070d74-95d4-4920-afcb-5588308a0a78)


```python
git restore  ~ to discard changes in working directory
```


```python
git log      ~ used to view the history
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/47d1c557-6f20-4f2a-b5a5-60d6c3f1b924)

```python
rm -rf <FileName>    ~ used to remove file
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/942ec903-a931-47e8-b7ff-f0270ab3de0e)

```python
- you can not directly remove a commit from anywhere
- for remove it, unstage them upto that commit you want to remove 
  - from top to bottom

- copy the commit id just below it
- use "git reset <commit id>" to unstaged changes after reset those commit
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/e57946bf-1d2c-4029-be6a-08ca8c6ff2cc)


```python
now the other are go to unstaged area
```



### FIRST satage the changes

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/6e4261d8-fd9e-47f8-b829-88dcc36ccc4f)

### Git stashing

- Don't want to commit and don't want to lose these changes
- use "git stash"
  - basically want you to go back stage and 
  - when ever I want you I bring you back

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/5e66661b-acbc-4f62-be12-9710674c1d50)

#### how to bring back to staging area
- use "git stash pop"

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/9db4fce3-d178-4175-9356-32606f1c032a)

- not committed and in the saperate structure ( at back stage)
- To remove them
  - Use "git stash clear"

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/6ab9896c-f3e6-4666-8d7a-ce3d38e6e7ed)
![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/6e70c7cf-8daa-4d01-84c8-d68073b5dbb3)

```python
git    - means git
remote - means you are working with url
add    - add a new url
origin - name of the url
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/fc484c1d-d9b5-493d-8c1d-c4c344be6a79)


###### git remote -v ~ show you all url attached to that folder

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/ef374a62-854f-48af-9410-625e39074b00)

- To share the changes at that url
  - Use "git push origin master"

Where,
- origin -  url name
- master - branch

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/635245bb-1d60-4fe4-a8fa-ea3784aab52f)

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/ef340e2a-fa8d-493f-94d2-618a17767414)

## Setup SSH Key to GitHub

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/ceffab7c-7ef5-4761-ba2d-3282720747eb)

```python
"ssh-keygen -t ed25519 -C 0211ite107@gmail.com"  ~ generate pulic and private key pair
```

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/6f1eba3e-3fbf-4d45-b103-30f1b5efb79b)


```python
"clip < ~/.shh/id_ed25519.pub" ~ Clip SSH Keys to clipboard (so you can paste SSH Keys anywhere after it directly)
```
![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/ae316a50-c5ba-4f4a-9876-c878c529f629)

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/f39e65cc-403c-40e9-9685-c31da8c3c157)

# Push The Repository

![download](https://github.com/Kumar-Aryan-NIET/Git-and-GitHub-Reference/assets/101974240/c1eaa6dc-02c9-4302-ad29-d1ab4d4069f7)
