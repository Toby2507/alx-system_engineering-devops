# Shell Executables

## 0-current_working_directory

This executable prints the absolute path name of the current working directory.

## 1-listit

This executable displays the contents list of your current directory.

## 2-bring_me_home

This executable changes the working directory to the user's home directory.
### *How to use* :
```bash
source ./2-bring_me_home
```

## 3-listfiles

This executable displays current directory contents in a long format.

## 4-listmorefiles

This executable displays current directory contents, including hidden files (starting with .). Use the long format.

## 5-listfilesdigitonly

This executable displays current directory contents.
- Long format
- With user and group IDs displayed numerically
- And hidden files (starting with .)

## 6-firstdirectory

This executable creates a directory named my_first_directory in the /tmp/ directory.

## 7-movethatfile

This executable moves the file betty from /tmp/ to /tmp/my_first_directory.

## 8-firstdelete

This executable deletes the betty file from /tmp/my_first_directory.

## 9-firstdirdeletion

This executable deletes the directory my_first_directory that is in the /tmp directory.

## 10-back

This executable changes the working directory to the previous one.

## 11-lists

This executable lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

## 12-file_type

This executable prints the type of file iamafile is.

## 13-symbolic_link

This executable creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

## 14-copy_html

This executable copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

## 100-lets_move

This executable moves all files beginning with an uppercase letter to the directory /tmp/u.

## 101-clean_emacs

This executable deletes all files in the current working directory that end with the character ~

## 102-tree

This executable creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

## 103-commas

This executable lists all the files and directories of the current directory, separated by commas (,).

- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line

## school.mgc

This is a magic file that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

### *How to use* :
- *First*: Complie the 'school.mgc' file using the file command with the following command:
```bash
file -C -m school.mgc
```
- *Then*: Every file that matches the criteria for school data type would return 'School data' when the file command is used.
