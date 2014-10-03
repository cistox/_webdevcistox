_webdevcistox
=============
$ sudo apt-get update
$ sudo apt-get install git
$ mkdir /opt/cistoxFramework
$ cd /opt/cistoxFramework
$ git clone https://github.com/cistox/_webdevcistox.git
$ cd :/opt/cistoxFramework/_webdevcistox

$ ls -la 
drwxr-xr-x 4 root root 4096 Oct  3 14:33 .
drwxr-xr-x 3 root root 4096 Oct  3 14:21 ..
-rwxr-xr-x 1 root root  101 Oct  3 14:36 adminGIT.sh
drwxr-xr-x 8 root root 4096 Oct  3 16:20 .git
-rwxr-xr-x 1 root root  101 Oct  3 14:35 nitishGIT.sh
-rwxr-xr-x 1 root root   99 Oct  3 14:36 vinayGIT.sh
drwxr-xr-x 4 root root 4096 Oct  3 07:18 work

$ chmod 755 nitishGIT.sh
# you have already done the modification in dir, then execute the following
# command to commit your changes to GITHUB server (remote repository)
$ ./nitishGIT.sh


# you want to pull the new version from git server, then do
$ git status
$ git stash # it will save your data on the local repository
$ git pull # it will pull the new version from the remote repository (careful with your local data)
$ git stash apply 

