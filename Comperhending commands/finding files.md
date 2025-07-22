### summary 
Imagine someone hid a toy called `flag` somewhere in a giant building. You don’t know where it is — it could be in a drawer, in a box, behind a door… 😮

But you have a magic scanner called `find` that lets you search everywhere for something with a specific name.

You just say:
```bash
find / -name flag
```
And it will go searching **everywhere** (starting from `/`) for anything named `flag`.

Just like in a real treasure hunt, there may be **fake flags** — so if you read one and it doesn’t look like the real thing<br> (it doesn’t start with `pwn.college`), just try the next one!

Also: some doors (folders) in the system are **locked**, and you might see errors like:
```bash
find: ‘/root’: Permission denied
```
*That’s totally fine — **just ignore** those. The real flag is in a place you can read*.
_________
### solution
- Run the `find` command to look for files named `flag`:
```bash
find / -name flag 
```
*The `2>/dev/null` part hides the permission errors to keep things clean*.
- You’ll get a list of paths like:
```bash
/usr/share/doc/somewhere/flag
/tmp/something/flag
/weird/place/flag
```
- Try reading each one with cat:
```bash
cat /tmp/something/flag
```
- When you find one that starts with:
```bash
pwn.college{flag_is_here}
```
