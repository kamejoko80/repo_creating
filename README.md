repo_creating
=============

1> From https://github.com/, create new repository name "repo_creating"
   https://github.com/yourusername/repo_creating.git

2> From Linux console create a directory name "repo_creating"
  
   $ mkdir repo_creating

   $ cd repo_creating

   $ git init

   $ git config --global user.name "Your Name"
   
   $ git config --global user.email you@example.com

3> Create new file name test.txt to test commiting
   $ nano test.txt
     repo commit testing file.   
   
   $ git add .
   $ git commit -m 'initial commit comment'
  
4> To attach with your remote repo which name 'repo_creating' 
   $ git remote add repo_creating https://github.com/yourusername/repo_creating.git 
   
5> Execute: git pull repo_creating master to pull the remote branch so that they are in sync.
   $ git pull repo_creating master
   
6> To push up your master branch (change master to something else for a different branch): 
   $ git push repo_creating master
   
