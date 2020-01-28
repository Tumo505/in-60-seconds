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

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- ***Building Your Code Résumé on GitHub***Eventually, students graduate and enter the workforce, and having coding skills on your résumé upon graduation is paramount for most of the big companies in the area.GitHub has become the platform of choice for showcasing coding projects to potential employers.

@ulend
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

