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
  
