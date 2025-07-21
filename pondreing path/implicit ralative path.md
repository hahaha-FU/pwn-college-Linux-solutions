### sunnary 
You’re in the /challenge room, and you want to use a toy (program) called `run` that’s sitting right there in the room with you.
So you try saying:
```bash
run
```
But Linux says ❌:

*"I don’t know what that is."*

Why?? 😱<br>

Because Linux doesn’t automatically look in your room for programs. It only checks special rooms called the `PATH`. That’s for safety, so you don’t accidentally run something bad that’s hiding in your current room.

**The Trick You Need :**<br>
You have to point directly at the toy and say:
```bash
./run
```
That means :<br>
"Hey Linux, run the run file that’s right here (.) in my current room!"

### solution
- Go to the right directory
-  make sure you're in /challenge
-  Run the program using ./
```bash
cd /challenge
pwd
./run
```


