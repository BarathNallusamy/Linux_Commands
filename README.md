## Linux commands
- Create a Dir `mkdir name_of_folder`
- Go inside the Dir `cd name of the dir`
- Come out of the Dir `cd ..` or ``cd``
- Who am I `uname -a`
- Where am I `pwd`
- Create file `touch name_of_the_file` or `nano file_name` you land inside the file
- Exit from nano `^X` then `Y` then `enter`(Mac keyboard)
- List all `ls -a` or `ls`
- To see the content of the file on terminal `cat file_name`
- Clear your screen `clear`
- Delete folder `rm -rf name_of_the_folder`
- Delete file `rm name_of_the_file`
- Delete a file or multiple files `rm file_name second_file_name`
- Copy files or group of files or directory `cp first_file second_file`
- `man` command in linux is used to display the user manual of any command that we can run on the terminal

##### To check hidden files and directories

`ls -a`


##### What is wildcards and How to use wildcards
A wildcard in Linux is a symbol or a set of symbols that stands in for other characters. It can be used to substitute for any other character or characters in a string. For example, you can use a wildcard to get a list of all files in a directory that begin with the letter O.

Three types of wildcards are common in Linux:

? – matches a single character. For example, O??d matches anything that begins with O, ends with d and has two characters in between (like Oind, Okhd, Oerd, but not Oereed, Oad, Oerererd.)
* – matches any character or set of characters, including no character. For example, O*d matches anything that begins with O and ends with d (like Oind, Okhd, Oerd, Oereed, Oad, Oerererd, Od, Oarmeerrd). The number of characters in between O and d is not important.
Bracketed values – match characters enclosed in square brackets. For example, O[ac]d matches only Oad and Ocd. You can also specify a range of values: O[a-e]d matches Oad, Obd, Ocd, Odd and Oed.


##### How can you do process management
**An instance of a program is called a Process. In simple terms, any command that you give to your Linux machine starts a new process.**

- `Fg` - use the command "fg" to continue a program which was stopped and bring it to the foreground `fg processname`
- `Top` - This utility tells the user about all the running processes on the Linux machine.
- `PS` - This command stands for 'Process Status'. It is similar to the "Task Manager" that pop-ups in a Windows Machine when we use Cntrl+Alt+Del.
- `Kill` - This command terminates running processes on a Linux machine.
- NICE - Linux can run a lot of processes at a time, which can slow down the speed of some high priority processes and result in poor performance.
To avoid this, you can tell your machine to prioritize processes as per your requirements.This priority is called Niceness in Linux, and it has a value between -20 to 19. The lower the Niceness index, the higher would be a priority given to that task.`nice -n 'Nice value' process name`
- `DF` - This utility reports the free disk space(Hard Disk) on all the file systems.
- `Free` - This command shows the free and used memory (RAM) on the Linux system
