### summary 
The command `/challenge/run` gives you lots of flags, but most of them are fake! 😱
The fake ones all have the word `DECOY` in them.
Only one flag is real — and it does not have `DECOY`.
________
### solution 
`/challenge/run | grep -v DECOY`
_________
- `grep -v` means: “show me the lines that do NOT match”
- So `grep -v DECOY` removes every line with `DECOY`
