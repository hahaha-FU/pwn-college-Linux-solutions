### summary 
- you’ll explore how tab completion works in Linux when there are multiple files starting with the same letters. Tab completion is a powerful feature that helps you quickly complete file names or commands by pressing the `<TAB>` key.
- **Example**
```bash
hacker@dojo:~$ ls
flag  flamingo  flowers

hacker@dojo:~$ cat f<TAB>
```
- When you press `<TAB>` once, the shell will auto-complete up to the point where it can't decide — in this case, it becomes `fl`.

- When you press `<TAB>` a second time, it will show you the available options
```bash
flamingo  flowers   flag
```
_______
### solution 
- Go to the directory:
```bash
cd /challenge/files
```
- Start typing:
```bash
cat /challenge/files/p<TAB><TAB>
```
- Look through the options and complete the correct file name.
- Run the full command to read the flag:
```bash
cat /challenge/files/pwncollege...  # use tab to complete
```
