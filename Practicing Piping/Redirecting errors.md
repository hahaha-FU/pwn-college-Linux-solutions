### summary 
**Run /challenge/run and**:

- Redirect standard output (FD 1) → to a file called myflag
- Redirect standard error (FD 2) → to a file called instructions

**You're dealing with file descriptors**:

- 1> or just > means “standard output”
- 2> means “standard error”
_____________________
### solution
- Just run:
```bash
/challenge/run > myflag 2> instructions
```
- Normal output (the flag) goes into the file myflag
- Error output (the message/instructions) goes into instructions
```bash
cat myflag          # see the flag!
```
