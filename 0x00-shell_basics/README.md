## Learning Shell Basics - **Tasks are numbered from 0 and a description of each task included** ##

### Where am I? ###
> A script that prints the absolute path name of the current working directory.

### 1. What’s in there? ###
> A script to display the contents list of the current directory.  

### 2. There is no place like home ###
> A script that changes the working directory to the user’s home directory without the use of any shell variables

### 3. The long format ###
> A script to display current directory contents in a long format

### 4. Hidden files ###
> A script to display current directory contents, including hidden files (starting with .). Using the long format.

### 5. I love numbers ###
> A script that display current directory contents, using the long Format, with user and group IDs displayed numerically, and hidden files (starting with .)

### 6. Welcome ###
> A script that creates a directory named my_first_directory in the /tmp/ directory.

### 7. Betty in my first directory ###
> A script to move the file betty from /tmp/ to /tmp/my_first_directory.

### 8. Bye bye Betty ###
> A script to delete the file betty. The file betty is in /tmp/my_first_directory

### 9. Bye bye My first directory ###
> A script to delete the directory my_first_directory that is in the /tmp directory.

### 10. Back to the future ###
> A script that changes the working directory to the previous one.

### 11. Lists ###
> A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

### 12. File type ###
> A script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

### 13. We are symbols, and inhabit symbols ###
> A script that creates a symbolic link to /bin/ls, named __ls__. in the current working directory.

### 14. Copy HTML files ###
> A script that copies all the HTML files (with dot html extension) from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

### 15. Let’s move ###
> A script that moves all files beginning with an uppercase letter to the directory /tmp/u

### 16. Clean Emacs ###
> A script that deletes all files in the current working directory that end with the character ~.

### 17. Tree ###
> A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. Using only two spaces (and lines), not more.

### 18. Life is a series of commas, not periods ###
> A script that lists all the files and directories of the current directory, separated by commas (,)
* Directory names should end with a slash (/)
* Files and directories starting with a dot (.) should be listed
* The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
* Only digits and letters are used to sort; Digits should come first
* You can assume that all the files we will test with will have at least one letter or one digit
* The listing should end with a new line
  
