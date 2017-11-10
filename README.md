# 2018-Hacksu-ui-main
The new website for Hacksu -- expected launch date 2018

# Getting Started

If you want to help out with the website, that's great! First, fork this repo, by clicking "Fork" on this page.  Then, do the following to set the website up on your computer:

1. Clone the forked repo with `git clone [your repo address]` in whatever directory you want to work in

2. Go into the newly cloned repo by typing `cd 2018-Hacksu-ui-main/hacksu-ui`

3. Run `npm install` 

4. Run `npm run dev` (You'll have to do this every time you want to see the website's build)

5. The build ui should now be available when you go on a browser and go to `localhost:8080`. Nice!

# Keeping your fork up to date

There are lots of people working on this project!! Every time you start to work, it's good practice to make sure you have the latest version of the code. Here's how you can update your fork:

We want to pull the latest code from the *original* repo, not our fork, so we need to tell Git where that original repo is. 
Type `git remote add upstream https://github.com/hacksu/2018-Hacksu-ui-main.git` . This will add a "remote" branch to git, telling it where the original repo is. You only need to do this once

1. Make sure you've added your remote upstream branch via the above instructions. Now you can type `git pull upstream master` to update your code from the master branch.

2. If you get an error, make sure:
  A. You have your upstream branch set up
  B. You don't have any changes that are uncommitted
  
3. If pulling in the new code works, but the new code is throwing errors, try `npm install`. This will make sure that you have the latest "dependencies". If this doesn't work, ask Elizabeth or Ben what's wrong. 

# Submitting your changes

Once you've made whatever changes to the code you want to make, add them to your fork like so:

1. `git add *` - This will add all the files in your repo as files you want to commit 

2. `git commit -m "Describe what changes you made here, briefly"` This will prepare a commit, but not actually send it back to the github repo

3. `git push` This "pushes" all your unpushed commits to the github server

Once your github fork has the changes you want to make, go to your fork on github, and click "New pull request".  One of the hacksu admins will then review and accept your changes!!


