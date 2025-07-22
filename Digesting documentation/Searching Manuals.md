### sumaary 
You’re still working with the program:
```bash
/challenge/challenge
```
And your goal is to find the **secret option** that makes it print the flag.

But this time, you need to search inside the man page to find it — instead of reading everything line by line.
__________
### solution 
- Run the man page:
```bash
man /challenge/challenge
```
- Press `/` to start searching.

- **Type a keyword like**:
```bash
flag
```
and press **Enter**.
- Now:
 *Press `q` to quit the man page*
- Once you find an option like:
```bash
--givemetheflag   Shows the flag and exits.
```
- Exit the man page and run:
```bash
/challenge/challenge --givemetheflag
```


