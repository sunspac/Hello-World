# Listing files and directories:

#ls     ==> list the file names

#ls -l  ==> long listing of the file

#ls –l  ==> filename to see the permissions of a particular file

#ls -al ==> shows the files in ascending order of modification.

#ls p*  ==> All the files start with p.

#ls ?ample ==> Files with any first character and has ample

#ls -ld l* ==> Directory listing only

#ls –ld    ==> directory name to see the permissions of a particular directory

#ls [ae]*  ==> First character of the filename must be a or e.

#ls [!ae]* ==> ! Symbol complements the condition that follows. The characters must

not be a or e.

#ls [a-m][c-z][4-9]  ==> list all the files in specific range


# Types of Files:
  Symbol  Type of File
  -       Normal file
  d       Directory
  l       Link file (shortcut)
  b       Block file (Harddisk, Floppy disk)
  c       Character file (Keyboard, Mouse)

# File Permissions:
## Permissions are applied on three levels:-
Owner or User level

Group level

Others level

## Access modes are of three types:-
r read only

w write/edit/delete/append

x execute/run a command

## Access modes are different on file and directory:
Permissions      Files                                     Directory

r             Open the file                          'ls' the contents of dir

w             Write, edit, append, delete file       Add/Del/Rename contents of dir

x             To run a command/shell script          To enter into dir using 'cd'


Filetype+permission, links, owner, group name of owner, size in bytes, date of modification,
file name

## Permission can be set on any file/dir by Absolute methods (numbers)
In Absolute method we use numbers instead of using symbols i.e.

Read=4

Write=2

Execute=1

## The default permission for file is 644
## The default permission for dir is 755

#### Assigning different permissions to the file (user=rwx, group=rw and others=r)
#chmod 764 ktfile (where 7 means rwx i.e. 4+2+1, rw=6 i.e. 4 indicates read 2 indicates write and 1 indicates x)

#### Removing all permissions from others
#chmod 770 ktfile (where 0 indicates no permissions)

#### Assigning full permission to the file i.e. rwx to all
#chmod 777 ktfile
