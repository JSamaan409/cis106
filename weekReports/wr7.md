---
name: Joseph Samaan
semester: Fall 2023
course: cis106
---

# Week Report 7

## Answers to Questions

| Command | Used for                                                   | Formula                                                       | Examples                                 |
| ------- | ---------------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------- |
| cat     | displaying contents of file                                | cat + option + file                                           | cat ~/Documents/cheese.txt               |
| tac     | displaying contents of file in reverse order               | tac + option + file                                           | tac ~/Documents/cheese.txt               |
| head    | displays the top N number of lines                         | head + option + file                                          | head ~/Documents/Book/dracula.txt        |
| tail    | displays the last N number of lines                        | tail + option + file                                          | tail ~/Documents/Book/dracula.txt        |
| cut     | extract a specific section of each line                    | cut + option + file                                           | cut -d ':' -f1 /etc/passwd               |
| paste   | used for joining files horizontally in columns             | paste + option + file                                         | paste users.lst ip_address.lst           |
| sort    | used for sorting files                                     | sort + option + file                                          | sort users.lst                           |
| wc      | printing the number of lines, characters, bytes            | wc + option + file                                            | wc -m users.txt                          |
| tr      | translating or deleting characters                         | tr + option + set + set                                       | cat file.txt (line) tr '.' ','           |
| grep    | search text in given file                                  | grep + option + search criteria + file                        | grep 'dracula' ~/Documents/dracula.txt   |
| awk     | scripting language used for processing and displaying text | awk + option + {awk command} + file + file to save (optional) | awk '{print$1}' ~/Documents/Csv/cars.csv |