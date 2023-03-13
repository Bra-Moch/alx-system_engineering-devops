# 0x02-shell_redirections
This directory contains shell scripts related to shell redirections. Below is a description of the scripts and their purposes.

## 0-hello_world
This script prints "Hello, World" to the standard output.

##The 1-confused_smiley
This script is a simple Bash script that displays a confused smiley "(Ôo)' to the console.

##2 Display a file
the script cat /etc/passwd command will display the contents of the /etc/passwd file.

##3 Display 2 file
This script uses the cat command to display the contents of both files, separated by a newline character.

##4 Display last 10 lines of a file
This script uses tail command to display the last 10 lines of the file.

##5 Display first 10 lines of a file
This script uses head command to display the first 10 lines of the file.

##8 Saving current state of directory
The ls -la command is run, which lists the files and directories in the current working directory, including hidden files and directories, in long format. The > operator is used to redirect the output of the ls -la command to the file ls_cwd_content. If the file already exists, it will be overwritten. If it does not exist, it will be created.

## 10 No more Javascript
The find command is used to search for files in the current directory and its subdirectories. The -type f option specifies that we only want to find regular files (not directories or other types of files). The -name "*.js" option specifies that we want to find files with a .js extension. Finally, the -delete option deletes the files that match the search criteria.

## 11 Don't just count your directories, make your directories count
The find command is used to search for directories in the current directory and its subdirectories. The -mindepth 1 option specifies that we want to exclude the current directory from the search, and the -type d option specifies that we only want to find directories. The wc -l command counts the number of lines (which corresponds to the number of directories found by find).
