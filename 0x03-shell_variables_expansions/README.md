printenv- this command displays the value of environment variables in the current shell
		- we can specify one or more varible names on the command line to  print only those specific varibles
		- or we can run the command without arguments. it will display all environment varibles

set		- this command displays and sets the names and values of shell and linux environments varibles.

unset	- this command is used to delete the varibles durring program execution. It can remove functions 
		  and shell varibles.

export  - this command ensures the environment varible and functions to be passed to child processes. it does not
		  affect the existing environment varible. Envrionment varibles are set when we open a new shell session.

allias	- this command is a shortcut that reffrences a comand. An alials replaces a string that invokes a command
		  in the linux shell with another user-defined string. Mostly used to replace long commands improves 
		  effeciency and avoiding spelling errors.

unallias-  this command removes each name or string from the list of user-defined alliases.

source  - this command reads and execute the file content in the current shell. These files usually contains a list
		  of commands delivered to the TCL interpreter to be read and run.

printf  - this command prints a formated string to the starndard output. Its roots are in the C program.. language
		  whinch  uses a dunction by the same name. Its a handy way to produce precisely-formatted output from 
		  numerical or textual arguments.
