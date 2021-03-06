# Introduction to  **GIT**

---

### TYPES OF VCS

![IMAGE](https://www.perforce.com/sites/default/files/image/2019-05/image-blog-what-is-version-control.jpg)

---?color=linear-gradient(180deg, white 75%, black 25%)
@title[TYPES OF VCS]

@snap[west span-55]
## Centralized VCS
@snapend

@snap[north-east span-45]
![IMAGE](https://scmquest.com/wp-content/uploads/2014/05/central_vcs.jpg)
@snapend

@snap[south span-100]
A centralized system works on a Client-Server relationship. The repository is located at one place and provides access to many clients.
@snapend

---?color=linear-gradient(180deg, white 75%, black 25%)
@snap[west span-55]
## Distributed VCS
@snapend

@snap[north-east span-45]
![IMAGE](https://scmquest.com/wp-content/uploads/2014/05/distributed_vcs.jpg)
@snapend

@snap[south span-100]
In a Distributed System, every user has a local copy of the repository in addition to the central repo on the server side.
@snapend

---
### WHAT IS GIT?

![IMAGE](https://git-scm.com/images/logos/downloads/Git-Icon-White.png)

---?color=linear-gradient(180deg, white 75%, black 25%)
@snap[west span-55]
## GIT
@snapend

@snap[east span-45]
![IMAGE](http://bryanavery.co.uk/wp-content/uploads/2017/05/capture_stepup1_5_6.png)
@snapend

@snap[south span-100]
Git is a distributed version-control system for tracking changes in source code during software development.
@snapend
---
### GIT STATES

![IMAGE](https://4.bp.blogspot.com/-2oRkFnCKNjs/XLvkR-un41I/AAAAAAAAU4c/Sl-D81Nm8tgKM61PQbn3_GKgUAUqx8i5wCLcBGAs/s1600/git-workflow-codemio.png)

---
### TRACKED VS UNTRACKED

>In short, ***tracked files*** are files that Git knows about. ***Untracked files*** are everything else — any files in your working directory that were not in your last snapshot and are not in your staging area.

---?color=linear-gradient(180deg, white 65%, black 35%)
@snap[north-west span-55]
## STAGED
@snapend

@snap[north-east span-45]
![IMAGE](https://miro.medium.com/max/686/1*diRLm1S5hkVoh5qeArND0Q.png)
@snapend

@snap[south span-100]
A staging step in git allows you to continue making changes to the working directory, and when you decide you wanna interact with version control, it allows you to record changes in small commits.
---
> Suppose you have edited three files (***a.html***, ***b.html***, and ***c.html***). After that you need to commit all the changes so that the changes to ***a.html*** and ***b.html*** were a single commit, while the changes to ***c.html*** were not logically associated with the first two files and were done in a separate commit.
---
> git add a.html

> git add b.html

> git commit -m "Changes for a and b"

***

>git add c.html

>git commit -m "Unrelated change to c"
@snapend
---?color=linear-gradient(180deg, white 65%, black 35%)
@snap[north-west span-55]
## Commited
@snapend

@snap[north-east span-45]
![IMAGE](https://www.earthdatascience.org/images/workshops/version-control/git-add-commit.png)
@snapend

@snap[south span-100]
The "commit" command is used to save your changes to the local repository. Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. 
---?color=linear-gradient(180deg, white 65%, black 35%)
@snap[north-west span-55]
## MODIFIED
@snapend

@snap[north-east span-45]
![IMAGE](https://i.stack.imgur.com/kslSd.png)
@snapend

@snap[south span-100]
As you edit files, Git sees them as modified, because you’ve changed them since your last commit. As you work, you selectively stage these modified files and then commit all those staged changes, and the cycle repeats.
---
@title[WHY GIT?]

@snap[north-west span-50 text-center]
#### WHY GIT?
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- ***Feature Branch Workflow***
- ***Distributed Development***
- ***Pull Requests***
- ***Faster Release Cycle***
@ulend
@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend
---
@snap[west span-55]
***Building Your Code Résumé on GitHub***

> Eventually, students graduate and enter the workforce, and having coding skills on your résumé upon graduation is paramount for most of the big companies in the area.GitHub has become the platform of choice for showcasing coding projects to potential employers.
@snapend

@snap[east span-45]
![IMAGE](https://user-images.githubusercontent.com/1387653/45539771-86065a80-b7bf-11e8-8d44-d9878cbae054.gif)
@snapend
---
@snap[north-west span-50 text-center]
#### I would recommend using Git if: 
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- ***You manage a repository of code for an ongoing experiment or project.***
- ***You write a lot of complex or collaborative documents in LaTeX.***
- ***You might need a portfolio of coding projects in the future.***
@ulend
@snapend

@snap[east span-45]
![IMAGE](https://miro.medium.com/max/2732/1*qwFrTMnFkcd3U9rFKwwacw.png)
@snapend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands
@snapend
@ul[list-spaced-bullets text-09]
- ***git init***-creates an empty repo on your local drive
- ***git status***-displays the state of the working directory and the staging area. *It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.*
- ***git add***-adds a change in the working directory to the staging area.*It tells Git that you want to include updates to a particular file in the next commit.*
@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***git add .***-adds all modified and new (untracked) files in the current directory and all subdirectories to the staging area (a.k.a. the index)
- ***git commit***-The "commit" command is used to save your changes to the local repository.*Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command.**add a commit message*
@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***git checkout -b <branch name>***-git checkout command lets you navigate between the branches.Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.
- ***git remote add***-The git remote add command takes two arguments: A remote name, for example, “origin” A remote URL, which you can find on the Source sub-tab of your Git repo.*It links your local repository with a remote repository. Local repository is on your machine. Remote repository is the central repository. *
@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***git push***-git push command allows you to send (or push) the commits from your local branch in your local Git repository to the remote repository. To be able to push to your remote repository, you must ensure that all your changes to the local repository are committed.
- ***git pull***-pulls the master branch from the remote called origin into your current branch.*git pull is essentially a combination of git fetch and git merge ; it fetches the remote branch then merges it into your current branch.*
@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***conflict***-Git can handle most merges on its own with automatic merging features. A conflict arises when two separate branches have made different edits to the same line in a file, or when a file has been deleted in one branch but edited in the other. Conflicts will most likely happen when working in a team environment.
- ***git fetch***-The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on.
- ***git merge***-The "merge" command is used to integrate changes from another branch.

@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***git merge***-The "merge" command is used to integrate changes from another branch.
- ***git revert***-The git revert command is a forward-moving undo operation that offers a safe method of undoing changes.*Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified. Git revert is a safer alternative to git reset in regards to losing work.*
@ulend
---
@snap[north-centre span-100 text-pink text-15]
Basic Git Terminology & Commands(cont.)
@snapend
@ul[list-spaced-bullets text-09]
- ***git reset***-git reset is a powerful command that is used to undo local changes to the state of a Git repo*Git reset operates on "The Three Trees of Git". These trees are the Commit History ( HEAD ), the Staging Index, and the Working Directory.*
- ***git rebase***-the rebase command integrates changes from one branch into another. It is an alternative to the better known "merge" command.*Most visibly, rebase differs from merge by rewriting the commit history in order to produce a straight, linear succession of commits.*
@ulend
---?image=https://github.githubassets.com/images/modules/logos_page/Octocat.png&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend



