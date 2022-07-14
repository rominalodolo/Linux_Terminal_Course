# The 50 Most Popular Linux and Terminal Commands

> Youtube tutorial by Free Code Camp 
> Full Course for Beginners. 

Get the Course Here: [Link](https://www.youtube.com/watch?v=ZtqBQ68cfJc)

Get the Linux Command handbook Here: [Link](https://www.freecodecamp.org/news/the-linux-commands-handbook/)

## Course Contents 
- (0:00:00) Introduction
- (0:04:37) Why use the command line?
- (0:06:56) The world of operating systems
- (0:10:56) What is Linux?
- (0:16:58) Shells and Bash
- (0:19:28) Setup For Linux Users
- (0:20:28) Setup For Mac Users
- (0:21:05) Setup For Windows (WSL)
- (0:29:43) Using The Terminal
- (0:31:12) whoami
- (0:32:34) man
- (0:33:40) clear
- (0:36:42) intro to options
- (0:39:05) pwd
- (0:41:07) ls
- (0:49:21) cd
- (1:00:40) mkdir
- (1:06:33) touch
- (1:12:03) rmdir
- (1:13:05) rm
- (1:21:26) open
- (1:23:55) mv
- (1:27:51) cp
- (1:31:56) head
- (1:33:02) tail
- (1:35:27) date
- (1:36:02) redirecting standard output
- (1:41:48) cat
- (1:46:15) less
- (1:49:17) echo
- (1:51:38) wc
- (1:53:52) piping
- (1:56:43) sort
- (2:01:09) uniq
- (2:06:59) expansions
- (2:17:08) diff
- (2:21:01) find
- (2:32:10) grep
- (2:36:52) du
- (2:40:55) df
- (2:44:04) history
- (2:47:32) ps
- (2:51:50) top
- (2:54:02) kill
- (3:00:13) killall
- (3:01:37) jobs, bg, and fg
- (3:09:40) gzip
- (3:12:18) gunzip
- (3:15:27) tar
- (3:23:36) nano
- (3:31:17) alias
- (3:42:48) xargs
- (3:50:57) ln
- (4:01:49) who
- (4:03:47) su
- (4:08:32) sudo
- (4:18:36) passwd
- (4:21:54) chown
- (4:31:08) Understanding permissions
- (4:47:15) chmod


### Why use the command line?
> More control over your machine
> 
> It's faster
>  
> Automate many tasks
> 
> It's available everywhere 
> 
> A basic requirement 
> 
> Cloud computing
> 
> Higher paying jobs


### The world of Operating systems 
- Microsoft NT decendents like Wondows, XBox OS, Windows mobile
- Everything else with lineage going back to Unix which includes Mac OS, linux, andriod, chrome, PS4..
 
 Check out the full family tree of the operating systems timeline [Full Image](https://eylenburg.github.io/pics/Eylenburg_Operating_System_Timeline_Family_Tree.svg)
 
![sace](https://user-images.githubusercontent.com/83961643/178505100-bd71e90b-5305-4e90-9c49-24d5c103ea44.jpeg)

![linuxhistory](https://user-images.githubusercontent.com/83961643/178504377-961834a2-c866-446e-a62f-5954a721b63a.jpeg)

[Reference](https://eylenburg.github.io/os_familytree.htm)
 
Unix is like the grandfather of Linux. Unix was developed in the 1960s.

![systems](https://user-images.githubusercontent.com/83961643/178508235-edb0af71-88c4-4cae-95fd-e04f61cee618.jpeg)

[Reference](https://commons.wikimedia.org/wiki/File:Unix_history-simple.svg)

Free software movement - being able to collaborate etc. Leader Richard Stallman. He started GNU. 
The linux Kernel was developed by Linus Torvalds. 
 
True Unix 
Unix-Like (not certified version)
 
Distributions: Fedore, Ubuntu, Debian, Slackware.
 
Shell exposes the operating system to the user - it's the outer layer of the system like a sea shell 
Terminal is a program that runs a shell. 
 
bash: Most Linux-based systems the default shell program is bash - an acronym for "Bourne-Again SHell"  

Windows Subsystem for Linux [Read Blog Post](https://www.windowscentral.com/how-install-wsl2-windows-10) 
 
### `whoami`
 ![whoami](https://user-images.githubusercontent.com/83961643/178579824-cb9e0e9f-a910-4f3a-86c6-dae6ff7e316b.jpeg)

### `man`

 ![man](https://user-images.githubusercontent.com/83961643/178580144-fa3ad9f6-7ab1-4897-a265-38c24f703a16.jpeg)
 type `q` to quit

### `clear `
Clears the terminal screen - `-V` `-x` `[-Ttype]`

 ![clear](https://user-images.githubusercontent.com/83961643/178581244-5a9eec56-f324-4fe0-b9f6-d157f102bac8.jpeg)

### `pwd`
print working directory 

![pwd](https://user-images.githubusercontent.com/83961643/178581695-a55f955c-8144-42d4-a128-11e07a729971.jpeg)

### `ls`
list contents of a folder

![ls](https://user-images.githubusercontent.com/83961643/178581726-4f3c2950-c2c1-4e9d-8f35-6ac3af388dcb.jpeg)


### `cd`
Change directory - once in a directory you can move around with cd 

![cd](https://user-images.githubusercontent.com/83961643/178584864-4c9e9f82-82cb-4372-906a-1bc54604b80a.jpeg)
![cd](https://user-images.githubusercontent.com/83961643/178586430-bd0f7e74-8aa5-4e82-971b-aa86ca291c3b.jpeg)

`cd ..` takes you back a level 

[How directory is structured](https://www.seobility.net/en/wiki/Root_Directory) 
![Root-Directory](https://user-images.githubusercontent.com/83961643/178587347-4bac8c3d-1702-47ca-af52-29609ca2fbdb.png)

` cd / `  Takes you to the root directory 

` cd ~/Desktop/ ` will take you to home directory 

### `mkdir`
make directory - it creates folders for you 
![mkdir](https://user-images.githubusercontent.com/83961643/178588189-69e45437-a791-4c15-81e8-86c520673752.jpeg)

![newfolder](https://user-images.githubusercontent.com/83961643/178588997-13feff7d-67b5-4504-ba76-8c6bf36d3f64.jpeg)

### `touch`
Main use is to update the file timestamp - if you create new files they are completely empty 
Creates files 
![file](https://user-images.githubusercontent.com/83961643/178590346-b8916a35-c57d-4637-a2e9-7463e7ee26b0.jpeg)

` touch red.pdf orange.txt blue.svg `

### `rmdir`
removes a directory - look at `mkdir`


### `rm`
Remove 
![rm](https://user-images.githubusercontent.com/83961643/178592017-aecc86ee-90dd-40cc-a23d-a30761664433.jpeg)
` -v ` with give info like verbose/verbatim  

### `open`
open is a MAC only command but it opens files 

### `mv`
moves files and can change the name of the files 
![mv](https://user-images.githubusercontent.com/83961643/178697987-01b5d23e-b9ca-43a2-974d-d2ff932c7941.jpeg)

### `cp`
Copy files and folders 

To copy folders you need to add the -r option to recursively copy the whole folder contents


### `head`
Outputs the first part of files - tail would be the end 
You can specify the amount of lines you want of the file. But you will automatically get the first 10 lines. 

### `tail`
Outputs the last 10 lines of a file. 

### `date`
Prints out the date 

![date](https://user-images.githubusercontent.com/83961643/178701406-347062c9-7d8d-49db-a149-27a9119559e8.jpeg)

You can change how the date is displayed. 

You can redirect 

### Redirecting standard output 
You can redirect the information to a file and store results in a file.  
` > ` 
so if you want to move date to a file - ` date > today.txt` will create the file with that information stored there.

### `cat`
Add content to a file. Concatanates files. You can print the content of multiple files.

1. prints a file's content to the standard output `cat file`
2. print the content of multiple files `cat file1 file2`
3. you can concatenate the content of multiple files into a new file `cat file1 file2 > file3`
4. `>>` append the content of multiple files into a new file, creating it if it does not exist `cat file1 file2 >> file3`
5. `-n` Prints line numbers `cat -n file1`


### `less`
Shows the content stored inside a file, in a nice and interactive UI.
Quit the session using `q`


### `echo`
Echos back the same output as input. But you can make a new file and redirect it. 

### `wc`
Word count

![wc](https://user-images.githubusercontent.com/83961643/178706276-0098a27c-10e0-44ca-963d-1ac63a9877cc.jpeg)

Via pipes, we can count the output of running the `ls -al` command


### `piping`
` | ` used to pipe, or transfer, the standard output from the command on its left into the standard input of the command on its right.


### `sort`
Helps you sort them by name. Sorts the output. But does not store it. Case sensitive. You can tell it not the be cas sensitive. 

` cat file1 file2 | sort ` will concatinate the two files then sort them 

### `uniq`
Unique command - sorts lines of text. Get the lines from a file or using pipes from the output of another command 
` uniq file.txt ` 

` ls | uniqu `

### Expansions
`~` `$PATH` `*` 

### `diff`
Will give the output of the two files that are almost the same but not. The output will be the files that are NOT the same. 
` diff file1.txt file2.txt `

### `find`
Helps you find files. 

eg: ` find . -name '7' ` will give you that exact name 
` find . -name '*7*' ` to find anything with number 7 in it if you use the wildcard `*`

![find1](https://user-images.githubusercontent.com/83961643/178716170-12b25fea-504c-435c-9acc-d5bf969820d8.jpeg)

![find2](https://user-images.githubusercontent.com/83961643/178716181-5e18f23f-0e41-4b67-ad24-336e069e9c61.jpeg)


### `grep` 
Stands for global regular expression print

Search in files, or combine it with pipes to filter the output of another command.

You can provide REGEX patterns to your command to make it more powerful and do more. 

### `du`
Disk Usage 
You can see the size of files on your machine. 
![size](https://user-images.githubusercontent.com/83961643/178719244-eb3f10c7-4d7f-4148-8b40-13323af40200.jpeg)

 MegaBytes using `du -m`
 GigaBytes using `du -g`
 
 `-h` option will show a human-readable notation for sizes
 `-a` option will print the size of each file in the directories
 
 sort the directories by size: `du -h <directory> | sort -nr` piping to head to only get the first 10 results

### `df`
Display free disk space

![df](https://user-images.githubusercontent.com/83961643/178719846-aad36ced-4f36-48cd-aa22-4c63f42bfcd3.jpeg)


### `history`
Displays all the history. Typically the last 500 commands are stored in the history.

`history -c` clear the history,


### `ps`
Process Status: Your computer is running tons of different processes at all times.
Inspect them all using the ps command. 

`I` a process that is idle (sleeping for longer than about 20 seconds)
`R` a runnable process
`S` a process that is sleeping for less than about 20 seconds
`T` a stopped process
`U` a process in uninterruptible wait
`Z` a dead process (a zombie)

### `top`
Used to display dynamic real-time information about running processes in the system.
![top](https://user-images.githubusercontent.com/83961643/178721063-36fdd498-0c87-4369-a24e-54b3072c206a.jpeg)


### `kill`
Main function: terminate a program

`HUP` means hang up. It's sent automatically when a terminal window that started a process is closed before terminating the process.

`INT` means interrupt, and it sends the same signal used when we press ctrl-C in the terminal, which usually terminates the process.

`KILL` is not sent to the process, but to the operating system kernel, which immediately stops and terminates the process.

`TERM` means terminate. The process will receive it and terminate itself. It's the default signal sent by kill.

`CONT` means continue. It can be used to resume a stopped process.

`STOP` is not sent to the process, but to the operating system kernel, which immediately stops (but does not terminate) the process.

You might see numbers used instead
- eg: `kill -1 <PID>`.

`1` corresponds to HUP.
`2` corresponds to INT.
`9` corresponds to KILL.
`15` corresponds to TERM.
`18` corresponds to CONT.
`15` corresponds to STOP.

### `killall`
Sends the signal to multiple processes at once instead of sending a signal to a specific process id.
`killall <name>`


### `jobs`, `bg`, and `fg`
To get the job number, we use the jobs command
bg - background 
fg - foreground 
These go hand in hand - When we run a command in Linux / macOS, we can set it to run in the background using the & symbol after the command.

Eg: `top &` handy for long-running programs

run `jobs `,`top &` & `top -o mem &` so we can see we have 2 top instances running



### `gzip`
Compress a file using the gzip compression protocol named LZ77.

`gzip filename` This will compress the file, and append a .gz extension to it. The original file is deleted.

`gzip filename1 filename2` Compress multiple files by listing them.

`gzip -r a_folder` Compress all the files in a directory, recursively, using the -r option

### `gunzip`
An equivalent to the gzip command, except the -d option is always enabled by default.
`gunzip filename.gz` This will gunzip and will remove the .gz extension, putting the result in the filename file. If that file exists, it will overwrite that.

### `tar`
tape archive
Creates an archive named archive.tar with the content of file1 and file2
`tar -cf archive.tar file1 file2` The `c` option stands for create. The `f` option is used to write to file the archive.

Extract files from an archive in the current folder: `tar -xf archive.tar`
`x` stands for extract

Extract them to a specific directory `tar -xf archive.tar -C directory`

### `nano`
Beginner friendly editor `nano <filename>`.
Quit using ` ctrl-X `


### `alias`
Running a program with a set of options that you like using. 

alias will work until the terminal session is closed.

### `xargs`
Convert input from standard input into arguments to a command ie: the output of a command is used as the input of another command.
`command1 | xargs command2`

Use a pipe (|) to pass the output to xargs. That will take care of running the command2 command, using the output of command1 as its argument(s).


### `ln`
Used to create links.
![link](https://user-images.githubusercontent.com/83961643/178966920-89125d5c-8758-4491-823f-9788cf0b51da.jpeg)


### `who`
Displays the users logged in to the system


### `su`
While you're logged in to the terminal shell with one user, you might need to switch to another user.
`su <username>` 
su will start a new shell as another user.
When you're done, typing exit in the shell will close that shell, and will return you back to the current user's shell.


### `sudo`
Runs a command as root 
` sudo -i ` ![root](https://user-images.githubusercontent.com/83961643/178710876-53e4936e-a758-431f-9e52-dd15b4e405ef.jpeg)


### `passwd`
Users in Linux have a password assigned. You can change the password using the `passwd` command.


### `chown`
Every file/directory in an Operating System like Linux or macOS (and every UNIX system in general) has an owner.
The owner of a file can do everything with it. It can decide the fate of that file.
You can use chown to transfer the ownership to you etc.

### `ping` 
The ping command pings a specific network host, on the local network or on the Internet
`ping <host>` <host> could be a domain name, or an IP address


## LAST EDIT July 2022
