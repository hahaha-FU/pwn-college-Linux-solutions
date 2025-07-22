### summary
**You learned**:
  - `file_[ab]` matches `file_a`, `file_b`
  - `file_[absh]` matches `file_a`, `file_b`, `file_s`, `file_h`
 
*Now, you’ll do the same thing, but this time:*
  - Use the full path
  - And do not change directory — stay in `~` (your home)
__________
### solution 
- Run:
```bash
/challenge/run <pattern>
```
- From your home directory, where `<pattern>` is:
```bash
/challenge/files/file_[absh]
```
That will expand into:

- `/challenge/files/file_a`
- `/challenge/files/file_b`
- `/challenge/files/file_s`
- `/challenge/files/file_h`
