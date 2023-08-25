# PROJECT: ODIN-RECIPES
## Setting up Git
**Step 2.3: Create an SSH key**
| Command | Function |
| ------------- | ------------- |
| ls ~/.ssh/id_ed25519.pub | to check if SSH key is installed  |
| ssh-keygen -t ed25519 -C (youremail) | to create new SSH key |
|cat ~/.ssh/id_ed25519.pub|to show openssh public key format|


**Create the repository**

- mkdir repos -> cd repos/ -> git clone ssh key
<br>clone your repository from GitHub onto your computer
- git remote -v <br>to show remote connection

__Using the Git workflow__
| Command |Function |
|---|---|
| touch hello_world.txt  |  to create a new file |
|gid add hello_world.txt|add file to staging area|
|git status| to checked if file is staged|
|git commit -m "Add hello_world.txt"|to make a commit|
|git status|to check if file is committed|
|git log|to check commit history|
|git push|Push your work to Github|
|git pull|to pull the changes from local repos and merge it to remote repos|
|code. | to open file in visual studio code|
|git add .|to add all files in the current directory to the staging area |
|git config --global core.editor "code --wait"|git commit to type message with VSCode|
