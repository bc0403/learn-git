![workflow](https://git-scm.com/images/about/index1@2x.png)

# learn-git
Memo for learning git. Please read references from top to bottom.

## Github flow (online)
1. **create a new repository** with README.md and a license
2. **create a new branch** for new feature. 
3. coding on the new branch. If finished, **make a new pull request**, discussing...
4. **merge** the pull request to `master` branch, then delete the finished feature branch since it's code has been merged to the master (no useful anymore)

## Github flow (online & local)
1. create a new repository at Github
2. install git locally. [https://git-scm.com/](https://git-scm.com/)
3. clone it to local
4. code, debug, push, collaborate, and enjoy it!

## Key points
1. Github's **pull requests workflow** is a popular way to create and review code.
2. **commit** messages capture the history of your changes, so other contributors can understand what you have done and why.
3. make a pull request on a `feature branch`, and the **team leader** review, discuss, and merge the pull request to `master` branch.
4. anything in the `master` branch is always deployable.

## Usages
* `git clone *.git`, clone a repository into a new dictory
* `git add`, add file to the staging area. (`git add .`, add all files to the staging area)
* `git commit -m "message"`, record changes to the repository
* `git log`, show commit logs
* `git push`, push to the remote repository. (`git push -u origin master` for the first time)
* `git status`, show the working tree status
* `git branch`, list, create, or delete branches (`git branch feature` to create; `git branch` to list; `git branch -d feature` to delete)
* `git checkout feature`, switch branches or restore working tree files (here, switch to `feature` branch)
* `git merge feature`, merge `feature` branch to `master` branch (should switch to `master` branch firstly)

## References
1. https://guides.github.com/activities/hello-world/ 
2. https://guides.github.com/introduction/flow/
3. https://guides.github.com/features/mastering-markdown/ [for Markdown Usage]
4. https://git-scm.com/doc
5. After install the git software, type `git help tutorial`, `git help everyday`, `git help revisions`, and `git help workflows` in the terminal to read the documentations

