# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 
cd	Home directory
cd [folder]	Change directory
cd ~	Home directory
cd /	Root of drive
ls	Short listing
ls -l	Long listing
ls -a	Listing incl. hidden files
ls -lh	Long listing with Human readable file sizes
ls -R	Entire content of folder recursively
sudo [command]	Run command with the security privileges of the superuser (Super User DO)
open [file]	Opens a file
open .	Opens the directory
top	Displays active processes. Press q to quit
nano [file]	Opens the Terminal it’s editor
pico	[file]	Opens the Terminal it’s editor
q	Exit
clear	Clear screen

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 
Short listing
Listing incl. hidden files
Long listing
Long listing with Human readable file sizes
Long listing with Human readable file sizes, including files starting with '.'
Long listing with Human readable file sizes, sorted by modification times, newest first
Long listing, with no group names, append / indicator to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
-b	Displays nonprinting characters in octal.
-c	Displays files by file timestamp.
-f	Interprets each name as a directory, not a file.
-m	Displays the names as a comma-separated list.
-n	Displays the long format listing, with GID and UID numbers.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 
'build and execute command lines from standard input'
echo 'one two three' | xargs mkdir
ls
one two three
 

