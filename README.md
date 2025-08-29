# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls <br>
<img width="776" height="78" alt="image" src="https://github.com/user-attachments/assets/773dd5f8-6a6e-449c-a208-6cc04d577987" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd <br>
<img width="775" height="71" alt="image" src="https://github.com/user-attachments/assets/8e247fcf-d66a-4e80-949d-0425bc449977" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="775" height="54" alt="image" src="https://github.com/user-attachments/assets/8b065a3c-2655-424e-9921-868a0292fe50" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="779" height="57" alt="image" src="https://github.com/user-attachments/assets/165fd8bb-9160-4b33-b1c4-0f087fc6ecad" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="774" height="51" alt="image" src="https://github.com/user-attachments/assets/6110d95d-1d3d-4bff-ae71-0717bc51d5a2" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="772" height="67" alt="image" src="https://github.com/user-attachments/assets/f43c8e1e-b173-4374-914c-c18c47e21404" />

<img width="771" height="69" alt="image" src="https://github.com/user-attachments/assets/8e371786-3129-4726-ab8e-583ca18e8ee6" /> <br>
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="772" height="112" alt="image" src="https://github.com/user-attachments/assets/c2146cc1-a89b-42f2-8417-6f9f7fa21213" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name <br>
<img width="763" height="53" alt="image" src="https://github.com/user-attachments/assets/0af59bc1-4b14-459f-bd3d-7f8f049a76d8" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name> <br>
<img width="751" height="65" alt="image" src="https://github.com/user-attachments/assets/5173ffbf-c7b1-49ee-accf-a03486882e22" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="756" height="56" alt="image" src="https://github.com/user-attachments/assets/a8964c30-631c-40a1-a06e-e4165939307f" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="766" height="142" alt="image" src="https://github.com/user-attachments/assets/223d614b-5c47-4166-8c75-21f09e39fdd8" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="749" height="314" alt="image" src="https://github.com/user-attachments/assets/b8627fe0-7673-4af2-a7c7-88d2eed4a443" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="754" height="250" alt="image" src="https://github.com/user-attachments/assets/48e8ab62-b429-42f1-9322-c1b7148ff478" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="927" height="118" alt="image" src="https://github.com/user-attachments/assets/eb19422f-2e65-47ce-9778-b650a9d23422" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="761" height="78" alt="image" src="https://github.com/user-attachments/assets/0a692eb6-b688-4636-97cd-3a56de243fcc" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="752" height="261" alt="image" src="https://github.com/user-attachments/assets/8d667c68-140a-4c25-ad46-1d0da71a6851" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="741" height="139" alt="image" src="https://github.com/user-attachments/assets/edbef9a7-b5d7-4cde-a19b-152892a218be" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="762" height="178" alt="image" src="https://github.com/user-attachments/assets/b73360d1-eba8-46b6-899a-b7ea9495745b" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="760" height="130" alt="image" src="https://github.com/user-attachments/assets/32df28a0-41a0-4d8f-9915-f2c1f26eb7d1" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="762" height="73" alt="image" src="https://github.com/user-attachments/assets/ddadab25-dd33-4b1b-9df3-d4cf2a80db9f" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="888" height="121" alt="image" src="https://github.com/user-attachments/assets/83b6eb99-377a-45ef-8ffd-5fe66ec8c9e2" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="757" height="130" alt="image" src="https://github.com/user-attachments/assets/af9a7af8-01cb-417a-a827-42d71691204d" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="759" height="134" alt="image" src="https://github.com/user-attachments/assets/a67e40d1-cfec-493a-ac5c-53af26de6052" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="754" height="215" alt="image" src="https://github.com/user-attachments/assets/d2da4be6-3a6f-4b81-8eff-537e1cefd090" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


<img width="760" height="281" alt="image" src="https://github.com/user-attachments/assets/0047e838-1903-4007-b932-4f1685ea7430" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="746" height="218" alt="image" src="https://github.com/user-attachments/assets/6ce23476-ddc9-4fed-b067-ea430235edcb" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="767" height="57" alt="image" src="https://github.com/user-attachments/assets/83dfd71b-922f-4a55-9460-89b605921f3b" />
<img width="750" height="137" alt="image" src="https://github.com/user-attachments/assets/bf1b6362-ef31-4954-b1e9-a874fada55ef" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address> <br>
<img width="764" height="112" alt="image" src="https://github.com/user-attachments/assets/7740fff2-e1f5-4a00-8b6e-4abe2d0309ee" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="922" height="278" alt="image" src="https://github.com/user-attachments/assets/2729365e-a5c5-4e25-94b0-e2e110be7253" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="744" height="326" alt="image" src="https://github.com/user-attachments/assets/13984486-d543-41c8-add8-8ccd03a6870f" />














## Result:

Thus, the execution of various Linux commands is executed successfully using Linux OS.
