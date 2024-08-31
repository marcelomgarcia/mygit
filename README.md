# mygit

Learning to use Git

## Status of Files

Each file can be in one of two states: _tracked_ or _untracked_.

![Lifecycle of the status of your files](images/lifecycle.png)

## Status of Your Files

Just after commiting the changes the repository should be clean:

```
mgarcia@valinor:~/Work/mygit$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
mgarcia@valinor:~/Work/mygit$ 
```

## Tracking New Files

To start tracking new files, use the subcommand `add`

