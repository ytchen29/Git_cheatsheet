

### Branches
I want all the branches at my disposal
```bash
git fetch
```

Change branches.
```bash
git checkout <branch_name>
## or ##
gco <branch_name>
```

Create new branch and switch to it.
```bash
git branch -b <branch_name>
## or ##
gcb <branch_name>
```

Delete the branch called `branch`.
```bash
git branch -d <branch>
## or ##
gb -d <branch>
```

Rename the current channel to `new_branch_name`.
```bash
git branch -m <new_branch_name>
## or ##
gb -m <new_branch_name>
```

### Oh Shits
I didn't mean to add `file_name`!!!
```bash
git reset <file_name>
```

I need to pretend the last five minutes didn't happen. (Assuming you committed `intact_commit` five minutes ago.)
```bash
git reset --hard <intact_commit>
git push origin <branch> -f
## or ##
grh <intact_commit>
ggp <branch> -f
```

I need to change the commit message on the last unpushed commit.
```bash
git commit --amend
## or ##
gca
```
```bash
<commit_message>
<Ctrl+X to save and exit>
```