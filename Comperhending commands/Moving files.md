### summary 
Imagine you have a toy (file) called `/flag`, and it’s sitting in one room.
Someone tells you:
“Take that toy and put it into a new box called `/tmp/hack-the-planet`.”

To move stuff in Linux, you use a command called `mv`.
It’s like saying: “**Move this from here to there**.”

So you're just moving the file from its current spot to a new one.
___________
### solution 
- Move the file `/flag` into `/tmp/hack-the-planet`
```bash
mv /flag /tmp/hack-the-planet
```
- Now run the check script to get your flag:
```bash
/challenge/check
```
