# How to use basic git!

I made this repository for people who don't know how to use git and might want to start with it and for me when i eventually forget all of this stuff and need it!

Also i'm kinda aware that VSCode has it's own source code with github thingy on the side-bar, but i still think it's important to learn these kind of things 

> Be aware that to follow this tutorial you should have downloaded git and optionally CLI-GH (GitHub for command line)<br>

> You can download it here:
- https://git-scm.com/downloads
- https://cli.github.com/

## Index
- [Setup](#setup)
- [Commiting](#commiting)
- [Other things](#other-things)

## Setup

### The local stuff
`git init`<br>
^ Starts a github repo<br>
`git remote add origin https://github.com/amyspark-ng/git-tuto.git`<br>
^ Adds the the remote URL to send the commits and pushes
`git add .`<br>
^ Adds new or changed files<br>
`git branch -M main`<br>
^ Creates and moves to the main branch, even tho i think you can just set it as the default name or something like that<br>
`git commit -m "Initial commit 😎"`<br>
^ Commits those changes<br>
`git push`<br>
^ Pushes the local commits to the current CLI and the current branch

## Commiting
`git add .`<br>
`git commit -m "Changed stuff"`<br>
`git push -u origin main`<br>

## Other things
`rm -fr .git`<br>
^ You use this command to delete the git stuff<br>

