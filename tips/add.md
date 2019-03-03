# git add

You use git add to begin tracking new files, to stage files and mark files containing conflicts as resolved. In other words, you can use `git add` to add files to the next commit.

## tips

#### files and folders

* `add` takes files and folder. If a folder is passed to add, it adds all the files in that directory in a recursive way.

#### changes in staged files

* the `add` command stages a file exactly as it is when you run this command. If you modify that file again a want those changes to be in your next commit, you will have to run `git add` again.
