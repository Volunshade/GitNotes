# GitNotes

To shows **current status of the branch** Whether or not the branch needs to be updated, staged files, behind or ahead of commits and which branch you are working on. You can use the following command 'git status'

If you decide you want to change code you should **create a new branch** (assumeing that you have the most up to date versioning of the project) with the following command: 'git branch YOU_BRANCH_NAME'

To check all created branches, you can use the following command 'git branch -a'

To **switch to an available branch** you can use the following command 'git checkoput YOUR_BRANCH_NAME'

At this point you have a new feature that you want to add to your project. You created and switched to your new branch Now, you can add whatever code you want to your project on you **local**

To check *unstaged changes* in your project, you can tun the following command 'git diff'

Now we the code that we want to add to our project written and we want to have 'git' tracking the changes, bhecause right now 'git' is not tracking. To track unstaged files or changes, you can run the following command 'git add NAME_OF_CHANGED_FILE'

Tracked files or changes that you would like to commit to your *LOCAL* git repository, and eventually your *REMOTE* git repository, can be commited with the following command 'git commit - m "This is a message that describes what you just did on this commit, so make sure it is descriptive"'

To show the current commit tree you can run the following command 'git log --oneline --graph'

Now we have code that is commited to **feature branch** but the remote git repo does not see any changes at all yet.

to *inform* the remote git repo of the changes that you make in your **local git** you can push your commits up to the **remote** using the following command 'git push'