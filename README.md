# git-cheatsheet
Commands I come across or use regularly, but which I might forget!

## Adding .gitignore late ##

Make changes or add .gitignore as usual. Then remove all locally cached files, using the command below.

```
$ git rm -r --cached
```

Add (remove) the changed files, using `git add .` in the root directory. Followed by using git commit as usual and push or don't. Whatever floats your boat.

# Changes (git bot)
Making changes on remote
