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

## cp

This is the command we use for copying and pasting files, mkdir is the command we use forcreating folders, when you want to create all the folders required you pass the -p flag

## cp mkdir demo

![Image](img/cp-mkdir.png "cp mkdir command image")

## rm

This is the command we use for the deleting files. When you want to eliminate a whole folder we use the recursive version rm -r, if dont want to receive questions asking if you are sure about the delete operation you should pass the -f flag, if you dont want the files in the rubbish bin you should pass the -skipTrash flag

## rm demo

![Image](img/rm.png "rm command image")

## history, pipe symbol and grep

Sometimes you use a command and later you forget the correct way to write that same command, the good new is that all of those command we execute are stored and we can see it executing the history command, and that generate another challenge, finding that one command inside all of all of that, the solution, we pass the result of one command to another another command with pipe symbol (the vertical line) and in that other command (in this case grep) we filter all the text generated taking only the lines that include a certain word. Grep can also be used to filter documents that contain certain lines as you can see in the image below

## history-pipe-grep demo

![Image](img/history-pipe-grep.png "history-pipe-grep command image")


# the vim editor

## important consideration

I usually prefer images and text to videos because the last one need more time, but I also understand that some concepts is better to see the whole process, so in this part of the tutorial I will give you the exact minute where I talk about that concept in the video 




