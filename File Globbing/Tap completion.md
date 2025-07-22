### summary 
Using `*` to match filenames is powerful, but also dangerous — especially with commands like `rm`.<br> One wrong match, and... goodbye files! 😱

That’s why tab completion is a safer and smarter choice when targeting specific files
- **In this challenge**:

- There's a file in /challenge/ that holds the flag.
- You can see it using ls, but…
- You can’t type its name manually — it's got some sneaky characters or formatting!
- You must use tab completion to auto-complete the filename.
__________
### solution 
```bash
cat /challenge/pwn[TAB]
```
**👉 Hit the `Tab` key after typing `pwn` and let Bash complete the filename for you.**
