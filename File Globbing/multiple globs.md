### summary 
You're in `/challenge/files`, and there are many files with different names.

You want to pass a glob pattern (just 1 argument) to `/challenge/run` that matches every file with the letter `p` in its name, like:

- `pwning`
- `optimistic`
- `uplifting`
- etc.

   **The trick**:

     - You must use two asterisks * (wildcards)

     -  And the entire glob must be 3 characters or less

  Bash Globbing Reminder:
- `*` matches any number of characters (including zero).

- So a glob like `*p*` means:

  - "Anything, then a `p`, then anything again"

It matches any file that contains the letter `p` anywhere in its name.

 And yes — `*p*` is exactly 3 characters long!
 ___________
 ### solution 
  - Try:
```bash
/challenge/run *p*
```
*But you have to cd into the directory first.*
- like that :
```bash
cd /challenge/files
```
