### summary 
The `?` character in the shell means:

*“Match exactly one character.”*

So if you have a file called `file_a`, and you write `file_?`, it will match it.
But `file_??` will only match things like `file_cc` — two characters after the underscore.
______________
### solution
- Start from your home directory.
- Use cd to go to the /challenge directory.
- But this time — you must use the ? wildcard instead of the letters c and l in the word challenge.
  **So, you can’t write:**
```bash
cd /challenge
```
- But you can write:
```bash
cd /?ha??enge
```
**Let’s break it down:

`?` instead of `c`

`?` instead of first `l`**
`/challenge` becomes:
```bash
/?ha??enge
```
- Then run:
```bash
/challenge/run
```
