#Exercises 0-5
Basic Runthrough

These exercises deal with getting C to run properly with basic makefiles and using the program 'valgrind' to assist with debugging a C program.

On my Ubuntu machine I used:
###	$ sudo apt-get install build-essential
to make sure that I had the necessary tools to make/run C programs.

My Text Editor Choices(In Order of Preference):
*Sublime Text 2 - While it is not technically free, it currently has an unlimited evaluation period, it offers an array of features while also being very pretty and user friendly
*Gedit - Default text editor for many Linux installs, simple with a decent amount of features
*Vim - Most difficult to utilize effectively, if you're up for a bit of a learning curve in your text editor it can be very effective. Based on commands rather than interfaces/menus

##Valgrind
Valgrind is a framework that analysis tools are built on, these tools can detect various bugs that go on in the program.
###Install
Follow the instructions on the site, patch the install if necessary (glibc 2.21 did not work for me otherwise).

