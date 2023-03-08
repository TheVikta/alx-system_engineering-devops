Scripts and what they do

0-current_working_directory
The script prints the absolute path name of the current working directory.

1-listit
The script lists the content list of the current working directory

2-bring_me_home
The script returns the user to the $HOME directory when executed

3-listfiles
The script list the files of the current directory in a long format

4-listmorefiles
The script lists the contents including hidden system files in the long format

5-listfilesdigitonly
The script display the current directory contents in the long format, with user and group IDs displayed numerically and hidden files

6-firstdirectory
The script creates a directory named my_first_directory in the /tmp directory

7-movethatfile
The script moves a file betty in the /tmp/ directory to the /tmp/my_first_directory

8-firstdelete
The script deletes the file betty in the /tmp/my_first_directory/ 

9-firstdirdeletion
This script deletetes my_first_directory in the /tmp/ directory

10-back
The script returns the user to the previous directory from the current one

11-lists
The script lists files including hidden ones in the long format beginning with the pwd, then the parent directory and finally the /boot/ directory

12-file_type
The script displays the file type of iamafile at the root of the /tmp/ directory

13-symbolic_link
The script creates a symbolic link to /bin/ls named _ls_ in the current working directory

14-copy_html
This script copies all .html files from the current working directory to the parent directory

100-lets_move
The Script moves all files in the current directory beginning with uppercase letters to the directory /tmp/u

101-clean_emacs
The script deletes all files in the current working directory that end with the ~ character

102-tree
Script to create tree directories in the current directory

103-commas
The script list all the files and directories of the current directory, separated by commas
directory names should end with a /
Files and directories starting with a (.) should be listed
The listing should be alpha ordered except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sorrt; Digits should come first
The listing should end with a new line

school.mgc
The script is a school magic file that can be used with the command file to detect school data files. School data files always contain the string SCHOOL at offset 0
