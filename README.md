"# document" 



## Note

### create a new repository on the command line

```git
echo "# document" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ecs-support/document.git
git push -u origin main
```

### push an existing repository from the command line

```git
git remote add origin https://github.com/ecs-support/document.git
git branch -M main
git push -u origin main
```