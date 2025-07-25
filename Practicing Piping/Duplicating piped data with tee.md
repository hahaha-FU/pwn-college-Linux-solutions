### Summary
You’re connecting two commands together:
 `/challenge/pwn` → `/challenge/college`

But what if something goes wrong and you don’t see the data?<br>
You want to peek at what’s flowing between them. <br>

That’s where `tee` comes in!<br>
**It copies the data so you can see it AND pass it along.**
__________
### Solution
`/challenge/pwn | tee seen.txt | /challenge/college`
__________
- `tee` makes a copy of the data into a file (like a T-pipe 💧).
- You can read `seen.txt` to debug what's flowing between commands.
