<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  
<tr> <td>  git help </td> <td>	Get help on a command </td> <td> 	$ git help push</td></tr>
<tr> <td>  git config </td> <td>	Configure Git </td> <td> 	$ git config --global …</td></tr>
<tr> <td>  source <file> </td> <td>	Activate Bash changes </td> <td> 	$ source ~/.bash_profile</td></tr>
<tr> <td>  mkdir -p </td> <td>	Make intermediate directories as necessary </td> <td> 	$ mkdir -p repos/website</td></tr>
<tr> <td>  git status </td> <td>	Show the status of the repository </td> <td> 	$ git status</td></tr>
<tr> <td>  touch <name> </td> <td>	Create empty file </td> <td> 	$ touch foo</td></tr>
<tr> <td>  git add -A </td> <td>	Add all files or directories to staging area </td> <td> 	$ git add -A</td></tr>
<tr> <td>  git add <name> </td> <td>	Add given file or directory to staging area	 </td> <td> $ git add foo</td></tr>
<tr> <td>  git commit -m </td> <td>	Commit staged changes with a message	 </td> <td> $ git commit -m "Add thing"</td></tr>
<tr> <td>  git commit -am </td> <td>	Stage and commit changes with a message	 </td> <td> $ git commit -am "Add thing"</td></tr>
<tr> <td>  git diff	</td> <td>Show diffs between commits, branches, etc.	 </td> <td> $ git diff</td></tr>
<tr> <td>  git commit --amend </td> <td>	Amend the last commit	 </td> <td> $ git commit --amend</td></tr>
<tr> <td>  git show <SHA></td> <td>	Show diff vs. the SHA	 </td> <td> $ git show fgdf...</td></tr>
<tr> <td>  git remote add	   </td> <td> Add remote repo	 </td> <td> $ git remote add origin</td></tr>
<tr> <td>  git push -u <loc> <br>	   </td> <td> Push to branch to remote	 </td> <td> $ git push -u origin master</td></tr>
<tr> <td>  git push	   </td> <td> Push to default remote	 </td> <td> $ git push</td></tr>

<tr> <td>  .gitignore	 </td> <td> Tell Git which things to ignore</td> <td>	$ echo .DS_store >> .gitignore</td></tr>
<tr> <td>  git checkout <br>	 </td> <td> Check out a branch</td> <td>	$ git checkout master</td></tr>
<tr> <td>  git checkout -b <br>	 </td> <td> Check out & create a branch	</td> <td>$ git checkout -b about-page</td></tr>
<tr> <td>  git branch	 </td> <td> Display local branches</td> <td>	$ git branch</td></tr>
<tr> <td>  git merge <br>	 </td> <td> Merge in a branch</td> <td>	$ git merge about-page</td></tr>
<tr> <td>  git rebase	 </td> <td> Do something possibly weird & confusing</td> <td>	 </td></tr>
<tr> <td>  git branch -d <br>	 </td> <td> Delete branch (if merged)	</td> <td>$ git branch -d about-page</td></tr>
<tr> <td>  git branch -D <br>	 </td> <td> Delete branch (even if unmerged) (dangerous)	</td> <td>$ git branch -D other-branch</td></tr>
<tr> <td>  git checkout -f </td> <td> 	Force checkout, discarding changes (dangerous)</td> <td>	$ git add -A && git checkout -f</td></tr>

<tr> <td> git clone <URL></td> <td> 	Copy repo (incl. full history) to local disk</td> <td> 	$ git clone https://ex.co/repo.git</td></tr>
<tr> <td> git pull	</td> <td> Pull in changes from remote repository	</td> <td> $ git pull</td></tr>
<tr> <td> git branch -a	</td> <td> List all branches	</td> <td> $ git branch -a</td></tr>
<tr> <td> git checkout <br>	</td> <td> Check out remote branch and configure for push</td> <td> 	$ git checkout fix-trademark</td></tr>

</table>
