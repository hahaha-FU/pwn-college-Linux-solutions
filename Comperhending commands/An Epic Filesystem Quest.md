### summary 
You’re starting at the front door of a big castle (which is /, the root folder).
Somewhere inside, the flag is hidden, and to find it, you have to follow notes (clues) left for you.

You’ll use:

- `cd` to go into rooms (folders)
- `ls` to look around
- `cat` to read the notes (files like `CLUE`, `HINT`, etc.)

It’s like a game of hide and seek, but with commands!
______________
### solution 
- Go to the root directory (you may already be there, but just to be sure):
```bash
cd /
```
- List all files and folders to look for your first clue:
```bash
ls
```
- Look for a clue file, like:
**`HINT`**
**`CLUE`**
**`README`**
**or anything that stands out**
- Read the clue using:
```bash
cat HINT
```
*(Replace **`HINT`** with whatever the file is actually named)*
- The clue might say something like:

  **|** Go to `/opt/mystery`

- Go there using cd:
```bash
cd /opt/mystery
```
**Repeat**:

- Use `ls` to look around
- Use `cat` to read the next clue
- Follow the trail until you find the file that **contains the flag** (it will probably be named something obvious, or you'll just<br> `cat` it and see it starts with `pwn.college`
