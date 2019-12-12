# suur
r package practice

Steps:
1. Create package localy
  R -> file -> new project -> New Directory -> R Package
  
2. push local package file to Github
  1) Create a new repository on github, having the same name with local file 
  2) Open git bash and change the current working directory to the local project with cd .. 
  3) Initialize the local directory as a Git repository 
      $ git init 
  4) Add the files in the new local repository 
      $ git add .
  5) Commit the files in local repository 
      $ git commit -m "Initiate commit"
  6) In the command prompt add the URL for the remote repository where the local repository will be pushed 
      $ git remote add origin https://github.com/YujieSu/suur.git
  7) Push the changes in the local repository to Github
      $ git push -u origin mastere 
      
3. install the package locally to R
  devtools::install_github("YujieSu/suur")
     
