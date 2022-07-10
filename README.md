# How to use basic git! 🖥

I made this repository for people who don't know how to use git and might want to start with it and for me when i eventually forget all of this stuff and need it!

Also i'm kinda aware that VSCode has it's own source code with github thingy on the side-bar, but i still think it's important to learn these kind of things 

If i missed something i might update it some day

<div align="center">
<img width="160px" src="https://camo.githubusercontent.com/ea09d843e584c4c4365baf0f1b8e691a36e7355536170ea93d45ca58308e507a/68747470733a2f2f6769746875622e6769746875626173736574732e636f6d2f696d616765732f6d6f6e612d6c6f6164696e672d6461726b2e676966">
</div>

> Be aware that to follow this tutorial you should have downloaded git and optionally CLI-GH (GitHub for command line)<br>

> You can download those here:
- https://git-scm.com/downloads
- https://cli.github.com/

## 📓 Index
- [Setup](#setup)
- [Commiting](#commiting)
- [Other things](#other-things)

### 🌿 Setup:
`git init`<br>
^ Initializes a local git repo<br>

- Now on other CLI using GH CLI you have to create a new repo

`gh repo create git-tuto --private`<br>
^ Creates a private remote repo on your github account (you had to login before this lol!)<br>
`git remote add origin https://github.com/amyspark-ng/git-tuto.git`<br>
^ Adds the the remote URL as 'origin' (name of the remote)<br>
`git add .`<br>
^ Adds new or changed files<br>
`git branch -M main`<br>
^ Creates and moves to the main branch, even tho i think you can just set it as the default name or something like that<br>
`git commit -m "Initial commit 😎"`<br>
^ Commits those changes<br>
`git push -u origin main`<br>
^ Pushes the commits to the origin remote URL and to the main branch

### 🧵 Commiting
`git add .`<br>
`git commit -m "Changed stuff"`<br>
`git push`<br>
^ Pushes all commits to current local branch to current remote URL<br>

### 🪶 Other useful commands
`clear`<br>
^ You use this command to clear the git bash

`git pull origin main`<br>
^ You can use this command to pull changes from the remote branch<br>

`git remote get-url origin`<br>
^ You can get the url of the origin remote URL<br>

`git remote rm origin`<br>
^ You can use this command to delete a remote URL<br>

`rm -fr .git`<br>
^ You use this command to delete the git stuff<br>
