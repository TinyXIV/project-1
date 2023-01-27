# UOCIS322 - Project 1 #

#Joshua Muzi
#jmuzi@uoregon.edu

#This project uses the files in pageserver, in order to configurate and grab information from credentials.ini 
#or default.ini to be imported in pageserver.py that uses the webpage file input in order to check the file pages for 
#the existing files then excuting error messages if not found or running the file if found

#You start the webserver with the following commands
#cd project-1
#lsof -i:5003
#make start

#You then can curl or go directly to the webpage to input an existing or non existing file that will output
#correct errors if not found, forbidden, or found

## Grading Rubric

* If everything works as expected, 100 will be assigned.
* If existing pages and files are NOT handled correctly, 30 points will be docked.
* For each of the errors not handled correctly (403, and 404), 15 points will be docked.
* If `README.md` is not updated with your name and info, 10 points will be docked.
* If `credentials.ini` is commited, 10 points will be docked.
* If the repo clones, but `make install` or `make run` throws an error, 10 will be assigned.
* If `credentials.ini` is incorrect or not submitted, 0 will be assigned.

## Authors

Michal Young, Ram Durairajan.