-The 0-current_working_directory file contains a script that prints the absolute path name of the current working directory.
-The 1-listit file contains a script that prints the contents of your current directory.
-The 2-bring_me_home file contains a script that changes the working directory to the user’s home directory.
-The 3-listfiles file contains a script that displays current directory contents in a long format.
-The 4-listmorefiles file contains a script that displays current directory contents, including hidden files.
-The 5-listfilesdigitonly file contains a script that display current directory contents.
-The 6-firstdirectory file contains a script that creates a directory named my_first_directory in the /tmp/ directory.
-The 7-movethatfile file contains a script that moves the file betty from /tmp/ to /tmp/my_first_directory.
-The 8-firstdelete file contains a script that deletes the file betty
-The 9-firstdirdeletion file contains a script that deletes the directory my_first_directory that is in the /tmp directory.
-The 10-back file contains a script that changes the working directory to the previous one.
-The 11-lists file contains a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
-The 12-file_type file contains a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
-The 13-symbolic_link contains a script that creates a symbolic link  to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
-The 14-copy_html file contains a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
-The 100-lets_move file contains a script that  moves all files beginning with an uppercase letter to the directory /tmp/u.
-The 101-clean_emacs file contains a script that deletes all files in the current working directory that end with the character ~.
-The 102-tree file contains a script that  creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
-The 103-commas file contains a script that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line.
-The school.mgc file contains a script that  that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. (school.mgc is a magic file)
