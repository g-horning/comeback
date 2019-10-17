1st draft

2nd draft

origin  https://git@github.com:g-horning/comeback.git (fetch)
origin  https://git@github.com:g-horning/comeback.git (push)

A git push command, when executed, pushes the changes that the user has made on the local machine to the remote repository.

To be able to push to your remote repository, you must ascertain that all your changes to the local repository are committed.

add remote repo:

--> git remote add origin git@github.com:g-horning/comeback.git

check remote repos:

--> git remote -v

git push / pull <remote_repo> <branch_name>

--> git pull origin master --allow-unrelated-histories
first pull

--> git push origin master
push to github repository

--> git pull origin master
pull from github repository

