# summer-project-2021

# This is the repo for the summer project(s) for summer 2021.

# The editors of this following repository are trying to create:. . .

# The way to run the project(s) is: . . .

# The technology we used are: . . . 

# The difficulties we had are: . . . 

# The lessons we learned are: . . .

# The real-life applications for our lessons are: . . .

# Etiquette for adding to project(s): 
## Make a branch that stems off the devel branch. This will give you the most up-to-date info regarding the project. 
## Only push to main once the ENTIRE project(s) is FINISHED. This prevents us from having unusable code on the master branch to show interviewers.
## All branches must be named in the following syntax so that we can properly track what changes are made from what branch : '<Issue-label>/#<issue_no>:[Changes made listed in bullet points]'.
## Every feature MUST have a matching issue. You can open issues in the issue tab. Make sure to label your issues with any of the pre-created issue labels or any new ones you created. Then make sure to create branches using the label.
## Do NOT push buggy code to devel, check everything in a secondary branch and only push working code to devel. 
                                     
 # Branching Philosophy
When working on a software project, it's important to follow similar workflows so everything can run smoothly with no conflicts. Here we will outline the roles of the master and devel branches.

## main: Always contains 100% functional, working code. Push to this branch only for "releases". Any time someone clones your repository and gets your master branch, they should always get a working version of code (even if it is not the most up-to-date, which could live on your devel branch). 

## devel: Devel should ALSO ONLY HAVE WORKING CODE. It will be used as the base branch for feature branches, which are introduced in a moment. If you break devel and it no longer compiles, you will hinder the rest of your project development until you fix the bug. The general workflow should be: create feature branch from devel, add feature/fix bug, merge feature branch into devel. As such, you shouldn't be working/committing directly to devel at all.

## Feature branches: These are the branches that should contain the actual development work. They should be named something specific (i.e. not just feature/phase2, but feature/phase2-widgetA-scaffolding). Keep your commits on these branches focused on the issue and make relatively few, unless the complexity of the feature warrants more. Resist the temptation to follow multiple paths and address multiple issues on a single feature branch. Instead, open an issue in github to track what you have found/want to do (See Github Issues), and continue on with the work of the feature branch.

## Feature branch naming format:
<issue_label>/<issue_number>-descriptive-title:[changes you made in bullet points]
When creating a feature branch you should use the above format where <issue_label> is replaced with the label of the issue the feature branch addresses. Additionally, each issue will have a number, which you should use in place of <issue_number>. Then the rest of the feature branch name is a descriptive title, separated with dashes.

Here is a diagram depicting the branching philosophy visually. In our case, the far right blue branch is our master branch, yellow is our devel branch, and pink are our Feature branches.

![image](https://user-images.githubusercontent.com/44474898/118415096-fa2ee580-b66d-11eb-8218-508154cef054.png)


## Github issues

The following are git resources for you to reference. The first resource lets you see a graphical representation of a git sandbox where you can model the workflow outlined above. The second link is a commonly referenced git branching philosophy resource which has been linked in at least one previous lab. The diagram above is also from that link. Feel free to check out either in more depth if you feel so inclined.

https://learngitbranching.js.org/

http://nvie.com/posts/a-successful-git-branching-model


