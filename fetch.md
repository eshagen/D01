#Fetch
If I make a mistake and need to later update a repository that you have already forked and cloned, follow these steps to fetch the latest version from python-boot-camp and merge with changes you may have made.

```
git remote add  upstream [URL for the original repo].git
git remote -v
git fetch upstream
git merge upstream/master -m "fetching and merging"
```

If **you** make a mistake and set the wrong upstream repo, you must remove it before adding the correct on (remove and confirm):

```
git remote rm upstream
git remote -v
```

###Resources
+ [GitHub Help: Configuring a remote for a fork][1]
+ [GitHub Help: Syncing a fork][2]
+ [GitHub Help: Resolving a merge conflict from the command line][3]

<!-- Links -->

[1]: https://help.github.com/articles/configuring-a-remote-for-a-fork/
[2]: https://help.github.com/articles/syncing-a-fork/
[3]: https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/