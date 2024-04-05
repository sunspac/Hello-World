# Regular Expressions
## Grep:
Grep stands for Global Regular Expression Print. It is used to pick out the required expression
from the file and print the output. If grep is combined with another command it can be used to
pick out the selected word, phrase from the output of first command and print it.

## Examples of Grep:

Let us pick the information about root from the file /etc/passwd (/etc/passwd contains
information about all the users present in the system)
#grep root /etc/passwd

## To avoid case sensitivity of the word (i.e. the word may be uppercase of lowercase) use -i
#grep –i kernel ktfile (lets grep the word kernel whether upper of lower case in the file ktfile)

## To display a word and 2 lines after the word:
#grep –nA2 wheel /etc/group

## To display a word and 2 lines after the word:
#grep -nB2 wheel /etc/group

## To display the things except the given word:
#grep –v kernel ktfile

## To display the searched word in color
#grep --color root /etc/passwd

## Combining grep with other commands
# cat ktfile | grep –I kernel (pipe | is used to combine to commands)
#ls –l |grep –I ktfile
# ifconfi g |grep –I eth0
Like this we can combine grep with many commands which we will see in later chapters
