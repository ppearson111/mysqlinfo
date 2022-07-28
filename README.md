# mysqlinfo
A command-line tool to get information about your MySQL configuration files and where they are located

Save the script to a folder within your current PATH. Then be sure to update file priveledges so that it
can execute: > sudo chmod a+x ./mysqlinfo

Then, just run the command: > mysqlinfo

Output shoud look something like this:

+=================================+
| MySQL Configuration information |
+=================================+
Default options are read from the following files in the given order:
/etc/my.cnf /etc/mysql/my.cnf /opt/homebrew/etc/my.cnf ~/.my.cnf

Possible configuration files:
File 0:              /etc/my.cnf <-- File exists
File 1:        /etc/mysql/my.cnf <-- Does NOT exist
File 2: /opt/homebrew/etc/my.cnf <-- File exists
File 3:                ~/.my.cnf <-- Does NOT exist
