
lost everywhere

git cheatsheet is this file dont lose it
smackdown of knowledge


can also use notepad++ "filename.ext" 
# is the heading
## is sub heading
### another subheading
#### etc



Git commands
```bash
git init REPO-NAME
```
-	creates a repository called REPO-NAME

```bash
git status
```
- shows the status of the git repository

```bash
git shows
```
- shows the commit command history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
- adds the file FILENAME and ANOTHERFILENAME to the stash	make sure the files are related to each other


```bash
git commit -m "message"
```
- commits the stashed files to the repo and adds the MESSAGE that describes what was done

```bash
git log
```
tells you the history of the commits commited at this point in time

```bash
git alias.CODE "extensions log --all --decorate"
```
can merge extensions of a long command and shortcut it currently have one "git adog"

```bash
git log --all --decorate --oneline --graph
```
displays a graph of the commits, on commit per line

## other git things

**.gitignore** is a file that tells git files/folders that are not to be apart of the repository	( that is - ignored when adding/committing)









add
edit
commit


						commited
					git		|			commit
							|	
					git		Stash 		add
							|	
							|
					git		working		add
							|
							|
							edit