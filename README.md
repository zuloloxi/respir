
"# respir" 

to ...

…or create a new repository on the command line


```  
echo "# respir" >> README.md
git init
git add README.md
git add -A
git commit -m "first commit"
git remote add origin https://github.com/zuloloxi/respir.git
git push -u origin master
```


…or push an existing repository from the command line


``` 
git remote add origin https://github.com/zuloloxi/respir.git
git push -u origin master
```

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.60 MiB | 309.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/zuloloxi/respir.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```
