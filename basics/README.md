0-current working directory
1-listit  Displays the contents list of the current directory. | `ls` |
2-bring_me_home` | Changes the working directory to the user's home directory without variables. | `cd` |
3-listfiles` | Displays current directory contents in long format. | `ls -l` |
4-listmorefiles` | Displays current directory contents, including hidden files, in long format. | `ls -la` |
5-listfilesdigitonly` | Displays directory contents in long format with numeric user and group IDs, including hidden files. | `ls -lan` |
6-firstdirectory` | Creates a directory named `my_first_directory` inside the `/tmp/` directory. | `mkdir` |
7-movethatfile` | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`. | `mv` |
8-firstdelete` | Deletes the file `betty` located in `/tmp/my_first_directory`. | `rm` |
9-firstdirdeletion` | Deletes the directory `my_first_directory` from the `/tmp/` directory. | `rmdir` |
10-back` | Changes the working directory to the previous working directory. | `cd -` |
11-lists` | Lists all files (including hidden) in the current directory, parent directory, and `/boot` directory in long format. | `ls -la . .. /boot` |
12-file_type` | Prints the file type of a file named `iamafile` located in `/tmp/`. | `file` |
13-symbolic_link` | Creates a symbolic link named `__ls__` pointing to `/bin/ls` in the current directory. | `ln -s` |
14-copy_html` | Copies new or updated HTML files from the current directory to its parent directory. | `cp -u` |
15-lets_move` | Moves all files starting with an uppercase letter to the directory `/tmp/u`. | `mv [A-Z]*` |
16-clean_emacs` | Deletes all files in the current working directory that end with the `~` character. | `rm *~` |
17-tree | Creates a nested directory structure 
