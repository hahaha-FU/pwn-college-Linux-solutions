### summary
You’re the hacker user, and your room (home directory) is `/home/hacker`.
Linux gives you a shortcut to this room called `~` (tilde). It's like a nickname!

So:
- `~` = `/home/hacker`

- ~`/file.txt` = `/home/hacker/file.txt`

And now here's the challenge:
You need to run a program 
```bash
/challenge/run
```
But this time, you give it a filename as an argument — a place to save the flag.
BUT — it has to follow some rules!

🚦 Rules:
The path must be absolute (start with `/`).

The file must be inside your home (`/home/hacker`).

The path you give must be 3 characters or less before expansion — like `~(any character )`

### solution 
- Pick any one-character name (like `x)`, and run:
```bash
/challenge/run ~/x
```
- To Read the Flag:
```bash
cat ~/x
```
