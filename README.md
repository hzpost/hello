# hello

## check contributing to other's project

### workflow

* hzget fork branch hzpost/hello via web site
* git clone hzget/hello
* move to a new branch
    * git branch feature
    * git checkout feature
* make some changes
* commit the changes
    * git add
    * git commit
    * git push

### errors

first time git push:

fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

follow the command,then push again

### workflow continue

* create pull request: base repo: hzget/hello base:main  <--  base repo: hzget/hello base:feature
* merge
* create pull request: base repo: hzpost/hello base:main  <--  base repo: hzget/hello base:main

