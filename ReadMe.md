# bash concepts that you will need for your day to day jobs

## ls

this command is used to see what is inside of the directory where you are, there are some variants of the command one of the most importan is ls -ltr and ll, both do the same thing but ll does not work in all linux distributions. one really useful way to execute the command is with the addition of wildcards

## ls demo

![Image](img/ls.png "ls command image")

## cd

cd command allow the movement of the user beetween directories, only executing cd will send you to the home directory (whatever you have configure as home directory), cd .. will take you one folder behind from your current position, cd follow by a path starting with slash will take you to a absolute path while a path not starting with slash will take you to a relative path. remember that while you are typing a direction you can press tab to autocomplete. cd - will take you to the position you were just before the last move.pwd show you were you currently are.When there are spaces in the direction you can put the whole path and you can use enviroment variables, this trick is used when an important folder is located in different paths in different servers like is the case with dev and prod servers 

## ls demo

![Image](img/cd.png "cd command image")

## cat-head-tail

Commands for showing in screen the content of a file, using cat show all of the command, using the flag "head" along with the flag "-n" can return the first n lines of a document. using the flag "tail" give us the n lines of the document.

## cat-head-tail demo

![Image](img/cat-head-tail.png "cat head tail command image")

## rm

This is the command we use for the deleting files. When you want to eliminate a whole folder we use the recursive version rm -r, if dont want to receive questions asking if you are sure about the delete operation you should pass the -f flag, if you dont want the files in the rubbish bin you should pass the -skipTrash flag

## rm demo

![Image](img/rm.png "cat head tail command image")

