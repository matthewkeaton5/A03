# A03.

`git` was created by Linus Torvalds and is a Version Control System (VCS) allowing it to track changes which is very useful in programming as it allows you to explicitly check what is being done to the program you are writing as you write it. The most popular git provider is Github. Github is a hosting service that runs git under a ruby on rails webservice that provides free public repositories to all users.
After downloading and installing GIT, one of your first steps will be to create a repostitory which is also commonly known as the remote. A repository is essentially where all the information you will be storing is stored. In this area the majority of your work will be done through a terminal. All the information here is hosted in the .git folder in the root of your project. There are several commands you will use in your git workflow. `git add`, adds the specified files into the git repository, they must be under the same directory as the `.git` folder. When a file is added it is considered to be tracked. `git commit` creates a hash of all of your tracked changes, it is required to have a comment describing the changes made during the commit. `git push` pushes all current commits to the repository, multiple commits can be done in a push. `git fetch` pulls any commits that are on the remote but not on the local host. However it does not preform any merges into the git repository unlike `git pull`.
Once a commit is pushed you have the ability to `git pull` which will bring all of the files out of the repository onto the local host. This feature also allows for more than one user to work on the code base. In the event that there are changes on the repository that are not on your local computer, and your computer has changes that are not on the repository during a `git push` there will be a merge conflict. Using `git merge` will fuse any 2 versions of a file that has conflicting changes alleviating the problem. You will have to manually select the files that you wish to use for the action to be successful.
As projects get larger branches will be made. Thus leaving the master branch to be the most recent working version of the code. When a user wishes to add a feature it can be made on a branch, this will leave the master branch working while the new feature is debugged and completed.
`git clone` is used to pull an entire git repository onto the local computer. By default it is the master branch that is taken.

Works Cited
“.1 Git Branching - What a Branch Is.” Git, git-scm.com/book/en/v1/Git-Branching-What-a-Branch-Is.
“Git Term References.” Git-Scm.com, git-scm.com/docs.
Nelson, Meghan. “An Intro to Git and GitHub for Beginners (Tutorial).” An Intro to Git and GitHub for Beginners (Tutorial), product.hubspot.com/blog/git-and-github-tutorial-for-beginners.
Silva, Jonathan. “Learning Git: What Is a Git Repository?” Dev Blog by Axosoft, Dev Blog by Axosoft, 10 Apr. 2018, blog.axosoft.com/learning-git-repository/.

https://git-scm.com/docs
