### summary 
Last time, you read a file called `flag` because it was in your room (your home folder).
But sometimes the file is not in your room. It’s somewhere else — far away — but you still know its full address.

That full address is called an absolute path.
So instead of just saying `flag`, you say:

“Go to the exact address: `/flag` and read it.”

You still use the same command: `cat`, but this time with the full path of the file
___________
### solution 
- Make sure you're in the terminal.
- Type this command to read the flag using its absolute path:
```bash
cat /flag
```
That’s it! 🎉<br>
This command will print the flag — even though it’s not in your home folder, because you told cat exactly where to find it.
