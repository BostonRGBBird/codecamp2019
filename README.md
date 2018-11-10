# codecamp2019


### Make your git folder

`mkdir {folder name}`

### Make your git folder

`cd {folder name}`


### Check your current path

`pwd`


## Initiate git repository

`git init`

### Clone the codecamp2019 repository master branch

`git clone https://github.com/Mangoblock/codecamp2019.git`

Note: make sure clone the Mangoblock url instead of the forked one. Otherwise, the branch created below won't show up in Mangoblock to be reviewed, even though PR will be there.

### Check local branch

`git branch`


### Check all branches including remote branch

`git branch -a`

* Local branches are the branches on your computer. Remote branches are the branches which you can see on github.

### Make your own branch

`git branch {your branch name}`

Note: you'll have to create your first file before creating a branch.

### Move to your branch

`git checkout {your branch name}`


* You can also do `git checkout -b {your branch name}` to do the two steps together.

### Push your branch to remote branch. (By doing this, you will be able to create a remote branch linked to your local branch`

`git push -u origin {your branch name}`

Note: you'll need add remote before this by `git remote -v` and `git remote add origin git@github.com:Mangoblock/codecamp2019.git`

## After you make some changes on your branch. Your can check the status.

`git status`

### Add the file changed to the repository

`git add {file name with path}`

Note: need add in dir to make sure it shows up correctly in remote `git add codecamp2019/`

### After you added all the files which you want to push to your remote branch

`git commit -m "{input commit log here}"`

### Push your work to remote branch

`git push`

Note: to make it more certain, use `git push origin your_branch`

