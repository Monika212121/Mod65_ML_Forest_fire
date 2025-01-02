This is my first ML End to end project.

It uses Regression model for Output prediction.


# Git commands used to setup this repository  and sync with the online github.
```
   2 git remote -v
   3 git init
   4 git add .
   5 git status
   6 git add .
   7 git commit -m "first commit in ML"
   8 git config --global user.email "mgadewar12@gmail.com"
   9 git config --global user.name "M,onika212121"
  10 git commit -m "first commit in ML"
  11 git branch -M main
  12 git branch
  13 git remote add origin https://github.com/Monika212121/Mod65_ML_Forest_fire.git
  14 git push -u origin main

  ```


  Afterwards for deployment, create .ebextentions folder and pyhton.config file inside it.

  Also make 2 changes:
  1.) Change name od app.py to application.py as while deploying, it is by default name.
  2.) In application.py file now, rename 'app' to 'application' and assign this 'application' variable to new variable 'app' .
