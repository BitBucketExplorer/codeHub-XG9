# Git Commonds

### Create git ignore file in folder directory
> touch .gitignore

### Initialize empty git
> git init -b main

### Add changes and commit them
> git add . && git commit -m "initial commit"

### Bind git with Repository url
> git remote add origin <REMOTE-URL>
  
### Check Remote 
> git remote -v
  
### Push The code
> git push origin main
  
### Remove Index.lock file 
> (Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.
)
# rm .git/index.lock
