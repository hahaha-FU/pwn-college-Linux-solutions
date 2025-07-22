Imagine you’re in a room, and someone tells you,
“Hey! I want you to put two empty sheets of paper on the table. One called `pwn`, and one called `college`.”

You don’t have to write anything on them — just create them.

In Linux, we do this using the magic word: `touch`<br>
It’s like saying: “Poof! Make a blank file with this name.”
_______
### solution 
- Create the first file:
```bash
touch /tmp/pwn
```
- Create the second file:
```bash
touch /tmp/college
```
- Now run the challenge script to get the flag:
```bash
/challenge/run
```
