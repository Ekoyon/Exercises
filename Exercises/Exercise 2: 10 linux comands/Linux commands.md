* locate:
The locate command is used to locate a file in a Linux system, just like the search command in Windows. This command is useful when you don't know where a file is saved or the actual name of the file. Using the -i argument with the command helps to ignore the case (it doesn't matter if it is uppercase or lowercase). So, if you want a file that has the word “aspire”, it gives the list of all the files in your Linux system containing the word "aspire" when you type in “locate -i aspire”. If you remember two words, you can separate them using an asterisk (*). For example, to locate a file containing the words "aspire" and "great", you can use the command “locate -i *aspire*great”.
![Use of locate command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(2).png)
* echo:
The "echo" command helps us move some data, usually text into a file. For example, if you want to create a new text file or add to an already made text file, you just need to type in, “echo hello, my name is alok >> new.txt”. You do not need to separate the spaces by using the backward slash here, because we put in two triangular brackets when we finish what we need to write.
![Use of echo command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(5).png)
* df:
Use the df command to see the available disk space in each of the partitions in your system. You can just type in df in the command line and you can see each mounted partition and their used/available space in % and in KBs. If you want it shown in megabytes, you can use the command “df -m”; "df -h" generally shows the values in human-readable form, usually in powers of 1024.
![Use of df command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(4).png)
* du:
The "du" is used to know the disk usage of a file in your system. If you want to know the disk usage for a particular folder or file in Linux, you can type in the command du and the name of the folder or file. For example, if you want to know the disk space used by the documents folder in Linux, you can use the command “du Documents”. You can also use the command “ls -lah” to view the file sizes of all the files in a folder.
![Use of du command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(7).png)
* sudo:
A widely used command in the Linux command line, sudo stands for "SuperUser Do"; it's pronounced as "sue dough". So, if you want any command to be done with administrative or root privileges, you can use the sudo command to override the need for those rights.
* apt-get:
Use apt to work with packages in the Linux command line. Use apt-get to install packages. This requires root privileges, so use the sudo command with it.You can upgrade the system by typing “sudo apt-get upgrade”. 
![Use of sudo and apt-get command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(6).png)
* hostname:
Use hostname to know your name in your host or network. Basically, it displays your hostname and IP address. Just typing “hostname” gives the output. Typing in “hostname -I” gives you your IP address in your network.
![Use of hostname command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(8).png)
* ping
In Linux, the ping command is a general utility which is used for checking whether any network is present and if a host is attainable. We can test if the server is up and executing using this command. Also, it helps several connectivity issues with troubleshooting. It allows us to: Test our Internet connection,Check if the remote machine is active, analyse when there are network problems such as high latency or dropped packages.ping 0: It is one of the quickest option to ping a localhost. The terminal will resolve determine the IP address and gives a response once we enter this command; to stop the command, we run "ctrl + c" to stop delivering packets to the target.
![Use of ping command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(11).png)
* grep 
It lets you search through all the text in a given file. To illustrate, grep blue notepad.txt will search for the word blue in the notepad file. Lines that contain the searched word will be displayed fully.
![Use of grep command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(12).png)
* head
The head command is used to view the first lines of any text file. By default, it will show the first ten lines, but you can change this number to your liking. For example, if you only want to show the first five lines, type head -n 5 filename.ext.
![Use of head commandt](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(13).png)
* tail
This one has a similar function to the head command, but instead of showing the first lines, the tail command will display the last ten lines of a text file. For example, tail -n filename.ext.
![Use of tail command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(14).png)
*history
When you’ve been using Linux for a certain period of time, you’ll quickly notice that you can run hundreds of commands every day. As such, running history command is particularly useful if you want to review the commands you’ve entered before.
![Use of history command](https://github.com/Ekoyon/Exercises/blob/main/Exercises/Exercise%202/Screenshot%20(15).png)
