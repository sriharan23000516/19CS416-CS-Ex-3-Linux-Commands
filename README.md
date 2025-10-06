# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## Name:SRIHARAN J V
## Reg.N0:212223100054
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

  ## 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
    To install and configure Oracle VM VirtualBox.

# Pre-requisites:
*Machine with Internet access

*Minimum 4 GB RAM

*Sufficient storage space

# Steps:
1.Download Oracle VM VirtualBox:

*Visit Oracle VirtualBox Official Site
*Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

*Launch Installer → Allow Changes → Click Next.
*Choose Installation Options → Click Next.
*Accept Network Interface Warning → Click Yes.
*Click Install.
*Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

*Open VirtualBox.

*Click New → Name VM → Select Type (Linux/Windows) and Version.

  *Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

*Start Virtual Machine and provide ISO to install OS.

# Result:
Thus, Oracle VM VirtualBox was installed successfully.

  ## 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
*Oracle VM VirtualBox Installed

*4 GB RAM and 20 GB Storage Minimum

*Kali Linux ISO image

# Steps:
1.Download Kali Linux ISO:

*Visit Kali Linux Official Site

*Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

*Open VirtualBox → Click New.

*Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

*Allocate Memory:
*Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

*Select VDI (VirtualBox Disk Image).

*Choose Dynamically allocated.

*Set Disk size to 20 GB or more.

5.Configure ISO Image:

*Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6.Start Installation:

*Boot Virtual Machine → Choose Graphical Install.

*Set Language, Region, Keyboard.

*Configure Network → Set Hostname (e.g., kali).

*Set root password.

*Disk Partitioning: Use entire disk → All files in one partition.

*Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

*Use root credentials.
8.(Optional) Install Guest Additions:

*Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
## Snapshots:
AWS Account Creation Snapshot

## Snapshot 1: Installing Oracle VirtualBox image:
<img width="1161" height="427" alt="484050075-4601a0ef-d745-41f6-ad82-5f3dc39058a5" src="https://github.com/user-attachments/assets/0b9d7ad3-85bd-48d9-9c7a-21d822ce4721" />

## Snapshot 2: Kali Running in Virtual image:
<img width="787" height="483" alt="484050272-1fbcef39-2761-4f43-9492-4af14ee84661" src="https://github.com/user-attachments/assets/ac12d577-6a6b-435e-8546-ad7d422d9224" />
## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

  ## 3.c) Execution of Linux Commands in Kali
# About Linux:
*Open-source operating system.

*Kernel manages communication between hardware and software.

*Commands are case-sensitive.
## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:ls** 

