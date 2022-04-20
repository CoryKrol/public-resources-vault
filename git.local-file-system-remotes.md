---
id: 8vevuv394j15dqotx0v9g2x
title: Local File System Remotes
desc: ''
updated: 1650470817327
created: 1650470250926
---

A bare repo can be useful for keeping repos in sync across machines using One Drive/Dropbox/Google Drive.

## Create Remote

```shell
cd repos # change to whichever directory you like
git init --bare my-repo.git
```

## Link Local Repo With File System Remote

```shell
git remote add origin /path/to/repos/my-repo.git
git push origin master
```

## Useful Commands

```shell
git remote show origin # show information about a remote, for example if tracked branches are up-to-date
git log origin/master ^master # show log messages of the changes between branches
git diff origin/master master # show differences between branches
```

## References

* [How to use local filesystem remotes with git](https://thehorrors.org.uk/snippets/git-local-filesystem-remotes/)