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
1. Go inside the directory (or create it) that contains the project 
2. git init // Create an empty Git repository or reinitialize an existing one
3. git add . //add ALL files into the repository
4. git commmit -m 'message' // submit all changes
```

## Connect to github

Now you have a local git repository that you can use, but in case you want to have a home in github:

Go to github.
Log in to your account.
Click the new repository button in the top-right. You’ll have an option there 

![Alternate text](resources\0.png)

to initialize the repository with a README file, but I don’t.
Click the “Create repository” button

Once done

````js
git remote add origin https://github.com/eroures/WebDevTest.git //connecting the local repository to github 
git push -u origin master
````
