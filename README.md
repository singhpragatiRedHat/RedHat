# Linux System Admin Command

# Basic Linux commands   Command and Description


<li> ls	                                                              =>>  Lists all files and directories in the present working directory
<li> ls-R	                                                          =>>  Lists files in sub-directories as well
<li> ls-a	                                                          =>>  Lists hidden files as well
<li> ls-al	                                                          =>>  Lists files and directories with detailed information like permissions,size, owner, etc.
<li> cd or cd ~	                                                      =>>  Navigate to HOME directory
<li> cd ..	                                                          =>>  Move one level up
<li> cd	                                                              =>>  To change to a particular directory
<li> cd /	                                                          =>>  Move to the root directory
<li> cat > filename	                                                  =>>  Creates a new file
<li> cat filename	                                                  =>>  Displays the file content
<li> cat file1 file2 > file3	                                      =>>      Joins two files (file1, file2) and stores the output in a new file (file3)
<li> mv file "new file path"	                                      =>>      Moves the files to the new location
<li> mv filename new_file_name                                        =>>   Renames the file to a new filename
<li> sudo	                                                          =>>  Allows regular users to run programs with the security privileges of the superuser or root
<li> rm                                                               =>>   filename	Deletes a file
<li> man	                                                          =>>      Gives help information on a command
<li> history	                                                      =>>      Gives a list of all past commands typed in the current terminal session
<li> clear	                                                          =>>  Clears the terminal
<li> mkdir directoryname	                                          =>>      Creates a new directory in the present working directory or a at the specified path
<li> rmdir	                                                          =>>  Deletes a directory
<li> mv	                                                              =>>  Renames a directory
<li> pr -x	                                                          =>>  Divides the file into x columns
<li> pr -h	                                                          =>>  Assigns a header to the file
<li> pr -n	                                                          =>>  Denotes the file with Line Numbers
<li> lp -nc , lpr c	Prints "c"                                        =>>  copies of the File
<li>  lp-d lp-P 	                                                  =>>       Specifies name of the printer
<li> apt-get 	                                                           =>>   Command used to install and update packages
<li> mail -s 'subject' -c 'cc-address'   -b 'bcc-address' 'to-address'     =>>   	Command to send email
<li> mail -s "Subject" to-address < Filename 	                         =>>    Command to send email with attachment


	
	
# Commands and its function Function


<li>man  			=>	Display information about all commands
<li>uptime			=>	Show how long system is running
<li>users			=>	Show username who are currently logged in
<li>service			=>	Call and execute script
<li>pkill			=>	Kill a process
<li>pmap			=>	Memory map of a process
<li>wget			=>	Download file from network
<li>ftp or sftp	    =>    Connect remote ftp host
<li>free	        =>    Show memory status
<li>top	            =>    Display processor activity of system
<li>last	        =>    Display user's activity in the system
<li>ps	            =>   Display about processes running on the system
<li>Shutdown        =>   commands	Shutdown and reboot system
<li>info	        =>  	Display information about given command
<li>env				=>	Display environment variable for currently logged-in user
<li>netstat			=>	Display network status
<li>arp				=>	Check ethernet connectivity and IP address
<li>df				=>	Display filesystem information
<li>du				=>	Display usage
<li>init			=>	Allow to change server bootup
<li>nano			=>	A command line editor
<li>nslookup		=>	Check domain name and IP information
<li>shred			=>	Delete a file by over writing its content
<li>cat				=>	Display, copy or combine text files
<li>pwd>			=>	Print path of current working directory
<li>locate			=>	Finding files by name on system
<li>chown			=>	Change ownership of a file
<li>>alias			=>	To short a command
<li>echo			=>	Display text
<li>cmp				=>	Compare two files byte by byte
<li>mount			=>	Mount a filesystem
<li>ifconfig        =>    Display configuration
<li>traceroute>	    =>   Trace existing network
<li>sudo			=>	Run a command as a root user
<li>route			=>	List routing table for your server
<li>ping			=>	Check connection by sending packet test packet
<li>find			=>	Find location of files/directories
<li>users			=>	Show current logged in user
<li>who				=>	Same as w but doesn't show current process
<li>ls				=>	List all the files
<li>tar				=>	Compress directories
<li>grep			=>		Search for a string in a file
<li>su				=>			Switch from one to another user
<li>awk				=>		Search lines for a given pattern
 </li> 
  
#  File Permission commands and  Command	Description


<li> ls-l	    =>> to show file type and access permission
<li> r	        =>> read permission
<li> w	        =>> write permission
<li> x	        =>> execute permission
<li> -=	        =>> no permission
<li> Chown user	=>> For changing the ownership of a file/directory
<li> Chown user =>>  group filename	change the user as well as group for a file or directory

</li>
 

# User management commands of linux and Command	Description


<li>sudo adduser username	              =>>  To display value of a variable
<li>sudo passwd -l 'username'	          =>>  Displays all environment variables
<li>sudo userdel -r 'username'	          =>>  Create a new variable
<li>sudo usermod -a -G GROUPNAME USERNAME =>>  Remove a variable
<li>sudo deluser USER GROUPNAME	          =>>  To set value of an environment variable
<li>finger	                              =>>  Gives information on all logged in user
<li>finger username	                      =>>  Gives information of a particular user
										  
</li>

# Networking command  and Command	Description



<li> SSH username@ip-address or hostname	=>>     login into a remote Linux machine using SSH
<li> Ping hostname="" or =""	            =>>     To ping and Analyzing network and host connections
<li> dir	                                =>>     Display files in the current directory of a remote computer
<li> cd "dirname"	                    =>>     change directory to "dirname" on a remote computer
<li> put file	                        =>>     upload 'file' from local to remote computer
<li> get file	                        =>>     Download 'file' from remote to local computer
<li> quit	                            =>>     Logout

  </li>
# Process command and Command	Description


<li> bg	      =>>    To send a process to the background
<li> fg	      =>>    To run a stopped process in the foreground
<li> top	  =>>    Details on all Active Processes
<li> ps	      =>>    Give the status of processes running for a user
<li> ps PID	  =>>    Gives the status of a particular process
<li> pidof	  =>>    Gives the Process ID (PID) of a process
<li> kill PID =>>    Kills a process
<li> nice	  =>>    Starts a process with a given priority
<li> renice	  =>>    Changes priority of an already running process
<li> df	      =>>    Gives free hard disk space on your system
<li> free	  =>>    Gives free RAM on your system

</li>

# VI Editing Commands and Command	Description


<li> i	=>> Insert at cursor (goes into insert mode)
<li> a	=>> Write after cursor (goes into insert mode)
<li> A	=>> Write at the end of line (goes into insert mode)
<li> ESC	=>> Terminate insert mode
<li> u	=>> Undo last change
<li> U	=>> Undo all changes to the entire line
<li> o	=>> Open a new line (goes into insert mode)
<li> dd	=>> Delete line
<li> 3dd	=>> Delete 3 lines
<li> D	=>> Delete contents of line after the cursor
<li> C	=>> Delete contents of a line after the cursor and insert new text. Press ESC key to end insertion.
<li> dw	=>> Delete word
<li> 4dw	=>> Delete 4 words
<li> cw	=>> Change word
<li> x	=>> Delete character at the cursor
<li> r	=>> Replace character
<li> R	=>> Overwrite characters from cursor onward
<li> s	=>> Substitute one character under cursor continue to insert
<li> S	=>> Substitute entire line and begin to insert at the beginning of the line
<li> ~	=>> Change case of individual character


