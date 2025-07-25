### summmary 
You have a magic command:<br>
 `/challenge/run`

It prints a mountain of words — 100,000 lines!
But one of them is very special: it has the FLAG. 

Your job is:

Save all those words into a file. 

Look through the file to find the word “FLAG”
_________
### solution 
`/challenge/run > /tmp/data.txt ` <br>
`grep -o '[a-zA-Z0-9_]\+{[^}]*}' /tmp/data.txt`

_________
### Tricks:
- `>` means “put the words into this file”.

- `grep` means “look for a word”.

