## test_repo readme

## Introduction
- This article is a Git starter tutorial. I'm trying to provide the steps to create a repo and Git commands related to initialzing a directory to pushing the files.
- Usecase for this article is,
  - An user having a set of files needs to be checked into Git
  - Files are stored in directory called `test_repo`
  - User wants to know, how to create repo in git
  - Also Git commands associated with initializing the local repo and pushing the changes to git


## Step 1 Create Repo in Github Website

## Step 2 Copy the Repo Url from Address Bar

## Step 3 Create a directory with similar repo name
mkdir test_repo

## Step 4 Go inside the directory
cd test_repo

## Step 6 Run Git init command to initialise .git directory
git init

## Step 7 Create branch main
- This command renames the branch master to main
git branch -m main

## Step 8 Now add the repo to remote Git URL
git remote add origin https://github.com/chefgs/test_repo.git

## Step 9 Create a file
echo "## test_repo readme" > README.md

## Step 10 Check repo changes using git status
git status

## Step 11 Add the files to git staging
git add .

## Step 12 Commit the staged files
git commit -m "first commit"

## Step 13 Push the repo changes to Git
git push --set-upstream origin main

## Next steps
Once it is pushed for the first time, follow-up changes can be pushed by running below commands

## Check repo changes using git status
git status

## Add the files to git staging
git add .

## Commit the staged files
git commit -m "new commit message"

## Push the repo changes to Git
git push origin main