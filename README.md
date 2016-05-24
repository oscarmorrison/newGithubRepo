newGit is a way to create a new repo using the github curl api from the command line

## Instructions ##

To use this script, add it to a folder in your path. I have a folder called '''.scripts''' in my home directory,
(that is on my path).

To do this 

```
cd ~
mkdir .scripts
vim bash_profile
```

then add 
```
PATH="PATH=$PATH:$HOME/.scripts" 
export PATH
```
You then need to refresh your profile
You can do this by typing
```
source .bash_profile
```
now just clone repo git@github.com:oscarmorrison/newBitBucketRepo.git
to your new scripts directory
now you need to make executable
```
chmod 775 newGit
```

now edit newGit
```
vim newGit
````
and change 
USERNAME = "YOURBITBUCKETUSERNAME"
PASSWORD = "YOURBITBUCKETPASSWORD"
to your bitbucket username and password

When you are in a directory that you want to upload to bitbucket in a new repo
just type 

```
newGit
```

add it will initialised directory as a git repo (locally),
add files, commit, and push to origin (remote)


Enjoy!

-----------

Forked from https://bitbucket.org/hannesr/fillbucket/overview