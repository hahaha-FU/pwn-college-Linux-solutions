### summary 
This time, the command prints the flag — but not in the usual place.
It prints it in the error stream (called `stderr`) instead of normal output (`stdout`). 😮

The problem?
`| grep FLAG` only sees normal output, not errors.
So we need to merge the errors with the output first!
__________
### solution 
`/challenge/run 2>&1 | grep FLAG`
__________
- `2>&1` means: “send errors (`stderr`) into the normal output (`stdout`)”.

- ` grep FLAG` means: “search for FLAG in whatever is coming out”.

- So now both output and errors go to `grep`.

🧠 **Think of it like:**

Combine both pipes into one, then filter!

