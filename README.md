# 1. Learn Git

Learning to use Git.

# 2. Git Command Reference

## 2.1 Quick reference
    git --version                                   -- display git version being used
    git clone <repo-branch-url>                     -- clone a repository with specified branch url
    git init                                        -- initialize a new repository
    git checkout <branch-name>                      -- switch to specified branch
    git status                                      -- get status of all files to be staged
    git add .                                       -- stage all files in current directory
    git commit -m <message>                         -- commit changes to git with a commit message
    git push                                        -- push commits from local to remote repo

## 2.2 Git Config
    git config --list                               -- list git config file entries
    git config --show-origin                        -- show origin and git file used to infer value
    git config --global user.name <user.name>       -- set user name (in global .gitconfig file)
    git config --global user.email <user.email>     -- set user email used to check-in to repo
    git config --global init.defaultBranch main     -- set main as default branch name
