# Shell Scripting
Shell scripting helps to automate repetitive task. Bash scripts are essentially a series of commands and instructions that are executed sequentially in a shell. You can create a shell by saving a collection of commands in a text file with a .sh extension. These scripts can be executed directly from the command line or called from other scripts.

## Shell Scripting Syntax Elements
1. Variables: Bash allows you to define and work with variable. Variables can store data of various types such as the variable name preceded by a $ sign.

![alt text](<Images/Screenshot 2024-06-12 143008.png>)

2. Control Flow: Bash provides control of flow statement like if-else, while loops, and case statements to execute different commands based on conditions.

![alt text](<Images/Screenshot 2024-06-12 145905.png>)

![alt text](<Images/Screenshot 2024-06-12 144752.png>)

Since 1.script is not executable, it has be made executable using chmod +x

![alt text](<Images/Screenshot 2024-06-12 145302.png>)

1.script can now be executed using ./

![alt text](<Images/Screenshot 2024-06-12 151740.png>)

![alt text](<Images/Screenshot 2024-06-12 152139.png>)

### Iterating through a list using a for loop
Script to pring from 1 to 5using a for loop
![alt text](<Images/Screenshot 2024-06-12 152701.png>)

![alt text](<Images/Screenshot 2024-06-12 152927.png>)

### Using backtick for command substitution
![alt text](<Images/Screenshot 2024-06-12 152927.png>)

4. Input and Output: Bash provides various ways to handle input and output. You can use the read command to accept user input, and output text to the console using the echo command. Additionally, you can redirect input and output using operators like > (output to a file), < (input from a file), and | (pipe the output of one command as input to another)

### File Oeration and Sorting
This script creates three files (file1.txt, file2.txt, file3.txt), displays them in their current order, sorts the alphabetically, saves the sorted files in sorted_files.txt, displays the sorted files, removes the original files, renames the soretd files to sorted_files_sorted_alphabetically.txt, and finally displays the contented of the final sorted file.

![alt text](<Images/Screenshot 2024-06-14 053059.png>)

![alt text](<Images/Screenshot 2024-06-14 053238.png>)

![alt text](<Images/Screenshot 2024-06-14 053405.png>)

### Working with numbers and Calculations

This script defines two variables num1 and num2 with numeric values, performs basic arithmetic operation (addition, subtraction, multiplication, division, and modulus), and displays the results. It also performs more complex calculations such as raising num1 to the power of 2 and calculating the square root of num2 and displays those results as well.

![alt text](<Images/Screenshot 2024-06-14 062610.png>)

![alt text](<Images/Screenshot 2024-06-14 062957.png>)

![alt text](<Images/Screenshot 2024-06-14 063146.png>)
