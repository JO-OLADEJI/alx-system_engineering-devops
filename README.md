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
