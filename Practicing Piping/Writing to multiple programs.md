### Summary
You want to run this command:
 `/challenge/hack` — it prints something.

But instead of sending its output to one place, you want to send it to TWO other commands:

- `/challenge/the`
- `/challenge/planet`

It's like taking one stream of water and splitting it into two pipes! 

To do this, we use:

- `tee` to duplicate
- `>(...)` to send output to commands instead of files
_________________
###  Solution
`/challenge/hack | tee >( /challenge/the ) | /challenge/planet`
______________
- `>(command)` is called process substitution — it acts like a file, but it's actually connected to a running command.
  
- So:
`tee >( /challenge/the )` sends a copy of the output to `/challenge/the`,
and also passes it forward to `/challenge/planet`.

- It’s like saying:

“Hey, bash! Send my data to `/challenge/the`, and also to `/challenge/planet!`”
