# commandstest
to test the commands

# Git commands

## Commands for to delete the previous commits

```
git rebase hard --
2,$  s/pick/g
git push --delete origin brnach_name
git push origin brnach_name
```

## Commands for to do cherry pick the commits

```
git checkout b3d92c5 Checkout the last usable commit.
git checkout -b repair Create a new branch to work on.
git cherry-pick 77b9b82 Run through commit 3.
git cherry-pick 2c6a45b Run through commit 1.
git checkout master Checkout master.
git reset --hard b3d92c5 Reset master to last usable commit.
git merge repair Merge our new branch onto master.
git push --hard origin master Push master to the remote repo.
```
Please refer the url : https://www.clock.co.uk/insight/deleting-a-git-commit

# Ansible commands

## Ansible command to run the playbook

```
ansible playbook -l hostname path_to_playbook
```
