# git status

It gives you som info about the status of your repo.

## tips

#### Short status

Git gives you a lot of info when you run `git status`, but some times this info can be quite verbose. If you prefer a more compact and concise style, you con use `-s` or `--short`.

```git
$ git status -s
 M tips/add.md
A  tips/status.md
?? tips/log.md
```

* `?` for untracked files.
* `A` for files that have been added to the statging area.
* `M` for modified files.
* left hand column for the status of the staging area.
* right hand column for the status of the working directory.

