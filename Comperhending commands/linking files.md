### summary
You have a magic machine:
```bash
/challenge/catflag
```
But the machine **isn’t looking at the real flag** — it's reading a **fake file** at:
```bash
/home/hacker/not-the-flag
```
Your job?
**Trick the machine** by **replacing** that fake file with a symlink (shortcut) to the **real flag** at `/flag`.

That way, when the machine opens `/home/hacker/not-the-flag`, it actually ends up reading the real flag from `/flag`! 🤫
__________
### solution 
- First, remove the fake `not-the-flag` file:
```bash
rm /home/hacker/not-the-flag
```
- Create a **symlink** from `/home/hacker/not-the-flag` to `/flag`:
```bash
ln -s /flag /home/hacker/not-the-flag
```
- Now, run the program:
```bash
/challenge/catflag
```
