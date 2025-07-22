### summary 
This time, the flag is hidden somewhere weird in the house. It’s not in your room, and you're not allowed to walk there <br>(you can't use `cd` to go to that folder).<br>
But someone told you exactly where it is — like giving you the full GPS address!

All you need to do is use `cat` and give it the full path to the file, and it will bring you the flag, no walking needed!

So imagine the flag is hiding at `/pwn/college/long/path/to/the/flag`.
_____________
### solution 
- Carefully read the message shown when the challenge starts.
- Look for the full absolute path to the flag
- Don’t use cd
- Example Solution:
```bash
cat /a/b/c/d/flag
```
