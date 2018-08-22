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

>>### Andrée's Cheat Sheet for Command Line
* print working directory - `pwd`
* create directory - `mkdir`
* delete directory - `rmdir`  
* create file using `touch` command -`touch <filename>` 
* deleting a file - `rm`  
* rename file - `mv <filename> <new filename>`
* list hidden files - `ls -a`
* copy file from directory to another - `cp <source> <destination>`    
* get information about what type of file or directory it is - `file`
* move to a different directory -`cd`
* list contents of directory - `ls`

---

### Q2.  List Files in Unix   

What do the following commands do:  
>>
`ls`  lists all files and directories in working directory  
`ls -a` lists all contents of working directory, including hidden files and directories  
`ls -l`  lists out all contents of directory in long format  
`ls -lh`  lists out all contents of directory in long format but with file sizes in human readable format  
`ls -lah`  lists out all contents of directory, including hidden files and directories, in long format but with file sizes in human readable format    
`ls -t`  orders files and directories by the time they were modified last  
`ls -Glp`  lists all contents of directory in long format with directories displayed with a `/` and different color fonts  


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>>
`ls -R` lists all subdirectories  
`ls -1` lists each entry on a  line  
`ls -u` lists files by the time the file was accessd  
`ls -d` lists only the directories  
`ls -C` lists files in a column format

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` is a command that converts standard input to arguments, especially for tools that cannot accept standard input as parameters like `echo` `rm` `mkdir` etc.  
Example: `echo 'I am enjoying this Metis pre-work' | xargs mkdir`
`ls`




 