**Output:**
<img width="783" height="57" alt="484050459-f5a47861-18c6-4691-bf31-71ee845752b9" src="https://github.com/user-attachments/assets/335afe5b-5fc7-4706-ba94-7f365fb1da59" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="250" height="67" alt="484050591-f109b5da-c6db-483c-b169-7bfca0a073c2" src="https://github.com/user-attachments/assets/b7787a34-1fea-44fd-8279-c55aac15f329" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
<img width="795" height="92" alt="484050723-cbc52820-d96a-42aa-a805-74967f55fb63" src="https://github.com/user-attachments/assets/1ab1272a-2a46-4d67-9e50-24326ad9153f" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="766" height="102" alt="484050798-c51c75a9-fa58-4bcc-aa8c-9b5509b29c93" src="https://github.com/user-attachments/assets/db4e85a4-0175-45d8-a9c8-16111190e51a" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```
### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="362" height="212" alt="484050999-09efb782-1edc-416d-aebd-fae177fc4ca6" src="https://github.com/user-attachments/assets/6c0f0627-c30d-483d-8c10-fc76af1fbf2f" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="315" height="157" alt="484051594-12fc3307-5834-445e-b1d0-9bbe63255651" src="https://github.com/user-attachments/assets/d872b880-b1ca-4201-bb06-6fcfaa7e5e8a" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="415" height="37" alt="484051715-3a0038a2-4240-4c8c-97b5-2eb0aca63841" src="https://github.com/user-attachments/assets/969fdec4-a369-48c3-a23d-c2ab80e2f57a" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="276" height="105" alt="484051830-abadda1d-b010-48f3-94b6-23557eb24ed6" src="https://github.com/user-attachments/assets/df473211-8940-41d3-8565-8a544c0a977f" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="423" height="647" alt="484052473-360a7499-4039-47e6-980b-e390309b5616" src="https://github.com/user-attachments/assets/a0b479f2-a51b-4a1a-a78d-d9f1b3da7b48" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="305" height="275" alt="484052578-84bf474c-e3b8-4ffb-b955-0ab9e4a5977f" src="https://github.com/user-attachments/assets/1f264ba0-366c-4273-9d66-970ea24a8882" />

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
<img width="807" height="31" alt="484053189-4f52e986-6d38-43a7-ae0d-1f173730831c" src="https://github.com/user-attachments/assets/84e65ced-f5c5-4c8a-865b-67cf8328bb38" />

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
<img width="368" height="77" alt="484053362-ee9fda3b-8878-46b3-a3b2-7a2ad3ef217e" src="https://github.com/user-attachments/assets/cb758ea0-cdcc-4999-8fa3-85dbfd752aeb" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="422" height="363" alt="484053521-108cd05c-3a5b-4e41-b5d0-6e14e50a7d27" src="https://github.com/user-attachments/assets/23c8a7e7-5b6c-4edc-9223-eb6a85c0d6a7" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="522" height="138" alt="484054682-2e015f71-baa0-40d5-8002-42937e42cc3a" src="https://github.com/user-attachments/assets/aee17490-dfb3-435e-b641-dd66e7a97a1e" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="405" height="185" alt="484054547-73654aa4-e11d-4901-9334-820aefde655a" src="https://github.com/user-attachments/assets/a33c8566-4f11-4d67-b20a-e2ce59f3d221" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="532" height="155" alt="484054892-b8a2b8fa-b095-45f8-974c-a379a99a7bde" src="https://github.com/user-attachments/assets/e8a9fa27-2fcc-41ca-9799-1a38bba8eff3" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
<img width="253" height="72" alt="484055220-b319bc46-9b86-43af-8f1b-ac218c49d9d9" src="https://github.com/user-attachments/assets/46b60743-f0c1-4020-a1b7-c1d0d0d45c7c" />

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="747" height="87" alt="484055457-5bebe4e9-28fc-40b8-bf5d-2618c5e4697f" src="https://github.com/user-attachments/assets/d7e135fa-e8f4-4924-a35c-7c112befdb73" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
<img width="542" height="137" alt="484055605-509b3a93-ae93-47c1-852b-e9d37513cf37" src="https://github.com/user-attachments/assets/58b97e59-8891-43da-a8fc-2f5e0ef81e95" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="608" height="120" alt="484055793-4cb52485-72e9-4b68-9967-dbbfb70a7fdc" src="https://github.com/user-attachments/assets/8a485095-425d-4ce7-be99-b8ea98ce2a3d" />

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```
bash
gzip <file1> <file2> <file3>
```
**Output**

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="265" height="363" alt="484056202-2e8d9d29-4e4b-47f7-9fe8-52636da381a6" src="https://github.com/user-attachments/assets/907f901a-2c3d-466d-b89b-1b93bf987b52" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
<img width="318" height="233" alt="484056374-8a213217-ee35-47dc-a4c1-543588cb31b7" src="https://github.com/user-attachments/assets/894703ef-0a67-4fc4-919d-7dc14e1dfced" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
<img width="683" height="772" alt="484056580-48ac904b-7486-4035-8a97-d0e0117f2831" src="https://github.com/user-attachments/assets/9a43cc44-b4e1-4d27-afd1-2abb8f867c98" />
<img width="547" height="286" alt="484056651-0a377cda-a9d4-40fd-9f60-1c7a4d256be7" src="https://github.com/user-attachments/assets/dc97cc3e-35ba-4420-aa6e-f7c84699d073" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
<img width="771" height="65" alt="484056934-5291a3d5-ef0d-4ba9-954d-d08e274526cc" src="https://github.com/user-attachments/assets/1d48301d-dfb8-4ac8-8951-832ae5347d09" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
<img width="761" height="248" alt="484057048-ddd09234-3826-4d7e-9a51-84441104c848" src="https://github.com/user-attachments/assets/c73c5a14-3cda-4867-93f2-9066f6289dd4" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="342" height="96" alt="484057129-a855266b-9b2b-4bcc-8edb-6c76819bc11c" src="https://github.com/user-attachments/assets/88098d10-102d-4393-9146-e73b54d0de65" />

## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
