# ALx System Engineering Devops
This repository contains basic automated scripts for bash/terminal.

<br />

### 0x00: Shell Basics
- Print the absolute path of your current working directory.
- Display the contents list of your current directory.
- Change the working directory to user's home directory.
- Display current directory contents in a long format.
- Display current directory contents, including hidden files in long format.
- Display current directory contents:
	- in long format
	- with user and group IDs displayed numerically
	- including hidden files (starting with .)
- Create a directory named `my_first_directory` in the `/tmp/` directory.
- Move file `betty` from `/tmp/` to `/tmp/my_first_directory`.
- Delete the file `betty` from `/tmp/my_first_directory/`.
- Delete the directory `my_first_directory` in the `/tmp` directory.
- Change the working directory to the previous one.
- List all files in 3 directories in specified order.
- Print the type of the file named `iamafile`.
- Create a symbolic link to `/bin/ls` named `__ls__` in the current working directory.
- Copy all HTML files from working directory to it's parent.

<br />

### 0x01: Shell Permissions
- Switch the current user to the user `betty`.
- Print the effective username of the current user.
- Print the groups the current user is part of.
- Change the owner of the file `hello` to the user `betty`.
- Create an empty file called `hello`.
- Add execute permission - `-rwxrw-r--` - to the owner of the file `hello`.
- Add execute permission to the owner and the group owner, read permissions to the other users to the file `hello`.
- Add execute permission to the owner, the group owner and the other users, to the file `hello`.
- Set the permission to the file `hello` as follows:
	- Owner: no permission at all
	- Group: no permission at all
	- Other users: all the permissions
- Set the mode of the file `hello` to this: - `-rwxr-x-wx`.
- Set the mode of the file `hello` the same as `olleh`'s mode.
- Add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
- Create a directory called `my_dir` with permissions 751 in the working directory.
- Change the group owner to `school` for the file `hello`.

<br />

### 0x02: Shell Redirections
- Print "Hello, World" followed by a new line to the standard output.
- Display a confused smiley `"(Ôo)'`.
- Display the content of the `/etc/passwd` file.
- Display the content of `/etc/passwd` and `/etc/hosts`.
- Display the last 10 lines of `/etc/passwd`.
- Display the third line of the file `iacta`.
- Create a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.
- Write into the file `ls_cwd_content` the result of the command `ls -la`.
- Write a script that duplicates the last line of the file `iacta`.
- Write a script that deletes all the regular files with  `.js` extension that are present in the currend directory and all its subfolders.
- Write a script that counts the number of directories and sub-directories in the current directory.
- Display the 10 newest files in the current directory.
- Create a script that takes a list of words as input and prints only words that appear exactly once.
- Display lines containing the pattern `"root"` from the file `/etc/passwd`.
- Display the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`.
- Display lines containing the pattern `"root"` and 3 lines after them in the file `/etc/passwd`.
- Display all the lines in the file `/etc/passwd` that do not contain the pattern `"bin"`.
- Display all lines of the file `/etc/ssh/sshd_config` starting with a letter.
- Replace all characters `A` and `c` from input to `Z` and `e` respectively.
- Remove all letters `c` and `C` from input.
- Reverse the input.
- Display all users and their home directories, sorted by users (Based on the `/etc/passwd` file).

<br />

### 0x03: Shell Variables Expansions
- Create an alias `ls` for the command `rm *`.
- Print `hello user`, where user is the current Linux user.
- Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.
- Count the number of directories in the `PATH`.
- List environment variables.
- List all local variables, environment variables and functions.
- Create a new local variable `BEST` with a value of `School`.
- Create a new global variable `BEST` with a value of `School`.
- Print the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`.
- Print the result of `POWER` divided by `DIVIDE`, followed by a new line.
- Display the result of `BREATH` to the power `LOVE`.
- Convert a number from base 2 to base 10. The number in base 2 is stored in the environment variable `BINARY`.
- Print all possible combinations of two letters, except `oo`.
- Print a number with 2 decimal places. The number will be stored in the environment variable `NUM`.
