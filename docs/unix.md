# Unix

### BASIC UNIX COMMANDS

`cd` or `cd ~`
Change directory to HOME directory

`cd <directory name>`
Change directory (e.g. `cd pictures` brings you to the sub-directory “pictures” in your current directory, but you can teleport anywhere so long as you know the directory structure.\
Take this: `cd ~/Desktop/Images/toUpload`. That command will take me to that folder no matter where I am currently located.)

`cd ..`
Change directory up one level to the parent directory

`cd -`
Go back to the previous directory, not to be confused with parent directory.

`chmod`
Modifies the permissions on a directory\
Learn more about chmod [here](https://linuxize.com/post/chmod-command-in-linux/)

`cp <current filename> <new file name>`
Copy (e.g. cp cats1.jpg cats2.jpg makes a copy of the picture “cats1.jpg” and calls it “cats2.jpg”)

`cp -i <current filename> <new file name>`
Use `cp -i` to be prompted before over-writing another file. This is a safer method.

`ls`
Lists a directory of your files

`ls -l`
Lists a directory with more information about the files

`ls -a`
Lists a directory including the hidden files

`man`
This is the online Unix help documentation (as in “manual”). Type `man` + the command (e.g. `man ls`) for a detailed explanation of the command. Type `q` to leave the manual pages.

`mkdir <directory name>`
Creates a new directory (e.g. `mkdir pictures` creates a directory called “pictures”)

`mv <filname> <destination or filename>`
Moves a file elsewhere or renames it or both.\
- `mv text.txt /Desktop/` Moves a text file in your current directory to the Desktop.
- `mv text.txt text2.txt` Renames the file.
- `mv text.txt /Desktop/text2.txt` Does both!

`touch`
Use `touch <filename>` to create a file.

`pico` OR `nano`
Use `pico <filename>` OR `nano <filename>` to edit a text file. **This also creates the file if it does not already exist.**

`pwd`
See the current directory and path

`rm <filename>`
Remove (or delete) a file (e.g. rm cats1.jpg deletes the file “cats1.jpg”)

`rmdir <directory name>`
Removes an empty directory (e.g. rmdir pictures removes a directory called “pictures” as long as that directory is empty)

`rm -r <directory name>`
Removes a directory with contents

`df -h <path>`
On i6.cims.nyu.edu, use this command to check the amount of space you have left. For example, to check on a student’s folder or directory: `df -h /home1/x/netid` where `x` represents the first letter of your NetID and netid represents your directory on i6 and your netid (eg. “ab123”). For example, for user id “dd123”: `df -h /home1/d/dd123`.

*Note: Use the Control key + c to cancel what you’re currently doing. Use Control key + d to log out.*

**Additional Resources**

Unix Tutorial for Beginners: (link: http://www.ee.surrey.ac.uk/Teaching/Unix text: www.ee.surrey.ac.uk/Teaching/Unix)

chmod Calculator: (link: http://www.javascriptkit.com/script/script2/chmodcal.shtml text: www.javascriptkit.com/script/script2/chmodcal.shtml)
