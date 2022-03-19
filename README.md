
# Git commands and Markdown

This repos contains some basic and most useful commands in Git.

# Git commands

## Installation
<details open>
<summary>Find out more </summary>
 
<pre>$ git --version </pre>

</details>

---

## Git configuartion 
<details open>
<summary>Find out more</summary>

<pre>$ git config --global user.name "[username]" </pre>

<pre>$ git config --global user.email "[valid-email]" </pre>

<pre>$ git config --global color.ui auto </pre>

</details>

---

## Working with Local Branch
<details>
<summary>Find out more </summary>
<br>

- Create a branch

<pre>$ git branch <branch_name> </pre>

<br>
  
- Display all branches

<pre>$ git branch -a </pre>

<br>
  
-  Delete a branch

<pre>$ git branch -d <branch_name> </pre>


<br>
  
- Delete remote branch

<pre>$ git push origin –delete [branchName] </pre>


<br>
  
- Checkout an existing branch

<pre>$ git checkout <branch_name> </pre>


<br>
  
-  Checkout and create a new branch

<pre>$ git checkout -b <new_branch_name> </pre>


<br>
  
- Merge a branch into an active branch

<pre>$ git merge <branch_name> </pre>


<br>
  
- Recover a deleted file and prepare it for commit

<pre>$ git checkout <deleted_file-name> </pre>

  
</details>

---

## Working With Remote Repositories
<details>
<summary>Find out more </summary>

<pre>$ git remote add origin <repository url> </pre>


<br>
  
- git Clone

<pre>$ git clone <remote url> </pre>


<br>
  
- git push

<pre>$ git push -u origin master </pre>


<br>
  
- git push

<pre>$ git pull origin master </pre>


<br>
  
- git fetch

<pre>$ git fetch <remote> <branch> </pre>

</details>

---


## Working With Local Repositories
<details>
<summary>Find out more </summary>


<br>
  
- Create a new Folder

<pre>$ mkdir test </pre>


<br>
  
- Initialize Git

<pre>$ cd test/ </pre>

<pre>$ git init </pre>


<br>
  
- Create Readme file

<pre>$ cat > Readme.md </pre>


<br>
  
- Staging

<pre>$ git add . </pre>

<pre>$ git add <filename> </pre>


<br>
  
- Check status

<pre>$ git status </pre>


<br>
  
-  Committing staged files

<pre>$ git commit -m "Commit message" </pre>


<br>
  
- Remove file

<pre>$ git rm <file_name> </pre>


<br>
  
- logs

<pre>$ git rm <file_name> </pre>

</details>

---

## Additional Commands
<details>
<summary>Find out more </summary>


<br>
  
- git stash

<pre>$ git stash -u </pre>


<br>
  
- brings the stashed work back to the working directory

<pre>$ git stash pop </pre>

<br>
  
- undoing changes

<pre>$ git reset <file> </pre>

<pre>$ git clean -n </pre>


<br>
  
- Define a tag

<pre>$ git tag <tagname> </pre>


<br>
  
- git diff

<pre>$ git diff </pre>

<pre>$ git diff --staged </pre>

<pre>$ git diff <commit1> <commit2> </pre>

</details>

---

