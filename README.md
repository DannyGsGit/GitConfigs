# GitConfigs

A repository of useful Git commands

## Aliases

The following alias will display a history of your commits:

```
git config --global alias.graph "log --all --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%ci) %C(bold blue)<%an>%Creset'"
```

The following alias can be used to unstage specific files:

```
git config --global alias.unstage 'reset --'
```

## Workflow

### Status Check

To view the status of any file changes and staging, use:

```
git status
```

### Staging

To stage all files, use:

```
git add -A
```

With the unstage alias defined above, we can unstage specific files with:

```
git unstage example.txt
```

Or unstage all with:

```
git unstage .
```

### Commit

Store a commit with:

```
git commit -m "My commit message"
```

### Push

### Change Branch
