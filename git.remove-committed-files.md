---
id: 3kjop7btkvlg4n99ar46z84
title: Remove Committed Files
desc: ''
updated: 1650470039280
created: 1650469872032
---

To accomplish this without modifying local files add the file to the `.gitignore`

```shell
git rm --cached /path/to/file
git status # Verify the files are being deleted from vcs
```

## References

* [How To Remove Committed Files From Git Version Control :: BetterProgramming](https://betterprogramming.pub/how-to-remove-committed-files-from-git-version-control-b6533b8f9044)