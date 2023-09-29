# Linux Comandos Básicos

https://github.com/amgauna/Linux-Basico/blob/main/linux-comandos-basicos.jpg

# Linux 40 comandos úteis                                                      
        
* pwd = Print Working Directory = Shows the absolute path of the working directory

* mkdir = Make Directory

* mkdir reports/ = Creates a single directory reports

* mkdir -p reports/finance/yearly/ = Creates entire directory structure

* cd = Change Directory

* cd icons = Switch to the "icons" directory

* cd/ = Switch to the previous directory

* cd.. = Switch to the parent directory

* cd = Switch to the home directory

* ls = List For current working directory

* ls /home/ = List For /home/

❯ ls -a
# Includes hidden files

❯ ls -R
# Recursively for subdirectories

❯ ls -l
# Lists in detail

❯ ls -ltr
# Sorted. Latest modified one is at the top.

➎ cp

Copy

❯ cp file1.txt file2.txt
# Copies the file file1.txt to file2.txt

❯ cp -r dir1/ dir2/
# Copies entire directory "dir1" to "dir2"

➏ mv

Move

❯ mv file1.js images/
# Moves the file to images/

❯ mv file1.js file2.js
# Renames the file1.js to file2.js

➐ touch

❯ touch new_file
# Creates a new empty file "new_file"

❯ touch -m old_file
# Changes the modification time

➑ cat

Concatenate

⬙ It is used to view, create, and concatenate files.

❯ cat file.txt
# Lists the contents of file1.txt to std output

❯ cat > file.txt
# Creates a new file

❯ cat file1 file2 > file3
# Concatenates file1 & file2 to file3

➒ rm

Remove

❯ rm file1.txt
# Removes a file

❯ rm -r dir1
# Removes an empty directory

❯ rm -rf dir2
# Removes any directory

➓ find

Search based on a regular expression

❯ find ./ -name "xyz"
# Finds files and directories whose name is xyz

❯ find ./ -type f -name "*.java"
# Finds files whose name ends with .java

➊➊ grep

Global Regular Expression Print

❯ grep "hello" message.txt
# Lists all lines of "message.txt"
# that contain "hello"

❯ grep -c "hi" message.txt
# Outputs the number of lines in
# "message.txt" that contain "hi"

➊➋ head

❯ head message.txt
# Outputs first 10 lines of message.txt

❯ head -n 5 message.txt
# Outputs first 5 lines of message.txt

➊➌ tail

❯ tail message.txt
# Outputs last 10 lines of message.txt

❯ tail -n 5 message.txt
# Outputs last 5 lines of message.txt

❯ tail -f app.log
# Shows new entries in app.log
# as and when they get added

➊➍ diff

Difference

❯ diff /dir1/package.json /dir2/package.json
# Compare the contents of the two files
# line by line and lists out all differences

➊➎ alias

❯ alias lsa="ls -a"
# Creates a new alias "lsa" for "ls -a" command

❯ alias
# Lists all aliases for the current session

               -- More Useful Commands --

❯ echo
Displays the given text in the terminal

❯ which
Shows the directory where the command is present 

❯ whoami
Displays the username of who currently is using this session

❯ man
Displays the manual page of any command

❯ tar
Creates and extracts an archive file

❯ chmod
Changes the mode (permission) of a file

❯ chown
Changes the ownership

❯ du
Checks how much space a file or a directory takes

❯ ps
Lists the processes that the current shell session is running

❯ kill
Kills (terminates) a process

❯ free
Shows the amount of free memory

❯ vmstat 10
Every 10 seconds, show statistics

❯ iotop
Displays the disk IO usage details

❯ systemctl
Manages systemd and services

❯ journalctl
Views systemd, kernel, and journal logs

❯ env
Prints list of environment variables

❯ host
Does DNS lookup operations

❯ hostname
Obtains the DNS name

❯ ping
Checks the network connectivity b/w host and server

❯ curl
Transfers data to or from a server

❯ wget
Retrieves/downloads content from the internet

❯ history
Displays all the commands used in the past

❯ clear
Clears the terminal window

❯ sudo
Allows the current user to act as a superuser or, a root user for running a specific command

❯ exit
Ends a shell session and closes the terminal

