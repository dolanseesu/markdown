
# How to use Git

Command | Meaning
--- | ---
git clone | clones the repo from the url
git add | adds all the specified files to the local git repo
git add -u | adds all _modified_ files to the local git repo
git commit -m "Commit Message" | Commit the changes with a message
git push | pushes the commits from the local repo to the remote repo 
git pull | pull all changes from the remote repo to the local repo


If you want Git to remember your username and password, use:

```bash
git config --global credential.helper store
```

After the next push, Git will store your credentials.
