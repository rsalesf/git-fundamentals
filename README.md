### Git Fundamentals

#### File status life-cycle
![Drag Racing](./images/git-files-life-cycle.jpg)

#### Basic Commands

```shell
#initialize an empty repository
git init
```

```shell
#define a git author
git config --global user.email
git config --global user.name
```

```shell
#move all modified/untraked files to staging area
git add *
```

```shell
#take a snapshot for the current repository (local repository)
git commit -m "my first commit"
```

Tips:

​	```git log``` [command](https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History) show all the commits made to a repository.

​	```git status``` command to see the status of working directory and stating area.
