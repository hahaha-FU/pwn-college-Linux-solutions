### summary
**You want a pattern that matches only these 3 files — not more, not less**.

You must:

Use globbing (`*`, `?`, `[]`)

Keep the total pattern 6 characters or less

**Provide only 1 argument to `/challenge/run`**
_______________
When you start thinking about solving this challenge, it’s honestly one of the most fun things to look at — because at first, you assume that when you're using `*` and `[]`, the `[]` has to be between the asterisks. So you think the best you can do is just two letters, which feels impossible — because if you run ls -a and look at all the filenames, you'll notice that any two letters you pick are probably in a bunch of them.

That’s why it’s important to realize that you can actually put a `*` before the `[]` — and that’s totally fine. So you’re not stuck with just two characters — you actually get to use three.
And just like that — problem solved!
_______________
### solution 
```bash
cd /challenge/files
```
```bash
/challenge/run *[cep]*
```

the First letter of each word , [sticker.webm](https://github.com/user-attachments/assets/0973e836-3844-435b-8d51-42c36faf6f64)
