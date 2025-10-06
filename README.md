# Ex-03-Linux-Commands
## NAME: Sriharan J V
## REGNO: 212223100054
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
 
![Screenshot from 2025-03-11 20-25-11](https://github.com/user-attachments/assets/55aac873-2a3e-4b66-b57b-c2e740fe2628)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![Screenshot from 2025-03-11 20-26-25](https://github.com/user-attachments/assets/fe2482fb-ea23-4e2d-8d34-abfcb2b2f8b4)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![Screenshot from 2025-03-11 20-31-57](https://github.com/user-attachments/assets/7742bba7-0054-4cc1-8a65-c36065f8b03e)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![Screenshot from 2025-03-11 20-32-48](https://github.com/user-attachments/assets/80e32a11-9a47-410f-932a-13585c106611)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![Screenshot from 2025-03-11 20-35-56](https://github.com/user-attachments/assets/53a8c7bd-c19b-4d19-bb50-316b4c5c35b3)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![Screenshot from 2025-03-11 20-57-48](https://github.com/user-attachments/assets/0b7d6a58-45d3-4536-88c1-662058ef68b4)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![Screenshot from 2025-03-11 21-35-54](https://github.com/user-attachments/assets/124aed10-fc05-4637-bfb4-ba713e3f9030)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![Screenshot from 2025-03-11 21-49-06](https://github.com/user-attachments/assets/b6ec2111-2eb3-4613-860e-a0147a2fd31f)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![Screenshot from 2025-03-11 21-52-57](https://github.com/user-attachments/assets/2dab84e7-7ae0-4f51-bf46-e32a4d0a6a52)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![Screenshot from 2025-03-11 22-04-45](https://github.com/user-attachments/assets/c37e9e11-5615-4702-b081-447217695894)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![Screenshot from 2025-03-11 22-05-52](https://github.com/user-attachments/assets/e3d3b731-5b21-44c8-8ffb-e5c40bafd4bc)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![Screenshot from 2025-03-11 22-16-42](https://github.com/user-attachments/assets/19f2cc01-2bbf-4773-89cb-072fd16828e2)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![Screenshot from 2025-03-11 22-28-58](https://github.com/user-attachments/assets/735d463e-d56d-4047-b84b-63f3b7e4629d)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![Screenshot from 2025-03-12 13-50-39](https://github.com/user-attachments/assets/8bdd8a8f-d70e-4bbc-95f8-db26b1271772)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![Screenshot from 2025-03-12 13-59-44](https://github.com/user-attachments/assets/6e6c1534-72bb-44c2-882e-54fb50f4dba2)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![Screenshot from 2025-03-12 14-03-13](https://github.com/user-attachments/assets/0be5c779-3c36-484c-b9d6-c03928d535a7)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

![Screenshot from 2025-03-12 14-06-18](https://github.com/user-attachments/assets/b496cf9a-d1b0-4026-9d95-88be00f3c835)

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

![Screenshot from 2025-03-12 14-08-45](https://github.com/user-attachments/assets/cd5fa012-5f83-4539-8b36-2da6f1cdfba7)

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/user-attachments/assets/8814f5ae-23ee-411f-8383-0ac2a175b874)



### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![Screenshot from 2025-03-12 14-36-29](https://github.com/user-attachments/assets/ce4cfd2d-7f5a-421f-be60-af885b574fa6)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![Screenshot from 2025-03-12 14-31-45](https://github.com/user-attachments/assets/4ddf3532-2c94-48ea-866d-ec8c013b942e)



### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

![Screenshot from 2025-03-12 14-29-10](https://github.com/user-attachments/assets/e24619be-b7c4-4605-96f3-33394061d0ec)

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![Screenshot from 2025-03-12 14-13-46](https://github.com/user-attachments/assets/5e639104-5660-4d9c-9862-bf82c039727f)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![Screenshot from 2025-03-12 14-14-29](https://github.com/user-attachments/assets/1e9562c0-7e52-4675-a158-ed6f8fed1166)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![Screenshot from 2025-03-12 14-16-28](https://github.com/user-attachments/assets/abf9b671-77b6-4400-b053-1de460b713b9)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![Screenshot from 2025-03-12 14-17-15](https://github.com/user-attachments/assets/5b26c9c0-e82c-4fab-aede-831b2c7016c7)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![Screenshot from 2025-03-12 14-17-47](https://github.com/user-attachments/assets/51d6674b-8d46-4ab5-a05e-612a441d08d8)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/user-attachments/assets/97d31451-b572-4400-96a9-e7f3e4fe8fa1)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/user-attachments/assets/6b69d9a7-5810-4c0d-add8-31e0ed490320)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![Screenshot from 2025-03-12 14-27-31](https://github.com/user-attachments/assets/76490a0c-f4c2-40a2-996f-87b3d52bc6db)

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
