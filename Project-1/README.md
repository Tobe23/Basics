# File Manipulation

## sudo command:

Short for superuser do, sudo is one of the most popular basic Linux commands that lets you perform tasks that requires administrative or root permissions.

Example, sudo apt update

![alt text](<Images/Screenshot 2024-04-22 082920.png>)


## pwd command
Use the pwd command to find the path of your current/present working directory. Simply entering pwd will return the full current path.

It has two acceptable options:
-L or -logical prints environment variabe content, including symbolic links.
-P or -physical prints the actual path of the current directory

![alt text](<Images/Screenshot 2024-04-24 101329.png>)


## cd command
cd command is used to navigate through files and directory. It requires the full path or the directory name.
Running this command without an option will take you to the home folder

![alt text](<Images/Screenshot 2024-04-24 110859.png>)

cd .. moves one directory up.

cd -  moves to your previous directory.

![alt text](<Images/Screenshot 2024-04-24 111915.png>)


## ls command
The ls command lists files and directories within a system. Running ls with a flag or parameter will show the current working directory's content.

![alt text](<Images/Screenshot 2024-04-28 100905.png>)

Here are some options for ls

ls -R

lists all the files in the subdirectories.

![alt text](<Images/Screenshot 2024-04-28 102723.png>)

ls -a

shows hidden files in addition to the visible ones.

![alt text](<Images/Screenshot 2024-04-28 103149.png>)

ls -lh
shows the file sizes in easily readable formats such as KB, MB, GB, and TB.git 

![alt text](<Images/Screenshot 2024-04-28 105639.png>)


## cat command

concatenate or cat command lists, combines and writes file content to the standard output. To run the cat command, type cat followed by the file name and it's extension.

![alt text](<Images/Screenshot 2024-04-28 123421.png>)

cat can also be used to merge two files 
cat filename1.txt filename2.txt > filename3.txt

![alt text](<Images/Screenshot 2024-04-28 124603.png>)


tac command
displays content in reverse order

![alt text](<Images/Screenshot 2024-04-28 125010.png>)


## cp command
cp command is for copying files or directories and their content. To copy an entire directory, pass the -R before the source directory, followed by the destibation directory.

![alt text](<Images/Screenshot 2024-04-29 103323.png>)

![alt text](<Images/Screenshot 2024-04-29 115227.png>)

To copy an entire directory, pass the -R flag (cp -R) before typing the source directory, followed by the destination directory.

![alt text](<Images/Screenshot 2024-04-30 104313.png>)

## mv command

The primary use of the mv command is to move and rename files and directory. It does not produce any output upon execution. Simply type mv followed by the filename and the destination directory.

![alt text](<Images/Screenshot 2024-04-30 111735.png>)

mv command can also be used to rename a file

![alt text](<Images/Screenshot 2024-05-01 155259.png>)

## mkdir command

Use the mkdir command to create one or multiple directories at once and set permissions for each of them.

![alt text](<Images/Screenshot 2024-05-01 160738.png>)

To create directory with full read, write and execute permissions, enter -m777

## rmdir command

rmdir command is used to permanently delete an empty directory.

![alt text](<Images/Screenshot 2024-05-01 161750.png>)

## rm command

The rm command is used to delete files within a directory. Make sure the user performing this command has the write permission.

![alt text](<Images/Screenshot 2024-05-01 163622.png>)

## touch command

touch command allows you to create an empty file or generate and modify timestamp in the linux command line.

![alt text](<Images/Screenshot 2024-05-01 164531.png>)

## df command
Use the df command to report the system's disk space shown in percentage and kilobyte(KB). 

df -h 

To the system's disk space in human readable format 

![alt text](<Images/Screenshot 2024-05-07 095412.png>)

df -m displays information on the file system usage in MBs

![alt text](<Images/Screenshot 2024-05-07 100756.png>)

df -k displays information on the file system usage in KBs

![alt text](<Images/Screenshot 2024-05-07 101131.png>)

df -T shows file system type in a new column

![alt text](<Images/Screenshot 2024-05-07 101528.png>)

## du command 

For checking how much space a file or directory takes up

![alt text](<Images/Screenshot 2024-05-07 102313.png>)

## head command

The head command allows you to view the first ten lines of a text. Adding an options lets change the number of lines shown. It can also be used to output piped data to the CLI.

![alt text](<Images/Screenshot 2024-05-08 100158.png>)

-n or -lines prints the first customized number of lines. 
Exmple -n 5 or -5

![alt text](<Images/Screenshot 2024-05-08 100356.png>)

![alt text](<Images/Screenshot 2024-05-08 100452.png>)

## tail command

The tail command displays the last ten lines of a file. It allows user check whether a file has new data or to read error messages.

![alt text](<Images/Screenshot 2024-05-08 101035.png>)

-n or -lines prints the last customised number of lines

![alt text](<Images/Screenshot 2024-05-08 101252.png>)

or

![alt text](<Images/Screenshot 2024-05-08 101614.png>)

## diff command

Short for difference, the diff command compares the contents of a file line by line.

## tar command

The tar command archives multiple files into a TAR file - a common linux fromat similar to ZIP, with optional compression


# Linux Command

A linux command is a program or utility that runs on the command line interface (CLI). Linux commands are executed on terminal by pressing enter at the end of the line. All linux commands are case-sensitive.

## chmod command

chmod is a commom command that modifies a file or directory's read, write and execute permission. In Linux, each file associated with three user classes- owner, group member, and others.

![alt text](<Images/Screenshot 2024-05-13 083904.png>)

This command supports many options, including:

-c or -changes displays information when a change is made. -f or -silent supresses error message. -v or -verboss displays a diagnostic for each processed file.

## chown command

This command let's you change the ownership of a file, directory, or symbolic link to a specific user name.

## wget command

This command lets you download file from the internet. It works in the background without hindering other running programs.

The wget command retrieves files using HTTP, HTTPS, FTP protocol. It can perform recursive download, which tranfer website parts by following the directory structures and links, creating local version of the web pages.

![alt text](<Images/Screenshot 2024-05-13 124223.png>)

## uname command

The uname or unix name command will print the detailed information about your linux system and hardware. This includes machine name, operating, and kernel.

This command has option:
-a prints all the system information. -s prints the kernel name. -n prints the system's node hostname.

![alt text](<Images/Screenshot 2024-05-13 125206.png>)

## top command
Top command displays all running processes and dynamic real-time view of the current system. It sums up the resource utilization, from CPU to memory useage. Top command can also help you identify and terminate a process that may usetoo many system resources.

![alt text](<Images/Screenshot 2024-05-13 125526.png>)


## history command

History command lets the system list upto 500 previously executed commands, allowning you to reuse them without re-entering. Omly user with sudo privileges can execute this command. How it runs depends on which linux shell you use.
This command has options:

-c clears the complete history list.

-d offset deletes the history entry at the OFFST position.

-a appends history lines

![alt text](<Images/Screenshot 2024-05-13 131442.png>)

![alt text](<Images/Screenshot 2024-05-13 131616.png>)





