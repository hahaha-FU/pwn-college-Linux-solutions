### Challenge Summary:
Imagine your computer is a big house 🏠, and inside this house are rooms (called folders or directories). Each room can have things inside it, like toys (files) or even more rooms.

Now, when you want to go get a toy (run a program), there are two ways you can describe where it is:

### 1. Absolute Path (The full path):
This is like saying:
"I will go from the front door, then to this room, then this one, and then I’ll get the toy."

🛣️ Like this:
```bash
/challenge/run
```
You’re starting from the root `/` (the front door) and going step by step.
_________________
## 2. Relative Path (The shortcut from where you're standing):
This is like saying:
"I'm already inside the house. From where I am now, I’ll just walk to the toy."

So if you're already standing in the main hallway (which is /), and the toy is in the "challenge" room, you'd just say
```bash
challenge/run
```
You're skipping the front door because you're already inside!

### solution : <br>
- First, go to the main hallway (which is the root `/`):
```bash
  cd /
```
- Now, you're standing at `/` — just like being in the front hallway of your house.
- Then, run the program using the shortcut path:
```bash
challenge/run
```
*Ta-da! 🎉* 
```bash
pwn.college{flag_is_here}
```


  
