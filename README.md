# rshell
School project to build a linux shell in c++ that I built with Noah Marestaing
we added piping, input redirection, and output redirection functionality.
### List of bugs
* can't take in echo arguments that come after connectors
* can't read in commands that come right after semicolons (ie date;ls will be 
* read as only command attempt)
* can't read in exit when it is linked with other commands
* doesnt accept parentheses with redirect
### Need to fix
* composite.cpp need to be cleaned up
