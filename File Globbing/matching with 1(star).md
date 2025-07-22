### summary
The `*` is a wildcard character. It means:

"match anything in this part of the filename or path"

When you use it in a command, the shell replaces it with real file or folder names that match the pattern.

🧠 In this challenge:
You need to:

- Start from your home directory.
- Use `cd` to change into the `/challenge` directory.
- BUT — you’re not allowed to type more than 4 characters as the argument to cd.

😮 So you can’t do:
```bash
cd /challenge
```
…but you can do:
```bash
cd /ch*
```
Because `/ch*` will match `/challenge` using globbing.
__________
### solution 
- Use globbing to get into `/challenge` using a max of 4 characters:
```bash
cd /ch*
```
- Then run:
```bash
/challenge/run
```
