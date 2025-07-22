### summary 
Imagine you have a really, really big book — like 100,000 pages!
You don’t want to read the whole thing just to find one special word.

That’s where a superhero comes in: grep!
grep is like a magic tool that says:
“Tell me what word you're looking for, and I’ll go find all the lines that have it!”

In this challenge, you’re looking for the flag. The flag always starts with:
```bash
pwn.college
```
___________
### solution 
- So instead of reading all 100,000 lines, you just say:
```bash
grep pwn.college /challenge/data.txt
```

