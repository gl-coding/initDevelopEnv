#all the configure file is begin with '.' to hide in the environment
#you should run "ls -a" to see all the hid files

#copy all the file to your home dir "~/"
#then run the command bellow in your home dir "~/" to make the configure to take effect

echo "PATH=$PATH:~/sysconfig/" >> .bashrc
source .bashrc
