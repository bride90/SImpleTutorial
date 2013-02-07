Summary Tutorial


				GitHUb - Tutorial





 CREATE Files
**************

create directory : 
$ mkdir ~/Hello-WOrld

---------------------------------------------------------------------------------

change directory : current -> newly directory
$ cd ~/Hello-World

---------------------------------------------------------------------------------

set up necessary GIT files
$ git init

---------------------------------------------------------------------------------

create new files :
$ touch (file_name)

---------------------------------------------------------------------------------

After Editing Files
$ git status

---------------------------------------------------------------------------------





 COMMIT Files
**************

add file into list before commited :
$ git add (file_name)
$ git add .
---------------------------------------------------------------------------------

commit/sent the files :
git commit -m 'your_title'

---------------------------------------------------------------------------------





 PUSH COMMIT Files
*******************

create remote"origin" -> pointing to GITHUB
$ git remote add origin <link - https://(link)>

---------------------------------------------------------------------------------

send commit in the master branch
$ git push origin master

or

$ git push origin --a		//for all files

---------------------------------------------------------------------------------





 DELETE Files
**************

delete file :
$ git rm -rf <File_Name>
$ git add -A

**note (remove from GitHUb webpage)
$ git commit -m 'remove file'


---------------------------------------------------------------------------------





General COmmand :

add		- Add file content to the index
bisect		- Find by binary search the change that itroduced a bug
branch		- List, create, or delete branches
checkout	- checkout a branch or paths to the working tree
clone		- Clone a repository into a new directory
commit		- Record changes to the repository
diff		- SHow change between commit, commits and working tree, etc
fetch		- Download object and refs from another repository
grep		- Print line matching a pattern
init		- Create an empty repository or reinitialized an existing one
log		- show commit log
merge		- join two or more development histories together
mv		- Move or rename a file, a directory, or a symlink
pull		- Fetch from and merge with another repository or a local branch
push		- update remote refs aong with associated object
rebase		- Forward-port local commits to the update upstream head
reset		- Reset current HEAD to the specific state
rm		- remove files from the working tree and from the index
show		- Show various types of objects
status		- Show the working tree status 
tag		- Create, list, delete or verify a tag 





---------------------------------------------------------------------------------

















