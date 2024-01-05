**Summary of BASIC LOCAL GIT Command**

# configuration
- git config --global user.name "your name"  
- git config --global user.eamil "your email@email.com at github email" 
- git config --global care.editor nano : change basic git editior to nano  

# basic command (working directory - staging area - local git repo)
- git init : creates .git file in your working directory 
- git add [file or .]: add file in your working directory to staging area (. to include everything in the current working directory)
- git ignore: https://github.com/github/gitignore 
 (template of gitignore file to prevent files from adding to the git // .DS_Store can also be included in your own gitignore file//
  useful files include Node.gitginore in the above website)
- (cf) git rm --cached -r .DS_STORE : to revert back to the unstaged status after adding files) 
- git status : check which files are added in staging area and which are not 
- git commit : add files from staging area to your local git repo
- git diff - to check which files are revised/not revised
- git checkout [file]: revert(roll back) to the last version of commit in the local repo (roll back to the status of before committing/adding  revised file(s) ) 
- git log : show commit logs (HEAD is the current reference point)


**Further Consieration to compare** 
-git rm --cached <file>
-git restore --staged <file>
-git reset <file>


**Summary of BASIC REMOTE GIT Command**
# push local files to remote repo
- git init (local repo directory)
- git remote add origin repository URL 
- git push origin main : upload files to main branch in origin repository 


**Summary of BASIC REMOTE GIT (GITHUB) for Collaboration Command**
- Fork : you can make changes to a project without affecting the original repository, "upstream" repository.
 (ref: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)


- git clone url : clone a remote repo to your local repo
  (git clone https://github.com/username/repository.git)
- On github - log onto your account and go to settings -> developer settings -> personal access token -> generate new token(Do not save in your computer for security reasons)
- copy the token and paste ont the password while cloning 

- git branch name-of-branch : create a new branch
- git checkout -b name-of-branch : create a new branch and change the current head to a new branch
- git merge name-of-branch: merge name-of-branch to the current branch(main in default setting)
- To check the github commit map : On the github menu : insights - network 
- Add git graph extension on 


-  After making changes to push the changes to the upstream branch
- git push upstream branch-name-of-upstream
- Make a new pull request 



