gittesttemp
===========

A temporary repos to test maintaining remote branches

Learning
=====
Once having created a new feature branch as long as you keep pushing to the corresponding remote feature branch then both branches will happily co-exist and as long as you have used git to set the current branch then when you run the code locally either the master or the feature branch will be run.

Here's an example of how to set this up :

```
$ git checkout -b feature_branch_name
... edit files, add and commit ...
$ git push -u origin feature_branch_name
```
