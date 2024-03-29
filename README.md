# GitHub-Notes

## GIT

**Git is a version control system also known as a **VCS**.**

  > **VCS** is basically some software designed to record changes made to a file or set of files overtime. 
 
**This gives you the ability to revert or recall changes to a file or set of files after you've made them.**

## GitHub

**GitHub is a collaboration platform built on top of Git, this distributed version control system.**

**all of work is organized into branches.**

  > these **branches** like a timeline on how project has changed over time. 

**There's one branch by default that is automatically created the first time any project is initialized with Git. This branch is called Master.**

  > **Master Branch** is a record of all the changes that have happened in my project. 

when it comes to making changes to project, whether it's a **hot fix change**, **feature edition**, or **bug fix**, it doesn't make a lot of sense to make those changes directly on the **Master Branch**. That's going live to Production. 

  > **So when you want to make these changes, you want to make a new line of work, a new timeline if you will, that represents the new changes that I want to make.**

to make the actual changes I want to make on my project. These changes are made in the form of **Commits**.

  > **A Commit is Git's way of adding a change to your project.**
  
**These Commits are recorded in history so you can always go back and review or analyze these past Commits to a project.**

## Install Git on Linux

### 1. From your shell, install Git using apt-get:

```shell
sudo apt-get update
```
```shell
sudo apt-get install git
```

### 2. Verify the installation was successful by typing git --version:

```shell
git --version
```
> git version 2.25.1

### 3. Configure your Git username and email using the following commands.

> These details will be associated with any commits that you create:

```shell
git config --global user.name "M0xYasser"
```
```shell
git config --global user.email "midyass17@gmail.com"
```

### 4. Make "Git" store the username and password and it will never ask for them.

```shell
git config --global credential.helper store
```

### 5. Save the username and password for a session (cache it);

```shell
git config --global credential.helper cache
```

## Cloning a Git Repository

```shell
git clone REPO_URL
```
## push changes to remote

```shell
git add *
```
```shell
git commit -m "message"
```
```shell
git push
```
## Status

```shell
git status
```

## Adding a Working Directory to Staging Area

```shell
git add FILE_NAME
```
**OR To add all file use * :**
```shell
git add *
```
