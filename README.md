# how-to
how to use github on the terminal

tips:

* [terminal tutorial](https://www.learnenough.com/command-line-tutorial)
* [markdown tutorial](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## instructions to work

### clone a repo from github to your computer

to clone a repo, where x is your repo

```shell
git clone X
```

### go to the folder

open terminal and go to your folder X

```shell
cd x
```

do more cd until you reach the folder you want

if you want to go back to the beginning, do cd without argument

```shell
cd
```

### open the file

to open a file with atom, where x is your filename

```shell
atom x
```

### workflow

* work on your local copy, on your computer

* check git status to check there are changes

```shell
git status
```

* stage a commit, a commit is a new version of your work

```shell
git add -A
```

* commit, now your repository in your computer will have a new commit.
replace x without your explanation about this commit, keep the double quotes.

```shell
git commit -m "x"
```
* push to github on the cloud

```shell
git push
```

* now your work is both on your computer and on the cloud =) !
