#!/bin/bash " this is the first line of your script, tells the OS to invoke the specified shell to execute the commands that follow in the script
pwd "shows the current directory you are working in "
ls  "used to list the content in your cureent directory"
cd ~  "changes the working directory to the user’s home directory"
ls -l "displays the current directory content in a long format"
ls -a -l  "Display current directory contents, including hidden files"
ls -lna "displays the content of the current directory with the long formant,users id and hidden files"
mkdir /tmp/my_first_directory "create the folder in the tmp"
mv /tmp/betty /tmp/my_first_directory "moving file betty in tmp to my_first_directory in tmp"
rm /tmp/holberton/betty "deleting the file of betty in tmp"
rm -r /tmp/my_first_directory "Delete the directory my_first_directory that is in the /tmp directory"
cd - "a script that changes the working directory to the previous one"
file /tmp/iamafile "it prints the file named iamafile"
ln -s /bin/ls __ls__ "used to create a symbolic link in the current directory"
cp -nu *.html .. "script that copies all the HTML files from the current working directory to the parent of the working directory"
