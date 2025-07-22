### summary
Sometimes you want to exclude files when using globbing patterns. Luckily, Bash supports that using `[]` with `!` or `^`.

If the **first character** inside the brackets is a `!` or `^`, the pattern becomes **inverted**, meaning:

Match files whose character is not listed inside the brackets.

- `file_[!ab]` and `file_[^ab]` both match files not starting with `a` or `b`.

- `!` works in most Bash versions.

- `^` is safer in new Bash, but might not work in older ones.

  -**Use a glob pattern like**:
  ```bash
  [!pwn]*
  ```
  This means:

   - Match all files that don’t start with `p`, `w`, or `n`.

The `*` at the end is important — it tells the shell to match the rest of the filename, whatever it is.
_____
### solution 
```bash
cd /challenge/files
/challenge/run [!pwn]*
```
- **Or, if `!` gives problems on your shell, try**:
```bash
/challenge/run [^pwn]*
```
___________
### **⚠️ Notes**
- `!` must be the first character inside the brackets.
- `^` is more consistent in modern shells.
- The `*` is required to match the rest of the filename.

