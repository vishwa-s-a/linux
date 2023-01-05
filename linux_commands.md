## linux commands
* ls -l
* ls -al
>here 'a' mainly refers to get the hidden stuff
* cd..
>takes us one directory back
4. cd
>takes us to home
* touch demo.txt
>easiest way to create a file
* touch -d tomorrow demo1.txt
> this creates a file in which the date of creation will be as specified
* touch -d 11/29/2022 demo1.txt
> here this file's date of creation will be 29th november 2022
* nano demo.txt
> to edit the file as a linux pro user, here use ctrl+x and press y to save the file.
* cat demo.txt
> quickly have a look of what is there inside the file
* shred demo.txt
> here this commands shreds the file and others cannot come to know what was there in file
* mkdir java
> to make a new directory called java
* cp demo.txt /home/Downloads/.../demo.txt
> cp refers to copy a file and paste it in specified location
> here instead of cp if we use mv then it moves the file
* rm demo.txt
> deletes the file
* rmdir java
> removes the directory
* sudo adduser ram
* sudo useradd bheem
> these commands are used for adding users to the system
* su ram
> su refers to switch user 
* users
> gives the list of users
* exit
> this is used to exit from any user
* sudo passwd ram
> this command changes the password of ram
* passwd
> this command changes the password of present
* man 
> command is used for knowing what is the use of other commands. example man cat,man touch
* whatis
> can be used to get the info of a certain application, like example whatis neofetch
* whereis
> to get the location of a certain application, like example whereis neofetch
* which
> same to get the location of a certain application, like which neofetch
* wget
> can be used to get the data from internet
* zip
> example zip demo.zip demo1.pdf demo2.pdf. it zips all the specified files to destined file.zip
* unzip demo.zip
> unzips the file
* sudo dnf localinstall sample_file.rpm
> to install .rpm file downloaded from other source
* less demo.pdf
> displays the pdf page by page
* head demo.pdf
> displays the begining part of the pdf
* tail demo.pdf
> displays the end of the pdf
* cmp demo1.java demo2.java
> compares both the files and says whether both are same or not
* diff demo1.java demo2.java
> shows what is the exact difference between files including lines
* cal
> shows up calender
* free
> shows the ram status
* ps 
> shows all processes currently running on pc
* ps -aux
> shows it much more than ps
* top
> also does the same work
* htop
> also works in more fun way
* history
> shows all the commands run on the terminal
* bash
> to activate the conda and anaconda-navigator
* anaconda-navigator
> to open the navigator after bash command
* conda config --set auto_activate_base false
> to remove base from left corner of the terminal path