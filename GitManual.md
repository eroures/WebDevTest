# GIT TUTORIAL

## Configuration

After Git is installed open **Git CMD** and run the following commands to configure your Git username and email using the following commands.
These details will be associated with any commits that you create:

```js
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
```

## Start a new git repository

Your first instinct, when you start to do something new:  ***git init***.

## A new repo from scratch || A new repo on existing project

```js
1. Go inside the directory (or create) that contains the project 
2. git init // Create an empty Git repository or reinitialize an existing one
3. git add . //add ALL existing files into the repository
4. git commmit -m 'message' // submit all changes
```

## Connect to github

Now you have a local git repository that you can use, but in case you want to have a home in github:

Go to github.
Log in to your account.
Click the new repository button in the top-right. You’ll have an option there:

![Alternate text](resources\0.png)
![Alternate text](resources\1.png)

Right after that connect the local repository to github

````js
git remote add origin https://github.com/eroures/WebDevTest.git 
git push -u origin master
````

Now we have our repo created and working!

## Creating & Switching Branches

Branching is the way to work on different versions of a repository at one time.

By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.

When you create a branch off the master branch, you’re making a copy of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.

```js
1. Go inside the directory that contains the project 
2. git branch <branchname> // create a branch named <branchname>
3. git branch-show // to check that our branch was succesfully created
4. git checkout <branchname> // switch from our current branch to <branchname>
5. git push origin <branchname> // save changes to remote repository
```

After pushing our changes it should look like this on git: 

![Alternate text](resources\3.png)