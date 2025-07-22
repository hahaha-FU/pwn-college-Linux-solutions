### summary
You’ve been given a program:
```bash
/challenge/challenge
```
But it doesn’t tell you how to use it.

😕 What do you do?

🧠 Use the `man` command! It shows you the   **manual** (help page) for any Linux command, including custom ones like this challenge.
The manual might show:

- What the command does
- What options (like `--help`, `--something`) it supports
- Which one gives you the flag
________
### solution 
- Run the `man` command on the challenge:
```bash
man /challenge/challenge
```
- Use the arrow keys or PgUp/PgDn to scroll.
-Look in the "DESCRIPTION" or "OPTIONS" section.
-When you see something like:
```bash
--showmetheflag   Print the flag and exit.
```
- Exit the manual (press `q` on your keyboard).
- Then run the command with the secret option:
```bash
/challenge/challenge --showmetheflag
```
