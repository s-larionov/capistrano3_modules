# Installation
clone this repo in "capistrano" directory in your root of project.
```bash
cd /path/to/project
git clone git@github.com:s-larionov/capistrano3_modules.git capistrano
```
# How to use
Configure your capistrano3 config for use scm 'git_with_submodules':
```
set :scm, :git_with_submodules
```