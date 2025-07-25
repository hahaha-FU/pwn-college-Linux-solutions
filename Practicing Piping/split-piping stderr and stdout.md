### Summary
You have one command:
 `/challenge/hack` — it prints two things:

- One to **stdout** (normal output)

- One to **stderr** (errors or messages)

Your goal is to:

Send stdout to `/challenge/planet` 

Send stderr to `/challenge/the` 

But be careful! If you use `2>&1`, it mixes them together — and we don’t want that.

Instead, you’ll use:

- `|` for stdout

- `2>` to redirect stderr

- `>(...)` to redirect to a command instead of a file
____________
### Solution
`/challenge/hack 2> >( /challenge/the ) | /challenge/planet`
____________
- `2>` `>(command)` sends stderr to a command.

- `|` command sends stdout to a command.

- You’re splitting the output before it mixes.

 *Think of it like:*

"Split the road! Errors go right → `/challenge/the`,<br>
Output goes left → `/challenge/planet`"


