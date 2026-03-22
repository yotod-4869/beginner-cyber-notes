## Linux Basics Tutorial 
**Command line interface**:is a way of communicating with the System (OS) via a terminal and shell.
### Command line Syntax with Usage
	pwd : Present Working Directory
	ls : list files in the pwd , has multiple flags to interact with it  
		-l : long
		-a : to show all files
		-s : to show size
		-S : to sort the files by file size
	cd : change directory
	man : manual for commands
	mkdir : to make a new directory
		-p : to create a directory recursively in a direcotry as a parent directory
	clear : to clear the terminal
	touch : to create files in a directory
	mv : move a file to another directory
		-f : by using force , as in forced move
	cat : concatenate file content to stdout
		-n : to indicate the number of lines to show
		-E : to show the end of lines
	echo : to transfer the output to stdout
	cp : to copy a file in to another directory 
		--copy-contents : to copy the contens of a file like with the same name
			eg. cp ../Downloads/txt.txt . --copy-contents
				when there already exists a file named txt.txt in the pwd
	history : to show previously used tools on the terminal
	rm : to remove a file
		-r : recursively deletes directory contnets 
	rmdir : to remove a directory
	chown : to change the ownership of the file
		-R : to recursively apply the change
		-v : verbose
	chmod : to change the permission of a file, adding and removing permissions 
### Basic service and systems
	Permission and Privileges : 
		drwxr-xr-x  4 barok barok 4096 Mar 15 03:36  .
		to show what permission the owner:group:other  then ownership of the file to what user and group
	Example : chmod +744 ./txt.txt -> this means the user can rwx, the group can only read and the other can only read

### Basic File System structure
	/bin : essential command binaries
	/boot : System boot loader files
	/dev : Device files
	/etc : Host-specific System-wide configuration files
	/home : User home directory
	/lib : Shared library modules
	/media : Media file such as CD-ROM
	/mnt : Temproray Mounted filesystems
	/opt : Add-on application software packages
	/proc : Interface to Kernel Data structures
	/root : Home directory for root user
	/sbin : System binaries
	/srv : Site-specific data served by this system
	/sys : virtual directory providing information about the system
	/tmp : Temprorary files
	/usr : Unix System Resources
	/var : Directory were variable directories are stored , like log files , bash history and stuff like that 


## Challenge for Linux basics
**Links Used:**








