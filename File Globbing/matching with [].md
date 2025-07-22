### summary 
In shell commands, `[]` means:

“Match one character, and it has to be one of the characters you put inside the brackets.”

For example:
```bash
file_[ab]
```
This matches:

- `file_a`
- `file_b`
- But not `file_c`, `file_d`, etc.
_____________
### solution
- **Go to the directory:**
```bash
cd /challenge/files
```
- Use `globbing with []` to match these specific files:

- file_a
- file_b
- file_s
- file_h
*You need to call:*
```bash
/challenge/run <pattern>
```
Where `<pattern>` is something that matches all those files.

The pattern you want is:
```bash
file_[absh]
```
 - **This matches** :

- file_a
- file_b
- file_s
- file_h
