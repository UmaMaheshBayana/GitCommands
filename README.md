**Git Basic Commands**

---- configure user details in our local repo ----
```
git config --global user.name "username"
```
```
git config --global user.email "emailId"
```

---- cloning public repo ----
```
git clone https://github.com/username/reponame.git
```

---- clone private repo ----
```
git clone https://username@github.com/username/reponame.git
```

---- checking git status ----
```
git status
```

---- add files to staging ----
```
git add .
```

---- commit files on staging ----
```
git commit -m "comment discription"
```

---- Pusing changes to remote repo ----
```
git push -u origin master
```


**Other Git Commands**

---- create branch staging ----
```
git branch branchname
```

---- checkout to the created branch ----
```
git checkout branch
```

---- push changes to perticular branch ----
```
git push -u origin branchName
```


**Creating repo in local and updating it on gitHUB**

1) Create a folder
2) inside the folder initiate git
---- to initiate git ----
```
git inti .
```

---- add files to staging ----
```
git add .
```

---- commit files on staging ----
```
git commit -m "comment discription"
```

3) Create repo manually in gitHUB
4) Add the repo details in local
--- add remote repo details ----
```
git remote add https://github.com/username/reponame.git
```

---- push the changes from local to repo ---- 
```git push -u origin branchName```
