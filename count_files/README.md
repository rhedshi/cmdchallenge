### count_files/

```bash
# Count the number of files in the current working directory. Print the number of files as a single integer.
(0)> ls -A | wc -l
```

```bash
# Count the number of files in the current working directory. Print the number of files as a single integer.
(0)> find . -maxdepth 1 -type f | wc -l
```
