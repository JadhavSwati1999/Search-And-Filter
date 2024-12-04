# Search and filter.


### Filter: to check a specific pattern from a file.

### Sort.

1. **To sort the data inside the file**

sort filename 

1. **To reverse the data in the file**

sort -r filename

### Grep

1. ***To find the word in the specific file***

grep word filename

1. ***To see the number of that word in that file.***

grep -n word filename

1. ***To check the unique words***

grep -w filename

1. ***Number of words after the particular given word***

grep -A no. word filename

1. ***Number of words before the particular given word***

grep -B no. word filename

1. ***Gives the count of the mentioned word***

grep -wc word filename

1. ***If you want to exclude a word and check the remaining file***

grep -v word filename

1. ***For multiple words***

grep -nE “root|network” filename

1. ***To ignore case-sensitive***

grep -i word filename

1. ***To get the number of that word***

grep -inE “multiple|word” filename

1. ***Count of the words***

grep -icE “multiple|words” filename

**Search: to find out the file location**

There are two types of search utilities

1. Find                                             2. Locate

1. **Find-To find the related list of files based on conditions**

find (path)(options)(parameters)

1. **Locate - It searches the path of a file**

updatedb

locate filename

### **To remove the duplicate lines from the file**

- uniq

uniq  /filename
