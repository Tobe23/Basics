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