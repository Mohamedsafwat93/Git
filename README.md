# Git
GitStudies 
#Basic Commands 
git add -> to add the created files on local Repo
git rm & file name and to be in it location -> to remove file
git Commit -m "Here include your Ref Comment" -> to commit the new files and prepare them to be pushing
git reset head -> to remove any files you don't need to add or commit it 
git status -> to know the Git local Dir status 
git branch -> to know your current branch 
git push Remotename Branchname -> to push your changes on local Repo
git Remote -v -> to know your remote location
git clone + ur Repo Link -> to add a Repo into your local Path
git pull remote repo -> to pull the changes of the remote to local "Get Fetch & Get Merge"
git config -l -> to list your github account full configuration 
git help config -> to display full manual config
git config --global user.mail -> to display the usermail value & set it too 
git config --global --unset user.name -> to revert the username value
git config --global --edit -> to modify it on editor 
ssh-keygen -t rsa -b 4096 -C "yourmail" -> to generate a Key for your access 
git push -u remotename branchname -> to pull and push at the same.
git config --global alias.br branch -> to get the branch name by shortcut of 2 char's "br"
git config --global alias.cm commit -m -> to summarize the commit command to be "cm" 
----------
https://snyk.io/blog/10-git-aliases-for-faster-and-productive-git-workflow/
the above url for git alias list to be summarized
----------
git branch Test -> to create new branch 
git checkout test -> to switch to Test branch 
git branch -d Test -> to delete the branch - (keep note if use -D it will use if include update , and if used -d during updates or merging it will not force)
git checkout -b Test -> to create branch and auto switch to it 
git branch -m TestDemo -> to rename the branch 
git merge Test -> to merge the Test Branch to the main 
Stash -> to store your process into hidden area 
git stash -> to store the files 
git stash list -> to show what you stashed = stored 
git stash pop -> to drop your hidden files to local repo 
git stash save "the changes name" -> to rename the stashed file 
git stash apply -> to commit the last changes with store it in stash without changes 
git stash pop stash@{0} -> to drop specific item 
git stash apply stash@{1} -> to apply specific item with store it in stash area 
git stash drop stash@{0} -> to drop an specified stash by it ID
git stash show -> to show what stash lnclude and details 
git stash show stash@{0} -> to show the included files by stash ID 
git stash clear -> to delete all files in stash 
git clean -n -> to show what you need to delete 
git clean -f -> to force the deleting 
git log -> to show the commits with head = meaning the last commit
git reset --hard hash -> get the hash of the git log next to the commit to reset it 
git push origin main --force -> to force push the changes after Head resseting
touch .gitignore -> to create and file that ignore all not required files like logs, include the extension that need to ignore into the file by Visualbasic code and to except one, write ! as a not and write the allowed file
git rm foldername -r -> to remove all folder 
search on google for git ignore patterns for work around
git tag v1.0 -> to create an tag that include your messege
git push origin v1.0 -> to push your created tag on remote repo 
git tag -a v2.0 -m "2nd version" -> to add the annotate tag 
git push origin v2.0 -> to push it on remote repo too 
git tage -l "v1.*" -> to give me the tags with this version name 
to push release or tag it's good on gui too 























