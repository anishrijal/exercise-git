# Introduction

##What's ...?
  [What is git? & What is github?](http://www.makeuseof.com/tag/git-version-control-youre-developer/)
## Learn Git
  [Tutorial: Try Git](https://www.codeschool.com/courses/try-git)
##  Github
  [Create a Repository](https://help.github.com/articles/create-a-repo/)
  
  [Cloning, Forking, Commiting & Updating](https://github.com/KsquareLabs/exercise-git/blob/master/github/readme.md)
#Exercise
  Fork this repository and download the repository to your computer
##Questionnaire
The next questionnaire could be answer within the readme file on your computer or within github repository.
If you decide to do it in your computer, just edit the readme.md file with each answer then  `add` changes, `commit` then and
finally push the changes to your github repository. If you decide to change it within github, you just need to click on the 
readme.md file, click the edit icon and start answering the questions.
  1. What is Git?
  2. What is Github?
  3. Describe the commands that were used on Try Git tutorial (Use a table).
  4. What are the main advantages?
  
###Answers

#### 1 What is Git?

Git is the most widely used version control system which is used for software development 
and other version control tasks

#### 2 What is Github?
GitHub is a Git repository hosting service where there are many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.

#### 3 Describe the command that were used on Try Git tutorial.
Command used in try Git:
git status -s
git init (initialize empty git repository)
git commit -m (description for the change)
git add '*.txt' (wild card to add)
git log (for changes committed)
git remote add origin http://,,,,,../ (to push our local rep to github server)
git push u origin master (tells git where to put our commits when ready, 
                -u tell git to remember the procedure so we can it next time)
git pull origin master (to pull changes)
git diff head(to see what has been changed) 
git diff --staged (to see changes you just staged)
git reset 
git branch branchname(to add a new branch for changed)
git checkout branchname(to switch branches)
git merge branchname (to merge all change made)
git branch -d branchname (to delete branch)

#### 4 What are the main advantages?
work offline
fast to work with
repositories are smaller
moving or adding files
ignore certain files
branches
check the status of changes
stash branches


##Exercise

  Work on the gitTutorial folder, in order to simulate everything that was done within the Try Git Tutorial.
  The tutorial allow you to use some git commands but is skipping the creation and editing of the files, so 
  you are going to create/edit/delete the files following the tutorial steps using `git add [files]` and 
  `git commit -m "PLACE COMMIT NAME HERE"` in order to have a reference within the project per change.
  
###For example:
  
####Edit octocat.txt file
  1. Open octocat.txt file then create a change within the file, could be just add or erase a letter/paragraph ...
  2. Add changes to stage area `git add octocat.txt`
  3. Commit changes to the project `git commit -m "Octocat cat File edited"`

#Useful Links

[Github Markdown readme file references](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Mac terminal Commands](https://github.com/0nn0/terminal-mac-cheatsheet)
