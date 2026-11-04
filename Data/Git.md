Firstly I gotta go into my particular folder where i want my local  git files
![[Pasted image 20261021192817.png|595]]
so here mkdir means i create anothe folder for that repo
1. [[git init]] 
2. ls - lists the files in my directory
3. ls -a includes hidden files
4. git status - shows everything
5. touch name - makes a new file



## okayyy so if i have an already local code how do i push it to git?

sooo I got to the folder okay 
then i say
git init
git add .
git commit -m "SMTG"

git branch  -M main
git remote add origin SSH
git push -u origin main ==🟡--force==


if it says privacy restriction do this

git config user.email "mahalux2007-art@users.noreply.github.com"
  git commit --amend --reset-author --no-edit