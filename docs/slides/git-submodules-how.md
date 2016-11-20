## Git Submodules: How to use them?

Adding a submodule

```
git submodule add -b master link_to_git_repo_here_ssh_or_https path_to_clone_git_submodule_to_here
```
Pull down code from submodules

```
git submodule init --recursive
```

Resetting submodules

```
git submodule foreach git reset --hard HEAD && git submodule init && git submodule update --init && git submodule update && git submodule foreach "git checkout master; git pull origin master" && git submodule foreach git clean -f
```

Removing submodules
```
git submodule deinit submodule_name_here && git rm --cached submodule_name_here
```

Note:
Talk about the code