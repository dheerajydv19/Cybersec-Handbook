# Basic Linux Commands Cheatsheet

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
 
 7. rm -
  - used to delete a file or folder
  - To delete a single file, use the following command: rm file.txt
  - To delete multiple files at once, use the following command: rm file1.txt file2.txt file3.txt
  - To delete all files in a directory, you can use the rm command with the * wildcard. For example, rm * will delete all files in the current directory.
  - To delete a directory and all of its contents, you can use the rm command with the -r flag. This will delete the directory and all files and subdirectories inside it. For example, rm -r my_directory

 # Editing Files in Linux with vim
 
- $ sudo vim filename
 
 (This will open the file within the current directory, if their is no file with that name, it will create itself with that name and open it.)
- $ sudo chown username filename
 
 (Here put the username of that account you are using in linux and you will get ownership of the respective file named filename.)
 
- Note - In order to enter the Insert mode in Vim, you simply type the letter “a.” Once you do that, you will be able to edit and start typing your modifications on the file.
When you are done making your modifications to the file, what you do to get out of the Insert mode is hit the ESC key on your keyboard.

 For using the below commands, you need to be out of insert mode.
 - :/ "word" - This will look for the word inside the file that is opened in vim. (This will only search below from wherever your mouse coursor is)
 - :/? "word " - This will search from below to above
 - n for navigating from the reults of above two commands.
 
 - To open a new file in Vim, use the :e <filename> command.
 - To exit Vim without saving your changes, use the :q command.
 - To force quit Vim, use the :q! command.
 - To save and quit Vim, use the :wq command.
- To save your changes to a new file, use the :w <new filename> command.
Note - Remember to always press ENTER after typing in a command to execute it in Vim. Also, be sure to always be in Normal mode when entering commands, as Vim will not interpret commands entered in Insert mode as commands.
 
 - $ sudo find -iname file/folder_name - Used to search for files and folders
 

 
 
 
 
 
 
 ## Contributions

Contributions are always welcome!

You can contact me any time on any of my social media platforms for any kind of suggestions and Contributions.
https://linktr.ee/dheerajydv19
 
Developed with ❤️ in India 🇮🇳 
