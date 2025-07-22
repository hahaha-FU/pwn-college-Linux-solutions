### summary 
You’re given a program:
```bash
/challenge/challenge
```
And according to its documentation, this program lets you **print the content of any file** to the terminal — but only if you give it the correct argument.

The special argument is:
```bash
--printfile
```
But here’s the catch:
`--printfile` **also needs its own argument — the **path of the file** you want to print.

So it works like this:
```bash
/challenge/challenge --printfile <path-to-file>
```
📄 Example from the docs:
```bash
/challenge/challenge --printfile /challenge/DESCRIPTION.md
```
This will print the contents of `DESCRIPTION.md`.
_____________
### solution 
- Run the program with the `--printfile` argument and give it `/flag` as its value:
```bash
/challenge/challenge --printfile /flag
```

