## learn git
* create a new repository on the command line
```
echo "# learngit" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:susengo/learngit.git
git push -u origin master
```
* push an existing repository from the command line
```
git remote add origin git@github.com:susengo/learngit.git
git push -u origin master
```