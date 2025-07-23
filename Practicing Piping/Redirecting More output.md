### summary
In Linux, commands can speak in two voices:

   - **Standard Output (stdout)** → normal output (what you usually see).

   - **Standard Error (stderr)** → error messages or special feedback.

The redirection `>` only catches **stdout** — it doesn’t affect stderr
_____________
### solution 
- Run the command `/challenge/run`, but instead of printing the flag on your screen, you need to redirect it into a file called `myflag`.
```bash
/challenge/run > myflag
```
- This puts the flag (which is printed via stdout) into the file `myflag`.

- You’ll still see **some messages** printed on your terminal — those are from **stderr**, and that’s expected.
```bash
cat myflag
```
