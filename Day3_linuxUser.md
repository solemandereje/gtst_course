# **Linux for User**

## Overview of kali linux

- Previously known as Backtrack

# kali linux Gnome Main Screen

1. **Information Gathering**

   > Tools for information gathering, in system network, host.
   >
   > > - dmitry
   > > - ike-scan
   > > - legion
   > > - maltego
   > > - netdiscover
   > > - nmap
   > > - p0f
   > > - recon-ng
   > > - spiderfoot

2. **Vulnerability Analysis**

   > Tools for Finding Vulnerabilities
   >
   > > - legion
   > > - lynis
   > > - nikto
   > > - nmap
   > > - unix-privesc-check

3. **Web Application Analysis**
   > Tools for Finding Vulnerabilities and exploits on websites.
   >
   > > - Burp Suite
   > > - commix
   > > - HTTrack
   > > - paros
   > > - skipfish
   > > - sqlmap
   > > - webscarab
   > > - ZAP
4. **Database Assessment**

- Tools for Finding Vulnerabilities and exploits on Databases.
  > > - jsql injection
  > > - mdb-sql
  > > - oscanner
  > >   -sidgusser
  > > - sqldict
  > > - Sqlite Database
  > > - sqlmap
  > > - sqlninija
  > > - sqlsus
  > > - tnscmd10g

5. **Password Attacks**

- Tools for exploiting
  Passwords for login,websites,application,
  windows.
  > > - cewl
  > > - crunch
  > > - hashcat
  > > - john
  > > - johnny
  > > - medusa
  > > - ncrack
  > > - ophcrack

6. **Wireless Attacks**

- Tools for exploiting Wireless Systems like wifi, bluetooth..
  > > - aircrack -ng
  > > -
  > > -
  > > -

7. **Reverse Engineering**

- Tools for exploiting Softwares, Mobile
  Applications and any binary files
  > > - apktool

8. **Exploitation Tools**

- Tools for exploiting
  Softwares, Mobile ,Computers ,websites and
  any things.
  > > - armitag

9. **Sniffing & Spoofing**

- Tools for Listening or hijacking networks
  > > - driftnet

10. **POST exploitation**

- Tools for Maintaining our access. Used after
  exploiting a system.
  > > - Backdoor -f

11. **Forensics**

- Tools for Doing researches
  and investigate a Cyber
  Attacks.
  > > - autopsy

12. **Reporting tools**

- Tools for Report
  preparation. After some
  forensic you will get data
  and you will write report
  and these tools will help
  you.
  > > - cutycapt

13. **Social Engineering tools**

- Tools Used for Social
  Engineering attacks.
  > > - backdoor -f

14. **System Services**

- Buttons used to start some
  services.

15. **Usually used applications**

- Softwares for some basic
  purposes

# **Linux Commands**

- Linux Systems uses shell. The shell help us to Communicate with the kernel and helps to execute codes.

## Basic Linux Command

- ls / List Directory
  > > - SYNOPSIS
  > >   > - ls [OPTION]... [FILE]...
  > > - DESCRIPTION
  > >   > - List information about the FILEs (the current directory by default).
- cd/ change directory
  > > - SYNOPSIS
  > >   > - cd [directory]
  > > - DESCRIPTION
  > >   > - It is used to change current working
  > >   >   directory.
- Pwd / print working directory
  > > - SYNOPSIS
  > >   > - pwd [-options]
  > > - DESCRIPTION
  > >   > - It prints the path of the working directory,
  > >   >   starting from the root.
- echo
  > > - SYNOPSIS
  > >   > - echo [option] [string]
  > > - DESCRIPTION
  > >   > - echo command in linux is used to
  > >   >   display line of text/string that are passed as an argument . This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file.
- cat / head / tail / less
  > - SYNOPSIS
  >   > - cat [FILE]...
  > - DESCRIPTION
  >   > - Used to show the content of a file
- Touch
  > - SYNOPSIS
  >   > - touch [FILE1] [FILE2] [FILE3]
  > - DESCRIPTION
  >   > - Creates any kind of Files with the name you gave it. With empty inside.
- Mkdir / make directory
  > - SYNOPSIS
  >   > - mkdir [FOLDER-NAME1] [FOLDER-NAME2] [FOLDER-NAME3]
  > - DESCRIPTION
  >   > - Creates Folder with the name u gave it.
  > - 🔔 DON’T forget to add the “ “ when you
  >   are using folders with space between
  >   them.
- clear
  > - SYNOPSIS
  >   > - clear
  > - DESCRIPTION
  >   > - Clears your screen.
- rm / remove
  > - SYNOPSIS
  >   > - rm [FILE1] [FILE2] [FILE3]
  > - DESCRIPTION
  >   > - Remove file.
- Cp| mv / copy,move
  > - SYNOPSIS
  >   > - cp [oldFILEplace] [newfilePlace]
  >   > - Mv [oldFILEplace] [newfilePlace]
  >   - DESCRIPTION
  >     > - Copy/move files & folders.
- grep - global search for regular expression
  > - grep [options] pattern [files]
  > - The grep filter searches a file for a
  >   particular pattern of characters, and
  >   displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression
  > - grep: stands for global search for regular expression and print out).
  > - Greep options:
  >   > - grep -i “search” file - case insensitive
  >   > - grep -c “search” file - count numbers
  >   > - grep -l “search” \* - displays filename
  >   > - grep -R “search” foldername - search text in folders
- Wc - word count
  > - SYNOPSIS
  >
  >   > - wc [OPTION]... [FILE]...
  >
  > - DESCRIPTION
  >   > - It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments.
- Multiple Command Executions
  > - You can run/ execute multiple commands in 1 line.
  >
  > - using 3 methods:
  >   > - And ( && )
  >   > - Or ( || )
  >   > - Pipeing( | )
- AND ( && )
  > - On AND operation All commands you entered will be
  >   executed. If both are working without error.
- OR ( || )
  > - On OR operation the command will be executed. If it have error or not
  - Pipeing ( | )
    > - On pipe, will help you run commands by using the output of the 1st command as the input for the next one.
