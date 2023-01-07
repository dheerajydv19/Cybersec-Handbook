# Basic Linux Commands 

1. Sudo - 

- Means super user do
-  temporarily gives a user administrative access (temporarily gives root access)
-  Similar to "Run as Administator" in Windows

2. Man Pages -

- Means Manual pages 
- used to lookup information about any linux command 
- ex - $ man ping
- press "Q" for exit

3. Tasksel

- means Task Select
- provides hassle-free installation of packages
- $ sudo tasksel (then just select which packages you want to install on your server)

4. Apt-get

- used to insall individual programs
- $ sudo apt-get install <name of program>
- $ sudo apt-get install Apache2 (this will install apache2 server programs in your server)
- $ sudo apt-get remove Apache2 (this will uninstall apache2 server programs from your server)
- $ sudo apt-get upgrade (this will display if update of any installed program is availiable or not.)

5. Services
 - $ sudo /etc/init.d/<name of the program or service> start
 - $ sudo /etc/init.d/<name of the program or service > stop
 - $ sudo /etc/init.d/<name of the program or service > restart
 - ex - $ sudo /etc/init.d/Apache2 restart (This would restart apache2 service while everything else will keep running)
  
6. Top 
 - This will list all the running processes with details about the cpu and memory being consumed.
 - Similar to task manager in windows
 - $ sudo top
 - $ K <PID>  (This will kill that particular process with given PID)
 
 ## Basic Linux Navigation 
 
 1. cd -
 - means change directory
 - cd foler_name (here folder_name refers to the folder in which you want to navigate, you can also enter complete folder path)
 - cd / (this command will enter you to the root folder)
 - ex - $ cd /etc/var/abc (this will get you inside folder abc)
 2. ls - 
 - shows full list of all files and folders
 - $ ls (this will display all the files and folders inside the current directory)
 - use the -l flag to show the files and directories in a long format  
 
 3. pwd -
  - means print working directory 
  - useful if you want to know the absolute path of the directory you are currently in.
  - $ pwd
 
 4.  mkdir -
  - used to create a new directory
  - $ mkdir new_directory (This will create a new directory called new_directory in the current working directory.)
 
 5. cp - 
  - used to copy a file or directory
  - $ cp file.txt new_file.txt (This will create a copy of file.txt called new_file.txt)
 
 6. mv -
  - used to move a file or directory
  - $ mv file.txt new_location/file.txt (This will move file.txt to the new_location directory.
  - $ mv file.txt new_name.txt (This will rename file.txt to new_name.txt.)
 
 
