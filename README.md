# Overview

In the release-branch merge strategy there are two main branches:
* The master branch.  This branch reflects the state of production at any given time
* The release branch.  This branch represents the set of changes being prepared for release

When a developer starts work on a new feature they create a new feature branch based on the master branch.

When a developer starts a new feature they create a feature branch using master as their starting point.

```
$ git checkout -b AM-1234/feature-branch-1 master
Switched to a new branch 'AM-1234/feature-branch-1'
```

Work is done on the feature branch until we're ready to open a pull request.
