# My GIT training area
This is a repository I am using to learn how to use GIT

# Initial Setup

1) Go to the base directory under which you want to create the local repositories.   
   $ cd c:/BS_Data/github/

2) Initialize local GIT repository in the base directory: 
   $ git init

3) Configute user name: 
   $ git config --global user.name '@robertohjdasilva'

4) Configure user email: 
   $ git config --global user.email 'robertohjdasilva@hotmail.com'

5) Clone repository. Note that if we clone a given repository e.g., coding_exercises,
   a directory called "coding_exercises" will be created under "c:/BS_Data/github".
   The URL of the remote repository is obtained from tghe GitHub web site.
   $ git clone https://github.com/robertohjdasilva/coding_exercises.git

# Adding/modifying new files

1) Adding new file to staging area
   $ git add SortedSquaredArray.cpp

2) Commit file
   $ git commit

3) Push/upload local repository content to the remote repository
   $ git push -u origin master
