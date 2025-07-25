### Summary
Last time, you saved all the words into a file, then searched the file.
This time, we skip the saving part! 

Instead, we connect two commands together using a pipe |.

 `/challenge/run` prints a lot of text.
 `grep FLAG` looks for the flag.
You will connect them so the flag goes straight into grep.
____________
###  Solution
`/challenge/run | grep -o '[a-zA-Z0-9_]\+{[^}]*}' /tmp/data.txt `
____________
- `|` is called a pipe — it sends the output of one command into another.
- Think of it like a water pipe: 🪠<br>
First command = fills the water
