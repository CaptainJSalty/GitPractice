# GitPractice

#This is my first time using Git 

#In the beginning, I have learnt to create, add, and commit files in local repository

"""
git init 

git add .                        (Add all files)
git add <filename.xx>            (Add specific file)

git rm --cached <filename.xx>     (Remove file from staging)

git status                        (Check status of files) 

git commit -m ""                  (Commit with memo)

touch xxx.extension               (Create file with specific extension)

git config --global user.name "" 
git config --global user.email ""

git remote set-url origin <link.git>    
git remove -v                       (List the git link)


"""




###Error Types 

(1) fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

(2)$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

<git branch --set-upstream-to=origin/main main>


(3) $ git pull
fatal: refusing to merge unrelated histories

<git pull origin main main --allow-unrelated-histories>
