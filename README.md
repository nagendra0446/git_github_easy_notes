# Git2 and GitHub2

1. [What is Git?](#1)
2. [What is GitHub?](#2)
3. [Working with Git](#3)

    3.1. [Git Work Flow](#3.1)

    3.2. [Creating a Repository](#3.2)

    3.3. [Working with Staging Area](#3.3)

    3.4. Commit Files

    3.5. Branches in Git

4. Working with GitHub

    4.1. Creating a remote repository

    4.2. Configuring remote repository

    4.3. Push/Pull changes with the remote repository. 

    4.4. Pull requests

    4.5. Fork

    4.6. Clone

<a name="1"></a>
# 1. What is Git ?

### Git is a Version Control System which can track changes in a project. These changes can be tracked and merged in case of multiple contributors to the project.

### Git is a Distributed Version Control System, where GitHub can be used to push/pull changes of a local machine into the remote Git Repository.

### Git was developed by Linus Torvalds in 2005.
 
<a name="2"></a>
# 2. What is GitHub ?

### GitHub is *one* of the platforms which offers the Distributed Version Control System or Source Code Management(SCM) for the Git Repositories.

### This platform also allows collaboration among the developers.

### GitHub was developed by four developers(Chris Wanstrath, P. J. Hyett, Tom Preston-Werner and Scott Chacon) in 2008.

<a name="3"></a>
# 3. Working with Git

<a name="3.1"></a>
## 3.1. Git Work Flow

The changes in the code can be classified as:

1. Un-staged / staged changes
2. Un-committed / committed changes.

<a name="3.2"></a>
## 3.2. Creating a Git repository

A Git repository generally represents a single project. After downloading and installing Git from [https://git-scm.com/downloads](https://git-scm.com/downloads), 

**Step 1:** Select an empty or existing directory which is the root folder of a project.

**Step 2:** Use

```bash
git init
```
<a name="3.3"></a>
## 3.3. Working with Staging Area or Index

Staging area acts as an intermediate region
