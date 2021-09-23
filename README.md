# hello-world-v2
$
$
$ git init
$ git add .		
$ git commit -m "First commit"
$ git remote add origin <https://github.com/Domzzzzz/hello-world-v2.git>
# Sets the new remote
$ git remote -v
# Verifies the new remote URL
$ git push -u origin master
$ git checkout -b readme-edits
$ git branch readme-edits
$ git checkout readme-edits
$ git commit -a -m "added new line for demo"
$ git checkout master
$ git merge readme-edits
$ git push
$ git branch -d readme-edits
$ git checkout -b feature
$ git add .
$ git commit -m "added new file index.html"
$ git checkout master
$ git merge feature
$ git push
$ git branch -d feature
