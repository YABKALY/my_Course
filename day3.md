# 1) Information gathering
 - Tools for information gathering, in system, network, host
**tools :-**
- dmitry
- legion
- maltego
- nmap and etc. . .
# 2) Vulnerability Analysis
- Tools for Finding Vulnerabilities
**tools :-**
- legion
- nmap
- nikto
- lynis and etc. . .
# 3) Web Application Analysis
● Tools for Finding Vulnerabilities and exploits on websites.

**tools :-**
- paros
- sqlmap
- zap and etc. . .
# 4) Database Assessment
● Tools for Finding Vulnerabilities and exploits on Databases.

**tools :-**
- sqlmap
- sqldict
- jSQL injection and etc . . .
# 5) Password Attacks
● Tools for exploiting Passwords for login,websites,application, windows..

**tools :-**
- john
- johnny
- medusa and etc . . .
# 6) Wireless Attacks
● Tools for exploiting Wireless Systems like wifi, bluetooth..

**tools :-**
- wifite
- reaver
- kismet
- mfterm and etc . . .
# 7) Reverse Engineering
● Tools for exploiting Softwares, Mobile Applications and any binary files

**tools :-**
- radare2
- clong
- clong++ and etc . . .
# 8) Exploitation Tools
● Tools for exploiting Softwares, Mobile ,Computers ,websites and any things

**tools :-**
- metasploit
- sql map and etc . . .
# 1) Sniffing & Spoofing
● Tools for Listening or hijacking networks

**tools :-**
- hamster
- wireshark and etc . . .
# 10) POST exploitation
● Tools for Maintaining our access. Used after exploiting a system

# 11) Forensics
● Tools for Doing researches and investigate a Cyber Attacks.

# 12) Reporting tools
● Tools for Report preparation. After some forensic you will get data and you will write report and these tools will help you.

# 13) Social Engineering tools
● Tools Used for Social Engineering attacks

# 14) System Services
● Buttons used to start some services.

# 15) Usually used applications
● Softwares for some basic purposes

**Linux Commands**
● Linux Systems uses shell. The shell help us to Communicate with the kernel and helps to execute codes.

This is the shells icon —->
Shell also called **“Terminal”**
The terminal have 5 parts.
- Username
- Hostname
- Current Directory
- Priviledge
- Command place
- Home directory
- Local directory with .
- All directory
# Linux Command Basics
● On linux there are over 100 commands.
Also those commands have their own options and arguments.
 **What is command ?**
- command is “Small programs that do one task well”

**ls / List Directory**
● List information about the FILEs (the current directory by default).

- ls -l
- ls -a show hidden file
- ls filename show or list file on thefile name
- ls -R => recursive show ditail Linux hidden files start with dot.
**cd / Change Directory**
- It is used to change current working directory.
- cd / => root
- cd => home
- cd .. => 1x Back
- cd ../.. => 2x Back
- cd foldername
- If folder name have space you have to add the name inside “ folder name “ cd “folder name” Pwd / print working directory It prints the path of the working directory, starting from the root.
**echo**
- echo command in linux is used to display line of text/string that are passed as an argument . This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file. You can write texts into files like :-
- echo text > file.txt
● You can add texts(append)
- echo text >> file.txt
# cat / head / tail / less
● Used to show the content of a file

**touch**
● Creates any kind of Files with the name you gave it. With empty inside.

# Mkdir / make directory
● Creates Folder with the name u gave it.

- DON’T forget to add the “ “ when you are using folders with space between them.
# clear
● Clears your screen.

# rm / remove
● used to remove a file.

- rm -r => recursive(4 folders)
- rm -i => for prompt(ask)
- rm -f => force delete You can use them in combination too like, rm -rf ‘filename’
# Cp| mv / copy,move
● Copy/move files & folders.

# grep - global search for regular expression
- grep [options] pattern [files]
- The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out).
- grep -i “search” file
   * case insensitive
- grep -c “search” file
  * count numbers
- grep -l “search” *
  * displays filename
- grep -R “search” foldername
  * search text in folders
# Wc - word count
- SYNOPSIS It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments. Line(-l) word(-w) byte(-c)

# Multiple Command Executions
● You can run/ execute multiple commands in 1 line.
using 3 methods:
- And ( && )
- Or ( || )
- Pipeing( | )
# AND ( && )
●On AND operation All commands you entered will be executed. If both are working without error

# OR ( || )
● On OR operation the command will be executed. If it have error or not

# Piping ( | )
● On pipe, will help you run commands by using the output of the 1st command as the input for the next one.

# sed / stream editor
● The sed command modifies lines from the specified File parameter according to an edit script and writes them to standard output. The sed command includes many features for selecting lines to be modified and making changes only to the selected lines.
# awk
● The awk command is a Linux tool and programming language that allows users to process and manipulate data and produce formatted reports. The tool supports various operations for advanced text processing and facilitates expressing complex data selections.