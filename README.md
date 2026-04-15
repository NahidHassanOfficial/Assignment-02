# Assignment-02

## Task: 1
<img width="753" height="313" alt="image" src="https://github.com/user-attachments/assets/bad741da-3f9f-4143-9fa1-257f8dc832aa" />


## Task: 2

steps:
``` 
-- repo setup
git init
git add .
git commit -m "initial commit"
git branch -M main
git checkout -b develop
git checkout -b feature/login
```

``` 
-- create branch
git checkout develop
git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error
```

```
--merge
git checkout develop
git merge feature/payment
```

```
--rebase
git checkout feature/profile
git rebase develop
git checkout develop
git merge feature/profile
```

`git rebase -i HEAD~5`
