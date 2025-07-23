### summary 
| Symbol | Meaning                            | Behavior                        |
| ------ | ---------------------------------- | ------------------------------- |
| `>`    | Output redirection (overwrite)     | Deletes old content, writes new |
| `>>`   | Append output redirection (append) | Keeps old content, adds new     |

**You have a program:**
```bash
/challenge/run
```
This program outputs the flag in two parts:

  - First half is written immediately.

  - Second half is written after it checks if you're redirecting properly.

__________________
### solution 
Run the program twice, using >> to append the second half without deleting the first part:
```bash
/challenge/run >> /home/hacker/the-flag
```
```bash
cat /home/hacker/the-flag
```
*Tip* :
- If you used >>, you'll see both halves of the flag together.
- If you mistakenly used >, only the second half will be there, and the flag won't work.
