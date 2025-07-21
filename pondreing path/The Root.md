### Challenge Summary:
- This challenge introduces the idea of absolute paths in a Unix-like filesystem.<br>
- An absolute path starts from the `root directory /`and defines the complete location of a file or program in the filesystem.

In this case, a program named `pwn` has been placed directly under the root directory `/`, and you must run it using its full path to get the flag.

**Hint** :<br>
- Absolute paths start with `/`.
- The program is located at `/pwn`.
- You don’t need to navigate — just run the program directly by giving the full path.

### Solution:
Simply run the following command in the terminal:
```bash
/pwn
```
- This will execute the pwn program and print the flag.

### Extra Tip:
- Use `ls  `to explore what exists in the root directory.
