### split_on_a_char/

```bash
# The file split-me.txt contains a list of numbers separated by a ; character. Split the numbers on the ; character, one number per line.
(0)> tr ';' '\n' < split-me.txt
```

```bash
# The file split-me.txt contains a list of numbers separated by a ; character. Split the numbers on the ; character, one number per line.
(0)> sed 's/;/\n/g' split-me.txt
```
