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
![IMAGE](data:image/jpeg;base64,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)
@snapend
---
@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend

@snap[south-east span-50 text-center text-06]
[Download GitPitch Desktop @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend

