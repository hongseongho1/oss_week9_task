# oss2025_intro
## Task-1: Checkout your branch. 
Note that, there are 10 branches (5-6 students per branch).
The branch assignment is as follows:\
intro1 -->강동혁, 강병규, 고홍규, 곽민준 ,구윤찬 
intro2 --> 
intro3 --> 
intro4 --> 
intro5 --> 
intro6 --> 
intro7 -->  
intro8 -->
intro9-->
intro10-->
(command: `$ git checkout intro<N>`)\

## Task-2: Open the intro.txt file, and write your name and department in it.
(format: 이름, 학과)\
Commit the changes.\
[Therefore, intro<N> branch is updated while origin/intro<N> is still in the previous commit]

## Task-3: Now push your branch to origin.\
command: `git push origin intro<N>`\
[With a successful push, We expect that origin/intro<N> would be updated.\
However, the push will be unsuccessful if your friend has pushed to the same branch first. If so, do the following]

## Task-3.1: Do the following only if the push was unsuccessful.
Fetch-Merge-Push\

Fetch the updated origin\
`git fetch origin`\

Merge the remote branch into your branch\
`git merge origin/intro<N>`\

Push again.
`git push origin intro<N>`\
