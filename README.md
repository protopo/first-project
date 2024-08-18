$ pwd print working directory
$ cd  change directory 
$ ls list directory contents
$ ls -a list directory content all
$ touch file.txt create file
$ mkdir folder create directory
$ cp file.txt folder/ copy file to directory
$ mv file.txt ./folder move file to directory
$ cat file.txt concatenate and print file
$ rm file.txt remove file
$ rmdir folder remove directory (if empty) 
$ rm -r folder remove directory (recursive)

$ git config --global user.name 
$ git config --global user.email 

$ cat ~/.gitconfig
$ git config --list 

$ git init create repository
$ rm -rf .git delete repository
$ git status check repository status
$ git add file.txt track file
$ git add . track directory
$ git add --all track repository
$ git commit -m "Commit" commit 
$ git log commit history

$ git remote add origin URL connect local to remote repository
$ git remote -v check connection local to remote repository
$ git push -u origin main connect local to remote branch
$ git push update remote repository