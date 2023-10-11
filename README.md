#Demo

Description!

#adding some basic changes

command to list hidden files/directories in bash - Linux ls -la
command to list hidden files in PowerShell Get-ChildItem . -Force

git clone
## Once cloned (copied to local machine) we then work on files 
git status
## shows all the files that have been created, updated or deleted but havent been saved in a commit yet.
git add .
## will add all the files and changes we made in files. In the other words they would be staged to git. Then we can check it again with git status to check that all the changes have been tracked, and ready to be commited.
git commit -m "
## we will commit changes now with -m which is the message where we explain what was done in the commit. First -m is what appears in GUI Git as a first box in commited file under the name and the second -m id the bigger box under with broader description of what is in the file. These updates are still not live (updated on GitHub). We will make it live using another git command:
git push
