# GIT TUTORIAL

## Configuration

After Git is installed open **Git CMD** and run the following commands to configure your Git username and email using the following commands.
These details will be associated with any commits that you create:

```js
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
```

## Start a new git repository

Your first instinct, when you start to do something new, should be git init. You’re starting to write a new paper, you’re writing a bit of code to do a computer simulation, … anything: think ***git init***.

## A new repo from scratch || A new repo on existing project

```js
1. Go inside the directory (or create it) that contains the project 
2. git init // Create an empty Git repository or reinitialize an existing one
3. git add . //add ALL files into the repository
4. git commmit -m 'message' // submit all changes
```
