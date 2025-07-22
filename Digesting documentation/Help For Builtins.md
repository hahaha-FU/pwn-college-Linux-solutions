### summary 
Normally, you use:
```bash
man some_command
```
…or:
```bash
some_command --help
```
But now you’re dealing with something different:

👉 The command `/challenge/challenge` is actually a shell builtin — that means it’s built into the shell, not a separate program.

🧠 Builtins don’t use man pages or `--help`.

Instead, you use the special command
```bash
help
```
______
### solution 
- Try listing all shell builtins:
```bash
help
```
- Then ask for help on the specific one — this challenge command:
```bash
help challenge
```
- Read the output — look for a secret argument or keyword it accepts, like:
```bash
challenge: challenge [--flag]
```
- Run the builtin with that argument:
```bash
challenge --flag
```

