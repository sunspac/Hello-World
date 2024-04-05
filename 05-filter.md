# Filter Commands:

Filter commands are used to filter the output so that the required things can easily be
picked up. The commands which are used to filter the output are

#less

#more

#head

#tail

#sort

#cut

#sed

## less:-
The less command is used to see the output line wise or page wise.

Ex: less /etc/passwd

Note: -press Enter key to scroll down line by line (or)

Use d to go to next page

Use b to go to previous page

Use / to search for a word in the file

Use v to go vi mode where you can edit the file and once you save it you will back to less

## more:-

more is exactly same like less

Ex: #more /etc/passwd

Note: -press Enter key to scroll down line by line (or)

Use d to go to next page

Use / to search for a word in the file

Use v to go vi mode where you can edit the file and once you save it you will back to
more command

## head:
It is used to display the top 10 lines of the file.

Ex:# head /etc/passwd

To display the custom lines

#head -n /etc/passwd (where n can be any number)

## tail:

It is used to display the last 10 lines of the file

#tail /etc/passwd

To display the custom lines

#tail -n /etc/passwd (where n can be any number)


## Sort:

It is used to sort the output in numeric or alphabetic order

#sort filename

To sort the file according to numbers

#sort –d ktfile or #sort –h ktfile


To remove the duplicate entries from the output

#sort –u ktfile

## cut command:

The cut command is used to pick the given expression (in columns) and display the output.

cut -d -f filename (where d stands for delimiter ex. : , “ “ etc and f stands for field)

To delimit spaces and print the field

#cut –d “ “ –f1 filename

To delimit commas and print the field

#cut –d, -f1 filename


## sed command:

sed stands for stream editor, which is used to search a word in the file and replace it with the
word required to be in the output
Note: it will only modify the output, but there will be no change in the original file.

#sed ‘s/searchfor/replacewith/g’ filename

## I/O Redirection:

Redirection is a process where we can copy the output of any command(s), file(s) into a new
file. There are two ways of redirecting the output into a file.

Using > or >> filename after the command, and

Using tee command

Let’s see the > and >> option first

Syn: command > new file

Note: if the given name of the file is not available a new file will be created automatically. If
the file already exists then it will overwrite contents of that file.

Appending another output in same the same file

Likewise there are many options where we can use redirections

Ex:
Copying contents of two files in a new file

#cat file1 file2 > file3

## Using tee command:

The above options of redirections will not display any output, but directly save the output in
a file. Using tee command will not only redirect the output to new file but it will also display
the output.

Syn: cat <filename> | tee <new file name>

Note: if the given name of the file (newfile) is not available a new file will be created
automatically. If the file already exists then it will overwrite contents of the file.

#cat ktfile |tee ktf1

Appending data in the same file using tee command

Syn: cat filename |tee –a filename2
