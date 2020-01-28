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
A Distributed System, every user has a local copy of the repository in addition to the central repo on the server side.
@snapend

---
@title[Add A Little Imagination]

@snap[north-west span-50 text-center]
#### Engage your Audience
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- You will be amazed
- What you can achieve
- With a **little imagination**
- And GitPitch Markdown
@ulend
@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend

@snap[south span-100 bg-black fragment]
@img[shadow](assets/img/conference.png)
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

