#### wsl installation:
https://learn.microsoft.com/en-us/windows/wsl/install-manual
https://learn.microsoft.com/en-us/windows/wsl/install

# BASIC COMMANDS
## Creating, Removing, Copying, Moving files & Directories
### Creating a file in Linux
#### Using cat command:
cat (Concatenate) command is used to create a file and to display and modify the contents
of a file.To create a file
cat > filename (say ktfile)
Hello World
Ctrl+d (To save the file)

#### To display the content of the file
cat filename (say ktfile)

#### To append the data in the already existing file
cat >> <filename>
cat >> ktfile
Ctrl+d (to save the changes)

#### Creating multiple files at same time using touch command
touch <filename> <filename> <filename>
touch file1 file2 file3
Note: to check the files use # ls command

#### Copying files into directory
cp <source filename> <destination directory in which to paste the file>
cp file1 ktdir

#### Copying directories from one location to other
cp –rvfp <dir name> <destination name>
cp –rvfp ktdir2 ktdir

#### Moving files from one location to other (cut and Paste)
mv <filename> <Destination directory>
mv file2 ktdir

#### Moving a Directory from one location to other
mv <dir name> <destination dir name>
mv ktdir ktdir2

#### Renaming a File
mv <old name> <new name>
mv ktfile kernelfile

#### Renaming a Directory
The procedure and command for renaming the directory is exactly same as renaming a file.
mv old name new name
mv ktdir kerneldir

#### Removing a File
#rm filename or #rm –f filename (without prompting)

#### Removing an Empty directory
#rmdir dirname

#### Removing a directory with files or directories inside
A dir which is having some contents inside it cannot be removed by rmdir command. There are
two ways to delete the directory with contents.

i. Remove the contents inside the directory and then run rmdir command

ii. Run #rm –rf dirname (where r stands for recursive and f stands for forcefully.
