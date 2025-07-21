### summary
You're still in your Linux house 🏠.
But now we’re learning about two secret doors that exist in every room:
| Symbol | What it means                            |
| ------ | ---------------------------------------- |
| `.`    | 🎯 "Stay in the same room — don’t move!" |
| `..`   | 🔙 "Go back to the room you came from!"  |

### solution 
You're still trying to run the program `/challenge/run...` but this time, you need to use `.` in the path.<br>
That means : you’ll pretend to move, but really just stay in place
- Go to the root `/` (the house entrance):
```bash
cd /
```
- Now run the challenge using a path that includes .. For example:
```bash
./challenge/run
```
That means: "from where I’m standing (which is `/`), go to the challenge room, and run the run program".
___________
### All of these would work the same: 
```bash
./challenge/run
././challenge/run
././././challenge/./run
```
Because `.` just means "stay where I am", they all lead to the same place!
