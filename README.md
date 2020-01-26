# hello text 
 - some bullet points here 
 ## hello 
 ### hello 
 text body 
 ## take aways from git sessions 
 * local 
 - create a git repository : create a folder, initialize git (tracking) 
 ''' git init 
 # dit add some files (text, python etc.) or update, add all file to tracking system (git)
 dit add . 
 git commit -m 'meaningful message that summarizes your changes' 
 # if you want t publish : create repo in github, copy the url that ends with .git 
 git set-upstream origin url 
 git push 

 # add files to '.gitignore' > exclude from tracking and publishing to the cloud repository 
 repository 
 cat >> .gitignore 
 data/ 
 mynotest.txt

 # publish ignoring mentioned iles or directories 
 git push 

 * Branching 
 - git branch 
 - git branch newBranch 
 - git checkout -b newBranch # creating ans switching to new branch 
 - git checkout branch # switching to existing branch 

 * working with githyb 
 - git clone userl.git # clone brand new project from the cloud 
 - git push # publish the changes from your local to cloud 
 - git pull # get the updates from cloud repo 
