# Level 8->9 

Objective: The password for the next level is stored in the file data.txt and is the only line of text that occurs only once


Command used: **_sort data.txt | uniq -u_**

_**sort data.txt**_: sorts the lines in `data.txt` alphabetically or numerically.

_**uniq**_: filters out adjacent duplicate lines in `data.txt`, displaying only one instance of each repeated line.

_**uniq -u**_: filters out and displays only the unique lines (those that occur exactly once).

_**uniq -c**_: displays each unique line from `data.txt` along with the count of how many times it occurs, preceded by the number of occurrences.

2. response given is the password.
if the command uniq -c is used, it shows all the texts and their no. of occurences.

Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM