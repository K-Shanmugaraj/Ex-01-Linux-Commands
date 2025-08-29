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

 Syntax: ls
<img width="776" height="78" alt="image" src="https://github.com/user-attachments/assets/773dd5f8-6a6e-449c-a208-6cc04d577987" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
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

<img width="771" height="69" alt="image" src="https://github.com/user-attachments/assets/8e371786-3129-4726-ab8e-583ca18e8ee6" />
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="772" height="112" alt="image" src="https://github.com/user-attachments/assets/c2146cc1-a89b-42f2-8417-6f9f7fa21213" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="763" height="53" alt="image" src="https://github.com/user-attachments/assets/0af59bc1-4b14-459f-bd3d-7f8f049a76d8" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="751" height="65" alt="image" src="https://github.com/user-attachments/assets/5173ffbf-c7b1-49ee-accf-a03486882e22" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 <img width="275" height="55" alt="Screenshot 2025-08-24 195126" src="https://github.com/user-attachments/assets/0d8c4f22-4bbf-417e-a369-735cf8d759d0" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="874" height="133" alt="Screenshot 2025-08-24 195138" src="https://github.com/user-attachments/assets/ccf576a8-0ae6-4ecd-b7fe-a6aaf7038240" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>



<img width="319" height="201" alt="Screenshot 2025-08-24 195257" src="https://github.com/user-attachments/assets/53e042ef-e882-4318-b5de-0217df2b76b5" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="283" height="196" alt="Screenshot 2025-08-24 195305" src="https://github.com/user-attachments/assets/451b09bf-6f07-4ad5-8b96-92dae91df772" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="948" height="102" alt="Screenshot 2025-08-24 195312" src="https://github.com/user-attachments/assets/fd0e98c2-ac17-433b-8d6a-b279f3f46eaa" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="298" height="56" alt="Screenshot 2025-08-24 195317" src="https://github.com/user-attachments/assets/49416cc2-f0bc-4db3-8898-4abee09f2fb4" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="386" height="212" alt="Screenshot 2025-08-24 195324" src="https://github.com/user-attachments/assets/7d48383a-abe4-4c50-9166-a1dc9022a563" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="521" height="108" alt="Screenshot 2025-08-24 195332" src="https://github.com/user-attachments/assets/07279f2a-3b1c-4360-8da5-14e943539cea" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

 <img width="355" height="148" alt="Screenshot 2025-08-24 195536" src="https://github.com/user-attachments/assets/c9dcbba9-1f8d-425e-9d2b-17eec9d90ef8" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="519" height="128" alt="Screenshot 2025-08-24 195545" src="https://github.com/user-attachments/assets/f5b10fd3-531b-41ba-aee0-90b211e67811" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="209" height="62" alt="image" src="https://github.com/user-attachments/assets/b9208aed-4851-4d88-b0e7-a5c96bf0623e" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="809" height="87" alt="Screenshot 2025-08-24 200216" src="https://github.com/user-attachments/assets/16959acd-ce6a-464b-87a5-5d58244c5534" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 <img width="503" height="111" alt="Screenshot 2025-08-24 200222" src="https://github.com/user-attachments/assets/4a62bbaa-feef-4884-81ee-1dfe2392c6ef" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="477" height="90" alt="Screenshot 2025-08-24 200228" src="https://github.com/user-attachments/assets/1e9854ba-13ed-4de4-b3cc-30746efadab5" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="737" height="174" alt="Screenshot 2025-08-24 200237" src="https://github.com/user-attachments/assets/b2de0e9a-bbc1-47e3-bdbe-93acff1da889" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


 <img width="361" height="224" alt="Screenshot 2025-08-24 200245" src="https://github.com/user-attachments/assets/3469d1bc-d1b9-4167-a212-3c20b12cacf4" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="308" height="178" alt="Screenshot 2025-08-24 200251" src="https://github.com/user-attachments/assets/c97b9e2c-184a-49db-bf0d-ebe72f9e4f28" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="313" height="42" alt="Screenshot 2025-08-24 200522" src="https://github.com/user-attachments/assets/740139f6-d3ab-4f12-99da-3a003f010a8c" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="1037" height="288" alt="Screenshot 2025-08-24 200300" src="https://github.com/user-attachments/assets/020f94b8-7fcb-4079-a7f0-d8d1f2976fff" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





<img width="301" height="251" alt="Screenshot 2025-08-24 200315" src="https://github.com/user-attachments/assets/a5ce3c68-58bd-4dc1-aaf6-1dbe74460cb8" />

















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
