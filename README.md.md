### Creating a SSH and pushing to GitHub

### Step 1: 
`pwd` - this command locates the current working directory

`ls` - this command is used to list files

`ls -a` - this command locates all the files including hidden ones

`mkdir .ssh` - this command creates a new .ssh directory

`cd.ssh` - this command adds a new file .ssh

`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"` - this command generates your key pair

`ls` - this command will then list your private and public key 

### Step 2:

`cat (name of public key.pub)`

`Go to Github and create new SSH`

`cd` - This command will be used to locate you to the correct directory 

`eval ssh-agent` creates an agent

`ssh-add ~/.ssh/(enter name of public key)` - Then add this command followed by the name of your public key.

`git remote set-url origin (locate SSH url in github)`

### Step 3: pushing to Git Hub

`git status`

`git add`

`git commit-m "comment`

`git push -u origin main` df
