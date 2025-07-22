### summary 
Imagine you’re in a room full of toys (files). Some toys are **hiding under a blanket** — they’re still there, but you can’t see them normally.

In Linux, files that start with a dot (like `.secret`) are hidden — and `ls` doesn’t show them unless you say,
“Hey, show me everything, even the hidden stuff!”

To do that, you use:
```bash
ls -a
```
The `-a` means: “All files, please — even the secret ones.”

In this challenge, the flag is hidden in the root folder `/`, and its name starts with a dot (like `.something`), so it's invisible unless you use `-a`.
_______
### solution
- List everything in the root directory, including hidden files:
```bash
ls -a /
```
- Look for a file that starts with a dot (`.`), like `.flag_hidden`.
- When you find it, use `cat` to read it:
```bash
cat /.flag_hidden
```
*(Replace .flag_hidden with the actual filename you see!)*
