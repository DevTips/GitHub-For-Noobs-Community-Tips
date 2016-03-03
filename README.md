# GitHub-For-Noobs-Community-Tips
#### This Repo is a collection of great tips and references from the comments found in the GitHub for Noobs Series

https://www.youtube.com/playlist?list=PLqGj3iMvMa4LFz8DZ0t-89twnelpT4Ilw


_Community Contributions_

---

**Scott Nimos**

`atom ./*`  opens all the files in the directory in Atom at once.

---

**Marcel Robitaille**

You can also just type `git push`. if there is no upstream, git will prompt you to do the command with `--set-upstream`.

---

**Steven Kemp**

You can use GitHub's `hub` command line wrapper. [github.com/github/hub](https://github.com/github/hub).
You can type in `hub pull-request` to make a pull request from the command line.﻿

---

**David Awsom**

Check this "terminal reviser tool": [github.com/nvbn/thefuck](https://github.com/nvbn/thefuck)
It can correct your last command, executing the `fuck` command. For example, if you execute `git brnch` literally, obviously the output will be a syntax error. Then enter `fuck` and whoala, it will execute the last command without syntax errors!   Helps a lot when one is very tired.

---

**Devin Chaves and ceghap**

I always do `git add .` to add all files to staging stage.

> **Marcel Robitaille**

> I don't think that adds deleted files. I like `git add -A`

---

**Sean Holdbrook**

A best practice for commit messages is to explain why you are committing over what you are committing. A git diff can tell you what changed so a message should explain the reason for the changes. Something like "we didn't like the gray background so we made it lavender" instead of "bg-color from gray to lavender"﻿

---

**segni bechir**
To Push a new branch : `git push -u BranchName`
To Commit and add Same Time : `git commit -am "you comment"`
To Add all the files without a commit : `git add .`
To Merge a Branch into master : 1: `git checkout master -> git merge BranchName`

----

**MUSTBENICE**

Ever heard about [git-flow](https://github.com/nvie/gitflow)? Make sure to google that, it's a great extension for git ^^

---

**Ratik Sharma**

Fun fact: newer versions of git allow you to execute `git status` using `git s`. There is more to these shorthands. Check 'em out!

---

**Andreas Storesund Madsen**

You can write `git commit -am "message"` instead of `git commit -a -m "message"`
