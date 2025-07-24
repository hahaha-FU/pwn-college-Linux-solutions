### summary 
You have a command:
```bash
/challenge/run
```
But it **doesn’t take a typed input**, it reads input from a file, which you will send using the `<` operator.

The program wants to read the word `COLLEGE` from a file called `PWN`.
__________
### soluion 
- Create the file `PWN` with the word `COLLEGE`:
```bash
echo COLLEGE > PWN
```
- Redirect the file as input into /challenge/run:
```bash
/challenge/run < PWN
```
