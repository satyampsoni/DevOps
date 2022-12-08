# Linux
- Linux is an open source computer operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc.
- It is a UNIX like operating system (command line interface) and GUI too.
- It was developed by Linus Torvalds who was a student in Helsinki, Finland, in 1991.
- Linux is an operating system that is "for the people, by the people."

# Linux Commands
- All these commands are typed in the terminal of the Linux Distributions.
- shortcut for linux terminal is `CTRL + ALT + T`

## list commands
- `ls` - list directory contents
- `ls -a` - list the hidden contents (name starting with .)
- `ls -l` - show the permissions 
- `ls -R` - shows subdirectory

Note: There are a lot of ls commands you can view them `man ls` command in your directory.

## File and Directory commands
- `pwd`- Current working directory
- `mkdir directory` - create directory
- `rm file` - deletes the file
- `rm -r directory`- Remove the directory and its contents recursively
- `rm -f file`-  Force removal without confirmation
- `rm rf` - Forcefully remove directory recursively
- `cp file1 file2`- copy file1 to file2
-`cp -r source_directory destination`- Copy source directory recursively to the destination
- `mv file1 file2` - Rename or move file1 to file2. If file2 present move if not rename.
- `touch` - creates a file
- `cat file` - see the contents inside the file
- `cat > <filename>`- creates a new file
- `cat>> <filename>` - Append the line
- `cat <filename1> <filename2>` - Display two files at a time
- `cat <filename1> <filename2> <newfilename>` - Merge both files into new file
- `cat <filename1> | tr > <new-filename>` - Translate the file
- `head file` - Used to view first 10 lines inside the file
- `tail file` - Used to view last 10 lines inside the file.
- `echo "HEllo Linux"` - Prints the contents
- `find <file/foldername>` - Finds the file and folder name
- `find <dir-name>` - find files inside the dir
- `find .-type d` - Show only dir.
       `.-type f` -Sshow only files.
        `.-type f -name "*.txt"` - Show only files with that specfic name.
        `.-type f -iname "*.txt"` - Show only files with that specfic name - not case sentive (i)
        `.-type f -mmin -20` - Show files which modify less than 20 min ago.
        `.-type f -mmin +20 `- show files which modify more than 20 min ago.
        `.-type f -maxdepth 2` - Will only show 1 folder deep.
        `.-size +1k` - will only show file/folder with size of 1kb


Note: You can see what a command does by typing `man <commandname>` right inside the terminal, commandname can be any command.

## Directory Navigation
 - `cd <folder-name>` - Change Dir.
 - `cd ..` - Go one Directory back.
 - `cd` - Go to home.
 - `cd ../<foldername>` - Open a previous dir folder.
 - `cd <path>` - Open a dir with the path.
 
 ## Networking
 - `ip a` - Display all network interfaces and IP address
 - `ip addr show dev eth0` - display eth0 address and details.
 - `Ping host` - Send ICMP echo request to host.
 - `whoisdomain` - Display who is information for domain
 - `nslookup`- query internet name servers (comes in interactive and non-interactive mode).
 - `hostname`-  show or set the system hostname
 - `domainname` - show or set the system domain name
 - `whoami` - Print the name of the effective user
 - `ping <domain name>` - Test to see if network device is availaible or not

## Permissions
- `chmod u=rwx,g=rxw,o=rwx <file-name>` READ WRITE AND EXECUTE PERMISSIONS
- `chmod 777 <file-name>` - 4: Read, 2: write, 1: execute
- `grep <keyword> <file-name>` To check if the certain keyword is present in filename or not

## User information and Management
- `id` : displays the user and the current user id
- `last` : display the last user who have logged into your system
- `who` : show who is logged into your system
- `w` : who is logged in and what they are doing
- `userdel <username>`: Delete the name of the user

 
 
 




