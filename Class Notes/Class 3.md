## Linux User Management
	There are 3 types of Users :-
			1 Root User : has full control over the System.
				-> can install/remove software
				-> Modify System files
				-> Add/Remove Users
			2 Regular User : Normal Accounts for daily use.
			3 System User : Used by services , don't log in interactively
	### Creating, Deleting, Managing Users
		add User: sudo useradd -m -s username
		set password: sudo passwd username
		Delete user: sudo userdel -r username
		Modify User: sudo usermod -aG groupname username
	Accessing Root User
	Switch to root : su -
	or : sudo command
## Package Manager
	There are a lot of package managers for Linux :
	**For Kali Linux  :even any other Debian, use APT

## CLI Symbols
	| (pipes) : to transfer the output of one command to another
	|| (OR) : it is used like this cmd1 || cmd2 , and cmd2 only runs if cm1 fails
	&& (AND) : it is used like this cmd1 || cmd2 , and cmd2 only runs if cm1 succeds
	> (Overwrite redirection) : 
	>> (Append Redirection) : 
## Shells
	Types of Shells:
		1. Bash
		2. Zsh
		3. sh
		4. Fish
### Script Installation
	1. First lets create a shell script file : nano backup.sh
	2. Second we write this command in it for the shell script
![[Pasted image 20260321041511.png]]
    3. then save and Exit
    4. then we change the permission of the file using chmod like : chomd +x backup.sh
    5. then we run ./backup.sh to run the script and it copies all the files in documents to BACKUP DIRECTORY

### Software Installation
	sudo apt update 
	sudo apt upgrade
	then to install a specific software from apt repo 
	sudo apt install specific-software
	



    
