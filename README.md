# odinaka-chukwuani

`VERSION CONTROL`: This is also known as source control or revision control, its a system that tracks changes to files over time so that you can recall specific versions later. its an essential tool for software development, web development and other collabortative projects where multiple work on shared files.

`DIFFERENCES BETWEEN GIT AND GITHUB`: 
GIT-- is a tool for tracking changes to files over time.
      This is an open source and free to use.
      This is used by developers, writers, designers and anyone who works with digital files.

GITHUB-- is a web-based hosting service for git repositories.
         This offers both free and paid plans.
         This is ideal for projects requiring collaborations, open source development or code sharing.

 `3 GITHUB ALTERNATIVES`:
 - Bitbucket
 - Sourceforge
 - Gitlab

 `EXPLAIN THHE DIFFERENCES BETWEEN GIT FETCH AND GIT PULL`:
 `git fetch` and `git pull` are both git commands used to update your local repository with changes from a remote repository, but they differ in how they handle those changes.

 `GIT FETCH`:
 - Fetches changes from the remote repository to your local repository.
 - Does not automatically merge or modify your working directory.
 - It updates your remote tracking branches.

 `GIT PULL`:
 - Fetches changes from the remote repository and automatically merges them into your current branch.
 - Updates your working directory with the changes.
 - Can lead to automatic merges, potentially causing conflicts.

 `EXPLAIN IN SIMPLE TERMS "GIT REBASE" AND THE CCOMMAND FOR IT`:
 Git rebase is a Git command used to change the base of a branch. it allows you to move or combine a sequence of commits to a new base commit. The primary purpose of git rebase is to maintain a cleaner and more linear project history by incorporating changes from one branch into another.
 `command for git rebase` is "git rebase <base_branch>".

 `EXPLAIN IN SIMPLE TERM "GIT CHERRY-PICK" AND THE COMMAND FOR IT`:
Git cherry-pick is a Git command that allows you to apply a specific commit from one branch to another. it is useful when you want to selectively pick one or  more commits and apply them to a different branch without merging the entire branch.  `command for git cherry-pick is as follows: ` "git cherry-pick <commit_hash>".