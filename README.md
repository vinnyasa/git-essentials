# UC Berkeley MSSE - Git Lessons (August 2020)

This repository contains git-lessons for Masters of MSSE taught by UC Berkeley.


## Git

This lesson covers basics of using git for verision control

The covers first day of bootcamp.

To make commit ("version or "checkpoint") of files, follow these procedures:

1. Make changes to your project
1. Tell 'git' you are ready to create checkpoint of files (using 'git add')
1. Create checkpoint using 'git commit -m' "Message what about you did"

## Adding features
Features should be developed on branches. To create and switch to a branch, use:

'git switch -c new_branch_name'

'-c' means "create".

To switch to an **existing branch**, use
'git switch branch_name'