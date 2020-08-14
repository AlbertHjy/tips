With a locally cloned repository, you can do the same with git in your CLI as follows. First change to your repository folder, then confirm:
>`git remote -v`

Specify a remote upstream repo to sync with your fork:
>`git remote add upstream https://github.com/OriginalOwner/OriginalProject.git`

Verify:
>`git remote -v`

Fetch branches and commits from the upstream repo. You’ll be storing the commits to master in a local branch upstream/master:
>`git fetch upstream`

Checkout your fork’s local master, then merge changes from upstream/master into it.
>`git checkout master`

>`git merge upstream/master`

Push changes to update your fork on Github.
>`git push`

