---
name: Joseph Samaan
course: cis106
semester: Fall 2023
---

# Question 1
| Name     | Description                                                               | Formula                                                       | Examples                                                                                              |
| -------- | ------------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| awk      | scripting language used for processing and displaying text                | awk + option + {awk command} + file + file to save (optional) | awk 'END {print NR}' filename.txt, awk '{print $2, $4}' cheese.txt, awk '/pattern/' cheese.txt        |
| cat      | displaying contents of file                                               | cat + option + file                                           | cat ~/Documents/cheese.txt,  cat file1.txt file2.txt, cat -n fire.txt                                 |
| cp       | copy files oor groups of files or directories                             | cp + file/directory                                           | cp DesktopWallpaper/Photos, cp file1.txt file2.txt /path/to/destination/, cp original.txt newname.txt |
| cut      | extract a specific section of each line                                   | cut + option + file                                           | cut -d ':' -f1 /etc/passwd, cut -d',' -f1,3 file.csv, cut -f2 file.txt                                |
| grep     | search text in given file                                                 | grep + option + search criteria + file                        | grep 'dracula' ~/Documents/dracula.txt, grep -n "pattern" burgers.txt, grep -c "pattern" fries.txt    |
| head     | displays the top N number of lines                                        | head + option + file                                          | head ~/Documents/Book/dracula.txt, head -n 20 water.txt,  head -n 15 -v watermelon.txt                |
| ls       | list files                                                                | ls                                                            | 'ls', ls -l, ls -a                                                                                    |
| man      | system manuel pager                                                       | man + options + command                                       | man -f ls, man -k burgers, man 3 printf                                                               |
| mkdir    | creates a new directory                                                   | mkdir + directory name                                        | mkdir cheetos,  mkdir dir1 dir2 dir3,  mkdir /path/to/directory                                       |
| mv       | moves files and directories from one directory to another or rename files | mv + file 1 + location                                        | mv dir 1/ dir2/, mv file1.txt file2.txt /path/to/destination/,  mv olddir/ newdir/                    |
| tac      | displaying contents of file in reverse order                              | tac + option + file                                           | tac ~/Documents/cheese.txt  tac water.txt, tac file1.txt file2.txt                                    |
| tail     | displays the last N number of lines                                       | tail + option + file                                          | tail ~/Documents/Book/dracula.txt, tail -n 20 filename.txt, tac filename.txt                          | tail -n 5                                  |
| touch    | creates or updates timestamps on a file                                   | touch + file name                                             | touch -a Doc1, touch file1.txt file2.txt, touch existing_file.txt                                     |
| tr       | translating or deleting characters                                        | tr + option + set + set                                       | cat file.txt (line) tr '.' ',', echo "Hello"                                                          | tr 'A-Z' 'a-z', echo "This is a sentence." | tr ' ' '\t' |
| tree     | listing program with an indented file list                                | tree                                                          | tree Directory/, tree -l, tree /path/to/directory                                                     |

# Question 2
## How to work with multiple terminals open?
By opening multiple terminals at once, it gives the user the freedom to test something that they need done while not ruining your current working area. This is good for efficiency and organization.
## How to work with manual pages?
Manuel pages are a resource for the user while doing work. It can help when using commands or learning new functions via the system.
## How to parse (search) for specific words in the manual page
The parse search allows you to look for specific words or patterns. It can be done by typing man less.
## How to redirect output (> and |)
Commands can be redirected to many outputs. You can do this by using command > output.txt. If you'd like to append a file you would add another arrow to the command.
## How to append the output of a command to a file
To append the output of a command you would simply add another arrow to the redirect output command. Command >> output
## How to use wildcards
Wildcards are used to look for specific file types that all have a matching file types. Users can find them by using the * while looking for a file type. ls *.docx
## For copying and moving multiple files at the same time
Copying files would use the cp command whereas moving would use the mv command. cp file1.txt file2.txt /path/to/destination/ versus mv file1.txt file2.txt /path/to/destination/
## How to use brace expansion
Brace expansion it good for doing the same action multiple times using the {}. This would be good for making the same filetype with different names.
## For creating entire directory structures in a single command
Mkdir would allow you to create an entire directory structure in one command via the output you provide. mkdir -p /home/user/documents/watermelon/watermelon1
