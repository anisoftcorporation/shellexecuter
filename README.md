
shellexecuter
=============

This PHP script will help executing shell scripts in background. It also takes arguments if any required by the shell sript from the index.php.

This one will have a sample .sh file which creates a directory based on the name provided in index.php.

Before testing the script please make sure that 

1. The .sh file has executing permision by the apache user
2. Also the target folder where to create folder should have permision to write by the apache user.
3. Make sure to change the path to the .sh file in script.php and place the .sh file in that directory
