### summary 
magine you have a piece of paper on your desk called `delete_me`, and someone tells you:
“Hey! This one’s trash — throw it away!”

In Linux, the command to delete a file is `rm`, which means: “Remove this file”.

So if you want to throw away `delete_me`, you just say:
```bash
rm delete_me
```
That’s it — paper gone, desk clean!
_________
### solution 
- List your files (just to be sure):
```bash
ls
```
*You should see a file named `delete_me`.*
- Delete it with:
```bash
rm delete_me
```
- Now run the check script:
```bash
/challenge/check
```
