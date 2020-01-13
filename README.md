# git-playground
For testing of git client features

## common issues

1. Carry over commits between multiple branches
  - git checkout -b branch1
  - # modify some files
  - git add -A
  - git commit -m "first commit"
  - git log
  - git push origin/branch1
  - # no PR or merge
  - git checkout master
  - git fetch
  - git pull
  - git checkout -b branch2
  - # modify some files
  - git add -A
  - git commit -m "second commit"
  - git push origin/branch2
  - # check commit for changes, likely includes files/updates from branch1, why?


