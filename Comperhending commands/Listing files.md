### summary 
Imagine you walk into a room (a **folder**) and you don’t know what’s inside.
You want to look around and see what’s there.

That’s what the command `ls` does.
It’s like asking: “Hey computer, what’s inside this folder?”

So if you say:
```bash
ls /challenge
```
The computer will show you **all the files** in that folder.

In this challenge, there’s a special file inside `/challenge`, but it’s given a random name — we don’t know what it is.

But once you list the contents with `ls`, you’ll **see the name**, and then you can use that name to do other things <br>(like run it with .`/name` or read it with `cat name`, depending on the challenge).
__________
### solution 
- Run:
```bash
ls /challenge
```
- Look at the output. It might show you something like:
```bask
hahaha-FU
```
*That’s the random name.*
- Now you know the name, you can do something with it in the next step (like maybe run it: .`/hahaha-FU`, or read it).
