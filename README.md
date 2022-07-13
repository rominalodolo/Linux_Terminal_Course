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

### `expansions`

### `diff`

### `find`

### `grep` 
Stands for global regular expression print

Search in files, or combine it with pipes to filter the output of another command.

### `du`

### `df`

### `history`

### `ps`

### `top`

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

### `gzip`

### `gunzip`

### `tar`

### `nano`

### `alias`

### `xargs`

### `ln`

### `who`

### `su`

### `sudo`
Runs a command as root 
` sudo -i ` ![root](https://user-images.githubusercontent.com/83961643/178710876-53e4936e-a758-431f-9e52-dd15b4e405ef.jpeg)


### `passwd`
Users in Linux have a password assigned. You can change the password using the `passwd` command.


### `chown`
Every file/directory in an Operating System like Linux or macOS (and every UNIX system in general) has an owner.
The owner of a file can do everything with it. It can decide the fate of that file.
You can use chown to transfer the ownership to you etc.

### Ping 
The ping command pings a specific network host, on the local network or on the Internet
`ping <host>` <host> could be a domain name, or an IP address


## LAST EDIT July 2022
