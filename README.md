# Branchout Project

Branchout project root/projection repo, with all branchout repositories.
Intended for engineers wishing to work on and contribute to branchout.


## Getting Started

Install branchout, then init and pull to get all the repos on disk ready to use:

### SSH

```bash
branchout init git@github.com:Branchout/branchout-project.git
cd ~/projects/branchout-project
branchout pull

```

### HTTPS

```bash
branchout init https://github.com/Branchout/branchout-project.git
cd ~/projects/branchout-project
branchout pull
```


## Commands

- `branchout status` - show the state of all known repositories
- `branchout pull` - pull all repositories
- `branchout add <repo>` - add a repository to the project
- `branchout clone <repo>` - add and clone a repository
