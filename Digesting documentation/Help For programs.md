### summary 
Sometimes, programs don’t have a man page at all 😮
But many still support a special option like:
```bash
--help
```
When you run a program with `--help`, it will usually print instructions on how to use it — like what arguments it supports.

Your goal is to do that with this program:
```bash
/challenge/challenge
```
________
### solution 
- Run this command to ask for help:
```bash
/challenge/challenge --help
```
- Read the output carefully — you're looking for an option that says something like:
```bash
--getflag    Print the flag and exit.
```
- Run the program again with that option:
```bash
/challenge/challenge --getflag
```
