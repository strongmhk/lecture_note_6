# Version control and Collaboration  
### Changes vs Snapshots  
Git use Snapshots  

### local vs centralized vs Distributed  
Git use Distributed  

### Three States in Git  

- Modified(working Directory)   
- Staged(Staging Area)  
- Comitted(git directory)  

### Git setup  
git config --global user.name "Minhyung Kim"  
git config --global user.email alsgudtkwjs@naver.com  
git config --global init.defaultBranch main  

git config --list  (show git list)    
git config --list --show-origin (show git origin list)  
git config user.name (check user name)  

### Initializing a Repository in an Existing Directory  
- git init  
- ls -lha  

### Checking Repository Status  
- git status  
Untracked files (not exist in Staging Area)  

### Adding a new file to be staged(tracked)  
- git add words.txt  
Changes to be committed : (files in staging Area)  
- git add words.txt hellow_world  

- use nano ($ nano words.txt) <- keep edit  
- git add . (add all files to staging area)  

### Unstaging a file  
- git rm -cached words.txt  

### Ignoring a file  
- nano .gitignore  
words.txt  

### Commit  
- git commit -m "initial commit"  

### Change branch name  
- git branch -m master main  










