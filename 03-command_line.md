# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > "cd" change directory by going into folder  
"ls" list out files in directory  
"pwd" shows current full directory  
"touch" creates file  
"rmdir" removes directory  
"cp" copies file  
"mv" move file  
"cat" stream file  
"find" find file  
"env" enviornment  

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

> > "ls" short lists all the files in the directory  
"ls -a" short listing includes hidden files (all files)  
"ls -l" long listing of files  
"ls -lh" long listing with readable file sizes  
"ls -lah" long listing with hidden file with newest file on top  
"ls -Glp" no group in long listing with indicator to directories (shown by /)  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > -lah  
-c  
-F  
-p  
-t  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > "xargs" reads items from standard input and executes the commpand one or more times with any arguments followed by items read from the input with blank lines ignored.  

For example,  

echo 1 2 3 4 5 6| xargs -n 3  
returns the numbers 1 to 6 in two lines of 3 numbers.

