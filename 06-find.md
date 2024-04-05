# Find command:

find command is used to find the files or directory’s path, it is exactly like the find option in
windows where you can search for a file.

Syntax: find / (under root) –option filename

## Options that can be used with find command:

Option Usage

-name For searching a file with its name

-type For searching a particular type of file

-user For files whose owner is a particular user

-group For files belonging to particular group

#### Finding a File with name
#find / -name Kernel Tech

#### Finding the files, whose owner is a user called “ktuser”
#find / -user ktuser

#### Finding the files whose group is “ktgroup”
#find / -group ktgroup
